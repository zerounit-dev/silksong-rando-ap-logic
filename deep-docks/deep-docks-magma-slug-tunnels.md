# Deep Docks Magma Slug Tunnels (Dock_11)

## Subrooms

- left exit area
- right exit area
- slug tunnels

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | left exit area | [Deep Docks Diving Bell (Dock_12)](deep-docks-diving-bell.md) | L | right door switch must be flipped (from this side) |  |  |  |
| L | left1 | right exit area | [Deep Docks Lower East Shaft (Dock_15)](deep-docks-lower-east-shaft.md) | LR | none |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LD | left doorway | left exit area | right exit area | left door switch flipped |  |  |  |
| LD | left doorway | right exit area | left exit area | none (door switch is on this side) |  |  |  |
| LT | left tunnel | left exit area | slug tunnels | none (falling) |  |  |  |
| LT | left tunnel | slug tunnels | left exit area | cling grip |  |  |  |
| RT | right tunnel | right exit area | slug tunnels | none (falling) |  |  |  |
| RT | right tunnel | slug tunnels | right exit area | cling grip |  |  |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| left door switch | left exit area | none |  |  | Not included | opens the pathway between left/right |
| right door switch | right exit area | none |  |  | Not included | unlocks the right exit |
| beast shard deep docks | slug tunnels | none |  |  | Included | annoying af areas enabled OR ( silk soar AND magma bell AND blue slot ) |
