# The Marrow Entrance

## Subrooms

- before gauntlet
- gauntlet room
- after gauntlet
- ceiling exit

## Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| LL | lower left | before gauntlet | [bone bottom](../bone-bottom/bone-bottom.md) -LR | none |
| LR | lower right | after gauntlet | [the marrow bell bench](./the-marrow-bell-bench.md) -L | none |
| UR | upper right | before gauntlet | [the marrow falling rocks](./the-marrow-falling-rocks.md) -L | none (breakable wall) |
| C | ceiling | ceiling exit | [the marrow shakra intro](./the-marrow-shakra-intro.md) -F | none |

## Subroom Connections

| alias | name | source | destination | requirements |
| --- | --- | --- | --- | --- |
| DS | door switch | before gauntlet | after gauntlet | flipped door switch |
| DS | door switch | after gauntlet | before gauntlet | none (can flip door switch) |
| GF | gauntlet fight | before gauntlet | gauntlet room | none |
| GF | gauntlet fight | gauntlet room | after gauntlet | defeat gauntlet |
| GF | gauntlet fight | gauntlet room | before gauntlet | defeat gauntlet |
| LP | lowered platform | before gauntlet | ceiling exit | platform lowered OR silk soar OR faydown cloak OR ( run AND clawline ) |

## Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| shell shard cache the marrow 1 | before gauntlet | none | MARKED AS ??? ON TRACKER |
| rosary cache the marrow 1 | after gauntlet | none |  |
| rosary cache the marrow 2 | after gauntlet | none |  |
