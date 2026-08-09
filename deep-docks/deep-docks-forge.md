# Deep Docks Forge (Room_Forge)

## Subrooms

- left area
- right area
- gauntlet
- forge daughter
- right exit platform

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| R | right1 | right area | [Deep Docks Chains Flow West (Dock_02)](deep-docks-chains-flow-west.md) | UL |  | Needs verification |
| L | left1 | left area | [Deep Docks Lower West Shaft (Dock_04)](deep-docks-lower-west-shaft.md) | UR |  | Needs verification |
| C | top1 | left area | [Deep Docks Lace Intro (Bone_East_12)](deep-docks-lace-intro.md) | F |  | activate airlock; Needs verification |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | Notes |
| --- | --- | --- | --- | --- | --- |
| DS | door switch | left area | right area | none (switch on this side) | Needs verification |
| DS | door switch | right area | left area | gate switch activated | Needs verification |
| GL | gauntlet left | left area | gauntlet | none | Needs verification |
| GL | gauntlet left | gauntlet | left area | gauntlet defeated | Needs verification |
| GR | gauntlet right | right area | gauntlet | none | Needs verification |
| GR | gauntlet right | gauntlet | right area | gauntlet defeated | Needs verification |
| GC | gauntlet upper | forge daughter | gauntlet | none | Needs verification |
| GC | gauntlet upper | gauntlet | forge daughter | gauntlet defeated | Needs verification |
| RJ | running jump | right area | right exit platform | run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart OR beast crest | Needs verification |
| RJ | running jump | right exit platform | right area |  | Needs verification |

## Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| shell shard cache deep docks 10 | left area | none | break wall; Needs verification |
| shard bundle deep docks 2 | left area | none | Needs verification |
| silkshot (forge daughter) | forge daughter | ??? | forge daughter shop; TODO; Needs verification |
| sting shard | forge daughter | none | forge daughter shop; Needs verification |
| magma bell | forge daughter | none | forge daughter shop; Needs verification |
| crafting kit forge daughter | forge daughter | none | forge daughter shop; Needs verification |
| readable lore tablet | left area | activate airlock | NOT CURRENTLY RANDOMIZED; Needs verification; Not included in Archipelago world |
| gate switch | forge daughter | none | Needs verification; Not included in Archipelago world |
