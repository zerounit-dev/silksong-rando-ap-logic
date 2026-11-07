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
| BEL | Bottom Entrance-Lever | Lower Entrance | Lever Door | (Clawline Both AND Ponder the Orb) OR (Spike Pogo AND (Cling Grip Both OR Scuttlebrace) AND Clawline AND (Ledge Grab OR Faydown Cloak)) OR (Faydown Cloak AND Proficient Movement AND Intended [Hunter, Reaper, Beast, Witch, Architect, Shaman] Pogo)  OR (Clawline Right OR Faydown Cloak OR ((Easy [Shaman, Architect] Pogo OR Medium [Hunter, Reaper, Witch, Beast] Pogo) AND ((Ledge Grab Right OR Cling Grip Right) AND Easy Pogo OFF [Cogwork Spine]) AND ((Medium [Hunter, Witch] Pogo AND (Dash Both OR Faydown Cloak OR Drifter's Cloak OR Clawline Both OR Sharpdart x 3 OR Medium [Parry, Pale Nails, Voltvessels, Plasmium] Stall x 6)) OR Medium [Reaper] Pogo OR Hard [Beast] Pogo OR Easy [Architect] Pogo OR Medium [Shaman] Pogo))) |  | Verified | ✓ |  |
| BEL | Bottom Entrance-Lever | Lever Door | Lower Entrance | Proficient Movement OR Drifter's Cloak |  | Verified | ✓ | let me add a Nothing as a medium skip pls it'll be funny |
| LTE | Lever-Top Entrance | Lever Door | Upper Entrance | Clawline AND Faydown Cloak AND Cling Grip |  | Verified | ✓ |  |
| LTE | Lever-Top Entrance | Upper Entrance | Lever Door | Clawline OR Sharpdart OR Dash OR Faydown Cloak OR Drifter's Cloak |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Cogwork Core: Flip Switch #7 | Lever Door | Nothing. |  | Verified | switch | ✓ |  |
| 2 | import enemies |  |  | TODO | Needs verification |  |  |  |
| 3 | Cogwork Crawler 1 |  |  |  |  | enemy | ✓ |  |
| 4 | Cogwork Crawler 2 |  |  |  |  | enemy | ✓ |  |
| 5 | Cogwork Crawler 3 |  |  |  |  | enemy | ✓ |  |
| 6 | Cogwork Cleanser 1 |  |  |  |  | enemy | ✓ |  |
| 7 | Cogwork Spine 1 |  |  |  |  | enemy | ✓ |  |
| 8 | Cogwork Spine 2 |  |  |  |  | enemy | ✓ |  |
| 9 | Cogwork Defender 1 |  |  |  |  | enemy | ✓ |  |
| 10 | Cogwork Spine 3 |  |  |  |  | enemy | ✓ |  |
| 11 | Cogwork Choirbug 1 |  |  |  |  | enemy | ✓ |  |
| 12 | Cogwork Cleanser 2 |  |  |  |  | enemy | ✓ |  |
| 13 | Cogwork Spine 4 |  |  |  |  | enemy | ✓ |  |

## Notes

enemies will be done later; this is just to fix the current logic connections.

## Room Images

### Connections

[![Connections for Cogwork Core North Main (Cog_08)](../00-annotations/cogwork-core/cogwork-core-north-main-connections.png)](../00-annotations/cogwork-core/cogwork-core-north-main-connections.png)

### Checks

[![Checks for Cogwork Core North Main (Cog_08)](../00-annotations/cogwork-core/cogwork-core-north-main-checks.png)](../00-annotations/cogwork-core/cogwork-core-north-main-checks.png)

### Scene

[![Scene for Cogwork Core North Main (Cog_08)](../00-annotations/cogwork-core/cogwork-core-north-main-scene.png)](../00-annotations/cogwork-core/cogwork-core-north-main-scene.png)
