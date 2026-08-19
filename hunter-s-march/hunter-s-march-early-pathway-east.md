# Hunter's March Early Pathway East (Ant_04)

**Game ID:** Ant_04

## Subrooms

- right exit platform
- right trap run
- upper right room
- left exit platform
- left upper platform
- left lower platform
- middle upper platform
- middle lower platform

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | right exit platform | [Hunter's March Shaft (Ant_14)](hunter-s-march-shaft.md) | L3 |  |  |  |  |
| L | left1 | left exit platform | [Hunter's March Map Shop (Ant_04_mid)](hunter-s-march-map-shop.md) | R |  |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| G1 | gap 1 | right exit platform | right trap run | can pogo OR run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart |  |  |  |
| G1 | gap 1 | right trap run | right exit platform | can pogo OR run OR dash OR faydown cloak OR clawline OR sharpdart |  |  | can't drifter's cloak this way |
| P1 | pogo 1 | right trap run | upper right room | can pogo OR silk soar |  |  |  |
| P1 | pogo 1 | upper right room | right trap run | none (falling) |  |  |  |
| G2 | gap 2 | right trap run | middle lower platform | can pogo OR run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart |  |  |  |
| G2 | gap 2 | middle lower platform | right trap run | can pogo OR run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart |  |  |  |
| V1 | vertical 1 | middle lower platform | middle upper platform | faydown cloak OR silk soar |  |  |  |
| V1 | vertical 1 | middle upper platform | middle lower platform | none (falling) |  |  |  |
| G3 | gap 3 | middle lower platform | left lower platform | can pogo OR clawline OR ( run AND dash AND faydown cloak ) |  |  |  |
| G3 | gap 3 | left lower platform | middle lower platform | can pogo OR clawline OR ( drifter's cloak AND faydown cloak ) |  |  |  |
| G4 | gap 4 | left lower platform | middle upper platform | run OR dash OR faydown cloak OR ( silk soar AND drifter's cloak ) |  |  |  |
| G4 | gap 4 | middle upper platform | left lower platform | none (falling) |  |  |  |
| G5 | gap 5 | middle upper platform | left upper platform | clawline OR sharpdart OR run AND ( dash OR drifter's cloak OR faydown cloak ) OR ( drifter's cloak AND ( faydown cloak OR silk soar ) ) |  |  |  |
| G5 | gap 5 | left upper platform | middle upper platform | run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart |  |  |  |
| V2 | vertical 2 | left lower platform | left upper platform | faydown cloak OR silk soar |  |  |  |
| V2 | vertical 2 | left upper platform | left lower platform | none (falling) |  |  |  |
| G6 | gap 6 | left lower platform | left exit platform | can pogo OR clawline OR drifter's cloak OR ( run AND dash ) OR ( run AND faydown cloak ) OR ( faydown cloak AND dash ) |  |  |  |
| G6 | gap 6 | left exit platform | left lower platform | can pogo OR clawline OR drifter's cloak OR ( run AND dash ) OR ( run AND faydown cloak ) OR ( faydown cloak AND dash ) |  |  |  |
| V3 | vertical 3 | left exit platform | left upper platform | cam pogo OR faydown cloak OR ( silk soar AND drifter's cloak ) |  |  |  |
| V3 | vertical 3 | left upper platform | left exit platform | none (falling) |  |  |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| shell shard cache hunters march 3 | upper right room | none |  |  | Included |  |
| shell shard cache hunters march 4 | upper right room | none |  |  | Included |  |
| silk webs x3 | upper right room | none |  |  | Not included | not yet randomized |
