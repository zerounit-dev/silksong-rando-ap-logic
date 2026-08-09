# Deep Docks Chains Center (Dock_02b)

## Subrooms

- upper left hallway
- upper chain platforms
- middle left exit area
- middle switch platform
- lower right area
- lower left area
- middle side room
- lower chain platforms

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| UL | left1 | upper left hallway | [Deep Docks Chains Flow West (Dock_02)](deep-docks-chains-flow-west.md) | UR |  | Needs verification |
| ML | left2 | middle left exit area | [Deep Docks Chains Flow West (Dock_02)](deep-docks-chains-flow-west.md) | MR |  | Needs verification |
| LL | left3 | lower left area | [Deep Docks Chains Flow West (Dock_02)](deep-docks-chains-flow-west.md) | LR |  | Needs verification |
| UR | right1 | upper chain platforms | [Deep Docks Chains Upper East (Dock_03)](deep-docks-chains-upper-east.md) | L | break wall (from this side) | can't enter from the other side until this is broken; Needs verification |
| LR | right2 | lower right area | [Deep Docks Chains Lower East (Dock_03c)](deep-docks-chains-lower-east.md) | L | break wall (from other side) | Needs verification |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | Notes |
| --- | --- | --- | --- | --- | --- |
| ME | middle exit to switch platform | middle left exit area | middle switch platform | cling grip OR ( silk soar AND magma bell AND blue slot ) | Needs verification |
| ME | middle exit to switch platform | middle switch platform | middle left exit area | none (falling) | Needs verification |
| LC | lower crossing | lower right area | lower left area | run OR dash OR drifter's cloak OR faydown cloak OR cling grip OR silk soar OR claw line OR sharp dart OR beast crest OR shaman crest | Needs verification |
| LC | lower crossing | lower left area | lower right area | none (jump) | Needs verification |
| P1 | lower to middle switch platform | lower left area | lower chain platforms | silk soar | Needs verification |
| P1 | lower to middle switch platform | lower chain platforms | lower left area | none (falling) | Needs verification |
| P2 | lower platforms to lower right area | lower chain platforms | lower right area | none (falling) | Needs verification |
| P2 | lower platforms to lower right area | lower right area | lower chain platforms | silk soar | Needs verification |
| C1 | middle chains to upper chains | middle switch platform | upper chain platforms | ceiling switch activated AND ( silk soar OR cling grip ) | Needs verification |
| C1 | middle chains to upper chains | upper chain platforms | middle switch platform | ceiling switch activated AND none (falling) | Needs verification |
| MS | middle switch platform to side room | middle switch platform | middle side room | none (falling) | one-way; Needs verification |
| MS | middle switch platform to side room | middle side room | middle switch platform | ceiling switch activated | Needs verification |
| MP | middle platform to lower chains | middle switch platform | lower chain platforms | none | Needs verification |
| MP | middle platform to lower chains | lower chain platforms | middle switch platform | none | Needs verification |
| DS | open door switch | upper left hallway | upper chain platforms | none (door switch is on this side) | Needs verification |
| DS | open door switch | upper chain platforms | upper left hallway | door switch flipped | Needs verification |
| S1 | side room to chain platforms | middle side room | lower chain platforms | none | Needs verification |
| S1 | side room to chain platforms | lower chain platforms | middle side room | none (falling) | I have a feeling this line is going to cause problems; Needs verification |

## Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| flintslate | upper left hallway | none | Needs verification; Not included in Archipelago world |
| door switch | upper left hallway | none | Needs verification; Not included in Archipelago world |
| ceiling switch | middle switch platform | none | lowers middle chain platforms; Needs verification; Not included in Archipelago world |
| shell shard cache deep docks 6 | middle switch platform | none | MARKED AS ??? ON TRACKER; Needs verification |
| shell shard cache deep docks 7 | middle switch platform | none | MARKED AS ??? ON TRACKER; Needs verification |
| shell shard cache deep docks 8 | middle switch platform |  | MARKED AS ??? ON TRACKER; Needs verification |
| shell shard cache deep docks 9 | middle switch platform |  | MARKED AS ??? ON TRACKER; Needs verification |

## Notes

the floor/lower half of this area is closed off initially

the switch to lower the middle chain section makes some of this logic difficult to reason about - but if you can reach the middle switch platform, there is no reason you can't reach all the stuff that unlocking the chains provides - might need to revise this for switch randomization
