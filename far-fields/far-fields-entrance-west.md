# Far Fields Entrance West (Bone_East_02b)

**Game ID:** Bone_East_02b

**Contributors:** herounit

## Subrooms

- lower walkway
- upper right platforms
- lower right exit platform
- upper left platforms
- check alcove

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | right1 | upper right platforms | [Far Fields Wind Shaft (Bone_East_07)](far-fields-wind-shaft.md) | L1 | none |  | Verified |  |
| LR | right2 | lower right exit platform | [Far Fields Wind Shaft (Bone_East_07)](far-fields-wind-shaft.md) | L2 | none |  | Verified |  |
| L | left1 | lower walkway | [Far Fields Entrance East (Bone_East_02)](far-fields-entrance-east.md) | R | none |  | Verified |  |
| C | top3 | upper right platforms | [Far Fields Fort Lower Passage (Bone_East_16)](far-fields-fort-lower-passage.md) | F | none |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | vertical 1 | lower walkway | upper right platforms | run OR clawline OR ( ledge grab AND ( dash OR sharpdart OR silk soar OR drifter's cloak OR faydown cloak |  | Verified |  |
| V1 | vertical 1 | upper right platforms | lower walkway | none (falling) |  | Verified |  |
| LC | lava crossing | lower walkway | lower right exit platform | run OR dash OR clawline OR sharpdart OR cling grip OR silk soar OR drifter's cloak  OR faydown cloak |  | Verified |  |
| LC | lava crossing | lower right exit platform | lower walkway | run OR dash OR clawline OR sharpdart OR cling grip OR silk soar OR drifter's cloak  OR faydown cloak |  | Verified |  |
| V2 | vertical 2 | lower walkway | upper left platforms | silk soar |  | Verified |  |
| V2 | vertical 2 | upper left platforms | lower walkway | none (falling) |  | Verified |  |
| UC | upper crossing | upper right platforms | upper left platforms | run OR dash OR clawline OR sharpdart OR silk soar OR drifter's cloak OR faydown cloak |  | Verified |  |
| UC | upper crossing | upper left platforms | upper right platforms | run OR dash OR clawline OR sharpdart OR silk soar OR drifter's cloak OR faydown cloak |  | Verified |  |
| V3 | vertical 3 | lower right exit platform | upper right platforms | cling grip OR silk soar |  | Verified |  |
| V3 | vertical 3 | upper right platforms | lower right exit platform | none (falling) |  | Verified |  |
| AC | alcove access | lower walkway | check alcove | ledge grab OR silk soar OR faydown cloak OR clawline OR shaman's crest |  | Verified | i love shamans pogo |
| AC | alcove access | check alcove | lower walkway | none (falling) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| shell shard cache far fields 1 | check alcove | none |  | Verified | Included |  |
