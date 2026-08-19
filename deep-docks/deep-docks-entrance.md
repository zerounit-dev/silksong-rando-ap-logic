# Deep Docks Entrance (Dock_08)

**Game ID:** Dock_08

**Contributors:** herounit

## Subrooms

- main pathway
- gauntlet left
- gauntlet
- gauntlet right

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LL | left1 | gauntlet right | [The Marrow Lava Docks (Bone_09)](../the-marrow/the-marrow-lava-docks.md) | LR | none |  | Needs verification |  |
| UL | left2 | main pathway | [The Marrow Lava Docks (Bone_09)](../the-marrow/the-marrow-lava-docks.md) | UR | none |  | Needs verification |  |
| R | right1 | main pathway | [Deep Docks Bench Shaft (Dock_01)](deep-docks-bench-shaft.md) | L | none |  | Needs verification |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DS | door switch | main pathway | gauntlet right | switch flipped |  | Needs verification |  |
| DS | door switch | gauntlet right | main pathway | none (switch is on this side) |  | Needs verification |  |
| GL | gauntlet fight left | gauntlet left | gauntlet | none (starts gauntlet) |  | Needs verification |  |
| GL | gauntlet fight left | gauntlet | gauntlet left | defeat gauntlet |  | Needs verification |  |
| GR | gauntlet fight right | gauntlet | gauntlet right | defeat gauntlet |  | Needs verification |  |
| GR | gauntlet fight right | gauntlet right | gauntlet | none (starts gauntlet) |  | Needs verification | probably not possible to reach unless switch is flipped via AP check |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| door switch | gauntlet right | none |  | Needs verification | Not included |  |
| gauntlet | gauntlet | none |  | Needs verification | Not included |  |
| mask shard the marrow deep docks passage | gauntlet right | none |  | Needs verification | Included |  |
