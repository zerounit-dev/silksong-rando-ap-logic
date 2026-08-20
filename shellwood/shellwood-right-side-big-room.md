# Shellwood Right Side Big room (Shellwood_01)

**Game ID:** Shellwood_01

**Contributors:** Pyxl

## Subrooms

- Ground Level Left
- Central Platforms
- Right Platforms
- Ground Level Right

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | right1 | Right Platforms | [Long Pin (Belltown_Room_shellwood)](long-pin.md) | L | Nest in Door broken |  |  |  |
| UL | left1 | Central Platforms | [Shellwood Sister Splinter Bench (Shellwood_01b)](shellwood-sister-splinter-bench.md) | LR | None |  |  |  |
| LR | right2 | Ground Level Right | [Bellhart Hallway to Shellwood (Belltown_07)](../bellhart/bellhart-hallway-to-shellwood.md) | L | None |  |  |  |
| LL | left2 | Ground Level Left | [Shellwood Big Room Left (Shellwood_02)](shellwood-big-room-left.md) | LR | Door opened from other side |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LA | Lake | Ground Level Left | Ground Level Right | ( Dash AND ( Sprint OR Drifters Cloak ) ) OR Clawline OR Sharpdart OR Swim OR ( Faydown Cloak AND Drifters Cloak ) |  |  |  |
| LA | Lake | Ground Level Right | Ground Level Left |  |  |  |  |
| C1 | Chasm 1 | Ground Level Left | Central Platforms | ( Ledge Grab AND ( Dash OR Drifters Cloak OR Beast Crest ) ) OR Clawline OR Cling Grip OR Silk Soar OR Sharpdart OR Faydown Cloak |  |  |  |
| C1 | Chasm 1 | Central Platforms | Ground Level Left | None |  |  |  |
| C2 | Chasm 2 | Central Platforms | Right Platforms | Ledge Grab OR Faydown Cloak OR Silk Soar OR Cling grip OR Dash OR Scuttlebrace OR Clawline  OR Sprint |  |  |  |
| C2 | Chasm 2 | Right Platforms | Central Platforms | None |  |  |  |
| C3 | Chasm 3 | Right Platforms | Ground Level Right | None |  |  |  |
| C3 | Chasm 3 | Ground Level Right | Right Platforms | Any movement abilty OR enemy pogo Silk Soar OR ( Cling Grip AND Faydown Cloak ) |  |  |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Collectable IFrayed Rosary String: Shellwoodtem Pickup | Central Platforms | None |  |  | Included |  |
| Pollip Heart #1 | Right Platforms | Cling Grip OR Silk Soar OR Scuttlebrace |  |  | Included |  |
| Shell shard Cache: Shellwood #? forgot the id 1 | Right Platforms | None | TODO |  | Included |  |
| Shell shard Cache: Shellwood #? forgot the id 2 | Right Platforms | None | TODO |  | Included |  |
| Shell shard Cache: Shellwood #? forgot the id 3 | Right Platforms | None | TODO |  | Included |  |
