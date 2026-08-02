# Bone Bottom

## Subrooms

- ground level
- sky
- upper right platforms
- upper middle platforms
- upper left platforms
- chapel roof

## Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| UL | upper left | upper left platforms | [bonegrave](./bonegrave.md) -UR | none |
| LL | lower left | ground level | [bonegrave](./bonegrave.md) -LR | door opened from other side |
| DR | descend rope | ground level | [ruined chapel](./ruined-chapel.md) -AR | none |
| F | floor | ground level | [moss grotto west](./moss-grotto-west.md) -C | none |
| BD | bellway door | ground level | [bone bottom bellway](./bone-bottom-bellway.md) -BD | none |
| LR | lower right | ground level | TODO | none |
| UR | upper right | upper right platforms | TODO | none |
| RC | right ceiling | upper right platforms | TODO | none |
| LC | left ceiling | sky | TODO | silk soar |

## Subroom Connections

| source | alias | name | destination | requirements |
| --- | --- | --- | --- | --- |
| ground level | CC | climb chapel | chapel roof | silk soar OR ( cling grip AND ( LL door NOT opened OR faydown cloak ) ) |
| ground level | SM | soar to middle platforms | upper middle platforms | silk soar |
| ground level | SS | soar to sky exit | sky | silk soar |
| ground level | SR | soar to right platforms | upper right platforms | silk soar |
| ground level | EV | elevator | upper right platforms | elevator switch flipped |
| chapel roof | CC | climb chapel | ground level | none |
| chapel roof | CR | climb roof | upper left platforms | silk soar OR cling grip |
| upper left platforms | CR | climb roof | chapel roof | none |
| upper middle platforms | MD | middle platform drift | chapel roof | drifter's cloak OR clawline OR ( dash + sharpdart ) |
| upper middle platforms | SM | soar to the middle platforms | ground level | none |
| upper middle platforms | CL | clawline across the sky | upper right platforms | clawline |
| upper right platforms | CL | clawline across the sky | upper middle platforms | clawline |
| upper right platforms | SR | soar to right platforms | ground level | none |
| sky | DL | sky drift to right platforms | upper right platforms | drifter's cloak OR horizontal movement tech |
| sky | DR | sky drift to middle platforms | upper middle platforms | drifter's cloak OR horizontal movement tech |
| sky | SS | soar to the sky | ground level | none |

## Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| bone bottom mossberry | upper right platforms | none |  |
| rosary cache bone bottom 8 | upper right platforms | none |  |
| rosary cache bone bottom 9 | upper right platforms | none |  |
| weaver effigy camora moss grotto | upper middle platforms | none |  |
| rosary dish | upper middle platforms | none | NOT CURRENTLY RANDOMIZED |
| mask shard pebbs shop grindle act 3 | ground level |  | pebb's shop |
| simple key | ground level |  | pebb's shop |
| bone bottom shop craft metal | ground level |  | pebb's shop |
| magnetite broach | ground level |  | pebb's shop |
| wish bone bottom repairs | ground level |  |  |
| wish a life saving bridge | ground level |  |  |
| wish an icon of hope | ground level |  |  |
| wish garb of the pilgrims | ground level |  |  |
| wish volatile flintbeetles | ground level |  |  |
| wish the terrible tyrant | ground level |  |  |
| wish bone bottom supplies | ground level |  |  |
| boss skull tyrant | ground level |  |  |
| shell shard cache bone bottom | ground level |  | is this breaking the statue? STILL MARKED AS ??? ON TRACKER |
