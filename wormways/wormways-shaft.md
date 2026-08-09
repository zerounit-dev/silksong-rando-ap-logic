# Wormways Shaft (Crawl_02)

## Subrooms

- lower area
- middle platform area
- upper platform area

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LR | lower right | lower area | [Wormways Craggler Hallway (Crawl_04)](wormways-craggler-hallway.md) | L | none |  |  |  |
| LL | lower left | lower area | [Wormways Middle (Crawl_03b)](wormways-middle.md) | R | door unlocked |  |  |  |
| UL | upper left | upper platform area | [Wormways Upper West (Crawl_03)](wormways-upper-west.md) | R | breakable wall -must be opened from the other side (verified) |  |  |  |
| UR | upper right | middle platform area | [Wormways Upper East (Crawl_01)](wormways-upper-east.md) | L | none |  |  |  |
| MR | middle right | middle platform area | [Wormways Flea Rescue (Crawl_06)](wormways-flea-rescue.md) | L | none |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DS | door switch | middle platform area | lower area | none (door switch is on this side) |  |  |  |
| DS | door switch | lower area | middle platform area | door switch needs to be flipped |  |  |  |
| CG | platform gaps | middle platform area | upper platform area | silk soar OR cling grip |  |  |  |
| CG | platform gaps | upper platform area | middle platform area | none (falling) |  |  |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| use simple key on lock | lower area | simple key |  |  | Included | unlocks the LL room exit |
| mask shard wormways | lower area | none |  |  | Included |  |
| frayed rosary string wormways | upper platform area | cling grip OR silk soar |  |  | Included |  |
| flip door switch | middle platform area | none |  |  | Not included | unlocks the middle/lower shortcut |
