# Choral Chambers Flea Shaft (Song_11)

**Game ID:** Song_11

**Contributors:** samupo

## Subrooms

- Base Bottom
- Base Upper
- Top Section 1
- Top Section 2
- Top Section 3 Left
- Top Section 3 Right

- **Base Bottom:** Base Isolated from Top by one-way door available on Top
- **Base Upper:** Base Isolated from Top by one-way door available on Top

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| S3L | left1 | Top Section 3 Left | [Corridor to High Halls (Song_17)](corridor-to-high-halls.md) | R | none |  |  |  |
| S2L | left2 | Top Section 2 | [Choral Chambers Maintenance Tunnel (Song_15)](choral-chambers-maintenance-tunnel.md) | R | none |  |  |  |
| S3R | right2 | Top Section 3 Right | [High Halls Corridor (Hang_07)](high-halls-corridor.md) | L | ledge grab or faydown cloak or cling grip or silk soar |  |  |  |
| BLB | left4 | Base Upper | [Choral Chambers Spa (Song_10)](choral-chambers-spa.md) | R | breakable wall -must be opened from the other side |  |  |  |
| BR | right3 | Base Bottom | [Choral Chambers Eastern Shaft (Song_05)](choral-chambers-eastern-shaft.md) | L3 | none |  |  |  |
| BLT | left3 | Base Upper | [Choral Chambers Above Spa (Song_13)](choral-chambers-above-spa.md) | R | none |  |  |  |
| S1R | right1 | Top Section 1 | [Choral Chambers Dining Room (Song_09b)](choral-chambers-dining-room.md) | L | none |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| VB | Vertical Base | Base Bottom | Base Upper | silk soar faydown cloak or (cling grip and ((dash and ledge grab) or (drifter's cloak and ledge grab) or clawline)) |  |  |  |
| VB | Vertical Base | Base Upper | Base Bottom | none |  |  | falling |
| VL | Vertical Lever | Top Section 1 | Base Upper | none |  |  | one way, falling |
| V1 | Section 1 to Section 2 | Top Section 1 | Top Section 2 | silk soar or cling grip or (faydown cloak and ledge grab) |  |  |  |
| V2L | Section 2 to Section 3 Left | Top Section 2 | Top Section 3 Left | silk soar and (ledge grab or clawline or dash or sharpdart or faydown cloak) |  |  |  |
| V3R | Section 2 to Section 3 Right | Top Section 2 | Top Section 3 Right | silk soar or (cling grip and (clawline or dash)) |  |  |  |
| F3L | Section 3 Right falling | Top Section 3 Right | Top Section 2 | none |  |  | falling |
| F3R | Section 3 Left falling | Top Section 3 Left | Top Section 2 | none |  |  | falling |
| F2 | Section 2 falling | Top Section 2 | Top Section 1 | none |  |  | falling |
| H | Top Horizontal Traversal | Top Section 3 Right | Top Section 3 Left | ledge grab or clawline or drifter's cloak | TODO |  | check sharpdart |
| H | Top Horizontal Traversal | Top Section 3 Left | Top Section 3 Right | ledge grab or clawline or cling grip |  |  |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Flea: Choral Chambers - Walled Room | Top Section 2 | (cling grip and drifter's cloak) or silk soar |  |  | Included |  |
| Rosary Cache: Choral Chambers #14 | Base Upper | clawline or faydown cloak or (dash and ledge grab) | TODO |  | Included | check, probably better to split Base Upper into two zones since they can be gotten from BLT easier than from BLB |
| Rosary Cache: Choral Chambers #15 | Base Upper | clawline or faydown cloak or (dash and ledge grab) | TODO |  | Included | check, probably better to split Base Upper into two zones since they can be gotten from BLT easier than from BLB |
| Rosary Cache: Choral Chambers #16 | Base Upper | clawline or faydown cloak or (dash and ledge grab) | TODO |  | Included | check, probably better to split Base Upper into two zones since they can be gotten from BLT easier than from BLB |
