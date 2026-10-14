---
name: starcraft-tmg-cost-tables
description: Read the latest StarCraft Tabletop Miniatures Game "Units and Upgrade Points" cost-table PDF (starcraft-tmg-cost-table-[month].[year].pdf) and create or update a Markdown file of units, upgrades, and tactical/creep cards by faction. Use when the user asks to read, refresh, or update StarCraft TMG point or cost data from the PDF.
---

# StarCraft TMG Cost Tables

Turns the official cost-table PDF into one Markdown data file. Output must be accurate: leave a field blank or flag it rather than guess.

## 1. Find the latest PDF

- Look in the uploads folder and the connected folder for files matching `starcraft-tmg-cost-table-*.pdf`. Use Glob with that pattern.
- Parse the `[month].[year]` part of each filename. If the month is a name (e.g. `october`), order by calendar month. If it is numeric (e.g. `10`), order numerically. Pick the highest year, then the highest month.
- If the month part does not match either form, or two files tie, ask the user which file to use. Do not guess.
- Tell the user which file was selected and why.

## 2. Read the PDF

- The text layer is readable. Read the PDF directly and do not switch to page images unless a value is missing or ambiguous.
- Read in page order. Pages are headed by faction (Terran, Zerg, Protoss), with unit tables first and tactical card tables after.
- Ignore colour markers (green = point drop, red = point increase). They are not data.

## 3. Parse the data

**Units.** Each unit has a name and three stats, each with a Small and a Large value:
- Models
- Supply Value
- Mineral Cost

If a unit has no large option, the Large column holds `-`. Record `-` as-is. Do not invent a value.

**Upgrades.** A unit may have an upgrade section (not every unit does). Each upgrade has:
- Name
- Notes
- Small cost
- Large cost

Notes may be empty (`-`). An arrow (↑) in the Notes column means **"Replacement for X"**. Write it that way in the output (e.g. `Replacement for Strike`). Keep other Notes text as printed, such as `SPECIALIST`.

**Tactical cards.** These follow each faction's units. Each has a name and a Vespene Gas Cost. Creep cards appear as a separate table under Zerg and use the same columns.

## 4. Write the output

- Filename: `starcraft-tmg-cost-table-[month].[year].md`, matching the source PDF.
- Date: write the cover date as day, month name, year (e.g. `9 October 2026`). The cover date is day.month.year. Do not reformat the source filename's month.
- Structure: one section per faction, in the order Terran, Zerg, Protoss.
  - Under each faction: units (each with a Small/Large stats table), then upgrades in a table under their unit, then tactical cards, then creep cards (Zerg only).
- Use `-` for absent values. Leave a cell blank only if the PDF itself has no value and the table requires one. Flag the cell rather than fill it.

## 5. Verify before finishing

1. Count units, upgrades, and tactical cards per faction in the PDF.
2. Count the same in the MD. The numbers must match.
3. Re-read the MD and spot-check at least five values per faction (supply, mineral cost, and upgrade costs), comparing against the PDF.
4. Check every "Replacement for" entry against the arrow in the PDF.
5. Report the result: the source file used, the output file, and the counts. Flag any item you could not verify.

## Guardrails

- Do not infer values the PDF does not show.
- Do not compare across faction or page boundaries to fill gaps.
- If the PDF text is garbled or a table cannot be parsed, say so and ask whether to read the page image.
- If no matching PDF is found, say so and ask the user to upload it or place it in the connected folder.
