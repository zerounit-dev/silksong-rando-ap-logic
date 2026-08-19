# Chapel of the Beast (Ant_19)

**Game ID:** Ant_19

**Contributors:** herounit

## Subrooms

- chapel entrance
- boss arena
- crest area
- right of boss fight

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | chapel entrance | [Hunter's March Chapel Passage (Ant_20)](hunter-s-march-chapel-passage.md) | D | none |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DS | door switch | chapel entrance | right of boss fight | drifter's cloak |  |  |  |
| DS | door switch | right of boss fight | chapel entrance | door switch flipped (other side) |  |  |  |
| BR | boss right entrance | right of boss fight | boss arena | none |  |  |  |
| BR | boss right entrance | boss arena | right of boss fight | boss defeated |  |  |  |
| BL | boss left entrance | crest area | boss arena | boss defeated |  |  |  |
| BL | boss left entrance | boss arena | crest area | boss defeated |  |  |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| crest beast | crest area | none |  |  | Included |  |
| savage beastly fight | boss arena | none |  |  | Not included |  |
| door switch | right of boss fight | none |  |  | Not included |  |
