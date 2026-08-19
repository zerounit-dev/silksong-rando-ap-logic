# Far Fields Bellway (Bellway_03)

**Game ID:** Bellway_03

**Contributors:** herounit

## Subrooms

- bellway
- hidden area
- right exit area

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | bellway | [Far Fields Pinstress Attic (Bone_East_09b)](far-fields-pinstress-attic.md) | L |  |  |  |  |
| L | left1 | bellway | [Far Fields Wind Shaft (Bone_East_07)](far-fields-wind-shaft.md) | R2 |  |  |  |  |
| BB | door_fastTravelExit | bellway | [Bellway Menu](../fast-travel/bellway-menu.md) | FF | bellway pay gate unlocked |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| HP | hidden pathway | bellway | hidden area | bellway pay gate unlocked |  |  |  |
| HP | hidden pathway | hidden area | bellway | bellway pay gate unlocked |  |  |  |
| TP | thorn path | hidden area | right exit area | ( silk soar AND (  ledge grab OR cling grip OR scuttlebrace ) ) OR ( faydown cloak AND cling grip ) OR ( drifter's cloak AND ( cling grip OR scuttlebrace ) ) |  |  |  |
| TP | thorn path | right exit area | hidden area | silk soar OR drifter's cloak |  |  |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| bench |  | bench pay gate unlocked |  |  | Not included |  |
| bench pay gate |  | none |  |  | Not included |  |
| bellway pay gate |  | none |  |  | Included |  |
