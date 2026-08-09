# Silksong Randomizer Logic

Compiled from the database-generated room notes.

## Bone Bottom

### Moss Grotto Center (Tut_01)

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
| C | ceiling | up and away | [Bone Bottom (Bonetown)](#bone-bottom-bonetown) | RF | has loading zone blocker until you first leave moss grotto |  |  | maybe see if removing this loading zone makes sense? |

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

#### Subrooms

- chapel
- boss room
- bench room

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right | bench room | [Moss Grotto Center (Tut_01)](#moss-grotto-center-tut01) | UL | none |  |  |  |
| AR | ascend rope | chapel | [Bone Bottom (Bonetown)](#bone-bottom-bonetown) | DR | none |  |  |  |
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

### Bone Bottom (Bonetown)

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

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BD | bellway door |  | [Bone Bottom (Bonetown)](#bone-bottom-bonetown) | BD | none |  |  |  |
| BB | bell beast |  | [Bellway Menu](#bellway-menu) | BB | bell beast available AND bone bottom bellway unlocked | TODO |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Bonegrave (Bonegrave)

#### Subrooms

- upper left exit
- upper right exit
- graveyard

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | upper right | upper right exit | [Bone Bottom (Bonetown)](#bone-bottom-bonetown) | UL | none |  |  |  |
| LR | lower right | graveyard | [Bone Bottom (Bonetown)](#bone-bottom-bonetown) | LL | none |  |  |  |
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

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LL | lower left |  | [Bone Bottom (Bonetown)](#bone-bottom-bonetown) | UR | none |  |  |  |
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
| LF | left floor | bottom area | [Bone Bottom (Bonetown)](#bone-bottom-bonetown) | LC | none |  |  |  |
| RF | right floor | lower right area | [Bone Bottom (Bonetown)](#bone-bottom-bonetown) | RC | none |  |  |  |

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

## The Marrow

### The Marrow Entrance (Bone_01)

#### Subrooms

- before gauntlet
- gauntlet room
- after gauntlet
- ceiling exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LL | lower left | before gauntlet | [Bone Bottom (Bonetown)](#bone-bottom-bonetown) | LR | none |  |  |  |
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
| LT | lava track | right track | left track | activate track |  |  |  |
| LT | lava track | left track | right track | activate track |  |  |  |
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
|  | bot1 |  | TODO |  |  |  | Needs verification |  |
|  | right1 |  | TODO |  |  |  | Needs verification |  |
|  | top1 |  | TODO |  |  |  | Needs verification |  |
|  | left1 |  | TODO |  |  |  | Needs verification |  |
|  | left2 |  | TODO |  |  |  | Needs verification |  |
|  | left4 |  | TODO |  |  |  | Needs verification |  |
|  | right3 |  | TODO |  |  |  | Needs verification |  |

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

#### Subrooms

- upper area
- lower area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | upper left | upper area | [The Marrow Lower Pogo (Bone_07)](#the-marrow-lower-pogo-bone07) | UR |  |  |  |  |
| LL | lower left | lower area | [The Marrow Lower Pogo (Bone_07)](#the-marrow-lower-pogo-bone07) | LR |  |  |  |  |
| UR | upper right | upper area | TODO |  |  |  |  | bellhart |
| MR | middle right | lower area | TODO |  |  |  |  | hunter's march |
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

## Weavenest Atla

### Weavenest Atla Entrance (Weave_04)

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

## Wormways

### Wormways Craggler Hallway (Crawl_04)

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
| BR | boss arena right | right area | boss arena | none | TODO | Needs verification | NEEDS VERIFICATION |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| gate switch | switch platform | none |  |  | Not included |  |
| lace 1 boss fight | boss arena | none |  |  | Included |  |

### Deep Docks Bellshrine (Bellshrine_05)

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Deep Docks Lace Intro (Bone_East_12)](#deep-docks-lace-intro-boneeast12) | R | none |  |  |  |
| R | right1 |  | [Far Fields Entrance (Bone_East_02)](#far-fields-entrance-boneeast02) | L | deep docks bellshrine activated |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| activate deep docks bellshrine switch |  | none |  |  | Not included |  |
| bench :) |  | deep docks bellshrine activated |  |  | Not included |  |

### Deep Docks Spire Lower (Bone_East_03)

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

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | top2 |  | [Hunter's March Deep Dock Passage (Ant_05b)](#hunters-march-deep-dock-passage-ant05b) | RF | none |  |  |  |
| UR | right2 |  | ["Deep Docks" March Side Room (Bone_East_04c)](#deep-docks-march-side-room-boneeast04c) | L | silk soar OR cling grip OR faydown cloak |  |  |  |
| LR | right1 |  | [Far Fields Deep Docks Loopback (Bone_East_15)](#far-fields-deep-docks-loopback-boneeast15) | L | none |  |  |  |
| L | left1 |  | [Is this still Deep Docks? (West) (Bone_East_04b)](#is-this-still-deep-docks-west-boneeast04b) | R | wall must be destroyed from the other side |  |  |  |
| F | bot1 |  | [Deep Docks Spire Lower (Bone_East_03)](#deep-docks-spire-lower-boneeast03) | C | floor must be destroyed from the other side |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Is this still Deep Docks? (West) (Bone_East_04b)

#### Subrooms

- side room
- ground
- upper level

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | ground | [Is this still Deep Docks? (East) (Bone_East_04)](#is-this-still-deep-docks-east-boneeast04) | L | attack blast rock, unblocks wall |  |  |  |
| C | top1 | upper level | [Hunter's March Deep Dock Passage (Ant_05b)](#hunters-march-deep-dock-passage-ant05b) | LF |  |  |  |  |
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

#### Subrooms

- left area
- right area
- gauntlet
- forge daughter
- right exit platform

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | right area | [Deep Docks Chains Flow West (Dock_02)](#deep-docks-chains-flow-west-dock02) | UL |  |  |  |  |
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

### Deep Docks Chains Flow West (Dock_02)

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

#### Notes

need to verify how this room works - thought it had some of the platforms go away, but not sure if that was in act 3

### Deep Docks Chains Flea Rescue (Dock_03d)

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
| UL | left1 | upper left hallway | [Deep Docks Chains Flow West (Dock_02)](#deep-docks-chains-flow-west-dock02) | UR | none |  |  |  |
| ML | left2 | middle left exit area | [Deep Docks Chains Flow West (Dock_02)](#deep-docks-chains-flow-west-dock02) | MR | none |  |  |  |
| LL | left3 | lower left area | [Deep Docks Chains Flow West (Dock_02)](#deep-docks-chains-flow-west-dock02) | LR | none |  |  |  |
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
| SP | open spool door | upper chains | spool fragment area | ??? | TODO | Needs verification | NEED SOMEONE BETTER THAN ME TO FIGURE OUT THE COMBINATIONS |
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

#### Subrooms

- right area
- boss area
- left area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | right area | [Deep Docks Chains Flow West (Dock_02)](#deep-docks-chains-flow-west-dock02) | LL | none |  |  |  |
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

### Deep Docks Lower East Shaft (Dock_15)

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

### Far Fields Entrance (Bone_East_02)

#### Subrooms

- deep docks platform
- main pathway

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | top1 | main pathway | [Far Fields Deep Docks Loopback (Bone_East_15)](#far-fields-deep-docks-loopback-boneeast15) | F | silk soar OR faydown cloak OR ( cling grip AND ( run OR dash OR drifter's cloak OR  OR sharpdart OR clawline ) ) |  |  | car barely make it up with faydown cloak |
| R | right1 | main pathway | TODO |  | none | TODO |  |  |
| L | left1 | deep docks platform | [Deep Docks Bellshrine (Bellshrine_05)](#deep-docks-bellshrine-bellshrine05) | R | deep docks bellshrine activated |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RJ | running jump | deep docks platform | main pathway | run OR dash OR drifter's cloak OR faydown cloak OR sharpdart OR clawline |  | Needs verification | couldn't get beast crest pogo to work, but might be possible |
| RJ | running jump | main pathway | deep docks platform | none |  |  |  |

#### Check Locations

No check locations defined.

### Far Fields Deep Docks Loopback (Bone_East_15)

#### Subrooms

- spike exit
- ground
- bell bench
- before gate

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | bell bench | [Is this still Deep Docks? (East) (Bone_East_04)](#is-this-still-deep-docks-east-boneeast04) | LR |  |  |  |  |
| F | bot1 | ground | [Far Fields Entrance (Bone_East_02)](#far-fields-entrance-boneeast02) | C |  |  |  |  |
| R | right1 | spike exit | TODO |  |  |  |  |  |

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

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Deep Docks Chains Upper East (Dock_03)](#deep-docks-chains-upper-east-dock03) | R |  |  |  |  |
| R | right1 |  | TODO |  |  |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| warding bell |  | none |  |  | Included |  |

### Weavenest Cindril Entrance (Bone_East_Weavehome)

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

### Hunter's March Deep Dock Passage (Ant_05b)

#### Subrooms

- before gate
- right of gauntlet
- gauntlet
- left of gauntlet

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | before gate | TODO |  |  |  | Needs verification |  |
| LF | bot1 | left of gauntlet | [Is this still Deep Docks? (West) (Bone_East_04b)](#is-this-still-deep-docks-west-boneeast04b) | C |  |  | Needs verification |  |
| RF | bot2 | right of gauntlet | [Is this still Deep Docks? (East) (Bone_East_04)](#is-this-still-deep-docks-east-boneeast04) | C |  |  | Needs verification |  |

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

## The Abyss

## Shellwood

## Bellhart

## Greymoor

## Verdania

## Blasted Steps

## Sinner's Road

## Underworks

## Bilewater

## Sands of Karak

## The Slab

## Mount Fay

## Putrified Ducts

## The Cradle

## Fast Travel

### Test room

#### Subrooms

- testing

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| ? | testing 2 |  | TODO |  | none |  |  |  |
| 1 | hello world |  | TODO |  | asdfa |  | Needs verification |  |
| T | testing 1 | testing | TODO |  | none |  | Verified |  |
| 2 | asdf |  | TODO |  | none |  | Needs verification |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| verified |  | none (falling) |  | Verified | Included |  |
| not verified |  |  |  | Needs verification | Included |  |
| unknown |  |  |  |  | Included |  |
| todo |  |  | TODO |  | Included |  |
| not todo |  |  |  |  | Included |  |
| apworld |  |  |  |  | Included |  |
| not apworld |  |  |  |  | Not included |  |

#### Notes

this is a **test** page

### Bellway Menu

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BB | bone bottom |  | [Bone Bottom Bellway (Bellway_01)](#bone-bottom-bellway-bellway01) | BB |  | TODO |  |  |
| TM | the marrow |  | TODO |  |  | TODO |  |  |
| DD | deep docks |  | [Deep Docks Bellway (Bellway_02)](#deep-docks-bellway-bellway02) | BB |  | TODO |  |  |
| FF | far fields |  | TODO |  |  | TODO |  |  |
| GM | greymoor |  | TODO |  |  | TODO |  |  |
| BH | bellhart |  | TODO |  |  | TODO |  |  |
| SW | shellwood |  | TODO |  |  | TODO |  |  |
| BS | blasted steps |  | TODO |  |  | TODO |  |  |
| TS | the slab |  | TODO |  |  | TODO |  |  |
| GB | grand bellway |  | TODO |  |  | TODO |  |  |
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
| FS | first shrine |  | TODO |  |  | TODO |  |  |
| CC | choral chambers |  | TODO |  |  | TODO |  |  |
| GB | grand bellway |  | TODO |  |  | TODO |  |  |
| UW | underworks |  | TODO |  |  | TODO |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

#### Notes

a virtual room to represent the ventrica fast travel menu
