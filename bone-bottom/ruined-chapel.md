# Ruined Chapel (Tut_03)

## Subrooms

- chapel
- boss room
- bench room

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| R | right | bench room | [Moss Grotto Center (Tut_01)](moss-grotto-center.md) | UL | none |  |
| AR | ascend rope | chapel | [Bone Bottom (Bonetown)](bone-bottom.md) | DR | none |  |
| CD | chapel door | chapel | [Ruined Chapel Interior](ruined-chapel-interior.md) | CD | unknown OR ruined chapel access override | randomizer currently forces the door open under some conditions |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | Notes |
| --- | --- | --- | --- | --- | --- |
| RB | right boss entrance | bench room | boss room | break vines |  |
| RB | right boss entrance | boss room | bench room | moss mother defeated |  |
| LB | left boss entrance | chapel | boss room | none |  |
| LB | left boss entrance | boss room | chapel | moss mother defeated |  |

## Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| moss mother boss fight | boss room |  |  |

## Notes

ROOM BUG: fighting moss mother without breaking the vines on the right side of the arena (by approaching from the left), you get locked into the arena with darkness still covering the area.

Ascend rope AND the ceiling are valid exits - but I believe they take you to the same bot1 exit on the other side.
