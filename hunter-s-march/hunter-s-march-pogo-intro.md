# Hunter's March Pogo Intro (Ant_03)

**Game ID:** Ant_03

## Subrooms

- flea rescue area
- middle exit area
- ground level

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left2 | ground level | [Hunter's March Entrance (Ant_02)](hunter-s-march-entrance.md) | R | none |  |  |  |
| R | right3 | middle exit area | [Hunter's March Early Pathway West (Ant_04_left)](hunter-s-march-early-pathway-west.md) | L | none |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LP | lower pogo | ground level | middle exit area | can pogo |  |  |  |
| LP | lower pogo | middle exit area | ground level | none (falling) |  |  |  |
| UP | upper pogo | middle exit area | flea rescue area | can pogo |  |  |  |
| UP | upper pogo | flea rescue area | middle exit area | can pogo |  |  |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| flea rescue | flea rescue area | can break cage |  |  | Included |  |
