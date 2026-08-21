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
| C | top1 | left area | [Deep Docks Lace Intro (Bone_East_12)](deep-docks-lace-intro.md) | F | none |  | Verified | activate airlock |
| L | left1 | left area | [Deep Docks Lower West Shaft (Dock_04)](deep-docks-lower-west-shaft.md) | UR | none |  | Verified |  |
| R | right1 | right exit platform | [Deep Docks Chains West (Dock_02)](deep-docks-chains-west.md) | UL | none |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DS | door switch | left area | right area | gate switch activated |  | Verified |  |
| DS | door switch | right area | left area | none (switch on this side) |  | Verified |  |
| GL | gauntlet left | left area | gauntlet | none |  | Verified |  |
| GL | gauntlet left | gauntlet | left area | gauntlet defeated |  | Verified |  |
| GR | gauntlet right | right area | gauntlet | none |  | Verified |  |
| GR | gauntlet right | gauntlet | right area | gauntlet defeated |  | Verified |  |
| GC | gauntlet upper | forge daughter | gauntlet | open airlock down |  | Verified |  |
| GC | gauntlet upper | gauntlet | forge daughter | gauntlet defeated AND ( open airlock up AND ( ledge grab OR faydown cloak OR clawline OR scuttlebrace OR shamans crest ) ) |  | Verified |  |
| RJ | running jump | right area | right exit platform | run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart OR beast crest |  | Verified |  |
| RJ | running jump | right exit platform | right area | run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart OR beast crest |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| shell shard cache deep docks 10 | left area | none |  | Verified | Included | break wall |
| shard bundle deep docks 2 | left area | none |  | Verified | Included |  |
| silkshot (forge daughter) | forge daughter | broken tool |  | Verified | Included | forge daughter shop |
| sting shard | forge daughter | none |  | Verified | Included | forge daughter shop |
| magma bell | forge daughter | none |  | Verified | Included | forge daughter shop |
| crafting kit forge daughter | forge daughter | none |  | Verified | Included | forge daughter shop |
| readable lore tablet | left area | open airlock left |  | Verified | Included |  |
| gate switch | forge daughter | none |  | Verified | Not included |  |
