# Hunter's March Map Shop (Ant_04_mid)

**Game ID:** Ant_04_mid

**Contributors:** herounit

## Subrooms

- left exit area
- left of gauntlet
- gauntlet
- right of gauntlet

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | left exit area | [Hunter's March Early Pathway West (Ant_04_left)](hunter-s-march-early-pathway-west.md) | R | none |  |  |  |
| R | right1 | right of gauntlet | [Hunter's March Early Pathway East (Ant_04)](hunter-s-march-early-pathway-east.md) | L | none |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| P1 | pogo 1 | left exit area | left of gauntlet | can pogo OR ( run AND dash AND faydown cloak ) OR ( run AND clawline ) OR ( faydown cloak AND clawline ) OR ( run AND drifter's cloak AND cling grip ) OR ( clawline AND sharpdart ) |  |  |  |
| P1 | pogo 1 | left of gauntlet | left exit area | can pogo OR ( run AND dash AND faydown cloak ) OR ( run AND clawline ) OR ( faydown cloak AND clawline ) OR ( run AND drifter's cloak AND cling grip ) OR ( clawline AND sharpdart ) |  |  |  |
| LG | left gauntlet entrance | left of gauntlet | gauntlet | none (starts gauntlet) |  |  |  |
| LG | left gauntlet entrance | gauntlet | left of gauntlet | defeat gauntlet |  |  |  |
| RG | right of gauntlet entrance | right of gauntlet | gauntlet | none (starts gauntlet) |  |  |  |
| RG | right of gauntlet entrance | gauntlet | right of gauntlet | defeat gauntlet |  |  |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| gauntlet fight | gauntlet | none |  |  | Not included |  |
| map purchase hunter's march | gauntlet | defeat gauntlet |  |  | Included |  |
