# Bone Bottom Town (Bonetown)

**Game ID:** Bonetown

**Contributors:** herounit, Super EpicGuy

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | sky left | ✓ |
| S2 | sky right | ✓ |
| S3 | ground level | ✓ |
| S4 | upper right platforms | ✓ |
| S5 | upper middle platforms | ✓ |
| S6 | upper left platforms | ✓ |
| S7 | chapel roof | ✓ |
| S8 | shakra platform | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | upper left | upper left platforms | [Bonegrave (Bonegrave)](bonegrave.md) | UR | none |  | Verified | ✓ |  |
| LL | lower left | ground level | [Bonegrave (Bonegrave)](bonegrave.md) | LR | clear vines holding door closed IN bonegrave |  | Verified | ✓ |  |
| DR | descend rope | ground level | [Ruined Chapel (Tut_03)](../moss-grotto/ruined-chapel.md) | AR | none |  | Verified | ✓ |  |
| RF | right floor | ground level | [Moss Grotto Center (Tut_01)](../moss-grotto/moss-grotto-center.md) | C | none |  | Verified | ✓ |  |
| BD | bellway door | ground level | [Bone Bottom Bellway (Bellway_01)](bone-bottom-bellway.md) | BD | none |  | Verified | ✓ |  |
| LR | lower right | ground level | [The Marrow Entrance (Bone_01)](../the-marrow/the-marrow-entrance.md) | LL | none |  | Verified | ✓ |  |
| UR | upper right | upper right platforms | [Mosshome Basement Passage (Bone_01b)](mosshome-basement-passage.md) | LL | none |  | Verified | ✓ |  |
| T1 | top1 | sky left | [The Big Fall (Aspid_01)](the-big-fall.md) | B1 | silk soar |  | Verified | ✓ |  |
| T2 | right ceiling | upper right platforms | [The Big Fall (Aspid_01)](the-big-fall.md) | B2 | ledge grab right OR cling grip either  OR silk soar  OR faydown OR easy shaman pogo OR easy scuttlebrace  OR easy pogo off aknid |  | Verified | ✓ | didn't want to make a tiny subroom to account for the ledge grab to get up here |
| T3 | top3 | sky left | [The Big Fall (Aspid_01)](the-big-fall.md) | B3 | silk soar |  | Verified | ✓ |  |
| T4 | top4 | sky right | [The Big Fall (Aspid_01)](the-big-fall.md) | B4 | silk soar |  | Verified | ✓ |  |
| T5 | top5 | sky right | [The Big Fall (Aspid_01)](the-big-fall.md) | B5 | silk soar |  | Verified | ✓ |  |
| WW | wish wall | ground level | [Bone Bottom Wish Wall](../wish-menus/bone-bottom-wish-wall.md) | BB | defeat THE bell beast boss fight OR visit shellwood |  | Verified | ✓ | "IT'S NOT BELL BEAST DEFEAT OR WIDOW DEFEAT FOR BONE BOTTOM WISH WALL IT'S BELL BEAST DEFEATED OR SHELLWOOD VISITED???" - Moriko, in utter denial |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| CC | climb chapel | ground level | chapel roof | silk soar  OR cling grip left OR ( easy scuttlebrace AND faydown ) |  | Verified | ✓ | cling grip only works by itself when the door has not been opened - this makes logic non-monotonic and needs a mod fix - in this case, a slow opening door |
| SM | soar to middle platforms | ground level | upper middle platforms | silk soar |  | Verified | ✓ |  |
| SSL | soar to sky exit left | ground level | sky left | silk soar |  | Verified |  |  |
| SSL | soar to sky exit left | sky left | ground level | none (falling) |  | Verified |  |  |
| SSR | soar to sky exit right | ground level | sky right | silk soar |  | Verified |  |  |
| SSR | soar to sky exit right | sky right | ground level | none (falling) |  | Verified |  |  |
| SR | soar to right platforms | ground level | upper right platforms | silk soar |  | Verified | ✓ |  |
| EV | elevator | ground level | upper right platforms | activate elevator switch |  | Verified | ✓ |  |
| EV | elevator | upper right platforms | ground level | activate elevator switch |  | Verified | ✓ |  |
| CC | climb chapel | chapel roof | ground level | none (falling) |  | Verified | ✓ |  |
| CR | climb roof | chapel roof | upper left platforms | silk soar  OR cling grip both OR ( cling grip left AND spike pogo ) OR ( easy scuttlebrace AND faydown cloak ) OR ( hard scuttlebrace AND hard [ hunter, reaper, wanderer, beast, architect ] crest heal stall ) OR ( hard scuttlebrace AND ( thread storm OR rune rage ) ) |  | Verified | ✓ | You need a very precise heal or spell boost to scuttlebrace the wall without wings, which can be done by anything but witch crest |
| CR | climb roof | upper left platforms | chapel roof | none (falling) |  | Verified | ✓ |  |
| MD | middle platform drift | upper middle platforms | chapel roof | drifters  OR clawline left OR sharpdart  OR easy beast pogo OR easy architect pogo OR ( hard shaman pogo )  OR ( ledge grab left AND easy shaman pogo ) OR ( dash left AND ( easy hunter pogo OR easy naked pogo ) )  OR ( dash left AND ( easy scuttlebrace OR flea brew OR silkspeed anklets OR faydown cloak ) )  OR ( run AND flea brew ) |  | Verified | ✓ | Beast and architect can just spam pogo |
| SM | soar to middle platforms | upper middle platforms | ground level | none (falling) |  | Verified | ✓ |  |
| CL | clawline across the sky | upper middle platforms | upper right platforms | clawline right OR ( dash right AND ( sharpdart OR drifters ) )  OR ( run AND sharpdart )  OR ( drifters AND ( faydown cloak OR proficient movement ) ) |  | Verified | ✓ | This is how it is currently implemented in the apworld; need to verify with SEG as it was malformed prior to correction. - hero |
| CL | clawline across the sky | upper right platforms | upper middle platforms | clawline left OR ( dash left AND ( sharpdart OR drifters ) )  OR ( run AND sharpdart )  OR ( drifters AND ( faydown cloak OR proficient movement ) ) |  | Verified | ✓ | This is how it is currently implemented in the apworld; need to verify with SEG as it was malformed prior to correction. - hero |
| SR | soar to right platforms | upper right platforms | ground level | none (falling) |  | Verified | ✓ |  |
| DL | sky drift to right platforms | sky left | upper middle platforms | drifters  OR clawline left OR faydown OR sharpdart OR dash left OR easy [ beast, hunter, architect, reaper, shaman ] pogo OR easy flea brew stall OR easy crest heal stall | TODO | Verified | ✓ | other stalls probably work here - hero, 11/3 |
| DR | sky drift to middle platforms | sky right | upper right platforms | drifters  OR clawline right OR faydown OR sharpdart OR dash right OR easy [ beast, hunter, architect, reaper, shaman ] pogo OR easy flea brew stall OR easy crest heal stall | TODO | Verified | ✓ | other stalls probably work here - hero, 11/3 |
| RC | right platform climb | ground level | shakra platform | ledge grab left OR cling grip either OR silk soar OR faydown |  | Verified | ✓ |  |
| RC | right platform climb | shakra platform | ground level | none (falling) |  | Verified | ✓ |  |
| RF | right platform fall | upper right platforms | shakra platform | none (falling) |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Bone Bottom Town Bench | ground level | none |  | Verified | bench | ✓ |  |
| 2 | Bone Bottom Icon of Hope Statue | ground level | complete THE an icon of hope wish granted |  | Verified | collectible | ✓ |  |
| 3 | bone bottom mossberry | upper right platforms | none |  | Verified | collectible | ✓ |  |
| 4 | elevator switch | upper right platforms | flip switch up |  | Verified | switch | ✓ |  |
| 5 | bone bottom rosary cache 8 | upper right platforms | none |  | Verified | collectible | ✓ |  |
| 6 | bone bottom rosary cache 9 | upper right platforms | none |  | Verified | collectible | ✓ |  |
| 7 | weaver effigy camora moss grotto | upper middle platforms | none |  | Verified | collectible | ✓ |  |
| 8 | bone bottom rosary dish | upper middle platforms | none |  | Verified | collectible | ✓ |  |
| 9 | magnetite broach | ground level | ( act 1 OR act 2 ) AND spend 120 rosaries |  | Verified | collectible | ✓ | pebb's shop |
| 10 | mask shard pebbs shop grindle act 3 | ground level | ( act 1 OR act 2 ) AND spend 300 rosaries |  | Verified | collectible | ✓ | pebb's shop |
| 11 | bone bottom shop craft metal | ground level | ( act 1 OR act 2 ) AND spend 60 rosaries |  | Verified | collectible | ✓ | pebb's shop |
| 12 | simple key | ground level | ( act 1 OR act 2 ) AND spend 500 rosaries |  | Verified | collectible | ✓ | pebb's shop |
| 13 | reach bone bottom | ground level | none |  | Verified | logic-point |  | addresses the loading zone blocker in moss grotto center ceiling that only goes away once you've been up here - remove this/requirement in moss grotto center if/when this is removed in the randomizer |
| 14 | Mister Mushroom Meeting Bone Bottom | shakra platform | after THE Mister Mushroom Meeting Moss Grotto AND Needolin |  | Verified | event | ✓ |  |
| 15 | skull tyrant bone bottom boss fight | ground level | complete THE the terrible tyrant wish granted AND ( visit blasted steps  OR visit the citadel  OR visit sinners road ) AND Combat Requirements |  | Verified | boss | ✓ | may be other hidden requirements. wiki says 30% chance of spawn after reaching key areas and using a bench in the zone. |
| 16 | Aknid 1 | upper right platforms | Normal World Spawn |  | Verified | enemy | ✓ |  |
| 17 | Aknid 2 | upper right platforms | Normal World Spawn |  | Verified | enemy | ✓ | Spawn conditions: bonetownAspidBerryCollected=false |
| 18 | Aknid 3 | upper right platforms | Normal World Spawn |  | Verified | enemy | ✓ |  |
| 19 | Snitchfly 1 | ground level | Black Thread World Spawn |  | Verified | enemy | ✓ |  |
| 20 | Snitchfly 2 | ground level | Black Thread World Spawn |  | Verified | enemy | ✓ |  |
| 21 | Snitchfly 3 | ground level | Black Thread World Spawn |  | Verified | enemy | ✓ |  |

## Room Images

### Connections

[![Connections for Bone Bottom Town (Bonetown)](../00-annotations/bone-bottom/bone-bottom-town-connections.png)](../00-annotations/bone-bottom/bone-bottom-town-connections.png)

### Checks

[![Checks for Bone Bottom Town (Bonetown)](../00-annotations/bone-bottom/bone-bottom-town-checks.png)](../00-annotations/bone-bottom/bone-bottom-town-checks.png)

### Scene

[![Scene for Bone Bottom Town (Bonetown)](../00-annotations/bone-bottom/bone-bottom-town-scene.png)](../00-annotations/bone-bottom/bone-bottom-town-scene.png)
