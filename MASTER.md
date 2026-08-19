# Silksong Randomizer Logic

Compiled from the database-generated room notes.

## Moss Grotto

### Moss Grotto Center (Tut_01)

**Game ID:** Tut_01

**Contributors:** herounit

#### Subrooms

- rock bottom
- upper crossing
- center shaft
- side room
- lower crossing
- up and away

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LL | lower left | rock bottom | [Moss Grotto West (Tut_02)](#moss-grotto-west-tut02) | LR | break vines |  |  |  |
| ML | middle left | lower crossing | [Moss Grotto West (Tut_02)](#moss-grotto-west-tut02) | UR | none |  |  |  |
| UL | upper left | upper crossing | [Ruined Chapel (Tut_03)](#ruined-chapel-tut03) | R | break vines |  |  |  |
| LR | lower right | lower crossing | [Moss Grotto East (Tut_01b)](#moss-grotto-east-tut01b) | LL | none |  |  |  |
| UR | upper right | upper crossing | [Moss Grotto East (Tut_01b)](#moss-grotto-east-tut01b) | UL | none |  |  |  |
| C | ceiling | up and away | [Bone Bottom Town (Bonetown)](#bone-bottom-town-bonetown) | RF | has loading zone blocker until you first leave moss grotto |  |  | maybe see if removing this loading zone makes sense? |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| S1 | shaft 1 | up and away | upper crossing | none (falling) |  |  |  |
| S1 | shaft 1 | upper crossing | up and away | silk soar OR ( cling grip AND ( faydown cloak OR run OR dash OR sharpdart OR clawline) ) |  |  | might be some crest options - basically anything that give ANY horizontal distance will enable this claw grip |
| S2 | shaft 2 | upper crossing | center shaft | none (falling) |  |  |  |
| S2 | shaft 2 | center shaft | upper crossing | silk soar OR cling grip |  |  |  |
| SV | side room vines | center shaft | side room | break vines |  |  |  |
| SV | side room vines | side room | center shaft | break vines |  |  |  |
| S3 | shaft 3 | center shaft | lower crossing | none (falling) |  |  |  |
| S3 | shaft 3 | lower crossing | center shaft | silk soar OR cling grip |  |  |  |
| S4 | shaft 4 | lower crossing | rock bottom | none (falling) |  |  |  |
| S4 | shaft 4 | rock bottom | lower crossing | silk soar OR ( cling grip AND faydown cloak ) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| frayed rosary string moss grotto | rock bottom | none |  | Verified | Included |  |
| shell shard cache moss grotto 1 | lower crossing | none |  |  | Included |  |
| moss grotto beast shard | rock bottom | none |  |  | Not included | NOT YET RANDOMIZED  right at game start jump into right room and again into right into upper right room |
| moss grotto rosary chest | side room | none |  |  | Not included | NOT YET RANDOMIZED |

#### Notes

renamed from "moss grotto west" - was mistakenly marked as same room as west room
not having the west part as part of this area causes the graph to be more complex

### Moss Grotto West (Tut_02)

**Game ID:** Tut_02

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | upper right |  | [Moss Grotto Center (Tut_01)](#moss-grotto-center-tut01) | ML | none |  |  | asdf |
| LR | lower right |  | [Moss Grotto Center (Tut_01)](#moss-grotto-center-tut01) | LL | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| shell shard cache moss grotto 5 |  | none |  |  | Included |  |
| shell shard cache moss grotto 6 |  | none |  |  | Included |  |
| shell shard cache moss grotto 7 |  | none |  |  | Included |  |
| moss grotto west mossberry |  | none |  |  | Included |  |

#### Notes

somehow missed this being its own room before

### Moss Grotto East (Tut_01b)

**Game ID:** Tut_01b

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | upper left |  | [Moss Grotto Center (Tut_01)](#moss-grotto-center-tut01) | UR | none |  |  |  |
| LL | lower left |  | [Moss Grotto Center (Tut_01)](#moss-grotto-center-tut01) | LR | none |  |  |  |
| WD | weavenest door |  | [Weavenest Atla Entrance (Weave_04)](#weavenest-atla-entrance-weave04) | WD | needolin |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| shell shard cache moss grotto 2 |  | none |  |  | Included |  |
| shell shard cache moss grotto 3 |  | none |  |  | Included |  |
| shell shard cache moss grotto 4 |  | none |  |  | Included |  |
| moss grotto east mossberry |  | easy skips enabled OR ( run OR dash OR drifter's cloak OR faydown cloak OR silk soar OR clawline OR sharpdart OR shaman crest OR ) |  |  | Included |  |

### Ruined Chapel (Tut_03)

**Game ID:** Tut_03

#### Subrooms

- chapel
- boss room
- bench room

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right | bench room | [Moss Grotto Center (Tut_01)](#moss-grotto-center-tut01) | UL | none |  |  |  |
| AR | ascend rope | chapel | [Bone Bottom Town (Bonetown)](#bone-bottom-town-bonetown) | DR | none |  |  |  |
| CD | chapel door | chapel | [Ruined Chapel Interior](#ruined-chapel-interior) | CD | unknown OR ruined chapel access override |  |  | randomizer currently forces the door open under some conditions |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RB | right boss entrance | bench room | boss room | break vines |  |  |  |
| RB | right boss entrance | boss room | bench room | moss mother defeated |  |  |  |
| LB | left boss entrance | chapel | boss room | none |  |  |  |
| LB | left boss entrance | boss room | chapel | moss mother defeated |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| moss mother boss fight | boss room |  |  |  | Included |  |

#### Notes

ROOM BUG: fighting moss mother without breaking the vines on the right side of the arena (by approaching from the left), you get locked into the arena with darkness still covering the area.

Ascend rope AND the ceiling are valid exits - but I believe they take you to the same bot1 exit on the other side.

### Ruined Chapel Interior

**Contributors:** herounit

#### Subrooms

- ritual chamber
- crest chamber

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| CD | chapel door | ritual chamber | [Ruined Chapel (Tut_03)](#ruined-chapel-tut03) | CD | TODO | TODO |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SS | silk soar spot | ritual chamber | crest chamber | silk soar |  |  |  |
| SS | silk soar spot | crest chamber | ritual chamber | silk soar |  |  |  |

#### Check Locations

No check locations defined.

#### Notes

**UNABLE TO ACCESS IN LOGIC AUDIT MODE**

## Bone Bottom

### Bone Bottom Town (Bonetown)

**Game ID:** Bonetown

**Contributors:** herounit

#### Subrooms

- sky
- ground level
- upper right platforms
- upper middle platforms
- upper left platforms
- chapel roof

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | upper left | upper left platforms | [Bonegrave (Bonegrave)](#bonegrave-bonegrave) | UR | none |  |  |  |
| LL | lower left | ground level | [Bonegrave (Bonegrave)](#bonegrave-bonegrave) | LR | door opened from other side |  |  |  |
| DR | descend rope | ground level | [Ruined Chapel (Tut_03)](#ruined-chapel-tut03) | AR | none |  |  |  |
| RF | right floor | ground level | [Moss Grotto Center (Tut_01)](#moss-grotto-center-tut01) | C | none |  |  |  |
| BD | bellway door | ground level | [Bone Bottom Bellway (Bellway_01)](#bone-bottom-bellway-bellway01) | BD | none |  |  |  |
| LR | lower right | ground level | [The Marrow Entrance (Bone_01)](#the-marrow-entrance-bone01) | LL | none |  |  |  |
| UR | upper right | upper right platforms | [Mosshome Basement (Bone_01b)](#mosshome-basement-bone01b) | LL | none |  |  |  |
| RC | right ceiling | upper right platforms | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | RF | none |  |  |  |
| T3 | left ceiling | sky | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | LF | silk soar |  |  |  |
| T5 | top5 | sky | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) |  |  | TODO | Needs verification | all part of the |
| T2 | top2 | sky | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) |  |  | TODO | Needs verification |  |
| T4 | top4 | sky | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) |  |  | TODO | Needs verification |  |
| T1 | top1 | sky | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) |  |  | TODO | Needs verification |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CC | climb chapel | ground level | chapel roof | silk soar OR ( cling grip AND ( LL door NOT opened OR faydown cloak ) ) |  |  |  |
| SM | soar to middle platforms | ground level | upper middle platforms | silk soar |  |  |  |
| SS | soar to sky exit | ground level | sky | silk soar |  |  |  |
| SR | soar to right platforms | ground level | upper right platforms | silk soar |  |  |  |
| EV | elevator | ground level | upper right platforms | elevator switch flipped |  |  |  |
| CC | climb chapel | chapel roof | ground level | none |  |  |  |
| CR | climb roof | chapel roof | upper left platforms | silk soar OR cling grip |  |  |  |
| CR | climb roof | upper left platforms | chapel roof | none |  |  |  |
| MD | middle platform drift | upper middle platforms | chapel roof | drifter's cloak OR clawline OR ( dash + sharpdart ) |  |  |  |
| SM | soar to middle platforms | upper middle platforms | ground level | none |  |  |  |
| CL | clawline across the sky | upper middle platforms | upper right platforms | clawline |  |  |  |
| CL | clawline across the sky | upper right platforms | upper middle platforms | clawline |  |  |  |
| SR | soar to right platforms | upper right platforms | ground level | none |  |  |  |
| DL | sky drift to right platforms | sky | upper right platforms | drifter's cloak OR horizontal movement tech |  |  |  |
| DR | sky drift to middle platforms | sky | upper middle platforms | drifter's cloak OR horizontal movement tech |  |  |  |
| SS | soar to sky exit | sky | ground level | none |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| bone bottom mossberry | upper right platforms | none |  |  | Included |  |
| elevator switch | upper right platforms | none |  |  | Not included |  |
| rosary cache bone bottom 8 | upper right platforms | none |  |  | Included |  |
| rosary cache bone bottom 9 | upper right platforms | none |  |  | Included |  |
| weaver effigy camora moss grotto | upper middle platforms | none |  |  | Included |  |
| rosary dish bone bottom | upper middle platforms | none |  |  | Not included | NOT CURRENTLY RANDOMIZED |
| mask shard pebbs shop grindle act 3 | ground level |  |  |  | Included | pebb's shop |
| simple key | ground level |  |  |  | Included | pebb's shop |
| bone bottom shop craft metal | ground level |  |  |  | Included | pebb's shop |
| magnetite broach | ground level |  |  |  | Included | pebb's shop |
| wish bone bottom repairs | ground level |  |  |  | Included |  |
| wish a life saving bridge | ground level |  |  |  | Included |  |
| wish an icon of hope | ground level |  |  |  | Included |  |
| wish garb of the pilgrims | ground level |  |  |  | Included |  |
| wish volatile flintbeetles | ground level |  |  |  | Included |  |
| wish the terrible tyrant | ground level |  |  |  | Included |  |
| wish bone bottom supplies | ground level |  |  |  | Included |  |
| boss skull tyrant | ground level |  |  |  | Included |  |
| shell shard cache bone bottom | ground level |  |  |  | Included | is this breaking the statue? STILL MARKED AS ??? ON TRACKER |

### Bone Bottom Bellway (Bellway_01)

**Game ID:** Bellway_01

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BD | bellway door |  | [Bone Bottom Town (Bonetown)](#bone-bottom-town-bonetown) | BD | none |  |  |  |
| BB | bell beast |  | [Bellway Menu](#bellway-menu) | BB | bell beast available AND bone bottom bellway unlocked | TODO |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Bonegrave (Bonegrave)

**Game ID:** Bonegrave

**Contributors:** herounit

#### Subrooms

- upper left exit
- upper right exit
- graveyard

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | upper right | upper right exit | [Bone Bottom Town (Bonetown)](#bone-bottom-town-bonetown) | UL | none |  |  |  |
| LR | lower right | graveyard | [Bone Bottom Town (Bonetown)](#bone-bottom-town-bonetown) | LL | none |  |  |  |
| C | ceiling | upper left exit | [Wormways Lower East (Crawl_07)](#wormways-lower-east-crawl07) | F | silk soar OR cling grip |  |  |  |
| CD | chapel door | graveyard | [Chapel of the Wanderer (Chapel_Wanderer)](#chapel-of-the-wanderer-chapelwanderer) | CD | no wanderer's crest OR wanderer's door override |  |  | "wanderer's door override" is meant to cover any situation that would require the door to stay open, such as rosary cache rando |
| LL | lower left | graveyard | [Bonegrave Passage](#bonegrave-passage) | R | steel soul |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CL | climb | graveyard | upper right exit | cling grip OR silk soar |  |  |  |
| CL | climb | upper right exit | graveyard | none (falling) |  |  |  |
| BW | breakable wall | upper left exit | upper right exit | none (break wall from this side) |  |  |  |
| BW | breakable wall | upper right exit | upper left exit | wall broken from other side |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| boneyard mossberry | graveyard | none |  |  | Included | can be gotten with only jump -tested |
| rosary cache bone bottom 6 | upper right exit | none |  |  | Included |  |
| rosary cache bone bottom 7 | upper right exit | none |  |  | Included |  |
| rosaries on grave | graveyard | none |  |  | Not included | NOT CURRENTLY RANDOMIZED |

### Bonegrave Passage

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right |  | [Bonegrave (Bonegrave)](#bonegrave-bonegrave) | LL | steel soul |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| summoned savior boss fight |  | TODO (steel soul only?) | TODO |  | Included |  |

### Chapel of the Wanderer (Chapel_Wanderer)

**Game ID:** Chapel_Wanderer

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| CD | chapel door |  | [Bonegrave (Bonegrave)](#bonegrave-bonegrave) | CD | none |  |  | apworld may force open |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| wanderer's crest |  | none |  |  | Included |  |
| rosary cache bongrave 1 |  | none |  |  | Included |  |
| rosary cache bongrave 2 |  | none |  |  | Included |  |
| rosary cache bongrave 3 |  | none |  |  | Included |  |
| rosary cache bongrave 4 |  | none |  |  | Included |  |

#### Notes

need see if there are other checks in here

### Mosshome Upper (Mosstown_02)

**Game ID:** Mosstown_02

**Contributors:** herounit

#### Subrooms

- main area
- bottom right area
- upper left area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LF | left floor | main area | [Mosshome Middle (Mosstown_01)](#mosshome-middle-mosstown01) | C | none |  |  |  |
| L | left | main area | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | MR | break wall |  |  | wall can be broken from this side |
| RF | right floor | bottom right area | [Mosshome Side Room (Bone_05b)](#mosshome-side-room-bone05b) | C | none |  |  |  |
| R | right | bottom right area | [Mosshome Druid (Mosstown_02c)](#mosshome-druid-mosstown02c) | L | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RS | right silk blockade | main area | bottom right area | can break silk blockade |  |  |  |
| RS | right silk blockade | bottom right area | main area | can break silk blockade |  |  |  |
| LS | left silk blockade | main area | upper left area | can break silk blockade |  |  |  |
| LS | left silk blockade | upper left area | main area | none (cut to open pathway) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| silkspear | main area | none |  |  | Included |  |
| frayed rosary string bone bottom silkspear passage | upper left area | none |  |  | Included |  |
| rosary cache mosshome 3 | main area | none |  |  | Included |  |
| rosary cache mosshome 4 | main area | none |  |  | Included |  |

#### Notes

known silk blockade breakers = silk spear, sharpdart, rune rage

### Mosshome Middle (Mosstown_01)

**Game ID:** Mosstown_01

**Contributors:** herounit

#### Subrooms

- main area
- upper right area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LR | lower right | main area | [The Marrow Bellway (Bone_05)](#the-marrow-bellway-bone05) | L | none |  |  |  |
| UR | upper right | upper right area | [Mosshome Side Room (Bone_05b)](#mosshome-side-room-bone05b) | L | none |  |  |  |
| F | floor | main area | [Mosshome Lower (Bone_11)](#mosshome-lower-bone11) | C | flip the switch in this area |  |  |  |
| C | ceiling | main area | [Mosshome Upper (Mosstown_02)](#mosshome-upper-mosstown02) | LF |  |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RJ | running jump | main area | upper right area | run OR dash OR silk soar OR faydown cloak OR clawline or sharpdart |  |  |  |
| RJ | running jump | upper right area | main area | none |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| flip switch to open floor exit | main area | none |  |  | Included |  |
| rosary cache mosshome 1 | main area | none |  |  | Included |  |
| rosary cache mosshome 2 | main area | none |  |  | Included |  |

### Mosshome Lower (Bone_11)

**Game ID:** Bone_11

**Contributors:** herounit

#### Subrooms

- main area
- upper left exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LR | lower right | main area | [The Marrow Shakra Intro (Bone_04)](#the-marrow-shakra-intro-bone04) | LL | none |  |  |  |
| UR | upper right | main area | [The Marrow Shakra Intro (Bone_04)](#the-marrow-shakra-intro-bone04) | UL | none |  |  |  |
| L | left | upper left exit | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | LR | none |  |  |  |
| C | ceiling | upper left exit | [Mosshome Middle (Mosstown_01)](#mosshome-middle-mosstown01) | F | must be opened from the other side |  |  |  |
| F | floor | main area | [Mosshome Spool (Bone_11b)](#mosshome-spool-bone11b) | C | must be opened from the other side |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RJ | running jump | main area | upper left exit | easy skips enabled OR run OR dash OR  faydown cloak OR silk soar OR clawline OR sharpdart OR beast crest OR shaman crest |  |  |  |
| RJ | running jump | upper left exit | main area | none (falling) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary cache bone bottom 4 | main area | none |  |  | Included |  |
| rosary cache bone bottom 5 | main area | none |  |  | Included |  |

### Mosshome Side Room (Bone_05b)

**Game ID:** Bone_05b

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [Mosshome Middle (Mosstown_01)](#mosshome-middle-mosstown01) | UR | none |  |  |  |
| C | ceiling |  | [Mosshome Upper (Mosstown_02)](#mosshome-upper-mosstown02) | RF | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| mosshome mossberry |  | none |  |  | Included |  |

### Mosshome Druid (Mosstown_02c)

**Game ID:** Mosstown_02c

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [Mosshome Upper (Mosstown_02)](#mosshome-upper-mosstown02) | R | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| wish berry picking |  | TODO |  |  | Not included | this just gets you druid's eye |
| druid's eye |  | progressive mossberry (3) |  |  | Included | TRACKER WRONG POSITION |
| druid's eyes |  | progressive mossberry (7) |  |  | Included | TRACKER WRONG POSITION |

### Mosshome Spool (Bone_11b)

**Game ID:** Bone_11b

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right |  | [Mosshome Basement (Bone_01b)](#mosshome-basement-bone01b) | UL | none |  |  |  |
| C | ceiling |  | [Mosshome Lower (Bone_11)](#mosshome-lower-bone11) | F | switch in room activated |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| bone bottom spool fragment |  | none |  |  | Included |  |
| floor switch to open ceiling exit |  | none |  |  | Included |  |

### Mosshome Basement (Bone_01b)

**Game ID:** Bone_01b

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LL | lower left |  | [Bone Bottom Town (Bonetown)](#bone-bottom-town-bonetown) | UR | none |  |  |  |
| UL | upper left |  | [Mosshome Spool (Bone_11b)](#mosshome-spool-bone11b) | R | none |  |  | Imported destination text: mosshome spool fragment |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary cache the marrow mosslands passage 1 |  | none |  |  | Included |  |
| rosary cache the marrow mosslands passage 2 |  | none |  |  | Included |  |
| rosary dish |  |  |  |  | Not included | NOT CURRENTLY RANDOMIZED |

### The Big Fall (Aspid_01)

**Game ID:** Aspid_01

**Contributors:** herounit

#### Subrooms

- top area
- upper right ledge
- upper left ledge
- wish ledge
- middle right ledge
- lower left area
- lower right area
- bottom area
- upper silk soar only zone
- lower silk soar only zone

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | ceiling | top area | blasted bridge | F | silk soar |  |  |  |
| UR | upper right | upper right ledge | shellwood grand gate bell | L | none |  |  |  |
| MR | middle right | middle right ledge | [Mosshome Upper (Mosstown_02)](#mosshome-upper-mosstown02) | L | breakable wall -must be opened from the other side (NEEDS VERIFICATION) | TODO | Needs verification | NEEDS VERIFICATION |
| LR | lower right | lower right area | [Mosshome Lower (Bone_11)](#mosshome-lower-bone11) | L | none |  |  |  |
| UL | upper left | upper left ledge | [Wormways Upper East (Crawl_01)](#wormways-upper-east-crawl01) | R | none |  |  |  |
| LL | lower left | lower left area | [Wormways Craggler Hallway (Crawl_04)](#wormways-craggler-hallway-crawl04) | R | none |  |  |  |
| LF | left floor | bottom area | [Bone Bottom Town (Bonetown)](#bone-bottom-town-bonetown) | LC | none |  |  |  |
| RF | right floor | lower right area | [Bone Bottom Town (Bonetown)](#bone-bottom-town-bonetown) | RC | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| F1 | top fall | top area | upper right ledge | none (falling) |  |  |  |
| F2 | upper right ledge fall | upper right ledge | upper left ledge | none (falling |  |  |  |
| F3 | upper left ledge fall | upper left ledge | wish ledge | none (falling) |  |  |  |
| F4 | wish ledge fall | wish ledge | upper silk soar only zone | none (falling) |  |  |  |
| F5 | upper silk soar zone fall | upper silk soar only zone | middle right ledge | none (falling) |  |  |  |
| F6 | middle right ledge fall | middle right ledge | lower silk soar only zone | none (falling) |  |  |  |
| F7 | lower silk soar zone fall | lower silk soar only zone | bottom area | none (falling) |  |  |  |
| F8 | lower left area fall | lower left area | bottom area | none (falling) |  |  |  |
| F9 | lower right area fall | lower right area | bottom area | none (falling) |  |  |  |
| S1 | bottom silk soar | bottom area | lower silk soar only zone | silk soar |  |  |  |
| S2 | lower zone silk soar | lower silk soar only zone | upper silk soar only zone | silk soar |  |  |  |
| S3 | upper zone silk soar | upper silk soar only zone | top area | silk soar |  |  |  |
| LC | lower crossing | lower left area | lower right area | easy skips enabled OR silk soar OR horizontal movement tech OR dash OR run OR cling grip OR faydown cloak OR silk soar |  |  |  |
| LC | lower crossing | lower right area | lower left area | easy skips enabled OR silk soar OR horizontal movement tech OR dash OR run OR cling grip OR faydown cloak |  |  |  |
| WC | wish climb | wish ledge | upper left ledge | silk soar OR cling grip |  |  | can't be collected unless the wish has been started from bellhart |
| UC | upper crossing | upper left ledge | upper right ledge | silk soar OR cling grip OR faydown cloak OR clawline OR sharpdart OR dash |  |  |  |
| UC | upper crossing | upper right ledge | upper left ledge | silk soar OR cling grip OR faydown cloak OR clawline OR sharpdart OR dash |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary cache moss grotto | lower left area | none |  |  | Included |  |
| choral commandment moss grotto | middle right ledge | none |  |  | Included |  |
| wish my missing courier | wish ledge | none |  |  | Included |  |

## Weavenest Atla

### Weavenest Atla Entrance (Weave_04)

**Game ID:** Weave_04

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| WD | weavenest door |  | [Moss Grotto East (Tut_01b)](#moss-grotto-east-tut01b) | WD | needolin |  |  |  |
| R | right |  | [Weavenest Atla Teleporter (Weave_02)](#weavenest-atla-teleporter-weave02) | UL | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Weavenest Atla Teleporter (Weave_02)

**Game ID:** Weave_02

**Contributors:** herounit

#### Subrooms

- upper telepad
- upper shaft
- lower shaft
- lower telepad

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | upper left | upper telepad | [Weavenest Atla Entrance (Weave_04)](#weavenest-atla-entrance-weave04) | R | none |  |  |  |
| UR | upper right | upper telepad | [Weavenest Atla Power (Weave_12)](#weavenest-atla-power-weave12) | L | none |  |  |  |
| MR | middle right | upper shaft | [Weavenest Atla Hallway (Weave_13)](#weavenest-atla-hallway-weave13) | L | none |  |  |  |
| ML | middle left | lower shaft | [Weavenest Atla Spool (Weave_11)](#weavenest-atla-spool-weave11) | R | none |  |  |  |
| LL | lower left | lower telepad | [Weavenest Atla Bench (Weave_07)](#weavenest-atla-bench-weave07) | R | none |  |  |  |
| LR | lower right | lower telepad | [Weavenest Atla Eva (Weave_10)](#weavenest-atla-eva-weave10) | L | break walls |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TP | teleporter | upper telepad | lower telepad | weavenest atla power activation |  |  |  |
| TP | teleporter | lower telepad | upper telepad | weavenest atla power activation |  |  |  |
| SM | shaft middle | lower telepad | upper shaft | cling grip OR silk soar |  |  |  |
| SM | shaft middle | upper shaft | lower telepad | none (falling) |  |  |  |
| SB | shaft base | lower telepad | lower shaft | cling grip OR silk soar |  |  |  |
| SB | shaft base | lower shaft | lower telepad | none (falling) |  |  |  |

#### Check Locations

No check locations defined.

### Weavenest Atla Power (Weave_12)

**Game ID:** Weave_12

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [Weavenest Atla Teleporter (Weave_02)](#weavenest-atla-teleporter-weave02) | UR | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| power activation |  | none |  |  | Not included | NOT CURRENTLY RANDOMIZED |
| weavenest atla map |  | none |  |  | Included | weavenest atla power activation |

### Weavenest Atla Eva (Weave_10)

**Game ID:** Weave_10

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [Weavenest Atla Teleporter (Weave_02)](#weavenest-atla-teleporter-weave02) | LR | break walls AND ( cling grip OR silk soar ) |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| crest of the hunter |  | TODO | TODO |  | Included |  |
| yellow vesticrest |  | TODO | TODO |  | Included |  |
| blue vesticrest |  | TODO | TODO |  | Included |  |
| crest of the hunter 2 |  | TODO | TODO |  | Included |  |
| sylphsong |  | TODO | TODO |  | Included |  |

### Weavenest Atla Bench (Weave_07)

**Game ID:** Weave_07

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right |  | [Weavenest Atla Teleporter (Weave_02)](#weavenest-atla-teleporter-weave02) | LL | none |  |  |  |
| L | left |  | [Weavenest Atla Grotto (Weave_03)](#weavenest-atla-grotto-weave03) | R | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

#### Notes

no checks but there is a bench

### Weavenest Atla Grotto (Weave_03)

**Game ID:** Weave_03

**Contributors:** herounit

#### Subrooms

- pathway
- mossberry platform
- boss room

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right | pathway | [Weavenest Atla Bench (Weave_07)](#weavenest-atla-bench-weave07) | L | break vines |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| MP | mossberry platform jump | pathway | mossberry platform | run OR dash OR drifter's cloak OR faydown cloak OR sharpdart OR clawline OR silk soar OR air stall pogo crest |  |  | air stall crest = shaman, beast, reaper, architect; couldn't make it work with the other three |
| MP | mossberry platform jump | mossberry platform | pathway | none (falling) |  |  |  |
| BR | boss room jump | pathway | boss room | break vines AND ( run OR dash OR drifter's cloak OR faydown cloak OR sharpdart OR clawline OR beast crest ) |  |  | beast pogo clears this easily |
| BR | boss room jump | boss room | pathway | none (falling) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| weavenest atla mossberry | mossberry platform |  |  |  | Included |  |
| double moss mother boss fight | boss room |  |  |  | Included | NOT CURRENTLY TRACKED |
| weavelight | boss room | defeat double moss mother |  |  | Included |  |

### Weavenest Atla Hallway (Weave_13)

**Game ID:** Weave_13

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [Weavenest Atla Teleporter (Weave_02)](#weavenest-atla-teleporter-weave02) | MR | none |  |  |  |
| R | right |  | [Weavenest Atla Lore (Weave_08)](#weavenest-atla-lore-weave08) | L | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Weavenest Atla Lore (Weave_08)

**Game ID:** Weave_08

**Contributors:** herounit

#### Subrooms

- main area
- right exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | main area | [Weavenest Atla Hallway (Weave_13)](#weavenest-atla-hallway-weave13) | R | none |  |  |  |
| R | right | right exit | [Weavenest Atla Mask Shard (Weave_05b)](#weavenest-atla-mask-shard-weave05b) | L | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CL | climb pit | main area | right exit | none (falling) |  |  | need to pogo spikes to get down without movement tech |
| CL | climb pit | right exit | main area | cling grip AND ( dash OR horizontal movement tech OR faydown cloak ) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rune harp weavenest atla | main area | none |  |  | Included |  |
| readable lore tablet | main area | none |  |  | Included | NOT ACTUALLY A CHECK |

### Weavenest Atla Mask Shard (Weave_05b)

**Game ID:** Weave_05b

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [Weavenest Atla Lore (Weave_08)](#weavenest-atla-lore-weave08) | R | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| weavenest alta mask shard |  | silk soar OR ( cling grip AND ( drifter's cloak OR faydown cloak OR clawline OR sharpdart OR  ) ) |  |  | Included | NEEDS VERIFICATION BY SOMEONE BETTER THAN ME |

### Weavenest Atla Snare (Weave_14)

**Game ID:** Weave_14

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | floor |  | [Weavenest Atla Spool (Weave_11)](#weavenest-atla-spool-weave11) | C | none (falling) |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| snare setter |  | none |  |  | Included |  |

### Weavenest Atla Spool (Weave_11)

**Game ID:** Weave_11

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right |  | [Weavenest Atla Teleporter (Weave_02)](#weavenest-atla-teleporter-weave02) | ML | none |  |  |  |
| C | ceiling |  | [Weavenest Atla Snare (Weave_14)](#weavenest-atla-snare-weave14) | F | silk soar OR ( faydown cloak + cling grip ) |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| weavenest atla spool fragment |  | none |  |  | Included |  |

## The Marrow

### The Marrow Entrance (Bone_01)

**Game ID:** Bone_01

**Contributors:** herounit

#### Subrooms

- before gauntlet
- gauntlet room
- after gauntlet
- ceiling exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LL | lower left | before gauntlet | [Bone Bottom Town (Bonetown)](#bone-bottom-town-bonetown) | LR | none |  |  |  |
| LR | lower right | after gauntlet | [The Marrow Bell Bench (Bone_01c)](#the-marrow-bell-bench-bone01c) | LL | none |  |  |  |
| UR | upper right | before gauntlet | [The Marrow Bell Bench (Bone_01c)](#the-marrow-bell-bench-bone01c) | UL | none (breakable wall) |  |  |  |
| C | ceiling | ceiling exit | [The Marrow Shakra Intro (Bone_04)](#the-marrow-shakra-intro-bone04) | F | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DS | door switch | before gauntlet | after gauntlet | flipped door switch |  |  |  |
| DS | door switch | after gauntlet | before gauntlet | none (can flip door switch) |  |  |  |
| UG | upper gauntlet entrance | before gauntlet | gauntlet room | none |  |  |  |
| UG | upper gauntlet entrance | gauntlet room | before gauntlet | defeat gauntlet |  |  |  |
| LG | lower gauntlet entrance | gauntlet room | after gauntlet | defeat gauntlet |  |  |  |
| LG | lower gauntlet entrance | after gauntlet | gauntlet room | defeat gauntlet |  |  |  |
| LP | lowered platform | before gauntlet | ceiling exit | platform lowered OR silk soar OR faydown cloak OR ( run AND clawline ) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| shell shard cache the marrow 1 | before gauntlet | none |  |  | Included |  |
| rosary cache the marrow 1 | after gauntlet | none |  |  | Included |  |
| rosary cache the marrow 2 | after gauntlet | none |  |  | Included |  |
| door switch | after gauntlet | none |  |  | Not included |  |

### The Marrow Bell Bench (Bone_01c)

**Game ID:** Bone_01c

**Contributors:** herounit

#### Subrooms

- falling rocks
- bell bench

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | upper left | falling rocks | [The Marrow Entrance (Bone_01)](#the-marrow-entrance-bone01) | UR | none |  |  |  |
| LL | left left | bell bench | [The Marrow Entrance (Bone_01)](#the-marrow-entrance-bone01) | LR | none |  |  |  |
| R | right | bell bench | [The Marrow Lava Intro (Bone_02)](#the-marrow-lava-intro-bone02) | L | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary cache the marrow 5 | falling rocks | none |  |  | Included |  |
| rosary cache the marrow 6 | falling rocks | none |  |  | Included |  |
| rosary cache the marrow 3 | bell bench | none |  |  | Included |  |
| rosary cache the marrow 4 | bell bench | none |  |  | Included |  |
| bench unlock | bell bench | pay monies |  |  | Not included | NOT CURRENTLY RANDOMIZED |

#### Notes

While falling rocks and the bell bench are the same in-game room, there is no connection between them. So no subroom connections here is to be expected.

### The Marrow Lava Intro (Bone_02)

**Game ID:** Bone_02

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [The Marrow Bell Bench (Bone_01c)](#the-marrow-bell-bench-bone01c) | R | none |  |  |  |
| R | right |  | [The Marrow Lava Track (Bone_16)](#the-marrow-lava-track-bone16) | L | none |  |  |  |
| LC | left ceiling |  | [The Marrow Shaft (Bone_03)](#the-marrow-shaft-bone03) | F | none |  |  |  |
| RC | right ceiling |  | [The Marrow Flea Caravan (Bone_10)](#the-marrow-flea-caravan-bone10) | F | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

#### Notes

no checks

### The Marrow Lava Track (Bone_16)

**Game ID:** Bone_16

**Contributors:** herounit

#### Subrooms

- left track
- right track
- left maze
- right maze

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | left track | [The Marrow Lava Intro (Bone_02)](#the-marrow-lava-intro-bone02) | R | none |  |  |  |
| R | right | right track | [The Marrow Lava Docks (Bone_09)](#the-marrow-lava-docks-bone09) | L | none |  |  |  |
| C | ceiling | left maze | [The Marrow Skull Tyrant Arena (Bone_15)](#the-marrow-skull-tyrant-arena-bone15) | F | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LT | lava track | right track | left track | activate track OR ( clawline AND shaman crest ) |  |  |  |
| LT | lava track | left track | right track | activate track OR ( clawline AND shaman crest ) |  |  |  |
| CR | climb right | right track | right maze | cling grip OR silk soar |  |  |  |
| CR | climb right | right maze | right track | none (falling) |  |  |  |
| CL | climb left | right maze | left maze | cling grip OR faydown cloak |  |  |  |
| CL | climb left | left maze | right maze | none (falling) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| activate track | right track | none |  |  | Not included |  |
| rosary cache the marrow 11 |  | none | TODO |  | Not included | one of these is in right maze |
| rosary cache the marrow 12 |  | none | TODO |  | Not included | one of these is in right maze |
| rosary cache the marrow 13 |  | none | TODO |  | Not included | one of these is in right maze |

### The Marrow Flea Caravan (Bone_10)

**Game ID:** Bone_10

**Contributors:** herounit

#### Subrooms

- main area
- behind metal gate

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | main area | [The Marrow Shaft (Bone_03)](#the-marrow-shaft-bone03) | LR | none |  |  |  |
| R | right | behind metal gate | [The Marrow Skull Tyrant Arena (Bone_15)](#the-marrow-skull-tyrant-arena-bone15) | L | none |  |  |  |
| F | floor | main area | [The Marrow Lava Intro (Bone_02)](#the-marrow-lava-intro-bone02) | RC | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DS | door switch | main area | behind metal gate | door switch activated |  |  |  |
| DS | door switch | behind metal gate | main area | none (can flip switch from this side) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| frayed rosary string the marrow flea caravan passage |  | none |  |  | Included |  |
| rosary dish |  | none | TODO |  | Not included | NOT CURRENTLY RANDOMIZED |
| wish survivor's camp supplies |  | TODO | TODO |  | Included | TODO |

### The Marrow Shaft (Bone_03)

**Game ID:** Bone_03

**Contributors:** herounit

#### Subrooms

- lower shaft
- upper shaft

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | floor | lower shaft | [The Marrow Lava Intro (Bone_02)](#the-marrow-lava-intro-bone02) | LC | none |  |  |  |
| LL | lower left | lower shaft | [The Marrow Shaft Side Room (Bone_17)](#the-marrow-shaft-side-room-bone17) | R | none |  |  |  |
| ML | middle left | lower shaft | [The Marrow Shakra Intro (Bone_04)](#the-marrow-shakra-intro-bone04) | R | none |  |  |  |
| UL | upper left | upper shaft | [The Marrow Bellshrine (Bellshrine)](#the-marrow-bellshrine-bellshrine) | R | bell must be rung |  |  |  |
| LR | lower right | lower shaft | [The Marrow Flea Caravan (Bone_10)](#the-marrow-flea-caravan-bone10) | L | none |  |  |  |
| UR | upper right | upper shaft | [The Marrow Mr Burns House (Bone_14)](#the-marrow-mr-burns-house-bone14) | L | none |  |  |  |
| C | ceiling | upper shaft | [The Marrow Skull Wall (Bone_06)](#the-marrow-skull-wall-bone06) | F | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DS | door switch | lower shaft | upper shaft | door switch flipped |  |  |  |
| DS | door switch | upper shaft | lower shaft | none (can flip switch from here) |  |  |  |

#### Check Locations

No check locations defined.

#### Notes

no checks

### The Marrow Shaft Side Room (Bone_17)

**Game ID:** Bone_17

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right |  | [The Marrow Shaft (Bone_03)](#the-marrow-shaft-bone03) | LL | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| shard pendant |  | none |  |  | Included |  |

### The Marrow Shakra Intro (Bone_04)

**Game ID:** Bone_04

**Contributors:** herounit

#### Subrooms

- behind gate
- main area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right | main area | [The Marrow Shaft (Bone_03)](#the-marrow-shaft-bone03) | ML | none |  |  |  |
| F | floor | main area | [The Marrow Entrance (Bone_01)](#the-marrow-entrance-bone01) | C | none |  |  |  |
| LL | lower left | main area | [Mosshome Lower (Bone_11)](#mosshome-lower-bone11) | LR | none |  |  |  |
| UL | upper right | behind gate | [Mosshome Lower (Bone_11)](#mosshome-lower-bone11) | UR | none |  |  |  |
| C | ceiling | main area | [The Marrow Bellway (Bone_05)](#the-marrow-bellway-bone05) | F | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DS | door switch | main area | behind gate | door switch flipped |  |  |  |
| DS | door switch | behind gate | main area | none (can flip door switch from this side) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| lower platform switch (into floor) | main area | lowers platform into the marrow entrance |  |  | Not included | NOT CURRENTLY RANDOMIZED |
| rosary cache the marrow 7 | main area | none |  |  | Included |  |
| shell shard cache the marrow 2 | main area | none |  |  | Included |  |
| shell shard cache the marrow 3 | main area | none |  |  | Included |  |
| quill | main area |  |  |  | Included | shakra's shop |
| compass | main area |  |  |  | Included | shakra's shop |
| map mosslands | main area |  |  |  | Included | shakra's shop |
| map the marrow | main area |  |  |  | Included | shakra's shop |
| map bench pins | main area |  |  |  | Included | shakra's shop |
| map bellway pins | main area |  |  |  | Included | shakra's shop \| appears to be bugged in availability logic still. shows available but isn't |
| mosshome middle door switch | behind gate | none |  |  | Not included |  |

### The Marrow Bellway (Bone_05)

**Game ID:** Bone_05

**Contributors:** herounit

#### Subrooms

- left area
- boss room
- right area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | left area | [Mosshome Middle (Mosstown_01)](#mosshome-middle-mosstown01) | LR | none |  |  |  |
| F | floor | left area | [The Marrow Shakra Intro (Bone_04)](#the-marrow-shakra-intro-bone04) | C | none |  |  |  |
| R | right | right area | [The Marrow Bellshrine (Bellshrine)](#the-marrow-bellshrine-bellshrine) | L | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LB | left boss fight | left area | boss room | none |  |  |  |
| LB | left boss fight | boss room | left area | none |  |  | boss fight doesn't start automatically so can leave any time |
| RB | right boss fight | right area | boss room | bell beast defeated |  |  | can't enter the arena from this side |
| RB | right boss fight | boss room | right area | bell beast defeated |  |  | bell beast defeated needs to be here to gate this from seemingly like a straight passthrough |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| bell beast boss fight | boss room | silk spear |  |  | Included | sharpdart doesn't work |
| silk heart bell beast | boss room | bell beast defeated |  |  | Included |  |

### The Marrow Bellshrine (Bellshrine)

**Game ID:** Bellshrine

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [The Marrow Bellway (Bone_05)](#the-marrow-bellway-bone05) | R | none |  |  |  |
| R | right |  | [The Marrow Shaft (Bone_03)](#the-marrow-shaft-bone03) | UL | bell must be rung |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| ring bell switch |  |  |  |  | Included | this opens the right exit |

### The Marrow Skull Wall (Bone_06)

**Game ID:** Bone_06

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | floor |  | [The Marrow Shaft (Bone_03)](#the-marrow-shaft-bone03) | C | none |  |  |  |
| R | right |  | [The Marrow Skull Wall Side Room (Bone_18)](#the-marrow-skull-wall-side-room-bone18) | L | none |  |  |  |
| L | left |  | TODO |  | opens from the other side | TODO |  | shellwood |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| flea the marrow |  | none |  |  | Included |  |

### The Marrow Skull Wall Side Room (Bone_18)

**Game ID:** Bone_18

**Contributors:** herounit

#### Subrooms

- lower level
- upper level

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | lower level | [The Marrow Skull Wall (Bone_06)](#the-marrow-skull-wall-bone06) | R | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CG | climb | lower level | upper level | cling grip or silk soar |  |  |  |
| CG | climb | upper level | lower level | cling grip or silk soar |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| lore tablet | lower level |  |  |  | Not included | NOT ACTUALLY A CHECK |
| memory locket the marrow | upper level |  | TODO |  | Included | on the tracker but appears to be inaccessible |
| gauntlet fight | upper level |  | TODO |  | Not included | not on the tracker / what are the trigger conditions? |

### The Marrow Mr Burns House (Bone_14)

**Game ID:** Bone_14

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [The Marrow Shaft (Bone_03)](#the-marrow-shaft-bone03) | UR | none |  |  |  |
| R | right |  | [The Marrow Lower Pogo (Bone_07)](#the-marrow-lower-pogo-bone07) | L | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary cache the marrow 10 |  | none |  |  | Included |  |
| shell shard cache the marrow 5 |  |  |  |  | Included |  |
| shell shard cache the marrow 6 |  |  |  |  | Included |  |

### The Marrow Lower Pogo (Bone_07)

**Game ID:** Bone_07

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [The Marrow Mr Burns House (Bone_14)](#the-marrow-mr-burns-house-bone14) | R | none |  |  |  |
| UR | upper right |  | [The Marrow Jail Pathway (Bone_08)](#the-marrow-jail-pathway-bone08) | UL | none |  |  |  |
| LR | upper left |  | [The Marrow Jail Pathway (Bone_08)](#the-marrow-jail-pathway-bone08) | LL | none |  |  |  |
| C | ceiling |  | [The Marrow Upper Pogo (Bone_19)](#the-marrow-upper-pogo-bone19) | F | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| craft metal |  | none |  |  | Included |  |
| shell shard cache the marrow 4 |  | none |  |  | Included | MARKED AS ??? ON TRACKER |

### The Marrow Upper Pogo (Bone_19)

**Game ID:** Bone_19

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | floor |  | [The Marrow Lower Pogo (Bone_07)](#the-marrow-lower-pogo-bone07) | C | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary cache the marrow 14 |  | none |  |  | Included |  |
| rosary cache the marrow 15 |  | none |  |  | Included |  |
| rosary cache the marrow 16 |  | none |  |  | Included |  |
| rosary chest |  | none |  |  | Not included | NOT RANDOMIZED YET |

### The Marrow Jail Pathway (Bone_08)

**Game ID:** Bone_08

**Contributors:** herounit

#### Subrooms

- upper area
- lower area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | upper left | upper area | [The Marrow Lower Pogo (Bone_07)](#the-marrow-lower-pogo-bone07) | UR |  |  |  |  |
| LL | lower left | lower area | [The Marrow Lower Pogo (Bone_07)](#the-marrow-lower-pogo-bone07) | LR |  |  |  |  |
| UR | upper right | upper area | TODO |  |  | TODO |  | bellhart |
| MR | middle right | lower area | [Hunter's March Entrance (Ant_02)](#hunters-march-entrance-ant02) | L | none | TODO |  | hunter's march |
| JD | lower right | lower area | [The Marrow Jail (Bone_12)](#the-marrow-jail-bone12) | L |  |  |  |  |
| F | floor | lower area | [The Marrow Lava Docks (Bone_09)](#the-marrow-lava-docks-bone09) | C |  |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| PS | platform switch | upper area | lower area | none (falling) |  |  |  |
| PS | platform switch | lower area | upper area | platform switch activated (at top of area) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| platform switch | upper area | none |  |  | Included |  |
| rosary cache the marrow 8 | lower area | none |  |  | Included |  |
| rosary cache the marrow 9 | lower area | none |  |  | Included |  |

### The Marrow Jail (Bone_12)

**Game ID:** Bone_12

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [The Marrow Jail Pathway (Bone_08)](#the-marrow-jail-pathway-bone08) | JD | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| straight pin |  | none |  |  | Included |  |
| pin minigame 1 |  |  |  |  | Included | straight pin minigame either missing or too early |
| pin minigame 2 |  |  |  |  | Included |  |

### The Marrow Lava Docks (Bone_09)

**Game ID:** Bone_09

**Contributors:** herounit

#### Subrooms

- elevated platforms
- main area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | ceiling | main area | [The Marrow Jail Pathway (Bone_08)](#the-marrow-jail-pathway-bone08) | F | none |  |  |  |
| L | left | main area | [The Marrow Lava Track (Bone_16)](#the-marrow-lava-track-bone16) | R | none |  |  |  |
| LR | lower right | main area | [Deep Docks Entrance (Dock_08)](#deep-docks-entrance-dock08) | LL | none |  |  |  |
| UR | upper right | elevated platforms | [Deep Docks Entrance (Dock_08)](#deep-docks-entrance-dock08) | UL | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CG | climb | main area | elevated platforms | cling grip OR silk soar OR faydown cloak |  |  |  |
| CG | climb | elevated platforms | main area | none (falling) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary spike | main area | none |  |  | Included | NOT RANDOMIZED YET |

### The Marrow Skull Tyrant Arena (Bone_15)

**Game ID:** Bone_15

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | floor |  | [The Marrow Lava Track (Bone_16)](#the-marrow-lava-track-bone16) | C | none |  |  |  |
| L | left |  | [The Marrow Flea Caravan (Bone_10)](#the-marrow-flea-caravan-bone10) | R | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| silk spool |  | none |  |  | Included | NOT RANDOMIZED YET |
| skull tyrant boss fight |  | none |  |  | Included | NOT RANDOMIZED YET |
| crown fragment |  | defeat skull tyrant |  |  | Included | NOT RANDOMIZED YET |

## Wormways

### Wormways Craggler Hallway (Crawl_04)

**Game ID:** Crawl_04

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [Wormways Shaft (Crawl_02)](#wormways-shaft-crawl02) | LR | none |  |  |  |
| R | right |  | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | LL | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| craggler mini boss fight |  | none |  |  | Included |  |
| beast shard |  | defeat craggler |  |  | Not included | NOT CURRENTLY RANDOMIZED |

### Wormways Shaft (Crawl_02)

**Game ID:** Crawl_02

**Contributors:** herounit

#### Subrooms

- lower area
- middle platform area
- upper platform area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LR | lower right | lower area | [Wormways Craggler Hallway (Crawl_04)](#wormways-craggler-hallway-crawl04) | L | none |  |  |  |
| LL | lower left | lower area | [Wormways Middle (Crawl_03b)](#wormways-middle-crawl03b) | R | door unlocked |  |  |  |
| UL | upper left | upper platform area | [Wormways Upper West (Crawl_03)](#wormways-upper-west-crawl03) | R | breakable wall -must be opened from the other side (verified) |  |  |  |
| UR | upper right | middle platform area | [Wormways Upper East (Crawl_01)](#wormways-upper-east-crawl01) | L | none |  |  |  |
| MR | middle right | middle platform area | [Wormways Flea Rescue (Crawl_06)](#wormways-flea-rescue-crawl06) | L | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DS | door switch | middle platform area | lower area | none (door switch is on this side) |  |  |  |
| DS | door switch | lower area | middle platform area | door switch needs to be flipped |  |  |  |
| CG | platform gaps | middle platform area | upper platform area | silk soar OR cling grip |  |  |  |
| CG | platform gaps | upper platform area | middle platform area | none (falling) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| use simple key on lock | lower area | simple key |  |  | Included | unlocks the LL room exit |
| mask shard wormways | lower area | none |  |  | Included |  |
| frayed rosary string wormways | upper platform area | cling grip OR silk soar |  |  | Included |  |
| flip door switch | middle platform area | none |  |  | Not included | unlocks the middle/lower shortcut |

### Wormways Flea Rescue (Crawl_06)

**Game ID:** Crawl_06

**Contributors:** herounit

#### Subrooms

- entrance
- main area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | entrance | [Wormways Shaft (Crawl_02)](#wormways-shaft-crawl02) | MR | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| D | dash | entrance | main area | none |  |  | spike pogo |
| D | dash | main area | entrance | none |  |  | spike pogo |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| flea wormways snacc | main area | none |  |  | Included |  |

### Wormways Middle (Crawl_03b)

**Game ID:** Crawl_03b

**Contributors:** herounit

#### Subrooms

- right area
- left area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right | right area | [Wormways Shaft (Crawl_02)](#wormways-shaft-crawl02) | LL | door must be unlocked from the other side |  |  |  |
| F | floor | right area | [Wormways Lower East (Crawl_07)](#wormways-lower-east-crawl07) | C | none |  |  | Imported destination text: wormways lower east - C |
| C | ceiling | left area | [Wormways Upper West (Crawl_03)](#wormways-upper-west-crawl03) | F | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RJ | running jump | left area | right area | run OR dash OR drifter's cloak OR faydown cloak OR sharpdart OR clawline |  |  |  |
| RJ | running jump | right area | left area | none (falling) |  |  |  |

#### Check Locations

No check locations defined.

### Wormways Upper West (Crawl_03)

**Game ID:** Crawl_03

**Contributors:** herounit

#### Subrooms

- main area
- plasmium spot
- weavenest landing

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | floor | main area | [Wormways Middle (Crawl_03b)](#wormways-middle-crawl03b) | C |  |  |  |  |
| R | right | main area | [Wormways Shaft (Crawl_02)](#wormways-shaft-crawl02) | UL |  |  |  |  |
| C | ceiling | main area | [Wormways Laboratory (Crawl_08)](#wormways-laboratory-crawl08) | F | silk soar OR cling grip |  |  |  |
| WD | weaver door | weavenest landing | [Wormways Weavenest (Crawl_05)](#wormways-weavenest-crawl05) | WD | needolin |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CG | climb | main area | plasmium spot | cling grip OR silk soar OR faydown cloak |  |  |  |
| CG | climb | plasmium spot | main area | cling grip OR silk soar OR faydown cloak |  |  |  |
| BJ | big jump | main area | weavenest landing | silk soar OR faydown cloak OR ( run AND dash AND clawline ) |  |  |  |
| BJ | big jump | weavenest landing | main area | none (falling) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| plasmium pustule upper west | plasmium spot | needle phial AND red tool slot |  |  | Included | NOT RANDOMIZED YET |

### Wormways Upper East (Crawl_01)

**Game ID:** Crawl_01

**Contributors:** herounit

#### Subrooms

- lower area
- upper area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | lower area | [Wormways Shaft (Crawl_02)](#wormways-shaft-crawl02) | UR | none |  |  |  |
| R | right | upper area | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | UL | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LD | left dash | lower area | upper area | run OR dash OR cling grip OR drifter's cloak OR faydown cloak OR sharpdart OR clawline |  |  |  |
| LD | left dash | upper area | lower area | none (falling) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| dead bugs purse | upper area | none |  |  | Included | STILL MARKED AS ??? ON TRACKER |
| shakra shop items | upper area |  |  |  | Included | :) |

### Wormways Laboratory (Crawl_08)

**Game ID:** Crawl_08

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | floor |  | [Wormways Upper West (Crawl_03)](#wormways-upper-west-crawl03) | C |  |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| needle phial |  | none |  |  | Included |  |
| plasmium phial |  | filled needle phial |  |  | Included |  |
| wish missing assitant |  | TODO | TODO |  | Included |  |
| wish alchemist assistant |  |  |  |  | Not included |  |

### Wormways Lower East (Crawl_07)

**Game ID:** Crawl_07

**Contributors:** herounit

#### Subrooms

- ceiling exit area
- left exit area
- tunnels
- floor exit area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | ceiling | ceiling exit area | [Wormways Middle (Crawl_03b)](#wormways-middle-crawl03b) | F | none |  |  |  |
| L | left | left exit area | [Wormways Lower West (Crawl_09)](#wormways-lower-west-crawl09) | R | none |  |  |  |
| F | floor | floor exit area | [Bonegrave (Bonegrave)](#bonegrave-bonegrave) | C | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CC | ceiling climb | ceiling exit area | tunnels | cling grip |  |  |  |
| CC | ceiling climb | tunnels | ceiling exit area | cling grip |  |  |  |
| LC | left climb | left exit area | tunnels | cling grip |  |  |  |
| LC | left climb | tunnels | left exit area | cling grip |  |  |  |
| RC | floor climb | floor exit area | tunnels | cling grip |  |  |  |
| RC | floor climb | tunnels | floor exit area | cling grip |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| plasmium pustule lower east | tunnels | needle phial AND red tool slot |  |  | Not included | NOT CURRENTLY RANDOMIZED |

#### Notes

this one seems a bit tricky, but also it's just a bit late

i think you need cling grip to from any one point to another in here

TODO: review the mapping in here

### Wormways Lower West (Crawl_09)

**Game ID:** Crawl_09

**Contributors:** herounit

#### Subrooms

- left exit area
- right exit area
- tunnels

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right | right exit area | [Wormways Lower East (Crawl_07)](#wormways-lower-east-crawl07) | L | none |  |  |  |
| L | left | left exit area | [Wormways Zango Arena (Crawl_10)](#wormways-zango-arena-crawl10) | R | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LC | left climb | left exit area | tunnels | cling grip |  |  |  |
| LC | left climb | tunnels | left exit area | cling grip |  |  |  |
| RC | right climb | right exit area | tunnels | cling grip |  |  |  |
| RC | right climb | tunnels | right exit area | cling grip |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| memory locket | tunnels | none |  |  | Included |  |
| plasmium pustule lower west | tunnels | needle phial AND red tool slot |  |  | Included | NOT RANDOMIZED YET |

#### Notes

this one seems a bit tricky, but also it's just a bit late

i think you need cling grip to from any one point to another in here

TODO: review the mapping in here

### Wormways Weavenest (Crawl_05)

**Game ID:** Crawl_05

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| WD | weaver door |  | [Wormways Upper West (Crawl_03)](#wormways-upper-west-crawl03) | WD | needolin |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| sharpdart |  | none |  |  | Included |  |

### Wormways Zango Arena (Crawl_10)

**Game ID:** Crawl_10

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right |  | [Wormways Lower West (Crawl_09)](#wormways-lower-west-crawl09) | L | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| plasmified zango boss fight |  | TODO (act 3?) | TODO |  | Included |  |

## Deep Docks

### Deep Docks Entrance (Dock_08)

**Game ID:** Dock_08

**Contributors:** herounit

#### Subrooms

- main pathway
- gauntlet left
- gauntlet
- gauntlet right

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LL | left1 | gauntlet right | [The Marrow Lava Docks (Bone_09)](#the-marrow-lava-docks-bone09) | LR | none |  | Needs verification |  |
| UL | left2 | main pathway | [The Marrow Lava Docks (Bone_09)](#the-marrow-lava-docks-bone09) | UR | none |  | Needs verification |  |
| R | right1 | main pathway | [Deep Docks Bench Shaft (Dock_01)](#deep-docks-bench-shaft-dock01) | L | none |  | Needs verification |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DS | door switch | main pathway | gauntlet right | switch flipped |  | Needs verification |  |
| DS | door switch | gauntlet right | main pathway | none (switch is on this side) |  | Needs verification |  |
| GL | gauntlet fight left | gauntlet left | gauntlet | none (starts gauntlet) |  | Needs verification |  |
| GL | gauntlet fight left | gauntlet | gauntlet left | defeat gauntlet |  | Needs verification |  |
| GR | gauntlet fight right | gauntlet | gauntlet right | defeat gauntlet |  | Needs verification |  |
| GR | gauntlet fight right | gauntlet right | gauntlet | none (starts gauntlet) |  | Needs verification | probably not possible to reach unless switch is flipped via AP check |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| door switch | gauntlet right | none |  | Needs verification | Not included |  |
| gauntlet | gauntlet | none |  | Needs verification | Not included |  |
| mask shard the marrow deep docks passage | gauntlet right | none |  | Needs verification | Included |  |

### Deep Docks Bench Shaft (Dock_01)

**Game ID:** Dock_01

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | right1 |  | [Deep Docks Upper Spire (Bone_East_05)](#deep-docks-upper-spire-boneeast05) | L | gate unlocked from other side |  | Needs verification | must be unlocked from the other side |
| LR | right2 |  | [Deep Docks Map Shop (Bone_East_01)](#deep-docks-map-shop-boneeast01) | UL | none |  | Needs verification |  |
| L | left1 |  | [Deep Docks Entrance (Dock_08)](#deep-docks-entrance-dock08) | R | none |  | Needs verification |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| bench rosary lock |  | none |  |  | Not included |  |
| bench |  | unlock bench |  |  | Not included |  |
| rosary cache deep docks 7 |  | none |  |  | Included | MARKED AS ??? ON TRACKER |
| rosary cache deep docks 8 |  | none |  |  | Included | MARKED AS ??? ON TRACKER |
| shell shard cache deep docks 4 |  | none |  |  | Included | MARKED AS ??? ON TRACKER |

### Deep Docks Map Shop (Bone_East_01)

**Game ID:** Bone_East_01

**Contributors:** herounit

#### Subrooms

- upper area
- lower area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | left1 | lower area | [Deep Docks Bench Shaft (Dock_01)](#deep-docks-bench-shaft-dock01) | LR | none |  | Needs verification |  |
| LL | left2 | lower area | [Deep Docks Bellway (Bellway_02)](#deep-docks-bellway-bellway02) | R | none |  | Needs verification |  |
| UR | right1 | upper area | [Deep Docks Spire Lower (Bone_East_03)](#deep-docks-spire-lower-boneeast03) | L | none |  | Needs verification |  |
| MR | right2 | lower area | [Deep Docks Map Shop Side Room (Dock_05)](#deep-docks-map-shop-side-room-dock05) | L | none |  | Needs verification |  |
| LR | right3 | lower area | [Deep Docks Lace Intro (Bone_East_12)](#deep-docks-lace-intro-boneeast12) | L | none |  | Needs verification |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LP | lower platform | lower area | upper area | flip switch to lower platform |  | Needs verification |  |
| LP | lower platform | upper area | lower area | none (falling) |  | Needs verification |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| map purchase deep docks | lower area | none |  | Needs verification | Included | shakra shop |
| pin purchase vendor pins | lower area | none |  | Needs verification | Included | shakra shop |
| switch to upper lower platform | lower area | none |  | Needs verification | Not included | NOT CURRENTLY RANDOMIZED |
| switch to lower lower platform | lower area | none |  | Needs verification | Not included | NOT CURRENTLY RANDOMIZED (doesn't currently really block anything since you can just jump above and fall down) |

### Deep Docks Map Shop Side Room (Dock_05)

**Game ID:** Dock_05

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Deep Docks Map Shop (Bone_East_01)](#deep-docks-map-shop-boneeast01) | MR | none |  | Needs verification |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

#### Notes

nothing to see here - just murder sleeping dudes

### Deep Docks Bellway (Bellway_02)

**Game ID:** Bellway_02

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Deep Docks Bellway Flea Rescue (Dock_16)](#deep-docks-bellway-flea-rescue-dock16) | R | break wall |  | Needs verification |  |
| BB | door_fastTravelExit |  | [Bellway Menu](#bellway-menu) | DD | bellway unlocked |  | Needs verification |  |
| R | right1 |  | [Deep Docks Map Shop (Bone_East_01)](#deep-docks-map-shop-boneeast01) | LL | none |  | Needs verification |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| bellway pay lock |  | none |  | Needs verification | Not included |  |

### Deep Docks Bellway Flea Rescue (Dock_16)

**Game ID:** Dock_16

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Deep Docks Bellway (Bellway_02)](#deep-docks-bellway-bellway02) | L | none |  | Needs verification |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| flea rescue |  | none |  | Needs verification | Included |  |

### Deep Docks Lace Intro (Bone_East_12)

**Game ID:** Bone_East_12

**Contributors:** herounit

#### Subrooms

- left area
- switch platform
- boss arena
- right area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | left area | [Deep Docks Map Shop (Bone_East_01)](#deep-docks-map-shop-boneeast01) | LR | none |  |  |  |
| R | right1 | right area | [Deep Docks Bellshrine (Bellshrine_05)](#deep-docks-bellshrine-bellshrine05) | L | none |  |  |  |
| F | bot1 | left area | [Deep Docks Forge (Room_Forge)](#deep-docks-forge-roomforge) | C | airlock lever |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SP | lever platform jump | left area | switch platform | run OR dash OR drifter's cloak OR faydown cloak OR silk soar OR clawline OR sharpdart OR beast crest |  |  |  |
| SP | lever platform jump | switch platform | left area | none (falling) |  |  |  |
| BL | boss arena left | left area | boss arena | gate switch flipped |  |  |  |
| BL | boss arena left | boss arena | left area | gate switch flipped AND defeat lace |  |  |  |
| BR | boss arena right | boss arena | right area | defeat lace |  |  |  |
| BR | boss arena right | right area | boss arena | none |  | Verified | NEEDS VERIFICATION |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| gate switch | switch platform | none |  |  | Not included |  |
| lace 1 boss fight | boss arena | none |  |  | Included |  |

### Deep Docks Bellshrine (Bellshrine_05)

**Game ID:** Bellshrine_05

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Deep Docks Lace Intro (Bone_East_12)](#deep-docks-lace-intro-boneeast12) | R | none |  |  |  |
| R | right1 |  | [Far Fields Entrance East (Bone_East_02)](#far-fields-entrance-east-boneeast02) | L | deep docks bellshrine activated |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| activate deep docks bellshrine switch |  | none |  |  | Not included |  |
| bench :) |  | deep docks bellshrine activated |  |  | Not included |  |

### Deep Docks Spire Lower (Bone_East_03)

**Game ID:** Bone_East_03

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | top1 |  | [Is this still Deep Docks? (East) (Bone_East_04)](#is-this-still-deep-docks-east-boneeast04) | F | hit blast rock, opens exit |  |  |  |
| L | left1 |  | [Deep Docks Map Shop (Bone_East_01)](#deep-docks-map-shop-boneeast01) | UR | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Is this still Deep Docks? (East) (Bone_East_04)

**Game ID:** Bone_East_04

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | top2 |  | [Hunter's March Deep Docks Passage (Ant_05b)](#hunters-march-deep-docks-passage-ant05b) | RF | none |  |  |  |
| UR | right2 |  | ["Deep Docks" March Side Room (Bone_East_04c)](#deep-docks-march-side-room-boneeast04c) | L | silk soar OR cling grip OR faydown cloak |  |  |  |
| LR | right1 |  | [Far Fields Deep Docks Loopback (Bone_East_15)](#far-fields-deep-docks-loopback-boneeast15) | L | none |  |  |  |
| L | left1 |  | [Is this still Deep Docks? (West) (Bone_East_04b)](#is-this-still-deep-docks-west-boneeast04b) | R | wall must be destroyed from the other side |  |  |  |
| F | bot1 |  | [Deep Docks Spire Lower (Bone_East_03)](#deep-docks-spire-lower-boneeast03) | C | floor must be destroyed from the other side |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Is this still Deep Docks? (West) (Bone_East_04b)

**Game ID:** Bone_East_04b

**Contributors:** herounit

#### Subrooms

- side room
- ground
- upper level

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | ground | [Is this still Deep Docks? (East) (Bone_East_04)](#is-this-still-deep-docks-east-boneeast04) | L | attack blast rock, unblocks wall |  |  |  |
| C | top1 | upper level | [Hunter's March Deep Docks Passage (Ant_05b)](#hunters-march-deep-docks-passage-ant05b) | LF |  |  |  |  |
| L | left1 | ground | [Deep Docks Upper Spire (Bone_East_05)](#deep-docks-upper-spire-boneeast05) | R |  |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BW | break wall | side room | ground | break wall (left) |  |  |  |
| BW | break wall | ground | side room | none |  |  |  |
| BJ | big jump | ground | upper level | silk soar OR faydown cloak OR cling grip |  |  |  |
| BJ | big jump | upper level | ground | none (falling) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| blast rock pathway opener | ground | blast rock |  |  | Not included |  |
| frayed rosary string deep docks | side room | none |  |  | Included | MARKED AS ??? ON TRACKER |

### "Deep Docks" March Side Room (Bone_East_04c)

**Game ID:** Bone_East_04c

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Is this still Deep Docks? (East) (Bone_East_04)](#is-this-still-deep-docks-east-boneeast04) | UR |  |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

#### Notes

just a camp? no enemies? did we find bush girl here at some point?

### Deep Docks Upper Spire (Bone_East_05)

**Game ID:** Bone_East_05

**Contributors:** herounit

#### Subrooms

- left flea platform
- spire
- right exit platform

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | left flea platform | [Deep Docks Bench Shaft (Dock_01)](#deep-docks-bench-shaft-dock01) | UR | none (door switch is on this side) |  |  |  |
| R | right1 | right exit platform | [Is this still Deep Docks? (West) (Bone_East_04b)](#is-this-still-deep-docks-west-boneeast04b) | L | none |  |  | need to verify if silksoar works with magma bell |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SR | spire right | spire | right exit platform | run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart OR (silk soar AND magma bell AND blue slot) OR beast crest |  |  | i did it exactly ONCE with shaman crest and couldn't do it again :( |
| SR | spire right | right exit platform | spire | none |  |  |  |
| PG | platform gaps | spire | left flea platform | run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart OR silk soar |  |  |  |
| PG | platform gaps | left flea platform | spire | none (falling) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| flea rescue | left flea platform | none |  |  | Included |  |
| swift step | spire | none |  |  | Included |  |
| door switch | spire | none |  |  | Not included |  |
| platform switch | left flea platform | none |  |  | Not included |  |

### Deep Docks Forge (Room_Forge)

**Game ID:** Room_Forge

**Contributors:** herounit

#### Subrooms

- left area
- right area
- gauntlet
- forge daughter
- right exit platform

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | right area | [Deep Docks Chains West (Dock_02)](#deep-docks-chains-west-dock02) | UL |  |  |  |  |
| L | left1 | left area | [Deep Docks Lower West Shaft (Dock_04)](#deep-docks-lower-west-shaft-dock04) | UR |  |  |  |  |
| C | top1 | left area | [Deep Docks Lace Intro (Bone_East_12)](#deep-docks-lace-intro-boneeast12) | F |  |  |  | activate airlock |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DS | door switch | left area | right area | none (switch on this side) |  |  |  |
| DS | door switch | right area | left area | gate switch activated |  |  |  |
| GL | gauntlet left | left area | gauntlet | none |  |  |  |
| GL | gauntlet left | gauntlet | left area | gauntlet defeated |  |  |  |
| GR | gauntlet right | right area | gauntlet | none |  |  |  |
| GR | gauntlet right | gauntlet | right area | gauntlet defeated |  |  |  |
| GC | gauntlet upper | forge daughter | gauntlet | none |  |  |  |
| GC | gauntlet upper | gauntlet | forge daughter | gauntlet defeated |  |  |  |
| RJ | running jump | right area | right exit platform | run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart OR beast crest |  |  |  |
| RJ | running jump | right exit platform | right area | run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart OR beast crest | TODO | Needs verification | NEED TO VERIFY YOU CAN'T JUST JUMP BACK |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| shell shard cache deep docks 10 | left area | none |  |  | Included | break wall |
| shard bundle deep docks 2 | left area | none |  |  | Included |  |
| silkshot (forge daughter) | forge daughter | broken tool |  | Verified | Included | forge daughter shop |
| sting shard | forge daughter | none |  |  | Included | forge daughter shop |
| magma bell | forge daughter | none |  |  | Included | forge daughter shop |
| crafting kit forge daughter | forge daughter | none |  |  | Included | forge daughter shop |
| readable lore tablet | left area | activate airlock |  |  | Not included | NOT CURRENTLY RANDOMIZED |
| gate switch | forge daughter | none |  |  | Not included |  |

### Deep Docks Lower West Shaft (Dock_04)

**Game ID:** Dock_04

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Deep Docks Church (Dock_06_Church)](#deep-docks-church-dock06church) | R | none |  |  |  |
| MR | right2 |  | [Deep Docks Spool East (Bone_East_13)](#deep-docks-spool-east-boneeast13) | L | none |  |  |  |
| UR | right1 |  | [Deep Docks Forge (Room_Forge)](#deep-docks-forge-roomforge) | L | none |  |  |  |
| LR | right3 |  | [Deep Docks Sauna (Dock_10)](#deep-docks-sauna-dock10) | L | must be opened from the other side for the first time |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Deep Docks Spool East (Bone_East_13)

**Game ID:** Bone_East_13

**Contributors:** herounit

#### Subrooms

- the floor is lava
- spool fragment area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | the floor is lava | [Deep Docks Lower West Shaft (Dock_04)](#deep-docks-lower-west-shaft-dock04) | MR | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LP | lower platforms | the floor is lava | spool fragment area | platforms lowered OR faydown cloak OR (silk soar AND magma bell) | TODO |  | might have more options, hard to check after lever is flipped |
| LP | lower platforms | spool fragment area | the floor is lava | none (falling) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| spool fragment deep docks | spool fragment area | none |  |  | Included |  |
| shell shard cache deep docks 1 | the floor is lava | magma bell AND blue slot |  |  | Included |  |
| shell shard cache deep docks 2 | the floor is lava | magma bell AND blue slot |  |  | Included |  |
| shell shard cache deep docks 3 | the floor is lava | magma bell AND blue slot |  |  | Included |  |
| platform lever | the floor is lava | none |  |  | Not included |  |

### Deep Docks Church (Dock_06_Church)

**Game ID:** Dock_06_Church

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Deep Docks Lower West Shaft (Dock_04)](#deep-docks-lower-west-shaft-dock04) | L | none |  |  |  |
| F | bot1 |  | TODO |  |  | TODO |  | FROM THE ABYSS ESCAPE |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary cache deep docks 3 |  | none |  |  | Included |  |
| rosary cache deep docks 4 |  | none |  |  | Included |  |
| rosary cache deep docks 5 |  | none |  |  | Included | MARKED AS ??? ON TRACKER |
| rosary cache deep docks 6 |  | none |  |  | Included | MARKED AS ??? ON TRACKER |
| rosary chest |  | none |  |  | Not included | NOT YET RANDOMIZED |

#### Notes

might need to revise the subrooms later

### Deep Docks Chains West (Dock_02)

**Game ID:** Dock_02

**Contributors:** herounit

#### Subrooms

- main area
- middle crossing
- lower left exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | left1 | main area | [Deep Docks Forge (Room_Forge)](#deep-docks-forge-roomforge) | R |  |  |  |  |
| LL | left2 | lower left exit | [Deep Docks Forebrothers (Dock_09)](#deep-docks-forebrothers-dock09) | R |  |  |  |  |
| UR | right1 | main area | [Deep Docks Chains Center (Dock_02b)](#deep-docks-chains-center-dock02b) | UL |  |  |  |  |
| MR | right2 | middle crossing | [Deep Docks Chains Center (Dock_02b)](#deep-docks-chains-center-dock02b) | ML |  |  |  |  |
| LR | right3 | middle crossing | [Deep Docks Chains Center (Dock_02b)](#deep-docks-chains-center-dock02b) | LL |  |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BF | break floor | middle crossing | main area | cling grip AND can break floor |  |  |  |
| BF | break floor | main area | middle crossing | none (falling) |  |  |  |
| LE | lower left exit | lower left exit | middle crossing | cling grip OR ( silk soar AND magma bell AND blue slot ) |  |  |  |
| LE | lower left exit | middle crossing | lower left exit |  |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| shard bundle deep docks 1 | main area | none |  |  | Included | MARKED AS ??? ON TRACKER can fall and grab the ledge to this one |
| shell shard cache deep docks 5 | main area | none |  |  | Included | MARKED AS ??? ON TRACKER |
| flintstone journal collection point | main area | none |  |  | Not included |  |
| rosary cache deep docks 1 | main area | none |  |  | Included | MARKED AS ??? ON TRACKER |
| rosary cache deep docks 2 | main area | none |  |  | Included | MARKED AS ??? ON TRACKER |

#### Notes

need to verify how this room works - thought it had some of the platforms go away, but not sure if that was in act 3

### Deep Docks Chains Flea Rescue (Dock_03d)

**Game ID:** Dock_03d

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | bot1 |  | [Deep Docks Chains Lower East (Dock_03c)](#deep-docks-chains-lower-east-dock03c) | LC | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Deep Docks Chains Center (Dock_02b)

**Game ID:** Dock_02b

**Contributors:** herounit

#### Subrooms

- upper left hallway
- upper chain platforms
- middle left exit area
- middle switch platform
- lower right area
- lower left area
- middle side room
- lower chain platforms

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | left1 | upper left hallway | [Deep Docks Chains West (Dock_02)](#deep-docks-chains-west-dock02) | UR | none |  |  |  |
| ML | left2 | middle left exit area | [Deep Docks Chains West (Dock_02)](#deep-docks-chains-west-dock02) | MR | none |  |  |  |
| LL | left3 | lower left area | [Deep Docks Chains West (Dock_02)](#deep-docks-chains-west-dock02) | LR | none |  |  |  |
| UR | right1 | upper chain platforms | [Deep Docks Chains Upper East (Dock_03)](#deep-docks-chains-upper-east-dock03) | L | break wall (from this side) |  |  | can't enter from the other side until this is broken |
| LR | right2 | lower right area | [Deep Docks Chains Lower East (Dock_03c)](#deep-docks-chains-lower-east-dock03c) | L | break wall (from other side) |  |  |  |

#### Subroom Connections

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

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| flintslate | upper left hallway | none |  |  | Included |  |
| shell shard cache deep docks 6 | middle switch platform | none |  |  | Included | MARKED AS ??? ON TRACKER |
| shell shard cache deep docks 7 | middle switch platform | none |  |  | Included | MARKED AS ??? ON TRACKER |
| shell shard cache deep docks 8 | middle switch platform | none |  |  | Included | MARKED AS ??? ON TRACKER |
| shell shard cache deep docks 9 | middle switch platform | none |  |  | Included | MARKED AS ??? ON TRACKER |
| ceiling switch | middle switch platform | none |  |  | Not included | lowers middle chain platforms |
| door switch | upper left hallway | none |  |  | Not included |  |

#### Notes

the floor/lower half of this area is closed off initially

the switch to lower the middle chain section makes some of this logic difficult to reason about - but if you can reach the middle switch platform, there is no reason you can't reach all the stuff that unlocking the chains provides - might need to revise this for switch randomization

### Deep Docks Chains Upper East (Dock_03)

**Game ID:** Dock_03

**Contributors:** herounit

#### Subrooms

- upper left hallway
- chain platforms
- lower left chest room
- behind ring gate

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | upper left hallway | [Deep Docks Chains Center (Dock_02b)](#deep-docks-chains-center-dock02b) | UR | none |  |  |  |
| F | bot1 | behind ring gate | [Deep Docks Chains Lower East (Dock_03c)](#deep-docks-chains-lower-east-dock03c) | RC | none |  |  |  |
| R | right1 | chain platforms | [Far Fields Deep Docks Backdoor (Dock_03b)](#far-fields-deep-docks-backdoor-dock03b) | L | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DS | open door switch | upper left hallway | chain platforms | none (switch is on this side) |  |  |  |
| DS | open door switch | chain platforms | upper left hallway | door opened from the other side |  |  |  |
| BW | break wall | chain platforms | lower left chest room | break wall (from this side) |  |  |  |
| BW | break wall | lower left chest room | chain platforms | wall broken |  |  |  |
| RG | open ring gate | chain platforms | behind ring gate | clawline |  |  |  |
| RG | open ring gate | behind ring gate | chain platforms | gate opened from the other side |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| craftmetal deep docks | lower left chest room | none |  |  | Included | its freeeeee, right? :) |

#### Notes

the floor/lower half of this area is closed off initially

### Deep Docks Chains Lower East (Dock_03c)

**Game ID:** Dock_03c

**Contributors:** herounit

#### Subrooms

- upper chains
- spool fragment area
- lower chains
- middle chains
- upper lava platform
- lower lava platform
- gauntlet
- upper left of gauntlet

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| RC | top2 | upper chains | [Deep Docks Chains Upper East (Dock_03)](#deep-docks-chains-upper-east-dock03) | F |  |  |  |  |
| LC | top1 | upper left of gauntlet | [Deep Docks Chains Flea Rescue (Dock_03d)](#deep-docks-chains-flea-rescue-dock03d) | F |  |  |  |  |
| L | left2 | lower lava platform | [Deep Docks Chains Center (Dock_02b)](#deep-docks-chains-center-dock02b) | LR | none (hit blast rock on this side to open exit for both sides) |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SP | open spool door | spool fragment area | upper chains | open airlock door |  |  | one-way |
| SP | open spool door | upper chains | spool fragment area | can pogo  AND cling grip  AND ( clawline OR ( dash AND ( run OR sharpdart OR drifter's cloak ) ) ) |  | Needs verification | run or sharpdart or drifter's cloak  or clawline to get to the initial wall to cling grip. clawline or dash to get to pogo area. then free. |
| C1 | upper to middle chains | middle chains | upper chains | run OR dash OR drifter's cloak OR faydown cloak OR cling grip OR silk soar OR clawline OR sharpdart |  |  |  |
| C1 | upper to middle chains | upper chains | middle chains | none (falling) |  |  |  |
| C2 | lower to middle chains | lower chains | middle chains | silk soar OR cling grip OR faydown cloak |  |  |  |
| C2 | lower to middle chains | middle chains | lower chains | none (falling) |  |  |  |
| UC | upper clawline area | lower chains | upper lava platform | clawline |  |  |  |
| UC | upper clawline area | upper lava platform | lower chains | clawline OR drifter's cloak |  |  |  |
| LG | cross lava gap | lower chains | lower lava platform | clawline OR ( drifter's cloak AND faydown cloak ) |  | Needs verification | seems just out of reach of drifter's cloak and dash |
| LG | cross lava gap | lower lava platform | lower chains | clawline OR ( drifter's cloak AND faydown cloak ) |  |  |  |
| UL | upper lava platform to lower lava platform | upper lava platform | lower lava platform | none (falling) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| silk spool deep docks 1 | spool fragment area | none |  |  | Included |  |

### Deep Docks Forebrothers (Dock_09)

**Game ID:** Dock_09

**Contributors:** herounit

#### Subrooms

- right area
- boss area
- left area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | right area | [Deep Docks Chains West (Dock_02)](#deep-docks-chains-west-dock02) | LL | none |  |  |  |
| L | left1 | left area | [Deep Docks Lower East Shaft (Dock_15)](#deep-docks-lower-east-shaft-dock15) | UR | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RB | right boss entrance | right area | boss area | none (starts fight) |  |  |  |
| RB | right boss entrance | boss area | right area | defeat forebrothers |  |  |  |
| LB | left boss entrance | left area | boss area | none |  |  | not sure if right side is blocked off by default - needs verification |
| LB | left boss entrance | boss area | left area | defeat forebrothers |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| forebrothers boss fight | boss area | none |  |  | Included |  |
| rosary cache 1 |  |  | TODO |  | Included |  |
| rosary cache 2 |  |  | TODO |  | Included |  |

### Deep Docks Lower East Shaft (Dock_15)

**Game ID:** Dock_15

**Contributors:** herounit

#### Subrooms

- upper area
- the floor is lava
- lower left exit area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | left1 | upper area | [Deep Docks Sauna (Dock_10)](#deep-docks-sauna-dock10) | R | none |  |  |  |
| LL | left2 | upper area | [Deep Docks Memory Hole (Dock_13)](#deep-docks-memory-hole-dock13) | R | none |  |  |  |
| UR | right1 | upper area | [Deep Docks Forebrothers (Dock_09)](#deep-docks-forebrothers-dock09) | L | none |  |  |  |
| MR | right2 | upper area | [Deep Docks Silkeater Room (Dock_14)](#deep-docks-silkeater-room-dock14) | L | none |  |  |  |
| LR | right3 | the floor is lava | [Deep Docks Magma Slug Tunnels (Dock_11)](#deep-docks-magma-slug-tunnels-dock11) | L | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CG | cling grip | upper area | the floor is lava | cling grip |  |  |  |
| CG | cling grip | the floor is lava | upper area | none (falling) |  |  |  |
| BW | breakable wall | upper area | lower left exit area | break wall |  |  |  |
| BW | breakable wall | lower left exit area | upper area | break wall |  |  |  |

#### Check Locations

No check locations defined.

### Deep Docks Sauna (Dock_10)

**Game ID:** Dock_10

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Deep Docks Lower West Shaft (Dock_04)](#deep-docks-lower-west-shaft-dock04) | LR | break switch blocker to open for both sides |  |  |  |
| R | right1 |  | [Deep Docks Lower East Shaft (Dock_15)](#deep-docks-lower-east-shaft-dock15) | UL | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Deep Docks Memory Hole (Dock_13)

**Game ID:** Dock_13

**Contributors:** herounit

#### Subrooms

- entrance
- pit of despair

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | entrance | [Deep Docks Lower East Shaft (Dock_15)](#deep-docks-lower-east-shaft-dock15) | LL |  |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TP | the pit | entrance | pit of despair | none (falling) |  |  | this is possible but a massive pain, also a one-way softlock potential |
| TP | the pit | pit of despair | entrance | cling grip |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| memory locket deep docks | pit of despair | none |  |  | Included |  |

### Deep Docks Silkeater Room (Dock_14)

**Game ID:** Dock_14

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Deep Docks Lower East Shaft (Dock_15)](#deep-docks-lower-east-shaft-dock15) | MR | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| silkeater deep socks |  | none |  |  | Included |  |

### Deep Docks Magma Slug Tunnels (Dock_11)

**Game ID:** Dock_11

**Contributors:** herounit

#### Subrooms

- left exit area
- right exit area
- slug tunnels

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | left exit area | [Deep Docks Diving Bell (Dock_12)](#deep-docks-diving-bell-dock12) | L | right door switch must be flipped (from this side) |  |  |  |
| L | left1 | right exit area | [Deep Docks Lower East Shaft (Dock_15)](#deep-docks-lower-east-shaft-dock15) | LR | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LD | left doorway | left exit area | right exit area | left door switch flipped |  |  |  |
| LD | left doorway | right exit area | left exit area | none (door switch is on this side) |  |  |  |
| LT | left tunnel | left exit area | slug tunnels | none (falling) |  |  |  |
| LT | left tunnel | slug tunnels | left exit area | cling grip |  |  |  |
| RT | right tunnel | right exit area | slug tunnels | none (falling) |  |  |  |
| RT | right tunnel | slug tunnels | right exit area | cling grip |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| left door switch | left exit area | none |  |  | Not included | opens the pathway between left/right |
| right door switch | right exit area | none |  |  | Not included | unlocks the right exit |
| beast shard deep docks | slug tunnels | none |  |  | Included | annoying af areas enabled OR ( silk soar AND magma bell AND blue slot ) |

### Deep Docks Diving Bell (Dock_12)

**Game ID:** Dock_12

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| D | door1 |  | TODO |  |  | TODO | Needs verification | DIVING BELL INTO THE ABYSS |
| L | left1 |  | [Deep Docks Magma Slug Tunnels (Dock_11)](#deep-docks-magma-slug-tunnels-dock11) | R | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

## Far Fields

### Far Fields Entrance East (Bone_East_02)

**Game ID:** Bone_East_02

**Contributors:** herounit

#### Subrooms

- deep docks platform
- main pathway

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | top1 | main pathway | [Far Fields Deep Docks Loopback (Bone_East_15)](#far-fields-deep-docks-loopback-boneeast15) | F | silk soar OR faydown cloak OR ( cling grip AND ( run OR dash OR drifter's cloak OR  OR sharpdart OR clawline ) ) |  |  | car barely make it up with faydown cloak |
| R | right1 | main pathway | [Far Fields Entrance West (Bone_East_02b)](#far-fields-entrance-west-boneeast02b) | L | none |  |  |  |
| L | left1 | deep docks platform | [Deep Docks Bellshrine (Bellshrine_05)](#deep-docks-bellshrine-bellshrine05) | R | deep docks bellshrine activated |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RJ | running jump | deep docks platform | main pathway | run OR dash OR drifter's cloak OR faydown cloak OR sharpdart OR clawline |  | Needs verification | couldn't get beast crest pogo to work, but might be possible |
| RJ | running jump | main pathway | deep docks platform | none |  |  |  |

#### Check Locations

No check locations defined.

### Far Fields Entrance West (Bone_East_02b)

**Game ID:** Bone_East_02b

**Contributors:** herounit

#### Subrooms

- lower walkway
- upper right platforms
- lower right exit platform
- upper left platforms

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | right1 | upper right platforms | [Far Fields Wind Shaft (Bone_East_07)](#far-fields-wind-shaft-boneeast07) | L1 | none |  |  |  |
| LR | right2 | lower right exit platform | [Far Fields Wind Shaft (Bone_East_07)](#far-fields-wind-shaft-boneeast07) | L2 | none |  |  |  |
| L | left1 | lower walkway | [Far Fields Entrance East (Bone_East_02)](#far-fields-entrance-east-boneeast02) | R | none |  |  |  |
| C | top3 | upper right platforms | [Far Fields Fort Lower Passage (Bone_East_16)](#far-fields-fort-lower-passage-boneeast16) | F | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | vertical 1 | lower walkway | upper right platforms | run OR dash OR clawline OR sharpdart OR silk soar OR drifter's cloak OR faydown cloak |  |  |  |
| V1 | vertical 1 | upper right platforms | lower walkway | none (falling) |  |  |  |
| LC | lava crossing | lower walkway | lower right exit platform | run OR dash OR clawline OR sharpdart OR cling grip OR silk soar |  |  |  |
| LC | lava crossing | lower right exit platform | lower walkway | run OR dash OR clawline OR sharpdart OR cling grip |  |  |  |
| V2 | vertical 2 | lower walkway | upper left platforms | silk soar |  |  |  |
| V2 | vertical 2 | upper left platforms | lower walkway | none (falling) |  |  |  |
| UC | lower crossing | upper right platforms | upper left platforms | run OR dash OR clawline OR sharpdart OR silk soar OR drifter's cloak OR faydown cloak |  |  |  |
| UC | lower crossing | upper left platforms | upper right platforms | run OR dash OR clawline OR sharpdart OR silk soar OR drifter's cloak OR faydown cloak |  |  |  |
| V3 | vertical 3 | lower right exit platform | upper right platforms | cling grip OR silk soar |  |  |  |
| V3 | vertical 3 | upper right platforms | lower right exit platform | none (falling) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| shell shard cache far fields 1 | lower walkway | none |  |  | Included |  |

### Far Fields Fort Lower Passage (Bone_East_16)

**Game ID:** Bone_East_16

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | bot1 |  | [Far Fields Entrance West (Bone_East_02b)](#far-fields-entrance-west-boneeast02b) | C | none |  |  |  |
| R | right1 |  | [Far Fields Fort Flea Rescue (Bone_East_17b)](#far-fields-fort-flea-rescue-boneeast17b) | L | none |  |  | break wall (can be broken from either side) |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary cache far fields 11 |  | none |  |  | Included |  |
| rosary cache far fields 12 |  | none |  |  | Included |  |
| rosary cache far fields 13 |  | none |  |  | Included |  |

### Far Fields Fort Flea Rescue (Bone_East_17b)

**Game ID:** Bone_East_17b

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Far Fields Fort Lower Passage (Bone_East_16)](#far-fields-fort-lower-passage-boneeast16) | R | none |  |  | break wall |
| C | top1 |  | [Far Fields Fort Upper Passage (Bone_East_17)](#far-fields-fort-upper-passage-boneeast17) | B | none |  |  | break wall (can be broken from either side) |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| flea rescue |  | none |  |  | Included | break cage |
| rosary cache far fields 16 |  | none |  |  | Included |  |
| rosary cache far fields 17 |  | none |  |  | Included |  |

### Far Fields Fort Upper Passage (Bone_East_17)

**Game ID:** Bone_East_17

**Contributors:** herounit

#### Subrooms

- left exit area
- right exit area
- lower area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | left exit area | [Far Fields Deep Docks Loopback (Bone_East_15)](#far-fields-deep-docks-loopback-boneeast15) | R | platforms lowered from above |  |  |  |
| B | bot1 | lower area | [Far Fields Fort Flea Rescue (Bone_East_17b)](#far-fields-fort-flea-rescue-boneeast17b) | C | none |  |  |  |
| R | right1 | right exit area | [Far Fields Wind Shaft (Bone_East_07)](#far-fields-wind-shaft-boneeast07) | L4 | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LP | lower platforms | left exit area | lower area | none (switch is on this side) |  |  |  |
| LP | lower platforms | lower area | left exit area | platform switch flipped |  |  |  |
| RJ | running jump | lower area | right exit area | run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart |  |  |  |
| RJ | running jump | right exit area | lower area | none (falling) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary cache far fields 14 | lower area | none |  |  | Included |  |
| rosary cache far fields 15 | lower area | none |  |  | Included |  |
| lower platform switch | left exit area | none |  |  | Included |  |
| rosary chest | left exit area | none |  |  | Not included | NOT YET RANDOMIZED |

### Far Fields Wind Shaft (Bone_East_07)

**Game ID:** Bone_East_07

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | top1 |  | TODO |  |  |  |  |  |
| R1 | right1 |  | [Far Fields Pilgrim's Rest (Bone_East_10)](#far-fields-pilgrims-rest-boneeast10) | LL |  |  |  |  |
| R4 | right4 |  | [Far Fields Target Practice (Bone_East_22)](#far-fields-target-practice-boneeast22) | L |  |  |  |  |
| R2 | right2 |  | [Far Fields Bellway (Bellway_03)](#far-fields-bellway-bellway03) | L |  |  |  |  |
| R5 | right5 |  | [Far Fields Map Shop (Bone_East_21)](#far-fields-map-shop-boneeast21) | L |  |  |  |  |
| R3 | right3 |  | [Far Fields Chorus (Bone_East_08)](#far-fields-chorus-boneeast08) | L |  |  |  |  |
| L4 | left4 |  | [Far Fields Fort Upper Passage (Bone_East_17)](#far-fields-fort-upper-passage-boneeast17) | R |  |  |  |  |
| L1 | left1 |  | [Far Fields Entrance West (Bone_East_02b)](#far-fields-entrance-west-boneeast02b) | UR |  |  |  |  |
| L2 | left2 |  | [Far Fields Entrance West (Bone_East_02b)](#far-fields-entrance-west-boneeast02b) | LR |  |  |  |  |
| L3 | left3 |  | [Far Fields Deep Docks Backdoor (Dock_03b)](#far-fields-deep-docks-backdoor-dock03b) | R |  |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary cache far fields 1 |  |  |  |  | Included |  |
| weighted belt |  |  |  |  | Included |  |

### Far Fields Pilgrim's Rest (Bone_East_10)

**Game ID:** Bone_East_10

**Contributors:** herounit

#### Subrooms

- main floor
- upper left exit
- upper right exit
- lower right exit
- middle upper platform

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | left1 | upper left exit | TODO |  | none |  | Verified |  |
| LL | left2 | main floor | [Far Fields Wind Shaft (Bone_East_07)](#far-fields-wind-shaft-boneeast07) | R1 | none |  | Verified |  |
| D | door1 | main floor | TODO |  | none (rosary gated) |  | Verified |  |
| UR | right1 | upper right exit | TODO |  | must be opened from other side |  | Verified |  |
| LR | right2 | lower right exit | [Far Fields Pilgrim's Rest Church (Bone_East_10_Church)](#far-fields-pilgrims-rest-church-boneeast10church) | L | must be opened from other side |  | Verified | door switch on other side |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | vertical 1 | main floor | upper left exit | silk soar OR faydown cloak |  | Verified | platform can be dropped to make it only ledge grab after middle platform access is granted |
| V1 | vertical 1 | upper left exit | main floor | none (falling) |  |  |  |
| G1 | gap 1 | middle upper platform | upper left exit | run OR ledge grab OR clawline OR faydown cloak OR drifter's cloak OR  clawline OR sharpdart |  |  | based on after platform falls |
| V2 | vertical 2 | main floor | lower right exit | ledge grab OR faydown cloak OR silk soar OR scuttlebrace |  |  |  |

#### Check Locations

No check locations defined.

### Far Fields Pilgrim's Rest Church (Bone_East_10_Church)

**Game ID:** Bone_East_10_Church

**Contributors:** herounit

#### Subrooms

- main floor
- flea rescue area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | bot1 | main floor | [Far Fields Pinstress Attic (Bone_East_09b)](#far-fields-pinstress-attic-boneeast09b) | C | none |  | Verified |  |
| L | left1 | main floor | [Far Fields Pilgrim's Rest (Bone_East_10)](#far-fields-pilgrims-rest-boneeast10) | LR | none (door switch flipped) |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CG | climb 1 | main floor | flea rescue area | cling grip OR scuttlebrace OR silk soar |  | Verified |  |
| CG | climb 1 | flea rescue area | main floor | none (falling) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| flea pilgrims restr | flea rescue area | none |  | Verified | Included |  |
| rhinogrund miniboss fight | main floor | none |  |  | Not included | can skip by leaving and coming back |
| door switch | main floor | none |  |  | Not included |  |
| beast shard | main floor | defeat rhinogrund |  |  | Not included | this can be missed - if the switch is flipped and you leave the room (or die) without defeating the rhinogrund or collecting the beast shard, they become unavailable |

### Far Fields Pilgrim's Rest Shop (Bone_East_10_Room)

**Game ID:** Bone_East_10_Room

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Far Fields Pilgrim's Rest (Bone_East_10)](#far-fields-pilgrims-rest-boneeast10) | D | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| memory locket pilgrims rest shop |  | none |  |  | Included | shop |
| wish pilgrims rest supplies |  | unknown | TODO | Needs verification | Included | ??? |

### Far Fields Chorus (Bone_East_08)

**Game ID:** Bone_East_08

**Contributors:** herounit

#### Subrooms

- left exit area
- lower left side
- upper left alcove
- boss arena
- upper right alcove
- lower right side

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | left exit area | [Far Fields Wind Shaft (Bone_East_07)](#far-fields-wind-shaft-boneeast07) | R3 | none |  |  |  |
| R | right1 | lower right side | [Far Fields Pinstress Room (Bone_East_09)](#far-fields-pinstress-room-boneeast09) | LL | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | vertical 1 | lower left side | left exit area | silk soar OR drifter's cloak |  | Verified |  |
| V1 | vertical 1 | left exit area | lower left side | none (falling) |  | Verified |  |
| G1 | gap 1 | left exit area | upper left alcove | drifter's cloak OR clawline |  | Verified | one way only |
| V2 | vertical 2 | lower left side | upper left alcove | silk soar OR drifter's cloak |  | Verified |  |
| V2 | vertical 2 | upper left alcove | lower left side | none (falling) |  | Verified |  |
| BL | boss left entrance | lower left side | boss arena | none | TODO |  | unsure what starts the boss fight but whatever |
| BL | boss left entrance | boss arena | lower left side | pre-boss fight trigger OR defeat boss | TODO |  |  |
| BR | boss right entrance | lower right side | boss arena | none | TODO |  | unsure what starts the boss fight but whatever |
| BR | boss right entrance | boss arena | lower right side | pre-boss fight trigger OR defeat boss | TODO |  |  |
| V3 | vertical 3 | lower right side | upper right alcove | drifter's cloak OR ( silk soar AND ( cling grip AND ( faydown cloak OR dash OR clawline OR sharpdart ) OR  scuttlebrace ) ) |  | Verified |  |
| V3 | vertical 3 | upper right alcove | lower right side | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| boss fourth chorus | boss arena | ??? | TODO |  | Included | what triggers this fight? |
| rosary cache far fields 2 | upper left alcove | none |  | Verified | Included |  |
| free silk | upper right alcove | none |  | Verified | Included | NOT CURRENTLY RANDOMIZED |

### Far Fields Pinstress Attic (Bone_East_09b)

**Game ID:** Bone_East_09b

**Contributors:** herounit

#### Subrooms

- bottom left area
- upper right area
- ceiling exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | bottom left area | [Far Fields Bellway (Bellway_03)](#far-fields-bellway-bellway03) | R | none |  | Verified |  |
| F | bot1 | bottom left area | [Far Fields Pinstress Room (Bone_East_09)](#far-fields-pinstress-room-boneeast09) | T | none (break blast rock) |  | Verified |  |
| C | top1 | ceiling exit | [Far Fields Pilgrim's Rest Church (Bone_East_10_Church)](#far-fields-pilgrims-rest-church-boneeast10church) | F | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| D1 | drift passage 1 | bottom left area | upper right area | drifter's cloak OR ( silk soar AND can pogo AND faydown cloak AND clawline ) |  | Verified |  |
| D1 | drift passage 1 | upper right area | bottom left area | drifter's cloak OR clawline |  | Verified |  |
| D2 | drift passage 2 | upper right area | ceiling exit | drifter's cloak AND ( dash OR clawline OR sharpdart ) AND cling grip |  | Needs verification | one way - might need some further validation |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary cache far field 3 | upper right area | none |  | Verified | Included |  |
| rosary cache far field 4 | upper right area | none |  | Verified | Included |  |

### Far Fields Pinstress Room (Bone_East_09)

**Game ID:** Bone_East_09

**Contributors:** herounit

#### Subrooms

- lower left platform
- upper left platform

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | top1 |  | [Far Fields Pinstress Attic (Bone_East_09b)](#far-fields-pinstress-attic-boneeast09b) | F | blocked from other side by blast rock |  |  |  |
| UL | left3 | upper left platform | [Far Fields Pinstress Mask Shard (Bone_East_20)](#far-fields-pinstress-mask-shard-boneeast20) | R |  |  |  |  |
| LR | right2 |  | TODO |  |  |  |  |  |
| LL | left2 |  | [Far Fields Chorus (Bone_East_08)](#far-fields-chorus-boneeast08) | R |  |  |  |  |
| UR | right1 |  | TODO |  |  |  |  |  |
| D | door1 |  | TODO |  |  |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | vertical 1 | lower left platform | upper left platform | silk soar |  |  |  |
| V1 | vertical 1 | upper left platform | lower left platform | none (falling) |  |  |  |

#### Check Locations

No check locations defined.

### Far Fields Pinstress Mask Shard (Bone_East_20)

**Game ID:** Bone_East_20

**Contributors:** herounit

#### Subrooms

- right side
- left side

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | right side | [Far Fields Pinstress Room (Bone_East_09)](#far-fields-pinstress-room-boneeast09) | UL | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TC | thorn crossing | right side | left side | claw line OR ( drifter's cloak AND ( ledge grab OR silk soar ) ) OR |  | Verified |  |
| TC | thorn crossing | left side | right side | drifter's cloak OR ( clawline AND ( silk soar OR faydown cloak OR run ) ) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| mask shard far fields above the seamstress | left side | drifter's cloak OR silk soar OR faydown cloak | TODO | Needs verification | Included | must break blast rock on ceiling - this likely has a large number of tool options - haven't really considered this here |
| random silk | left side | none |  | Verified | Not included | NOT YET RANDOMIZED |

### Far Fields Target Practice (Bone_East_22)

**Game ID:** Bone_East_22

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Far Fields Wind Shaft (Bone_East_07)](#far-fields-wind-shaft-boneeast07) | R4 | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| progressive curveclaw |  | act 3 AND curveclaw AND red slot |  |  | Not included | NOT CURRENTLY ON TRACKER - MAY NOT BE RANDOMIZED |

#### Notes

this is the room where you get progressive curveclaw (curvesickle) in act 3

### Far Fields Map Shop (Bone_East_21)

**Game ID:** Bone_East_21

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Far Fields Wind Shaft (Bone_East_07)](#far-fields-wind-shaft-boneeast07) | R5 | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| map purchase far fields |  | none |  | Verified | Included | shakra shop |

### Far Fields Bellway (Bellway_03)

**Game ID:** Bellway_03

**Contributors:** herounit

#### Subrooms

- bellway
- hidden area
- right exit area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | bellway | [Far Fields Pinstress Attic (Bone_East_09b)](#far-fields-pinstress-attic-boneeast09b) | L |  |  |  |  |
| L | left1 | bellway | [Far Fields Wind Shaft (Bone_East_07)](#far-fields-wind-shaft-boneeast07) | R2 |  |  |  |  |
| BB | door_fastTravelExit | bellway | [Bellway Menu](#bellway-menu) | FF | bellway pay gate unlocked |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| HP | hidden pathway | bellway | hidden area | bellway pay gate unlocked |  |  |  |
| HP | hidden pathway | hidden area | bellway | bellway pay gate unlocked |  |  |  |
| TP | thorn path | hidden area | right exit area | ( silk soar AND (  ledge grab OR cling grip OR scuttlebrace ) ) OR ( faydown cloak AND cling grip ) OR ( drifter's cloak AND ( cling grip OR scuttlebrace ) ) |  |  |  |
| TP | thorn path | right exit area | hidden area | silk soar OR drifter's cloak |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| bench |  | bench pay gate unlocked |  |  | Not included |  |
| bench pay gate |  | none |  |  | Not included |  |
| bellway pay gate |  | none |  |  | Included |  |

### Far Fields Deep Docks Loopback (Bone_East_15)

**Game ID:** Bone_East_15

**Contributors:** herounit

#### Subrooms

- spike exit
- ground
- bell bench
- before gate

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | bell bench | [Is this still Deep Docks? (East) (Bone_East_04)](#is-this-still-deep-docks-east-boneeast04) | LR | none |  |  |  |
| F | bot1 | ground | [Far Fields Entrance East (Bone_East_02)](#far-fields-entrance-east-boneeast02) | C | none |  |  |  |
| R | right1 | spike exit | [Far Fields Fort Upper Passage (Bone_East_17)](#far-fields-fort-upper-passage-boneeast17) | L | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SF | spike float | ground | spike exit | ( cling grip AND drifter's cloak ) OR ( silk soar AND drifter's cloak ) |  |  |  |
| SF | spike float | spike exit | ground | none (falling) | TODO |  | can barely ledge grab by falling to jump down |
| BG | bell bench gate | before gate | bell bench | none (switch is on this side) |  |  |  |
| BG | bell bench gate | bell bench | before gate | gate switch flipped |  |  |  |
| CG | cling grip | ground | before gate | cling grip OR silk soar |  |  |  |
| CG | cling grip | before gate | ground | none (falling) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary cache far fields 9 | ground | none |  |  | Included | MARKED AS ??? ON TRACKER |
| rosary cache far fields 10 | ground | none |  |  | Included | MARKED AS ??? ON TRACKER |
| gate switch | before gate | none |  |  | Not included |  |
| bench pay lock | bell bench | none |  |  | Not included |  |
| bench :) | bell bench | unlock bench lock |  |  | Not included |  |

### Far Fields Deep Docks Backdoor (Dock_03b)

**Game ID:** Dock_03b

**Contributors:** herounit

#### Subrooms

- upper area
- lower area
- platform

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | upper area | [Deep Docks Chains Upper East (Dock_03)](#deep-docks-chains-upper-east-dock03) | R | must be opened from the other side |  |  |  |
| R | right1 | lower area | [Far Fields Wind Shaft (Bone_East_07)](#far-fields-wind-shaft-boneeast07) | L3 | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LG | ledge grabs | lower area | upper area | ledge grab OR silk soar OR faydown cloak OR clawline OR shaman crest |  | Verified |  |
| LG | ledge grabs | upper area | lower area | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| warding bell | upper area | none |  |  | Included |  |

### Weavenest Cindril Entrance (Bone_East_Weavehome)

**Game ID:** Bone_East_Weavehome

**Contributors:** herounit

#### Subrooms

- entrance
- secret room

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | entrance | TODO |  | needolin |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RN | run | entrance | secret room | run AND silkspeed anklets AND yellow slot AND flea brew AND red slot AND can refill flea brew | TODO |  | need to check if there are platforming requirements |
| RN | run | secret room | entrance | none |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| silkspeed anklets |  |  |  |  | Included |  |
| relic rune harp weavenest cindril |  |  |  |  | Included |  |

## Hunter's March

### Chapel of the Beast (Ant_19)

**Game ID:** Ant_19

**Contributors:** herounit

#### Subrooms

- chapel entrance
- boss arena
- crest area
- right of boss fight

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | chapel entrance | [Hunter's March Chapel Passage (Ant_20)](#hunters-march-chapel-passage-ant20) | D | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DS | door switch | chapel entrance | right of boss fight | drifter's cloak |  |  |  |
| DS | door switch | right of boss fight | chapel entrance | door switch flipped (other side) |  |  |  |
| BR | boss right entrance | right of boss fight | boss arena | none |  |  |  |
| BR | boss right entrance | boss arena | right of boss fight | boss defeated |  |  |  |
| BL | boss left entrance | crest area | boss arena | boss defeated |  |  |  |
| BL | boss left entrance | boss arena | crest area | boss defeated |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| crest beast | crest area | none |  |  | Included |  |
| savage beastly fight | boss arena | none |  |  | Not included |  |
| door switch | right of boss fight | none |  |  | Not included |  |

### Hunter's March Chapel Passage (Ant_20)

**Game ID:** Ant_20

**Contributors:** herounit

#### Subrooms

- left entrance
- crossing platform
- memory locket platform
- chapel entrance

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | left entrance | [Hunter's March Shaft (Ant_14)](#hunters-march-shaft-ant14) | LR | none |  |  |  |
| D | door1 | chapel entrance | [Chapel of the Beast (Ant_19)](#chapel-of-the-beast-ant19) | L | no beast crest OR beast chapel door override |  |  | door override is meant to cover when the randomizer ensures the door stays open |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LC | lower crossing | left entrance | crossing platform | can pogo OR run OR dash OR clawline OR drifter's cloak OR faydown cloak OR ( sharpdart AND silk heart ) |  |  |  |
| LC | lower crossing | crossing platform | left entrance | can pogo OR run OR dash OR clawline OR drifter's cloak OR faydown cloak OR ( sharpdart AND silk heart ) |  |  |  |
| MP | memory locket platform | crossing platform | memory locket platform | can pogo OR drifter's cloak OR clawline OR sharpdart OR ( run AND dash ) OR ( run AND faydown cloak ) OR ( faydown cloak AND dash ) |  |  |  |
| MP | memory locket platform | memory locket platform | crossing platform | can pogo OR drifter's cloak OR clawline OR sharpdart OR ( run AND dash ) OR ( run AND faydown cloak ) OR ( faydown cloak AND dash ) |  |  |  |
| WT | wind tunnel | crossing platform | chapel entrance | drifter's cloak OR silk soar |  |  |  |
| WT | wind tunnel | chapel entrance | crossing platform | none (falling) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| memory locket | memory locket platform | none |  |  | Included | need to break a cage |

### Hunter's March Entrance (Ant_02)

**Game ID:** Ant_02

**Contributors:** herounit

#### Subrooms

- before door
- after door
- right exit area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | before door | [The Marrow Jail Pathway (Bone_08)](#the-marrow-jail-pathway-bone08) | MR | none |  |  |  |
| R | right1 | right exit area | [Hunter's March Pogo Intro (Ant_03)](#hunters-march-pogo-intro-ant03) | L | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| FG | fight grunt | before door | after door | none (defeat grunt) |  |  |  |
| FG | fight grunt | after door | before door | grunt defeated (other side) |  |  |  |
| EP | easy pogo | after door | right exit area | can pogo |  |  |  |
| EP | easy pogo | right exit area | after door | can pogo |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| shell shard cache hunter's march 1 | after door | none |  |  | Included | MARKED AS ??? ON TRACKER |
| shell shard cache hunter's march 2 | after door | none |  |  | Included | MARKED AS ??? ON TRACKER |

### Hunter's March Pogo Intro (Ant_03)

**Game ID:** Ant_03

**Contributors:** herounit

#### Subrooms

- flea rescue area
- middle exit area
- ground level

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left2 | ground level | [Hunter's March Entrance (Ant_02)](#hunters-march-entrance-ant02) | R | none |  |  |  |
| R | right3 | middle exit area | [Hunter's March Early Pathway West (Ant_04_left)](#hunters-march-early-pathway-west-ant04left) | L | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LP | lower pogo | ground level | middle exit area | can pogo |  |  |  |
| LP | lower pogo | middle exit area | ground level | none (falling) |  |  |  |
| UP | upper pogo | middle exit area | flea rescue area | can pogo |  |  |  |
| UP | upper pogo | flea rescue area | middle exit area | can pogo |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| flea rescue | flea rescue area | can break cage |  |  | Included |  |

### Hunter's March Early Pathway West (Ant_04_left)

**Game ID:** Ant_04_left

**Contributors:** herounit

#### Subrooms

- left exit area
- upper left platforms
- upper middle side room
- lower center platforms
- right exit area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | left exit area | [Hunter's March Pogo Intro (Ant_03)](#hunters-march-pogo-intro-ant03) | R | none |  |  |  |
| R | right1 | right exit area | [Hunter's March Map Shop (Ant_04_mid)](#hunters-march-map-shop-ant04mid) | L | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| P1 | pogo 1 | left exit area | upper left platforms | can pogo OR faydown cloak OR silk soar |  |  |  |
| P1 | pogo 1 | upper left platforms | left exit area | none (falling) |  |  |  |
| P2 | pogo 2 | upper left platforms | upper middle side room | can pogo OR ( faydown cloak  AND dash ) OR clawline OR sharpdart OR (run AND ( dash OR drifter's cloak ) ) |  |  |  |
| P2 | pogo 2 | upper middle side room | upper left platforms | can pogo OR ( faydown cloak  AND dash ) OR clawline OR sharpdart OR (run AND ( dash OR drifter's cloak ) ) |  |  |  |
| LC | lower crossing | left exit area | right exit area | can pogo OR run OR dash OR drifter's cloak OR faydown cloak OR clawline |  |  | sharpdart not included due to silk requirement |
| LC | lower crossing | right exit area | left exit area | can pogo OR run OR dash OR drifter's cloak OR faydown cloak OR clawline |  |  | sharpdart not included due to silk requirement |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary cache hunters march 1 | upper left platforms | none |  |  | Included | get there fast - the ants will eat them |
| rosary cache hunters march 2 | upper left platforms | none |  |  | Included | get there fast - the ants will eat them |
| rosary cache hunters march 3 | upper middle side room | none |  |  | Included |  |
| rosary necklace hunters march | upper middle side room | none |  |  | Included | ants eat them before you can collect |

### Hunter's March Map Shop (Ant_04_mid)

**Game ID:** Ant_04_mid

**Contributors:** herounit

#### Subrooms

- left exit area
- left of gauntlet
- gauntlet
- right of gauntlet

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | left exit area | [Hunter's March Early Pathway West (Ant_04_left)](#hunters-march-early-pathway-west-ant04left) | R | none |  |  |  |
| R | right1 | right of gauntlet | [Hunter's March Early Pathway East (Ant_04)](#hunters-march-early-pathway-east-ant04) | L | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| P1 | pogo 1 | left exit area | left of gauntlet | can pogo OR ( run AND dash AND faydown cloak ) OR ( run AND clawline ) OR ( faydown cloak AND clawline ) OR ( run AND drifter's cloak AND cling grip ) OR ( clawline AND sharpdart ) |  |  |  |
| P1 | pogo 1 | left of gauntlet | left exit area | can pogo OR ( run AND dash AND faydown cloak ) OR ( run AND clawline ) OR ( faydown cloak AND clawline ) OR ( run AND drifter's cloak AND cling grip ) OR ( clawline AND sharpdart ) |  |  |  |
| LG | left gauntlet entrance | left of gauntlet | gauntlet | none (starts gauntlet) |  |  |  |
| LG | left gauntlet entrance | gauntlet | left of gauntlet | defeat gauntlet |  |  |  |
| RG | right of gauntlet entrance | right of gauntlet | gauntlet | none (starts gauntlet) |  |  |  |
| RG | right of gauntlet entrance | gauntlet | right of gauntlet | defeat gauntlet |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| gauntlet fight | gauntlet | none |  |  | Not included |  |
| map purchase hunter's march | gauntlet | defeat gauntlet |  |  | Included |  |

### Hunter's March Early Pathway East (Ant_04)

**Game ID:** Ant_04

**Contributors:** herounit

#### Subrooms

- right exit platform
- right trap run
- upper right room
- left exit platform
- left upper platform
- left lower platform
- middle upper platform
- middle lower platform

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | right exit platform | [Hunter's March Shaft (Ant_14)](#hunters-march-shaft-ant14) | L3 |  |  |  |  |
| L | left1 | left exit platform | [Hunter's March Map Shop (Ant_04_mid)](#hunters-march-map-shop-ant04mid) | R |  |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| G1 | gap 1 | right exit platform | right trap run | can pogo OR run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart |  |  |  |
| G1 | gap 1 | right trap run | right exit platform | can pogo OR run OR dash OR faydown cloak OR clawline OR sharpdart |  |  | can't drifter's cloak this way |
| P1 | pogo 1 | right trap run | upper right room | can pogo OR silk soar |  |  |  |
| P1 | pogo 1 | upper right room | right trap run | none (falling) |  |  |  |
| G2 | gap 2 | right trap run | middle lower platform | can pogo OR run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart |  |  |  |
| G2 | gap 2 | middle lower platform | right trap run | can pogo OR run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart |  |  |  |
| V1 | vertical 1 | middle lower platform | middle upper platform | faydown cloak OR silk soar |  |  |  |
| V1 | vertical 1 | middle upper platform | middle lower platform | none (falling) |  |  |  |
| G3 | gap 3 | middle lower platform | left lower platform | can pogo OR clawline OR ( run AND dash AND faydown cloak ) |  |  |  |
| G3 | gap 3 | left lower platform | middle lower platform | can pogo OR clawline OR ( drifter's cloak AND faydown cloak ) |  |  |  |
| G4 | gap 4 | left lower platform | middle upper platform | run OR dash OR faydown cloak OR ( silk soar AND drifter's cloak ) |  |  |  |
| G4 | gap 4 | middle upper platform | left lower platform | none (falling) |  |  |  |
| G5 | gap 5 | middle upper platform | left upper platform | clawline OR sharpdart OR run AND ( dash OR drifter's cloak OR faydown cloak ) OR ( drifter's cloak AND ( faydown cloak OR silk soar ) ) |  |  |  |
| G5 | gap 5 | left upper platform | middle upper platform | run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart |  |  |  |
| V2 | vertical 2 | left lower platform | left upper platform | faydown cloak OR silk soar |  |  |  |
| V2 | vertical 2 | left upper platform | left lower platform | none (falling) |  |  |  |
| G6 | gap 6 | left lower platform | left exit platform | can pogo OR clawline OR drifter's cloak OR ( run AND dash ) OR ( run AND faydown cloak ) OR ( faydown cloak AND dash ) |  |  |  |
| G6 | gap 6 | left exit platform | left lower platform | can pogo OR clawline OR drifter's cloak OR ( run AND dash ) OR ( run AND faydown cloak ) OR ( faydown cloak AND dash ) |  |  |  |
| V3 | vertical 3 | left exit platform | left upper platform | cam pogo OR faydown cloak OR ( silk soar AND drifter's cloak ) |  |  |  |
| V3 | vertical 3 | left upper platform | left exit platform | none (falling) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| shell shard cache hunters march 3 | upper right room | none |  |  | Included |  |
| shell shard cache hunters march 4 | upper right room | none |  |  | Included |  |
| silk webs x3 | upper right room | none |  |  | Not included | not yet randomized |

### Hunter's March Shaft (Ant_14)

**Game ID:** Ant_14

**Contributors:** herounit

#### Subrooms

- L4 exit platform
- LR exit platform
- L3 exit platform
- middle exit platforms
- L1 exit platform
- L5 exit platform

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L5 | left5 | L5 exit platform | [Hunter's March Treasure Vault (Ant_21)](#hunters-march-treasure-vault-ant21) | R | none |  |  |  |
| L1 | left1 | L1 exit platform | [Hunter's March Skarr Shop (Ant_Merchant)](#hunters-march-skarr-shop-antmerchant) | R | none |  |  |  |
| L2 | left2 | middle exit platforms | [Hunter's March Trapped Bench (Ant_17)](#hunters-march-trapped-bench-ant17) | R | none |  |  |  |
| L3 | left3 | L3 exit platform | [Hunter's March Early Pathway East (Ant_04)](#hunters-march-early-pathway-east-ant04) | R | none |  |  |  |
| L4 | left4 | L4 exit platform | [Hunter's March Deep Docks Passage (Ant_05b)](#hunters-march-deep-docks-passage-ant05b) | R | none |  |  |  |
| UR | right2 | middle exit platforms | [Hunter's March Statue (Ant_05c)](#hunters-march-statue-ant05c) | L | none |  |  |  |
| LR | right3 | LR exit platform | [Hunter's March Chapel Passage (Ant_20)](#hunters-march-chapel-passage-ant20) | L | none |  |  |  |

#### Subroom Connections

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

#### Check Locations

No check locations defined.

### Hunter's March Trapped Bench (Ant_17)

**Game ID:** Ant_17

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Hunter's March Shaft (Ant_14)](#hunters-march-shaft-ant14) | L2 | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| trapped bench |  | bench trap switch flipped |  |  | Not included |  |
| bench trap switch |  | none |  |  | Not included |  |

### Hunter's March Skarr Shop (Ant_Merchant)

**Game ID:** Ant_Merchant

**Contributors:** herounit

#### Subrooms

- storage room
- skarr shop

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | storage room | [Hunter's March Shaft (Ant_14)](#hunters-march-shaft-ant14) | L1 | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CG | cross gap | storage room | skarr shop | run OR dash OR faydown cloak OR clawline OR ( sharpdart AND silk heart ) |  |  | too many jumps for sharpdart without upgrades or silk heart; could add progressive spool fragments as a requirement for multiple sharpdart jumps |
| CG | cross gap | skarr shop | storage room | run OR dash OR faydown cloak OR clawline OR ( sharpdart AND silk heart ) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| fractured mask | skarr shop | none |  |  | Included |  |
| curveclaw | skarr shop | none | TODO |  | Included | I think this item mistakenly displays in the treasure vault instead of the skarr shop |
| shell shard cache hunter's march 5 | storage room | none |  |  | Included |  |
| shell shard cache hunter's march 6 | storage room | none |  |  | Included |  |
| shell shard cache hunter's march 7 | storage room | none |  |  | Included |  |
| shell shard cache hunter's march 8 | storage room | none |  |  | Included |  |

### Hunter's March Treasure Vault (Ant_21)

**Game ID:** Ant_21

**Contributors:** herounit

#### Subrooms

- right of door
- left of door

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | right of door | [Hunter's March Shaft (Ant_14)](#hunters-march-shaft-ant14) | L5 | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| GF | grunt fight | left of door | right of door | none (defeat grunts) |  |  |  |
| GF | grunt fight | right of door | left of door | grunts defeated |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary cache hunters march 4 | left of door | none |  |  | Included |  |
| rosary cache hunters march 5 | left of door | none |  |  | Included |  |
| rosary cache hunters march 6 | left of door | none |  |  | Included |  |
| rosary cache hunters march 7 | left of door | none |  |  | Included |  |
| rosary cache hunters march 8 | left of door | none |  |  | Included |  |
| rosary cache hunters march 9 | left of door | none |  |  | Included |  |
| rosary cache hunters march 10 | left of door | none |  |  | Included |  |

### Hunter's March Statue (Ant_05c)

**Game ID:** Ant_05c

**Contributors:** herounit

#### Subrooms

- statue area
- right exit area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | statue area | [Hunter's March Shaft (Ant_14)](#hunters-march-shaft-ant14) | UR | none |  |  |  |
| R | right1 | right exit area | TODO |  | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SS | silk soar spot | statue area | right exit area | silk soar |  |  |  |
| SS | silk soar spot | right exit area | statue area | none (falling) |  |  |  |

#### Check Locations

No check locations defined.

### Hunter's March Deep Docks Passage (Ant_05b)

**Game ID:** Ant_05b

**Contributors:** herounit

#### Subrooms

- before gate
- right of gauntlet
- gauntlet
- left of gauntlet

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | before gate | [Hunter's March Shaft (Ant_14)](#hunters-march-shaft-ant14) | L4 | none |  | Needs verification |  |
| LF | bot1 | left of gauntlet | [Is this still Deep Docks? (West) (Bone_East_04b)](#is-this-still-deep-docks-west-boneeast04b) | C | none |  | Needs verification |  |
| RF | bot2 | right of gauntlet | [Is this still Deep Docks? (East) (Bone_East_04)](#is-this-still-deep-docks-east-boneeast04) | C | none |  | Needs verification |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BG | bone gate | before gate | right of gauntlet | none (switch is on this side) |  | Needs verification |  |
| BG | bone gate | right of gauntlet | before gate | switched flipped |  | Needs verification |  |
| RG | right gauntlet | right of gauntlet | gauntlet | none (starts gauntlet) |  | Needs verification |  |
| RG | right gauntlet | gauntlet | right of gauntlet | defeat gauntlet |  | Needs verification |  |
| LG | left gauntlet | left of gauntlet | gauntlet | none (starts gauntlet) |  | Needs verification |  |
| LG | left gauntlet | gauntlet | left of gauntlet | defeat gauntlet |  | Needs verification |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| bone switch | before gate | none |  | Needs verification | Not included |  |
| gauntlet fight | gauntlet | none |  | Needs verification | Not included |  |

### Hunter's March Deep Entrance (Ant_09)

**Game ID:** Ant_09

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Hunter's March Statue (Ant_05c)](#hunters-march-statue-ant05c) | R |  |  |  |  |
| R | right1 |  | TODO |  |  |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

## Shellwood

## Bellhart

## Greymoor

## Verdania

## Blasted Steps

## Grand Gate

### Grand Gate Maintenance Room (Song_01c)

**Game ID:** Song_01c

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Grand Gate Courtroom (Song_19_entrance)](#grand-gate-courtroom-song19entrance) | TR | none |  |  | falling is enough |
| T | top1 |  | [Choral Chambers Below Ventrica (Song_01)](#choral-chambers-below-ventrica-song01) | B | cling grip |  |  | no silk soar |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Grand Gate Courtroom (Song_19_entrance)

**Game ID:** Song_19_entrance

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | TODO |  | beating last judge |  |  | blocked |
| TR | right1 |  | [Grand Gate Maintenance Room (Song_01c)](#grand-gate-maintenance-room-song01c) | L | faydown cloak or silk soar |  |  |  |
| R | right2 |  | [Grand Elevator (Under_01)](#grand-elevator-under01) | TL | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Spool Fragment: Grand Gate |  | (faydown cloak and cling grip) or silk soar |  |  | Included |  |
| Map Purchase: Grand Gate |  | rosaries |  |  | Included |  |

### Grand Elevator (Under_01)

**Game ID:** Under_01

**Contributors:** samupo

#### Subrooms

- Top
- Crash Site

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TL | left1 | Top | [Grand Gate Courtroom (Song_19_entrance)](#grand-gate-courtroom-song19entrance) | R | none |  |  |  |
| SLB | left3 | Crash Site | TODO |  | opens from the other side (breakable wall) | TODO |  |  |
| SLT | left2 | Crash Site | TODO |  | silk soar and cling grip | TODO |  | Either come back from Top for a second time or get access from the crash site. To check if the breakable wall exists both sides |
| R | right1 | Crash Site | [Broken Elevator (Under_01b)](#broken-elevator-under01b) | L | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| F | Falling | Top | Crash Site | none |  |  | Just once |

#### Check Locations

No check locations defined.

## Underworks

### Broken Elevator (Under_01b)

**Game ID:** Under_01b

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Grand Elevator (Under_01)](#grand-elevator-under01) | R | none |  |  |  |
| R | right1 |  | [Underworks Shaft (Under_02)](#underworks-shaft-under02) | L1 | none |  |  | one way, opens from this side |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Confession Toll (Under_08)

**Game ID:** Under_08

**Contributors:** samupo

#### Subrooms

- Base
- Top
- Memory
- Secret

- **Secret:** Whiteward entrance?

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | top1 | Secret | TODO |  | none | TODO |  | has to be checked from white ward |
| B | bot1 | Base | TODO |  | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V | Base to Top | Base | Top | cling grip and (faydown cloak or dash or sharpdart or drifter's cloak or ledge grab) or silk soar |  |  |  |
| V2 | Top To Memory | Top | Memory | faydown cloak or ledge grab or silk soar | TODO |  | check cling grip as well when there's no ledge grab |
| F | Top to Base | Top | Base | none |  |  | falling |
| S | Secret to Top | Secret | Top | none | TODO |  | falling |
| S2 | Secret to Memory | Secret | Memory | none | TODO |  | falling |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Memory Locket: Underworks | Memory | none |  |  | Included |  |
| Shell Shard Cache: Underworks #15 | Top | none |  |  | Included |  |
| Relic: Psalm Cylinder (Underworks) | Secret | TBD | TODO |  | Included |  |

### Underworks Below Confession (Under_06)

**Game ID:** Under_06

**Contributors:** samupo

#### Subrooms

- Center
- Left
- Right

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | TODO |  | none |  |  |  |
| T | top1 |  | [Confession Toll (Under_08)](#confession-toll-under08) | B | cling grip or silk soar |  |  |  |
| R | right1 |  | TODO |  | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LC | Left-Center | Left | Center | spike pogo or dash or clawline | TODO |  | Very hard for me to verify |
| LC | Left-Center | Center | Left | spike pogo or dash or clawline | TODO |  | Very hard for me to verify |
| RC | Right-Center | Right | Center | spike pogo or dash or clawline | TODO |  | Very hard for me to verify |
| RC | Right-Center | Center | Right | spike pogo or dash or clawline | TODO |  | Very hard for me to verify |

#### Check Locations

No check locations defined.

### Underworks Map Room (Under_16)

**Game ID:** Under_16

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Underworks Shaft (Under_02)](#underworks-shaft-under02) | L2 | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Map Pickup: Underworks |  | none |  | Verified | Included |  |
| Relic: Bone Scroll (Underworks) |  | none |  | Verified | Included |  |

### Underworks Outside Choral Chambers (Under_07c)

**Game ID:** Under_07c

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| NF | bot1 |  | [Underworks Western Gauntlet (Under_07)](#underworks-western-gauntlet-under07) | NF | NOT IMPLEMENTED | TODO |  | Haven't found any connection to bottom in Act 2. Maybe Act 3? Maybe a miss from the devs? |
| L | left2 |  | [Underworks Shaft (Under_02)](#underworks-shaft-under02) | R4 | none |  |  |  |
| T | top1 |  | [Choral Chambers Outisde Underworks (Under_07b)](#choral-chambers-outisde-underworks-under07b) | B | cling grip or silk soar |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Rosary Cache: Underworks #2 |  | cling grip |  | Verified | Included |  |
| Rosary Cache: Underworks #3 |  | cling grip |  | Verified | Included |  |
| Shell Shard Cache: Underworks #14 |  | cling grip and (dash or clawline or sharpdart) |  | Verified | Included |  |
| Frayed Rosary String: Underworks #1 |  | cling grip |  | Verified | Included |  |

### Underworks Shaft (Under_02)

**Game ID:** Under_02

**Contributors:** samupo

#### Subrooms

- Underground
- Bottom
- Lever
- Mid
- Top
- Overtop

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R4 | right1 | Overtop | [Underworks Outside Choral Chambers (Under_07c)](#underworks-outside-choral-chambers-under07c) | L | none |  |  |  |
| R3 | right2 | Top | [Underworks Western Gauntlet (Under_07)](#underworks-western-gauntlet-under07) | L | none |  |  |  |
| R2 | right3 | Mid | [Underworks Saw Intro (Under_03b)](#underworks-saw-intro-under03b) | L | none |  |  |  |
| L2 | left3 | Mid | [Underworks Map Room (Under_16)](#underworks-map-room-under16) | R | none |  |  |  |
| L1 | left1 | Bottom | [Broken Elevator (Under_01b)](#broken-elevator-under01b) | R | must be opened from the other side |  |  |  |
| R1 | right4 | Underground | [Underworks Delver's Drill (Under_14)](#underworks-delvers-drill-under14) | L | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BL | Reaching Bottom Lever | Bottom | Lever | silk soar or (cling grip and (ledge grab or faydown cloak or clawline)) |  |  |  |
| LM | Lever to Mid | Lever | Mid | cling grip or silk soar |  |  |  |
| TOT | Top to Overtop | Top | Overtop | cling grip or faydown cloak or silk soar |  |  |  |
| UG | Coming form Underground | Underground | Bottom | been able to reach top and  (faydown cloak and cling grip) or (silk soar and ((dash and ledge grab) or cling grip or clawline) | TODO |  | Hard to verify because of the difficult geometry |
| UGL | Underground Level | Top | Underground | none |  |  | Hitting the lever will let you go all the way down to the underground |
| FOT | Falling from Overtop | Overtop | Top | none |  |  | falling |
| FT | Falling from Top | Top | Mid | none |  |  | falling |
| FT2 | Falling from Top 2 | Top | Lever | none |  |  | falling. It's not done from Mid, since there would be a wall if you haven't cleared it. |
| FL | Falling from Lever | Lever | Bottom | none |  |  | falling |

#### Check Locations

No check locations defined.

### Underworks Western Gauntlet (Under_07)

**Game ID:** Under_07

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right2 |  | [Underworks Below Confession (Under_06)](#underworks-below-confession-under06) | L | gauntlet |  |  |  |
| NF | top1 |  | [Underworks Outside Choral Chambers (Under_07c)](#underworks-outside-choral-chambers-under07c) | NF | NOT IMPLEMENTED | TODO |  | Not found? Act 3 only? Mistake by the devs? |
| L | left3 |  | [Underworks Shaft (Under_02)](#underworks-shaft-under02) | R3 | gauntlet |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Rosary Cache: Underworks #1 |  | cling grip or silk soar or (faydown cloak and ledge grab) |  |  | Included |  |

### Underworks Central Shaft (Under_05)

**Game ID:** Under_05

**Contributors:** samupo

#### Subrooms

- Wisp Thicket
- Bottom
- Mid
- Top

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TL | left1 | Top | [Underworks Below Confession (Under_06)](#underworks-below-confession-under06) | R | none |  |  |  |
| R | right2 | Mid | TODO |  | none |  |  |  |
| BL | left2 | Bottom | [Underworks Crushing Path (Under_04)](#underworks-crushing-path-under04) | R | none |  |  |  |
| BR | right3 | Bottom | TODO |  | none |  |  |  |
| WT | left3 | Wisp Thicket | [Underworks Wisp Thicket Passage (Under_23)](#underworks-wisp-thicket-passage-under23) | R | none |  |  |  |
| TR | right1 | Top | TODO |  | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BF | Break Floor | Wisp Thicket | Bottom | cling grip and (spike pogo or clawline or faydown cloak) |  |  |  |
| BM | Bototm to Mid | Bottom | Mid | silk soar or (cling grip and (dash or ledge grab or faydown cloak or sharpart or clawline or drifter's cloak) |  |  |  |
| MT | Mid to Top | Mid | Top | silk soar or cling grip |  |  |  |
| FT | Falling from Top | Top | Mid | none |  |  | falling |
| FM | Falling from Mid | Mid | Bottom | none |  |  | falling |

#### Check Locations

No check locations defined.

### Underworks Crushing Path (Under_04)

**Game ID:** Under_04

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Underworks Saw Shaft (Under_03c)](#underworks-saw-shaft-under03c) | R | dash or clawline | TODO |  | may be other options |
| T | top1 |  | [Underworks Gym (Under_03d)](#underworks-gym-under03d) | B | cling grip | TODO |  | may be other options |
| R | right1 |  | [Underworks Central Shaft (Under_05)](#underworks-central-shaft-under05) | BL | dash or clawline | TODO |  | may be other options |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Shell Shard Cache: Underworks |  | cling grip and (dash or faydown cloak or clawline) | TODO |  | Included | may be other options |

### Underworks Delver's Drill (Under_14)

**Game ID:** Under_14

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Underworks Shaft (Under_02)](#underworks-shaft-under02) | R1 | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Delver's Drill |  | none |  |  | Included |  |

### Underworks Gym (Under_03d)

**Game ID:** Under_03d

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | bot1 |  | [Underworks Crushing Path (Under_04)](#underworks-crushing-path-under04) | T | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Underworks Saw Intro (Under_03b)

**Game ID:** Under_03b

**Contributors:** samupo

#### Subrooms

- Left
- Right

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Left | [Underworks Shaft (Under_02)](#underworks-shaft-under02) | R2 | none |  |  |  |
| R | right1 | Right | [Underworks Saw Shaft (Under_03c)](#underworks-saw-shaft-under03c) | L2 | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| H | Horizontal | Left | Right | ledge grab or dash or clawline or cling grip |  |  |  |
| H | Horizontal | Right | Left | ledge grab or dash or clawline |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Shell Shard Cache: Underworks #12 | Left | none |  |  | Included |  |

### Underworks Saw Shaft (Under_03c)

**Game ID:** Under_03c

**Contributors:** samupo

#### Subrooms

- Top
- Left
- Right

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L2 | left1 | Top | [Underworks Saw Intro (Under_03b)](#underworks-saw-intro-under03b) | R | none |  |  |  |
| L1 | left2 | Left | [Underworks Shard Room (Under_03)](#underworks-shard-room-under03) | R | none |  |  |  |
| R | right1 | Right | [Underworks Crushing Path (Under_04)](#underworks-crushing-path-under04) | L | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| H | Horizontal | Left | Right | dash or clawline or faydown cloak or (spike pogo and ledge grab) or (drifter's cloak and ledge grab) |  |  |  |
| H | Horizontal | Right | Left | dash or clawline or faydown cloak or spike pogo or drifter's cloak |  |  |  |
| V | Vertical | Top | Left | cling grip |  |  |  |
| V | Vertical | Left | Top | cling grip |  |  |  |

#### Check Locations

No check locations defined.

### Underworks Shard Room (Under_03)

**Game ID:** Under_03

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Underworks Saw Shaft (Under_03c)](#underworks-saw-shaft-under03c) | L1 | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Shard Bundle: Underworks #1 |  | easy skips or dash or faydown cloak or drifter's cloak or spike pogo or clawline or sharpdart |  |  | Included |  |

### Underworks Wisp Thicket Passage (Under_23)

**Game ID:** Under_23

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Underworks Central Shaft (Under_05)](#underworks-central-shaft-under05) | WT | cling grip and dash |  |  |  |
| B | bot1 |  | [Wisp Thicket Cave (Wisp_09)](#wisp-thicket-cave-wisp09) | T | cling grip and dash |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Shell Shard Cache: Underworks #13 |  | cling grip and dash |  |  | Included |  |
| Flea: Underworks - Wisp Thicket Passage |  | cling grip and dash |  |  | Included |  |

## Whisp Thicket

### Eastern Wisp Thicket (Wisp_07)

**Game ID:** Wisp_07

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Wisp Thicket Shaft (Wisp_08)](#wisp-thicket-shaft-wisp08) | R | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Mask Shard: Wisp Thicket |  | cling grip and (clawline or (faydown cloak and spike pogo)) |  | Verified | Included |  |

### Wisp Thicket Shaft (Wisp_08)

**Game ID:** Wisp_08

**Contributors:** samupo

#### Subrooms

- Bottom
- Right
- Top

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Bottom | [Wisp Thicket Bench (Wisp_04)](#wisp-thicket-bench-wisp04) | R | none |  |  |  |
| R | right1 | Right | [Eastern Wisp Thicket (Wisp_07)](#eastern-wisp-thicket-wisp07) | L | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | Right to Top | Right | Top | cling grip and spike pogo |  |  |  |
| V2 | Bottom to Right | Bottom | Right | cling grip and spike pogo and faydown cloak |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Relic: Bone Scroll (Wisp Thicket) | Top | none |  |  | Included |  |

### Wisp Thicket Bench (Wisp_04)

**Game ID:** Wisp_04

**Contributors:** samupo

#### Subrooms

- Bench
- Bottom
- Left

- **Bench:** somehow got this duplicated or something internally

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Left | [Wisp Thicket Grounds (Wisp_02)](#wisp-thicket-grounds-wisp02) | R | none |  |  |  |
| R | right1 | Bench | [Wisp Thicket Shaft (Wisp_08)](#wisp-thicket-shaft-wisp08) | L | none |  |  |  |
| B | bot1 | Bottom | TODO |  | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| L1 | Left to Bench | Left | Bench | clawline or dash or spike pogo or drifter's cloak or faydown cloak |  |  |  |
| L2 | Left to Bottom | Left | Bottom | spike pogo or drifter's cloak or clawline or dash |  |  |  |
| B1 | Bench to Left | Bench | Left | (dash and ledge grab) or faydown cloak or clawline |  |  |  |
| B2 | Bench to Bottom | Bench | Bottom | drifter's cloak or spike pogo or clawline or dash |  |  |  |
| V1 | Bottom to Bench | Bottom | Bench | spike pogo or (faydown cloak and clawline) |  |  |  |
| V2 | Bottom to Left | Bottom | Left | spike pogo and (ledge grab or faydown cloak or clawline) |  |  |  |

#### Check Locations

No check locations defined.

### Wisp Thicket Grounds (Wisp_02)

**Game ID:** Wisp_02

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | top1 |  | [Wisp Thicket Secret Path (Wisp_05)](#wisp-thicket-secret-path-wisp05) | B | silk soar or cling grip |  |  |  |
| R | right1 |  | [Wisp Thicket Bench (Wisp_04)](#wisp-thicket-bench-wisp04) | L | none |  |  |  |
| L | left1 |  | [Father of the Flame (Belltown_08)](#father-of-the-flame-belltown08) | R | ledge grab or faydown cloak or silk soar |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Rosary Necklace: Wisp Thicket |  | silk soar or cling grip |  |  | Included |  |

### Father of the Flame (Belltown_08)

**Game ID:** Belltown_08

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Wisp Thicket Grounds (Wisp_02)](#wisp-thicket-grounds-wisp02) | L | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Wispfire Lantern |  | faydown cloak | TODO |  | Included | You can defeat the boss naked... but maybe something is "recommended" |
| Boss: Father of the Flame |  | faydown cloak | TODO |  | Included | You can defeat the boss naked... but maybe something is "recommended" |

### Wisp Thicket Secret Path (Wisp_05)

**Game ID:** Wisp_05

**Contributors:** samupo

#### Subrooms

- Top
- Bottom

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | bot1 | Bottom | [Wisp Thicket Grounds (Wisp_02)](#wisp-thicket-grounds-wisp02) | T | none |  |  |  |
| L | left1 | Top | [Wisp Thicket Cave (Wisp_09)](#wisp-thicket-cave-wisp09) | R | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | Bottom | Top | cling grip and (spike pogo or (faydown cloak and clawline)) |  |  |  |
| V | Vertical | Top | Bottom | spike pogo or drifter's cloak |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Craftmetal: Wisp Thicket | Top | none |  |  | Included |  |

### Wisp Thicket Cave (Wisp_09)

**Game ID:** Wisp_09

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Wisp Thicket Secret Path (Wisp_05)](#wisp-thicket-secret-path-wisp05) | L | spike pogo or clawline or drifter's cloak or (faydown cloak and dash) |  |  |  |
| T | top1 |  | [Underworks Wisp Thicket Passage (Under_23)](#underworks-wisp-thicket-passage-under23) | B | faydown cloak |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Shell Shard Cache: Wisp Thicket #6 |  | (dash and cling grip) clawline or spike pogo or drifter's cloak | TODO |  | Included | May have different requirements if entered from the top |
| Shell Shard Cache: Wisp Thicket #7 |  | (dash and cling grip) or clawline or spike pogo or drifter's cloak | TODO |  | Included | May have different requirements if entered from the top |
| Shell Shard Cache: Wisp Thicket #1 |  | dash or faydown cloak or clawline or spike pogo or drifter's cloak |  |  | Included |  |
| Shell Shard Cache: Wisp Thicket #2 |  | dash or faydown cloak or clawline or spike pogo or drifter's cloak |  |  | Included |  |
| Shell Shard Cache: Wisp Thicket #3 |  | dash or faydown cloak or clawline or spike pogo or drifter's cloak |  |  | Included |  |
| Shell Shard Cache: Wisp Thicket #4 |  | dash or faydown cloak or clawline or spike pogo or drifter's cloak |  |  | Included |  |
| Shell Shard Cache: Wisp Thicket #5 |  | dash or faydown cloak or clawline or spike pogo or drifter's cloak |  |  | Included |  |

## Sinner's Road

## Bilewater

## The Slab

### Slab Bridge (Slab_01)

**Game ID:** Slab_01

**Contributors:** samupo

#### Subrooms

- Left
- Right

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Left | TODO |  | none |  |  |  |
| R | right1 | Right | [Choral Chambers Outside Spa (Song_04)](#choral-chambers-outside-spa-song04) | L | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| H | Horizontal | Left | Right | cling grip or ledge grab or faydown cloak or clawline |  | Verified | You can jump off of the left obstacle and use clawline twice, this cannot be done from the other side |
| H | Horizontal | Right | Left | cling grip or ledge grab or faydown cloak |  | Verified |  |

#### Check Locations

No check locations defined.

## Sands of Karak

## Mount Fay

## Choral Chambers

### Choral Chambers Spa (Song_10)

**Game ID:** Song_10

**Contributors:** samupo

#### Subrooms

- Showers
- Spa

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Showers | [Choral Chambers Outside Spa (Song_04)](#choral-chambers-outside-spa-song04) | R2 | none |  | Verified |  |
| R | right1 | Spa | [Choral Chambers Flea Shaft (Song_11)](#choral-chambers-flea-shaft-song11) | BLB | cling grip or silk soar or (faydown cloak and ledge grab) |  | Verified | one way door, opens from this side |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| H | Horizontal | Showers | Spa | cling grip | TODO |  |  |
| H | Horizontal | Spa | Showers | none |  | Verified | lever shortcut |

#### Check Locations

No check locations defined.

### Choral Chambers Outside Spa (Song_04)

**Game ID:** Song_04

**Contributors:** samupo

#### Subrooms

- Base
- Gauntlet
- Left
- Top

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | bot1 | Left | [Choral Chambers Above Ventrica (Song_03)](#choral-chambers-above-ventrica-song03) | T | none |  | Verified |  |
| L | left1 | Top | [Slab Bridge (Slab_01)](#slab-bridge-slab01) | R | none |  | Verified |  |
| R1 | right1 | Top | [Choral Chambers Western Shaft (Song_12)](#choral-chambers-western-shaft-song12) | BL | none |  | Verified |  |
| R2 | right2 | Base | [Choral Chambers Spa (Song_10)](#choral-chambers-spa-song10) | L | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | Top | Base | none |  | Verified | falling |
| V | Vertical | Base | Top | cling grip or silk soar |  | Verified |  |
| GL | Gauntlet Left | Left | Gauntlet | none |  | Verified |  |
| GL | Gauntlet Left | Gauntlet | Left | gauntlet |  | Verified |  |
| GR | Gauntlet Right | Base | Gauntlet | none |  | Verified |  |
| GR | Gauntlet Right | Gauntlet | Base | gauntlet |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Heavy Rosary Necklace: Choral Chambers | Base | cling grip or silk soar |  |  | Included | Secret hidden by breaking the ceiling |

### Choral Chambers Western Shaft (Song_12)

**Game ID:** Song_12

**Contributors:** samupo

#### Subrooms

- Bottom
- Section 1
- Section 2
- Section 3
- Section 4 Left
- Section 4 Right

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BL | left1 | Bottom | [Choral Chambers Outside Spa (Song_04)](#choral-chambers-outside-spa-song04) | R1 | none |  |  |  |
| BR | right3 | Bottom | [Choral Chambers Above Spa (Song_13)](#choral-chambers-above-spa-song13) | L | none |  |  |  |
| S1L | left4 | Section 1 | [Choral Chambers Shop (Song_28)](#choral-chambers-shop-song28) | R | none |  |  |  |
| S2R | right2 | Section 2 | [Choral Chambers Flea Room (Song_14)](#choral-chambers-flea-room-song14) | L | none |  |  |  |
| S3L | left2 | Section 3 | [Choral Chambers Cogheart Room (Song_26)](#choral-chambers-cogheart-room-song26) | R | none |  |  |  |
| S4R | right1 | Section 4 Right | [Choral Chambers Maintenance Tunnel (Song_15)](#choral-chambers-maintenance-tunnel-song15) | L | none |  |  |  |
| S4L | left3 | Section 4 Left | [Choral Chambers Grindle (Song_08)](#choral-chambers-grindle-song08) | R | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | Bottom to Section 1 | Bottom | Section 1 | silk soar or (faydown cloak and ledge grab) or (cling grip and (dash or faydown cloak or clawline or sharpdart)) |  | Verified |  |
| V2 | Section 1 to Section 2 | Section 1 | Section 2 | ledge grab or silk soar or faydown cloak or clawline |  | Verified |  |
| V3 | Section 2 to Section 3 | Section 2 | Section 3 | silk soar or cling grip or (faydown cloak and ledge grab) |  | Verified |  |
| V4L | Section 3 to Section 4 Left | Section 3 | Section 4 Left | cling grip or (faydown cloak and ledge grab) |  | Verified |  |
| V4R | Section 3 to Section 4 Right | Section 3 | Section 4 Right | spike pogo or silk soar or (faydown cloak and ledge grab) |  | Verified |  |
| S4 | Section 4 traversal | Section 4 Left | Section 4 Right | clawline or drifter's cloak or dash or faydown cloak or sharpdart |  | Verified |  |
| S4 | Section 4 traversal | Section 4 Right | Section 4 Left | clawline or drifter's cloak or dash or faydown cloak or sharpdart |  | Verified |  |
| F4L | Section 4 Left falling | Section 4 Left | Section 3 | none |  | Verified | falling |
| F4R | Section 4 Right falling | Section 4 Right | Section 3 | none |  | Verified | falling |
| F3 | Section 3 Falling | Section 3 | Section 2 | none |  | Verified | falling |
| F2 | Section 2 Falling | Section 2 | Section 1 | none |  | Verified | falling |
| F1 | Section 1 Falling | Section 1 | Bottom | none |  | Verified | falling |

#### Check Locations

No check locations defined.

### Choral Chambers Shop (Song_28)

**Game ID:** Song_28

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Choral Chambers Western Shaft (Song_12)](#choral-chambers-western-shaft-song12) | S1L | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Choral Chambers Cogheart Room (Song_26)

**Game ID:** Song_26

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Choral Chambers Western Shaft (Song_12)](#choral-chambers-western-shaft-song12) | S3L | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Choral Chambers Grindle (Song_08)

**Game ID:** Song_08

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Choral Chambers Western Shaft (Song_12)](#choral-chambers-western-shaft-song12) | S4L | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Choral Chambers Flea Room (Song_14)

**Game ID:** Song_14

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Choral Chambers Western Shaft (Song_12)](#choral-chambers-western-shaft-song12) | S2R | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Flea: Choral Chambers - Spa |  | none |  | Verified | Included |  |

### Choral Chambers Above Spa (Song_13)

**Game ID:** Song_13

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Choral Chambers Flea Shaft (Song_11)](#choral-chambers-flea-shaft-song11) | BLT | none |  | Verified |  |
| L | left1 |  | [Choral Chambers Western Shaft (Song_12)](#choral-chambers-western-shaft-song12) | BR | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Choral Chambers Maintenance Tunnel (Song_15)

**Game ID:** Song_15

**Contributors:** samupo

#### Subrooms

- Base
- Maintenance Tunnel

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Base | [Choral Chambers Flea Shaft (Song_11)](#choral-chambers-flea-shaft-song11) | S2L | none |  | Verified |  |
| L | left1 | Maintenance Tunnel | [Choral Chambers Western Shaft (Song_12)](#choral-chambers-western-shaft-song12) | S4R | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | Base | Maintenance Tunnel | silk soar |  |  |  |
| V | Vertical | Maintenance Tunnel | Base | silk soar or cling grip |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Rosary Cache: Choral Chambers #17 | Base | none |  |  | Included |  |
| Rosary Cache: Choral Chambers #18 | Base | none |  |  | Included |  |
| Rosary Cache: Choral Chambers #19 | Base | none |  |  | Included |  |

### Choral Chambers Flea Shaft (Song_11)

**Game ID:** Song_11

**Contributors:** samupo

#### Subrooms

- Base Bottom
- Base Upper
- Top Section 1
- Top Section 2
- Top Section 3 Left
- Top Section 3 Right

- **Base Bottom:** Base Isolated from Top by one-way door available on Top
- **Base Upper:** Base Isolated from Top by one-way door available on Top

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| S3L | left1 | Top Section 3 Left | [Corridor to High Halls (Song_17)](#corridor-to-high-halls-song17) | R | none |  |  |  |
| S2L | left2 | Top Section 2 | [Choral Chambers Maintenance Tunnel (Song_15)](#choral-chambers-maintenance-tunnel-song15) | R | none |  |  |  |
| S3R | right2 | Top Section 3 Right | [High Halls Corridor (Hang_07)](#high-halls-corridor-hang07) | L | ledge grab or faydown cloak or cling grip or silk soar |  |  |  |
| BLB | left4 | Base Upper | [Choral Chambers Spa (Song_10)](#choral-chambers-spa-song10) | R | breakable wall -must be opened from the other side |  |  |  |
| BR | right3 | Base Bottom | [Choral Chambers Eastern Shaft (Song_05)](#choral-chambers-eastern-shaft-song05) | L3 | none |  |  |  |
| BLT | left3 | Base Upper | [Choral Chambers Above Spa (Song_13)](#choral-chambers-above-spa-song13) | R | none |  |  |  |
| S1R | right1 | Top Section 1 | [Choral Chambers Dining Room (Song_09b)](#choral-chambers-dining-room-song09b) | L | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| VB | Vertical Base | Base Bottom | Base Upper | silk soar faydown cloak or (cling grip and ((dash and ledge grab) or (drifter's cloak and ledge grab) or clawline)) |  |  |  |
| VB | Vertical Base | Base Upper | Base Bottom | none |  |  | falling |
| VL | Vertical Lever | Top Section 1 | Base Upper | none |  |  | one way, falling |
| V1 | Section 1 to Section 2 | Top Section 1 | Top Section 2 | silk soar or cling grip or (faydown cloak and ledge grab) |  |  |  |
| V2L | Section 2 to Section 3 Left | Top Section 2 | Top Section 3 Left | silk soar and (ledge grab or clawline or dash or sharpdart or faydown cloak) |  |  |  |
| V3R | Section 2 to Section 3 Right | Top Section 2 | Top Section 3 Right | silk soar or (cling grip and (clawline or dash)) |  |  |  |
| F3L | Section 3 Right falling | Top Section 3 Right | Top Section 2 | none |  |  | falling |
| F3R | Section 3 Left falling | Top Section 3 Left | Top Section 2 | none |  |  | falling |
| F2 | Section 2 falling | Top Section 2 | Top Section 1 | none |  |  | falling |
| H | Top Horizontal Traversal | Top Section 3 Right | Top Section 3 Left | ledge grab or clawline or drifter's cloak | TODO |  | check sharpdart |
| H | Top Horizontal Traversal | Top Section 3 Left | Top Section 3 Right | ledge grab or clawline or cling grip |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Flea: Choral Chambers - Walled Room | Top Section 2 | (cling grip and drifter's cloak) or silk soar |  |  | Included |  |
| Rosary Cache: Choral Chambers #14 | Base Upper | clawline or faydown cloak or (dash and ledge grab) | TODO |  | Included | check, probably better to split Base Upper into two zones since they can be gotten from BLT easier than from BLB |
| Rosary Cache: Choral Chambers #15 | Base Upper | clawline or faydown cloak or (dash and ledge grab) | TODO |  | Included | check, probably better to split Base Upper into two zones since they can be gotten from BLT easier than from BLB |
| Rosary Cache: Choral Chambers #16 | Base Upper | clawline or faydown cloak or (dash and ledge grab) | TODO |  | Included | check, probably better to split Base Upper into two zones since they can be gotten from BLT easier than from BLB |

### High Halls Corridor (Hang_07)

**Game ID:** Hang_07

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Choral Chambers Flea Shaft (Song_11)](#choral-chambers-flea-shaft-song11) | S3R | one way entrance, opens from the other side |  | Verified | one way entrance, opens from the other side |
| R | right1 |  | [Cog Dancers (Cog_Dancers)](#cog-dancers-cogdancers) | L | none |  | Verified |  |
| B | bot1 |  | [Choral Chambers Over Dininig (Song_09)](#choral-chambers-over-dininig-song09) | T | none |  | Verified |  |
| T | top1 |  | TODO |  | one way entrance, opens from the other side |  | Verified | one way entrance, opens from the other side |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Corridor to High Halls (Song_17)

**Game ID:** Song_17

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Choral Chambers Flea Shaft (Song_11)](#choral-chambers-flea-shaft-song11) | S3L |  |  |  |  |
| L | left1 |  | TODO |  |  |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Choral Chambers Over Dininig (Song_09)

**Game ID:** Song_09

**Contributors:** samupo

#### Subrooms

- Top
- Base
- Right Secret

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Right Secret | TODO |  | none |  |  |  |
| T | top1 | Top | [High Halls Corridor (Hang_07)](#high-halls-corridor-hang07) | B | none |  |  |  |
| B | bot1 | Base | [Choral Chambers Dining Room (Song_09b)](#choral-chambers-dining-room-song09b) | T | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | Top | Base | none |  |  | falling |
| V | Vertical | Base | Top | cling grip or faydown cloak or silk soar | TODO |  | Needs checking |
| S | Secret | Right Secret | Base | none |  |  | one way door |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Rosary Cache: Choral Chambers #11 | Top | none |  |  | Included | falling |
| Rosary Cache: Choral Chambers #12 | Top | none |  |  | Included | falling |
| Rosary Cache: Choral Chambers #13 | Top | none |  |  | Included | falling |
| Mask Shard: Cogwork Core | Right Secret | none |  |  | Included |  |

### Choral Chambers Dining Room (Song_09b)

**Game ID:** Song_09b

**Contributors:** samupo

#### Subrooms

- Diner
- Below Diner

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | top1 | Diner | [Choral Chambers Over Dininig (Song_09)](#choral-chambers-over-dininig-song09) | B | ledge grab or clawline or faydown cloak or silk soar |  |  |  |
| L | left1 | Below Diner | [Choral Chambers Flea Shaft (Song_11)](#choral-chambers-flea-shaft-song11) | S1R | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | Diner | Below Diner | none |  |  | one way levers |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Silkeater: Choral Chambers East | Below Diner | ledge grab or silk soar or cling grip or faydown cloak | TODO |  | Included | Check |

### Choral Chambers Eastern Shaft (Song_05)

**Game ID:** Song_05

**Contributors:** samupo

#### Subrooms

- Section 1
- Section 2
- Section 3
- Section 4

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L1 | left5 | Section 1 | [Choral Chambers Below Spa (Song_02)](#choral-chambers-below-spa-song02) | R | none |  | Verified |  |
| R1 | right3 | Section 1 | TODO |  | none |  | Verified |  |
| L2 | left4 | Section 3 | [Choral Chambers Merchant Room (Song_07)](#choral-chambers-merchant-room-song07) | R | none |  | Verified |  |
| R2 | right4 | Section 2 | [Choral Chambers East to West (Song_27)](#choral-chambers-east-to-west-song27) | L | door should be opened from the other side |  | Verified |  |
| L3 | left3 | Section 3 | [Choral Chambers Flea Shaft (Song_11)](#choral-chambers-flea-shaft-song11) | BR | none |  | Verified |  |
| R4 | right2 | Section 4 | [Choral Chambers Below Dining (Song_18)](#choral-chambers-below-dining-song18) | L | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | Section 1 to Section 2 | Section 1 | Section 2 | (ledge grab and pogo) or silk soar or (cling grip and (dash or clawline) |  |  |  |
| V2 | Section 2 to Section 3 | Section 2 | Section 3 | silk soar or (cling grip and (ledge grab or clawline)) or faydown cloak |  |  |  |
| V3 | Section 3 to Section 4 | Section 3 | Section 4 | ((ledge grab or clawline) and pogo) or silk soar |  |  |  |
| F4 | Falling from Section 4 | Section 4 | Section 3 | none |  |  | falling |
| F3 | Falling from Section 3 | Section 3 | Section 2 | none |  |  | falling |
| F2 | Falling from Section 2 | Section 2 | Section 1 | none |  |  | falling |

#### Check Locations

No check locations defined.

### Choral Chambers Merchant Room (Song_07)

**Game ID:** Song_07

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Choral Chambers Eastern Shaft (Song_05)](#choral-chambers-eastern-shaft-song05) | L2 | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Rosary Cache: Choral Chambers #10 |  | cling grip |  | Verified | Included |  |

### Choral Chambers Below Dining (Song_18)

**Game ID:** Song_18

**Contributors:** samupo

#### Subrooms

- Top
- Bottom

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Top | [Choral Chambers Eastern Shaft (Song_05)](#choral-chambers-eastern-shaft-song05) | R4 | none |  |  |  |
| B | bot1 | Bottom | [Choral Chambers East to West (Song_27)](#choral-chambers-east-to-west-song27) | T | none |  |  | one way only, cannot be traversed from the other side |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | Top | Bottom | none |  |  | falling |
| V | Vertical | Bottom | Top | silk soar or cling grip |  |  |  |

#### Check Locations

No check locations defined.

### Choral Chambers Below Spa (Song_02)

**Game ID:** Song_02

**Contributors:** samupo

#### Subrooms

- Left
- Right

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Right | [Choral Chambers Eastern Shaft (Song_05)](#choral-chambers-eastern-shaft-song05) | L1 | none |  |  |  |
| L | left2 | Left | [Choral Chambers Ventrica Room (Song_01b)](#choral-chambers-ventrica-room-song01b) | R | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| H | Horizontal | Right | Left | cling grip or silk soar |  |  |  |
| H | Horizontal | Left | Right | ledge grab or faydown cloak or silk soar |  |  |  |

#### Check Locations

No check locations defined.

### Choral Chambers Above Ventrica (Song_03)

**Game ID:** Song_03

**Contributors:** samupo

#### Subrooms

- Top
- Bottom

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | bot1 | Bottom | [Choral Chambers Ventrica Room (Song_01b)](#choral-chambers-ventrica-room-song01b) | T | none |  |  |  |
| T | top1 | Top | [Choral Chambers Outside Spa (Song_04)](#choral-chambers-outside-spa-song04) | B | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | Top | Bottom | none |  |  | falling |
| V | Vertical | Bottom | Top | silk soar or (cling grip and (faydown cloak or clawline or dash)) or (faydown cloak and ledge grab) |  |  |  |

#### Check Locations

No check locations defined.

### Choral Chambers Ventrica Room (Song_01b)

**Game ID:** Song_01b

**Contributors:** samupo

#### Subrooms

- Ventrica
- Lateral

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Lateral | [Choral Chambers Below Spa (Song_02)](#choral-chambers-below-spa-song02) | L | none |  |  |  |
| T | top1 | Ventrica | [Choral Chambers Above Ventrica (Song_03)](#choral-chambers-above-ventrica-song03) | B | cling grip or silk soar or faydown cloak |  |  |  |
| B | bot1 | Lateral | [Choral Chambers Below Ventrica (Song_01)](#choral-chambers-below-ventrica-song01) | T | none |  |  |  |
| V | door_tubeEnter | Ventrica | [Ventrica Menu](#ventrica-menu) | CC | rosaries |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| H | Horizontal | Ventrica | Lateral | none |  |  | one way door |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Map Purchase: Choral Chambers | Lateral | rosaries |  |  | Included |  |
| Rosary Cache: Choral Chambers #5 | Ventrica | none |  |  | Included |  |
| Rosary Cache: Choral Chambers #6 | Ventrica | none |  |  | Included |  |
| Rosary Cache: Choral Chambers #7 | Ventrica | none |  |  | Included |  |
| Ventrica: Choral Chambers | Ventrica | rosaries |  |  | Included |  |

### Choral Chambers Below Ventrica (Song_01)

**Game ID:** Song_01

**Contributors:** samupo

#### Subrooms

- Bottom
- Window
- Right Exit
- Side Chamber
- Pre Top
- Top

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | bot1 | Bottom | [Grand Gate Maintenance Room (Song_01c)](#grand-gate-maintenance-room-song01c) | T | none |  |  |  |
| T | top1 | Top | [Choral Chambers Ventrica Room (Song_01b)](#choral-chambers-ventrica-room-song01b) | B | cling grip or silk soar |  |  |  |
| R | right2 | Right Exit | [Choral Chambers Outisde Underworks (Under_07b)](#choral-chambers-outisde-underworks-under07b) | L | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | Pre Top to Top | Pre Top | Top | cling grip or faydown cloak |  |  |  |
| V2 | Side Chamber to Top | Side Chamber | Top | silk soar or cling grip |  |  |  |
| V3 | Window to Side Chamber | Window | Side Chamber | silk soar or cling grip |  |  |  |
| V4 | Bottom to Window | Bottom | Window | (cling grip and (ledge grab or clawline or faydown cloak)) or silk soar |  |  |  |
| V5 | Bottom to Right Exit | Bottom | Right Exit | faydown cloak or (cling grip and (ledge grab or clawline)) or silk soar |  |  |  |
| FT | Falling from Top | Top | Pre Top | none |  |  | falling |
| FPT | Falling from Pre Top | Pre Top | Side Chamber | none |  |  | falling |
| LV | Lever | Window | Right Exit | none |  |  | one side lever |
| SW | Side Chamber to Window | Side Chamber | Window | none |  |  |  |
| FW | Falling from Window | Window | Bottom | none |  |  | falling |
| FR | Falling from Right Exit | Right Exit | Bottom | none |  |  | falling |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Rosary Cache: Choral Chambers #3 | Pre Top | none |  |  | Included |  |
| Rosary Cache: Choral Chambers #4 | Pre Top | none |  |  | Included |  |
| Shell Shard Cache: Choral Chambers | Side Chamber | none |  |  | Included |  |
| Rosary Cache: Choral Chambers #1 | Window | none |  |  | Included |  |
| Rosary Cache: Choral Chambers #2 | Window | none |  |  | Included |  |

### Choral Chambers Outisde Underworks (Under_07b)

**Game ID:** Under_07b

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | bot1 |  | [Underworks Outside Choral Chambers (Under_07c)](#underworks-outside-choral-chambers-under07c) | T | Only opened from the other side |  |  |  |
| L | left1 |  | [Choral Chambers Below Ventrica (Song_01)](#choral-chambers-below-ventrica-song01) | R | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Songclave (Song_Enclave)

**Game ID:** Song_Enclave

**Contributors:** samupo

#### Subrooms

- Base
- Top Platform

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BL | left2 | Base | [Songclave Steam Tunnel (Library_02)](#songclave-steam-tunnel-library02) | TR | none |  | Verified |  |
| TL | left1 | Top Platform | [Memorium Entrance Tunnel (Song_25)](#memorium-entrance-tunnel-song25) | R | none |  | Verified |  |
| T | top1 | Top Platform | [Songclave Tube (Song_Enclave_Tube)](#songclave-tube-songenclavetube) | B | none |  | Verified |  |
| D | door1 | Base | TODO |  | none |  | Verified |  |
| B | bot1 | Base | TODO |  | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | Base | Top Platform | silk soar or cling grip |  | Verified |  |
| V | Vertical | Top Platform | Base | none |  | Verified | falling |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| White Key | Base | none |  |  | Included |  |

### Songclave Tube (Song_Enclave_Tube)

**Game ID:** Song_Enclave_Tube

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | bot1 |  | [Songclave (Song_Enclave)](#songclave-songenclave) | T | none |  |  |  |
| V | door_tubeEnter |  | [Ventrica Menu](#ventrica-menu) | FS | ventrica | TODO |  | ventrica, repeat for each possible exit |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Ventrica: Songclave |  | none |  |  | Included |  |

### Memorium Entrance Tunnel (Song_25)

**Game ID:** Song_25

**Contributors:** samupo

#### Subrooms

- Base
- Secret Platform

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TL | top2 | Secret Platform | TODO |  | none | TODO |  |  |
| L | left1 | Base | [Cog Dancers (Cog_Dancers)](#cog-dancers-cogdancers) | R | none |  | Verified |  |
| T | top1 | Base | TODO |  | (silk soar or faydown cloak) and breaking wall |  | Verified |  |
| R | right1 | Base | [Songclave (Song_Enclave)](#songclave-songenclave) | TL | none |  | Verified |  |
| B | bot1 | Base | [Rotating Tunnel (Song_20b)](#rotating-tunnel-song20b) | T | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical Secret | Base | Secret Platform | act3 and silk soar | TODO |  | NEEDS LOGIC, PROBABLY ACT 3 ONLY |
| V | Vertical Secret | Secret Platform | Base | none | TODO |  | Not verified, most likely falling |

#### Check Locations

No check locations defined.

### Songclave Steam Tunnel (Library_02)

**Game ID:** Library_02

**Contributors:** samupo

#### Subrooms

- Top
- Bottom

- **Bottom:** TODO

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BL | left1 | Top | [Rotating Tunnel (Song_20b)](#rotating-tunnel-song20b) | RH |  | TODO |  |  |
| TL | left2 |  | [Rotating Tunnel (Song_20b)](#rotating-tunnel-song20b) | R1 |  | TODO |  |  |
| BR | right1 |  | TODO |  |  | TODO |  |  |
| TR | right2 | Top | [Songclave (Song_Enclave)](#songclave-songenclave) | BL |  | TODO |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Rotating Tunnel (Song_20b)

**Game ID:** Song_20b

**Contributors:** samupo

#### Subrooms

- Top Platform
- Central Area
- Bottom Area
- Horizontal Tunnel

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | top1 | Top Platform | [Memorium Entrance Tunnel (Song_25)](#memorium-entrance-tunnel-song25) | B | none |  | Verified |  |
| L1 | left2 | Central Area | [Songclave Silk Shop (Song_29)](#songclave-silk-shop-song29) | R | ledge grab or dash or faydown cloak or clawline or sharpdart or drifter's cloak or silk soar or enemy pogo |  | Verified |  |
| R1 | right2 | Central Area | [Songclave Steam Tunnel (Library_02)](#songclave-steam-tunnel-library02) | TL | none |  | Verified |  |
| B | bot1 | Bottom Area | [Grand Bellway Shaft (Song_20)](#grand-bellway-shaft-song20) | T | none |  | Verified |  |
| RH | right3 | Horizontal Tunnel | [Songclave Steam Tunnel (Library_02)](#songclave-steam-tunnel-library02) | BL | none |  | Verified | both sides have levers making the tunnel horizontal |
| LH | left4 | Horizontal Tunnel | TODO |  | none |  | Verified | both sides have levers making the tunnel horizontal |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | Top Platform | Central Area | none |  | Verified | falling, door on top platform's side (no inverse) |
| T | Tunnel | Central Area | Bottom Area | none |  | Verified | falling, both sides have levers making the tunnel vertical |
| T | Tunnel | Bottom Area | Central Area | silk soar or cling grip |  | Verified | both sides have levers making the tunnel vertical |

#### Check Locations

No check locations defined.

### Songclave Silk Shop (Song_29)

**Game ID:** Song_29

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Rotating Tunnel (Song_20b)](#rotating-tunnel-song20b) | L1 | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Grand Bellway Shaft (Song_20)

**Game ID:** Song_20

**Contributors:** samupo

#### Subrooms

- Top
- Upper Right
- Upper Left
- Right Stage
- Bottom Left
- Bottom Right

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | left1 | Upper Left | [Choral Chambers East to West (Song_27)](#choral-chambers-east-to-west-song27) | R | none |  |  |  |
| T | top1 | Top | [Rotating Tunnel (Song_20b)](#rotating-tunnel-song20b) | B | none |  |  |  |
| UR | right4 | Upper Right | [Grand Bellway Library (Library_03)](#grand-bellway-library-library03) | L | none |  |  |  |
| RS | right5 | Right Stage | TODO |  | none |  |  |  |
| BR | right6 | Bottom Right | [Grand Bellway (Bellway_City)](#grand-bellway-bellwaycity) | L | none |  |  |  |
| BL | left2 | Bottom Left | [Grand Bellway Side Room (Song_24)](#grand-bellway-side-room-song24) | R | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| F1 | Top to Upper Right | Top | Upper Right | none |  | Verified | falling |
| F2 | Upper Right to Upper Left | Upper Right | Upper Left | none |  | Verified | falling |
| F3 | Upper Left to Right Stage | Upper Left | Right Stage | none |  | Verified | falling |
| F4 | Right Stage to Bottom Left | Right Stage | Bottom Left | none |  | Verified | falling |
| F5 | Bottom Left to Bottom Right | Bottom Left | Bottom Right | none |  | Verified | falling |
| J5 | Bottom Right to Bottom Left | Bottom Right | Bottom Left | silk soar or cling grip |  |  | Might be able to use enemy pogo and faydown cloak |
| J4 | Bottom Left to Right Stage | Bottom Left | Right Stage | ((faydown cloak or pogo) and cling grip) or silk soar |  |  |  |
| J3 | Right Stage to Upper Left | Right Stage | Upper Left | (faydown cloak or pogo) and cling grip |  |  |  |
| J3E | Bottom Right to Upper Left | Bottom Right | Upper Left | silk soar |  |  |  |
| J2 | Upper Left to Upper Right | Upper Left | Upper Right | ((clawline or dash or faydown cloak or (drifter's cloak and ledge grab)) and cling grip and pogo) or silk soar |  |  |  |
| J1 | Upper Right to Top | Upper Right | Top | ledge grab or silk soar or clawline or faydown cloak |  |  |  |

#### Check Locations

No check locations defined.

### Grand Bellway Side Room (Song_24)

**Game ID:** Song_24

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Grand Bellway Shaft (Song_20)](#grand-bellway-shaft-song20) | BL | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Silkeater: Choral Chambers West |  | spike pogo or dash or clawline or faydown cloak or sharpdart or drifer's cloak or cling grip |  | Verified | Included |  |

### Grand Bellway (Bellway_City)

**Game ID:** Bellway_City

**Contributors:** samupo

#### Subrooms

- Base
- Secret Tunnel

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Secret Tunnel | TODO |  |  | TODO |  |  |
| L | left1 | Base | [Grand Bellway Shaft (Song_20)](#grand-bellway-shaft-song20) | BR | none |  | Verified |  |
| BW | door_fastTravelExit | Base | [Bellway Menu](#bellway-menu) | GB | rosaries | TODO |  |  |
| VT | door_tubeEnter | Base | [Ventrica Menu](#ventrica-menu) | GB | rosaries | TODO |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | Secret Tunnel | Base | none |  |  | falling, one sided door |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Memory Locket: Choral Chambers | Secret Tunnel | none |  | Verified | Included | breakable wall |
| Ventrica: Grand Bellway | Base | rosaries |  | Verified | Included |  |
| Map Purchase: Choral Chambers | Base | rosaries |  | Verified | Included |  |
| Bellway: Grand Bellway | Base | rosaries |  | Verified | Included |  |

### Grand Bellway Library (Library_03)

**Game ID:** Library_03

**Contributors:** samupo

#### Subrooms

- Bottom
- Top

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Bottom | [Grand Bellway Shaft (Song_20)](#grand-bellway-shaft-song20) | UR | none |  |  |  |
| R | right1 | Top | TODO |  | none | TODO |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | Top | Bottom | none | TODO |  | lever, one sided door |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Pale Oil: Whispering Vaults | Top | none | TODO |  | Included |  |

### Choral Chambers East to West (Song_27)

**Game ID:** Song_27

**Contributors:** samupo

#### Subrooms

- Left Side
- Right Side

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | top1 | Left Side | [Choral Chambers Below Dining (Song_18)](#choral-chambers-below-dining-song18) | B | One way, can't be used at all from this side even if you entered from it! | TODO |  | One way, can't be used at all from this side even if you entered from it! |
| R | right1 | Right Side | [Grand Bellway Shaft (Song_20)](#grand-bellway-shaft-song20) | UL |  | TODO |  |  |
| L | left1 | Left Side | [Choral Chambers Eastern Shaft (Song_05)](#choral-chambers-eastern-shaft-song05) | R2 | none |  |  | one way door |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| H | Horizontal | Left Side | Right Side | clawline or ledge grab or faydown cloak or spike pogo |  | Verified |  |
| H | Horizontal | Right Side | Left Side | clawline or ledge grab or faydown cloak or spike pogo |  |  |  |

#### Check Locations

No check locations defined.

#### Notes

Door on the east can be only opened from the west

## White Ward

## Cogwork Core

### Cog Dancers (Cog_Dancers)

**Game ID:** Cog_Dancers

**Contributors:** samupo

#### Subrooms

- BaseLeft
- Top
- BaseRight
- BossArena

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | BaseRight | [Memorium Entrance Tunnel (Song_25)](#memorium-entrance-tunnel-song25) | L | none |  | Verified |  |
| L | left1 | BaseLeft | [High Halls Corridor (Hang_07)](#high-halls-corridor-hang07) | R | none |  | Verified |  |
| B1 | bot1 | BossArena | TODO |  | Boss: Cogwork Dancers |  | Verified |  |
| B2 | bot2 | BossArena | TODO |  | Boss: Cogwork Dancers |  | Verified |  |
| E | elevator | BossArena | TODO |  | Boss: Cogwork Dancers and more | TODO |  | TODO: Check all that's needed for the elevator to work |
| D | door1 | Top | TODO |  |  | TODO |  | TODO |
| T | top1 | Top | TODO |  | clawline | TODO |  | probably one way |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | BossArena | Top | Boss: Cogwork Dancers and silk soar |  | Verified |  |
| V | Vertical | Top | BossArena | none | TODO |  | falling, check if dancers boss is required on a new save |
| R | RightSide | BaseRight | BossArena | none |  | Verified |  |
| R | RightSide | BossArena | BaseRight | Boss: Cogwork Dancers |  | Verified |  |
| L | LeftSide | BossArena | BaseLeft | Boss: Cogwork Dancers |  | Verified |  |
| L | LeftSide | BaseLeft | BossArena | none |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Boss: Cogwork Dancers | BossArena | any crest |  | Verified | Included |  |

#### Notes

Boss needs only any crest to be beatable. The big line attack can be parried with appropriate timing.

## Whispering Vaults

## High Halls

## Memorium

## Putrified Ducts

## The Cradle

## The Abyss

## Fast Travel

### Bellway Menu

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BB | bone bottom |  | [Bone Bottom Bellway (Bellway_01)](#bone-bottom-bellway-bellway01) | BB |  | TODO |  |  |
| TM | the marrow |  | TODO |  |  | TODO |  |  |
| DD | deep docks |  | [Deep Docks Bellway (Bellway_02)](#deep-docks-bellway-bellway02) | BB |  | TODO |  |  |
| FF | far fields |  | [Far Fields Bellway (Bellway_03)](#far-fields-bellway-bellway03) | BB |  | TODO |  |  |
| GM | greymoor |  | TODO |  |  | TODO |  |  |
| BH | bellhart |  | TODO |  |  | TODO |  |  |
| SW | shellwood |  | TODO |  |  | TODO |  |  |
| BS | blasted steps |  | TODO |  |  | TODO |  |  |
| TS | the slab |  | TODO |  |  | TODO |  |  |
| GB | grand bellway |  | [Grand Bellway (Bellway_City)](#grand-bellway-bellwaycity) | BW |  | TODO |  |  |
| BW | bilewater |  | TODO |  |  | TODO |  |  |
| PD | putrified ducts |  | TODO |  |  | TODO |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

#### Notes

a virtual room to represent the bellway fast travel menu

### Ventrica Menu

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | terminus |  | TODO |  |  | TODO |  |  |
| M | memorium |  | TODO |  |  | TODO |  |  |
| HH | high halls |  | TODO |  |  | TODO |  |  |
| FS | first shrine |  | [Songclave Tube (Song_Enclave_Tube)](#songclave-tube-songenclavetube) | V |  | TODO |  |  |
| CC | choral chambers |  | [Choral Chambers Ventrica Room (Song_01b)](#choral-chambers-ventrica-room-song01b) | V |  | TODO |  |  |
| GB | grand bellway |  | [Grand Bellway (Bellway_City)](#grand-bellway-bellwaycity) | VT |  | TODO |  |  |
| UW | underworks |  | TODO |  |  | TODO |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

#### Notes

a virtual room to represent the ventrica fast travel menu
