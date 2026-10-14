# StarCraft TMG: Terran Units and Cards

Source: Terran P2P Card Sheets (A4) and Terran P2P W2 Card Sheets (A4). Card text is transcribed from the card sheets. Costs are not included; see `SCTMG Cost Table.md`. Supply Values per model count are also in the cost table.

## Unit Statistics

| Unit | HP | Armour | Evade | Size | Speed | Army Slot | Combat Role | Combat Tags | Faction Tags |
|---|---|---|---|---|---|---|---|---|---|
| Marine | 2 | 5+ | 5+ | 2 | 4/7 | Core | Damage Dealer | Biological, Light, Ground | Terran |
| Marauder | 5 | 4+ | 6+ | 2 | 4/7 | Core | Tank | Armoured, Biological, Ground | Terran |
| Medic | 2 | 5+ | 5+ | 2 | 4/7 | Support | Lifesaver | Biological, Light, Ground | Terran |
| Jim Raynor | 8 | 4+ | 5+ | 2 | 7 | Hero | Tactician | Biological, Ground | Terran |
| Point Defense Drone | 3 | 6+ | 6+ | - | - | - | Lifesaver | Armoured, Flying, Mechanical | Terran, Raynor's Raiders |
| Raynor's Raider | 2 | 5+ | 5+ | 2 | 4/7 | Core | Damage Dealer | Biological, Light, Ground | Terran, Raynor's Raiders |
| Goliath | 10 | 4+ | - | 3 | 7 | Elite | Damage Dealer | Armoured, Mechanical, Ground | Terran |
| Siege Tank | 14 | 5+ | - | 2 | 7 | Elite | Damage Dealer | Armoured, Mechanical, Ground | Terran |

---

## Marine

**Movement Phase**
- **STIMPACK:** ACTIVE 1 CP This Unit suffers NON-LETHAL DAMAGE (2). This Unit gains BUFF Speed (3). Additionally, its C-14 Rifle and all Close Combat Weapons gain PRECISION (3).

**Weapons**

| Phase | Name | RNG | Target | RoA | Hit | Surge Type | S Dice | Dmg | Keyword |
|---|---|---|---|---|---|---|---|---|---|
| Combat | Strike | E | Ground | 1 | 5+ | - | - | 1 | - |
| Assault | C-14 Rifle | 12 | All | 2 | 3+ | Light | D3 | 1 | - |

**Upgrades**

| Upgrade | Phase | RNG | Target | RoA | Hit | Surge Type | S Dice | Dmg | Keyword | Card Text |
|---|---|---|---|---|---|---|---|---|---|---|
| AGG-12 (for C-14 Rifle) | Assault | 12 | Ground | 2 | 3+ | Armoured | D3 | 1 | LONG RANGE (18"), SPECIALIST | - |
| Bayonet (for Strike) | Combat | E | Ground | 2 | 5+ | - | - | 1 | - | - |
| Combat Shield | Movement | - | - | - | - | - | - | - | - | ACTIVE 1 CP: This Unit is always eligible to make an Evade Roll against any Close Combat Attack targeting it and any Damage from an Enemy Special Ability. |
| Grenades - Frag | Assault (passive) | - | - | - | - | - | - | - | - | PASSIVE: When this Unit makes a Ranged Attack with a C-14 Rifle and the target is Within 8", that weapon's S Dice is replaced by D6. |
| Rocket Launcher | Assault | 12 | Ground | 4 | 3+ | - | - | 1 | INDIRECT FIRE, LONG RANGE (18"), SIDEARM, SPECIALIST | - |
| Slugthrower | Assault (passive) | - | - | - | - | - | - | - | - | PASSIVE: When this Unit makes a Ranged Attack with a C-14 Rifle and the target is Within 8", that weapon gains ANTI-EVADE (1). |

---

## Marauder

**Movement Phase**
- **STIMPACK:** ACTIVE 1 CP This Unit suffers NON-LETHAL DAMAGE (2). This Unit gains BUFF Speed (3). Additionally, its Quad K12 and all Close Combat Weapons gain PRECISION (2).

**Reaction (Assault Phase)**
- **CONCUSSIVE SHELLS:** REACTION 1 CP When an Enemy declares a Charge against a Friendly Unit Within 8", that Enemy gains DEBUFF Speed (2).

**Weapons**

| Phase | Name | RNG | Target | RoA | Hit | Surge Type | S Dice | Dmg | Keyword |
|---|---|---|---|---|---|---|---|---|---|
| Combat | Strike | E | Ground | 2 | 4+ | - | - | 1 | - |
| Assault | Quad K12 | 12 | Ground | 3 | 3+ | Armoured | D3 | 1 | PIERCE Armoured (2) |

**Upgrades**

| Upgrade | Card Text |
|---|---|
| Kinetic Foam | PASSIVE: Increase this Unit's Hit Points characteristic by 1. |
| Laser Targeting Systems | PASSIVE: This Unit's Quad K12 weapon gains LONG RANGE (16"). |
| Veteran of Tarsonis | PASSIVE: While this Unit is Within 3" of a Mission Marker, its Armour characteristic is increased by 1. |

---

## Medic

**Any Phase**
- **LIFE SUPPORT:** REACTION 1 CP Use when another Friendly Biological Unit suffers Damage Within 4". Reduce the Total Damage before allocation by 1 for each model in this Unit that is Within 4" of the damaged Unit.
- **RESTORATION:** REACTION 1 CP Use when a Friendly Unit Within 4" receives a DEBUFF. Remove all DEBUFFS from it.

**Movement Phase**
- **MEDPACK:** ACTIVE 1 CP Select another Friendly Biological Unit Within 4". Resolve the HEAL (X) effect for the targeted Unit, where X is the number of models in this Unit that are Within 4" of the target Unit.
- **OPTICAL FLARE:** ACTIVE 2 CP Select one Enemy Unit Within 12". Until the End of the Round, apply DEBUFF Range (4) to that Unit's Ranged Weapons. That Unit cannot benefit from LONG RANGE.

**Weapons**

| Phase | Name | RNG | Target | RoA | Hit | Surge Type | S Dice | Dmg | Keyword |
|---|---|---|---|---|---|---|---|---|---|
| Combat | Strike | E | Ground | 1 | 5+ | - | - | 1 | - |

**Upgrades**

| Upgrade | Card Text |
|---|---|
| A-13 Flash Grenade Launcher | PASSIVE: Increase the Optical Flare special ability's Range to 16". |
| Advanced Medic Facilities | PASSIVE: This Unit's Supply Value counts as 0 when calculating the Supply Pool. |
| Stabilizer Medpacks | PASSIVE: When this Unit resolves a Life Support or Medpack ability, treat it as having 1 additional model Within Range for calculating that ability's effects. |

---

## Jim Raynor

**Any Phase**
- **COMMANDER:** PASSIVE Treat this Unit's Supply characteristic as increased by 1 for Controlling and Contesting Mission Markers, completing objectives, and resolving Disengage checks.
- **FREEDOM FIGHTERS:** PASSIVE The Supply Value of all Friendly Units Within 8" of this Unit cannot be reduced below 1 for Contesting Mission Markers and completing objectives.

**Movement Phase**
- **ORDERS:** ACTIVE X CP REPEATABLE. Select another Friendly Biological Unit Within 8", spend CP and apply one of the following effects:
  - 1 CP: That Unit's first used weapon gains the CRITICAL HIT (2).
  - 1 CP: That Unit ignores the Disengage penalty for the remainder of the Round.
  - 2 CP: Remove the Activation Marker from that Unit.

**Weapons**

| Phase | Name | RNG | Target | RoA | Hit | Surge Type | S Dice | Dmg | Keyword |
|---|---|---|---|---|---|---|---|---|---|
| Assault | Commando Rifle | 18 | All | 3 | 3+ | Armoured | D3 | 1 | BULKY, PIERCE Armoured (3) |
| Assault | "Justice" Revolver | 6 | Ground | 2 | 3+ | - | - | 2 | ANTI-EVADE (2), SIDEARM, PINPOINT |
| Combat | Bayonet | E | Ground | 2 | 4+ | Light | D3 | 1 | - |

**Upgrades**

| Upgrade | Phase | RNG | Target | RoA | Hit | Surge Type | S Dice | Dmg | Keyword |
|---|---|---|---|---|---|---|---|---|---|
| C-14 Rifle (for Commando Rifle) | Assault | 12 | All | 6 | 3+ | Light | D3+1 | 1 | BURST FIRE 8" (3) |

---

## Point Defense Drone

**Any Phase**
- **POINT DEFENSE LASER:** PASSIVE When another Friendly Unit Within 4" is targeted by a Ranged Attack without the INSTANT keyword, remove up to 2 dice from the Attack Pool. Then remove this Unit from the battlefield.
- **STRUCTURE:** PASSIVE This Unit cannot be Activated in any Phase and cannot perform actions. Additionally, its Current Supply Value is treated as 0, and it can never Control or Contest Mission Markers, ignoring the standard Zero Supply Exception. This Unit cannot be a target of an ability, unless stated otherwise.
- **GLIDING:** PASSIVE This model has DISPLACEMENT.

---

## Raynor's Raider

**Any Phase**
- **RAIDERS ROLL!:** PASSIVE When this Unit is nominated to deploy from Reserves, it may resolve its Stimpack ability with the CP cost reduced by 1 (to a minimum of 0).
- **RAPID REINFORCEMENTS:** PASSIVE When this Unit is nominated to deploy from Reserves, it may resolve the PLACE (10) effect from another Friendly Unit. No model may be set Within 8" of any Enemy model. This Unit's Activation ends.

**Movement Phase**
- **STIMPACK:** ACTIVE 1 CP This Unit suffers NON-LETHAL DAMAGE (2). This Unit gains BUFF Speed (3). Additionally, its C-14 Rifle and all Close Combat Weapons gain PRECISION (3).

**Weapons**

| Phase | Name | RNG | Target | RoA | Hit | Surge Type | S Dice | Dmg | Keyword |
|---|---|---|---|---|---|---|---|---|---|
| Combat | Bayonet | E | Ground | 2 | 5+ | - | - | 1 | - |
| Assault | C-14 Rifle | 12 | All | 2 | 3+ | Light | D3 | 1 | - |

**Passive weapon abilities (built in)**
- **SLUGTHROWER:** PASSIVE When this Unit makes a Ranged Attack with a C-14 Rifle and the target is Within 8", that weapon gains ANTI-EVADE (1).
- **GRENADES - FRAG:** PASSIVE When this Unit makes a Ranged Attack with a C-14 Rifle and the target is Within 8", that weapon's S Dice is replaced by D6.

---

## Goliath

**Any Phase**
- **ARES-CLASS TARGETING SYSTEM (upgrade):** PASSIVE This Unit's Autocannon and Underbelly Machine Gun weapons gain PRECISION (1).

**Movement Phase**
- **TARGET LOCK:** ACTIVE 1 CP Select one Enemy Unit Within 12". Whenever a Friendly Goliath Unit targets that enemy with an Autocannon, that weapon gains Surge Type: Light, Armoured, and S Dice: D3+1.

**Assault Phase**
- **INDOMITABLE:** PASSIVE While Engaged, this Unit may target and be targeted by Unengaged Enemy Units. In both cases, the defending Unit gains an Evade Roll against those attacks.
- **DEVASTATING CHARGE:** PASSIVE Immediately after this Unit completes a successful Charge, resolve the IMPACT (4) 3+ effect.

**Weapons**

| Phase | Name | RNG | Target | RoA | Hit | Surge Type | S Dice | Dmg | Keyword |
|---|---|---|---|---|---|---|---|---|---|
| Assault | Autocannon | 12 | Ground | 9 | 4+ | - | - | 1 | LONG RANGE (18") |
| Assault | Underbelly Machine Gun | 8 | Ground | 6 | 3+ | Light | D3 | 1 | PINPOINT, SIDEARM |
| Assault | Hellfire Missiles | 16 | Flying | 6 | 3+ | Light | D3 | 1 | ANTI-EVADE (1), SIDEARM |
| Combat | Stomp | E | Ground | 4 | 5+ | - | - | 1 | - |

**Upgrades (replace Hellfire Missiles)**

| Upgrade | RNG | Target | RoA | Hit | Surge Type | S Dice | Dmg | Keyword |
|---|---|---|---|---|---|---|---|---|
| Haywire Missiles | 12 | Ground | 3 | 3+ | Armoured | D3 | 1 | PIERCE Armoured (3), SIDEARM |
| Scatter Missiles | 18 | Ground | 6 | 5+ | Light | D3 | 1 | INDIRECT FIRE, LOCKED IN (6), LONG RANGE (24"), SIDEARM |

---

## Siege Tank

**Any Phase**
- **LARGE:** PASSIVE When this Unit's Leading Model moves, it cannot pass through physical gaps smaller than 3" wide, regardless of its size. If the Leading Model's path of travel passes through, or any model in this Unit ends its movement on a Size 0 or Size 1 Impassable Terrain piece (excluding Tokens) during any movement action, that terrain piece is immediately removed from the game.
- **HEAVY PLATING:** PASSIVE When this Unit resolves an Armour Roll, it gains TOUGH (1), provided it does not currently have the SIEGE MODE Status.

**Movement Phase**
- **MODE TRANSFORMATION:** ACTIVE 1 CP The active Unit gains or loses the SIEGE MODE Status. While this Unit has the SIEGE MODE Status, its Size characteristic is treated as if it was 3.
- **COORDINATED STRIKE:** ACTIVE 0 CP Target a Friendly Non-Engaged Unit on the battlefield (Line of Sight is not required). When this Unit resolves a Ranged Attack using the Shock Cannon weapon profile this Round, it may choose to ignore the weapon's standard Range characteristic. If it does, it may target an Enemy Unit that is Within 8" of, and Visible to, a model of the selected Friendly Unit, treating that model as the acting model.

**Assault Phase**
- **INDOMITABLE:** PASSIVE While Engaged, this Unit may target and be targeted by Unengaged Enemy Units. In both cases, the defending Unit gains an Evade Roll against those attacks.
- **POINT BLANK:** PASSIVE While this Unit has the SIEGE MODE Status, it cannot target Enemy Units it is Engaged with.
- **AFTERSHOCK ROUNDS:** PASSIVE When this Unit has the SIEGE MODE Status, its Damage characteristic is treated as equal to the Size characteristic of the current target Unit (to a minimum of 1).
- **DEVASTATING CHARGE:** PASSIVE Immediately after this Unit completes a successful Charge, resolve the IMPACT (4) 3+ effect.
- **SHAPED BLAST:** REACTION 0 CP Once per Game. When this Unit declares a Ranged Attack action. If this Unit has SIEGE MODE Status, its weapon gains PINPOINT and LOCKED IN (4).
- **SMART SHELLS:** REACTION 0 CP Once per Game. When this Unit declares a Ranged Attack action. If this Unit has SIEGE MODE Status, its weapon gains INDIRECT FIRE and LONG RANGE (24).

**Weapons**

| Phase | Name | RNG | Target | RoA | Hit | Surge Type | S Dice | Dmg | Keyword |
|---|---|---|---|---|---|---|---|---|---|
| Assault | Twin Cannon | 12 | Ground | 8 | 3+ | Armoured | D6 | 1 | PIERCE Armoured (2) |
| Assault | Shock Cannon | 18 | Ground | BT+4 | 4+ | Light, Armoured | BT | 1 | SIEGE MODE Status |
| Combat | Rolling Over | E | Ground | 2 | 2+ | - | - | 1 | - |

---

## Terran Tactical Cards

*Resource value printed on the card (a resource the card may provide, not a cost). Not every card prints one.*

| Card | Resource (CP) | Unique | Army Slot Requirement |
|---|---|---|---|
| Academy | 1 | Yes | 2 × Support |
| Barracks | 1 | No | 1 × Core |
| Barracks (Tech Lab) | 2 | Yes | 1 × Core, 1 × Elite |
| Barracks (Proxy) | 2 | Yes | 2 × Core |
| Engineering Bay | 1 | No | 1 × Core |
| Factory | 1 | No | 2 × Elite |
| Factory (Tech Lab) | 1 | Yes | 2 × Elite |
| Armory | 1 | No | 1 × Elite |
| Dropship | 1 | Yes | 1 × Core, 1 × Support |
| Supply Depot | 1 | Yes | 1 × Core, 1 × Elite, 1 × Hero |
| Orbital Command | 1 | Yes | 1 × Core |

**Academy**
- **ADVANCED TRAINING:** REACTION Once per Round, when a Friendly Support Unit activates a Special Ability that costs CP, resolve that ability with its CP cost reduced by 1 (to a minimum of 0). Do not Exhaust this card.

**Barracks**
- **GO! GO! GO!:** ACTIVE The active Biological Unit performs a 2" Move action. This does not count towards its action limit.

**Barracks (Tech Lab)**
- **GO! GO! GO!:** ACTIVE The active Biological Unit performs a 2" Move action. This does not count towards its action limit.
- **LET'S HAVE A BLAST!:** ACTIVE The active Biological Unit's first Ranged Weapon used gains ANTI-EVADE (1).

**Barracks (Proxy)**
- **GO! GO! GO!:** ACTIVE The active Biological Unit performs a 2" Move action. This does not count towards its action limit.
- **ARMED AND READY:** ACTIVE The active Biological Unit Deploys from any table edge that is not a player's Entry Edge. No model may be placed Within 10" of any Enemy model. This ability cannot be used if another Friendly Biological Unit has already been Deployed this Round.

**Engineering Bay**
- **INFANTRY ARMOR:** REACTION Use before a Friendly Biological Unit makes an Armour Roll. That Unit gains TOUGH (1) for this roll.
- **INFANTRY WEAPONS:** ACTIVE The active Biological Unit's first Ranged Weapon used gains CRITICAL HIT (1).

**Factory**
- **FIELD REPAIR:** ACTIVE The active Mechanical Unit resolves the HEAL (2) effect.

**Factory (Tech Lab)**
- **FIELD REPAIR:** ACTIVE The active Mechanical Unit resolves the HEAL (2) effect.
- **POUND 'EM FLAT!:** ACTIVE If the active Mechanical Unit has the Stationary Status, its first Ranged Weapon used gains PRECISION (2).

**Armory**
- **VEHICLE PLATING:** REACTION Use before a Friendly Mechanical Unit makes an Armour Roll. That Unit gains TOUGH (1) for this roll.
- **VEHICLE WEAPONS:** ACTIVE The active Mechanical Unit's first Ranged Weapon used gains CRITICAL HIT (1).

**Dropship**
- **STRAP IN!:** ACTIVE The active, Unengaged Ground Unit is returned to Reserves instead of performing an action.
- **READY FOR DUST-OFF:** ACTIVE Set a Faction Indicator anywhere on the battlefield more than 10" away from any Enemy model. At the End of the Round, the controlling player may Deploy one Ground Unit from Reserves in base-to-base contact with this Faction Indicator.

**Supply Depot**
- **ADDITIONAL SUPPLY DEPOTS:** ACTIVE The active Unit's Supply Value is improved by 1 for Controlling and Contesting Mission Markers and completing objectives.

**Orbital Command**
- **COMSAT STATION:** ACTIVE Select one table edge that is not a player's Entry Edge. Until the End of the Round, Enemy Units cannot Deploy from that edge.
- **SCANNER SWEEP:** ACTIVE Set a Faction Indicator anywhere on the battlefield. While Enemy Units are Within 6" of this Faction Indicator, they lose HIDDEN Status.

---

## Terran Faction Cards

**Terran Armed Forces**
- Unique, Terran faction
- Supply: 3 × Core, 1 × Elite, 1 × Support, 1 × Air
- CP: 1
- **TACTICAL RETREAT:** ACTIVE The active Unit ignores the Disengage penalty for the remainder of the Round.
- **TERRAN TENACITY:** ACTIVE Once per Game. Immediately claim the First Player Marker. No other player may claim the First Player Marker for the remainder of this Phase.

**Raynor's Raiders**
- Unique, Terran faction and Raynor's Raiders
- Supply: 3 × Core, 1 × Hero, 1 × Support, 1 × Air
- CP: 1
- **RAPID INGRESS:** ACTIVE Set a Friendly Point Defence Drone Unit anywhere on the battlefield, more than 1" away from any Enemy model. Remove this Unit at the End of the Round.
- **READY FOR PICKUP?:** ACTIVE Once Per Game. The active Unit resolves the PLACE (12) effect. Models set by this effect cannot be set up Within the Engagement Range of any Enemy Unit. This resolves instead of performing a standard action.
