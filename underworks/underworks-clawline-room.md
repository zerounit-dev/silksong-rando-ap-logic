# Underworks Clawline Room (Under_18)

**Game ID:** Under_18

**Contributors:** Rebel, Cry

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | Clawline Statue | ✓ |
| S2 | Blocked Off Corridor Left | ✓ |
| S3 | Shard Bundle Check | ✓ |
| S4 | Main Side Door | ✓ |
| S5 | Arena | ✓ |
| S6 | Blocked Off Corridor Top | ✓ |
| S7 | Metalwork Barge | ✓ |
| S8 | Clawline Entrance Rafter | ✓ |
| S9 | Clawline Shrine Rafter | ✓ |
| S10 | Cogfly Airspace 1 | ✓ |
| S11 | Cogfly Airspace 2 | ✓ |

- **Arena:** Arena activated by Clawline Ring

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TR | Top Right | Arena | [Underworks Twelfth Architect (Under_17)](underworks-twelfth-architect.md) | BR | (Clear Underworks Clawline Gauntlet AND (Cling Grip OR Scuttlebrace OR Silk Soar OR (Faydown Cloak AND (Easy Shaman Pogo OR Easy Beast Charge)))) |  | Verified | ✓ |  |
| L | Left | Blocked Off Corridor Left | [Underworks East Shaft (Under_13)](underworks-east-shaft.md) | MR | Nothing. |  | Verified | ✓ |  |
| R | Right | Main Side Door | [Underworks Clawline Entrance (Under_19c)](underworks-clawline-entrance.md) | TL | Invalid |  | Verified | ✓ |  |
| TL | Top Left | Blocked Off Corridor Top | [Underworks Twelfth Architect (Under_17)](underworks-twelfth-architect.md) | BL | Nothing. |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| STB | Shrine to Barge | Metalwork Barge | Clawline Statue | Clawline Left x 3  OR Sharpdart x 3 OR Run OR Faydown Cloak OR (Medium Needle Strike AND (Cling Grip Left OR Ledge Grab Left)) OR (Proficient Movement AND Flea Brew AND (Easy Architect Needle Strike OR Architect Slash Left OR Easy Beast Pogo OR ((Easy Flea Brew Stall OR Easy [Wanderer, Reaper] Needle Strike) AND Cling Grip Left) OR (Easy Hunter Pogo AND Cling Grip Left))) |  | Verified | ✓ |  |
| STB | Shrine to Barge | Clawline Statue | Metalwork Barge | Clawline Right x 3  OR Sharp Dart x 3  OR Faydown Cloak  OR Drifter's Cloak  OR Run OR (Easy Architect Pogo AND (Architect Slash Right OR Ledge Grab Right)) OR Easy Beast Pogo OR Easy [Beast, Architect] Needle Strike OR (Flea Brew AND ((Easy Flea Brew Stall OR Easy [Wanderer, Reaper, Witch] Needle Strike) OR Easy Hunter Pogo)) |  | Verified | ✓ |  |
| LST | Left Side Travel | Blocked Off Corridor Left | Blocked Off Corridor Top | Silk Soar OR Cling Grip Either OR Easy Scuttlebrace OR (Faydown Cloak AND Ledge Grab Either) |  | Verified | ✓ |  |
| LST | Left Side Travel | Blocked Off Corridor Top | Blocked Off Corridor Left | Nothing. (Fall) |  | Verified | ✓ |  |
| AP | Arena Path | Clawline Shrine Rafter | Arena | (Faydown Cloak AND (Sharp Dart OR Clawline Right OR ((Run AND Dash Right AND (Medium Architect Fast Needle Strike OR (Flea Brew AND Easy Flea Brew Stall))) AND (Ledge Grab Right OR Cling Grip Right)))) |  | Verified | ✓ | getting up here without clawline is worthless unless cause the exit needs clawline anyway lmao |
| AP | Arena Path | Arena | Clawline Shrine Rafter | Clawline Left OR Sharp Dart OR Drifter's Cloak |  | Verified | ✓ |  |
| SP | Shard Path | Clawline Entrance Rafter | Main Side Door | Clawline Right OR Run OR Drifter's Cloak |  | Verified | ✓ |  |
| SP | Shard Path | Main Side Door | Clawline Entrance Rafter | Clawline Left OR (Clawline Right AND (Sharpdart OR (Run AND (Dash Left OR Drifter's Cloak OR Faydown Cloak OR Easy Beast Pogo OR Medium [Voltvessels, Plasmium] Stall x 2 OR (Flea Brew AND (Easy Flea Brew Stall OR (Easy Witch Pogo AND Ledge Grab Left))))))) OR (Faydown Cloak AND (Sharp Dart OR (Dash Left AND (Ledge Grab Left OR Cling Grip Left)))) |  | Verified | ✓ | same thing as the arena path but you go left at the end instead of right |
| CLB | Clawline to Barge | Main Side Door | Metalwork Barge | run  OR easy [hunter, architect, shaman, beast] pogo OR easy naked pogo OR architect slash left OR easy [witch, architect, beast, wanderer] needle strike OR clawline left OR sharpdart OR drifter's cloak  OR faydown cloak OR flea brew |  | Verified | ✓ | Adding new subroom on the understanding this and the surrounding platforms in the molten steel have been updated to remain after clawline shrine's been picked up. Will adjust if not the case. - Cry 11/24 1:48 CST |
| CLB | Clawline to Barge | Metalwork Barge | Main Side Door | run OR easy beast pogo OR clawline right OR sharpdart OR drifter's cloak OR faydown cloak OR flea brew OR easy [beast, architect] needle strike OR (architect slash right AND ledge grab right) OR easy [voltvessels, plasmium] stall |  | Verified | ✓ |  |
| CSS | check silk soar | Clawline Statue | Shard Bundle Check | silk soar |  | Verified | ✓ |  |
| CSS | check silk soar | Shard Bundle Check | Clawline Statue | none (falling) |  | Verified | ✓ |  |
| RSC | rafter shard crossing | Clawline Shrine Rafter | Shard Bundle Check | (run AND (clawline left AND (ledge grab left OR cling grip left)))  OR (faydown cloak AND (clawline left OR (run AND dash left AND (ledge grab left OR cling grip left)) OR drifter's cloak)) |  | Verified | ✓ |  |
| RSC | rafter shard crossing | Shard Bundle Check | Clawline Shrine Rafter | run AND (clawline right OR sharpdart OR (dash right AND faydown cloak)) |  | Verified | ✓ |  |
| STA | soar to arena | Metalwork Barge | Arena | silk soar AND (proficient movement OR dash right OR easy [hunter, architect, shaman, reaper, beast, witch] pogo OR faydown cloak OR flea brew OR drifter's cloak) |  | Verified | ✓ |  |
| STA | soar to arena | Arena | Metalwork Barge | none (falling) |  | Verified | ✓ |  |
| A1S | airspace 1 shard clawline | Cogfly Airspace 1 | Shard Bundle Check | Clawline Left AND intended pogo off Cogwork Underfly |  | Verified | ✓ |  |
| A1S | airspace 1 shard clawline | Shard Bundle Check | Cogfly Airspace 1 | Clawline Right AND intended pogo off Cogwork Underfly |  | Verified | ✓ |  |
| A1R | airspace 1 rafter clawline | Clawline Shrine Rafter | Cogfly Airspace 1 | Clawline Left AND intended pogo off Cogwork Underfly |  | Verified | ✓ |  |
| A1R | airspace 1 rafter clawline | Cogfly Airspace 1 | Clawline Shrine Rafter | Clawline Left AND intended pogo off Cogwork Underfly |  | Verified | ✓ |  |
| RUG | Rafter Union Gap | Clawline Entrance Rafter | Clawline Shrine Rafter | Run AND ((Faydown Cloak AND Dash Left AND (Drifter's Cloak OR Hard Beast Needle Strike OR (Hard Architect Needle Strike AND Ledge Grab Right))) OR ((Clawline Left x 2 OR Sharpdart x 2) AND ((Drifter's Cloak AND (Ledge Grab Left OR Cling Grip Left)) OR Faydown Cloak))) |  | Verified | ✓ |  |
| RUG | Rafter Union Gap | Clawline Shrine Rafter | Clawline Entrance Rafter | (Drifter's Cloak AND (Run OR Dash Right OR Easy [Architect, Beast, Shaman] Pogo OR Easy [Architect, Beast, Reaper, Wanderer] Needle Strike OR Easy [Plasmium, Voltvessels, FLintslate, Pale Nails, Rune Rage, Air Bind, Cross Stitch, Flea Brew] Stall OR Flea Brew)) OR (Clawline Right x 2 OR Sharpdart x 2) OR (Run AND (Dash Right AND Faydown Cloak AND (Easy [Architect, Beast] Pogo OR Easy [Architect, Beast, Wanderer, Reaper] Needle Strike))) |  | Verified | ✓ |  |
| SRG | Shrine Rafter Gap | Clawline Statue | Clawline Shrine Rafter | Cling Grip Left AND (Clawline Right x 3 AND (Dash Right OR Drifter's Cloak OR Proficient Movement) AND Faydown Cloak) |  | Verified | ✓ |  |
| SRG | Shrine Rafter Gap | Clawline Shrine Rafter | Clawline Statue | (Run AND (Dash Right OR Faydown Cloak OR Easy [Hunter, Reaper] Pogo OR Easy Wanderer Needle Strike)) OR Clawline Left OR Easy [Architect, Beast] Pogo |  | Verified | ✓ |  |
| A2E | Airspace 2 Entrance Clawline | Clawline Entrance Rafter | Cogfly Airspace 2 | (Clawline Left x 2 AND Intended Pogo Off Cogwork Underfly)  OR (Run AND Faydown Cloak AND Easy Pogo Off Cogwork Underfly) |  | Verified | ✓ |  |
| A2E | Airspace 2 Entrance Clawline | Cogfly Airspace 2 | Clawline Entrance Rafter | (Clawline Right AND Intended Pogo Off Cogwork Underfly) |  | Verified | ✓ |  |
| A2S | Airspace 2 Shrine Clawline | Cogfly Airspace 2 | Clawline Shrine Rafter | (Clawline Left x 2 AND Intended Pogo Off Cogwork Underfly) |  | Verified | ✓ |  |
| A2S | Airspace 2 Shrine Clawline | Clawline Shrine Rafter | Cogfly Airspace 2 | (Clawline Right AND Intended Pogo Off Cogwork Underfly) |  | Verified | ✓ |  |
| A2A | Airspace 2 Arena Clawline | Cogfly Airspace 2 | Arena | (Clawline Right x 2 AND Intended Pogo Off Cogwork Underfly) |  | Verified | ✓ |  |
| A2A | Airspace 2 Arena Clawline | Arena | Cogfly Airspace 2 | (Clawline Left AND Intended Pogo Off Cogwork Underfly) |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Clawline Pickup | Clawline Statue | Nothing. |  | Verified | collectible | ✓ |  |
| 2 | Underworks: Shard Bundle #2 | Shard Bundle Check | Nothing. |  | Verified | collectible | ✓ |  |
| 3 | Clawline Ring | Arena | Clawline Either |  | Verified | switch | ✓ |  |
| 4 | Silk Spools | Clawline Entrance Rafter | none (attack) |  | Verified | resource | ✓ |  |
| 5 | Underworks Clawline Gauntlet | Arena | Activate Clawline Ring AND Combat Requirements |  | Verified | gauntlet | ✓ |  |
| 6 | Cogwork Underfly 1 | Cogfly Airspace 2 | Prereq Clawline Pickup |  | Verified | enemy | ✓ | Spawn conditions: hasHarpoonDash=true |
| 7 | Cogwork Underfly 2 | Cogfly Airspace 1 | Prereq Clawline Pickup |  | Verified | enemy | ✓ | Spawn conditions: hasHarpoonDash=true |
| 8 | Cogwork Underfly 3 | Cogfly Airspace 2 | Prereq Clawline Pickup |  | Verified | enemy | ✓ | Spawn conditions: hasHarpoonDash=true |
| 9 | Underscrub 1 | Arena | none |  | Verified | enemy | ✓ |  |
| 10 | Undersweep 1 | Arena | none |  | Verified | enemy | ✓ |  |
| 11 | Underloft 1 | Arena | none |  | Verified | enemy | ✓ |  |
| 12 | Underpoke 1 | Arena | none |  | Verified | enemy | ✓ |  |
| 13 | Undercrank 1 | Arena | none |  | Verified | enemy | ✓ |  |
| 14 | Cogwork Hauler 1 | Arena | none |  | Verified | enemy | ✓ |  |
| 15 | Cogwork Hauler 2 | Arena | none |  | Verified | enemy | ✓ |  |
| 16 | Cogwork Hauler 3 | Arena | none |  | Verified | enemy | ✓ |  |
| 17 | Cogwork Hauler 4 | Arena | none |  | Verified | enemy | ✓ |  |
| 18 | Cogwork Hauler 5 | Arena | none |  | Verified | enemy | ✓ |  |
| 19 | Underpoke 2 | Clawline Shrine Rafter | none |  | Verified | enemy | ✓ |  |
| 20 | Void Mass 1 | Clawline Statue | Black Thread World Spawn |  | Verified | enemy | ✓ |  |
| 21 | Underpoke 3 | Clawline Statue | Black Thread World Spawn |  | Verified | enemy | ✓ |  |
| 22 | Underloft 2 | Clawline Statue | Black Thread World Spawn |  | Verified | enemy | ✓ |  |

## Notes

Left and right sides of this room are not connected.

Need confirmation (and changes to the room) on the vanilla approach to Clawline in underworks/underworks-clawline-room
The left and top blocked-off corridors are reachable without Clawline or Faydown, but neither connects to the statue. Its only incoming route is from Main Side Door and requires Clawline or Faydown, creating a cycle when skills stay vanilla. Which connection and requirements are missing 

Also the room has been modified that R can be left even after entering/obtaining Clawline and the platforms also don't sink anymore

-Moriko

## Room Images

### Connections

[![Connections for Underworks Clawline Room (Under_18)](../00-annotations/underworks/underworks-clawline-room-connections.png)](../00-annotations/underworks/underworks-clawline-room-connections.png)

### Checks

[![Checks for Underworks Clawline Room (Under_18)](../00-annotations/underworks/underworks-clawline-room-checks.png)](../00-annotations/underworks/underworks-clawline-room-checks.png)

### Scene

[![Scene for Underworks Clawline Room (Under_18)](../00-annotations/underworks/underworks-clawline-room-scene.png)](../00-annotations/underworks/underworks-clawline-room-scene.png)
