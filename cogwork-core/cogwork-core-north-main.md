# Cogwork Core North Main (Cog_08)

**Game ID:** Cog_08

**Contributors:** Rebel

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | Lower Entrance | ✓ |
| S2 | Upper Entrance | ✓ |
| S3 | Lever Door | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | bot1 | Lower Entrance | [Cog Dancers (Cog_Dancers)](cog-dancers.md) | T | Nothing |  | Verified | ✓ |  |
| T | top1 | Upper Entrance | [Cogwork Core Architect's Melody (Cog_09)](cogwork-core-architect-s-melody.md) | B | Nothing |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BEL | Bottom Entrance-Lever | Lower Entrance | Lever Door | ((Proficient Movement AND Spike Pogo)  OR Medium Hunter Pogo OR Medium Reaper Pogo OR Medium Architect Pogo OR Medium Shaman Pogo OR ((Cling Grip OR Faydown Cloak OR Ledge Grab) AND (Easy Enemy Pogo))) |  | Verified | ✓ | Can be clawline only'd but since theres no specific skip tag for that i am omitting it. |
| BEL | Bottom Entrance-Lever | Lever Door | Lower Entrance | Drifter's Cloak |  | Verified | ✓ | let me add a Nothing as a medium skip pls it'll be funny |
| LTE | Lever-Top Entrance | Lever Door | Upper Entrance | Clawline AND Faydown Cloak AND Cling Grip |  | Verified | ✓ |  |
| LTE | Lever-Top Entrance | Upper Entrance | Lever Door | Clawline OR Sharpdart OR Dash OR Faydown Cloak OR Drifter's Cloak |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Cogwork Core: Flip Switch #7 | Lever Door | Nothing. |  | Verified | switch | ✓ |  |
| 2 | import enemies |  |  | TODO | Needs verification |  |  |  |

## Room Images

### Connections

[![Connections for Cogwork Core North Main (Cog_08)](../00-annotations/cogwork-core/cogwork-core-north-main-connections.png)](../00-annotations/cogwork-core/cogwork-core-north-main-connections.png)

### Checks

[![Checks for Cogwork Core North Main (Cog_08)](../00-annotations/cogwork-core/cogwork-core-north-main-checks.png)](../00-annotations/cogwork-core/cogwork-core-north-main-checks.png)

### Scene

[![Scene for Cogwork Core North Main (Cog_08)](../00-annotations/cogwork-core/cogwork-core-north-main-scene.png)](../00-annotations/cogwork-core/cogwork-core-north-main-scene.png)
