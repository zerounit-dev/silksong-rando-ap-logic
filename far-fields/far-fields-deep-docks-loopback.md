# Far Fields Deep Docks Loopback (Bone_East_15)

## Subrooms

- spike exit
- ground
- bell bench
- before gate

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | bell bench | [Is this still Deep Docks? (East) (Bone_East_04)](../deep-docks/is-this-still-deep-docks-east.md) | LR |  |  |  |  |
| F | bot1 | ground | [Far Fields Entrance (Bone_East_02)](far-fields-entrance.md) | C |  |  |  |  |
| R | right1 | spike exit | TODO |  |  |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SF | spike float | ground | spike exit | ( cling grip AND drifter's cloak ) OR ( silk soar AND drifter's cloak ) |  |  |  |
| SF | spike float | spike exit | ground | none (falling) | TODO |  | can barely ledge grab by falling to jump down |
| BG | bell bench gate | before gate | bell bench | none (switch is on this side) |  |  |  |
| BG | bell bench gate | bell bench | before gate | gate switch flipped |  |  |  |
| CG | cling grip | ground | before gate | cling grip OR silk soar |  |  |  |
| CG | cling grip | before gate | ground | none (falling) |  |  |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary cache far fields 9 | ground | none |  |  | Included | MARKED AS ??? ON TRACKER |
| rosary cache far fields 10 | ground | none |  |  | Included | MARKED AS ??? ON TRACKER |
| gate switch | before gate | none |  |  | Not included |  |
| bench pay lock | bell bench | none |  |  | Not included |  |
| bench :) | bell bench | unlock bench lock |  |  | Not included |  |
