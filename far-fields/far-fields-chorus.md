# Far Fields Chorus (Bone_East_08)

**Game ID:** Bone_East_08

## Subrooms

- left exit area
- lower left side
- upper left alcove
- boss arena
- upper right alcove
- lower right side

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | left exit area | [Far Fields Wind Shaft (Bone_East_07)](far-fields-wind-shaft.md) | R3 | none |  |  |  |
| R | right1 | lower right side | [Far Fields Pinstress Room (Bone_East_09)](far-fields-pinstress-room.md) | LL | none |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | vertical 1 | lower left side | left exit area | silk soar OR drifter's cloak |  | Verified |  |
| V1 | vertical 1 | left exit area | lower left side | none (falling) |  | Verified |  |
| G1 | gap 1 | left exit area | upper left alcove | drifter's cloak OR clawline |  | Verified | one way only |
| V2 | vertical 2 | lower left side | upper left alcove | silk soar OR drifter's cloak |  | Verified |  |
| V2 | vertical 2 | upper left alcove | lower left side | none (falling) |  | Verified |  |
| BL | boss left entrance | lower left side | boss arena | none | TODO |  | unsure what starts the boss fight but whatever |
| BL | boss left entrance | boss arena | lower left side | pre-boss fight trigger OR defeat boss | TODO |  |  |
| BR | boss right entrance | lower right side | boss arena | none | TODO |  | unsure what starts the boss fight but whatever |
| BR | boss right entrance | boss arena | lower right side | pre-boss fight trigger OR defeat boss | TODO |  |  |
| V3 | vertical 3 | lower right side | upper right alcove | drifter's cloak OR ( silk soar AND ( cling grip AND ( faydown cloak OR dash OR clawline OR sharpdart ) OR  scuttlebrace ) ) |  | Verified |  |
| V3 | vertical 3 | upper right alcove | lower right side | none (falling) |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| boss fourth chorus | boss arena | ??? | TODO |  | Included | what triggers this fight? |
| rosary cache far fields 2 | upper left alcove | none |  | Verified | Included |  |
| free silk | upper right alcove | none |  | Verified | Included | NOT CURRENTLY RANDOMIZED |
