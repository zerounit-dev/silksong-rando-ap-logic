# Hunter's March Chapel Passage (Ant_20)

**Game ID:** Ant_20

## Subrooms

- left entrance
- crossing platform
- memory locket platform
- chapel entrance

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | left entrance | [Hunter's March Shaft (Ant_14)](hunter-s-march-shaft.md) | LR | none |  |  |  |
| D | door1 | chapel entrance | [Chapel of the Beast (Ant_19)](chapel-of-the-beast.md) | L | no beast crest OR beast chapel door override |  |  | door override is meant to cover when the randomizer ensures the door stays open |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LC | lower crossing | left entrance | crossing platform | can pogo OR run OR dash OR clawline OR drifter's cloak OR faydown cloak OR ( sharpdart AND silk heart ) |  |  |  |
| LC | lower crossing | crossing platform | left entrance | can pogo OR run OR dash OR clawline OR drifter's cloak OR faydown cloak OR ( sharpdart AND silk heart ) |  |  |  |
| MP | memory locket platform | crossing platform | memory locket platform | can pogo OR drifter's cloak OR clawline OR sharpdart OR ( run AND dash ) OR ( run AND faydown cloak ) OR ( faydown cloak AND dash ) |  |  |  |
| MP | memory locket platform | memory locket platform | crossing platform | can pogo OR drifter's cloak OR clawline OR sharpdart OR ( run AND dash ) OR ( run AND faydown cloak ) OR ( faydown cloak AND dash ) |  |  |  |
| WT | wind tunnel | crossing platform | chapel entrance | drifter's cloak OR silk soar |  |  |  |
| WT | wind tunnel | chapel entrance | crossing platform | none (falling) |  |  |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| memory locket | memory locket platform | none |  |  | Included | need to break a cage |
