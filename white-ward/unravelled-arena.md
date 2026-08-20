# Unravelled Arena (Ward_02)

**Game ID:** Ward_02

## Subrooms

- Vertical Left
- Surgery Tables (Right)
- Surgery Tables (Left)
- Key Shaft
- Unravelled Arena

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | Top | Vertical Left | [Whiteward Map Room (Ward_02b)](whiteward-map-room.md) | B | Silk Soar OR Faydown OR Cling Grip OR Scuttlebrace |  |  |  |
| R | Right | Surgery Tables (Right) | [Whiteward Entrance (Ward_01)](whiteward-entrance.md) | BL | Nothing |  |  |  |
| B | Bottom | Unravelled Arena | [Confession Toll (Under_08)](../underworks/confession-toll.md) | T | Beat Unravelled Arena |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SLV | Surgery Left to Vertical | Surgery Tables (Left) | Vertical Left | Ledge Grab OR Faydown OR Clawline OR Silk Soar OR (Proficient Movement AND Scuttlebrace) |  |  |  |
| SLV | Surgery Left to Vertical | Vertical Left | Surgery Tables (Left) | Nothing (Falling) |  |  |  |
| SRL | Surgery Right to Left | Surgery Tables (Right) | Surgery Tables (Left) | (Nothing AND NOT Key Inserted) OR (Faydown OR Clawline OR Sharpdart) |  |  |  |
| SKS | Surgery to Key Shaft | Surgery Tables (Left) | Key Shaft | Nothing (Falling) |  |  |  |
| SKS | Surgery to Key Shaft | Key Shaft | Surgery Tables (Left) | Silk Soar |  |  |  |
| KSA | Key Shaft to Arena | Key Shaft | Unravelled Arena | Nothing (Falling) |  |  |  |
| KSA | Key Shaft to Arena | Unravelled Arena | Key Shaft | Silk Soar |  |  |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| White Ward: Silk Heart | Unravelled Arena | Beat Unravelled Arena |  |  | Included |  |
