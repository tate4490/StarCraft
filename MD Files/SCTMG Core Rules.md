# StarCraft: Tabletop Miniature Game: Core Rules Book

> Converted from *StarCraft-TMG_EN.pdf* (Core Rules Book, 2026 edition). Text was taken from the PDF's text layer, so the layout is simplified. Unit and tactical card costs (Parts 12.10 to 12.12) come from the Cost Table file, not this rulebook. Map layouts in the appendix are diagrams and are not transcribed.

## Contents

- Dedication, Credits, and Table of Contents
- **The Nature of the Game**
- **Part 1: Learn to Play**: Worked Example: Starting Rounds
- **Part 2: Core Concepts**: Models, Units, Bases, Tags, Player Roles, Keywords and Rule Priority, Ability Types
- **Part 3: Dice and Rolling**
- **Part 4: Measuring and Movement**
- **Part 5: Cards and Characteristics**
- **Part 6: The Supply System**
- **Part 7: The Battlefield**
- **Part 8: The Game Sequence**
- **Part 9: Preparing for Battle**
- **Part 10: Advanced Rules**
- **Part 11: Keyword Glossary and Definitions**
- **Part 12: Quick Reference**
- Index and Map Layouts

---

## The Nature of the Game

Each player is the general of an army. Before the game begins, you build that army by spending resources to recruit Units of Archon Studio miniatures, then wage war against your opponent.

These rules are designed to capture the feel of StarCraft: the reaction-based gameplay, the distinct asymmetry between Terran, Zerg, and Protoss, and the tension of holding a line or breaking through one. Whether you're playing a casual game with friends or competing at a tournament, everything here serves that goal.

> **Note:** Some words appear in **bold** in the rules. These are key phrases and terms used consistently throughout the rules.

---

## Part 1: Learn to Play

Moved to its own file: **MD Files/SCTMG Worked Example.md** in the GitHub repository. The file is a verbatim copy of source pages 5 to 28.

---

## Part 2: Core Concepts

Moved to **MD Files/SCTMG Core Concepts.md**.

---

## Part 3: Dice and Rolling

Moved to **MD Files/SCTMG Dice and Rolling.md**.

---

## Part 4: Measuring and Movement

### 4.1 Measuring Distances

All distances are measured in inches (") using a tape measure or ruler. Players may measure any distance at any time, including before declaring an action and between Phases.

- **Between Models:** Measure from the nearest point of one model's base to the nearest point of the other model's base.
- **Ignore Overhang:** Weapons, wings, limbs, and scenic elements extending beyond the base rim are ignored.
- **Base-to-Base Contact:** If two bases are touching, the distance is 0".
- **Tokens and Markers:** Measure to the nearest physical edge.
- **Elevation:** When calculating distances between models at different elevations, always measure horizontally from a top-down perspective. The vertical height difference is not included. This applies to Range, Engagement Range, and ability ranges. Movement distances are measured as specified by the action (Part 8.5.3).

### 4.2 Within vs. Wholly Within

- **Within:** A model is Within a distance if any part of its base touches or crosses into that range. A Unit is Within a distance if at least one model's base touches or crosses into it.
- **Wholly Within:** A model is Wholly Within a distance only if its entire base sits inside that range. A Unit is Wholly Within only if every model's base satisfies this condition.

> **Example:** A Zergling whose entire base sits inside a 3" range is Wholly Within 3". A Zergling that is partly inside is Within 3". A Unit with one model Within and another model not Wholly Within is Within 3" but not Wholly Within 3".

### 4.3 The Leading Model

The **Leading Model** is a temporary reference point used to execute a Unit's movement. Whenever a Unit resolves a Move, Deploy, Run, Charge, Disengage, or Close Ranks action, or any other action that instructs the Unit to nominate a Leading Model, the controlling player selects one model.

Move the Leading Model first, measuring its exact path. Then set the remaining models in valid Coherency around its new position. The Leading Model nomination ends once the action resolves.

### 4.4 Unit Coherency

Coherency is checked at the end of any action that repositions models: Move, Deploy, Charge, Disengage, Close Ranks, Run, PLACE, and SUMMON.

- At the end of such an action, all models must be Wholly Within 3" of the Leading Model and able to trace a valid **Coherency Link** to it. If this is met, the Unit is **In Coherency**.
- If terrain or crowding prevents a model from reaching a legal position, set it as close as possible to the Leading Model while maintaining a valid Coherency Link. A Unit with one or more models beyond 3" is **Out of Coherency**.
- If a model cannot be set in any legal position while maintaining a valid Coherency Link, it is removed as a casualty immediately.
- A Unit that is In Coherency remains so until its next repositioning action. Casualties never trigger a Coherency check.
- While In Coherency, a Unit may control and contest Mission Markers normally (Part 8.9.1).

**Coherency Link:** A chain of imaginary lines drawn model-to-model through models of the same Unit. Links cannot pass through models from other Units, terrain, or gaps that the Leading Model itself could not move through. A link may pass through Enemy models the Unit is Engaged with, and through ACCESS POINTS.

**Flying Units and Coherency Links:** Ignore terrain. Links may pass freely through terrain of any Size and through models from other Units.

**Out of Coherency:** Out of Coherency Units cannot control or contest Mission Markers (Part 8.9.1).

> **Example:** A Unit of Marines in Coherency has all models Wholly Within 3" of the Leading Model, with links drawn to the Leading Model. A Marine behind a wall cannot draw a link without passing through restricted terrain, so that placement is illegal.

### 4.5 Directly Towards and Directly Away

Some abilities force a Unit to move **DIRECTLY TOWARDS** or **DIRECTLY AWAY** from another Unit. Draw a straight line from the centre of the acting model's base through the centre of the target model's base. The affected model follows this line.

- If terrain or another model blocks the path, the model bypasses it by the shortest route, then continues in the original direction. If two routes are equally short, the controlling player chooses.
- A model moving DIRECTLY TOWARDS cannot end further from the target than it started.
- A model moving DIRECTLY AWAY cannot end closer to the target than it started.
- **Multi-model Units moving DIRECTLY TOWARDS:** The Leading Model must be the one with the shortest route. Move it first, then set the remaining models as close to the target as possible while maintaining Coherency.
- **Multi-model Units moving DIRECTLY AWAY:** The Leading Model must be the one with the shortest route. Move it first, then set the remaining models as far from the target as possible while maintaining Coherency.
- If a model is forced off the battlefield edge by an involuntary movement effect, it stops at the edge.

### 4.6 Gap Clearance and Model Size

A **gap** is any physical space between terrain pieces or models through which a model's path passes.

- **Size 2 or lower:** May pass through gaps at least 1" wide.
- **Size 3 or larger:** Requires a gap at least 3" wide.
- Regardless of clearance, a model cannot be set where its base does not physically fit. Clearance governs movement through a space, not stopping inside one.
- Openings in terrain (archways, doorways, breaches) are treated as gaps for Gap Clearance, even if the surrounding terrain is Size 2 or larger. Players should agree which openings are passable during Battlefield Setup.
- This applies to Move, Run, Charge, Disengage, and Close Ranks.
- **Flying Units** ignore Gap Clearance. Their Leading Model moves point-to-point, but must end in a legal position where its base fits without overlapping another base or terrain.

---

## Part 5: Cards and Characteristics

### 5.1 Unit Cards

Every Unit has a Unit Card with the information needed to use it.

1. **Unit Name.**
2. **Speed:** The maximum distance in inches the Leading Model may traverse in a standard Move.
   - **Split Values (e.g., 4"/7"):** Use the second value only when the Unit is reduced to a single remaining model, or when it started with a single model.
   - **Null Value (-):** The Unit cannot move or be repositioned by any means, including PLACE and involuntary movement.
3. **Armour:** The Target Number the defender must meet or exceed on a D6 to cancel a hit.
4. **Evade:** A secondary defensive characteristic. Used only when a rule or condition specifically grants an Evade Roll. A Null Value (-) means the Unit cannot make Evade Rolls, and no ability that grants an Evade Roll overrides this.
5. **Hit Points (HP):** Damage a single model must sustain before it is removed.
6. **Shield (Optional):** If present, add it to the HP of the first model. The Unit is **Shielded**. It loses Shielded Status when the Total Damage assigned to it exceeds its Shield value, or when the first model is removed. Losing Shielded Status does not remove remaining HP. Shielded Status cannot be restored by HEAL.
7. **Size:** The model's vertical height category, used for Line of Sight and terrain interaction.
8. **Supply Profile:** Links the number of remaining models to the Unit's Current Supply Value. Update immediately when casualties reduce the model count to a lower bracket.
9. **Phase Boxes:** Special Abilities and weapon profiles available during specific Phases.
10. **Weapon Profiles:** Each weapon is assigned to either the Assault Phase or the Combat Phase, and may be used only during that Phase. Each profile lists:
    - **[RNG] Range:** Maximum effective distance. Melee weapons list E (Engagement Range). Some template weapons list FT.
    - **Target:** Ground (Ground Units only), Flying (Flying Units only), or All.
    - **[RoA] Rate of Attack:** Dice rolled per firing model.
    - **Hit:** Target Number on a D6 to score a hit.
    - **Surge Type:** The Combat Tag that triggers the weapon's Surge efficiency.
    - **S Dice:** Die type for Surge results (D3 or D6).
    - **[DMG] Damage:** Damage inflicted per die in the Damage Pool.
    - **Keyword:** Special rules on the weapon (e.g., PIERCE, SIDEARM).
11. **Combat Tags.**
12. **Faction Tag.**

### 5.2 Special Rules and Upgrades

The reverse of each Unit Card lists optional Upgrades available during Army Building.

13. **Upgrade:** New abilities or weapons added to the profile.
14. **Replacements (FOR):** An entry showing "FOR [Weapon Name]" means the new weapon replaces the original entirely.
15. **Combat Range:** The preferred distance this Unit seeks to maintain from Enemy Units.
16. **Army Slot:** The slot type (Core, Elite, Support, Air, or Hero) required to field this Unit. A Unit occupies a number of slots equal to its starting Supply Value (Part 9.1.6).
17. **Flavour Text** describing the Unit's role.
18. **Base Diameter** on which the model must be mounted.

### 5.3 Tactical Cards

Tactical Cards are the strategic resources, orders, and doctrines a commander has available, bought before the battle with Vespene Gas and deployed when needed.

1. **Name.**
2. **Unique Marking:** If present, only one copy may be included in an army.
3. **Faction Tags:** The Race Tag and any Sub-Faction Tags that determine which armies may include this card (Part 9.1.2).
4. **Army Slots:** The organisation slots unlocked when this card is included (e.g., 2x Core, 1x Support). These are in addition to those provided by the Faction Card.
5. **Resource Type and Value:** The faction's resource (CP for Terran, BM for Zerg, PE for Protoss) and the amount generated when this card is Exhausted instead of using its Special Ability.
6. **Special Abilities:** One or more Active, Passive, or Reaction Abilities (Parts 10.1–10.4).

### 5.4 Faction Cards

The Faction Card is the foundation of every army. Every army must include exactly one, selected during Army Building.

1. **Faction Name:** May also function as a keyword referenced by other rules.
2. **Faction Tags:** The Race Tag and any Sub-Faction Tags that specify which Units and Tactical Cards can be included (Part 9.1.2).
3. **Starting Army Slots:** Provided by the Faction Card itself (e.g., 3x Core, 1x Hero, 2x Support). Additional slots are unlocked by purchasing Tactical Cards.
4. **Resource Type and Value:** As for Tactical Cards.
5. **Special Abilities:** As for Tactical Cards.

### 5.5 Mission Cards

Mission Cards decide what the conflict is about, how long the battle lasts, and what must be achieved to win. Missions are chosen during the Draft (Part 9.2).

1. **Name.**
2. **Engagement Scale:** Skirmish, Standard, or Grand Offensive.
3. **Starting Supply:** The Supply Pool available to each player in Round 1.
4. **Supply Escalation:** The amount the Supply Pool increases at the start of each subsequent Round.
5. **Game Length:** The number of Rounds before the game ends (usually 5).
6. **Mission Parameters:** Setup instructions, Mission Marker states, and special conditions from the start of the game.
7. **Scoring Conditions:** How players earn Victory Points at the end of each Round.
8. **Additional Conditions:** Special rules or winning conditions, including instant victory triggers.

### 5.6 Deployment Cards

Deployment Cards determine the war's geometry, entry points, restricted zones, and the ground that must be taken. They are selected during the Draft.

1. **Name.**
2. **Engagement Scale.**
3. **Battlefield Dimensions:** The required table size.
4. **Entry Edges:** The table edges assigned to each player. Units enter from their Entry Edge when deploying from Reserves.
5. **Zone of Influence:** A restricted area extending 6" inward from each player's Entry Edge. Enemy Units arriving from Reserves cannot end their deployment within this area. It does not affect Units already on the battlefield.
6. **Marker Coordinates:** Precise positions for each numbered Mission Marker.

**Using the Deployment Card during Setup:** Confirm the table dimensions, assign Entry Edges, set Zone of Influence Markers at the corners of each player's Entry Edge where applicable, then set Mission Markers at the listed coordinates. See Part 9.3.

---

## Part 6: The Supply System

Armies do not deploy at full strength. Reinforcements arrive in waves, and as Units take casualties, their ability to deploy shrinks. Supply governs when and how many Units a player can field.

### 6.1 The Supply Profile

Every Unit Card includes a Supply Profile in the top-right corner. As casualties reduce the model count into a lower bracket, the Current Supply Value updates immediately.

> **Example:** A squad of 9 Marines has Supply 2. A squad of 6 Marines has Supply 1. Reduced to 3 models, Supply drops to 0.

### 6.2 How Supply Is Used

**Deployment.** Each mission establishes a **Supply Pool**, the maximum Supply that can be on the battlefield at one time. It starts at the Mission Card's Starting Supply and increases by the Supply Escalation each Round.

- A player may set a Unit in play from Reserves only if the Unit's Current Supply Value is less than or equal to the **Available Supply**.
- Available Supply = Current Supply Pool minus the total Supply of all Friendly Units already in play.
- At no point may the Total Current Supply of a player's Units on the battlefield exceed the Supply Pool.
- In the final Round (as determined by the Mission Card), the Supply Pool is unlimited.

**Mission Marker Control.** Control is decided by total Current Supply of eligible contesting Units, not model count. The player with the highest total controls the Marker. A Unit at Supply 0 can control a Marker if no Enemy Units are contesting it. A Unit that is Out of Coherency can never control or contest a Mission Marker. Flying Units cannot Contest or Control Mission Markers.

**Tactical Mass.** A Unit that Disengages suffers a penalty: it cannot perform Ranged Attack or Charge actions in the following Assault Phase. This penalty is ignored if, at the moment the Disengage is declared, the Disengaging Unit's Current Supply Value exceeds the Combined Supply of all Enemy Units it is Engaged with.

**Unit Starting Supply.** Some Mission Cards award VPs equal to the Enemy Supply destroyed in a Round. The Supply Value destroyed in that Round is added to the score during the Scoring Phase.

> **Designer's Note:** Supply is the heart of the game's strategic layer. A Unit with fewer models consumes less Supply, contests objectives less effectively, and has less Tactical Mass to safely Disengage. Do you keep a Unit for its firepower, or sacrifice it to free Supply for a new Unit from Reserves?

---

## Part 7: The Battlefield

### 7.1 Line of Sight

StarCraft: Tabletop Miniature Game uses a **2D Line of Sight (LoS)** system. All checks are resolved from a top-down perspective.

To determine whether an acting model can see a target, trace an imaginary straight line from any part of the acting model's base to any part of the target model's base.

- If the line does not pass through any **Blocking Terrain** (terrain with an Effective Size of 1 or greater), the target is **Visible**. No further checks are required.
- If the line passes through Blocking Terrain, the target is not automatically hidden. Check the Cover rules (Part 7.1.1). Terrain that does not meet the requirements for Full Cover or Direct Cover does not block Line of Sight.
- A terrain piece's footprint is its physical base, or, if it has no base, the outermost edges of its solid structure viewed from above. Unless players agree otherwise, gaps, windows, doorways, and open interiors within the footprint block Line of Sight.
- A terrain opening may be passable for movement without counting as open for Line of Sight (Part 4.6).
- Players must agree during Battlefield Setup on the footprint of each terrain piece and on which openings count as passable gaps.

> **Designer's Note:** The top-down Line of Sight method prevents disputes over posture, slouching torsos, and weapon placement. It ensures terrain interacts correctly regardless of model posture or base design.

#### 7.1.1 Cover

A terrain piece provides Cover in one of two ways:

- **Full Cover:** A terrain piece blocks Line of Sight if its Effective Size (Part 7.1.2) is equal to or greater than the Effective Size of both the attacker and the target.
- **Direct Cover:** If the Line of Sight trace passes through a terrain piece, and either the attacker or the target is Within 1" of that terrain, the Line of Sight is blocked, provided the terrain's Effective Size is equal to or greater than the Effective Size of the model that is Within 1".

Each terrain piece is assessed for Cover independently. Terrain pieces do not combine their Effective Size or proximity. If no single piece meets Full or Direct Cover, Line of Sight is not blocked, regardless of how many pieces the trace passes through.

**Elevation Dead Zone:** If a model on HIGH GROUND (Size 3+) draws Line of Sight to a model at GROUND LEVEL that is Within 1" of the base of the same terrain piece, Line of Sight is blocked. This applies in both directions.

**Close Quarters:** If both models are Within 1" of the same terrain piece and Within 3" of each other, Direct Cover, Elevation, and Dead Zone do not apply. Use the standard trace.

> **Examples:**
> - A Goliath (Size 3) checking Line of Sight to a Marauder (Size 2) through a ruined wall (Size 2): the wall is too short to hide the Goliath, so both models are Visible.
> - A Goliath checking Line of Sight to Marines through a ruined wall: two Marines are Within 1" of the wall, and the wall's Effective Size equals the Marines' Size, so they benefit from Direct Cover and Line of Sight to them is blocked.
> - A Marine on HIGH GROUND and a Zergling at GROUND LEVEL, Within 1" of the cliff base but more than 3" apart: Elevation Dead Zone blocks Line of Sight in both directions.
> - If both models were Within 3" of each other, Close Quarters would apply and standard Line of Sight would be used instead.

#### 7.1.2 Verticality and Effective Size

When a model stands on top of a terrain piece (such as HIGH GROUND), its **Effective Size** equals the model Size plus the terrain Size.

> **Example:** A Marine (Size 2) on HIGH GROUND (Size 4) has an Effective Size of 6. It can see over Size 5 walls that would block it at GROUND LEVEL.

- **Top-Down Perspective:** Only terrain pieces that rise vertically between the two models (as viewed from above) can block the shot. The horizontal surface a model stands on does not obstruct the trace.
- **Stacking Terrain:** When a terrain piece is set on HIGH GROUND or MID GROUND, its Effective Size increases in the same way as a model's.

> **Abathur's Tip:** HIGH GROUND is a powerhouse. Units on Size 3 or 4 terrain can peer over barriers that block Units on lower ground. The downside is that they are exposed to nearly everything, so only put Units there if they can handle what is coming.

> **Example:** A Marauder (Size 2) on HIGH GROUND (Size 3) has Effective Size 5. A ruined wall (Size 2) on HIGH GROUND (Size 3) also has Effective Size 5. The Marauder cannot see over the wall. A Roach at GROUND LEVEL cannot see the Marauder through the wall. A Hydralisk at GROUND LEVEL, with no obstacle in the way, can.

#### 7.1.3 High Ground Cover

If all models of a Unit are standing on HIGH GROUND (Size 3 or larger terrain) with any part of their bases, the Unit may make an **Evade Roll** against all Ranged Attacks originating from a lower elevation. An attack originates from a lower elevation if at least one model of the attacking Unit is not standing on HIGH GROUND with any part of its base.

- **Exception:** Flying Units never benefit from High Ground Cover. Ranged Attacks made by Flying Units never originate from a lower elevation.

> **Designer's Note:** High Ground gives a strong defensive reason to occupy a raised position, separate from the Line of Sight bonus. It is more difficult to fire uphill.

#### 7.1.4 Flying Units and Cover

When checking Line of Sight to or from a Flying model, **ignore the Full Cover rule**. Direct Cover and the Elevation Dead Zone still apply.

- A Flying model's Effective Size is treated as higher than the Effective Size of any terrain piece on the table.
- Terrain can never provide Full Cover or Direct Cover against a Flying model as the model that is Within 1" of terrain.
- A Flying model still obeys any Direct Cover or Elevation Dead Zone rule that applies to the other model.

> **Designer's Note:** A Unit on HIGH GROUND is also more Visible to almost everything on the table, which is its weakness.

#### Line of Sight Summary (from source p. 50–52)

| Situation | Result |
|---|---|
| Trace does not pass through Blocking Terrain | Visible, no further checks |
| Full Cover: terrain Effective Size ≥ both attacker and target Effective Size | Line of Sight blocked |
| Direct Cover: trace passes terrain, attacker or target Within 1", terrain Effective Size ≥ that model's Effective Size | Line of Sight blocked (unless Close Quarters) |
| Attacker on HIGH GROUND, target at GROUND LEVEL Within 1" of same terrain | Blocked in both directions (Elevation Dead Zone, unless Close Quarters) |
| All defending models Wholly Within HIGH GROUND (Size 3+) and at least one attacker is not | Evade Roll granted (High Ground Cover) |
| Multiple small terrain pieces, none meeting Full or Direct Cover | Visible |
| Flying model | Ignore Full Cover; Direct Cover and Dead Zone still apply |

**Blocking and Passability:** Terrain's effect on Line of Sight and its effect on movement are determined separately. GRASS, unlike other Size 2 terrain, does not block movement but does block Line of Sight.

### 7.2 Engagement and Engagement Range

The **Engagement Range** extends 1" horizontally from any model's base. When two Enemy models are Within 1" of each other, they are **Engaged**.

- Unless stated otherwise, a Unit cannot end any movement or be PLACED within the Engagement Range of any Enemy model.
- When any model in a Unit is Engaged with any model in an Enemy Unit, both Units are considered Engaged.

#### 7.2.1 Engagement Restrictions

Models are Engaged only when all of the following are met:

- **Combat Tags match:** Ground models Engage only Ground models. Flying models cannot be Engaged by any model.
- **Terrain does not block:**
  - Size 0–1 terrain: Engagement is possible across it.
  - Size 2+ terrain: Models cannot Engage through it. Even within 1", a Size 2+ wall means they are not Engaged.
  - Models on HIGH GROUND cannot Engage models on GROUND LEVEL, and vice versa.
  - Models on MID GROUND can Engage models on HIGH GROUND or GROUND LEVEL only if both models are adjacent to the same ACCESS POINT connecting their respective elevations.

### 7.3 Markers and Tokens

#### 7.3.1 Tokens

Tokens represent tangible battlefield assets: Creep Tumors, Corrosive Bile, and Shades. Treat them as Terrain (Size 0) with their own base. Models may move through Tokens but cannot end movement overlapping them unless specified. Tokens are removed at the end of the Game Round unless stated otherwise. Always measure to the closest base edge of a Token.

#### 7.3.2 Markers

Markers track status or game states. They have no physical presence and do not block Line of Sight or movement.

- **Mission Markers:** Numbered Markers placed during Setup at the coordinates on the Deployment Card. Each is 32mm in diameter and has an Activated side and a Deactivated side. Markers 1 and 3 are Red, Markers 2 and 4 are Blue, and Marker 5 is Neutral.
- **Activation Markers:** Set beside the Unit that has completed its turn in a Phase. They are double-sided. One side shows the Movement Phase (arrow up), and the other shows the Assault Phase.
- **Faction Indicators:** Used on Mission Markers to show which player controls them. Some abilities use them to mark an area.
- **Mode Markers:** Track operational shifts (e.g., SIEGE MODE, BURROWED). They have STAY IN PLAY.
- **Zone of Influence Markers:** L-shaped corner markers that define the Zone of Influence when the Entry Edge does not span the full table edge.
- **First Player Marker:** Tracks initiative. The holder chooses which player activates first at the beginning of each Phase. It passes between players, usually when a player Passes early in a Phase or when VPs are tallied at the end of the Round.
- **Buff/Debuff Markers:** Positive effects are tracked with Blue Buff Markers, and negative effects with Red Debuff Markers.

### 7.4 Destroyed Units

When the last model falls, the Unit is **Destroyed**. Every effect, ability, and condition on the Destroyed Unit immediately ends. Tokens created by the Unit are removed (unless they are STAY IN PLAY). Effects the Unit applied to other Units remain unless stated otherwise. A Destroyed Unit cannot return to play unless a specific rule says so.

---

## Part 8: The Game Sequence

### 8.1 Rounds and Phases

A game lasts up to 5 Rounds. Each Round has four Phases, resolved in strict order:

| Phase | Name | Key Actions |
|---|---|---|
| 1 | The Movement Phase | Deploy, Move, Disengage, Hold |
| 2 | The Assault Phase | Ranged Attack, Charge, Run, Hold |
| 3 | The Combat Phase | Close Ranks, Close Combat Attack |
| 4 | The Scoring and Cleanup Phase | Control Markers, Score VP, Cleanup |

### 8.2 The Activation System

During Phases 1, 2, and 3, players use **Alternating Activation**. The holder of the First Player Marker decides which player activates first each Phase. Players then alternate, each activating one Unit per turn. Each Activated Unit performs exactly one action from the list available in that Phase.

> **Abathur's Tip:** Early in the game, deploy cheap Units to contest Markers and gather information, then deploy high-value Units in Rounds 2 and 3.

#### 8.2.1 Passing and Initiative

At any point during a turn, the Active Player may **Pass** instead of activating a Unit. A player must Pass if they have no eligible Units left.

- The first player to Pass in a Phase takes the First Player Marker for the next Phase.
- Once a player Passes, they cannot activate any further Units this Phase. The opponent then completes their remaining activations.

#### 8.2.2 Determining the First Player

Players Roll-Off (Part 3.2). The winner assigns the First Player Marker to either player for Round 1.

### 8.3 Deployment and Reserves

No Units begin on the battlefield. All Units in the Army List start in **Reserves** and are brought onto the battlefield during the Movement Phase as Supply allows.

#### 8.3.1 The Supply Pool

- **Round 1:** The Supply Pool equals the Mission Card's starting Supply.
- **Later Rounds:** The Supply Pool increases by the Supply Escalation value each Round.
- **Final Round:** In the last Round (as defined by the Mission Card), the Supply Pool becomes unlimited. All remaining Units in Reserves may be deployed without Supply restrictions.
- **Hard Cap:** Total Current Supply of on-table Units may never exceed the Supply Pool.

#### 8.3.2 Available Supply

Available Supply equals the Current Supply Pool minus the Total Supply of Friendly Units on the Battlefield. A Unit can be fielded only if its Current Supply Value is less than or equal to the Available Supply. Units Destroyed (or reduced by casualties) free up Available Supply.

#### 8.3.3 Deployment Restrictions

- A Unit arriving from Reserves cannot end its arrival during that Activation inside the opponent's Zone of Influence. This applies to all forms of arrival, including Warp Prism and SUMMON.
- A Unit can never end a Deploy action Out of Coherency. If all models cannot be placed legally while maintaining Coherency, the Unit cannot be deployed there.

> **Designer's Note:** The Roll-Off winner can give the First Player Marker to their opponent, and this is sometimes the right call. Going second in the Movement Phase lets you react. Going first in the Assault Phase rewards passing early in Movement.

> **Designer's Note:** Starting each Unit in Reserve is a deliberate departure from traditional miniature wargaming. It develops battlefield presence gradually, similar to a real-time strategy game, and avoids alpha-striking on Turn 1.

### 8.4 Phase 1: The Movement Phase

The battlefield changes before the first shot is fired. At the start of the Movement Phase:

- Resolve all "Start of the Round" abilities. The first player resolves theirs first. If a player has several, that player chooses the order, and each is fully resolved before the next begins.
- Verify Available Supply for all players.

#### 8.4.1 Activations

On the Active Player's turn, choose one:

- Activate a Unit on the battlefield without an Activation Marker and perform a **Move**, **Hold**, or **Disengage**.
- Activate a Unit in Reserves without an Activation Marker and perform a **Deploy** to enter the battlefield.

After the action, set an Activation Marker (Movement side) next to the Unit.

#### 8.4.2 Passing

The first player to Pass takes the First Player Marker for Phase 2. Set Activation Markers (Movement side) next to any Friendly on-table Units that did not activate.

### 8.5 Movement Phase Actions

#### 8.5.1 Hold

The Unit performs no action. Set an Activation Marker beside it. The Unit counts as Activated for the current Phase.

#### 8.5.2 Move

An Unengaged Unit changes its position on the battlefield.

#### 8.5.3 Resolving a Move

When a rule instructs a Unit to Move, Run, or otherwise reposition using standard movement, resolve it as follows.

**Step 1: The Leading Model**

- Choose a Leading Model and move it up to the Unit's Speed (Part 5.1 for split Speed values). Measure the actual path travelled.
- The Leading Model may pass through Friendly models in its own Unit.
- The Leading Model may not pass through Enemy models or Friendly models from other Units. Ground models may pass through a Flying model's base as if it were not there, and vice versa.
- The Leading Model cannot move through terrain of Size 2 or larger.
- Follow Gap Clearance rules (Part 4.6).
- The Leading Model cannot change elevation unless it passes through an ACCESS POINT.
- The Leading Model may not end overlapping terrain or another model's base.
- The Leading Model's entire base must end on the battlefield.
- The Leading Model cannot end within 1" (Engagement Range) of an Enemy Ground Unit.
- No part of the Leading Model's base can move more than the Unit's Speed value.

> **Abathur's Tip:** Passing early in the Movement Phase is a game-changing move. The first player to Pass gains the First Player Marker for the Assault Phase and gets to shoot first. Passing early also gives you information while your opponent uses their activations, but moving too early means missing chances to manoeuvre.

**Step 2: Other Models**

- Pick up all remaining models and set them in Coherency (Part 4.4) around the Leading Model.
- These models are set, not moved. They may ignore intervening obstacles, but they must end in a legal position: no overlapping bases, entire bases on the battlefield, and not within 1" of an Enemy Unit.

**Terrain Interactions**

- **Size 0 and Size 1:** Pass through freely. Cannot end movement overlapping the terrain's footprint.
- **Grass (Size 2, special case):** See the GRASS keyword (Part 11). Grass does not block movement but does block Line of Sight. If the Leading Model's path passes through, or any model of a Unit ends on, a Grass piece, that piece is immediately removed from the game for the rest of the battle.
- **Flying Units** moving over Grass do not destroy it. If a model of a Flying Unit ends on Grass, it is removed as normal.
- **Size 2 and larger:** Cannot move through.

**Elevation**

- **GROUND LEVEL:** Standing directly on the playmat.
- **MID GROUND:** Standing on horizontal terrain of Size 1 or 2.
- **HIGH GROUND:** Standing on horizontal terrain of Size 3 or larger.

A model stands on the elevation of its base. If its base spans multiple levels, it is on the highest.

- **ACCESS POINTS** connect elevation levels. Models change elevation only by moving through an ACCESS POINT (examples: ladders, portals, doors). Coherency Links may pass through ACCESS POINTS.
- **RAMPS** are Size 1 MID GROUND terrain. A model on any part of a ramp is at MID GROUND. Models enter and exit a ramp only through its two ACCESS POINTS (one at the base, one at the top), and may end their movement on the ramp.

#### 8.5.4 Disengage

An Engaged Unit withdraws from melee.

- Move it following the standard Move rules (Part 8.5.3).
- Any individual model that cannot end its movement strictly outside the Engagement Range of all Enemy Units is immediately removed and considered Destroyed. Other models that clear the Engagement Range remain.
- If the Leading Model cannot end its movement outside the Engagement Range of all Enemy Units, the Disengage fails. The Unit does not move, the Leading Model is removed, and the Unit's activation ends.
- A Unit that Disengages cannot perform a Ranged Attack or Charge in the following Assault Phase, **unless** its Current Supply Value is greater than the Combined Supply of all enemies it was Engaged with (Tactical Mass).

> **Designer's Note:** The Tactical Mass exception prevents small screening Units from holding up a much larger force indefinitely. Zerglings should not be able to hold a Siege Tank locked in melee indefinitely.

#### 8.5.5 Deploy

A Unit from Reserves enters the battlefield.

- Confirm the Unit's Current Supply Value fits within the Available Supply.
- Treat the player's Entry Edge as the base of a Leading Model. Set the Leading Model in contact with the Entry Edge outside the battlefield, then move it up to the Unit's Speed following standard Move rules (Part 8.5.3).
- The Leading Model enters first. Set the rest of the Unit In Coherency.
- The Unit cannot finish its activation within the enemy's Zone of Influence.
- A Unit can never end a Deploy action Out of Coherency. If all models cannot be placed legally while maintaining Coherency, the Unit cannot be deployed in that location.

> **Designer's Note:** Timing a deployment correctly can swing an entire flank. Timing it wrong feeds reinforcements into a meat grinder.

**Units Returned to Reserves**

Some rules return a Unit to Reserves. The Unit is not Destroyed; it has left the battlefield.

- When returned, its Current Supply is released, and Available Supply is recalculated from that moment.
- The Unit keeps its equipment. Damage recorded on its Damage Marker remains, and the Unit carries it when redeployed.
- Buffs, debuffs, and effects with a duration "until the End of the Round" stay on the Unit. The clock does not pause while it is away.
- While in Reserves, the Unit keeps its Active, Passive, and Reaction Abilities, but none of them function. They cannot be triggered, produce effects, or be used to pay costs. When the Unit redeploys, its abilities resume immediately unless an ability says otherwise.
- Tokens and Markers the Unit left on the battlefield are removed, unless they have STAY IN PLAY.
- If the Unit was Activated during the current Phase, it remains Activated and cannot take further action in that Phase.

### 8.6 Phase 2: The Assault Phase

The Assault Phase is when the Damage is done. Ranged Attacks tear through exposed Units, and Charges strike defenders who chose a poor position.

#### 8.6.1 Activations

On the Active Player's turn, activate a Unit with a Movement-side Activation Marker and select one action: **Run**, **Hold**, **Charge**, or **Ranged Attack**. After completing the action, set an Activation Marker (Assault side) next to it. Units still in Reserves cannot act during this Phase.

#### 8.6.2 Passing

The first player to Pass takes the First Player Marker for Phase 3. Set Activation Markers (Assault side) next to any Units that did not activate.

### 8.7 Assault Phase Actions

#### 8.7.1 Run

An Unengaged Unit moves across the battlefield following the standard Move rules (Part 8.5.3). Nominate a Leading Model, move it up to the Unit's Speed, and set the remaining models In Coherency. All standard restrictions apply, including Gap Clearance and the prohibition on ending within the Engagement Range of Enemy Units.

> **Abathur's Tip:** Running is underused. If a Unit cannot reach a worthwhile target, use the Run to close distance for the next Round, reposition onto a Mission Marker, or pull back behind Cover. Two Moves across two Phases cover twice the ground of one Move.

#### 8.7.2 Hold

The Unit does not take any action. Set an Activation Marker (Assault side).

#### 8.7.3 Ranged Attack

A Ranged Attack is resolved in two stages. First, the attacking player selects a valid target and assigns weapons to it. Second, the attack is resolved through the three-pool system (Part 8.7.4). Units with multiple weapon profiles may split their fire across targets, resolving each weapon as a separate **Batch**.

**1. Target Eligibility.** A valid target must meet all of the following:

- At least one Visible model from the target Unit is within the weapon's maximum Range. Measure from the attacking model's base to the target model's base.
- Only models within Range of at least one Visible model from the target Unit contribute dice.
- The target's Combat Tag matches the weapon's target characteristic (Ground, Flying, or All).
- **Engagement Status:** An Unengaged attacking Unit cannot select an Engaged Unit as a target (except Spillover from Template Weapons, Part 8.7.6). An Engaged attacking Unit may only target the Unit(s) it is currently Engaged with.

**2. Weapon Selection and Batching.**

- Each model fires one of its available Assault Phase weapons. All models using the same Weapon Profile must fire at the same target. A **Batch** consists of all models firing the same weapon at the same target.
- The same-profile, same-target rule applies to SIDEARM weapons as well. All models firing the same SIDEARM profile must target the same Unit, which may differ from the target of the Unit's other weapons.
- If a Unit has multiple Weapon Profiles, it may fire at different targets, resolved in separate Batches.
- **Removing Dice:** When a Special Ability reduces the number of dice in a Batch, the controlling player of the Unit resolving the ability chooses which dice are removed.
- **Batch Sequence:** Declare the target of one Batch, resolve it fully, then declare the next. Targets are not declared simultaneously.

> **Designer's Note:** If dice in the same Batch have different modifiers, roll them separately. It still counts as the same Batch.

#### 8.7.4 Ranged Attack Resolution

Every attack moves dice through three pools. Dice begin in the **Attack Pool**, pass through the **Armour Pool**, and end in the **Damage Pool**. Dice that survive the sequence inflict casualties.

- **Attack Pool:** Generate dice equal to each attacking model's Rate of Attack (RoA). Roll them against the weapon's Hit characteristic. Each success moves to the Armour Pool. Discard all failures.
- **Armour Pool:** The defender rolls all dice against the target Unit's Armour. Each success is discarded. Each failure moves to the Damage Pool. Dice moved by Surge or CRITICAL HIT go directly to the Damage Pool without an Armour Roll.
- **Damage Pool:** Each die remaining inflicts Damage equal to the weapon's Damage characteristic. If the target Unit is eligible for an Evade Roll, the defender rolls all dice in this pool against the Unit's Evade before Damage is applied. Each success is discarded.

> **Abathur's Tip:** Batch sequencing gives an advantage. Use the first Batch to weaken or eliminate your target, then adjust the second Batch based on the result.

> **Abathur's Tip:** Surge bypasses the entire Armour roll, making it one of the most efficient sources of Damage. Before firing, check that the weapon's Surge Type matches the target's Combat Tag. An Anti-Ground Surge on a Ground target can double or triple Damage compared to firing at a Flying target with the same weapon.

**Resolve each Batch in sequence:**

1. **Roll to Hit**
   - For each attacking model with an eligible target, add dice equal to the weapon's RoA to the Attack Pool.
   - If the weapon has an S Dice characteristic, add one **Surge Die** (use a different colour). If there is no S Dice, the Surge Result is 0.
   - Roll all Attack Dice. Results equal to or higher than the Hit value are successes. Move successful dice to the Armour Pool.

2. **Resolve Surge**
   - If the target's Combat Tag matches the weapon's Surge Type, move a number of dice equal to the Surge Die result from the Armour Pool directly to the Damage Pool. These bypass Armour entirely. Surge can never move more dice than are in the Armour Pool.
   - If the tag does not match, the Surge Die result is ignored entirely.

3. **Armour Rolls**
   - The defender rolls all dice in the Armour Pool. Results equal to or higher than the Unit's Armour: success, discard the die. Lower results: failure, move the die to the Damage Pool.

4. **Evade Rolls** (only if the target qualifies)
   - A Special Ability or keyword grants an Evade Roll, or the target is Engaged and suffering Damage from a Ranged Attack.
   - The defender rolls all dice in the Damage Pool. Results equal to or higher than the Unit's Evade: success, remove those dice. The remaining dice are confirmed Damage.

5. **Resolve Damage and Casualties**
   - If no dice remain in the Damage Pool, skip this step.
   - Multiply the remaining dice by the weapon's Damage characteristic.
   - Add any previously accumulated Damage (from earlier attacks in this or previous Rounds, indicated by a Damage Marker). This total is the **Total Damage**.
   - Apply any Special Abilities that reduce Total Damage.
   - The defending player removes casualties model by model, following these rules:
     - The attack cannot remove more models than the number of Visible models in the target Unit.
     - While Total Damage equals or exceeds a model's HP, remove one Visible model and reduce Total Damage by that model's HP. Repeat.
     - If all Visible models are Destroyed, discard remaining Total Damage. It does not carry over to non-Visible models.
     - If Total Damage remains but cannot Destroy the next Visible model, record it with a Damage Marker (e.g., a D6 set next to the Unit).

#### 8.7.5 Removing Models from Engaged Units

When a Unit is Engaged and suffers casualties from any source, ignore standard Visibility rules and apply this priority order. The defending player must remove casualties in this strict order:

1. **Priority 1:** Models not Within the Engagement Range of any Enemy Unit.
2. **Priority 2:** Models Within the Engagement Range but not in Base-to-Base contact with an Enemy model.
3. **Priority 3:** Models in Base-to-Base contact with an Enemy model.

When selecting a model at Priority 2 or 3, the defending player cannot choose a model whose removal would end the Unit's Engagement with a specific Enemy Unit, provided another valid casualty exists in any tier.

> **Designer's Note:** The priority system prevents the defender from picking off the model holding them in melee, which would give the enemy a free Disengage. Shooting at a melee force eats away at the outer models first.

#### 8.7.6 Template Weapons

Template weapons are **Blast Templates (BT)** and **Flamer Templates (FT)**.

**1. Alignment**

- **BT:** The template must cover as much of the target model's base as possible. The centre of the target model's base is the Target Point.
- **FT:** The narrow end must be flush with the attacking model's base edge and aimed at the target. The centre of the target model's base is the Target Point.
- Templates affect only models at the same elevation as the Target Point.
- Flying models are not on any elevation level for template purposes. A template at GROUND LEVEL does not affect Flying models, unless the template weapon has Target: ALL or Target: Flying.

**2. Declaring Targets.** Follow standard Target Eligibility (Part 8.7.3), with this exception: select one Enemy Unit as the **Primary target**. All models in that Unit covered by the template are the Main target. Every other model (Friendly or Enemy) covered by the template is resolved under **Spillover**, provided it shares the same elevation and Combat Tag as the Primary target.

**3. Determining Hits.** A model is affected if all of the following are true:

- Its base is partially or fully covered by the template.
- It is on the same elevation as the declared Target Point.
- A line traced from the target model's base (BT) or the attacking model's base (FT) to the model's base is not blocked by terrain (Size 2+).
- It is an eligible target type.

**4. Attack Pool Generation**

- **Main Target:** Generate Attack Dice equal to the number of Affected models in the target Unit, plus any weapon RoA modifiers.
- **Spillover (separate Batch per Unit):** Generate Attack Dice equal to the number of Affected models in that Unit only. Do not apply RoA modifiers. Do not apply Surge.

**5. Resolution**

- Roll to Hit as normal. Results equal to or higher than the Hit characteristic are successes and move to the Armour Pool.
- Do not roll a Surge Die. For the Main target, the Surge Result equals the number of Affected models in that Unit. Spillover attacks do not generate Surge.
- Apply Surge normally for the Main target if the Combat Tag matches. Do not apply Surge to Spillover.

> **Abathur's Tip:** A well-timed Blast Template can hit two or three Units at once, causing Spillover in addition to the main Damage. Flamer Templates have a shorter range but almost always hit everything within the cone, making them effective against tightly packed melee Units.

#### 8.7.7 Charge

An Unengaged Ground Unit moves into the Engagement Range of Enemy Units.

**1. Declare Targets**

- All targets must have the Ground Combat Tag. Flying Units cannot Charge or be Charged.
- A Charge does not require Line of Sight.
- Declare all intended targets before rolling.

> **Designer's Note:** Charges do not require Line of Sight because melee combatants are assumed to detect threats through sound, vibration, and general awareness. Without this, melee Units would be unplayable in a map-heavy game.

**2. Determine Charge Distance**

- Choose the Leading Model and nominate one model per target Unit as the Charge target.
- Roll 1D6 and add it to the Unit's Speed. This is the **Charge Roll Distance**.
- Measure along the actual path of travel. Bypass impassable obstacles. Follow Gap Clearance rules.

**3. Successful and Failed Charges.** The Charge succeeds only if the Leading Model can be legally set in a position that is:

- Wholly Within the Charge Roll Distance of its starting point.
- Within the Engagement Range (1") of every declared Charge target.
- Not overlapping other bases or impassable terrain.
- Not within the Engagement Range of any Enemy Unit that was not declared as a target.

If the Charge fails, the Unit does not move and its activation ends.

**4. Execute the Move.** Move the Leading Model into the valid position. Set it in Base-to-Base contact with the Charge target(s) if possible, otherwise as close as possible within the Engagement Range. Set remaining models In Coherency. Coherency Links may pass through Enemy models the Unit is Engaged with. None may end within the Engagement Range of a Unit not declared as a target. Placement priority:

- **Priority A:** Base-to-Base contact with declared target models (whenever physically possible).
- **Priority B:** Within the Engagement Range of targets (if Base-to-Base is impossible).
- **Priority C:** As close as possible to the Leading Model to maintain Coherency.

> **Abathur's Tip:** A failed Charge wastes the whole activation. The Charge Roll is Speed plus 1D6, so know your minimum, average, and maximum range. For multi-charges, the Leading Model must be within 1" of all declared targets, which makes them powerful but risky.

---


## Part 8 (continued)

### 8.8 Phase 3: The Combat Phase

Engaged Units trade blows in melee. Unlike the previous Phases, activation is **mandatory**: every Unit currently Engaged with an Enemy must act in this Phase. A player cannot skip a fight.

- Flying Units are never Engaged. They do not participate in the Combat Phase, cannot be Activated, cannot Close Ranks, and cannot be the target of Close Combat Attacks.
- **Activations:** Players take turns activating one Engaged Unit at a time. The holder of the First Player Marker chooses who activates first. Players then alternate, each activating one Engaged Unit per turn. Each Unit follows the Close Combat Attack (Part 8.8.1).
- **Unit Eligibility:** Only Engaged Units may be Activated. Unengaged Units cannot act. Once a Unit's Close Combat Attack is fully resolved, remove its Activation Marker.
- **Passing:** A player Passes only when they have no remaining Engaged Units to activate. When both players Pass, the Phase ends.

#### 8.8.1 The Close Combat Attack

An Engaged Ground Unit attacks the Enemy Units it is Engaged with.

**1. Close Ranks (Optional).** Before rolling, the Unit may press into the fight:

- Choose a Leading Model and move it up to 3" following standard Move rules, with two restrictions:
  - The Leading Model must end closer to the Unit(s) it is Engaged with than it started.
  - This move cannot bring the Unit into Engagement with new Enemy Units that were not Engaged at the start of this Phase.
- Reposition the rest of the Unit into Coherency. Coherency Links may pass through Enemy models the Unit is Engaged with.
- Set models in Base-to-Base contact with Enemy models wherever possible. If not possible, set them in Base-to-Base contact with Friendly models from the same Unit that are within the Engagement Range.
- Models already in Base-to-Base contact at the start of this step are not moved.
- Models cannot use this move to Disengage from other Enemy Units.

**2. Declare Attackers.**

- **Fighting Rank:** Within the Engagement Range (1") of an Enemy model.
- **Supporting Rank:** In Base-to-Base contact with a Friendly model from the same Unit that is in the Fighting Rank.
- Line of Sight is not required. Eligible models strike the Enemy Unit as a whole.

> **Designer's Note:** Making the Close Combat Attack obligatory removes the option to avoid an unfavourable melee. It promotes cautious play in the Movement and Assault Phases.

> **Abathur's Tip:** Close Ranks is a useful 3" move that many new players overlook. The more models touching the enemy, the more dice you roll. Close Ranks cannot bring a Unit into Engagement from outside, so plan Charges accordingly.

**3. Roll Attacks.** Resolve attacks using the Ranged Attack sequence (Part 8.7.4), with this restriction:

- Use only Combat Phase weapons listed on the Unit Card.
- If a model has more than one eligible Combat Phase weapon, the controlling player chooses one.
- Evade Rolls are available in the Combat Phase only if the Unit has a Special Ability or keyword that explicitly grants an Evade Roll against Close Combat attacks.

**4. Fighting Multiple Units.** If Engaged with more than one Enemy Unit:

- A model may attack an Enemy Unit only if it is in the Fighting Rank with a model from that Enemy Unit, or in the Supporting Rank (in Base-to-Base contact with a Friendly model that is in Fighting Rank contact with that Enemy Unit).
- Declare which target receives the Surge Die before rolling. The Surge Die cannot be split.

**5. Casualty Removal.** Follow the Engaged Unit rules (Part 8.7.5).

**6. Post-Combat Status.** After casualties are removed:

- If none of the Unit's remaining models is within 1" of an Enemy, the Unit is immediately Unengaged.
- A freed Unit that has not yet Activated this Phase is no longer bound by mandatory Combat activation. It effectively Passes, and acts normally from the next Round.
- In rare cases, a Reaction or specific trigger may allow a freed Unit to act in the current Phase.

> **Abathur's Tip:** A Mission Marker is controlled by total Supply, not by the number of models. A lone Elite Unit with high Supply can outvote a horde of cheap infantry.

### 8.9 Phase 4: The Scoring and Cleanup Phase

The first player initiates each step in order:

1. Determine Mission Marker Control
2. Score Victory Points
3. End of Game Check
4. Resolve End of the Round Effects
5. Cleanup and Refresh
6. Determine Initiative

#### 8.9.1 Determine Mission Marker Control

**Identify Contesting Units.** A Unit may Contest a Mission Marker only if all three conditions are met:

- It is on the battlefield (not in Reserves).
- At least one model is within 3", has Line of Sight to the Marker, and is on the same elevation as the Marker. For tracing Line of Sight, treat the Marker as Size 0.
- The Unit is In Coherency.

A Flying Unit cannot Contest or Control Mission Markers, regardless of position or Coherency state. A BURROWED Unit cannot Contest or Control Mission Markers.

**Calculate Control.** For each Marker:

- Each player sums the Current Supply Value of all their contesting Units.
- The player with the higher total controls the Marker.
- A tie means the Marker is **Contested**, and control does not change.
- A Unit at Supply 0 may still control a Marker if no Enemy Units contest it.

**Sticky Control.** Set a Faction Indicator on each controlled Marker. Once a Marker is controlled, it remains under that player's control, even if they move Units away, until the opponent actively reclaims it by ending a Scoring Phase with a higher contesting Supply total. A tied result never transfers control. A Marker cannot become neutral again once a player has taken control.

> **Designer's Note:** Sticky Control means a location stays yours until the opponent retakes it. This encourages bold play and forces the opponent to spend real resources to take an objective.

> **Key Rule:** Control is determined by Current Supply Value, not the number of models.

> **Eligibility Summary (source p. 71):**
> - **Not on the battlefield (in Reserves):** cannot contest.
> - **Supply 0:** can control a Marker if no Enemy Units contest it, but cannot win a contest.
> - **Flying Unit:** cannot contest or control. Overrides standard rules.
> - **BURROWED Unit:** cannot contest or control. Overrides standard rules.
> - **Out of Coherency:** cannot contest or control any Marker.
> - **Not within 3" with Line of Sight on the same elevation:** cannot contest.

#### 8.9.2 Score Victory Points

Both players simultaneously tally VPs based on the Mission Card's scoring conditions.

#### 8.9.3 End of Game Check

The game ends immediately if:

- A Special Winning Condition is fulfilled. The player who meets it wins outright.
- A player has no models on the battlefield and no Units in Reserves. The surviving player gains +10 VP.
- The final Phase of the final Round (usually Round 5) is complete. Proceed to Part 8.10.

#### 8.9.4 Resolve End of the Round Effects

Resolve all "End of the Round" abilities. The holder of the First Player Marker resolves theirs first. If a player has several, that player chooses the order, and each is fully resolved before the next begins.

#### 8.9.5 Cleanup and Refresh

- Remove all Tokens and Markers except:
  - Tokens and Markers with STAY IN PLAY
  - Damage Markers
  - Mission Markers
  - Faction Indicators that represent control over Mission Markers
- Flip all Exhausted Tactical and Faction Cards back to their active (face-up) side.

#### 8.9.6 Determine Initiative

- The First Player Marker is awarded to the player with **fewer** Victory Points.
- If tied, conduct a Roll-Off. The winner takes the First Player Marker.
- Begin Phase 1 of the next Round.

> **Designer's Note:** Giving initiative to the player with fewer VPs is a catch-up mechanic. It prevents a runaway lead.

### 8.10 The Final Score

If the game ends by the Round Limit:

- **Mission Score:** Total all VP earned from objectives.
- **Final Round, All Units Destroyed:** At the start of the final Scoring Phase, all Units remaining in Reserves are considered Destroyed. Each player is awarded VPs for these Units as normal, following the Mission Card's scoring conditions for Destroyed Enemy Units.
- **Determine Winner:** The player with the highest final VP total wins.
- **Tiebreaker:** If both forces have the same total VPs, apply the Mission Card's tiebreaker. If none is defined, the game is a **Draw**.

---

## Part 9: Preparing for Battle

Players build an army with two resources: **Minerals**, used for Units and Upgrades, and **Vespene Gas**, used for Tactical Cards. They then draft the Mission and Deployment and set up the board.

### 9.1 Army Building

Moved to **MD Files/SCTMG Army Building.md** in the GitHub repository (and the project doc `SCTMG Army Building.md`). That file also includes the Tactical and Faction Card rules from Part 10.5 that apply to army building.

### 9.2 Mission Selection and the Draft

Players use a short draft to determine the Mission and Deployment.

**What You Need.** Each player's 2 Mission Cards and 2 Deployment Cards are covered in the army building file. Arrange all cards face-up in two rows: Row 1 is Mission Cards, and Row 2 is Deployment Cards.

**Step 1: Roll-Off.** The winner makes two choices, in order:

- **Choice 1, Colour:** Declare yourself the **Red Player** or the **Blue Player**. This determines your Entry Edge, Zone of Influence, and Mission Marker affinity for the game.
- **Choice 2, Draft Control:** Choose to control either the Mission Draft or the Deployment Draft. Your opponent automatically controls the other.

**Step 2: Mission Draft.**

- The player without Mission Draft control removes any 2 Mission Cards.
- The player with Mission Draft control selects 1 of the 2 remaining cards. This is the Mission. Discard the last card.

**Step 3: Deployment Draft.** Repeat the same process for Deployment Cards.

> **Abathur's Tip:** Controlling the Mission Draft secures victory conditions that suit your army. Controlling the Deployment Draft shapes the battlefield. Tight deployment zones favour melee armies. Spread-out zones favour ranged ones.

**Step 4: Marker Affinity.**

- Markers 1 and 3 are associated with the **Red Player**.
- Markers 2 and 4 are associated with the **Blue Player**.
- Marker 5 begins **Neutral**.

Marker affinity indicates which player's colour is printed on each Marker. It does not grant starting control.

#### 9.2.1 Mission and Deployment Card Details

- **Mission Cards** define victory conditions and pacing: timing windows for triggered rules, Starting Supply and Escalation, Game Length (usually 5 Rounds), and Additional Conditions such as instant win scenarios.
- **Deployment Cards** define the battlefield layout: dimensions, Mission Marker coordinates for Markers 1 to 5, the Entry Edge for each player, and the Zone of Influence, which extends 6" inward from each player's Entry Edge.

### 9.3 Battlefield Setup

Once the draft is complete, set up the battlefield in this order:

1. **Table dimensions:** Confirm the dimensions on the Deployment Card.
2. **Entry Edges:** Assign Entry Edges to each player as shown on the Deployment Card.
3. **Zone of Influence Markers:** Set them at the corners of each player's Entry Edge where the Entry Edge does not run the full length of a table edge.
4. **Terrain:** Select or roll for one of the pre-made maps (roll D6 for Standard, or D3 for Skirmish), or, starting with the Red Player, alternate placing one terrain piece at a time following the density guidelines below.
5. **Mission Markers:** Place them at the coordinates on the Deployment Card. Markers can be set up on MID GROUND and HIGH GROUND. They cannot be placed on impassable terrain. If a Marker's coordinates overlap impassable terrain, move the terrain piece as close as possible without overlapping the Marker.

#### Terrain Density Guidelines

These guidelines apply to a Standard (36" x 54") table and should be scaled for other sizes.

- **Recommended total:** 8 to 12 pieces.
  - 0 to 2 pieces of **Size 0** (scatter terrain).
  - 2 to 4 pieces of **Size 1** (barricades, low walls, scatter crates). They give Cover to infantry but do not block Line of Sight for models larger than Size 1.
  - 6 to 8 pieces of **Size 2** (ruins, bunkers, wrecked vehicles). They form the backbone of the table, blocking Line of Sight and creating fire lanes and chokepoints.
  - 1 to 2 pieces of **Size 3+** (if available). They create HIGH GROUND and block Line of Sight for almost everything. Too many make ranged combat nearly impossible.
  - 4 to 6 pieces of **Grass** (Size 2 special). They do not block movement but provide natural Line of Sight cover.
- **Distribution:** Divide the table into four quarters. Each quarter should contain at least 2 significant pieces (Size 2 or larger). No quarter should be empty, and none should be so dense that Units cannot manoeuvre.
- **The Centre:** The area within 6" of the table centre should contain at least one significant terrain piece.
- **Fire Lanes:** At least 2 clear fire lanes of 6" or wider should run roughly from one Entry Edge toward the other.
- **Access Points:** Every piece of Size 3+ terrain that models can stand on should have at least one ACCESS POINT reachable from GROUND LEVEL without passing through another Size 2+ terrain piece.

> **Abathur's Tip:** Terrain placement is the first strategic move. Position tall blocking terrain toward the centre if your force excels at ranged combat. If your force is better at close combat, use terrain to create sneaky routes. Placing terrain near a Marker makes it easier to hold with Cover.

---

## Part 10: Advanced Rules

Part 10 covers Special Abilities (Active, Passive, and Reaction), Tactical and Faction Cards, and the resources used to pay for abilities.

### 10.1 Special Abilities

Each ability on a Unit Card or Tactical Card has a consistent format:

- **Name** identifying the ability.
- **Phase Limitation** restricting when it can be used (if applicable).
- **Type:** Passive, Active, or Reaction.
- **Cost:** The resource payment (CP, BM, or PE), and the Instruction text. Abilities with 0 cost are free.

An ability may be used only when all its requirements are met:

- The timing or trigger condition is correct, and any Phase restrictions are satisfied.
- The target is within Range and Line of Sight (unless the ability states otherwise).
- If an ability does not specify a target, Line of Sight does not apply. Placing a Token or Marker is not a target.
- All Costs are paid in full before the ability resolves, and the Unit using it must be on the battlefield.
- If a Unit is affected by multiple instances of an ability with the same name, the effects **do not stack**. Only one instance applies at a time.
- Effects from Active or Reaction Abilities that expire "at the End of the Round" remain active until all End of the Round effects (Part 8.9.4) are resolved. They are removed during Cleanup and Refresh (Part 8.9.5).

### 10.2 Active Abilities (Full Rules)

Active Abilities represent deliberate manoeuvres, technologies, or enhancements that require a command to execute.

- A Unit may use an Active Ability only when it is currently Activated.
- The ability must be triggered either immediately before declaring an action or immediately after fully resolving one. It cannot be used during an action.
- Active Abilities cannot be used while the Unit is in Reserves, unless the ability says otherwise.
- Unless stated otherwise, effects granted by an Active Ability expire at the End of the Current Round.
- **Once Per Round:** A specific Unit may use a named Active Ability only once per Round, unless it has the REPEATABLE keyword. This limit applies to each Unit individually. Two squads of the same Unit type can each use the same ability in one Round, but a single squad may not use it twice.
- If a Unit gains an Active Ability through a Tactical Card, the Once Per Round limit still applies, regardless of how many copies of the card the player controls.

### 10.3 Passive Abilities (Full Rules)

- Passive Abilities are always active while the Unit is on the battlefield. They do not require activation.
- They are not in effect while the Unit is in Reserves, unless the ability says otherwise.
- **Priority:** If multiple Passive Abilities trigger simultaneously, the controlling player chooses the order. If both players have Passive Abilities triggering at the same time, the Active Player resolves theirs first.

### 10.4 Reaction Abilities (Full Rules)

Reaction Abilities respond to specific events as they occur. A Reaction is used in direct response to a defined trigger, such as "When this Unit is targeted by an attack."

- It must be declared at the exact moment the trigger occurs. If the window is missed, it cannot be used retroactively.
- Reactions cannot be used while the Unit is in Reserves, unless stated otherwise.
- Unless stated otherwise, effects granted by a Reaction expire at the End of the Current Round.
- **Frequency Limit:** A specific Unit may use a named Reaction only once per Round, following the same rules as Active Abilities.
- **Reaction Limit:** Each player may resolve only one Reaction per Activation. If both players want to react to the same trigger, the Active Player resolves first.

> **Example:** If a Marine Unit is attacked and uses Infantry Armor for its Armour Roll, the Medic Unit behind it cannot use Life Support in the same Enemy Activation.

**Summary Table (source p. 81)**

| | Active Ability | Passive Ability | Reaction Ability |
|---|---|---|---|
| When it is used | Immediately before declaring an action, or immediately after one resolves | Always on, no trigger needed | At the exact moment the trigger occurs |
| Can interrupt an action? | No | Resolves as conditions are met | Yes, fires at the trigger point mid-sequence |
| Requires Activation? | Yes | No | No |
| Player decision? | Yes, a deliberate choice | No, automatic | Yes, must be declared at the trigger |
| Frequency | Once per Round per Unit per named ability, unless REPEATABLE | Always active, no limit | Once per Round per Unit per named ability, unless REPEATABLE |
| In Reserves? | No | No, unless stated otherwise | No, unless stated otherwise |
| Cost | Pay in full before resolving | None | Pay in full before resolving |
| Simultaneous triggers | Controlling player chooses order; Active Player first if both trigger | Controlling player chooses order; Active Player first | Active Player resolves first |

### 10.5 Tactical Cards and Faction Cards

The introduction to this section and the Unique rule are moved to **MD Files/SCTMG Army Building.md**. Resources and Costs (10.5.1) and Managing Card States (10.5.2) remain below.

#### 10.5.1 Resources and Costs

- Terran uses **CP**, Zerg uses **BM**, and Protoss uses **PE**. These resources are provided by Exhausting cards.
- **Exhausting a Card:** To pay a cost such as "Cost: 1 CP," the player must Exhaust a Ready card that matches the resource type. Exhausting means flipping the card face down.
- If the player cannot Exhaust enough cards to pay the entire cost, the ability cannot be activated.
- Excess resources generated by a card are lost. Resources generated to activate one ability cannot be saved or spent on another.

#### 10.5.2 Managing Card States

Every Tactical Card and Faction Card is in one of two states:

- **Ready** (face-up).
- **Exhausted** (face-down).

A Ready card may be Exhausted in two ways:

1. To use an Active or Reaction Special Ability printed on the card.
2. To generate its resource to pay for an ability located elsewhere (for example, on a Unit Card).

Once a card is Exhausted, it provides no resources and its abilities cannot be used until it is Refreshed (flipped face-up) during Phase 4 Cleanup.

---

## Part 11: Keyword Glossary and Definitions

Moved to **MD Files/SCTMG Keywords.md** in the GitHub repository (and the project doc `SCTMG Keywords.md`).

---

## Part 12: Quick Reference

Moved to **MD Files/SCTMG Quick Reference.md** in the GitHub repository. The file is a verbatim copy of 12.1 to 12.9, plus the 12.10 introduction. The unit tables (12.10), Tactical Card points (12.11) and Example Armies (12.12) are not reproduced. Costs come from the Cost Table file.

---

## Appendix: Map Layouts

The map layouts (Terrain Key, and the Assembly Requires lists and diagrams for the pre-made maps) are diagrams. They are not reproduced in this file. The Terrain Key and the item lists can be read from the source PDF, pages 115 to 124.

**Terrain key (from the source text):** Head Statue, Shrubs A, Shrubs B, Wall Sets 1 to 6, Lost Temple Ramp, Protoss Banner, Temple Obelisk, Statue Shard, Vespene Geyser.

---

## Index

The index (source p. 114) is not reproduced. It is a page-reference list for the terms defined in this file. Use the section headings above, or search the file for a term.

---

## Notes on This Conversion

- The source text is 115 pages. Page headers, "Back to Table of Contents" links, and page numbers were removed. Bracketed page numbers were kept as section markers.
- Sidebar "Abathur's Tip," "Designer's Note," and "Note" boxes are kept as blockquotes. They are not rules.
- Diagram captions are kept where they describe a rule. The diagrams themselves are not included.
- Spelling follows the source (British spellings such as "Armour" and "organisation"). Terms are not changed.
- Obvious text-extraction artifacts, such as hyphenation splits and joined words, were repaired. Rules text was not reworded.
- Part 1's worked example is condensed to the mechanics each step demonstrates.
