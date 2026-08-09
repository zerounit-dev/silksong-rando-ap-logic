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

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | left1 | upper left hallway | [Deep Docks Chains Flow West (Dock_02)](deep-docks-chains-flow-west.md) | UR | none |  |  |  |
| ML | left2 | middle left exit area | [Deep Docks Chains Flow West (Dock_02)](deep-docks-chains-flow-west.md) | MR | none |  |  |  |
| LL | left3 | lower left area | [Deep Docks Chains Flow West (Dock_02)](deep-docks-chains-flow-west.md) | LR | none |  |  |  |
| UR | right1 | upper chain platforms | [Deep Docks Chains Upper East (Dock_03)](deep-docks-chains-upper-east.md) | L | break wall (from this side) |  |  | can't enter from the other side until this is broken |
| LR | right2 | lower right area | [Deep Docks Chains Lower East (Dock_03c)](deep-docks-chains-lower-east.md) | L | break wall (from other side) |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| ME | middle exit to switch platform | middle left exit area | middle switch platform | cling grip OR ( silk soar AND magma bell AND blue slot ) |  |  |  |
| ME | middle exit to switch platform | middle switch platform | middle left exit area | none (falling) |  |  |  |
| LC | lower crossing | lower right area | lower left area | run OR dash OR drifter's cloak OR faydown cloak OR cling grip OR silk soar OR claw line OR sharp dart OR beast crest OR shaman crest |  |  |  |
| LC | lower crossing | lower left area | lower right area | none (jump) |  |  |  |
| P1 | lower to middle switch platform | lower left area | lower chain platforms | silk soar |  |  |  |
| P1 | lower to middle switch platform | lower chain platforms | lower left area | none (falling) |  |  |  |
| P2 | lower platforms to lower right area | lower chain platforms | lower right area | none (falling) |  |  |  |
| P2 | lower platforms to lower right area | lower right area | lower chain platforms | silk soar |  |  |  |
| C1 | middle chains to upper chains | middle switch platform | upper chain platforms | ceiling switch activated AND ( silk soar OR cling grip ) |  |  |  |
| C1 | middle chains to upper chains | upper chain platforms | middle switch platform | ceiling switch activated AND none (falling) |  |  |  |
| MS | middle switch platform to side room | middle switch platform | middle side room | none (falling) |  |  | one-way |
| MS | middle switch platform to side room | middle side room | middle switch platform | ceiling switch activated |  |  |  |
| MP | middle platform to lower chains | middle switch platform | lower chain platforms | none |  |  |  |
| MP | middle platform to lower chains | lower chain platforms | middle switch platform | none |  |  |  |
| DS | open door switch | upper left hallway | upper chain platforms | none (door switch is on this side) |  |  |  |
| DS | open door switch | upper chain platforms | upper left hallway | door switch flipped |  |  |  |
| S1 | side room to chain platforms | middle side room | lower chain platforms | none |  |  |  |
| S1 | side room to chain platforms | lower chain platforms | middle side room | none (falling) |  |  | I have a feeling this line is going to cause problems |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| flintslate | upper left hallway | none |  |  | Included |  |
| shell shard cache deep docks 6 | middle switch platform | none |  |  | Included | MARKED AS ??? ON TRACKER |
| shell shard cache deep docks 7 | middle switch platform | none |  |  | Included | MARKED AS ??? ON TRACKER |
| shell shard cache deep docks 8 | middle switch platform | none |  |  | Included | MARKED AS ??? ON TRACKER |
| shell shard cache deep docks 9 | middle switch platform | none |  |  | Included | MARKED AS ??? ON TRACKER |
| ceiling switch | middle switch platform | none |  |  | Not included | lowers middle chain platforms |
| door switch | upper left hallway | none |  |  | Not included |  |

## Notes

the floor/lower half of this area is closed off initially

the switch to lower the middle chain section makes some of this logic difficult to reason about - but if you can reach the middle switch platform, there is no reason you can't reach all the stuff that unlocking the chains provides - might need to revise this for switch randomization
