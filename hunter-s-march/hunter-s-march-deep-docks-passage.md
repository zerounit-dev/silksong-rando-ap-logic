# Hunter's March Deep Docks Passage (Ant_05b)

**Game ID:** Ant_05b

## Subrooms

- before gate
- right of gauntlet
- gauntlet
- left of gauntlet

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | before gate | [Hunter's March Shaft (Ant_14)](hunter-s-march-shaft.md) | L4 | none |  | Needs verification |  |
| LF | bot1 | left of gauntlet | [Is this still Deep Docks? (West) (Bone_East_04b)](../deep-docks/is-this-still-deep-docks-west.md) | C | none |  | Needs verification |  |
| RF | bot2 | right of gauntlet | [Is this still Deep Docks? (East) (Bone_East_04)](../deep-docks/is-this-still-deep-docks-east.md) | C | none |  | Needs verification |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BG | bone gate | before gate | right of gauntlet | none (switch is on this side) |  | Needs verification |  |
| BG | bone gate | right of gauntlet | before gate | switched flipped |  | Needs verification |  |
| RG | right gauntlet | right of gauntlet | gauntlet | none (starts gauntlet) |  | Needs verification |  |
| RG | right gauntlet | gauntlet | right of gauntlet | defeat gauntlet |  | Needs verification |  |
| LG | left gauntlet | left of gauntlet | gauntlet | none (starts gauntlet) |  | Needs verification |  |
| LG | left gauntlet | gauntlet | left of gauntlet | defeat gauntlet |  | Needs verification |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| bone switch | before gate | none |  | Needs verification | Not included |  |
| gauntlet fight | gauntlet | none |  | Needs verification | Not included |  |
