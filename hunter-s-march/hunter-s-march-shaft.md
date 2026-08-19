# Hunter's March Shaft (Ant_14)

**Game ID:** Ant_14

## Subrooms

- L4 exit platform
- LR exit platform
- L3 exit platform
- middle exit platforms
- L1 exit platform
- L5 exit platform

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L5 | left5 | L5 exit platform | [Hunter's March Treasure Vault (Ant_21)](hunter-s-march-treasure-vault.md) | R | none |  |  |  |
| L1 | left1 | L1 exit platform | [Hunter's March Skarr Shop (Ant_Merchant)](hunter-s-march-skarr-shop.md) | R | none |  |  |  |
| L2 | left2 | middle exit platforms | [Hunter's March Trapped Bench (Ant_17)](hunter-s-march-trapped-bench.md) | R | none |  |  |  |
| L3 | left3 | L3 exit platform | [Hunter's March Early Pathway East (Ant_04)](hunter-s-march-early-pathway-east.md) | R | none |  |  |  |
| L4 | left4 | L4 exit platform | [Hunter's March Deep Docks Passage (Ant_05b)](hunter-s-march-deep-docks-passage.md) | R | none |  |  |  |
| UR | right2 | middle exit platforms | [Hunter's March Statue (Ant_05c)](hunter-s-march-statue.md) | L | none |  |  |  |
| LR | right3 | LR exit platform | [Hunter's March Chapel Passage (Ant_20)](hunter-s-march-chapel-passage.md) | L | none |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| G1 | gap 1 | L4 exit platform | LR exit platform | can pogo OR drifter's cloak OR faydown cloak OR clawline OR sharpdart OR  ( run AND dash ) |  | Needs verification |  |
| G1 | gap 1 | LR exit platform | L4 exit platform | can pogo OR run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart |  |  |  |
| F1 | fall 1 | L3 exit platform | L4 exit platform | none (falling) |  |  |  |
| G2 | gap 2 | LR exit platform | L3 exit platform | can pogo OR drifter's cloak OR faydown cloak OR silk soar |  |  |  |
| G2 | gap 2 | L3 exit platform | LR exit platform | none (falling) |  |  |  |
| G3 | gap 3 | L3 exit platform | middle exit platforms | can pogo OR drifter's cloak OR silk soar |  |  |  |
| G3 | gap 3 | middle exit platforms | L3 exit platform | none (falling) |  |  |  |
| G4 | gap 4 | middle exit platforms | L1 exit platform | can pogo OR drifter's cloak OR  silk soar OR ( faydown cloak AND cling grip ) |  |  |  |
| G4 | gap 4 | L1 exit platform | middle exit platforms | none (falling) |  |  |  |
| G5 | gap 5 | L1 exit platform | L5 exit platform | easy skips enabled  OR silk soar OR ( cling grip AND ( can pogo OR dash OR clawline OR sharpdart OR drifter's cloak OR faydown cloak ) ) |  |  |  |
| G5 | gap 5 | L5 exit platform | L1 exit platform | none (falling) |  |  |  |
| T1 | test 1 | L5 exit platform | middle exit platforms | none |  |  |  |

## Check Locations

No check locations defined.
