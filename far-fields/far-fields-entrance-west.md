# Far Fields Entrance West (Bone_East_02b)

**Game ID:** Bone_East_02b

## Subrooms

- lower walkway
- upper right platforms
- lower right exit platform
- upper left platforms

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | right1 | upper right platforms | [Far Fields Wind Shaft (Bone_East_07)](far-fields-wind-shaft.md) | L1 | none |  |  |  |
| LR | right2 | lower right exit platform | [Far Fields Wind Shaft (Bone_East_07)](far-fields-wind-shaft.md) | L2 | none |  |  |  |
| L | left1 | lower walkway | [Far Fields Entrance East (Bone_East_02)](far-fields-entrance-east.md) | R | none |  |  |  |
| C | top3 | upper right platforms | [Far Fields Fort Lower Passage (Bone_East_16)](far-fields-fort-lower-passage.md) | F | none |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | vertical 1 | lower walkway | upper right platforms | run OR dash OR clawline OR sharpdart OR silk soar OR drifter's cloak OR faydown cloak |  |  |  |
| V1 | vertical 1 | upper right platforms | lower walkway | none (falling) |  |  |  |
| LC | lava crossing | lower walkway | lower right exit platform | run OR dash OR clawline OR sharpdart OR cling grip OR silk soar |  |  |  |
| LC | lava crossing | lower right exit platform | lower walkway | run OR dash OR clawline OR sharpdart OR cling grip |  |  |  |
| V2 | vertical 2 | lower walkway | upper left platforms | silk soar |  |  |  |
| V2 | vertical 2 | upper left platforms | lower walkway | none (falling) |  |  |  |
| UC | lower crossing | upper right platforms | upper left platforms | run OR dash OR clawline OR sharpdart OR silk soar OR drifter's cloak OR faydown cloak |  |  |  |
| UC | lower crossing | upper left platforms | upper right platforms | run OR dash OR clawline OR sharpdart OR silk soar OR drifter's cloak OR faydown cloak |  |  |  |
| V3 | vertical 3 | lower right exit platform | upper right platforms | cling grip OR silk soar |  |  |  |
| V3 | vertical 3 | upper right platforms | lower right exit platform | none (falling) |  |  |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| shell shard cache far fields 1 | lower walkway | none |  |  | Included |  |
