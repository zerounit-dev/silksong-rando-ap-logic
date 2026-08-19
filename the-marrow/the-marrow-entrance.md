# The Marrow Entrance (Bone_01)

**Game ID:** Bone_01

**Contributors:** herounit

## Subrooms

- before gauntlet
- gauntlet room
- after gauntlet
- ceiling exit

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LL | lower left | before gauntlet | [Bone Bottom Town (Bonetown)](../bone-bottom/bone-bottom-town.md) | LR | none |  |  |  |
| LR | lower right | after gauntlet | [The Marrow Bell Bench (Bone_01c)](the-marrow-bell-bench.md) | LL | none |  |  |  |
| UR | upper right | before gauntlet | [The Marrow Bell Bench (Bone_01c)](the-marrow-bell-bench.md) | UL | none (breakable wall) |  |  |  |
| C | ceiling | ceiling exit | [The Marrow Shakra Intro (Bone_04)](the-marrow-shakra-intro.md) | F | none |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DS | door switch | before gauntlet | after gauntlet | flipped door switch |  |  |  |
| DS | door switch | after gauntlet | before gauntlet | none (can flip door switch) |  |  |  |
| UG | upper gauntlet entrance | before gauntlet | gauntlet room | none |  |  |  |
| UG | upper gauntlet entrance | gauntlet room | before gauntlet | defeat gauntlet |  |  |  |
| LG | lower gauntlet entrance | gauntlet room | after gauntlet | defeat gauntlet |  |  |  |
| LG | lower gauntlet entrance | after gauntlet | gauntlet room | defeat gauntlet |  |  |  |
| LP | lowered platform | before gauntlet | ceiling exit | platform lowered OR silk soar OR faydown cloak OR ( run AND clawline ) |  |  |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| shell shard cache the marrow 1 | before gauntlet | none |  |  | Included |  |
| rosary cache the marrow 1 | after gauntlet | none |  |  | Included |  |
| rosary cache the marrow 2 | after gauntlet | none |  |  | Included |  |
| door switch | after gauntlet | none |  |  | Not included |  |
