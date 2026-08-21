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
| B | Bottom | Lower Tunnels | Unravelled Arena | T | Nothing |  |  |  |
| R | Right | Pickup Section | [Whiteward Entrance (Ward_01)](whiteward-entrance.md) | ML | Break 4x Wall |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LUT | Lower to Upper Tunnels | Lower Tunnels | Upper Tunnels | Cling Grip or Scuttlebrace or Silk Soar |  |  |  |
| LUT | Lower to Upper Tunnels | Upper Tunnels | Lower Tunnels | Nothing (Falling) |  |  |  |
| UCT | Upper to Center Tunnels | Center Tunnels | Upper Tunnels | Cling Grip or Scuttlebrace or Silk Soar |  |  |  |
| UCT | Upper to Center Tunnels | Upper Tunnels | Center Tunnels | Nothing (Falling) |  |  |  |
| CTH | Center to Top Horizontal | Center Tunnels | Top Horizontal | Cling Grip or Scuttlebrace or Silk Soar |  |  |  |
| CTH | Center to Top Horizontal | Top Horizontal | Center Tunnels | Nothing (Falling) |  |  |  |
| TTP | Top to Pickup Section | Top Horizontal | Pickup Section | Nothing (Falling) |  |  |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Map: Whiteward | Pickup Section | Nothing |  |  | Included |  |
