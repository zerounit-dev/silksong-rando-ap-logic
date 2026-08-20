# Shellwood Sister Splinter Bench (Shellwood_01b)

**Game ID:** Shellwood_01b

**Contributors:** Pyxl

## Subrooms

- Above Arena
- Arena
- Bench Toll
- Elevator Platform
- Upper Main
- Upper Hidden

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | right1 | Elevator Platform | [Shellwood Upper Bellhart Entrance (Shellwood_13)](shellwood-upper-bellhart-entrance.md) | LL | None |  |  |  |
| LR | right2 | Bench Toll | [Shellwood Right Side Big room (Shellwood_01)](shellwood-right-side-big-room.md) | UL | None |  |  |  |
| MR | right3 | Upper Hidden | [Shellwood Hidden Bellhart Connection (Shellwood_15)](shellwood-hidden-bellhart-connection.md) | L | Door Opened from other side |  |  |  |
| UL | left1 | Upper Main | [Shellwood Flower Pogo Upper Hall (Shellwood_20)](shellwood-flower-pogo-upper-hall.md) | R | None |  |  |  |
| LL | left2 | Above Arena | [Shellwood Big Room Left (Shellwood_02)](shellwood-big-room-left.md) | UR | None |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| AD | Arena Drop | Above Arena | Arena | None |  |  |  |
| AD | Arena Drop | Arena | Above Arena | Silk Soar |  |  |  |
| AE | Arena Exit | Arena | Bench Toll | Ledge Grab OR ( Dash AND Scuttlebrace ) OR Clawline OR Cling Grip OR Faydown Cloak OR Silk Soar |  |  |  |
| AE | Arena Exit | Bench Toll | Arena | None |  |  |  |
| CL1 | Climb 1 | Bench Toll | Upper Hidden | ( Cling Grip AND ( Clawline OR Dash OR Sharpdart OR Drifters Cloak OR Faydown Cloak OR Beast Crest ) OR Silk Soar |  |  |  |
| CL1 | Climb 1 | Upper Hidden | Bench Toll | None |  |  |  |
| EL | Elevator | Bench Toll | Elevator Platform | Elevator activated |  |  |  |
| EL | Elevator | Elevator Platform | Bench Toll | Elevator activated |  |  |  |
| CL2 | Climb 2 | Upper Main | Bench Toll | None |  |  |  |
| CL2 | Climb 2 | Bench Toll | Upper Main | Cling Grip OR Silk Soar |  |  |  |
| HP | Hidden Path | Upper Main | Upper Hidden | None |  |  |  |
| HP | Hidden Path | Upper Hidden | Upper Main | None |  |  |  |
| EP | Elevator Platform | Upper Main | Elevator Platform | None |  |  |  |
| EP | Elevator Platform | Elevator Platform | Upper Main | Ledge Grab OR ( Dash AND Scuttlebrace ) OR Clawline OR Cling Grip OR Faydown Cloak OR Silk Soar |  |  |  |
| CL3 | Climb 3 | Above Arena | Bench Toll | Cling Grip OR Silk Soar OR ( Dash AND Scuttlebrace ) |  |  |  |
| CL3 | Climb 3 | Bench Toll | Above Arena | None |  |  |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Rosary String: Shellwood #1 | Upper Hidden | None |  |  | Included |  |
| Bench | Bench Toll | None |  |  | Included |  |
