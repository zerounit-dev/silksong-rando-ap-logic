# Whiteward Entrance (Ward_01)

**Game ID:** Ward_01

**Contributors:** skai

## Subrooms

- Top Third
- Middle Third (Left)
- Middle Third (Right)
- Bottom Third (Left)
- Elevator Shaft
- Vertical Shaft (Upper)
- Vertical Shaft (Lower)
- Pit
- Top Right (Entrance)

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TL | Top Left | Top Third | [Choral Chambers Eastern Shaft (Song_05)](../choral-chambers/choral-chambers-eastern-shaft.md) | R1 | Nothing |  |  |  |
| TR | Top Right | Top Right (Entrance) | ward-05 | L | Nothing |  |  |  |
| ML | Middle Left | Middle Third (Left) | [Whiteward Map Room (Ward_02b)](whiteward-map-room.md) | R | Nothing |  |  |  |
| MR | Middle Right | Middle Third (Right) | [Whiteward Silkeater (Ward_04)](whiteward-silkeater.md) | L | Break Wall |  |  |  |
| BL | Bottom Left | Bottom Third (Left) | Unravelled Arena | R | Nothing |  |  |  |
| BR | Bottom Right | Vertical Shaft (Lower) | [Whiteward Descent Connection (Ward_03)](whiteward-descent-connection.md) | L | Nothing |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TES | Top to Elevator Shaft | Top Third | Elevator Shaft | White Key Used |  |  |  |
| TES | Top to Elevator Shaft | Elevator Shaft | Top Third | White Key Used |  |  |  |
| EBL | Elevator to Bottom Left | Elevator Shaft | Bottom Third (Left) | White Key Used |  |  |  |
| EBL | Elevator to Bottom Left | Bottom Third (Left) | Elevator Shaft | White Key Used |  |  |  |
| MLR | Middle Left to Right | Middle Third (Left) | Middle Third (Right) | Nothing (Jump) |  |  |  |
| MLR | Middle Left to Right | Middle Third (Right) | Middle Third (Left) | Nothing (Jump) |  |  |  |
| RVL | Right to Vertical Lower | Middle Third (Right) | Vertical Shaft (Lower) | Nothing (Fall) |  |  |  |
| RVL | Right to Vertical Lower | Vertical Shaft (Lower) | Middle Third (Right) | Cling Grip OR (Scuttlebrace AND (Flea Brew Stall OR Heal Stall OR Faydown)) OR Silk Soar |  |  |  |
| RVU | Right to Vertical Upper | Middle Third (Right) | Vertical Shaft (Upper) | Silk Soar OR (Faydown AND Cling Grip AND Precise Movement) |  |  |  |
| RVU | Right to Vertical Upper | Vertical Shaft (Upper) | Middle Third (Right) | Nothing (Fall) |  |  |  |
| VTR | Vertical to Top Right (Entrance) | Vertical Shaft (Upper) | Top Right (Entrance) | Silk Soar OR (Faydown AND Cling Grip AND Precise Movement) |  |  |  |
| VTR | Vertical to Top Right (Entrance) | Top Right (Entrance) | Vertical Shaft (Upper) | Nothing (Fall) |  |  |  |
| ETP | Elevator to Pit | Elevator Shaft | Pit | Set Elevator to Top |  |  |  |
| ETP | Elevator to Pit | Pit | Elevator Shaft | Cling Grip OR Scuttlebrace OR Silk Soar |  |  |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Silk Spool #15 | Pit | Nothing |  |  | Included |  |
| Whiteward Bench | Top Third | White Key |  |  | Included |  |
| Map Purchase: Whiteward | Vertical Shaft (Lower) | Nothing |  |  | Included |  |
