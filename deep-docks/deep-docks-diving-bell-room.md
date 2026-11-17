# Deep Docks Diving Bell Room (Dock_12)

**Game ID:** Dock_12

**Contributors:** herounit,Pyxl, Gallos

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | diving bell platform | ✓ |
| S2 | diving bell control room | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| D | door1 | diving bell platform | [Deep Docks Diving Bell Interior (Room_Diving_Bell)](deep-docks-diving-bell-interior.md) | L | unlock diving bell lock |  | Verified | ✓ |  |
| L | left1 | diving bell platform | [Deep Docks Magma Slug Tunnels (Dock_11)](deep-docks-magma-slug-tunnels.md) | R | none |  | Verified | ✓ | transition is not blocked by door in next room |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| CL | climb | diving bell platform | diving bell control room | silk soar OR easy scuttlebrace OR cling grip right OR (cling grip left AND faydown) |  | Verified | ✓ |  |
| CL | climb | diving bell control room | diving bell platform | none (falling) |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | diving bell lock | diving bell platform | have diving bell key |  | Verified | lock | ✓ |  |
| 2 | diving bell key | diving bell control room | after Ballow in Diving Bell Control Room |  | Verified | collectible | ✓ |  |
| 3 | Ballow in Diving Bell Control Room | diving bell control room | complete THE Ballow Move to Control Room |  | Verified | event | ✓ |  |

## Notes

dive bell thingy room wow.

## Room Images

### Connections

[![Connections for Deep Docks Diving Bell Room (Dock_12)](../00-annotations/deep-docks/deep-docks-diving-bell-room-connections.png)](../00-annotations/deep-docks/deep-docks-diving-bell-room-connections.png)

### Checks

[![Checks for Deep Docks Diving Bell Room (Dock_12)](../00-annotations/deep-docks/deep-docks-diving-bell-room-checks.png)](../00-annotations/deep-docks/deep-docks-diving-bell-room-checks.png)

### Scene

[![Scene for Deep Docks Diving Bell Room (Dock_12)](../00-annotations/deep-docks/deep-docks-diving-bell-room-scene.png)](../00-annotations/deep-docks/deep-docks-diving-bell-room-scene.png)
