# Wormways Shaft

## Subrooms

- lower area
- middle platform area
- upper platform area

## Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| LR | lower right | lower area | [wormways craggler hallway](./wormways-craggler-hallway.md) -L | none |
| LL | lower left | lower area | [wormways middle](./wormways-middle.md) -R | door unlocked |
| UL | upper left | upper platform area | [wormways upper west](./wormways-upper-west.md) -R | breakable wall -must be opened from the other side (verified) |
| UR | upper right | middle platform area | [wormways upper east](./wormways-upper-east.md) -L | none |
| MR | middle right | middle platform area | [wormways flea rescue](./wormways-flea-rescue.md) -L | none |

## Subroom Connections

| alias | name | source | destination | requirements |
| --- | --- | --- | --- | --- |
| DS | door switch | platform area | lower area | none (door switch is on this side) |
| DS | door switch | lower area | platform area | door switch needs to be flipped |
| CG | platform gaps | middle platform area | upper platform area | silk soar OR ( cling grip AND (faydown cloak or horizontal movement tech) ) |
| CG | platform gaps | upper platform area | middle platform area | none (falling) |

## Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| use simple key on lock | lower area | simple key | unlocks the LL room exit |
| mask shard | lower area | none |  |
| frayed rosary string wormways | upper platform area | cling grip OR silk soar |  |
