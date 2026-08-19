# Deep Docks Forge (Room_Forge)

**Game ID:** Room_Forge

**Contributors:** herounit

## Subrooms

- left area
- right area
- gauntlet
- forge daughter
- right exit platform

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | right area | [Deep Docks Chains West (Dock_02)](deep-docks-chains-west.md) | UL |  |  |  |  |
| L | left1 | left area | [Deep Docks Lower West Shaft (Dock_04)](deep-docks-lower-west-shaft.md) | UR |  |  |  |  |
| C | top1 | left area | [Deep Docks Lace Intro (Bone_East_12)](deep-docks-lace-intro.md) | F |  |  |  | activate airlock |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DS | door switch | left area | right area | none (switch on this side) |  |  |  |
| DS | door switch | right area | left area | gate switch activated |  |  |  |
| GL | gauntlet left | left area | gauntlet | none |  |  |  |
| GL | gauntlet left | gauntlet | left area | gauntlet defeated |  |  |  |
| GR | gauntlet right | right area | gauntlet | none |  |  |  |
| GR | gauntlet right | gauntlet | right area | gauntlet defeated |  |  |  |
| GC | gauntlet upper | forge daughter | gauntlet | none |  |  |  |
| GC | gauntlet upper | gauntlet | forge daughter | gauntlet defeated |  |  |  |
| RJ | running jump | right area | right exit platform | run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart OR beast crest |  |  |  |
| RJ | running jump | right exit platform | right area | run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart OR beast crest | TODO | Needs verification | NEED TO VERIFY YOU CAN'T JUST JUMP BACK |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| shell shard cache deep docks 10 | left area | none |  |  | Included | break wall |
| shard bundle deep docks 2 | left area | none |  |  | Included |  |
| silkshot (forge daughter) | forge daughter | broken tool |  | Verified | Included | forge daughter shop |
| sting shard | forge daughter | none |  |  | Included | forge daughter shop |
| magma bell | forge daughter | none |  |  | Included | forge daughter shop |
| crafting kit forge daughter | forge daughter | none |  |  | Included | forge daughter shop |
| readable lore tablet | left area | activate airlock |  |  | Not included | NOT CURRENTLY RANDOMIZED |
| gate switch | forge daughter | none |  |  | Not included |  |
