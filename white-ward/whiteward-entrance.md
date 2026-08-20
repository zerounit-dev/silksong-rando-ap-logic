# Whiteward Entrance (Ward_01)

**Game ID:** Ward_01

## Subrooms

- Top Third
- Middle Third (Left)
- Middle Third (Right)
- Bottom Third (Left)
- Elevator Shaft
- Vertical Shaft (Upper)
- Vertical Shaft (Lower)

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TL | Top Left | Top Third | [Choral Chambers Eastern Shaft (Song_05)](../choral-chambers/choral-chambers-eastern-shaft.md) | R1 | Nothing |  |  |  |
| TR | Top Right | Vertical Shaft (Upper) | [Ward_05 (Ward_05)](ward-05.md) | L |  |  |  |  |
| ML | Middle Left | Middle Third (Left) | [Whiteward Map Room (Ward_02b)](whiteward-map-room.md) | R | Nothing |  |  |  |
| MR | Middle Right | Middle Third (Right) | [Whiteward Silkeater (Ward_04)](whiteward-silkeater.md) | L | Break Wall |  |  |  |
| BL | Bottom Left | Bottom Third (Left) | [Unravelled Arena (Ward_02)](unravelled-arena.md) | R | Nothing |  |  |  |
| BR | Bottom Right | Bottom Third (Left) | TODO |  |  |  |  |  |

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
| RVU | Right to Vertical Upper | Middle Third (Right) | Vertical Shaft (Upper) | Silk Soar |  |  |  |
| RVU | Right to Vertical Upper | Vertical Shaft (Upper) | Middle Third (Right) | Nothing (Fall) |  |  |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Silk Spool #15 | Elevator Shaft | Nothing |  |  | Included |  |
| Whiteward Bench | Top Third | White Key |  |  | Included |  |
| Map Purchase: Whiteward | Vertical Shaft (Lower) | Nothing |  |  | Included |  |
