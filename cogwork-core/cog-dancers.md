# Cog Dancers (Cog_Dancers)

**Game ID:** Cog_Dancers

**Contributors:** samupo

## Subrooms

- BaseLeft
- Top
- BaseRight
- BossArena

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | BaseRight | [Memorium Entrance Tunnel (Song_25)](../choral-chambers/memorium-entrance-tunnel.md) | L | none |  | Verified |  |
| L | left1 | BaseLeft | [High Halls Corridor (Hang_07)](../choral-chambers/high-halls-corridor.md) | R | none |  | Verified |  |
| B1 | bot1 | BossArena | TODO |  | Boss: Cogwork Dancers |  | Verified |  |
| B2 | bot2 | BossArena | TODO |  | Boss: Cogwork Dancers |  | Verified |  |
| E | elevator | BossArena | TODO |  | Boss: Cogwork Dancers and more | TODO |  | TODO: Check all that's needed for the elevator to work |
| D | door1 | Top | TODO |  |  | TODO |  | TODO |
| T | top1 | Top | TODO |  | clawline | TODO |  | probably one way |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | BossArena | Top | Boss: Cogwork Dancers and silk soar |  | Verified |  |
| V | Vertical | Top | BossArena | none | TODO |  | falling, check if dancers boss is required on a new save |
| R | RightSide | BaseRight | BossArena | none |  | Verified |  |
| R | RightSide | BossArena | BaseRight | Boss: Cogwork Dancers |  | Verified |  |
| L | LeftSide | BossArena | BaseLeft | Boss: Cogwork Dancers |  | Verified |  |
| L | LeftSide | BaseLeft | BossArena | none |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Boss: Cogwork Dancers | BossArena | any crest |  | Verified | Included |  |

## Notes

Boss needs only any crest to be beatable. The big line attack can be parried with appropriate timing.
