# Deep Docks Lace Intro (Bone_East_12)

**Game ID:** Bone_East_12

## Subrooms

- left area
- switch platform
- boss arena
- right area

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | left area | [Deep Docks Map Shop (Bone_East_01)](deep-docks-map-shop.md) | LR | none |  |  |  |
| R | right1 | right area | [Deep Docks Bellshrine (Bellshrine_05)](deep-docks-bellshrine.md) | L | none |  |  |  |
| F | bot1 | left area | [Deep Docks Forge (Room_Forge)](deep-docks-forge.md) | C | airlock lever |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SP | lever platform jump | left area | switch platform | run OR dash OR drifter's cloak OR faydown cloak OR silk soar OR clawline OR sharpdart OR beast crest |  |  |  |
| SP | lever platform jump | switch platform | left area | none (falling) |  |  |  |
| BL | boss arena left | left area | boss arena | gate switch flipped |  |  |  |
| BL | boss arena left | boss arena | left area | gate switch flipped AND defeat lace |  |  |  |
| BR | boss arena right | boss arena | right area | defeat lace |  |  |  |
| BR | boss arena right | right area | boss arena | none | TODO | Needs verification | NEEDS VERIFICATION |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| gate switch | switch platform | none |  |  | Not included |  |
| lace 1 boss fight | boss arena | none |  |  | Included |  |
