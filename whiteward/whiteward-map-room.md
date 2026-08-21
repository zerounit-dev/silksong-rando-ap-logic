# Whiteward Map Room (Ward_02b)

**Game ID:** Ward_02b

**Contributors:** skai

## Subrooms

- Top Horizontal
- Pickup Section
- Lower Tunnels
- Upper Tunnels
- Center Tunnels

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | Bottom | Lower Tunnels | [Whiteward Unravelled Arena Room (Ward_02)](whiteward-unravelled-arena-room.md) | T | Nothing |  | Verified |  |
| R | Right | Pickup Section | [Whiteward Entrance (Ward_01)](whiteward-entrance.md) | ML | Break 4x Wall |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LUT | Lower to Upper Tunnels | Lower Tunnels | Upper Tunnels | Cling Grip OR Scuttlebrace OR Silk Soar |  | Verified |  |
| LUT | Lower to Upper Tunnels | Upper Tunnels | Lower Tunnels | Nothing (Falling) |  | Verified |  |
| UCT | Upper to Center Tunnels | Center Tunnels | Upper Tunnels | Cling Grip OR Scuttlebrace OR Silk Soar |  | Verified |  |
| UCT | Upper to Center Tunnels | Upper Tunnels | Center Tunnels | Nothing (Falling) |  | Verified |  |
| CTH | Center to Top Horizontal | Center Tunnels | Top Horizontal | Cling Grip OR Scuttlebrace OR Silk Soar |  | Verified |  |
| CTH | Center to Top Horizontal | Top Horizontal | Center Tunnels | Nothing (Falling) |  | Verified |  |
| TTP | Top to Pickup Section | Top Horizontal | Pickup Section | Nothing (Falling) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Map: Whiteward | Pickup Section | Nothing |  | Verified | Included |  |
