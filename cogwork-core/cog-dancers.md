# Cog Dancers (Cog_Dancers)

**Game ID:** Cog_Dancers

**Contributors:** samupo, Gallos

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | BaseLeft | ✓ |
| S2 | Top | ✓ |
| S3 | BaseRight | ✓ |
| S4 | BossArena | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | BaseRight | [Memorium Entrance Tunnel (Song_25)](../choral-chambers/memorium-entrance-tunnel.md) | L | none |  | Verified | ✓ |  |
| L | left1 | BaseLeft | [High Halls Corridor (Hang_07)](../choral-chambers/high-halls-corridor.md) | R | none |  | Verified | ✓ |  |
| B1 | bot1 | BossArena | [Cogwork Core South Main (Cog_04)](cogwork-core-south-main.md) | TL | none |  | Verified | ✓ |  |
| B2 | bot2 | BossArena | [Cogwork Core South Main (Cog_04)](cogwork-core-south-main.md) | TR | none |  | Verified | ✓ |  |
| E | elevator | BossArena | [Lace 2 Fight (Song_Tower_01)](../the-cradle/lace-2-fight.md) | D | activate Play Threefold Melody |  | Verified | ✓ |  |
| D | door1 | Top | [Cogwork Core Main Connection (Cog_Pass)](cogwork-core-main-connection.md) | TL | Nothing. |  | Verified | ✓ |  |
| T | top1 | Top | [Cogwork Core North Main (Cog_08)](cogwork-core-north-main.md) | B | activate Cog dancers - clawline mechanism 2 AND (cling grip left OR easy scuttlebrace OR (faydown AND (ledge grab right OR easy [reaper,architect,beast,shaman] pogo))) |  | Verified | ✓ | probably one way |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | BossArena | Top | defeat Cogwork Dancers Boss Fight AND (Silk Soar OR (activate Cog dancers - clawline mechanism 1 AND clawline either)) |  | Verified | ✓ |  |
| V | Vertical | Top | BossArena | defeat Cogwork Dancers Boss Fight |  | Verified | ✓ |  |
| R | RightSide | BaseRight | BossArena | none |  | Verified | ✓ |  |
| R | RightSide | BossArena | BaseRight | defeat Cogwork Dancers Boss Fight |  | Verified | ✓ |  |
| L | LeftSide | BossArena | BaseLeft | defeat Cogwork Dancers Boss Fight |  | Verified | ✓ |  |
| L | LeftSide | BaseLeft | BossArena | none |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Play Threefold Melody | BossArena | defeat Cogwork Dancers Boss Fight AND get 3 threefold melody parts |  | Verified | logic-point |  | Used in Liquid Lacquer wish requirements per the wiki. |
| 2 | Cog dancers - clawline mechanism 1 | Top | attack up |  | Verified | switch | ✓ |  |
| 3 | Cog dancers - clawline mechanism 2 | Top | clawline either |  | Verified | switch | ✓ |  |
| 4 | Cog dancers - Green prince meeting | BaseLeft | defeat Cogwork Dancers Boss Fight AND complete Sinner's road - Green Prince freedom IN Sinner's Road Vertical Hall West |  | Verified | event | ✓ |  |
| 5 | Cogwork Dancers Boss Fight | BossArena | Combat Requirements |  | Verified | boss |  |  |

## Notes

Boss needs only any crest to be beatable. The big line attack can be parried with appropriate timing.

## Room Images

### Connections

[![Connections for Cog Dancers (Cog_Dancers)](../00-annotations/cogwork-core/cog-dancers-connections.png)](../00-annotations/cogwork-core/cog-dancers-connections.png)

### Checks

[![Checks for Cog Dancers (Cog_Dancers)](../00-annotations/cogwork-core/cog-dancers-checks.png)](../00-annotations/cogwork-core/cog-dancers-checks.png)

### Scene

[![Scene for Cog Dancers (Cog_Dancers)](../00-annotations/cogwork-core/cog-dancers-scene.png)](../00-annotations/cogwork-core/cog-dancers-scene.png)
