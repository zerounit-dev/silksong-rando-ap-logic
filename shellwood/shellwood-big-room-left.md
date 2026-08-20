# Shellwood Big Room Left (Shellwood_02)

**Game ID:** Shellwood_02

**Contributors:** Pyxl

## Subrooms

- Ceiling area
- Ground Left
- Platforms
- Ground Centre
- Ground Right

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | right1 | Ceiling area | [Shellwood Sister Splinter Bench (Shellwood_01b)](shellwood-sister-splinter-bench.md) | LL |  |  |  |  |
| LL | left2 | Ground Left | [shellwood Shakra (Shellwood_16)](shellwood-shakra.md) | R |  |  |  |  |
| UL | left3 | Platforms | [Shellwood Greyroot entrance (Shellwood_Witch)](shellwood-greyroot-entrance.md) | R |  |  |  |  |
| LR | right2 | Ground Right | [Shellwood Right Side Big room (Shellwood_01)](shellwood-right-side-big-room.md) | LL |  |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| EL | Elevator | Ground Centre | Ceiling area | Activated from Ceiling area |  |  |  |
| EL | Elevator | Ceiling area | Ground Centre | Activated from Ceiling area |  |  |  |
| RL | Right Lake | Ground Centre | Ground Right | ( Enemy Pogo AND Ledge Grab ) OR Dash OR Sprint OR clawline OR Beast Crest OR Faydown Cloak OR Drifters Cloak OR ( Swim AND Ledge Grab ) |  |  |  |
| RL | Right Lake | Ground Right | Ground Centre | ( Enemy Pogo AND Ledge Grab ) OR Dash OR Sprint OR clawline OR Beast Crest OR Faydown Cloak OR Drifters Cloak OR ( Swim AND Ledge Grab ) |  |  |  |
| LL | Left Lake | Ground Centre | Ground Left | ( Enemy Pogo AND Ledge Grab ) OR Dash OR Sprint OR clawline OR Beast Crest OR Faydown Cloak OR Drifters Cloak |  |  |  |
| LL | Left Lake | Ground Left | Ground Centre | None |  |  |  |
| LP | Left Platforms | Platforms | Ground Left | None |  |  |  |
| LP | Left Platforms | Ground Left | Platforms | ( Faydown Cloak AND ( Cling Grip OR ( Scuttle Brace AND Dash ) ) ) Silk Soar OR Enemy Pogo |  |  |  |
| CP | Central Platforms | Platforms | Ground Centre | None |  |  |  |
| CP | Central Platforms | Ground Centre | Platforms | ( Faydown Cloak AND Ledge Grab ) OR Silk Soar |  |  |  |
| RP | Right Platforms | Platforms | Ground Right | None |  |  |  |
| RP | Right Platforms | Ground Right | Platforms | Silk Soar |  |  |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Pollip Heart #6 | Platforms | Ledge Grab OR Silk Soar OR Faydown Cloak |  |  | Included |  |
