# Silksong Randomizer Logic

Compiled from the database-generated room notes.

## Moss Grotto

### Moss Grotto Center (Tut_01)

**Game ID:** Tut_01

**Contributors:** herounit, super epicguy

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
| S1 | shaft 1 | upper crossing | up and away | silk soar OR ( cling grip AND ( easy skips OR faydown cloak OR run OR dash OR sharpdart OR clawline) OR (scuttlebrace AND dash) |  |  | Easy skip is a heal boost or a reverse dslash boost with Shaman's |
| S2 | shaft 2 | upper crossing | center shaft | none (falling) |  |  |  |
| S2 | shaft 2 | center shaft | upper crossing | silk soar OR cling grip OR (dash AND scuttlebrace) |  |  |  |
| SV | side room vines | center shaft | side room | break vines |  |  |  |
| SV | side room vines | side room | center shaft | break vines |  |  |  |
| S3 | shaft 3 | center shaft | lower crossing | none (falling) |  |  |  |
| S3 | shaft 3 | lower crossing | center shaft | silk soar OR cling grip OR (scuttlebrace AND dash AND (sharpdart OR clawline OR faydown cloak) AND easy skips) |  |  |  |
| S4 | shaft 4 | lower crossing | rock bottom | none (falling) |  |  |  |
| S4 | shaft 4 | rock bottom | lower crossing | silk soar OR ( cling grip AND faydown cloak ) OR (scuttlebrace AND dash AND faydown cloak AND ((drifters cloak AND ledge grab) OR clawline OR sharpdart) AND easy skips) |  |  |  |

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

**Contributors:** herounit

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

### Bone Bottom Town (Bonetown)

**Game ID:** Bonetown

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
| T1 | top1 | sky | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | B1 |  | TODO | Needs verification |  |
| T2 | top2 | sky | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | B2 |  | TODO | Needs verification |  |
| T3 | left ceiling | sky | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | B3 | silk soar |  |  |  |
| T4 | top4 | sky | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | B4 |  | TODO | Needs verification |  |
| T5 | top5 | sky | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | B5 |  | TODO | Needs verification | all part of the |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CC | climb chapel | ground level | chapel roof | silk soar OR ( cling grip AND ( LL door NOT opened OR faydown cloak ) ) OR (scuttlebrace AND dash AND faydown cloak) |  |  |  |
| SM | soar to middle platforms | ground level | upper middle platforms | silk soar |  |  |  |
| SS | soar to sky exit | ground level | sky | silk soar |  |  |  |
| SR | soar to right platforms | ground level | upper right platforms | silk soar |  |  |  |
| EV | elevator | ground level | upper right platforms | elevator switch flipped |  |  |  |
| CC | climb chapel | chapel roof | ground level | none |  |  |  |
| CR | climb roof | chapel roof | upper left platforms | silk soar OR cling grip OR (scuttlebrace AND dash AND (((faydown cloak OR shaman OR flea brew)) AND easy skips) OR (hard skips AND (hunter OR reaper OR wanderer OR beast OR architect) OR (silk storm OR rune rage)) |  |  | You need a very precise heal or spell boost to scuttlebrace the wall without wings, which can be done by anything but witch crest |
| CR | climb roof | upper left platforms | chapel roof | none |  |  |  |
| MD | middle platform drift | upper middle platforms | chapel roof | drifter's cloak OR clawline OR sharpdart OR beast OR architect OR (shaman AND (ledge grab AND easy skips) OR hard skips) OR ((hunter OR nude) AND dash) OR (dash AND (scuttlebrace OR flea brew OR silkspeed anklets OR faydown cloak)) OR (run AND flea brew AND easy skips) |  |  | Beast and architect can just spam pogo |
| SM | soar to middle platforms | upper middle platforms | ground level | none |  |  |  |
| CL | clawline across the sky | upper middle platforms | upper right platforms | clawline OR (dash AND (sharpdart OR drifter's cloak)) OR (run AND sharpdart OR (easy skips OR faydown cloak) AND drifters cloak) |  |  |  |
| CL | clawline across the sky | upper right platforms | upper middle platforms | clawline OR (dash AND (sharpdart OR drifter's cloak)) OR (run AND sharpdart OR (easy skips OR faydown cloak) AND drifters cloak) |  |  |  |
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

### Bonegrave (Bonegrave)

**Game ID:** Bonegrave

**Contributors:** herounit, super epicguy

#### Subrooms

- upper left exit
- upper right exit
- graveyard

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | upper right | upper right exit | [Bone Bottom Town (Bonetown)](#bone-bottom-town-bonetown) | UL | none |  |  |  |
| LR | lower right | graveyard | [Bone Bottom Town (Bonetown)](#bone-bottom-town-bonetown) | LL | none |  |  |  |
| C | ceiling | upper left exit | [Wormways Lower East (Crawl_07)](#wormways-lower-east-crawl07) | F | silk soar OR cling grip OR faydown cloak OR (dash AND scuttlebrace) |  |  |  |
| CD | chapel door | graveyard | [Chapel of the Wanderer (Chapel_Wanderer)](#chapel-of-the-wanderer-chapelwanderer) | CD | no wanderer's crest OR wanderer's door override |  |  | "wanderer's door override" is meant to cover any situation that would require the door to stay open, such as rosary cache rando |
| LL | lower left | graveyard | [Bonegrave Passage](#bonegrave-passage) | R | steel soul |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CL | climb | graveyard | upper right exit | cling grip OR silk soar OR (easy skips AND run AND faydown cloak AND ledge grab AND (drifters cloak OR clawline OR sharpdart)) OR (dash AND scuttlebrace) |  |  |  |
| CL | climb | upper right exit | graveyard | none (falling) |  |  |  |
| BW | breakable wall | upper left exit | upper right exit | none (break wall from this side) |  |  |  |
| BW | breakable wall | upper right exit | upper left exit | wall broken from other side |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| boneyard mossberry | graveyard | ledge grab OR clawline OR faydown cloak OR cling grip OR silk soar OR (upper right entrance AND dash OR sharpdart OR (easy skips AND any air stall better than heal)) |  |  | Included | can be gotten with only jump -tested edit: jump *and* ledge grab  air stalls include tool stalls and architect, hunter, and beast down slashes, but NOT low silk spell stalls or needle strikes |
| rosary cache bone bottom 6 | upper right exit | none |  |  | Included |  |
| rosary cache bone bottom 7 | upper right exit | none |  |  | Included |  |
| rosaries on grave | graveyard | none |  |  | Not included | NOT CURRENTLY RANDOMIZED |

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

### Mosshome Upper (Mosstown_02)

**Game ID:** Mosstown_02

**Contributors:** herounit, super epicguy

#### Subrooms

- main area
- bottom right area
- upper left area
- upper main area

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
| LS | left silk blockade | upper main area | upper left area | can break silk blockade |  |  |  |
| LS | left silk blockade | upper left area | upper main area | none (broken silk blockade) |  |  |  |
| RB | rope barrier | upper left area | main area | none (cut the rope) |  |  |  |
| RB | rope barrier | main area | upper left area | rope cut from other side AND (ledge grab OR height gain) |  |  |  |
| RP | right platforms | main area | upper main area | ledge grab OR any height gain OR easy skips |  |  |  |
| RP | right platforms | upper main area | main area | none |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| silkspear | main area | none |  |  | Included |  |
| frayed rosary string bone bottom silkspear passage | upper left area | none |  |  | Included |  |
| rosary cache mosshome 3 | main area | none |  |  | Included |  |
| rosary cache mosshome 4 | main area | none |  |  | Included |  |

#### Notes

known silk blockade breakers = silk spear, sharpdart, rune rage, weaver silkshot, pimpillo, and needle strikes from hunter, reaper, beast, and shaman

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

**Contributors:** herounit, super epicguy

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
| T1 | top1 | top area | [Blasted Steps Map Edge (Coral_19)](#blasted-steps-map-edge-coral19) | B1 | silk soar |  |  |  |
| T2 | top2 | top area | [Blasted Steps Map Edge (Coral_19)](#blasted-steps-map-edge-coral19) | B2 | silk soar |  |  |  |
| T3 | top3 | top area | [Blasted Steps Map Edge (Coral_19)](#blasted-steps-map-edge-coral19) | B3 | silk soar |  |  |  |
| T4 | top4 | top area | [Blasted Steps Map Edge (Coral_19)](#blasted-steps-map-edge-coral19) | B4 | silk soar |  |  |  |
| T5 | top5 | top area | [Blasted Steps Map Edge (Coral_19)](#blasted-steps-map-edge-coral19) | B5 | silk soar |  |  |  |
| T6 | top6 | top area | [Blasted Steps Map Edge (Coral_19)](#blasted-steps-map-edge-coral19) | B6 | silk soar |  |  |  |
| T7 | top7 | top area | [Blasted Steps Map Edge (Coral_19)](#blasted-steps-map-edge-coral19) | B7 | silk soar |  |  |  |
| UR | upper right | upper right ledge | [Shellwood Lower Toll bench (Shellwood_08c)](#shellwood-lower-toll-bench-shellwood08c) | L | none |  |  |  |
| MR | middle right | middle right ledge | [Mosshome Upper (Mosstown_02)](#mosshome-upper-mosstown02) | L | breakable wall -must be opened from the other side |  | Verified |  |
| LR | lower right | lower right area | [Mosshome Lower (Bone_11)](#mosshome-lower-bone11) | L | none |  |  |  |
| UL | upper left | upper left ledge | [Wormways Upper East (Crawl_01)](#wormways-upper-east-crawl01) | R | none |  |  |  |
| LL | lower left | lower left area | [Wormways Craggler Hallway (Crawl_04)](#wormways-craggler-hallway-crawl04) | R | none |  |  |  |
| B1 | bot1 | bottom area | [Bone Bottom Town (Bonetown)](#bone-bottom-town-bonetown) | T1 | none |  |  |  |
| B2 | right floor | lower right area | [Bone Bottom Town (Bonetown)](#bone-bottom-town-bonetown) | T2 | none |  |  |  |
| B3 | left floor | bottom area | [Bone Bottom Town (Bonetown)](#bone-bottom-town-bonetown) | T3 | none |  |  |  |
| B4 | bot4 | bottom area | [Bone Bottom Town (Bonetown)](#bone-bottom-town-bonetown) | T4 | none |  |  |  |
| B5 | bot5 | bottom area | [Bone Bottom Town (Bonetown)](#bone-bottom-town-bonetown) | T5 | none |  |  |  |

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
| one way break from moss |  |  |  |  | Included |  |

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
| volatile flintbeetle 1 | before gauntlet | none |  |  | Included | stable position |
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

- ceiling exit area
- upper maze left
- middle maze
- left alcove
- lower maze 1
- lower maze 2
- lower maze 3
- right alcove
- left lava track
- right lava track

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | left lava track | [The Marrow Lava Intro (Bone_02)](#the-marrow-lava-intro-bone02) | R | none |  | Verified |  |
| R | right | right lava track | [The Marrow Lava Docks (Bone_09)](#the-marrow-lava-docks-bone09) | L | none |  | Verified |  |
| C | ceiling | ceiling exit area | [The Marrow Skull Tyrant Arena (Bone_15)](#the-marrow-skull-tyrant-arena-bone15) | F | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LT | lava track | right lava track | left lava track | activate track OR ( clawline AND shaman crest ) |  | Verified |  |
| LT | lava track | left lava track | right lava track | activate track OR ( clawline AND shaman crest ) |  | Verified |  |
| AM | ascend to maze | right lava track | lower maze 2 | cling grip OR silk soar OR ( scuttle brace AND ( ledge grab OR faydown cloak OR clawline  ) ) |  | Verified |  |
| AM | ascend to maze | lower maze 2 | right lava track | none (falling) |  | Verified |  |
| RBW | right break wall | lower maze 2 | lower maze 3 | none (break wall right) |  | Verified |  |
| RBW | right break wall | lower maze 3 | lower maze 2 | none (break wall left) |  | Verified |  |
| AR | ascend right | lower maze 3 | right alcove | cling grip OR scuttlebrace OR ( faydown cloak AND ledge grab ) ) |  | Verified |  |
| AR | ascend right | right alcove | lower maze 3 | spike pogo OR cling grip OR faydown cloak OR dash OR drifter's cloak OR clawline OR sharpdart OR scuttlebrace |  | Verified |  |
| MMA | middle maze ascend | lower maze 1 | middle maze | cling grip OR scuttlebrace OR ( faydown cloak AND ( ledge grab OR clawline OR shaman's crest ) ) |  | Verified |  |
| MMA | middle maze ascend | middle maze | lower maze 1 | none (falling) |  | Verified |  |
| LA | left alcove access | middle maze | left alcove | none (break wall left) |  | Verified |  |
| LA | left alcove access | left alcove | middle maze | cling grip OR scuttlebrace OR ( ledge grab AND faydown cloak ) |  | Verified |  |
| SP | spike pogo | lower maze 1 | lower maze 2 | ledge grab OR spike pogo OR run OR dash OR drifter's cloak OR faydown cloak OR clawline OR scuttlebrace OR sharpdart |  | Verified | roof makes it so ledge grab works from left to right  but not the other way |
| SP | spike pogo | lower maze 2 | lower maze 1 | spike pogo OR run OR dash OR drifter's cloak OR faydown cloak OR clawline OR scuttlebrace OR sharpdart |  | Verified | possible other stalls might work - lip on ceiling seems to make it impassable with walking jump? |
| UBW | upper break wall | upper maze left | ceiling exit area | none (break wall right) |  | Verified |  |
| UBW | upper break wall | ceiling exit area | upper maze left | none (break wall left) |  | Verified |  |
| UA | upper ascend | middle maze | upper maze left | silk soar OR cling grip OR scuttlebrace OR ( faydown cloak AND ledge grab ) ) |  | Verified |  |
| UA | upper ascend | upper maze left | middle maze | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| activate track | right lava track | none |  | Verified | Not included |  |
| rosary cache the marrow 11 | left alcove | none |  | Verified | Included |  |
| rosary cache the marrow 12 | left alcove | none |  | Verified | Included |  |
| rosary cache the marrow 13 | right alcove | none |  | Verified | Included |  |

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
| volatile flintbeetle 2 | main area | none | TODO |  | Included | this one swaps position based on when [GAME STATE] - wiki says when the shortcut after bellshrine is opened |

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
| BB | bellway | boss room | [Bellway Menu](#bellway-menu) | TM | defeat bell beast |  |  |  |

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
| volatile flintbeetle 2 |  | none |  |  | Included | this one swaps position based on when [GAME STATE] - wiki says when the shortcut after bellshrine is opened |

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
| LR | lower right |  | [The Marrow Jail Pathway (Bone_08)](#the-marrow-jail-pathway-bone08) | LL | none |  |  |  |
| C | ceiling |  | [The Marrow Upper Pogo (Bone_19)](#the-marrow-upper-pogo-bone19) | F | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| craft metal |  | none |  |  | Included |  |
| shell shard cache the marrow 4 |  | none |  |  | Included | MARKED AS ??? ON TRACKER |
| volatile flintbeetle 3 |  | none |  |  | Included | this one has a stable position |

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

#### Subrooms

- upper area
- lower area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | upper left | upper area | [The Marrow Lower Pogo (Bone_07)](#the-marrow-lower-pogo-bone07) | UR |  |  |  |  |
| LL | lower left | lower area | [The Marrow Lower Pogo (Bone_07)](#the-marrow-lower-pogo-bone07) | LR |  |  |  |  |
| UR | upper right | upper area | [Bellhart Lower (Belltown_basement_03)](#bellhart-lower-belltownbasement03) | L |  | TODO |  | bellhart |
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
| UL | left2 | gauntlet left | [The Marrow Lava Docks (Bone_09)](#the-marrow-lava-docks-bone09) | UR | none |  | Needs verification |  |
| LL | left1 | main pathway | [The Marrow Lava Docks (Bone_09)](#the-marrow-lava-docks-bone09) | LR | none |  | Needs verification |  |
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
| R | right1 |  | [Deep Docks Bellway (Bellway_02)](#deep-docks-bellway-bellway02) | L | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| flea rescue |  | ledge grab OR faydown cloak OR clawline OR silk soar |  | Verified | Included |  |

#### Notes

ledge grab is the only real requirement in this room

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
| C | top1 | left area | [Deep Docks Lace Intro (Bone_East_12)](#deep-docks-lace-intro-boneeast12) | F | none |  | Verified | activate airlock |
| L | left1 | left area | [Deep Docks Lower West Shaft (Dock_04)](#deep-docks-lower-west-shaft-dock04) | UR | none |  | Verified |  |
| R | right1 | right exit platform | [Deep Docks Chains West (Dock_02)](#deep-docks-chains-west-dock02) | UL | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| DS | door switch | left area | right area | gate switch activated |  | Verified |  |
| DS | door switch | right area | left area | none (switch on this side) |  | Verified |  |
| GL | gauntlet left | left area | gauntlet | none |  | Verified |  |
| GL | gauntlet left | gauntlet | left area | gauntlet defeated |  | Verified |  |
| GR | gauntlet right | right area | gauntlet | none |  | Verified |  |
| GR | gauntlet right | gauntlet | right area | gauntlet defeated |  | Verified |  |
| GC | gauntlet upper | forge daughter | gauntlet | open airlock down |  | Verified |  |
| GC | gauntlet upper | gauntlet | forge daughter | gauntlet defeated AND ( open airlock up AND ( ledge grab OR faydown cloak OR clawline OR scuttlebrace OR shamans crest ) ) |  | Verified |  |
| RJ | running jump | right area | right exit platform | run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart OR beast crest |  | Verified |  |
| RJ | running jump | right exit platform | right area | run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart OR beast crest |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| shell shard cache deep docks 10 | left area | none |  | Verified | Included | break wall |
| shard bundle deep docks 2 | left area | none |  | Verified | Included |  |
| silkshot (forge daughter) | forge daughter | broken tool |  | Verified | Included | forge daughter shop |
| sting shard | forge daughter | none |  | Verified | Included | forge daughter shop |
| magma bell | forge daughter | none |  | Verified | Included | forge daughter shop |
| crafting kit forge daughter | forge daughter | none |  | Verified | Included | forge daughter shop |
| readable lore tablet | left area | open airlock left |  | Verified | Included |  |
| gate switch | forge daughter | none |  | Verified | Not included |  |

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
| UL | left1 | main area | [Deep Docks Forge (Room_Forge)](#deep-docks-forge-roomforge) | R | none |  |  |  |
| LL | left2 | lower left exit | [Deep Docks Forebrothers (Dock_09)](#deep-docks-forebrothers-dock09) | R | none |  |  |  |
| UR | right1 | main area | [Deep Docks Chains Center (Dock_02b)](#deep-docks-chains-center-dock02b) | UL | none |  |  |  |
| MR | right2 | middle crossing | [Deep Docks Chains Center (Dock_02b)](#deep-docks-chains-center-dock02b) | ML | none |  |  |  |
| LR | right3 | middle crossing | [Deep Docks Chains Center (Dock_02b)](#deep-docks-chains-center-dock02b) | LL | none |  |  |  |

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

### Bone_East_11 (Bone_East_11)

**Game ID:** Bone_East_11

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | top1 |  | TODO |  |  |  |  |  |
| LR | right2 |  | [Far Fields Pilgrim's Rest (Bone_East_10)](#far-fields-pilgrims-rest-boneeast10) | UL |  |  |  |  |
| F | bot1 |  | [Far Fields Wind Shaft (Bone_East_07)](#far-fields-wind-shaft-boneeast07) | C |  |  |  |  |
| UR | right1 |  | TODO |  |  |  |  |  |
| L | left1 |  | [Hunter's March Deep Entrance (Ant_09)](#hunters-march-deep-entrance-ant09) | R |  |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Bone_East_14 (Bone_East_14)

**Game ID:** Bone_East_14

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | right1 |  | [Far Fields East Skull Room (Bone_East_14b)](#far-fields-east-skull-room-boneeast14b) | UL |  |  |  |  |
| LR | right2 |  | [Far Fields East Skull Room (Bone_East_14b)](#far-fields-east-skull-room-boneeast14b) | LL |  |  |  |  |
| LL | left2 |  | [Far Fields Pinstress Room (Bone_East_09)](#far-fields-pinstress-room-boneeast09) | LR |  |  |  |  |
| UL | left1 |  | [Far Fields Pinstress Room (Bone_East_09)](#far-fields-pinstress-room-boneeast09) | UR |  |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Collectable Item Pickup |  |  |  |  | Included |  |

### Far Fields East Skull Room (Bone_East_14b)

**Game ID:** Bone_East_14b

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LL | left2 |  | [Bone_East_14 (Bone_East_14)](#boneeast14-boneeast14) | LR |  |  |  |  |
| UL | left1 |  | [Bone_East_14 (Bone_East_14)](#boneeast14-boneeast14) | UR |  |  |  |  |
| D | door1 |  | [Far Fields Lava Challenge (Bone_East_LavaChallenge)](#far-fields-lava-challenge-boneeastlavachallenge) | L |  |  |  |  |
| R | right1 |  | [Weavenest Cindril Entrance (Bone_East_Weavehome)](#weavenest-cindril-entrance-boneeastweavehome) | L |  |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Far Fields Entrance East (Bone_East_02)

**Game ID:** Bone_East_02

**Contributors:** herounit

#### Subrooms

- deep docks platform
- main pathway
- ceiling exit platform

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | top1 | main pathway | [Far Fields Deep Docks Loopback (Bone_East_15)](#far-fields-deep-docks-loopback-boneeast15) | F | silk soar OR faydown cloak OR cling grip |  | Verified | car barely make it up with faydown cloak |
| L | left1 | deep docks platform | [Deep Docks Bellshrine (Bellshrine_05)](#deep-docks-bellshrine-bellshrine05) | R | deep docks bellshrine activated |  | Verified |  |
| R | right1 | main pathway | [Far Fields Entrance West (Bone_East_02b)](#far-fields-entrance-west-boneeast02b) | L | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RJ | running jump | deep docks platform | main pathway | run OR faydown cloak OR sharpdart  OR clawline OR ( ledge grab AND ( dash OR drifter's cloak ) ) |  | Verified | couldn't get beast crest pogo to work, but might be possible |
| RJ | running jump | main pathway | deep docks platform | none |  | Verified |  |
| V1 | vertical 1 | main pathway | ceiling exit platform | silk soar OR faydown cloak OR clawline OR ( ledge grab AND ( run OR dash OR drifter's cloak  OR sharpdart ) ) |  | Verified |  |
| V1 | vertical 1 | ceiling exit platform | main pathway | none (falling) |  | Verified |  |

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
- check alcove

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | right1 | upper right platforms | [Far Fields Wind Shaft (Bone_East_07)](#far-fields-wind-shaft-boneeast07) | L1 | none |  | Verified |  |
| LR | right2 | lower right exit platform | [Far Fields Wind Shaft (Bone_East_07)](#far-fields-wind-shaft-boneeast07) | L2 | none |  | Verified |  |
| L | left1 | lower walkway | [Far Fields Entrance East (Bone_East_02)](#far-fields-entrance-east-boneeast02) | R | none |  | Verified |  |
| C | top3 | upper right platforms | [Far Fields Fort Lower Passage (Bone_East_16)](#far-fields-fort-lower-passage-boneeast16) | F | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | vertical 1 | lower walkway | upper right platforms | run OR clawline OR ( ledge grab AND ( dash OR sharpdart OR silk soar OR drifter's cloak OR faydown cloak |  | Verified |  |
| V1 | vertical 1 | upper right platforms | lower walkway | none (falling) |  | Verified |  |
| LC | lava crossing | lower walkway | lower right exit platform | run OR dash OR clawline OR sharpdart OR cling grip OR silk soar OR drifter's cloak  OR faydown cloak |  | Verified |  |
| LC | lava crossing | lower right exit platform | lower walkway | run OR dash OR clawline OR sharpdart OR cling grip OR silk soar OR drifter's cloak  OR faydown cloak |  | Verified |  |
| V2 | vertical 2 | lower walkway | upper left platforms | silk soar |  | Verified |  |
| V2 | vertical 2 | upper left platforms | lower walkway | none (falling) |  | Verified |  |
| UC | upper crossing | upper right platforms | upper left platforms | run OR dash OR clawline OR sharpdart OR silk soar OR drifter's cloak OR faydown cloak |  | Verified |  |
| UC | upper crossing | upper left platforms | upper right platforms | run OR dash OR clawline OR sharpdart OR silk soar OR drifter's cloak OR faydown cloak |  | Verified |  |
| V3 | vertical 3 | lower right exit platform | upper right platforms | cling grip OR silk soar |  | Verified |  |
| V3 | vertical 3 | upper right platforms | lower right exit platform | none (falling) |  | Verified |  |
| AC | alcove access | lower walkway | check alcove | ledge grab OR silk soar OR faydown cloak OR clawline OR shaman's crest |  | Verified | i love shamans pogo |
| AC | alcove access | check alcove | lower walkway | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| shell shard cache far fields 1 | check alcove | none |  | Verified | Included |  |

### Far Fields Fort Lower Passage (Bone_East_16)

**Game ID:** Bone_East_16

**Contributors:** herounit

#### Subrooms

- the pit of despair
- the highest highs

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | bot1 | the pit of despair | [Far Fields Entrance West (Bone_East_02b)](#far-fields-entrance-west-boneeast02b) | C | none |  | Verified |  |
| R | right1 | the highest highs | [Far Fields Fort Flea Rescue (Bone_East_17b)](#far-fields-fort-flea-rescue-boneeast17b) | L | none (break wall) |  | Verified | can be broken from either side |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| MJ | massive jump | the pit of despair | the highest highs | ledge grab OR clawline OR shaman's crest OR faydown cloak OR silk soar OR scuttlebrace OR cling grip |  | Verified |  |
| MJ | massive jump | the highest highs | the pit of despair | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary cache far fields 11 | the highest highs | none |  | Verified | Included |  |
| rosary cache far fields 12 | the highest highs | none |  | Verified | Included |  |
| rosary cache far fields 13 | the highest highs | none |  | Verified | Included |  |

### Far Fields Fort Flea Rescue (Bone_East_17b)

**Game ID:** Bone_East_17b

**Contributors:** herounit

#### Subrooms

- left exit area
- ceiling exit area
- flea rescue area
- camp

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | left exit area | [Far Fields Fort Lower Passage (Bone_East_16)](#far-fields-fort-lower-passage-boneeast16) | R | none |  | Verified | break wall |
| C | top1 | ceiling exit area | [Far Fields Fort Upper Passage (Bone_East_17)](#far-fields-fort-upper-passage-boneeast17) | B | none |  | Verified | break wall (can be broken from either side) |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| S1 | shaft 1 | left exit area | flea rescue area | ledge grab OR faydown cloak OR silk soar OR clawline |  | Verified |  |
| S1 | shaft 1 | flea rescue area | left exit area | none (falling) |  | Verified |  |
| S2 | shaft 2 | left exit area | camp | ledge grab OR faydown cloak OR silk soar OR clawline |  | Verified |  |
| S2 | shaft 2 | camp | left exit area | none (falling) |  | Verified |  |
| FA | flea ascend | flea rescue area | ceiling exit area | ledge grab OR faydown cloak OR silk soar OR clawline |  | Verified |  |
| FA | flea ascend | ceiling exit area | flea rescue area | none (falling) |  | Verified |  |
| CA | camp ascend | camp | ceiling exit area | ledge grab OR faydown cloak OR silk soar OR clawline OR cling grip |  | Verified |  |
| CA | camp ascend | ceiling exit area | camp | none (falling) |  | Verified |  |
| MC | middling crossing | camp | flea rescue area | ledge grab OR run OR dash OR sharpdart OR drifter's cloak OR faydown cloak OR cling grip OR silk soar OR scuttlebrace |  | Verified |  |
| MC | middling crossing | flea rescue area | camp | ledge grab OR run OR sharpdart OR clawline OR faydown cloak OR cling grip OR silk soar OR scuttlebrace |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| flea rescue | flea rescue area | none |  | Verified | Included | break cage |
| rosary cache far fields 16 | camp | none |  | Verified | Included |  |
| rosary cache far fields 17 | camp | none |  | Verified | Included |  |

#### Notes

this had no subrooms before ledge grab...

### Far Fields Fort Upper Passage (Bone_East_17)

**Game ID:** Bone_East_17

**Contributors:** herounit

#### Subrooms

- left exit area
- right exit area
- main area
- check niche

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | left exit area | [Far Fields Deep Docks Loopback (Bone_East_15)](#far-fields-deep-docks-loopback-boneeast15) | R | platforms lowered from above |  | Verified |  |
| B | bot1 | main area | [Far Fields Fort Flea Rescue (Bone_East_17b)](#far-fields-fort-flea-rescue-boneeast17b) | C | none |  | Verified |  |
| R | right1 | right exit area | [Far Fields Wind Shaft (Bone_East_07)](#far-fields-wind-shaft-boneeast07) | L4 | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LP | lower platforms | left exit area | main area | none (switch is on this side) |  | Verified |  |
| LP | lower platforms | main area | left exit area | platform switch flipped |  | Verified |  |
| RJ | running jump | main area | right exit area | run OR dash OR drifter's cloak OR faydown cloak OR clawline OR sharpdart |  | Verified | silk soar doesn't get enough horizontal distance without one of the skills that just gets you there |
| RJ | running jump | right exit area | main area | none (falling) |  | Verified |  |
| AC | access niche | main area | check niche | ledge grab OR run OR dash OR silk soar OR beast crest OR shaman crest OR drifter's cloak OR faydown cloak OR cling grip OR clawline OR sharpdart OR scuttlebrace |  | Verified |  |
| AC | access niche | check niche | main area | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary cache far fields 14 | check niche | none |  | Verified | Included |  |
| rosary cache far fields 15 | main area | none |  | Verified | Included |  |
| lower platform switch | left exit area | none |  | Verified | Included |  |
| rosary chest | left exit area | none |  | Verified | Not included | NOT YET RANDOMIZED |

### Far Fields Wind Shaft (Bone_East_07)

**Game ID:** Bone_East_07

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | top1 |  | [Bone_East_11 (Bone_East_11)](#boneeast11-boneeast11) | F |  |  |  |  |
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
| UL | left1 | upper left exit | [Bone_East_11 (Bone_East_11)](#boneeast11-boneeast11) | LR | none |  | Verified |  |
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
| LR | right2 |  | [Bone_East_14 (Bone_East_14)](#boneeast14-boneeast14) | LL |  |  |  |  |
| LL | left2 |  | [Far Fields Chorus (Bone_East_08)](#far-fields-chorus-boneeast08) | R |  |  |  |  |
| UR | right1 |  | [Bone_East_14 (Bone_East_14)](#boneeast14-boneeast14) | UL |  |  |  |  |
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

### Far Fields Lava Challenge (Bone_East_LavaChallenge)

**Game ID:** Bone_East_LavaChallenge

**Contributors:** herounit

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Far Fields East Skull Room (Bone_East_14b)](#far-fields-east-skull-room-boneeast14b) | D |  |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| shell shard cache far fields 8 |  |  | TODO |  | Included |  |
| mask shard far fields skull cave |  |  | TODO |  | Included |  |

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
| L | left1 | bell bench | [Is this still Deep Docks? (East) (Bone_East_04)](#is-this-still-deep-docks-east-boneeast04) | LR | none |  | Verified |  |
| F | bot1 | ground | [Far Fields Entrance East (Bone_East_02)](#far-fields-entrance-east-boneeast02) | C | none |  | Verified |  |
| R | right1 | spike exit | [Far Fields Fort Upper Passage (Bone_East_17)](#far-fields-fort-upper-passage-boneeast17) | L | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SF | spike float | ground | spike exit | ( cling grip AND drifter's cloak ) OR ( silk soar AND drifter's cloak ) |  | Verified | exit silk soar early and land on platform |
| SF | spike float | spike exit | ground | none (falling) |  | Verified | can barely ledge grab by falling to jump down |
| BG | bell bench gate | before gate | bell bench | none (switch is on this side) |  | Verified |  |
| BG | bell bench gate | bell bench | before gate | gate switch flipped |  | Verified |  |
| CG | cling grip | ground | before gate | cling grip OR silk soar OR scuttlebrace |  | Verified |  |
| CG | cling grip | before gate | ground | none (falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary cache far fields 9 | ground | none |  | Verified | Included | MARKED AS ??? ON TRACKER |
| rosary cache far fields 10 | ground | none |  | Verified | Included | MARKED AS ??? ON TRACKER |
| gate switch | before gate | none |  | Verified | Not included |  |
| bench pay lock | bell bench | none |  | Verified | Not included |  |
| bench :) | bell bench | unlock bench lock |  | Verified | Not included |  |

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
| L | left1 | entrance | [Far Fields East Skull Room (Bone_East_14b)](#far-fields-east-skull-room-boneeast14b) | R | needolin |  |  |  |

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
| R | right1 |  | [Bone_East_11 (Bone_East_11)](#boneeast11-boneeast11) | L |  |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

## Shellwood

### Cling Grip Room (Shellwood_10)

**Game ID:** Shellwood_10

**Contributors:** Pyxl

#### Subrooms

- Ground Level
- Central Level
- Upper Level

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | right1 | Upper Level | [Shellwood Top Room (Shellwood_26)](#shellwood-top-room-shellwood26) | L | Cling Grip Or Silk Soar OR ( Dash AND Scuttlebrace ) |  |  |  |
| LR | right2 | Ground Level | [Shellwood Flower Pogo Upper Hall (Shellwood_20)](#shellwood-flower-pogo-upper-hall-shellwood20) | L | ( Dash AND Scuttlebrace ) OR Cling Grip OR Clawline OR Faydown Cloak OR Ledge Grab |  |  |  |
| ML | left2 | Central Level | [Cling grip Side room (Shellwood_11)](#cling-grip-side-room-shellwood11) | LR | Dash OR Sprint OR Clawline OR Sharp Dart OR Beast Crest OR Faydown Cloak OR Drifters Cloak |  |  |  |
| UL | left1 | Upper Level | [Cling grip Side room (Shellwood_11)](#cling-grip-side-room-shellwood11) | UR | None |  |  |  |
| MR | right3 | Central Level | [Sister Splinter (Shellwood_18)](#sister-splinter-shellwood18) | L | ( Dash AND Scuttlebrace ) OR Cling Grip OR Clawline OR Faydown Cloak OR Ledge Grab |  |  |  |
| LL | left3 | Ground Level | [Shellwood Lower Left Tall Room (Shellwood_03)](#shellwood-lower-left-tall-room-shellwood03) | UR | None |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| EP |  | Ground Level | Central Level | ( Dash AND Scuttlebrace ) OR Cling Grip OR (( Faydown Cloak OR Easy skips ) AND ( Clawline OR  Sharpdart OR  Faydown Cloak ) ) OR Silk Soar |  |  |  |
|  |  | Central Level | Ground Level | None |  |  |  |
|  |  | Central Level | Upper Level | Silk Soar OR ( Easy skips AND Cling Grip AND Faydown Cloak ) |  |  |  |
|  |  | Upper Level | Central Level | None |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Cling Grip | Upper Level | None |  |  | Included |  |
| Pollip Heart #5 | Central Level | None |  |  | Included |  |

### Cling grip Side room (Shellwood_11)

**Game ID:** Shellwood_11

**Contributors:** Pyxl

#### Subrooms

- Upper Level
- Lower Level

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LR | right2 | Lower Level | [Cling Grip Room (Shellwood_10)](#cling-grip-room-shellwood10) | ML | None |  |  |  |
| UR | right1 | Upper Level | [Cling Grip Room (Shellwood_10)](#cling-grip-room-shellwood10) | UL | None |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| FP | Flower Pogos | Lower Level | Upper Level | ( Easy skips AND Swim ) OR Dash OR Sprint OR Sharp Dart OR Beast Crest OR Faydown Cloak OR Drifters Cloak OR Clawline OR ( Dash AND Scuttlebrace ) OR Cling Grip OR Silk Soar |  |  |  |
| FP | Flower Pogos | Upper Level | Lower Level | None |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Rosaries | Upper Level | None | TODO |  | Not included | Not included rn |

### Greyroot (Room_Witch)

**Game ID:** Room_Witch

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Shellwood Greyroot entrance (Shellwood_Witch)](#shellwood-greyroot-entrance-shellwoodwitch) | D | None |  |  |  |
| QR | Quest Rebirth |  | [Witch Chapel (Shellwood_25b)](#witch-chapel-shellwood25b) | QR | Rite of the pollip Completed AND owns twisted bud |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Pollip Pouch |  | 6 Pollip Hearts |  |  | Included |  |

### Greyroots Basement Tall room (Mosstown_03)

**Game ID:** Mosstown_03

**Contributors:** Pyxl

#### Subrooms

- Top
- Bottom

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | right2 | Top | [Shellwood Diddy Basement Main (Shellwood_25)](#shellwood-diddy-basement-main-shellwood25) | L | None |  |  |  |
| LR | right1 | Bottom | [The Marrow Skull Wall (Bone_06)](#the-marrow-skull-wall-bone06) | L | None |  |  |  |
| C | top1 | Top | [Shellwood Lower Left Tall Room (Shellwood_03)](#shellwood-lower-left-tall-room-shellwood03) | F | Cling Grip |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SH | Shaft | Top | Bottom | None |  |  |  |
| SH | Shaft | Bottom | Top | Silksoar OR Cling grip |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Shell Shard Cache: Shellwood #12 | Top | None |  |  | Included |  |
| Bench | Bottom | Cling Grip OR ( Dash AND Scuttlebrace ) |  |  | Included |  |

### Long Pin (Belltown_Room_shellwood)

**Game ID:** Belltown_Room_shellwood

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Shellwood Right Side Big room (Shellwood_01)](#shellwood-right-side-big-room-shellwood01) | UR |  |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Long pin |  | None |  |  | Included |  |

### Shellgrave (Shellgrave)

**Game ID:** Shellgrave

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | bot1 |  | [Shellwood Left side Long pond room (Shellwood_04b)](#shellwood-left-side-long-pond-room-shellwood04b) | RC | None |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Rosary Cache |  | None |  |  | Not included |  |

### Shellwood Bellshrine (Bellshrine_03)

**Game ID:** Bellshrine_03

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Shellwood Connection To Blasted steps (Shellwood_08)](#shellwood-connection-to-blasted-steps-shellwood08) | R | None |  |  |  |
| R | right1 |  | [Shellwood Bellway  (Shellwood_19)](#shellwood-bellway) | L | Bell: Shellwood AND Bellsrhine Active |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Bell: Shellwood |  | None |  |  | Included |  |

### Shellwood Bellway
 (Shellwood_19)

**Game ID:** Shellwood_19

**Contributors:** Pyxl

#### Subrooms

- Left Puddle
- Right Puddle

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Right Puddle | [Shellwood Lower Left Tall Room (Shellwood_03)](#shellwood-lower-left-tall-room-shellwood03) | UL | None |  |  |  |
| L | left1 | Left Puddle | [Shellwood Bellshrine (Bellshrine_03)](#shellwood-bellshrine-bellshrine03) | R | Bell: shellwood owned | TODO | Needs verification | Might also need switch from other side, needs testing |
| BB | door_fastTravelExit | Right Puddle | [Bellway Menu](#bellway-menu) | SW | Bell beast Access |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| PU | Puddle | Left Puddle | Right Puddle | Swim Or Dash OR Sprint OR Clawline OR Sharpdart OR Beast Crest OR Drifters Cloak OR Faydown Cloak |  |  |  |
| PU | Puddle | Right Puddle | Left Puddle | Swim Or Dash OR Sprint OR Clawline OR Sharpdart OR Beast Crest OR Drifters Cloak OR Faydown Cloak |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Bellway: Shellwood | Right Puddle | None |  |  | Included |  |

### Shellwood Big Room Left (Shellwood_02)

**Game ID:** Shellwood_02

**Contributors:** Pyxl

#### Subrooms

- Ceiling area
- Ground Left
- Platforms
- Ground Centre
- Ground Right

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | right1 | Ceiling area | [Shellwood Sister Splinter Bench (Shellwood_01b)](#shellwood-sister-splinter-bench-shellwood01b) | LL |  |  |  |  |
| LL | left2 | Ground Left | [shellwood Shakra (Shellwood_16)](#shellwood-shakra-shellwood16) | R |  |  |  |  |
| UL | left3 | Platforms | [Shellwood Greyroot entrance (Shellwood_Witch)](#shellwood-greyroot-entrance-shellwoodwitch) | R |  |  |  |  |
| LR | right2 | Ground Right | [Shellwood Right Side Big room (Shellwood_01)](#shellwood-right-side-big-room-shellwood01) | LL |  |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| EL | Elevator | Ground Centre | Ceiling area | Activated from Ceiling area |  |  |  |
| EL | Elevator | Ceiling area | Ground Centre | Activated from Ceiling area |  |  |  |
| RL | Right Lake | Ground Centre | Ground Right | ( Enemy Pogo AND Ledge Grab ) OR Dash OR Sprint OR clawline OR Beast Crest OR Faydown Cloak OR Drifters Cloak OR ( Swim AND Ledge Grab ) |  |  |  |
| RL | Right Lake | Ground Right | Ground Centre | ( Enemy Pogo AND Ledge Grab ) OR Dash OR Sprint OR clawline OR Beast Crest OR Faydown Cloak OR Drifters Cloak OR ( Swim AND Ledge Grab ) |  |  |  |
| LL | Left Lake | Ground Centre | Ground Left | ( Enemy Pogo AND Ledge Grab ) OR Dash OR Sprint OR clawline OR Beast Crest OR Faydown Cloak OR Drifters Cloak |  |  |  |
| LL | Left Lake | Ground Left | Ground Centre | None |  |  |  |
| LP | Left Platforms | Platforms | Ground Left | None |  |  |  |
| LP | Left Platforms | Ground Left | Platforms | ( Faydown Cloak AND ( Cling Grip OR ( Scuttle Brace AND Dash ) ) ) Silk Soar OR Enemy Pogo |  |  |  |
| CP | Central Platforms | Platforms | Ground Centre | None |  |  |  |
| CP | Central Platforms | Ground Centre | Platforms | ( Faydown Cloak AND Ledge Grab ) OR Silk Soar |  |  |  |
| RP | Right Platforms | Platforms | Ground Right | None |  |  |  |
| RP | Right Platforms | Ground Right | Platforms | Silk Soar |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Pollip Heart #6 | Platforms | Ledge Grab OR Silk Soar OR Faydown Cloak |  |  | Included |  |

### Shellwood Connection To Blasted steps (Shellwood_08)

**Game ID:** Shellwood_08

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Shellwood Bellshrine (Bellshrine_03)](#shellwood-bellshrine-bellshrine03) | L | None |  |  |  |
| L | left1 |  | [Blasted Steps Map Edge (Coral_19)](#blasted-steps-map-edge-coral19) | R | None |  |  |  |
| F | bot1 |  | [shellwood Far Left Tall Room (Shellwood_04c)](#shellwood-far-left-tall-room-shellwood04c) | C | None |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Shellwood Diddy Basement Main (Shellwood_25)

**Game ID:** Shellwood_25

**Contributors:** Pyxl

#### Subrooms

- Left Corridor
- Left Puddles
- Right Puddles
- Right Corridor

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Left Corridor | [Greyroots Basement Tall room (Mosstown_03)](#greyroots-basement-tall-room-mosstown03) | UR | None |  |  |  |
| D | door1 | Right Corridor | [Witch Chapel (Shellwood_25b)](#witch-chapel-shellwood25b) | L | Not accesible from this side |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LW | Left Wall | Left Corridor | Left Puddles | Cling Grip OR Silk soar OR Faydown Cloak OR ( Dash AND Scuttlebrace ) |  |  |  |
| LW | Left Wall | Left Puddles | Left Corridor | None |  |  |  |
| PU | Puddles | Left Puddles | Right Puddles | Swim OR Clawline OR Sharpdart OR Drifters Cloak OR Easy skips |  |  |  |
| PU | Puddles | Right Puddles | Left Puddles | Swim OR Clawline OR Sharpdart OR Drifters Cloak OR Easy skips |  |  |  |
| RW | Right Wall | Right Puddles | Right Corridor | Cling Grip OR Silk soar OR Faydown Cloak OR ( Dash AND Scuttlebrace ) |  |  |  |
| RW | Right Wall | Right Corridor | Right Puddles | None |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Rosary String: Shellwood #2 | Left Puddles | Cling Grip OR Silk Soar OR ( Faydown Cloak AND Shaman Crest ) OR ( Dash AND Scuttlebrace ) |  |  | Included |  |
| Relic: Weaver effigy (Keelal, Shellwood) | Right Corridor | Cling Grip AND Swim AND ( Clawline OR Faydown Cloak OR Drifters Cloak OR Sharpdart OR Beast Crest OR Sprint OR Dash ) |  |  | Included |  |

### Shellwood Flower Pogo Upper Hall (Shellwood_20)

**Game ID:** Shellwood_20

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Shellwood Sister Splinter Bench (Shellwood_01b)](#shellwood-sister-splinter-bench-shellwood01b) | UL | None |  |  |  |
| L | left1 |  | [Cling Grip Room (Shellwood_10)](#cling-grip-room-shellwood10) | LR | None |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Pollip Heart #3 |  | None |  |  | Included |  |

### Shellwood Greyroot entrance (Shellwood_Witch)

**Game ID:** Shellwood_Witch

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| D | door1 |  | [Greyroot (Room_Witch)](#greyroot-roomwitch) | L | None |  |  |  |
| R | right1 |  | [Shellwood Big Room Left (Shellwood_02)](#shellwood-big-room-left-shellwood02) | UL | None |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Shellwood Hidden Bellhart Connection (Shellwood_15)

**Game ID:** Shellwood_15

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Shellwood Sister Splinter Bench (Shellwood_01b)](#shellwood-sister-splinter-bench-shellwood01b) | MR | Faydown Cloak OR ( Drifters Cloak AND Ledge Grab ) OR ( Dash AND Ledge Grab )  OR Clawline OR Sharpdart OR Beast Crest |  |  |  |
| R | right1 |  | [Upper Bellhart (Belltown_04)](#upper-bellhart-belltown04) | LL | Faydown Cloak OR Drifters Cloak OR Dash OR Clawline OR Sharpdart OR Beast Crest |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Pollip Heart #2 |  | Faydown Cloak OR Drifters Cloak OR Dash OR Clawline OR Sharpdart OR Beast Crest |  |  | Included |  |

### Shellwood Left side Long pond room (Shellwood_04b)

**Game ID:** Shellwood_04b

**Contributors:** Pyxl

#### Subrooms

- Right Lake
- Left Lake

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Shellwood Lower Left Tall Room (Shellwood_03)](#shellwood-lower-left-tall-room-shellwood03) | LL | None |  |  |  |
| RC | top2 |  | [Shellgrave (Shellgrave)](#shellgrave-shellgrave) | F | Ledge grab OR Faydown Cloak OR Silk Soar OR Enemy Pogo |  |  |  |
| L | left1 |  | [Shellwood Lower Toll bench (Shellwood_08c)](#shellwood-lower-toll-bench-shellwood08c) | R | Break Vines |  |  |  |
| LC | top1 |  | [shellwood Far Left Tall Room (Shellwood_04c)](#shellwood-far-left-tall-room-shellwood04c) | F | Enemy Pogo OR Cling grip OR Silk soar OR Faydown Cloak OR ( Dash AND Scuttlebrace ) |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| PC | Pond Crossing | Left Lake | Right Lake | Swim OR Clawline OR ( Sprint AND Drifters Cloak ) OR ( Wings AND Enemy Pogo ) OR ( Drifters Cloak AND Enemy Pogo ) |  |  |  |
| PC | Pond Crossing | Right Lake | Left Lake | Swim OR Clawline OR ( Sprint AND Drifters Cloak ) OR ( Wings AND Enemy Pogo ) OR ( Drifters Cloak AND Enemy Pogo ) |  |  |  |

#### Check Locations

No check locations defined.

### Shellwood Lower Left Tall Room (Shellwood_03)

**Game ID:** Shellwood_03

**Contributors:** Pyxl

#### Subrooms

- Top
- Bottom

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | left1 | Top | [Shellwood Bellway  (Shellwood_19)](#shellwood-bellway) | R | Sprint OR Dash OR clawline OR silksoar OR Sharpdart OR Drifters Cloak OR Faydown Cloak OR Beast Crest |  |  |  |
| F | bot1 | Bottom | [Greyroots Basement Tall room (Mosstown_03)](#greyroots-basement-tall-room-mosstown03) | C | Exit opened from other side |  |  |  |
| MR | right2 | Top | [Shellwood Mask Shard Room (Shellwood_14)](#shellwood-mask-shard-room-shellwood14) | L | None |  |  |  |
| LL | left3 | Bottom | [Shellwood Left side Long pond room (Shellwood_04b)](#shellwood-left-side-long-pond-room-shellwood04b) | R | None |  |  |  |
| UR | right1 | Top | [Cling Grip Room (Shellwood_10)](#cling-grip-room-shellwood10) | LL | Ledge Grab OR Faydown Cloak OR Silk Soar OR Cling Grip |  |  |  |
| LR | right3 | Bottom | [shellwood Shakra (Shellwood_16)](#shellwood-shakra-shellwood16) | L | None |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| FP | Flower Pogo | Bottom | Top | Ledge Grab OR Cling Grip OR Silk Soar |  |  |  |
| FP | Flower Pogo | Top | Bottom | None |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Flea: Shellwood | Top | None |  |  | Included |  |

### Shellwood Lower Toll bench (Shellwood_08c)

**Game ID:** Shellwood_08c

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | UR | None |  |  |  |
| R | right1 |  | [Shellwood Left side Long pond room (Shellwood_04b)](#shellwood-left-side-long-pond-room-shellwood04b) | L | None |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Bench |  | Dont be broke |  |  | Not included |  |

### Shellwood Mask Shard Room (Shellwood_14)

**Game ID:** Shellwood_14

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Shellwood Lower Left Tall Room (Shellwood_03)](#shellwood-lower-left-tall-room-shellwood03) | MR | None |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Mask Shard: Shellwood #12 |  | Ledge Grab OR Dash OR Clawline OR Faydown Cloak OR Drifters Cloak OR Beast Crest |  |  | Included |  |

### Shellwood Right Side Big room (Shellwood_01)

**Game ID:** Shellwood_01

**Contributors:** Pyxl

#### Subrooms

- Ground Level Left
- Central Platforms
- Right Platforms
- Ground Level Right

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | right1 | Right Platforms | [Long Pin (Belltown_Room_shellwood)](#long-pin-belltownroomshellwood) | L | Nest in Door broken |  |  |  |
| UL | left1 | Central Platforms | [Shellwood Sister Splinter Bench (Shellwood_01b)](#shellwood-sister-splinter-bench-shellwood01b) | LR | None |  |  |  |
| LR | right2 | Ground Level Right | [Bellhart Hallway to Shellwood (Belltown_07)](#bellhart-hallway-to-shellwood-belltown07) | L | None |  |  |  |
| LL | left2 | Ground Level Left | [Shellwood Big Room Left (Shellwood_02)](#shellwood-big-room-left-shellwood02) | LR | Door opened from other side |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LA | Lake | Ground Level Left | Ground Level Right | ( Dash AND ( Sprint OR Drifters Cloak ) ) OR Clawline OR Sharpdart OR Swim OR ( Faydown Cloak AND Drifters Cloak ) |  |  |  |
| LA | Lake | Ground Level Right | Ground Level Left |  |  |  |  |
| C1 | Chasm 1 | Ground Level Left | Central Platforms | ( Ledge Grab AND ( Dash OR Drifters Cloak OR Beast Crest ) ) OR Clawline OR Cling Grip OR Silk Soar OR Sharpdart OR Faydown Cloak |  |  |  |
| C1 | Chasm 1 | Central Platforms | Ground Level Left | None |  |  |  |
| C2 | Chasm 2 | Central Platforms | Right Platforms | Ledge Grab OR Faydown Cloak OR Silk Soar OR Cling grip OR Dash OR Scuttlebrace OR Clawline  OR Sprint |  |  |  |
| C2 | Chasm 2 | Right Platforms | Central Platforms | None |  |  |  |
| C3 | Chasm 3 | Right Platforms | Ground Level Right | None |  |  |  |
| C3 | Chasm 3 | Ground Level Right | Right Platforms | Any movement abilty OR enemy pogo Silk Soar OR ( Cling Grip AND Faydown Cloak ) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Collectable IFrayed Rosary String: Shellwoodtem Pickup | Central Platforms | None |  |  | Included |  |
| Pollip Heart #1 | Right Platforms | Cling Grip OR Silk Soar OR Scuttlebrace |  |  | Included |  |
| Shell shard Cache: Shellwood #? forgot the id 1 | Right Platforms | None | TODO |  | Included |  |
| Shell shard Cache: Shellwood #? forgot the id 2 | Right Platforms | None | TODO |  | Included |  |
| Shell shard Cache: Shellwood #? forgot the id 3 | Right Platforms | None | TODO |  | Included |  |

### Shellwood Sister Splinter Bench (Shellwood_01b)

**Game ID:** Shellwood_01b

**Contributors:** Pyxl

#### Subrooms

- Above Arena
- Arena
- Bench Toll
- Elevator Platform
- Upper Main
- Upper Hidden

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | right1 | Elevator Platform | [Shellwood Upper Bellhart Entrance (Shellwood_13)](#shellwood-upper-bellhart-entrance-shellwood13) | LL | None |  |  |  |
| LR | right2 | Bench Toll | [Shellwood Right Side Big room (Shellwood_01)](#shellwood-right-side-big-room-shellwood01) | UL | None |  |  |  |
| MR | right3 | Upper Hidden | [Shellwood Hidden Bellhart Connection (Shellwood_15)](#shellwood-hidden-bellhart-connection-shellwood15) | L | Door Opened from other side |  |  |  |
| UL | left1 | Upper Main | [Shellwood Flower Pogo Upper Hall (Shellwood_20)](#shellwood-flower-pogo-upper-hall-shellwood20) | R | None |  |  |  |
| LL | left2 | Above Arena | [Shellwood Big Room Left (Shellwood_02)](#shellwood-big-room-left-shellwood02) | UR | None |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| AD | Arena Drop | Above Arena | Arena | None |  |  |  |
| AD | Arena Drop | Arena | Above Arena | Silk Soar |  |  |  |
| AE | Arena Exit | Arena | Bench Toll | Ledge Grab OR ( Dash AND Scuttlebrace ) OR Clawline OR Cling Grip OR Faydown Cloak OR Silk Soar |  |  |  |
| AE | Arena Exit | Bench Toll | Arena | None |  |  |  |
| CL1 | Climb 1 | Bench Toll | Upper Hidden | ( Cling Grip AND ( Clawline OR Dash OR Sharpdart OR Drifters Cloak OR Faydown Cloak OR Beast Crest ) OR Silk Soar |  |  |  |
| CL1 | Climb 1 | Upper Hidden | Bench Toll | None |  |  |  |
| EL | Elevator | Bench Toll | Elevator Platform | Elevator activated |  |  |  |
| EL | Elevator | Elevator Platform | Bench Toll | Elevator activated |  |  |  |
| CL2 | Climb 2 | Upper Main | Bench Toll | None |  |  |  |
| CL2 | Climb 2 | Bench Toll | Upper Main | Cling Grip OR Silk Soar |  |  |  |
| HP | Hidden Path | Upper Main | Upper Hidden | None |  |  |  |
| HP | Hidden Path | Upper Hidden | Upper Main | None |  |  |  |
| EP | Elevator Platform | Upper Main | Elevator Platform | None |  |  |  |
| EP | Elevator Platform | Elevator Platform | Upper Main | Ledge Grab OR ( Dash AND Scuttlebrace ) OR Clawline OR Cling Grip OR Faydown Cloak OR Silk Soar |  |  |  |
| CL3 | Climb 3 | Above Arena | Bench Toll | Cling Grip OR Silk Soar OR ( Dash AND Scuttlebrace ) |  |  |  |
| CL3 | Climb 3 | Bench Toll | Above Arena | None |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Rosary String: Shellwood #1 | Upper Hidden | None |  |  | Included |  |
| Bench | Bench Toll | None |  |  | Included |  |

### Shellwood Top Room (Shellwood_26)

**Game ID:** Shellwood_26

**Contributors:** Pyxl

#### Subrooms

- Left Side
- Central
- Right Side
- Upper Area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Left Side | [Cling Grip Room (Shellwood_10)](#cling-grip-room-shellwood10) | UR | None |  |  |  |
| F | bot1 | Right Side | [Sister Splinter (Shellwood_18)](#sister-splinter-shellwood18) | C | None |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LW | Left Wall | Left Side | Central | Cling Grip OR Faydown Cloak OR Silk Soar OR ( Dash AND Scuttlebrace ) |  |  |  |
| LW | Left Wall | Central | Left Side | Cling Grip OR Faydown Cloak OR Silk Soar OR ( Dash AND Scuttlebrace ) |  |  |  |
| RW | Right Wall | Central | Right Side | ( Swim OR Drifters Cloak AND Easy Skip ) AND ( Cling Grip OR ( Dash AND Scuttlebrace ) |  |  |  |
| RW | Right Wall | Right Side | Central | Cling Grip OR Faydown Cloak OR Silk Soar OR ( Dash AND Scuttlebrace ) |  |  |  |
| HS | Hidden Shaft | Left Side | Upper Area | Break wall from upper Area AND Silk Soar |  |  |  |
| HS | Hidden Shaft | Upper Area | Left Side | Break wall from upper Area |  |  |  |
| CC | Central Shaft | Central | Upper Area | Cling Grip AND ( Swim OR Clawline OR Drifters Cloak OR Sharpdart OR ( Beast Crest AND Dash ) OR ( Sprint AND Dash ) ) OR ( Dash AND Scuttlebrace AND ( Swim OR Clawline OR Easy skips OR Faydown Cloak ) ) |  |  |  |
| CC | Central Shaft | Upper Area | Central | None |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Pollip Heart #4 | Upper Area | Cling Grip OR Silk Soar OR Clawline OR ( Faydown Cloak AND ( Ledge Grab OR Clawline ) ) |  |  | Included |  |
| Rosary cache: Shellwood | Right Side | Cling Grip OR Silk Soar OR ( Scuttlebrace AND Dash ) |  |  | Included |  |
| Upper Area | Upper Area | None |  |  | Not included | Not included |
| Resting Site: Shellwood | Right Side | Wish: A vassal Lost started AND Steel Soul |  |  | Not included |  |

### Shellwood Upper Bellhart Entrance (Shellwood_13)

**Game ID:** Shellwood_13

**Contributors:** Pyxl

#### Subrooms

- Left Pond
- Right Pond
- Bell Ledge
- Upper Area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | left1 | Upper Area | [Sister Splinter (Shellwood_18)](#sister-splinter-shellwood18) | R | (ANY Crest - Wanderer AND Ledge Grab } OR Clawline OR Dash OR Drifters Cloak OR Faydown Cloak OR Sharpdart |  |  |  |
| R | right1 | Bell Ledge | [Upper Bellhart (Belltown_04)](#upper-bellhart-belltown04) | UL | None |  |  |  |
| LL | left2 | Left Pond | [Shellwood Sister Splinter Bench (Shellwood_01b)](#shellwood-sister-splinter-bench-shellwood01b) | UR | None |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BL | Bell Ledge | Bell Ledge | Upper Area | Cling Grip OR Faydown Cloak OR Silk soar OR ( Dash AND Scuttlebrace ) |  |  |  |
| BL | Bell Ledge | Upper Area | Bell Ledge | None |  |  |  |
| PO | Pond | Left Pond | Right Pond | Swim OR Clawline OR ( Drifters Cloak AND ( Faydown Cloak OR ( Sprint AND Dash ) OR ( Sharpdart AND Ledge grab ) ) OR ( Faydown Cloak AND Sharpdart AND ( Dash OR Beast Crest ) |  |  |  |
| PO | Pond | Right Pond | Left Pond | Swim OR ( Clawline AND ( Ledge Grab OR Dash OR Sharpdart OR beast Crest OR Faydown Cloak ) ) OR ( Sprint AND ( Sharpdart AND Dash ) OR ( Sharpdart AND Beast Crest ) OR ( Faydown Cloak AND Drifters Cloak ) OR ( Sharpdart AND Drifters Cloak) OR ( Faydown Cloak AND Sharpdart ) ) |  |  |  |
| PL | Platforms | Upper Area | Right Pond | None |  |  |  |
| PL | Platforms | Right Pond | Upper Area | Ledge Grab OR Dash OR Clawline OR Faydown Cloak OR Cling Grip OR Silk soar |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Shard Bundle: Shellwood | Upper Area | (Cling Grip AND Faydown Cloak ) OR Silk Soar OR ( Faydown Cloak AND Dash AND Scuttlebrace ) |  |  | Included |  |
|  |  |  |  |  | Not included |  |

### Sister Splinter (Shellwood_18)

**Game ID:** Shellwood_18

**Contributors:** Pyxl

#### Subrooms

- Arena Side
- Right Side

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Arena Side | [Cling Grip Room (Shellwood_10)](#cling-grip-room-shellwood10) | MR |  |  |  |  |
| R | right1 | Right Side | [Shellwood Upper Bellhart Entrance (Shellwood_13)](#shellwood-upper-bellhart-entrance-shellwood13) | UL |  |  |  |  |
| C | top1 | Right Side | [Shellwood Top Room (Shellwood_26)](#shellwood-top-room-shellwood26) | F | Cling Grip OR ( Dash AND Scuttlebrace ) |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| PU | Puddle | Arena Side | Right Side | Swim OR ( Cling Grip AND Ledge grab ) OR Dash OR Clawline OR Sharp Dart OR Drifters Cloak OR Faydown Cloak OR Beast Crest |  |  |  |
| PU | Puddle | Right Side | Arena Side | Swim OR Dash OR Clawline OR Sharp Dart OR Drifters Cloak OR Faydown Cloak OR Beast Crest |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Boss: Sister Splinter | Arena Side | None |  |  | Included |  |

### Witch Chapel (Shellwood_25b)

**Game ID:** Shellwood_25b

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | Left1 |  | [Shellwood Diddy Basement Main (Shellwood_25)](#shellwood-diddy-basement-main-shellwood25) | D | None |  |  |  |
| QR | Quest Rebirth |  | [Greyroot (Room_Witch)](#greyroot-roomwitch) | QR |  |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### shellwood Far Left Tall Room (Shellwood_04c)

**Game ID:** Shellwood_04c

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | top1 |  | [Shellwood Connection To Blasted steps (Shellwood_08)](#shellwood-connection-to-blasted-steps-shellwood08) | F | (Faydown Cloak AND difficult enemy pogo AND Ledge grab) OR cling grip OR silk soar OR ( Dash AND Scuttlebrace AND Faydown Cloak ) |  |  |  |
| F | bot1 |  | [Shellwood Left side Long pond room (Shellwood_04b)](#shellwood-left-side-long-pond-room-shellwood04b) | LC | None |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### shellwood Shakra (Shellwood_16)

**Game ID:** Shellwood_16

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Shellwood Lower Left Tall Room (Shellwood_03)](#shellwood-lower-left-tall-room-shellwood03) | LR | None |  |  |  |
| R | right1 |  | [Shellwood Big Room Left (Shellwood_02)](#shellwood-big-room-left-shellwood02) | LL | None |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Map: Shellwood |  | None |  |  | Included |  |

## Bellhart

### Bellhart Bellway (Belltown_basement)

**Game ID:** Belltown_basement

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | bot1 |  | [Bellhart Lower (Belltown_basement_03)](#bellhart-lower-belltownbasement03) | C | None |  |  |  |
| L | left1 |  | [Belltown (Belltown)](#belltown-belltown) | BD | Ledge Grab OR Clawline OR Faydown Cloak OR Cling Grip OR Silk Soar |  |  |  |
| BH | door_fastTravelExit |  | [Bellway Menu](#bellway-menu) | BH | Bellway access |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Bellway: Bellhart |  | None |  |  | Included |  |

### Bellhart Hallway to Shellwood (Belltown_07)

**Game ID:** Belltown_07

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Shellwood Right Side Big room (Shellwood_01)](#shellwood-right-side-big-room-shellwood01) | LR | None |  |  |  |
| R | right1 |  | [Belltown (Belltown)](#belltown-belltown) | L | None |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Rosary Cache: Bellhart #4 |  | Cling Grip OR Silk soar OR ( Dash AND Scuttlebrace AND Faydown Cloak ) |  |  | Included |  |
| Lore: Bellhart #2 |  | None |  |  | Included |  |

### Bellhart Lower (Belltown_basement_03)

**Game ID:** Belltown_basement_03

**Contributors:** Pyxl

#### Subrooms

- Top Exit
- Hermit
- Upper Hall
- Under Hermit Hall
- Rosary Room
- Passage below rosary
- Breakable Wall Passage
- Lower Passage 1
- Lower Passage 2
- Bottom Exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | top1 |  | [Bellhart Bellway (Belltown_basement)](#bellhart-bellway-belltownbasement) | F | None |  |  |  |
| L | left1 |  | [The Marrow Jail Pathway (Bone_08)](#the-marrow-jail-pathway-bone08) | UR | None |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| PL | Platforms Upper | Top Exit | Hermit | None |  |  |  |
| PL | Platforms Upper | Hermit | Top Exit | Clawline OR Ledge Grab OR Shamen Crest OR ( Dash AND Scuttlebrace ) OR Faydown Cloak OR Silk Soar OR  Cling Grip |  |  |  |
| UP | Upper Hall | Hermit | Upper Hall | Cling Grip OR Silk Soar OR ( Scuttlebrace AND Dash ) |  |  |  |
| UP | Upper Hall | Upper Hall | Hermit | None |  |  |  |
| TL | Tall Passage Left | Upper Hall | Under Hermit Hall | None |  |  |  |
| TL | Tall Passage Left | Under Hermit Hall | Upper Hall | Cling Grip OR ( Scuttlebrace AND Dash ) |  |  |  |
| HH | Hermit Hole | Hermit | Under Hermit Hall | One way wall broken From Underneath |  |  |  |
| HH | Hermit Hole | Under Hermit Hall | Hermit | Cling Grip OR Silk Soar OR ( Scuttlebrace AND Dash ) AND One way wall broken |  |  |  |
| TR | Tall Passage Right | Under Hermit Hall | Rosary Room | None |  |  |  |
| TR | Tall Passage Right | Rosary Room | Under Hermit Hall | Cling Grip OR ( Scuttlebrace AND Dash ) |  |  |  |
| WS | Wide Shaft | Rosary Room | Passage below rosary | None |  |  |  |
| WS | Wide Shaft | Passage below rosary | Rosary Room | Cling Grip OR Silk Soar OR ( Scuttlebrace AND Dash ) |  |  |  |
| RS | Shaft near Rosary Cache | Passage below rosary | Breakable Wall Passage | Cling Grip OR Silk Soar OR ( Scuttlebrace AND Dash ) |  |  |  |
| RS | Shaft near Rosary Cache | Breakable Wall Passage | Passage below rosary | None |  |  |  |
| BW | Broken Floor Shaft | Breakable Wall Passage | Under Hermit Hall | Cling Grip OR ( Scuttlebrace AND Dash ) |  |  |  |
| BW | Broken Floor Shaft | Under Hermit Hall | Breakable Wall Passage | One way wall broken From Underneath |  |  |  |
| BL | Tall Passage Bottom Left | Breakable Wall Passage | Lower Passage 1 | None |  |  |  |
| BL | Tall Passage Bottom Left | Lower Passage 1 | Breakable Wall Passage | Cling Grip OR ( Scuttlebrace AND Dash ) |  |  |  |
| LV | Lower Passages Shaft | Lower Passage 1 | Lower Passage 2 | None |  |  |  |
| LV | Lower Passages Shaft | Lower Passage 2 | Lower Passage 1 | Cling Grip OR ( Scuttlebrace AND Dash ) |  |  |  |
| WP | Wide Platform Shaft | Lower Passage 2 | Passage below rosary | Cling Grip OR Silk Soar OR ( Dash AND Scuttlebrace AND ( Ledge Grab OR Clawline OR Faydown Cloak OR Sharpdart OR Beast Crest ) ) AND Breakable Floor Opened |  |  |  |
| WP | Wide Platform Shaft | Passage below rosary | Lower Passage 2 | One way wall broken From Underneath AND ( Dash OR Sprint OR Ledge grab OR Clawline OR Drifters Cloak OR Faydown Cloak OR Cling grip OR Shamen Crest OR Architect Crest OR Beast Crest ) |  |  |  |
| ES | Exit Shaft | Lower Passage 2 | Bottom Exit | Break One way wall |  |  |  |
| ES | Exit Shaft | Bottom Exit | Lower Passage 2 | One way wall broken from above AND ( Cling Grip OR Silk Soar ( Dash AND Scuttlebrace AND Faydown Cloak ) ) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Hermits Soul | Hermit | Silk and Soul Wish Started |  |  | Not included |  |
| Silver Bell Spawn Location #6 | Upper Hall | Silver Bells Wish Started |  |  | Not included |  |
| Rosary Cache: Bellhart #6 | Upper Hall | None |  |  | Included |  |
| Silver Bell Spawn Location #7 | Upper Hall | Silver Bells Wish Started |  |  | Not included |  |
| Silver Bell Spawn Location #8 | Under Hermit Hall | Silver Bells Wish Started |  |  | Not included |  |
| Silver Bell Spawn Location #12 | Under Hermit Hall | Silver Bells Wish Started |  |  | Not included |  |
| Rosary Cache: Bellhart #7 | Rosary Room | None |  |  | Included |  |
| Silver Bell Spawn Location #9 | Passage below rosary | Silver Bells Wish Started |  |  | Not included |  |
| Silver Bell Spawn Location #10 | Lower Passage 1 | Silver Bells Wish Started |  |  | Not included |  |
| Silver Bell Spawn Location #11 | Lower Passage 2 | Silver Bells Wish Started |  |  | Not included |  |
| Rosary Cache: Bellhart #5 | Bottom Exit | None |  |  | Included |  |

### Bellhart Pinsmith (Belltown_Room_pinsmith)

**Game ID:** Belltown_Room_pinsmith

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Belltown (Belltown)](#belltown-belltown) | ND | None |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Needle Upgrade 1 |  | None |  |  | Included |  |
| Needle Upgrade 2 |  | Pale Oil |  |  | Included |  |
| Needle Upgrade 3 |  | Pale Oil |  |  | Included |  |
| Needle Upgrade 4 |  | Pale Oil |  |  | Included |  |

### Bellhart Relic Shop (Belltown_Room_Relic)

**Game ID:** Belltown_Room_Relic

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Belltown (Belltown)](#belltown-belltown) | RD | None |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Hand In bone scroll 1 |  | Bone scroll |  |  | Included |  |
| Hand In bone scroll 2 |  | Bone scroll |  |  | Included |  |
| Hand In bone scroll 3 |  | Bone scroll |  |  | Included |  |
| Hand In bone scroll 4 |  | Bone scroll |  |  | Included |  |
| Hand In Weaver Effigy 1 |  | Weaver Effigy |  |  | Included |  |
| Hand In Weaver Effigy 2 |  | Weaver Effigy |  |  | Included |  |
| Hand In Weaver Effigy 3 |  | Weaver Effigy |  |  | Included |  |
| Hand in Choral Commandment 1 |  | Choral Commandment |  |  | Included |  |
| Hand in Choral Commandment 2 |  | Choral Commandment |  |  | Included |  |
| Hand in Choral Commandment 3 |  | Choral Commandment |  |  | Included |  |
| Hand in Choral Commandment 4 |  | Choral Commandment |  |  | Included |  |
| Hand in Rune Harp 1 |  | Rune Harp |  |  | Included |  |
| Hand in Rune Harp 2 |  | Rune Harp |  |  | Included |  |
| Hand in Rune Harp 3 |  | Rune Harp |  |  | Included |  |
| Hand in Arcane Egg |  | Arcane Egg |  |  | Included |  |

### Bellhart Right Entrance (Belltown_06)

**Game ID:** Belltown_06

**Contributors:** Pyxl

#### Subrooms

- Lower Level
- Upper Level

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | left3 | Upper Level | [Widow Boss Fight (Belltown_Shrine)](#widow-boss-fight-belltownshrine) | R | None |  |  |  |
| UD | door1 | Upper Level | [Bellhart Right Entrance (Belltown_06)](#bellhart-right-entrance-belltown06) | UD | Inaccessible |  |  |  |
| LL | left1 | Lower Level | [Belltown (Belltown)](#belltown-belltown) | R | None |  |  |  |
| R | right1 | Lower Level | TODO |  | None |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| EL | Elevator | Lower Level | Upper Level | Elevator activated from avobe |  |  |  |
| EL | Elevator | Upper Level | Lower Level | Elevator activated |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Lore: Bellhart #1 | Lower Level | none |  |  | Not included |  |

### Belltown (Belltown)

**Game ID:** Belltown

**Contributors:** Pyxl

#### Subrooms

- Upper Area
- Lower Area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| RD | door4 |  | [Bellhart Relic Shop (Belltown_Room_Relic)](#bellhart-relic-shop-belltownroomrelic) | L |  |  |  |  |
| L | left3 |  | [Bellhart Hallway to Shellwood (Belltown_07)](#bellhart-hallway-to-shellwood-belltown07) | R |  |  |  |  |
| BD | door1 |  | [Bellhart Bellway (Belltown_basement)](#bellhart-bellway-belltownbasement) | L |  |  |  |  |
| HD | door5 |  | [Bellhome (Belltown_room_spare)](#bellhome-belltownroomspare) | L |  |  |  |  |
| ND | door3 |  | [Bellhart Pinsmith (Belltown_Room_pinsmith)](#bellhart-pinsmith-belltownroompinsmith) | L |  |  |  |  |
| R | right2 |  | [Bellhart Right Entrance (Belltown_06)](#bellhart-right-entrance-belltown06) | LL |  |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| PL | Platforms | Lower Area | Upper Area | Ledge grab OR Dash OR Clawline OR Silksoar OR Faydown Cloak OR Sharpdart OR Shamen Crest OR Cling Grip |  |  |  |
| PL | Platforms | Upper Area | Lower Area | None |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Memory Locket: Bellhart roof | Upper Area | Silk Soar |  |  | Included |  |
| Wish: Silver Bells | Lower Area | 8 Silver Bells |  |  | Included |  |
| Wish: My Missing Courier | Lower Area | Locate Tipp in Aspid_01 |  |  | Included |  |
| Wish: Crawbug Clearing | Lower Area | 25 Ragpelt |  |  | Included |  |
| Wish: Restoration of Bellhart | Lower Area | 250 Rosaries |  |  | Included |  |
| Wish: Bellharts Glory | Lower Area | 400 Rosaries |  |  | Included |  |
| Wish: My missing Brother | Lower Area | Locate Pill in Dust_04 |  |  | Included |  |
| Wish: Savage Beastfly | Lower Area | Kill the Savage Beastfly in Bone_East_08 |  |  | Included |  |
| Wish: Trails End | Lower Area | Meet Shakra in Shadow_24 |  |  | Included |  |
| Wish: Fatal Resolve | Lower Area | Find note in room_pinstress and beat her at Peak_07 AND ACT3 |  |  | Included |  |
| Wish: Ecstacy of the end | Lower Area | Achieve the highscore in all 3 games in Fleatopia ( Aqueduct_05 ) AND ACT3 |  |  | Included |  |
| Wish: Heros Call | Lower Area | Defeat Lost Garmond in Coral_33 AND ACT3 |  |  | Included |  |
| Wish: The Hidden Hunter | Lower Area | Defeat Gurr the Outcast in Bone_east_18b |  |  | Included |  |
| Wish: Dark hearts | Lower Area | Defeat 12 Void Masses AND ACT3 |  |  | Included |  |
| Wish: The Threadspun town | Lower Area | Defeat Widow in Belltown_Shrine |  |  | Included |  |
| Wish: Bone bottom supplys | Upper Area | Travel to Bone Bottom ( Bonetown ) |  |  | Included |  |
| Wish: Pilgrims Rest Supplys | Upper Area | Travel to Pilgrims Rest ( Bone_east_10 ) |  |  | Included |  |
| Wish: Queens Egg | Upper Area | Travel to Dust_11 |  |  | Included |  |
| Wish; Songclave Supplys | Upper Area | Travel to Songclave ( Song_enclave ) |  |  | Included |  |
| Wish: Fleatopia Supplys | Upper Area | Travel to Fleatopia ( Aqueduct_05 ) |  |  | Included |  |
| Wish: Liquid Laquer | Upper Area | Travel to Mask Maker ( Peak_mask_maker ) |  |  | Included |  |
| Wish: Couriers Rasher | Upper Area | Travel to Song_09b fast |  |  | Included |  |
| Memory Locket ( Frey ) | Lower Area | 330 Rosaries |  |  | Included |  |
| Spool Fragment ( Frey ) | Lower Area | 270 Rosaries AND Wish: My missing Courier completed |  |  | Included |  |
| Multibinder | Lower Area | 880 Rosaries AND Wish: My missing Courier completed |  |  | Included |  |
| Desk | Lower Area | 380 Rosaries |  |  | Included |  |
| Gleamlights | Lower Area | 320 Rosaries |  |  | Included |  |
| Bell Lacquer | Lower Area | 520 Rosaries |  |  | Included |  |
| Personal Spa | Lower Area | 1100 Rosaries AND 2 other bellhome items |  |  | Included |  |
| Gramophone | Lower Area | 490 Rosaries AND All psalm cylinders handed in |  |  | Included |  |
| Map: Bellhart | Upper Area | 40 Rosaries |  |  | Included |  |
| Craw Summons | Lower Area | None |  |  | Included |  |

### Upper Bellhart (Belltown_04)

**Game ID:** Belltown_04

**Contributors:** Pyxl

#### Subrooms

- Lower Exits
- Lower Big Room
- Silver Bell Cubby
- Central Passage
- Upper Big room

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LL | left2 | Lower Exits | [Shellwood Hidden Bellhart Connection (Shellwood_15)](#shellwood-hidden-bellhart-connection-shellwood15) | R | None |  |  |  |
| F | bot1 | Lower Exits | [Widow Boss Fight (Belltown_Shrine)](#widow-boss-fight-belltownshrine) | C | None |  |  |  |
| UL | left1 | Upper Big room | [Shellwood Upper Bellhart Entrance (Shellwood_13)](#shellwood-upper-bellhart-entrance-shellwood13) | R | None |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TS1 | Tall Shaft1 | Lower Exits | Lower Big Room | Break wall AND ( Ledge Grab OR Clawline OR Faydown Cloak OR ( Dash AND Scuttlebrace ) OR Damage Knockback OR Cling Grip ) |  |  |  |
| TS1 | Tall Shaft1 | Lower Big Room | Lower Exits | Break wall AND ( Ledge Grab OR Clawline OR Faydown Cloak OR ( Dash AND Scuttlebrace ) OR Cling grip ) |  |  |  |
| TS2 | Tall Shaft2 | Lower Exits | Silver Bell Cubby | Break wall AND ( Cling Grip OR ( Dash AND Scuttlebrace ) ) |  |  |  |
| TS2 | Tall Shaft2 | Silver Bell Cubby | Lower Exits | Break wall |  |  |  |
| TS3 | Tall Shaft3 | Lower Big Room | Silver Bell Cubby | None |  |  |  |
| TS3 | Tall Shaft3 | Silver Bell Cubby | Lower Big Room | Cling Grip OR ( Dash AND Scuttlebrace ) |  |  |  |
| TS4 | Tall Shaft4 | Silver Bell Cubby | Central Passage | Cling Grip OR ( Dash AND Scuttlebrace ) |  |  |  |
| TS4 | Tall Shaft4 | Central Passage | Silver Bell Cubby | None |  |  |  |
| US | Upper Shafts | Central Passage | Upper Big room | Break wall AND ( Cling Grip OR ( Dash AND Scuttlebrace ) ) |  |  |  |
| US | Upper Shafts | Upper Big room | Central Passage | None |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Silver Bell Spawn Location #1 | Lower Big Room | None |  |  | Included |  |
| Silver Bell Spawn Location #2 | Lower Big Room | Cling Grip OR Silk Soar OR ( Dash AND Scuttlebrace ) |  |  | Included |  |
| Rosary Cache: Bellhart #1 | Lower Big Room | Cling Grip OR Silk Soar OR ( Dash AND Scuttlebrace ) |  |  | Included |  |
| Rosary Cache: Bellhart #2 | Lower Big Room | Cling Grip OR Silk Soar OR ( Dash AND Scuttlebrace ) |  |  | Included |  |
| Silver Bell Spawn Location #3 | Silver Bell Cubby | None |  |  | Included |  |
| Silver Bell Spawn Location #4 | Central Passage | Break wall |  |  | Included |  |
| Rosary Cache: Bellhart #3 | Central Passage | Break wall |  |  | Included |  |
| Silver Bell Spawn Location #5 | Upper Big room | None |  |  | Included |  |
| Flea: Bellhart | Upper Big room | Silk Soar OR Cling Grip OR ( Dash AND Scuttlebrace ) OR ( Easy skips AND ( Faydown Cloak OR Drifters Cloak ) ) |  |  | Included |  |

### Widow Boss Fight (Belltown_Shrine)

**Game ID:** Belltown_Shrine

**Contributors:** Pyxl

#### Subrooms

- Arena
- Upper

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Arena | [Bellhart Right Entrance (Belltown_06)](#bellhart-right-entrance-belltown06) | UL | None |  |  |  |
| C | top1 | Upper | [Upper Bellhart (Belltown_04)](#upper-bellhart-belltown04) | F | Silk Soar OR Cling Grip OR ( Dash AND Scuttlebrace ) OR ( Easy skips AND ( Faydown Cloak OR Drifters Cloak ) ) |  |  |  |
| D | door_wakeOnGround | Arena | TODO |  |  | TODO |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TD | Trapdoor | Arena | Upper | Hit Switch AND ( Cling Grip OR Silk soar OR ( Dash AND Scuttlebrace ) ) |  |  |  |
| TD | Trapdoor | Upper | Arena | Hit Switch |  |  |  |
| RH | Roof Hole | Arena | Upper | Silk Soar OR ( Cling Grip AND Faydown Cloak AND ( Clawline OR Sharpdart ) |  |  |  |
| RH | Roof Hole | Upper | Arena | None |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Boss: Widow | Arena | None |  |  | Included |  |
| Bell: Bellhart | Arena | None |  |  | Included |  |
| Needolin | Arena | None |  |  | Included |  |

### Bellhome (Belltown_room_spare)

**Game ID:** Belltown_room_spare

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | Left1 |  | [Belltown (Belltown)](#belltown-belltown) | HD | None |  |  |  |
| A3 | Act3 |  | TODO |  | Act 3 Access AND Sitting on bench Dash + Needolin | TODO |  |  |
| A2 | Act2 |  | TODO |  | Act 3 AND Sitting on bench Dash + Needolin | TODO |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

## Greymoor

### Greymoor Bellshrine (Bellshrine_02)

**Game ID:** Bellshrine_02

**Contributors:** isssma

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [Greymoor West Bellshrine Room  (Greymoor_01)](#greymoor-west-bellshrine-room-greymoor01) | MR | Activating the Bellshrine:Greymoor check |  | Verified |  |
| R | right |  | greymoor east bellshrine room | ML | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Greymoor - Bellshrine (ring bell switch) |  | none |  | Verified | Included | Opens up room transition: L |

### Greymoor Bone Scroll Room (Greymoor_21)

**Game ID:** Greymoor_21

**Contributors:** isssma

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | top |  | [Greymoor Lower Halfway Home Path (Greymoor_13)](#greymoor-lower-halfway-home-path-greymoor13) | D | Ledge grab OR faydown cloak OR silk soar OR cling grip OR shaman crest pogo |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Relic: Bone Scroll (Greymoor) |  | swim |  | Verified | Included |  |

### Greymoor Lower Halfway Home Path (Greymoor_13)

**Game ID:** Greymoor_13

**Contributors:** isssma

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left |  | TODO |  | Progressive swift step 1 OR clawline OR faydown cloak OR drifter cloak OR sharp dart OR beast crest pogo OR flea brew OR (cling grip AND (crest pogo EXCEPT wanderer crest pogo) OR swim) |  | Verified |  |
| R | right |  | [Greymoor West Bellshrine Room  (Greymoor_01)](#greymoor-west-bellshrine-room-greymoor01) | LL | Swim OR Crest Pogo OR Progressive swift step 2 OR clawline OR sharpdart OR (drifter cloak AND (ledge grab OR progressive swift step 1 OR faydown cloack)) OR (faydown cloak and progressive swift step 1) |  | Verified |  |
| D | down |  | [Greymoor Bone Scroll Room (Greymoor_21)](#greymoor-bone-scroll-room-greymoor21) | T | Swim OR (clawline AND ledge grab) |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Greymoor West Bellshrine Room  (Greymoor_01)

**Game ID:** Greymoor_01

**Contributors:** isssma

#### Subrooms

- main path
- middle section left
- middle section right
- upper path right
- upper path left

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TL | top left | upper path left | greymoor upper halfway home path | R | Ledge grab OR cling grip OR enemy pogo OR faydown cloak OR scuttlebrace OR (progressive swftstep 1 AND claw line OR sharpdart) OR silk soar |  | Verified |  |
| TR | top right | upper path right | greymoor east bellshrine room | BL | cling grip OR progressive swift step 1 OR faydown cloak OR silk soar OR clawline OR sharp dart OR (drifter cloak AND ledge grab) |  | Verified |  |
| LR | lower right | main path | greymoor east bellshrine room | LSL | IF (lever switch was activated) => ledge grab OR Shaman crest OR faydown cloak OR silk soar |  | Verified |  |
| LL | lower left | main path | [Greymoor Lower Halfway Home Path (Greymoor_13)](#greymoor-lower-halfway-home-path-greymoor13) | R | none |  | Verified |  |
| MR | middle right | middle section right | [Greymoor Bellshrine (Bellshrine_02)](#greymoor-bellshrine-bellshrine02) | L | Bellshrine: Greymoor check |  | Verified |  |
| D | down | main path | TODO |  | Enter from far fields using drifter cloak |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LS | Lever Switch | main path | middle section right | cling grip OR silk soar OR (lever switch AND (faydown cloak OR ledge grab OR shaman crest pogo)) |  | Verified |  |
| LS | Lever Switch | middle section right | main path | none (Switch is on this sidel) |  | Verified | the switch can be missed and fall to Main Pathway |
| P | Platform | middle section left | upper path right | ledge grab OR faydown cloak OR silk soar OR shaman crest pogo OR cling grip |  | Verified | the platform can be missed and fall to main pathway |
| P | Platform | upper path right | middle section left | none (can fall to reach it) |  | Verified | the platform can be missed and fall to main pathway |
| F1 | Fall 1 | middle section right | upper path right | Silk soar |  | Verified |  |
| F1 | Fall 1 | upper path right | middle section right | none (can fall to reach it) |  | Verified |  |
| BG | Big Gap | middle section right | middle section left | progressive swift step 1 AND clawline AND drifter cloak AND faydown cloak |  | Verified |  |
| BG | Big Gap | middle section left | middle section right | progressive swift step 1 AND clawline AND drifter cloak AND faydown cloak |  | Verified |  |
| G | Gap | upper path right | upper path left | faydown cloak OR OR drifter cloak OR flea brew OR progressive swift step 1 OR clawline OR sharpdart OR scuttlebrace |  | Verified |  |
| G | Gap | upper path left | upper path right | ledge grab OR enemy pogo OR progressive swift step 1 OR clawline OR sharpdart OR faydown cloak OR beast crest pogo OR shaman crest pogo |  | Verified |  |
| F2 | Fall 2 | middle section right | main path | none (can fall to reach it) |  | Verified |  |
| F2 | Fall 2 | main path | middle section right | silk soar |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Greymoor #1 - Rosary Cache | middle section left | Silk soar OR none OR (progressive swift step 1 AND faydown cloak AND clawline AND drifter cloak) |  | Verified | Not included | it really dpeends a lot from the entrance to the room to define the requirements so i placed subroom transitions that matter |
| lever switch | middle section right | silk soar OR cling grip |  | Verified | Not included | this drops down a platform that alters subroom connection LS and room connection LR |

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

## Verdania

## Blasted Steps

### Blasted Steps Bellway (Bellway_08)

**Game ID:** Bellway_08

**Contributors:** skai

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | Right |  | [Blasted Steps Wide Long Vertical (Coral_03)](#blasted-steps-wide-long-vertical-coral03) | TL | Nothing |  |  |  |
| BB | Bell Beast |  | [Bellway Menu](#bellway-menu) | BS | Bell Beast Available AND Blasted Steps Bellway Unlocked |  |  |  |
| L | Left |  | [Blasted Steps Thin Long Vertical (Coral_35)](#blasted-steps-thin-long-vertical-coral35) | R | Nothing |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Blasted Steps Grindle (Coral_42)

**Game ID:** Coral_42

**Contributors:** skai

#### Subrooms

- Lower Half
- Upper Half

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | Right | Lower Half | [Blasted Steps Thin Long Vertical (Coral_35)](#blasted-steps-thin-long-vertical-coral35) | ML | Nothing |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| MO | Middle Opening | Lower Half | Upper Half | Faydown AND (Cling Grip OR (Swift Step and Scuttlebrace)) OR Silk Soar |  |  |  |
| MO | Middle Opening | Upper Half | Lower Half | Nothing (Falling) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Thief's Mark | Upper Half | Nothing |  |  | Included |  |
| Snitch Pick | Upper Half | Nothing |  |  | Included |  |
| Reserve Bind | Upper Half | Nothing |  |  | Included |  |
| Relic: Psalm Cylinder (Grindle) | Upper Half | Nothing |  |  | Included |  |
| Crafting Kit: Grindle | Upper Half | Nothing |  |  | Included |  |
| Spool Fragment: Grindle (Blasted Steps) | Upper Half | Nothing |  |  | Included |  |

### Blasted Steps Horizontal Room with Two Sand Pits (Coral_43)

**Game ID:** Coral_43

**Contributors:** skai

#### Subrooms

- Left of Sand Pits
- Right of Sand Pits
- Sand Pits

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | Right | Right of Sand Pits | [Blasted Steps Thin Long Vertical (Coral_35)](#blasted-steps-thin-long-vertical-coral35) | BL | Nothing |  |  |  |
| L | Left | Left of Sand Pits | [Lumble the Lucky (Coral_33)](#lumble-the-lucky-coral33) | R | Nothing |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SPR | Sand Pit to Right | Sand Pits | Right of Sand Pits | Swift Step OR Faydown OR Clawline OR Drifter's Cloak OR Beast Crest OR Sharpdart OR (Flea Brew AND (Flea Brew Stall OR Crest Pogo)) |  |  |  |
| SPR | Sand Pit to Right | Right of Sand Pits | Sand Pits | Nothing |  |  |  |
| SPL | Sand Pit to Left | Left of Sand Pits | Sand Pits | Swift Step OR Faydown OR Clawline OR Drifter's Cloak OR Beast Crest OR Sharpdart OR (Flea Brew AND (Flea Brew Stall OR Crest Pogo)) |  |  |  |
| SPL | Sand Pit to Left | Sand Pits | Left of Sand Pits | Nothing |  |  |  |

#### Check Locations

No check locations defined.

### Blasted Steps Map Edge (Coral_19)

**Game ID:** Coral_19

**Contributors:** skai

#### Subrooms

- Lace Bridge
- Before Map Edge
- Map Edge

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B1 | Bottom | Lace Bridge | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | T1 | Nothing (Falling) |  |  |  |
| B2 | bot2 | Lace Bridge | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | T2 | Nothing (Falling) |  |  |  |
| B3 | bot3 | Lace Bridge | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | T3 | Nothing (Falling) |  |  |  |
| B4 | bot4 | Lace Bridge | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | T4 | Nothing (Falling) |  |  |  |
| B5 | bot5 | Lace Bridge | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | T5 | Nothing (Falling) |  |  |  |
| B6 | bot6 | Lace Bridge | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | T6 | Nothing (Falling) |  |  |  |
| B7 | bot7 | Lace Bridge | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | T7 | Nothing (Falling) |  |  |  |
| R | Right | Lace Bridge | [Shellwood Connection To Blasted steps (Shellwood_08)](#shellwood-connection-to-blasted-steps-shellwood08) | L | Nothing |  |  |  |
| TR3 | Top Right (3) | Lace Bridge | [Blasted Steps Wide Long Vertical (Coral_03)](#blasted-steps-wide-long-vertical-coral03) | B3 | Silk Soar |  |  |  |
| TR4 | Top Right (4) | Lace Bridge | [Blasted Steps Wide Long Vertical (Coral_03)](#blasted-steps-wide-long-vertical-coral03) | B4 | Silk Soar |  |  |  |
| TR5 | Top Right (5) | Lace Bridge | [Blasted Steps Wide Long Vertical (Coral_03)](#blasted-steps-wide-long-vertical-coral03) | B5 | Silk Soar |  |  |  |
| TR6 | Top Right (6) | Lace Bridge | [Blasted Steps Wide Long Vertical (Coral_03)](#blasted-steps-wide-long-vertical-coral03) | B6 | Silk Soar |  |  |  |
| TR7 | Top Right (7) | Lace Bridge | [Blasted Steps Wide Long Vertical (Coral_03)](#blasted-steps-wide-long-vertical-coral03) | B7 | Silk Soar |  |  |  |
| TR8 | Top Right (8) | Lace Bridge | [Blasted Steps Wide Long Vertical (Coral_03)](#blasted-steps-wide-long-vertical-coral03) | B8 | Silk Soar |  |  |  |
| TM | Top Middle | Before Map Edge | [Blasted Steps Toll Bench Bottom (Coral_02)](#blasted-steps-toll-bench-bottom-coral02) | BR | (Cling Grip AND (Spike Pogo OR Swift Step OR Faydown OR Crest Pogo OR Drifter's Cloak OR Flea Brew OR Precise Movement OR Sharpdart OR Clawline OR Needle Strike OR Heal Stall) OR (Swift Step AND Scuttlebrace) |  |  |  |
| TL | Top Left | Map Edge | [Blasted Steps Mask Shard (Coral_19b)](#blasted-steps-mask-shard-coral19b) | B | Silk Soar OR (Swift Step AND Faydown AND Clawline AND Precise Movement) |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| MEB | Map Edge to Before | Map Edge | Before Map Edge | Nothing |  |  |  |
| MEB | Map Edge to Before | Before Map Edge | Map Edge | Nothing |  |  |  |
| BLB | Before to Lace Bridge | Before Map Edge | Lace Bridge | Nothing |  |  |  |
| BLB | Before to Lace Bridge | Lace Bridge | Before Map Edge | Nothing |  |  |  |

#### Check Locations

No check locations defined.

### Blasted Steps Mask Shard (Coral_19b)

**Game ID:** Coral_19b

**Contributors:** skai

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | Bottom |  | [Blasted Steps Map Edge (Coral_19)](#blasted-steps-map-edge-coral19) | TL | Nothing |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Mask Shard: Blasted Steps |  | (Swift Step AND Scuttlebrace AND Faydown) OR (Cling Grip AND Spike Pogos AND (Ledge Grab OR Hazard Respawn)) |  |  | Included |  |

### Blasted Steps Shakra Room (Coral_12)

**Game ID:** Coral_12

**Contributors:** skai

#### Subrooms

- Bottom Third (Left)
- Bottom Third (Right)
- Middle Third (Bottom)
- Middle Third (Top)
- Middle Third (Entrance)
- Top Third
- Top Third (Entrance)

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BL | Bottom Left | Bottom Third (Left) | [Blasted Steps Wide Long Vertical (Coral_03)](#blasted-steps-wide-long-vertical-coral03) | BR | Nothing |  |  |  |
| R | Right | Middle Third (Entrance) | [Blasted Steps Steel Soul (Coral_37)](#blasted-steps-steel-soul-coral37) | L | Nothing |  |  |  |
| TL | Top Left | Top Third (Entrance) | [Blasted Steps Wide Long Vertical (Coral_03)](#blasted-steps-wide-long-vertical-coral03) | MR | Nothing |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BLR | Bottom Third Left to Right | Bottom Third (Left) | Bottom Third (Right) | Swift Step OR Faydown OR Clawline OR Flea Brew OR Sharpdart |  |  |  |
| BLR | Bottom Third Left to Right | Bottom Third (Right) | Bottom Third (Left) | Swift Step OR Faydown OR Clawline OR Flea Brew OR Sharpdart |  |  |  |
| BMB | Bottom to Middle Bottom | Bottom Third (Right) | Middle Third (Bottom) | ((Swift Step OR Faydown OR Clawline OR Proficient Beast OR Sharpdart) AND Cling Grip) OR (Swift Step AND Scuttlebrace AND (Enemy Pogo OR Flea Brew OR Precise Movement)) OR Silk Soar |  |  |  |
| BMB | Bottom to Middle Bottom | Middle Third (Bottom) | Bottom Third (Right) | Nothing (Falling) |  |  |  |
| MBT | Middle Bottom to Middle Top | Middle Third (Bottom) | Middle Third (Top) | ((Swift Step OR Faydown OR Clawline OR Proficient Beast OR Sharpdart) AND Cling Grip) OR (Swift Step AND Scuttlebrace AND (Enemy Pogo OR Flea Brew OR Precise Movement)) OR Silk Soar |  |  |  |
| MBT | Middle Bottom to Middle Top | Middle Third (Top) | Middle Third (Bottom) | Nothing (Falling) |  |  |  |
| MTE | Middle Top to Middle Entrance | Middle Third (Top) | Middle Third (Entrance) | ((Swift Step OR Faydown OR Clawline OR Proficient Beast OR Sharpdart) AND Cling Grip) OR (Swift Step AND Scuttlebrace AND (Enemy Pogo OR Flea Brew OR Precise Movement)) OR Silk Soar |  |  |  |
| MTE | Middle Top to Middle Entrance | Middle Third (Entrance) | Middle Third (Top) | Swift Step OR Faydown OR Clawline OR Flea Brew OR Sharpdart |  |  |  |
| MET | Middle Entrance to Top | Middle Third (Entrance) | Middle Third (Top) | ((Swift Step OR Faydown OR Clawline OR Proficient Beast OR Sharpdart) AND Cling Grip) OR (Swift Step AND Scuttlebrace AND (Enemy Pogo OR Flea Brew OR Precise Movement)) OR Silk Soar |  |  |  |
| MET | Middle Entrance to Top | Middle Third (Top) | Middle Third (Entrance) | Nothing (Falling) |  |  |  |
| TTE | Top to Top Entrance | Top Third | Top Third (Entrance) | ((Swift Step OR Faydown OR Clawline OR Proficient Beast OR Sharpdart) AND Cling Grip) OR (Swift Step AND Scuttlebrace AND (Enemy Pogo OR Flea Brew OR Precise Movement)) OR Silk Soar |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Map Purchase: Blasted Steps | Bottom Third (Right) | Swift Step OR Faydown OR Clawline OR Flea Brew OR Sharpdart |  |  | Included |  |

### Blasted Steps Shell / Beast Shard (Coral_36)

**Game ID:** Coral_36

**Contributors:** skai

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | Left |  | [Blasted Steps Thin Long Vertical (Coral_35)](#blasted-steps-thin-long-vertical-coral35) | MR | Nothing |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Beast Shard: Blasted Steps |  | (Swift Step AND Scuttlebrace AND Faydown) OR Cling Grip OR Silk Soar |  |  | Included |  |
| Shell Shard Cache: Blasted Steps #4 |  | (Swift Step AND Scuttlebrace AND Faydown) OR Cling Grip OR Silk Soar |  |  | Included |  |
| Shell Shard Cache: Blasted Steps #5 |  | (Swift Step AND Scuttlebrace AND Faydown) OR Cling Grip OR Silk Soar |  |  | Included |  |

### Blasted Steps Steel Soul (Coral_37)

**Game ID:** Coral_37

**Contributors:** skai

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | Left |  | [Blasted Steps Shakra Room (Coral_12)](#blasted-steps-shakra-room-coral12) | R | Nothing |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Silkeater: Blasted Steps |  | Nothing |  |  | Included |  |
| Wish: A Vassal Lost |  | Break Wall |  |  | Included | Steel Soul required |

### Blasted Steps Thin Long Vertical (Coral_35)

**Game ID:** Coral_35

**Contributors:** skai

#### Subrooms

- Bottom Third (Lower Half)
- Bottom Third (Upper Half)
- Middle Third (Lower Half)
- Middle Third (Upper Half)
- Top Third (Lower Half)
- Top Third (Upper Half)

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BL | Bottom Left | Bottom Third (Lower Half) | [Blasted Steps Horizontal Room with Two Sand Pits (Coral_43)](#blasted-steps-horizontal-room-with-two-sand-pits-coral43) | R | Nothing |  |  |  |
| R | Right | Bottom Third (Upper Half) | [Blasted Steps Bellway (Bellway_08)](#blasted-steps-bellway-bellway08) | L | Nothing |  |  |  |
| ML | Middle Left | Middle Third (Lower Half) | [Blasted Steps Grindle (Coral_42)](#blasted-steps-grindle-coral42) | R | Nothing |  |  |  |
| MR | Middle Right | Middle Third (Upper Half) | [Blasted Steps Shell / Beast Shard (Coral_36)](#blasted-steps-shell-beast-shard-coral36) | L | Nothing |  |  |  |
| T | Top | Top Third (Upper Half) | [Sands of Karak Tall Centre Room (Coral_35b)](#sands-of-karak-tall-centre-room-coral35b) | F | Break Wall from Coral_35b |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BLU | Bottom Lower to Upper | Bottom Third (Lower Half) | Bottom Third (Upper Half) | (Cling Grip OR (Scuttlebrace AND Swift Step) OR (Silk Soar and Ledge Grab) |  |  |  |
| BLU | Bottom Lower to Upper | Bottom Third (Upper Half) | Bottom Third (Lower Half) | Nothing (Falling) |  |  |  |
| BML | Bottom to Middle Lower | Bottom Third (Upper Half) | Middle Third (Lower Half) | (Cling Grip OR (Scuttlebrace AND Swift Step AND (Clawline OR Faydown OR Flea Brew Stall OR Sharpdart)) OR Silk Soar) |  |  |  |
| BML | Bottom to Middle Lower | Middle Third (Lower Half) | Bottom Third (Upper Half) | Nothing (Falling) |  |  |  |
| MLU | Middle Lower to Upper | Middle Third (Lower Half) | Middle Third (Upper Half) | (Cling Grip OR (Scuttlebrace AND Swift Step AND (Faydown OR Flea Brew Stall) OR Silk Soar) AND Break Wall |  |  |  |
| MLU | Middle Lower to Upper | Middle Third (Upper Half) | Middle Third (Lower Half) | Nothing (Falling) |  |  |  |
| MTL | Middle to Top Lower | Middle Third (Upper Half) | Top Third (Lower Half) | (Cling Grip OR (Scuttlebrace AND Swift Step AND (Faydown OR Flea Brew Stall) OR Silk Soar) AND Break Wall from Coral_35b |  |  |  |
| MTL | Middle to Top Lower | Top Third (Lower Half) | Middle Third (Upper Half) | Nothing (Falling) |  |  |  |
| TLU | Top Lower to Upper | Top Third (Lower Half) | Top Third (Upper Half) | Nothing (Jump) |  |  |  |
| TLU | Top Lower to Upper | Top Third (Upper Half) | Top Third (Lower Half) | Nothing (Fall) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Flea: Blasted Steps | Top Third (Upper Half) | Nothing |  |  | Included |  |

### Blasted Steps Toll Bench Bottom (Coral_02)

**Game ID:** Coral_02

**Contributors:** skai

#### Subrooms

- Bottom Right
- Middle
- Bottom Left
- Top Left
- Top Right
- Top Right Pit (Right)
- Top Right Pit (Left)

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BR | Bottom Right | Bottom Right | [Blasted Steps Map Edge (Coral_19)](#blasted-steps-map-edge-coral19) | TM | Nothing |  | Verified |  |
| TR | Top Right | Top Right | [Blasted Steps Wide Long Vertical (Coral_03)](#blasted-steps-wide-long-vertical-coral03) | BL | Nothing |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BRM | Bottom Right to Middle | Bottom Right | Middle | Swift Step OR Faydown OR Clawline OR Flea Brew OR Sharpdart |  |  |  |
| BRM | Bottom Right to Middle | Middle | Bottom Right | Nothing (Falling) |  |  |  |
| BLM | Bottom Left to Middle | Bottom Left | Middle | ((Swift Step OR Proficient Beast OR Clawline OR Sharpdart OR (Flea Brew AND Flew Brew Stall AND Ledge Grab)) AND (Faydown OR Cling Grip OR Silk Soar)) OR Scuttlebrace OR (Drifter's Cloak AND ((Faydown AND Enemy Pogo AND Ledge Grab) OR Silk Soar)) |  |  |  |
| BLM | Bottom Left to Middle | Middle | Bottom Left | Nothing (Falling) |  |  |  |
| MTL | Middle to Top Left | Middle | Top Left | ((Swift Step OR Proficient Beast OR Clawline OR Sharpdart OR (Flea Brew AND Flew Brew Stall AND Ledge Grab)) AND (Faydown OR Cling Grip OR Silk Soar)) OR Scuttlebrace OR (Drifter's Cloak AND ((Faydown AND Enemy Pogo AND Ledge Grab) OR Silk Soar)) |  |  |  |
| MTL | Middle to Top Left | Top Left | Middle | Swift Step OR Faydown OR Clawline OR Flea Brew OR Sharpdart OR Crest Pogo |  |  |  |
| TLR | Top Left to Top Right | Top Left | Top Right | ((Swift Step OR Proficient Beast OR Clawline OR Sharpdart OR (Flea Brew AND Flew Brew Stall AND Ledge Grab)) AND (Faydown OR Cling Grip OR Silk Soar)) OR Scuttlebrace OR (Drifter's Cloak AND ((Faydown AND Enemy Pogo AND Ledge Grab) OR Silk Soar)) |  |  |  |
| TLR | Top Left to Top Right | Top Right | Top Left | ((Swift Step OR Proficient Beast OR Clawline OR Sharpdart OR (Flea Brew AND Flew Brew Stall AND Ledge Grab)) AND (Faydown OR Cling Grip OR Silk Soar)) OR Scuttlebrace OR (Drifter's Cloak AND ((Faydown AND Enemy Pogo AND Ledge Grab) OR Silk Soar)) |  |  |  |
| PLT | Pit Left to Top Right | Top Right Pit (Left) | Top Right | Cling Grip OR Scuttlebrace OR Silk Soar OR (Faydown AND Ledge Grab AND (Heal Stall or Flea Brew Stall)) |  |  |  |
| PLT | Pit Left to Top Right | Top Right | Top Right Pit (Left) | Nothing (Falling) |  |  |  |
| PRT | Pit Right to Top RIght | Top Right Pit (Right) | Top Right | Cling Grip OR Scuttlebrace OR Faydown |  |  |  |
| PRT | Pit Right to Top RIght | Top Right | Top Right Pit (Right) | Nothing (Falling) |  |  |  |
| BRP | Bottom Right to Pit | Top Right Pit (Left) | Bottom Right | Nothing (Falling) |  |  |  |
| LPM | Left Pit to Middle | Top Right Pit (Left) | Middle | Hit Lever OR Crest Pogo OR Clawline OR Flea Brew OR Sharpdart OR Swift Step OR Faydown |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Memory Locket: Blasted Steps | Top Right Pit (Right) | ((Swift Step OR Proficient Beast OR Clawline OR Sharpdart) AND (Faydown OR Cling Grip)) OR (Swift Step AND Scuttlebrace) OR (Drifter's Cloak AND (Faydown OR Silk Soar) OR (Silk Soar AND Faydown) |  |  | Included |  |
| Shell Shard Cache: Blasted Steps #1 | Bottom Left | (Cling Grip AND (Swift Step OR Flea Brew OR Faydown OR Clawline)) OR (Swift Step and Scuttlebrace) |  |  | Included |  |
| Shell Shard Cache: Blasted Steps #2 | Bottom Left | (Cling Grip AND (Swift Step OR Flea Brew OR Faydown OR Clawline)) OR (Swift Step and Scuttlebrace) |  |  | Included |  |
| Shell Shard Cache: Blasted Steps #3 | Bottom Left | (Cling Grip AND (Swift Step OR Flea Brew OR Faydown OR Clawline)) OR (Swift Step and Scuttlebrace) |  |  | Included |  |

### Blasted Steps Wide Long Vertical (Coral_03)

**Game ID:** Coral_03

**Contributors:** skai

#### Subrooms

- Pit
- Bottom Third (Left)
- Bottom Third (Right)
- Middle Left (Entrance)
- Middle Right (Entrance)
- Middle Section 1
- Middle Section 2
- Top Third Entrances
- Top Third

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BL | Bottom Left | Bottom Third (Left) | [Blasted Steps Toll Bench Bottom (Coral_02)](#blasted-steps-toll-bench-bottom-coral02) | TR | Nothing |  |  |  |
| B3 | Bottom (3) | Pit | [Blasted Steps Map Edge (Coral_19)](#blasted-steps-map-edge-coral19) | TR3 | Nothing |  |  |  |
| B4 | Bottom (4) | Pit | [Blasted Steps Map Edge (Coral_19)](#blasted-steps-map-edge-coral19) | TR4 | Nothing |  |  |  |
| B5 | Bottom (5) | Pit | [Blasted Steps Map Edge (Coral_19)](#blasted-steps-map-edge-coral19) | TR5 | Nothing |  |  |  |
| B6 | Bottom (6) | Pit | [Blasted Steps Map Edge (Coral_19)](#blasted-steps-map-edge-coral19) | TR6 | Nothing |  |  |  |
| B7 | Bottom (7) | Pit | [Blasted Steps Map Edge (Coral_19)](#blasted-steps-map-edge-coral19) | TR7 | Nothing |  |  |  |
| B8 | Bottom (8) | Pit | [Blasted Steps Map Edge (Coral_19)](#blasted-steps-map-edge-coral19) | TR8 | Nothing |  |  |  |
| BR | Bottom Right | Bottom Third (Right) | [Blasted Steps Shakra Room (Coral_12)](#blasted-steps-shakra-room-coral12) | BL | Nothing |  |  |  |
| ML | Middle Left | Middle Left (Entrance) | [Great Conchflies (Coral_11)](#great-conchflies-coral11) | R | Nothing |  |  |  |
| MR | Middle Right | Middle Right (Entrance) | [Blasted Steps Shakra Room (Coral_12)](#blasted-steps-shakra-room-coral12) | TL | Nothing |  |  |  |
| TR | Top Right | Top Third Entrances | [Pre Last Judge Room (Coral_32)](#pre-last-judge-room-coral32) | L | Nothing |  |  |  |
| TL | Top Left | Top Third Entrances | [Blasted Steps Bellway (Bellway_08)](#blasted-steps-bellway-bellway08) | R | Nothing |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BLR | Bottom Left to Right | Bottom Third (Left) | Bottom Third (Right) | Swift Step OR Faydown OR Enemy Pogo OR Silk Soar OR Clawline OR (Flea Brew AND (Crest Pogo OR Flew Brew Stall)) |  |  |  |
| BLR | Bottom Left to Right | Bottom Third (Right) | Bottom Third (Left) | Swift Step OR Faydown OR Enemy Pogo OR Silk Soar OR Clawline OR (Flea Brew AND (Crest Pogo OR Flew Brew Stall)) |  |  |  |
| BLM | Bottom Left to Middle 1 | Bottom Third (Left) | Middle Section 1 | ((Enemy Pogo AND Faydown AND Ledge Grab) OR (Swift Step OR Faydown OR Clawline OR Drifter's Cloak OR Enemy Pogo OR (Flea Brew AND (Crest Pogo OR Flea Brew Stall)) AND CLING) OR (Swift Step AND Scuttlebrace AND Faydown) OR Silk Soar |  |  |  |
| BLM | Bottom Left to Middle 1 | Middle Section 1 | Bottom Third (Left) | Nothing (Falling) |  |  |  |
| BRM | Bottom Right to Middle | Bottom Third (Right) | Middle Section 1 | ((Enemy Pogo AND Faydown AND Ledge Grab) OR (Swift Step OR Faydown OR Clawline OR Drifter's Cloak OR Enemy Pogo OR (Flea Brew AND (Crest Pogo OR Flea Brew Stall)) AND CLING) OR (Swift Step AND Scuttlebrace AND Faydown) OR Silk Soar |  |  |  |
| BRM | Bottom Right to Middle | Middle Section 1 | Bottom Third (Right) | Nothing (Falling) |  |  |  |
| M12 | Middle 1 to Middle 2 | Middle Section 1 | Middle Section 2 | Nothing (Jumping) |  |  |  |
| M12 | Middle 1 to Middle 2 | Middle Section 2 | Middle Section 1 | Nothing (Falling) |  |  |  |
| MLE | Middle to Middle Left | Middle Section 2 | Middle Left (Entrance) | Enemy Pogo OR Silk Soar OR Swift Step OR Clawline OR Sharpdart (Drifter's Cloak AND Ledge Grab) OR (Flea Brew AND (Cling OR Flea Brew Stall OR Heal Stall)) |  |  |  |
| MLE | Middle to Middle Left | Middle Left (Entrance) | Middle Section 2 | Enemy Pogo OR Swift Step OR Clawline OR Sharpdart OR Drifter's Cloak OR Faydown OR Flea Brew OR Silk Soar OR (Crest Pogo and Cling Grip) |  |  |  |
| MRE | Middle to Middle Right | Middle Section 2 | Middle Right (Entrance) | (Easy Skip AND Drifter's Cloak) OR (Easy Skip AND Swift Step AND Clawline AND Cling AND Ledge Grab) OR (Faydown AND ((Swift Step AND Ledge Grab) OR (Drifter's Cloak AND Wind AND Ledge Grab) OR Clawline)) OR Silk Soar |  |  |  |
| MRE | Middle to Middle Right | Middle Right (Entrance) | Middle Section 2 | Nothing (Falling) |  |  |  |
| PTB | Pit to Bottom | Pit | Bottom Third (Left) | Cling Grip OR Scuttle OR Silk Soar |  |  |  |
| PTB | Pit to Bottom | Bottom Third (Left) | Pit | Nothing (Falling) |  |  |  |
| MRT | Middle Right to Top | Middle Right (Entrance) | Top Third | Ledge Grab OR Cling Grip OR Faydown OR Silk Soar OR Scuttle |  |  |  |
| MRT | Middle Right to Top | Top Third | Middle Right (Entrance) | Nothing (Falling) |  |  |  |
| TTE | Top Third to Entrances | Top Third | Top Third Entrances | (Ledge Grab AND (Cling Grip OR (Scuttlebrace AND Proficient Movement)) AND ((Lever Hit AND Flea Brew) OR Swift Step OR Clawline)) OR Silk Soar |  |  |  |
| TTE | Top Third to Entrances | Top Third Entrances | Top Third | Nothing (Falling) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Frayed Rosary String: Blasted Steps | Pit | Nothing (Falling) |  |  | Included |  |
| Lever | Top Third | Ledge Grab AND (Cling Grip OR Scuttlebrace) OR Faydown OR Silk Soar |  |  | Included |  |

### Great Conchflies (Coral_11)

**Game ID:** Coral_11

**Contributors:** skai

#### Subrooms

- Great Conchflies
- Triple Sand Pit Right
- Triple Sand Pit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | Right | Triple Sand Pit Right | [Blasted Steps Wide Long Vertical (Coral_03)](#blasted-steps-wide-long-vertical-coral03) | ML | Nothing |  |  |  |
| L | Left | Great Conchflies | [Horizontal Room with Sand Pit (Coral_11b)](#horizontal-room-with-sand-pit-coral11b) | R | Beat Great Conchflies |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TSC | Triple Sand Pit to Conch | Triple Sand Pit | Great Conchflies | Swift Step OR Faydown OR Clawline OR Drifter's Cloak OR Beast Crest OR Sharpdart (Flea Brew AND (Flea Brew Stall OR Heal Stall OR Ledge Grab)) |  |  |  |
| TSC | Triple Sand Pit to Conch | Great Conchflies | Triple Sand Pit | Nothing |  |  |  |
| TSR | Triple Sand Pit to Right | Triple Sand Pit | Triple Sand Pit Right | Swift Step OR Faydown OR Clawline OR Drifter's Cloak OR Beast Crest OR Sharpdart (Flea Brew AND (Flea Brew Stall OR Heal Stall OR Ledge Grab)) |  |  |  |
| TSR | Triple Sand Pit to Right | Triple Sand Pit Right | Triple Sand Pit | Nothing |  |  |  |

#### Check Locations

No check locations defined.

### Horizontal Room with Sand Pit (Coral_11b)

**Game ID:** Coral_11b

**Contributors:** skai

#### Subrooms

- Sand Pit Left
- Sand Pit Right

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | Right | Sand Pit Right | [Great Conchflies (Coral_11)](#great-conchflies-coral11) | L | Nothing |  |  |  |
| L | Left | Sand Pit Left | [Windy Pinstress Entrance (Coral_34)](#windy-pinstress-entrance-coral34) | R | Nothing |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SP | Sand Pit | Sand Pit Left | Sand Pit Right | Swift Step OR Faydown OR Clawline OR Drifter's Cloak OR Beast Crest OR Sharpdart (Flea Brew AND (Flea Brew Stall OR Heal Stall OR Ledge Grab)) |  |  |  |
| SP | Sand Pit | Sand Pit Right | Sand Pit Left | Swift Step OR Faydown OR Clawline OR Drifter's Cloak OR Beast Crest OR Sharpdart (Flea Brew AND (Flea Brew Stall OR Heal Stall OR Ledge Grab)) |  |  |  |

#### Check Locations

No check locations defined.

### Last Judge Arena (Coral_Judge_Arena)

**Game ID:** Coral_Judge_Arena

**Contributors:** skai

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | Left |  | [Pre Last Judge Room (Coral_32)](#pre-last-judge-room-coral32) | R | Nothing |  |  |  |
| R | Right |  | Coral_10 | L | Beat Last Judge and 5 Bells |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Lumble the Lucky (Coral_33)

**Game ID:** Coral_33

**Contributors:** skai

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | Right |  | [Blasted Steps Horizontal Room with Two Sand Pits (Coral_43)](#blasted-steps-horizontal-room-with-two-sand-pits-coral43) | L | Nothing |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Magnetite Dice |  | Prior to defeating the Cogwork Dancers or obtaining the Clawline: Given by Lumble the Lucky if you win against him after he runs out of Rosaries.  After defeating the Cogwork Dancers or obtaining the Clawline: Found next to Lumble's body.  Act 3: Sold by Grindle for Rosaries 300. |  |  | Included |  |

### Pinstress Room (Room_Pinstress)

**Game ID:** Room_Pinstress

**Contributors:** skai

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | Left |  | [Windy Pinstress Entrance (Coral_34)](#windy-pinstress-entrance-coral34) | C | Nothing |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Pre Last Judge Room (Coral_32)

**Game ID:** Coral_32

**Contributors:** skai

#### Subrooms

- Ascension
- Intermission
- Descent
- Top (Entrance)
- Right (Entrance)
- Top Vertical Shaft
- Top Right
- Left (Entrance)

- **Ascension:** This shouldn't actually cover the Craftmetal but there's no way to make an oblong room.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | Left | Left (Entrance) | [Blasted Steps Wide Long Vertical (Coral_03)](#blasted-steps-wide-long-vertical-coral03) | TR | Nothing |  |  |  |
| T | Top | Top (Entrance) | [Sands of Karak Elevator to Blasted Steps (Coral_38)](#sands-of-karak-elevator-to-blasted-steps-coral38) | F | ((Swift Step OR Faydown OR Clawline OR Drifter's Cloak OR (Flea Brew AND Ledge Grab)) AND Cling Grip) OR Silk Soar |  |  |  |
| R | Right | Right (Entrance) | [Last Judge Arena (Coral_Judge_Arena)](#last-judge-arena-coraljudgearena) | L | ((Swift Step OR Faydown OR Clawline OR Drifter's Cloak OR (Flea Brew AND Ledge Grab)) AND Cling Grip) OR Silk Soar |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LTA | Left to Ascension | Left (Entrance) | Ascension | Nothing |  |  |  |
| LTA | Left to Ascension | Ascension | Left (Entrance) | ((Swift Step OR Faydown OR Clawline OR Drifter's Cloak OR (Flea Brew AND Ledge Grab)) AND Cling Grip) OR Silk Soar |  |  |  |
| ATI | Ascension to Intermission | Ascension | Intermission | ((Swift Step OR Faydown OR Clawline OR Drifter's Cloak OR (Flea Brew AND Ledge Grab)) AND Cling Grip) OR Silk Soar |  |  |  |
| ATI | Ascension to Intermission | Intermission | Ascension | Nothing (Fall) |  |  |  |
| ITR | Intermission to Top Right | Intermission | Top Right | Nothing (Fall) |  |  |  |
| ITR | Intermission to Top Right | Top Right | Intermission | ((Swift Step OR Faydown OR Clawline OR Drifter's Cloak OR (Flea Brew AND Ledge Grab)) AND Cling Grip) OR Silk Soar |  |  |  |
| TRD | Top Right to Descent | Top Right | Descent | Nothing (Fall) |  |  |  |
| TRD | Top Right to Descent | Descent | Top Right | ((Swift Step OR Faydown OR Clawline OR Drifter's Cloak OR (Flea Brew AND Ledge Grab)) AND Cling Grip) OR Silk Soar |  |  |  |
| TRV | Top Right to Top Vertical | Top Right | Top Vertical Shaft | ((Swift Step OR Faydown OR Clawline OR Drifter's Cloak OR (Flea Brew AND Ledge Grab)) AND Cling Grip) OR Silk Soar |  |  |  |
| TRV | Top Right to Top Vertical | Top Vertical Shaft | Top Right | Nothing (Fall) |  |  |  |
| VTE | Top Vertical to Top (Entrance) | Top Vertical Shaft | Top (Entrance) | Cling Grip OR Silk Soar |  |  |  |
| VTE | Top Vertical to Top (Entrance) | Top (Entrance) | Top Vertical Shaft | Nothing (Fall) |  |  |  |
| TRE | Top Right to Right (Entrance) | Top Right | Right (Entrance) | ((Swift Step OR Faydown OR Clawline OR Drifter's Cloak OR (Flea Brew AND Ledge Grab)) AND Cling Grip) OR Silk Soar |  |  |  |
| TRE | Top Right to Right (Entrance) | Right (Entrance) | Top Right | Nothing (Fall) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Craftmetal: Blasted Steps | Descent | ((Swift Step OR Faydown OR Clawline OR Drifter's Cloak OR (Flea Brew AND Ledge Grab)) AND Cling Grip) OR Silk Soar |  |  | Included |  |

### Windy Pinstress Entrance (Coral_34)

**Game ID:** Coral_34

**Contributors:** skai

#### Subrooms

- Lower Third
- Middle Third
- Upper Third

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | Right | Lower Third | [Horizontal Room with Sand Pit (Coral_11b)](#horizontal-room-with-sand-pit-coral11b) | L | Nothing |  |  |  |
| C | Center | Middle Third | [Pinstress Room (Room_Pinstress)](#pinstress-room-roompinstress) | L | Nothing (Falling) |  |  |  |
| T | Top | Upper Third | [Sands of Karak Entrance (Coral_25)](#sands-of-karak-entrance-coral25) | F | Cling Grip OR (Scuttlebrace AND Faydown) OR Silk Soar |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LTC | Lower to Center | Lower Third | Middle Third | Clawline  OR (Flea Brew AND (Faydown OR (Swift Step AND Ledge Grab) OR (Beast Crest AND Ledge Grab))) |  |  |  |
| LTC | Lower to Center | Middle Third | Lower Third | Nothing (Falling) |  |  |  |
| CTT | Center to Top | Middle Third | Upper Third | (Clawline AND (Cling Grip OR Scuttlebrace) AND 2 Silk Hearts) OR (Clawline AND Cling Grip AND (Faydown OR (Beast Crest AND Ledge Grab))) |  |  |  |
| CTT | Center to Top | Upper Third | Middle Third | Nothing (Falling) |  |  |  |

#### Check Locations

No check locations defined.

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

## Sinner's Road

### Sinner's Road Bench (Dust_10)

**Game ID:** Dust_10

**Contributors:** herchey

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right |  | [Sinner's Road Vertical Hall West (Dust_02)](#sinners-road-vertical-hall-west-dust02) | ML | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Rosary Cache: Sinner’s Road #8 |  | Silk soar OR (Faywing cloak AND cling grip) |  |  | Included |  |
| Map Purchase: Sinner's Road |  | Silk Soar OR (crest pogo AND (swim OR ledge grab)) |  |  | Included |  |

### Sinner's Road Chef's Kitchen (Dust_Chef)

**Game ID:** Dust_Chef

**Contributors:** herchey

#### Subrooms

- lower
- upper
- basement

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | lower | [Sinner's Road Hanging Cages (Dust_04)](#sinners-road-hanging-cages-dust04) | R | none |  |  |  |
| H | hatch | basement | [Sinner's Road Muckroach Cages (Dust_03)](#sinners-road-muckroach-cages-dust03) | C | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LU | lower to upper | lower | upper | faydown cloak OR silk soar |  |  |  |
| LU | lower to upper | upper | lower | none |  |  |  |
| BL | basement to lower | basement | lower | scuttlebrace OR cling grip OR silk soar |  |  |  |
| BL | basement to lower | lower | basement | none (IMPOSSIBLE!!!) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Boss: Disgraced Chef Lugoli | upper | Silk soar OR faydown cloak |  |  | Included |  |

### Sinner's Road Entrance (Dust_01)

**Game ID:** Dust_01

**Contributors:** herchey

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left |  | TODO |  | ledge grab | TODO |  |  |
| R | right |  | [Sinner's Road Vertical Hall West (Dust_02)](#sinners-road-vertical-hall-west-dust02) | LL | ledge grab |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Frayed Rosary String: Sinner's Road |  | left attack |  |  | Included |  |

### Sinner's Road Flea Rescue (Dust_12)

**Game ID:** Dust_12

**Contributors:** herchey

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [Sinner's Road Vertical Hall East (Dust_06)](#sinners-road-vertical-hall-east-dust06) | MR | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Flea: Sinner's Road |  | left attack |  |  | Included |  |

### Sinner's Road Hanging Cages (Dust_04)

**Game ID:** Dust_04

**Contributors:** herchey

#### Subrooms

- lower entry
- right ledge
- shard ledge
- upper entry
- shack

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LL | lower left | lower entry | [Sinner's Road Vertical Hall West (Dust_02)](#sinners-road-vertical-hall-west-dust02) | MR | none |  |  |  |
| R | right | right ledge | [Sinner's Road Chef's Kitchen (Dust_Chef)](#sinners-road-chefs-kitchen-dustchef) | L | none |  |  |  |
| UL | upper left | upper entry | [Sinner's Road Vertical Hall West (Dust_02)](#sinners-road-vertical-hall-west-dust02) | UR | none |  |  |  |
| S | shack | shack | [Sinner's Road Shack (dust_shack)](#sinners-road-shack-dustshack) | L | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| RSL | right ledge to shard ledge | right ledge | shard ledge | Faydown cloak OR silk soar OR (cling grip AND crest pogo AND (clawline OR sharpdart)) |  |  |  |
| RSL | right ledge to shard ledge | shard ledge | right ledge | none |  |  |  |
| UES | upper entry to shack | upper entry | shack | Clawline OR ((Cling grip OR silk soar) AND crest pogo AND (drifter’s cloak OR sharpdart)) |  |  |  |
| UES | upper entry to shack | shack | upper entry | Run AND (faydown cloak OR clawline OR sharpdart) |  |  |  |
| RLS | right ledge to shack | right ledge | shack | silk soar |  |  |  |
| RLS | right ledge to shack | shack | right ledge | none |  |  |  |
| LRL | lower entry to right ledge | lower entry | right ledge | Clawline OR (crest pogo AND (cling grip OR ledge grab OR silk soar OR hunter’s crest OR beast crest OR architect’s crest OR shaman’s crest OR reaper’s crest)) |  |  |  |
| LRL | lower entry to right ledge | right ledge | lower entry | Crest pogo OR swim OR clawline |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Wish: My Missing Brother | upper entry | Complete My Missing Courier Wish |  |  | Included |  |
| Shell Shard Cache: Sinner’s Road #4 | shard ledge | none |  |  | Included |  |
| Shell Shard Cache: Sinner’s Road #5 | shard ledge | none |  |  | Included |  |

### Sinner's Road Muckroach Cages (Dust_03)

**Game ID:** Dust_03

**Contributors:** herchey

#### Subrooms

- left half
- right half

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | ceiling | right half | [Sinner's Road Chef's Kitchen (Dust_Chef)](#sinners-road-chefs-kitchen-dustchef) | H | (faydown cloak AND cling grip) OR silk soar |  |  |  |
| LR | lower right | right half | [Sinner's Road Spike Basement (Dust_Barb)](#sinners-road-spike-basement-dustbarb) | C | none |  |  |  |
| L | left | left half | [Sinner's Road Vertical Hall West (Dust_02)](#sinners-road-vertical-hall-west-dust02) | LR | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LR | left to right | left half | right half | none |  |  |  |
| LR | left to right | right half | left half | Cling grip OR ledge grab OR silk soar OR dash OR crest pogo OR faydown cloak |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Shell Shard Cache: Sinner’s Road #1 | left half | Silk soar OR ledge grab OR cling grip OR faydown cloak | TODO |  | Included | Check subroom |
| Shell Shard Cache: Sinner’s Road #2 | left half | Silk soar OR ledge grab OR cling grip OR faydown cloak | TODO |  | Included |  |
| Shell Shard Cache: Sinner’s Road #3 | left half | Silk soar OR ledge grab OR cling grip OR faydown cloak | TODO |  | Included |  |
| Rosary Cache: Sinner’s Road #4 | left half | Ledge grab OR silk soar OR faydown cloak OR scuttlebrace | TODO |  | Included |  |

### Sinner's Road North Hall (Dust_05)

**Game ID:** Dust_05

**Contributors:** herchey

#### Subrooms

- behind left wall
- left area
- middle area
- right door platform
- hatch

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | behind left wall | TODO |  | none |  |  |  |
| C | center | hatch | [Sinner's Road Vertical Hall West (Dust_02)](#sinners-road-vertical-hall-west-dust02) | C | none |  |  |  |
| R | right | right door platform | [Sinner's Road Vertical Hall East (Dust_06)](#sinners-road-vertical-hall-east-dust06) | L | faydown cloak OR (crest pogo AND drifter’s cloak) OR (clawline AND (ledge grab OR cling grip) |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LWL | Behind left wall to left area | behind left wall | left area | right attack |  |  |  |
| LWL | Behind left wall to left area | left area | behind left wall | Left attack AND (Silk soar OR faydown cloak OR cling grip OR scuttlebrace) |  |  |  |
| LAM | Left area to middle area | left area | middle area | clawline OR crest pogo OR (sharpdart AND 12 silk AND (drifter’s cloak OR faydown cloak)) OR (drifter’s cloak AND ((cling grip AND ledge grab) OR faydown cloak)) OR (swim and ledge grab) |  |  |  |
| LAM | Left area to middle area | middle area | left area | clawline OR crest pogo OR (sharpdart AND (drifter’s cloak OR faydown cloak)) OR (drifter’s cloak AND faydown cloak) OR (swim and (ledge grab OR cling grip)) |  |  |  |
| MAH | Middle area to hatch | middle area | hatch | none |  |  | Technically "any attack" is the requirement |
| MAH | Middle area to hatch | hatch | middle area | Ledge grab OR cling grip OR faydown cloak OR silk soar |  |  |  |
| MAR | Middle area to right door platform | middle area | right door platform | (swim AND faydown cloak) OR (clawline AND (drifter’s cloak OR sharpdart OR rest pogo)) OR (drifter’s cloak AND (sharpdart OR crest pogo)) OR (sharpdart AND crest pogo) |  |  |  |
| MAR | Middle area to right door platform | right door platform | middle area | Crest pogo OR swim OR (drifter’s cloak AND (run OR dash OR ledge grab OR sharpdart OR clawline OR faydown cloak)) OR (run AND (faydown cloak OR sharpdart OR clawline)) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Shell Shard Cache: Sinner’s Road #6 | left area | swim |  |  | Included |  |
| Shell Shard Cache: Sinner’s Road #7 | left area | swim |  |  | Included |  |

### Sinner's Road Spike Basement (Dust_Barb)

**Game ID:** Dust_Barb

**Contributors:** herchey

#### Subrooms

- upper
- lower

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | ceiling | upper | [Sinner's Road Muckroach Cages (Dust_03)](#sinners-road-muckroach-cages-dust03) | LR | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| UL | Upper to lower | upper | lower | none |  |  |  |
| UL | Upper to lower | lower | upper | Silk soar OR cling grip |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Barbed Bracelet | lower | none |  |  | Included |  |

### Sinner's Road Styx Room (Dust_11)

**Game ID:** Dust_11

**Contributors:** herchey

#### Subrooms

- left
- right
- cage

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | left | [Sinner's Road Vertical Hall East (Dust_06)](#sinners-road-vertical-hall-east-dust06) | LR | none |  |  |  |
| B | basement | cage | TODO |  | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LR | left to right | left | right | (Swim OR (reaper’s crest AND ledge grab) OR architect’s crest OR beast crest OR hunter’s crest) AND right attack |  |  |  |
| LR | left to right | right | left | Spike pogo OR Faydown cloak OR (silk soar AND drifter’s cloak) OR (cling grip AND (sharpdart OR clawline OR dash)) (impossible without left to right first) |  |  |  |
| CR | cage to right | cage | right | right attack |  |  |  |
| CR | cage to right | right | cage | None (impossible without cage to right first) |  |  |  |

#### Check Locations

No check locations defined.

### Sinner's Road Vertical Hall East (Dust_06)

**Game ID:** Dust_06

**Contributors:** herchey

#### Subrooms

- lower
- middle
- upper

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | upper | [Sinner's Road North Hall (Dust_05)](#sinners-road-north-hall-dust05) | R | none |  |  |  |
| LR | lower right | lower | [Sinner's Road Styx Room (Dust_11)](#sinners-road-styx-room-dust11) | L | none |  |  |  |
| MR | middle right | upper | [Sinner's Road Flea Rescue (Dust_12)](#sinners-road-flea-rescue-dust12) | L | none |  |  |  |
| UR | upper right | upper | [Bilewater Entrance (Shadow_05)](#bilewater-entrance-shadow05) | L | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Rosary Cache: Sinner’s Road #5 | upper | none |  |  | Included |  |
| Rosary Cache: Sinner’s Road #6 | upper | none |  |  | Included |  |
| Rosary Cache: Sinner’s Road #7 | upper | none |  |  | Included |  |
| Shard Bundle: Sinner’s Road | upper | Ledge grab OR cling grip OR faydown cloak OR silk soar OR scuttlebrace |  |  | Included |  |
| Simple Key: Roachkeeper | upper | Cling grip AND (dash OR drifter’s cloak OR clawline OR sharpdart) |  |  | Included |  |

### Sinner's Road Vertical Hall West (Dust_02)

**Game ID:** Dust_02

**Contributors:** herchey

#### Subrooms

- basement
- lower
- middle right
- middle left
- upper right
- top

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LL | lower left | lower | [Sinner's Road Entrance (Dust_01)](#sinners-road-entrance-dust01) | R | none |  |  |  |
| ML | middle left | middle left | [Sinner's Road Bench (Dust_10)](#sinners-road-bench-dust10) | R | none |  |  |  |
| C | ceiling | top | [Sinner's Road North Hall (Dust_05)](#sinners-road-north-hall-dust05) | C | none |  |  |  |
| LR | lower right | lower | [Sinner's Road Muckroach Cages (Dust_03)](#sinners-road-muckroach-cages-dust03) | L | none |  |  |  |
| MR | middle right | middle right | [Sinner's Road Hanging Cages (Dust_04)](#sinners-road-hanging-cages-dust04) | LL | none |  |  |  |
| UR | upper right | top | [Sinner's Road Hanging Cages (Dust_04)](#sinners-road-hanging-cages-dust04) | UL | none |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BL | basement to lower | lower | basement | none |  |  | Technically "any attack" is a requirement |
| BL | basement to lower | basement | lower | cling grip |  |  |  |
| LMR | low to mid right | lower | middle right | noneCling grip OR silk soar OR (scuttlebrace AND faydown cloak) |  |  |  |
| LMR | low to mid right | middle right | lower | none |  |  |  |
| MRL | mid right to mid left | middle right | middle left | silk soar |  |  |  |
| MRL | mid right to mid left | middle left | middle right | none |  |  |  |
| LUR | mid left to upper right | middle left | upper right | Cling grip OR faydown cloak |  |  |  |
| LUR | mid left to upper right | upper right | middle left | none |  |  |  |
| URT | upper right to top | upper right | top | Silk soar OR (cling grip AND crest pogo |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Rosary Cache: Sinner’s Road #1 | lower | Ledge grab OR cling grip OR faydown cloak |  |  | Included |  |
| Rosary Cache: Sinner’s Road #2 | upper right | none |  |  | Included |  |
| Rosary Cache: Sinner’s Road #3 | upper right | none |  |  | Included |  |

### Sinner's Road Shack (dust_shack)

**Game ID:** dust_shack

**Contributors:** herchey

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [Sinner's Road Hanging Cages (Dust_04)](#sinners-road-hanging-cages-dust04) | S | none |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Tacks |  | Complete Roach Guts OR reach act 3 |  |  | Included |  |

## The Mist

### Mist Entrance (Dust_Maze_09_entrance)

**Game ID:** Dust_Maze_09_entrance

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | Right |  | Dust_05 |  | Nothing |  |  |  |
| L | Left |  | :) | R | Nothing |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### The Mist Room 5 (Dust_Maze_05)

**Game ID:** Dust_Maze_05

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | Left |  | ? | ? |  |  |  |  |
| UR | Upper Right |  | ? | L |  |  |  |  |
| T | Top |  | ? | ? |  |  |  |  |
| B | Bottom |  | ? | ? |  |  |  |  |
| LR | Right |  | ? | ? |  |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

## Underworks

### Vaults Cauldron Entrance (Library_11)

**Game ID:** Library_11

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TL | left1 |  | [Trobbio (Library_13)](#trobbio-library13) | BR |  | TODO |  |  |
|  | left2 |  | [Grand Bellway (Bellway_City)](#grand-bellway-bellwaycity) | R |  | TODO |  |  |
|  | right2 |  | TODO |  |  | TODO |  |  |
|  | left3 |  | TODO |  |  | TODO |  |  |
|  | right1 |  | TODO |  |  | TODO |  |  |
|  |  |  | TODO |  |  | TODO |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
|  |  |  | TODO |  | Included |  |

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
| T | top1 | Secret | [Whiteward Unravelled Arena Room (Ward_02)](#whiteward-unravelled-arena-room-ward02) | B | none | TODO |  | has to be checked from white ward |
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

### Library_12b (Library_12b-0)

**Game ID:** Library_12b-0

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | Top |  | [Vaultkeeper Cauldron Entrance (Library_10)](#vaultkeeper-cauldron-entrance-library10) | B | ??? | TODO |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

## Choral Chambers

### Bellshrine_Enclave (Bellshrine_Enclave)

**Game ID:** Bellshrine_Enclave

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  | left1 |  | [Songclave (Song_Enclave)](#songclave-songenclave) | D |  |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### High Halls Entrance (Hang_01)

**Game ID:** Hang_01

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BR | right2 |  | [Corridor to High Halls (Song_17)](#corridor-to-high-halls-song17) | L | none |  | Verified |  |
| TP | right1 |  | [High Halls Small Slide (Hang_02)](#high-halls-small-slide-hang02) | L | clawline and (spike pogo or faydown cloak) or silk soar |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Songclave (Song_Enclave)

**Game ID:** Song_Enclave

#### Subrooms

- Base
- Top Platform

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BL | left2 | Base | [Songclave Steam Tunnel (Library_02)](#songclave-steam-tunnel-library02) | TR | none |  | Verified |  |
| TL | left1 | Top Platform | [Memorium Entrance Tunnel (Song_25)](#memorium-entrance-tunnel-song25) | R | none |  | Verified |  |
| B | bot1 | Base | [Whispering Vaults Hell (Library_04)](#whispering-vaults-hell-library04) | T | none |  | Verified |  |
| T | top1 | Top Platform | [Songclave Tube (Song_Enclave_Tube)](#songclave-tube-songenclavetube) | B | none |  | Verified |  |
| D | door1 | Base | TODO |  | none | TODO | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | Base | Top Platform | silk soar or cling grip |  | Verified |  |
| V | Vertical | Top Platform | Base | none |  | Verified | falling |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| White Key | Base | none |  |  | Included |  |

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
| T | top1 |  | [High Halls Vault (Hang_06)](#high-halls-vault-hang06) | B | one way entrance, opens from the other side |  | Verified | one way entrance, opens from the other side |

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
| L | left1 |  | [High Halls Entrance (Hang_01)](#high-halls-entrance-hang01) | BR |  |  |  |  |

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

#### Subrooms

- Section 1
- Section 2
- Section 3
- Section 4

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L1 | left5 | Section 1 | [Choral Chambers Below Spa (Song_02)](#choral-chambers-below-spa-song02) | R | none |  | Verified |  |
| R1 | right3 | Section 1 | [Whiteward Entrance (Ward_01)](#whiteward-entrance-ward01) | TL | none |  | Verified |  |
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
| RS | right5 | Right Stage | [Trobbio (Library_13)](#trobbio-library13) | L | none |  |  |  |
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

### Whispering Vaults Hell (Library_04)

**Game ID:** Library_04

**Contributors:** rebelslayer

#### Subrooms

- Ground
- Lowest Hallway
- Middle Hallway
- Upper Platform
- Map Room
- Top Hallway
- Upper Low Hallway
- Rosary Dish
- Left Side Shaft
- Lever
- Distant Platform
- Shortcut Box
- Shortcut Box (Moved)

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | Top | Map Room | [Songclave (Song_Enclave)](#songclave-songenclave) | B | Nothing. |  |  |  |
| HR | High Right | Distant Platform | [Whispering Vaults Silkeater (Library_14)](#whispering-vaults-silkeater-library14) | L | Nothing. |  |  |  |
| CR | Center Right | Middle Hallway | [Whispering Vaults East To West (Library_05)](#whispering-vaults-east-to-west-library05) | TL | Nothing. |  |  |  |
| BL | Bottom Left | Lowest Hallway | [Whispering Vaults Music Box (Library_16)](#whispering-vaults-music-box-library16) | R | Nothing. |  |  |  |
| CL | Center Left | Middle Hallway | [Trobbio Entrance (Library_13b)](#trobbio-entrance-library13b) | R | Nothing. |  |  |  |
| LL | Low Left | Left Side Shaft | [Whispering Vaults Flea Shaft (Library_01)](#whispering-vaults-flea-shaft-library01) | BR | Nothing. |  |  |  |
| LR | Low Right | Upper Platform | [Whispering Vaults East To West (Library_05)](#whispering-vaults-east-to-west-library05) | BL | Nothing. |  |  |  |
| TR | Top Right | Top Hallway | [Whispering Vaults Jumps (Library_09)](#whispering-vaults-jumps-library09) | L | Nothing. |  |  |  |
| TL | Top Left | Top Hallway | [Whispering Vaults Flea Shaft (Library_01)](#whispering-vaults-flea-shaft-library01) | TR | Nothing. |  |  |  |
| BR | Bottom Right | Ground | [Vaultkeeper Cauldron Entrance (Library_10)](#vaultkeeper-cauldron-entrance-library10) | L | Nothing. |  |  |  |
| MHR | Mid High Right | Upper Platform | [Whispering Vaults Bench (Library_08)](#whispering-vaults-bench-library08) | L | Nothing. |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| A1 | Ascent 1 | Ground | Lowest Hallway | Silk Soar OR Ledge Grab OR Clawline OR Faydown Cloak OR Cling Grip |  |  |  |
| BR | BL to LR | Lowest Hallway | Upper Low Hallway | Silk Soar OR Enemy Pogo/Ledge Grab/Clawline/Faydown Cloak/Sprint/Cling Grip/Scuttlebrace |  |  |  |
| CR | Collect Rosaries | Lever | Rosary Dish | Sprint/Dash/Clawline/Drifter's Cloak/Faydown Cloak/Cling Grip/Scuttlebrace/Sharp Dart/Beast Pogo/Beast Charge/Architect Pogo/Architect Charge |  |  |  |
| PR! | Progresion! | Left Side Shaft | Lever | Silk Soar OR Cling Grip OR Scuttlebrace |  |  |  |
| MP! | More Progression! | Lever | Upper Platform | Silk Soar OR Cling Grip OR Scuttlebrace OR Faydown Cloak AND Ledge Grab/Clawline/Shaman Pogo |  |  |  |
| EMP | Even More Progression! | Upper Platform | Distant Platform | Silk Soar OR Cling Grip/Scuttlebrace AND Clawline/(Sprint/Dash/Drifter's Cloak AND Ledge Grab)/Faydown Cloak |  |  |  |
| LP! | Last Push! | Distant Platform | Top Hallway | Silk Soar OR Cling Grip OR Scuttlebrace AND |  |  |  |
| MT! | Map Time! | Top Hallway | Map Room | Silk Soar OR Cling Grip OR Scuttlebrace AND Enemy Pogo/Faydown Cloak |  |  |  |
| MT! | Map Time! | Map Room | Top Hallway | Nothing. (fall) |  |  |  |
| LP! | Last Push! | Top Hallway | Distant Platform | Nothing. Fall) |  |  |  |
| EMP | Even More Progression! | Distant Platform | Upper Platform | Nothing. (Fall) |  |  |  |
| MP! | More Progression! | Upper Platform | Lever | Silk Soar OR Cling Grip OR Scuttlebrace |  |  | accounting for the fact the player may not have activated the shortcut |
| PR! | Progresion! | Lever | Left Side Shaft | Nothing. (Fall) |  |  |  |
| BR | BL to LR | Upper Low Hallway | Lowest Hallway | Nothing. (Fall) |  |  |  |
| A1 | Ascent 1 | Lowest Hallway | Ground | Nothing. (Fall) |  |  |  |
| US | Unlock Shortc8ut9 | Shortcut Box | Shortcut Box (Moved) | (Nothing? not sure, forgot to test if you can hit it from the ledge.) Ledge Grab OR Cling Grip OR Faydown Cloak OR Clawline OR Sharp Dart OR Beast Pogo OR Beast Charge OR Architect Charge |  |  |  |
| US2 | Use Shortcut | Shortcut Box (Moved) | Middle Hallway | Nothing. (Fall) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Lever: Whispering Vaults #6 | Distant Platform | Nothing. |  |  | Included |  |
| Lever: Whispering Vaults #7 | Lever | Nothing. |  |  | Included |  |
| Ladder #3 | Top Hallway | Nothing. |  |  | Included |  |
| Map Station | Map Room | Nothing. |  |  | Included |  |
| Breakable Floor | Map Room | Nothing. |  |  | Included |  |
| Rosary Dish #5 | Rosary Dish | Nothing. |  |  | Included |  |

### Grand Bellway Library (Library_03)

**Game ID:** Library_03

**Contributors:** rebelslayer

#### Subrooms

- Oil Room
- Entrance

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Oil Room | [Grand Bellway Shaft (Song_20)](#grand-bellway-shaft-song20) | UR | Nothing. (Fall) |  |  |  |
| R | right1 | Oil Room | [Whispering Vaults Flea Shaft (Library_01)](#whispering-vaults-flea-shaft-library01) | CL | Nothing. (Fall) |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | Entrance | Oil Room | Silk Soar OR Cling Grip/Scuttlebrace AND Faydown Cloak/Drifter's Cloak/Clawline/Sharp Dart/Spint/(Dash AND Crest Pogo) |  |  | lever, one sided door |
| V | Vertical | Oil Room | Entrance | Nothing. (Fall) |  |  | both sides. |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Pale Oil: Whispering Vaults | Oil Room | Flick the first lever. |  |  | Included |  |
| Lever: Whispering Vaults #3 | Oil Room | Nothing. |  |  | Included |  |
| Lever: Whispering Vaults #4 | Oil Room | Flick the first lever. |  |  | Included |  |

### Vaultkeeper Cauldron Entrance (Library_10)

**Game ID:** Library_10

**Contributors:** rebelslayer

#### Subrooms

- Left Side
- Right Side
- Top Room

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | Bottom | Left Side | [Library_12b (Library_12b-0)](#library12b-library12b-0) | T | Nothing. |  |  | the bottom portion of 04 doesn't link for some reason, so this transition can't connect until that's fixed |
| L | Left | Right Side | [Whispering Vaults Hell (Library_04)](#whispering-vaults-hell-library04) | BR | Nothing. |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| W | Walk | Right Side | Left Side | Open the door. |  |  |  |
| W | Walk | Left Side | Right Side | Open the door. |  |  |  |
| J | Jump | Right Side | Top Room | Silk Soar OR Cling Grip OR Scuttlebrace OR Faydown Cloak AND Ledge Grab |  |  |  |
| J | Jump | Top Room | Right Side | Nothing. (Fall) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Breakable Wall | Right Side | Nothing. |  |  | Included |  |
| Sacred Cylinder | Left Side | Nothing. |  |  | Included |  |
| Pressure Plate | Right Side | Nothing. |  |  | Included |  |
| Lore | Left Side | Nothing. |  |  | Included |  |

### Songclave Steam Tunnel (Library_02)

**Game ID:** Library_02

**Contributors:** rebelslayer

#### Subrooms

- Top
- Bottom
- Arena
- Bottom Right
- Blocks

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BL | left1 | Top | [Rotating Tunnel (Song_20b)](#rotating-tunnel-song20b) | R1 | Nothing. |  |  |  |
| TL | left2 | Bottom | [Rotating Tunnel (Song_20b)](#rotating-tunnel-song20b) | RH | SB1 |  |  |  |
| BR | right1 | Bottom | [Whispering Vaults Flea Shaft (Library_01)](#whispering-vaults-flea-shaft-library01) | TL | Nothing. |  |  |  |
| TR | right2 | Top | [Songclave (Song_Enclave)](#songclave-songenclave) | BL | Nothing. |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LV | Left Vertical | Blocks | Arena | Silk Soar/Faydown Cloak AND Spike Pogo (except Witch) AND Ledge Grab/Clawline OR Cling Grip AND Crest Pogo/Dash/Sprint/Clawline/Drifter's Cloak/Sharp Dart OR Spike Pogo Scuttlebrace AND Faydown Cloak/(Dash AND Ledge Grab)/Clawline/Sharp Dart/Beast Pogo |  |  |  |
| RV | Right Vertical | Bottom Right | Arena | Silk Soar OR Cling Grip OR Scuttlebrace AND Faydown Cloak |  |  |  |
| LV | Left Vertical | Arena | Blocks | Crest Pogo |  |  |  |
| RV | Right Vertical | Arena | Bottom Right | Nothing. (Fall) |  |  |  |

#### Check Locations

No check locations defined.

### Whispering Vaults Below Bench (Library_06)

**Game ID:** Library_06

**Contributors:** rebelslayer

#### Subrooms

- Bottom
- Top
- Rosary
- Right Exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BL | left2 | Bottom | [Whispering Vaults East To West (Library_05)](#whispering-vaults-east-to-west-library05) | BR | Nothing. |  |  |  |
| R | right1 | Top | [Whispering Vaults Totally Not White Palace (Library_07)](#whispering-vaults-totally-not-white-palace-library07) | BL | Nothing. |  |  |  |
| TL | left1 | Top | [Whispering Vaults East To West (Library_05)](#whispering-vaults-east-to-west-library05) | TR | Nothing. |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LA | Lower Ascent | Bottom | Top | Silk Soar OR Cling Grip AND Dash/Clawline/Sharp Dart/(Hunter Pogo AND Ledge Grab)/Beast Pogo/Beast Charge/Architect Pogo/Architect Charge OR Faydown Cloak AND (Ledge Grab OR Clawline OR Scuttlebrace AND Clawline |  |  |  |
| HA | Higher Ascent | Top | Rosary | Silk Soar OR Cling Grip AND (Enemy Pogo OR Box Pogo with any crest except Hunter OR Faydown Cloak OR Clawline OR Sharp Dart OR Architect Charge) |  |  |  |
| E | Exit | Top | Right Exit | Silk Soar OR Cling Grip OR Scuttlebrace OR Faydown Cloak AND (Ledge Grab OR Clawline) |  |  | clawline skip here is REALLY precise |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| AP Minor Cache - Whispering Vaults - Rosary Cache #4 | Rosary | Nothing. |  |  | Included |  |
| Rosary Cache (Small) | Rosary | Nothing. |  |  | Included |  |
| Rosary Dish #2 | Rosary | Nothing. |  |  | Included |  |

### Whispering Vaults Bench (Library_08)

**Game ID:** Library_08

**Contributors:** rebelslayer

#### Subrooms

- Bench
- Loot
- Cylinder
- Cardinius
- Side Room

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | Right | Side Room | [Whispering Vaults Totally Not White Palace (Library_07)](#whispering-vaults-totally-not-white-palace-library07) | TL | Nothing. |  |  |  |
| L | Left | Cardinius | [Whispering Vaults Hell (Library_04)](#whispering-vaults-hell-library04) | MHR | Nothing. |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| L | Loot! | Side Room | Loot | Silk Soar OR Cling Grip OR Scuttlebrace |  |  |  |
| BT | Bench Time! | Cardinius | Bench | Silk Soar OR Cling Grip AND Faydown Cloak/Clawline/Sharp Dart/Sprint/Dash/Beast Charge/Architect Charge |  |  |  |
| PC | Psalm Cylinder | Cardinius | Cylinder | Silk Soar OR Cling Grip OR Scuttlebrace |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Rosary Cache | Loot | Nothing. |  |  | Included |  |
| Memory Locket: Whispering Vaults | Loot | Nothing. |  |  | Included |  |
| Rosary Cache #2 | Loot | Nothing. |  |  | Included |  |
| Psalm Cylinder #1 | Cylinder | Nothing. |  |  | Included |  |

### Whispering Vaults East To West (Library_05)

**Game ID:** Library_05

**Contributors:** rebelslayer

#### Subrooms

- Top
- Center
- Bottom
- Shard

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BL | Bottom Left | Bottom | [Whispering Vaults Hell (Library_04)](#whispering-vaults-hell-library04) | LR | Nothing. |  |  |  |
| BR | Bottom Right | Bottom | [Whispering Vaults Below Bench (Library_06)](#whispering-vaults-below-bench-library06) | TL | Nothing. |  |  |  |
| TR | Top Right | Top | [Whispering Vaults Below Bench (Library_06)](#whispering-vaults-below-bench-library06) | BL | Nothing. |  |  |  |
| TL | Top Left | Top | [Whispering Vaults Hell (Library_04)](#whispering-vaults-hell-library04) | CR | Nothing. |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| VL | Vertical Low | Bottom | Center | Silk Soar OR Cling Grip OR Faydown Cloak AND Ledge Grab/Clawline |  |  |  |
| VH | Vertical High | Center | Top | Cling Grip OR Silk Soar |  |  |  |
| MS | Mask Shard | Top | Shard | Silk Soar OR Box Pogo |  |  |  |
| MS | Mask Shard | Shard | Top | Nothing. (Fall) |  |  |  |
| VH | Vertical High | Top | Center | Nothing. (Fall) |  |  |  |
| VL | Vertical Low | Center | Bottom | Nothing. (fall) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Mask Shard #? | Shard | Nothing. |  |  | Included |  |
| Ladder | Bottom | Nothing. |  |  | Included |  |

### Whispering Vaults Flea Shaft (Library_01)

**Game ID:** Library_01

**Contributors:** rebelslayer

#### Subrooms

- Top
- Bottom
- Flea Check
- Lower Platforms
- Upper Platforms

- **Top:** Self contained.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BR | right2 | Bottom | [Whispering Vaults Hell (Library_04)](#whispering-vaults-hell-library04) | LL | Nothing. |  |  |  |
| CL | left2 | Lower Platforms | [Grand Bellway Library (Library_03)](#grand-bellway-library-library03) | R | Silk Soar OR Enemy Pogo x2 OR Faydown Cloak AND (Ledge Grab/Clawline OR (Sprint AND Shaman Pogo/Beast Charge/Beast Pogo)) OR Cling Grip AND Enemy Pogo/Sprint/Dash/Clawline/Drifter's Cloak/Sharp Dart/Architect Charge/Beast Pogo/Beast Charge |  |  | first enemy pogo only available with flipped lever. crest specific options and enemy pogos probably easy skip? |
| TR | right1 | Top | [Whispering Vaults Hell (Library_04)](#whispering-vaults-hell-library04) | TL | Nothing. |  |  |  |
| TL | left1 | Top | [Songclave Steam Tunnel (Library_02)](#songclave-steam-tunnel-library02) | BR | Nothing. |  |  |  |
| BL | left3 | Bottom | [Whispering Vaults Vaultborn Lever (Library_15)](#whispering-vaults-vaultborn-lever-library15) | R | Nothing. |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| GF | Ground to Floor 1 | Bottom | Lower Platforms | Silk Soar OR Enemy Pogo x2 OR Faydown Cloak AND Ledge (Grab/Clawline OR (Sprint AND Shaman Pogo/Beast Charge)) OR Cling Grip AND Enemy Pogo/Sprint/Dash/Clawline/Drifter's Cloak/Sharp Dart/Architect Charge/Beast Pogo/Beast Charge |  |  |  |
| UT | Upwards Traversal | Lower Platforms | Upper Platforms | Silk Soar OR Enemy Pogos AND Faydown Cloak OR Faydown Cloak AND Ledge Grab/Clawline/Beast Pogo/Beast Charge/Shaman Pogo/Cling Grip OR Cling Grip AND Sprint/Dash/Beast Pogo/Beast Charge/Architect Charge/Sharp Dart/Drifter's Cloak/Clawline |  |  |  |
| FG | Flea Grab | Upper Platforms | Flea Check | Silk Soar OR Cling Grip AND Clawline/Sharp Dart/Drifter's Cloak/Beast Charge/Beast Pogo/Architect Charge OR Cling Grip/Scuttlebrace AND Faydown Cloak AND Swift Step |  |  | collect yo flea. |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Flea: Whispering Vaults | Flea Check | Silk Soar OR Scuttlebrace/Cling Grip AND Clawline/Sharp Dart/Drifter's Cloak/Beast Charge/Beast Pogo/Architect Charge OR Cling Grip/Scuttlebrace AND Faydown Cloak AND Swift Step |  |  | Included |  |
| Breakable Wall: Whispering Vaults | Bottom | Nothing, leads to BL |  |  | Included |  |

### Whispering Vaults Jumps (Library_09)

**Game ID:** Library_09

**Contributors:** rebelslayer

#### Subrooms

- Flea Chase
- Flea
- Annoying Ass Jump (Left)
- Annoying Ass Jump (Right)
- Jump 2 (Right)
- Jump 2 (Left)
- Rosary Necklace
- Room With Stuff

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | bot1 | Flea Chase | [Whispering Vaults Totally Not White Palace (Library_07)](#whispering-vaults-totally-not-white-palace-library07) | T | Nothing. |  |  |  |
| L | left1 | Room With Stuff | [Whispering Vaults Hell (Library_04)](#whispering-vaults-hell-library04) | TR | Nothing. |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| FG | Flea Get | Flea Chase | Flea | Silk Soar OR Clawline AND Cling Grip) OR Clawline AND Scuttlebrace AND (Spike Pogo/Faydown Cloak ) |  |  |  |
| FG | Flea Get | Flea | Flea Chase | Nothing. (BIG fall) |  |  |  |
| AJ | Annoying Jump | Annoying Ass Jump (Right) | Annoying Ass Jump (Left) | Sprint/Dash/Drifter's Cloak/Faydown Cloak/Clawline/Scuttlebrace/Spike Pogo/Enemy Pogo/Sharp Dart/Hunter Pogo/Reaper Pogo/Beast Pogo/Architect Nail Swing/Architect Pogo/Witch Pogo AND Ledge Grab/Shaman Pogo/Hunter Charge AND Ledge Grab/Wanderer Charge/Reaper Charge/Beast Charge/Architect Charge/Witch Charge/Shaman Charge/Heal stall/flintslate stall/flea brew boost/flea brew stall/voltvessel stall |  |  | dont put this in logic im just being an ass. you can damage boost it. |
| AJ | Annoying Jump | Annoying Ass Jump (Left) | Annoying Ass Jump (Right) | Dash/Sprint/Faydown Cloak/Drifter's Cloak AND Ledge Grab/Scuttlebrace/Clawline/Sharp Dart/Beast Charge/Architect Charge/Beast Pogo/Spike Pogo/Enemy Pogo |  |  | this side you CANT damage boost. |
| JT | Jump Two | Jump 2 (Left) | Jump 2 (Right) | Dash/Sprint/Faydown Cloak/Drifter's Cloak AND Ledge Grab/Scuttlebrace/Clawline/Sharp Dart/Beast Charge/Architect Charge/Beast Pogo/Spike Pogo/Enemy Pogo |  |  | its literally the SAME jump again. |
| JT | Jump Two | Jump 2 (Right) | Jump 2 (Left) | Dash/Sprint/Faydown Cloak/Drifter's Cloak AND Ledge Grab/Scuttlebrace/Clawline/Sharp Dart/Beast Charge/Architect Charge/Beast Pogo/Spike Pogo/Enemy Pogo |  |  |  |
| RP | Rosary Pickup | Jump 2 (Right) | Rosary Necklace | Sprint AND Clawline OR Sprint AND Faydown Cloak AND (Drifter's Cloak OR Dash) AND Spike Pogo |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Lever: Whispering Vaults #5 | Room With Stuff | Nothing. |  |  | Included |  |
| Heavy Rosary Necklace | Rosary Necklace | Nothing. |  |  | Included |  |
| Psalm Cylinder | Room With Stuff | Nothing. |  |  | Included |  |

### Whispering Vaults Silkeater (Library_14)

**Game ID:** Library_14

**Contributors:** rebelslayer

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | Left |  | [Whispering Vaults Hell (Library_04)](#whispering-vaults-hell-library04) | HR | Nothing. |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Breakable Wall #3 |  | Nothing. |  |  | Included |  |
| Silkeater |  | Nothing. |  |  | Included |  |

#### Notes

lol

### Whispering Vaults Totally Not White Palace (Library_07)

**Game ID:** Library_07

**Contributors:** rebelslayer

#### Subrooms

- White Palace Lite
- Up And Away
- Collectibles(TM)
- Collectibles 2(TM)
- Down We Go
- Sky High

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TL | left1 | Down We Go | [Whispering Vaults Bench (Library_08)](#whispering-vaults-bench-library08) | R | Nothing. |  |  |  |
| BL | left2 | Up And Away | [Whispering Vaults Below Bench (Library_06)](#whispering-vaults-below-bench-library06) | R | Nothing. |  |  |  |
| T | top1 | Sky High | [Whispering Vaults Jumps (Library_09)](#whispering-vaults-jumps-library09) | B | Nothing. |  |  |  |
| B | bot1 | White Palace Lite | [Shadow_22 (Shadow_22)](#shadow22-shadow22) | T | Nothing. |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CS | Collect Shit | Up And Away | Collectibles(TM) | Silk Soar OR Cling Grip OR Scuttlebrace AND Faydown Cloak |  |  |  |
| MC | More Collecting | Down We Go | Collectibles(TM) | Nothing. (Fall) |  |  |  |
| NHA | NOT HIM AGAIN! | Collectibles(TM) | White Palace Lite | Clawline/Faydown Cloak/Cling Grip AND Spike Pogo OR Drifter's Cloak AND Spike Pogo AND Ledge Grab OR Cling Grip AND Dash/Drifter's Cloak |  |  |  |
| OH | GET ME OUTTA HERE!! | White Palace Lite | Sky High | Silk Soar OR Drifter's Cloak OR Cling Grip OR Scuttlebrace AND Faydown Cloak |  |  |  |
| CS | Collect Shit | Collectibles(TM) | Up And Away | Silk Soar OR Scuttlebrace OR Cling Grip |  |  |  |
| MC | More Collecting | Collectibles(TM) | Down We Go | Nothing. (Fall) |  |  |  |
| NHA | NOT HIM AGAIN! | White Palace Lite | Collectibles(TM) | you have literally no reason to ever do this |  |  |  |
| OH | GET ME OUTTA HERE!! | Sky High | White Palace Lite | Nothing. (BIG fall.) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Clawline Ring | Collectibles(TM) | Clawline. |  |  | Included |  |
| AP Minor Cache - Whispering Vaults - Rosary Cache #5 | Collectibles 2(TM) | Nothing. |  |  | Included |  |
| AP Minor Cache - Whispering Vaults - Shell Shard Cache #1 | Collectibles(TM) | Nothing. |  |  | Included |  |
| Breakable Wall #1 | Collectibles(TM) | Nothing. |  |  | Included |  |
| Breakable Wall #2 | Collectibles(TM) | Nothing. |  |  | Included |  |
| Fan Lever | White Palace Lite | Nothing. |  |  | Included |  |

### Whispering Vaults Vaultborn Lever (Library_15)

**Game ID:** Library_15

**Contributors:** rebelslayer

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Whispering Vaults Flea Shaft (Library_01)](#whispering-vaults-flea-shaft-library01) | BL | Nothing. |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Lever: Whispering Vaults #8 |  | Nothing. |  |  | Included |  |

### Trobbio (Library_13)

**Game ID:** Library_13

**Contributors:** rebelslayer

#### Subrooms

- Top
- Bottom
- Fight

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TR | right1 | Top | [Trobbio Entrance (Library_13b)](#trobbio-entrance-library13b) | L | Nothing. |  |  |  |
| L | left1 | Bottom | [Grand Bellway Shaft (Song_20)](#grand-bellway-shaft-song20) | RS | Nothing. |  |  |  |
| BR | right2 | Fight | [Vaults Cauldron Entrance (Library_11)](#vaults-cauldron-entrance-library11) | TL | Nothing. |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| VR | Vertical Right | Top | Bottom | Nothing. (Fall) |  |  | Needs to be opened with Lever. |
| VR | Vertical Right | Bottom | Top | Cling Grip OR Scuttlebrace OR Faydown Cloak OR Clawline OR Dash OR Silk Soar OR Ledge Grab |  |  | needs to be opened with Lever |
| VL | Vertical Left | Top | Bottom | Nothing. (Fall) |  |  |  |
| VL | Vertical Left | Bottom | Top | Silk Soar OR Faydown Cloak AND Cling Grip/Scuttlebrace |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Dual Mirrors | Fight | Beat Trobbio 2 |  |  | Included |  |
| Lore Tablet #1 | Bottom | Nothing. |  |  | Included |  |
| Trobbio | Fight | Nothing. |  |  | Included |  |
| Claw Mirror | Fight | Beat Trobbio 1 |  |  | Included |  |
| Lever: Whispering Vaults #1 | Bottom | Nothing. |  |  | Included |  |
| Lever: Whispering Vaults #2 | Bottom | Nothing. |  |  | Included |  |
| AP Minor Cache - Whispering Vaults - Shell Shard Cache #2 | Top | Nothing. |  |  | Included |  |

### Trobbio Entrance (Library_13b)

**Game ID:** Library_13b

**Contributors:** rebelslayer

#### Subrooms

- The Only Jump In This Entire Room
- Not The Jump.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | Left | The Only Jump In This Entire Room | [Trobbio (Library_13)](#trobbio-library13) | TR | Nothing. |  |  |  |
| R | Right | The Only Jump In This Entire Room | [Whispering Vaults Hell (Library_04)](#whispering-vaults-hell-library04) | CL | Nothing. |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| J | Jump | The Only Jump In This Entire Room | Not The Jump. | Ledge Grab OR Cling Grip OR Faydown Cloak OR Clawline OR Beast Charge OR Scuttlebrace OR Sprint |  |  |  |
| J | Jump | Not The Jump. | The Only Jump In This Entire Room | Spike Pogo OR Clawline OR Dash OR Sprint OR Faydown Cloak OR Drifter's Cloak OR Scuttlebrace OR Cling Grip OR Sharp Dart |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Collectable Item Pickup - Quill Red | Not The Jump. | Nothing. |  |  | Included |  |
| Collectable Item Pickup - Quill Purple | Not The Jump. | Nothing. |  |  | Included |  |
| Lore Tablet #2 | Not The Jump. | Nothing. |  |  | Not included |  |
| Lore Tablet #3 | Not The Jump. | Nothing. |  |  | Included |  |

### Whispering Vaults Music Box (Library_16)

**Game ID:** Library_16

**Contributors:** rebelslayer

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | Right |  | [Whispering Vaults Hell (Library_04)](#whispering-vaults-hell-library04) | BL | Nothing. |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Cogheart Piece |  | The ability to swing your needle. |  |  | Included |  |

## Whiteward

### Whiteward Entrance (Ward_01)

**Game ID:** Ward_01

**Contributors:** skai

#### Subrooms

- Top Third
- Middle Third (Left)
- Middle Third (Right)
- Bottom Third (Left)
- Elevator Shaft
- Vertical Shaft (Upper)
- Vertical Shaft (Lower)
- Pit
- Top Right (Entrance)

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TL | Top Left | Top Third | [Choral Chambers Eastern Shaft (Song_05)](#choral-chambers-eastern-shaft-song05) | R1 | Nothing |  | Verified |  |
| TR | Top Right | Top Right (Entrance) | [Whiteward Long Horizontal (Ward_05)](#whiteward-long-horizontal-ward05) | L | Nothing |  | Verified |  |
| ML | Middle Left | Middle Third (Left) | [Whiteward Map Room (Ward_02b)](#whiteward-map-room-ward02b) | R | Nothing |  | Verified |  |
| MR | Middle Right | Middle Third (Right) | [Whiteward Silkeater (Ward_04)](#whiteward-silkeater-ward04) | L | Break Wall |  | Verified |  |
| BL | Bottom Left | Bottom Third (Left) | [Whiteward Unravelled Arena Room (Ward_02)](#whiteward-unravelled-arena-room-ward02) | R | Nothing |  | Verified |  |
| BR | Bottom Right | Vertical Shaft (Lower) | [Whiteward Descent Connection (Ward_03)](#whiteward-descent-connection-ward03) | L | Nothing |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TES | Top to Elevator Shaft | Top Third | Elevator Shaft | White Key Used |  | Verified |  |
| TES | Top to Elevator Shaft | Elevator Shaft | Top Third | White Key Used |  | Verified |  |
| EBL | Elevator to Bottom Left | Elevator Shaft | Bottom Third (Left) | White Key Used |  | Verified |  |
| EBL | Elevator to Bottom Left | Bottom Third (Left) | Elevator Shaft | White Key Used |  | Verified |  |
| MLR | Middle Left to Right | Middle Third (Left) | Middle Third (Right) | Nothing (Jump) |  | Verified |  |
| MLR | Middle Left to Right | Middle Third (Right) | Middle Third (Left) | Nothing (Jump) |  | Verified |  |
| RVL | Right to Vertical Lower | Middle Third (Right) | Vertical Shaft (Lower) | Nothing (Fall) |  | Verified |  |
| RVL | Right to Vertical Lower | Vertical Shaft (Lower) | Middle Third (Right) | Cling Grip OR (Scuttlebrace AND (Flea Brew Stall OR Heal Stall OR Faydown)) OR Silk Soar |  | Verified |  |
| RVU | Right to Vertical Upper | Middle Third (Right) | Vertical Shaft (Upper) | Silk Soar OR (Faydown AND Cling Grip AND Easy Tool  Skip) |  | Verified |  |
| RVU | Right to Vertical Upper | Vertical Shaft (Upper) | Middle Third (Right) | Nothing (Fall) |  | Verified |  |
| VTR | Vertical to Top Right (Entrance) | Vertical Shaft (Upper) | Top Right (Entrance) | Silk Soar OR (Faydown AND Cling Grip AND Easy Tool Skip) |  | Verified |  |
| VTR | Vertical to Top Right (Entrance) | Top Right (Entrance) | Vertical Shaft (Upper) | Nothing (Fall) |  | Verified |  |
| ETP | Elevator to Pit | Elevator Shaft | Pit | Set Elevator to Top AND White Key Used |  | Verified |  |
| ETP | Elevator to Pit | Pit | Elevator Shaft | Set Elevator to Top AND (Cling Grip OR Scuttlebrace OR Silk Soar) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Whiteward - Spool Fragment | Pit | Nothing |  | Verified | Included |  |
| Whiteward Bench | Top Third | White Key |  | Verified | Included |  |
| Whiteward - Map Purchase | Vertical Shaft (Lower) | Nothing |  | Verified | Included |  |

### Whiteward Descent Connection (Ward_03)

**Game ID:** Ward_03

**Contributors:** skai

#### Subrooms

- Bottom (Left)
- Spikes
- Bottom (Middle)
- Ascent
- Middle (Left)
- Middle (Right)
- Top
- Bottom Right (Upper)
- Bottom Right (Lower)

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | Left | Bottom (Left) | [Whiteward Entrance (Ward_01)](#whiteward-entrance-ward01) | BR | Nothing |  | Verified |  |
| B | Bottom | Bottom Right (Lower) | [Whiteward Descent (Ward_06)](#whiteward-descent-ward06) | T | Nothing |  | Verified |  |
| T | Top | Top | [Whiteward Junk Dump (Ward_07)](#whiteward-junk-dump-ward07) | B | Nothing |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BLS | Bottom Left to Spikes | Bottom (Left) | Spikes | Spike Pogo OR Dash OR Sprint OR Sharpdart OR Clawline OR Faydown OR Drifter's Cloak OR Flea Brew OR ((Plasmium Phial OR Voltvessels) AND Easy Tool Skip) |  | Verified |  |
| BLS | Bottom Left to Spikes | Spikes | Bottom (Left) | Spike Pogo OR Dash OR Sprint OR Sharpdart OR Clawline OR Faydown OR Drifter's Cloak OR Flea Brew OR ((Plasmium Phial OR Voltvessels) AND Easy Tool Skip) |  | Verified |  |
| SBR | Spikes to Bottom Right | Spikes | Bottom (Middle) | Spike Pogo OR Dash OR Sprint OR Sharpdart OR Clawline OR Faydown OR Drifter's Cloak OR Flea Brew OR ((Plasmium Phial OR Voltvessels) AND Easy Tool Skip) |  | Verified |  |
| SBR | Spikes to Bottom Right | Bottom (Middle) | Spikes | Spike Pogo OR Dash OR Sprint OR Sharpdart OR Clawline OR Faydown OR Drifter's Cloak OR Flea Brew OR ((Plasmium Phial OR Voltvessels) AND Easy Tool Skip) |  | Verified |  |
| BMA | Bottom to Ascent | Bottom (Middle) | Ascent | Cling Grip OR Scuttlebrace OR Silk Soar OR Faydown |  | Verified |  |
| BMA | Bottom to Ascent | Ascent | Bottom (Middle) | Cling Grip OR Scuttlebrace OR Silk Soar OR Faydown |  | Verified |  |
| AML | Ascent to Middle Left | Ascent | Middle (Left) | Cling Grip OR Scuttlebrace OR Silk Soar OR Faydown |  | Verified |  |
| AML | Ascent to Middle Left | Middle (Left) | Ascent | Nothing (Fall) |  | Verified |  |
| AMR | Ascent to Middle Right | Ascent | Middle (Right) | Cling Grip OR Scuttlebrace OR Silk Soar OR Faydown |  | Verified |  |
| AMR | Ascent to Middle Right | Middle (Right) | Ascent | Nothing (Fall) |  | Verified |  |
| MRB | Middle Right to Bottom | Bottom Right (Lower) | Middle (Right) | (Magma Bell AND Silk Soar) OR (Faydown AND Cling Grip) |  | Verified |  |
| MRB | Middle Right to Bottom | Middle (Right) | Bottom Right (Lower) | Nothing (Fall) |  | Verified |  |
| AAT | Ascent to Top | Ascent | Top | Cling Grip OR Silk Soar OR Faydown |  | Verified |  |
| AAT | Ascent to Top | Top | Ascent | Cling Grip OR Silk Soar OR Faydown |  | Verified |  |
| BUL | Bottom Right Upper to Lower | Bottom Right (Lower) | Bottom Right (Upper) | Cling Grip OR Silk Soar |  | Verified |  |
| BUL | Bottom Right Upper to Lower | Bottom Right (Upper) | Bottom Right (Lower) | Nothing (Fall) |  | Verified |  |

#### Check Locations

No check locations defined.

### Whiteward Descent (Ward_06)

**Game ID:** Ward_06

**Contributors:** skai

#### Subrooms

- Descent Rosary Side
- Descent Upper
- Descent Lower

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | Top | Descent Upper | [Whiteward Descent Connection (Ward_03)](#whiteward-descent-connection-ward03) | B | Nothing |  | Verified |  |
| B | Bottom | Descent Lower | Under_17 | T | Nothing (Fall) |  | Verified | The Cauldron is undone as of now so the game name for the room destination is listed. |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LTR | Descent Lower to Rosaries | Descent Lower | Descent Rosary Side | Wall Broken FROM Right OR Wall Broken FROM Left |  | Verified |  |
| LTR | Descent Lower to Rosaries | Descent Rosary Side | Descent Lower | Wall Broken FROM Left OR Wall Broken FROM Right |  | Verified |  |
| LTU | Descent Lower to Upper | Descent Lower | Descent Upper | Cling Grip OR Scuttlebrace OR Silk Soar OR Faydown |  | Verified |  |
| LTU | Descent Lower to Upper | Descent Upper | Descent Lower | Nothing (Fall) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Whiteward Descent - Rosary Cache #1 | Descent Rosary Side | Nothing |  | Verified | Included |  |
| Whiteward Descent - Rosary Cache #2 | Descent Rosary Side | Nothing |  | Verified | Included |  |

### Whiteward Junk Dump (Ward_07)

**Game ID:** Ward_07

**Contributors:** skai

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | Bottom |  | [Whiteward Descent Connection (Ward_03)](#whiteward-descent-connection-ward03) | T | Nothing |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Whiteward Top Right - Lore |  | Nothing |  | Verified | Included |  |

### Whiteward Long Horizontal (Ward_05)

**Game ID:** Ward_05

**Contributors:** skai

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | Left |  | [Whiteward Entrance (Ward_01)](#whiteward-entrance-ward01) | TR | Nothing |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Choral Commandment #3 |  | Nothing |  | Verified | Included |  |

### Whiteward Silkeater (Ward_04)

**Game ID:** Ward_04

**Contributors:** skai

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | Left |  | [Whiteward Entrance (Ward_01)](#whiteward-entrance-ward01) | MR | Nothing |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| White Ward: Silkeater |  | Cling Grip OR Scuttlebrace OR Silk Soar OR (Faydown AND Ledge Grab) |  | Verified | Included |  |

### Whiteward Unravelled Arena Room (Ward_02)

**Game ID:** Ward_02

**Contributors:** skai

#### Subrooms

- Vertical Left
- Surgery Tables (Right)
- Surgery Tables (Left)
- Key Shaft
- Unravelled Arena

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | Top | Vertical Left | [Whiteward Map Room (Ward_02b)](#whiteward-map-room-ward02b) | B | Silk Soar OR Faydown OR Cling Grip OR Scuttlebrace |  | Verified |  |
| R | Right | Surgery Tables (Right) | [Whiteward Entrance (Ward_01)](#whiteward-entrance-ward01) | BL | Nothing |  | Verified |  |
| B | Bottom | Unravelled Arena | [Confession Toll (Under_08)](#confession-toll-under08) | T | Beat Unravelled Arena |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SLV | Surgery Left to Vertical | Surgery Tables (Left) | Vertical Left | Ledge Grab OR Faydown OR Clawline OR Silk Soar OR (Proficient Movement AND Scuttlebrace) |  | Verified |  |
| SLV | Surgery Left to Vertical | Vertical Left | Surgery Tables (Left) | Nothing (Falling) |  | Verified |  |
| SRL | Surgery Right to Left | Surgery Tables (Right) | Surgery Tables (Left) | (Nothing AND NOT Key Inserted) OR (Faydown OR Clawline OR Sharpdart) |  | Verified |  |
| SRL | Surgery Right to Left | Surgery Tables (Left) | Surgery Tables (Right) | (Nothing AND NOT Key Inserted) OR (Faydown OR Clawline OR Sharpdart) |  | Verified |  |
| SKS | Surgery to Key Shaft | Surgery Tables (Left) | Key Shaft | Nothing (Falling) |  | Verified |  |
| SKS | Surgery to Key Shaft | Key Shaft | Surgery Tables (Left) | Silk Soar |  | Verified |  |
| KSA | Key Shaft to Arena | Key Shaft | Unravelled Arena | Nothing (Falling) |  | Verified |  |
| KSA | Key Shaft to Arena | Unravelled Arena | Key Shaft | Silk Soar |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| White Ward: Silk Heart | Unravelled Arena | Beat Unravelled Arena |  | Verified | Included |  |

### Whiteward Map Room (Ward_02b)

**Game ID:** Ward_02b

**Contributors:** skai

#### Subrooms

- Top Horizontal
- Pickup Section
- Lower Tunnels
- Upper Tunnels
- Center Tunnels

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | Bottom | Lower Tunnels | [Whiteward Unravelled Arena Room (Ward_02)](#whiteward-unravelled-arena-room-ward02) | T | Nothing |  | Verified |  |
| R | Right | Pickup Section | [Whiteward Entrance (Ward_01)](#whiteward-entrance-ward01) | ML | Break 4x Wall |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LUT | Lower to Upper Tunnels | Lower Tunnels | Upper Tunnels | Cling Grip OR Scuttlebrace OR Silk Soar |  | Verified |  |
| LUT | Lower to Upper Tunnels | Upper Tunnels | Lower Tunnels | Nothing (Falling) |  | Verified |  |
| UCT | Upper to Center Tunnels | Center Tunnels | Upper Tunnels | Cling Grip OR Scuttlebrace OR Silk Soar |  | Verified |  |
| UCT | Upper to Center Tunnels | Upper Tunnels | Center Tunnels | Nothing (Falling) |  | Verified |  |
| CTH | Center to Top Horizontal | Center Tunnels | Top Horizontal | Cling Grip OR Scuttlebrace OR Silk Soar |  | Verified |  |
| CTH | Center to Top Horizontal | Top Horizontal | Center Tunnels | Nothing (Falling) |  | Verified |  |
| TTP | Top to Pickup Section | Top Horizontal | Pickup Section | Nothing (Falling) |  | Verified |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Map: Whiteward | Pickup Section | Nothing |  | Verified | Included |  |

## High Halls

### High Halls Small Slide (Hang_02)

**Game ID:** Hang_02

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [High Halls Shaft Bottom (Hang_03)](#high-halls-shaft-bottom-hang03) | ML | (ledge grab or clawline or cling grip or faydown cloak) and swim |  | Verified |  |
| L | left1 |  | [High Halls Entrance (Hang_01)](#high-halls-entrance-hang01) | TP | clawline or (faydown cloak and dash and ledge grab) |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### High Halls Shaft Top (Hang_03_top)

**Game ID:** Hang_03_top

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | bot1 |  | [High Halls Shaft Bottom (Hang_03)](#high-halls-shaft-bottom-hang03) | T | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| High Halls - Spool Fragment |  | silk soar or (clawline and faydown cloak and cling grip) |  | Verified | Included |  |

### High Halls Shaft Bottom (Hang_03)

**Game ID:** Hang_03

**Contributors:** samupo

#### Subrooms

- Top
- Top Right
- Middle Left
- Bottom Left
- Bottom Right

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| T | top1 | Top | [High Halls Shaft Top (Hang_03_top)](#high-halls-shaft-top-hang03top) | B | none |  | Verified |  |
| TR | right1 | Top Right | [High Halls Big Slide (Hang_13)](#high-halls-big-slide-hang13) | L | none |  | Verified |  |
| BL | left2 | Middle Left | [High Halls Small Room (Hang_15)](#high-halls-small-room-hang15) | R | none |  | Verified |  |
| BR | right2 | Bottom Right | [High Halls Flooded Room (Hang_10)](#high-halls-flooded-room-hang10) | L | one way door (opens from the east) |  | Verified |  |
| ML | left1 | Middle Left | [High Halls Small Slide (Hang_02)](#high-halls-small-slide-hang02) | R | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| B | Bottom Traversal | Bottom Left | Bottom Right | swim or clawline or (faydown cloak and dash) |  | Verified |  |
| B | Bottom Traversal | Bottom Right | Bottom Left | swim or clawline or (faydown cloak and dash) |  | Verified |  |
| B2 | Bottom Right to Mid Left | Bottom Right | Middle Left | cling grip and faydown cloak or clawline |  | Verified |  |
| M | Middle Left to Top Right | Middle Left | Top Right | clawline and cling grip |  | Verified |  |
| T | Top Right to Top | Top Right | Top | faydown cloak and (clawline or (cling grip and dash)) |  | Verified |  |
| FT | Falling from Top | Top | Middle Left | none |  | Verified | falilng |
| FT2 | Falling from Top 2 | Top | Top Right | clawline or dash or faydown cloak |  | Verified |  |
| FM | Falling from Mid | Middle Left | Bottom Left | none |  | Verified | falling |
| FM2 | Falling from Mid 2 | Middle Left | Bottom Right | clawline or dash or faydown cloak |  | Verified |  |

#### Check Locations

No check locations defined.

### High Halls Small Room (Hang_15)

**Game ID:** Hang_15

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [High Halls Shaft Bottom (Hang_03)](#high-halls-shaft-bottom-hang03) | BL | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| High Halls - Shell Shard Cache #2 |  | none |  | Verified | Included |  |

### High Halls Big Slide (Hang_13)

**Game ID:** Hang_13

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [High Halls Big Shaft (Hang_08)](#high-halls-big-shaft-hang08) | TL | clawline and (ledge grab or faydown cloak or dash) |  | Verified |  |
| L | left1 |  | [High Halls Shaft Bottom (Hang_03)](#high-halls-shaft-bottom-hang03) | TR | (swim and ledge grab) or (clawline and dash) or drifter's cloak |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### High Halls Big Shaft (Hang_08)

**Game ID:** Hang_08

**Contributors:** samupo

#### Subrooms

- Top
- Middle
- Left Spike Exit
- Bottom

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| SL | left3 | Left Spike Exit | [High Halls Flooded Room (Hang_10)](#high-halls-flooded-room-hang10) | R | none |  | Verified |  |
| B | bot1 | Bottom | [High Halls Vault (Hang_06)](#high-halls-vault-hang06) | T | none |  | Verified | One way only (opened from this side) |
| L | left4 | Bottom | [High Halls Baby Room (Hang_16)](#high-halls-baby-room-hang16) | R | none |  | Verified |  |
| NI | right2 |  | TODO |  | NOT IMPLEMENTED BY DEVS |  |  | NOT IMPLEMENTED BY DEVS |
| R | right1 | Bottom | TODO |  | opened during Final Audience Wish according to wiki | TODO |  |  |
| ML | left2 | Middle | [High Halls Cogfly Room (Hang_09)](#high-halls-cogfly-room-hang09) | R | none |  | Verified |  |
| TL | left1 | Top | [High Halls Big Slide (Hang_13)](#high-halls-big-slide-hang13) | R | none |  | Verified |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TF | Falling from Top | Top | Middle | clawline and drifter's cloak |  | Verified |  |
| S | Spiked Secreft | Middle | Left Spike Exit | drifter's cloak and (cling grip or clawline) |  | Verified |  |
| MF | Falling from Middle | Middle | Bottom | drifter's cloak and clawline |  | Verified |  |
| SF | Falling from Secret | Left Spike Exit | Bottom | drifter's cloak and clawline |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| High Halls - Rosary Cache | Top | clawline and (silk soar or cling grip) |  | Verified | Included |  |

### High Halls Flooded Room (Hang_10)

**Game ID:** Hang_10

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [High Halls Shaft Bottom (Hang_03)](#high-halls-shaft-bottom-hang03) | BR | swim |  | Verified | breakable wall from this side |
| R | right1 |  | [High Halls Big Shaft (Hang_08)](#high-halls-big-shaft-hang08) | SL | swim |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| High Halls - Shell Shard Cache #1 |  | faydown cloak and cling grip and swim |  | Verified | Included |  |

### High Halls Cogfly Room (Hang_09)

**Game ID:** Hang_09

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [High Halls Big Shaft (Hang_08)](#high-halls-big-shaft-hang08) | ML | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Cogfly |  | 1 craftmetal |  | Verified | Included |  |

### High Halls Baby Room (Hang_16)

**Game ID:** Hang_16

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [High Halls Big Shaft (Hang_08)](#high-halls-big-shaft-hang08) | L | none |  | Verified |  |
| S | door1 |  | TODO |  | faydown cloaka and cling grip | TODO |  | Secret door to Hang_14 (not in the map, doesn't have any checks) |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Relic Psalm Cylinder (High Halls) |  | none |  | Verified | Included |  |

### High Halls Vault (Hang_06)

**Game ID:** Hang_06

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| D | door1 |  | TODO |  | (ledge grab or faydown cloak or silk soar) and Simple Key (Rosary Bank) | TODO |  |  |
| L | left1 |  | [High Halls Arena (Hang_04)](#high-halls-arena-hang04) | R | none |  | Verified |  |
| B | bot1 |  | [High Halls Corridor (Hang_07)](#high-halls-corridor-hang07) | T | none |  | Verified | One way lever (opens from this side) |
| R | right1 |  | [High Halls Ventrica (Hang_06b)](#high-halls-ventrica-hang06b) | L | none |  | Verified |  |
| T | top1 |  | [High Halls Big Shaft (Hang_08)](#high-halls-big-shaft-hang08) | B | cling grip or (faydown cloak and ledge grab) or silk soar |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### High Halls Ventrica (Hang_06b)

**Game ID:** Hang_06b

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [High Halls Vault (Hang_06)](#high-halls-vault-hang06) | R | none |  | Verified |  |
| V | door_tubeEnter |  | [Ventrica Menu](#ventrica-menu) | HH | rosaries |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| High Halls - Map Purchase |  | rosaries |  | Verified | Included |  |
| High Halls - Ventrica |  | rosaries |  | Verified | Included |  |

### High Halls Conductor (Hang_12)

**Game ID:** Hang_12

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [High Halls Arena (Hang_04)](#high-halls-arena-hang04) | L | none |  | Verified |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Are there things here? |  |  | TODO |  | Included |  |

### High Halls Arena (Hang_04)

**Game ID:** Hang_04

**Contributors:** samupo

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [High Halls Conductor (Hang_12)](#high-halls-conductor-hang12) | R | gauntlet |  |  |  |
| R | right1 |  | [High Halls Vault (Hang_06)](#high-halls-vault-hang06) | L | gauntlet |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

## Bilewater

### Bellway (Bellway_Shadow)

**Game ID:** Bellway_Shadow

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| FT | door_fastTravelExit |  | TODO |  |  |  |  |  |
| L | left1 |  | TODO |  |  |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Bilewater Entrance (Shadow_05)

**Game ID:** Shadow_05

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right |  | TODO |  |  |  |  |  |
| L | left |  | [Sinner's Road Vertical Hall East (Dust_06)](#sinners-road-vertical-hall-east-dust06) | UR |  |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### New room

#### Subrooms

No subrooms defined.

#### Room Transitions

No room transitions defined.

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Shadow_22 (Shadow_22)

**Game ID:** Shadow_22

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  | bot1 |  | TODO |  |  |  |  |  |
| T | top1 |  | [Whispering Vaults Totally Not White Palace (Library_07)](#whispering-vaults-totally-not-white-palace-library07) | B |  |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### New room

#### Subrooms

No subrooms defined.

#### Room Transitions

No room transitions defined.

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

## Memorium

## Sands of Karak

### Coral Tower (Coral_Tower_01)

**Game ID:** Coral_Tower_01

**Contributors:** Pxyl

#### Subrooms

- Entrance
- Main
- Bench

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Entrance | [Coral Tower Entrance (Coral_28)](#coral-tower-entrance-coral28) | D | None |  |  |  |
| DR | door_wakeOnGround | Main | TODO |  | Needolin AND Elegy of the Deep |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SC | Sandcarver Pit | Entrance | Main | Dash OR Sprint OR Drifters cloak OR Faydown Cloak OR Clawline OR Beast Crest OR Sharpdart OR Architect Crest |  |  |  |
| SC | Sandcarver PIt | Main | Entrance | Dash OR Sprint OR Drifters cloak OR Faydown Cloak OR Clawline OR Beast Crest OR Sharpdart OR Architect Crest |  |  |  |
| S2 | Sandcarver Pit 2 | Main | Bench | Dash OR Sprint OR Drifters cloak OR Faydown Cloak OR Clawline OR Beast Crest OR Sharpdart OR ( Architect Crest AND Ledge Grab AND Needle Strike ) |  |  |  |
| S2 | Sandcarver Pit 2 | Bench | Main | Dash OR Sprint OR Drifters cloak OR Faydown Cloak OR Clawline OR Beast Crest OR Sharpdart OR Architect Crest |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Conchcutter | Main | None |  |  | Included |  |
| Lore | Entrance | None |  |  | Included |  |

### Coral Tower Entrance (Coral_28)

**Game ID:** Coral_28

**Contributors:** Pxyl

#### Subrooms

- Exit
- Door

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Exit | [Sands of Karak Upper Left Long Room (Coral_27)](#sands-of-karak-upper-left-long-room-coral27) | L | None |  |  |  |
| D | door1 | Door | [Coral Tower (Coral_Tower_01)](#coral-tower-coraltower01) | L | None |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SC | Sandcarver Pit | Door | Exit | "Clawline OR Sharpdart OR Drifters Cloak OR ( Sprint AND ( Dash OR Faydown Cloak OR Beast Crest ) ) OR  ( Faydown Cloak AND ( Beast Crest OR Hunter Crest OR Architect Crest OR Shaman Crest ( Wanderer Crest AND Needle strike ) ) ) " |  |  |  |
| SC | Sandcarver Pit | Exit | Door | Clawline OR Sharpdart OR ( Sprint AND ( Dash OR Faydown Cloak OR Drifters Cloak OR Beast Crest OR Architect Crest ) )  OR ( Sprint AND ( Shaman Crest OR Hunter crest OR Heal stall OR ( Wanderers Crest AND Needle Strike AND Ledge Grab ) ) ) OR ( Dash AND ( Reaper Crest OR Beast Crest OR Faydown Cloak OR Drifters Cloak OR ( Architect Crest AND ( Ledge Grab OR Needle Strike ) ) ) ) OR ( Faydown Cloak AND ( Beast Crest OR Architect Crest OR Shaman Crest OR Hunter Crest OR Drifters Cloak OR ( Reaper Crest AND Ledge Grab ) OR ( Wanderer Crest AND Needle strike ) ) ) OR ( Drifters Cloak And ( Beast Crest OR Architect Crest OR Shaman Crest OR Wanderer Crest OR Heal Stall OR Ledge Grab OR Silk Soar OR ( Reaper Crest AND Needle Strike ) ) ) OR ( Silk Soar AND ( Beast Crest OR Architect Crest ) ) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Resting Site | Door | Wish: A vassal lost started AND Steel soul AND ( Sprint AND ( Dash OR Drifters Cloak OR Faydown Cloak OR Beast Crest ) OR Clawline OR ( Silk soar AND Ledge Grab ) |  |  | Not included | Not Included for the better |

### Crustnut (Coral_41)

**Game ID:** Coral_41

**Contributors:** Pyxl

#### Subrooms

- Start
- End
- Shard Platform

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Start | [Sands of Karak Tall Centre Room (Coral_35b)](#sands-of-karak-tall-centre-room-coral35b) | UML | None |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| WR | Whole Room | Start | End | Cling grip AND ( Clawline OR Sharpdart OR ( Dash AND ( Drifters Cloak OR Beast Crest ) ) ) OR ( Beast crest AND Faydown Cloak AND Needle Strike ) |  |  |  |
| WR | Whole Room | End | Start | Cling grip AND ( Clawline OR Sharpdart OR ( Dash AND ( Drifters Cloak OR Beast Crest ) ) ) OR ( Beast crest AND Faydown Cloak AND Needle Strike ) |  |  |  |
| SD | Shard Detour | Start | Shard Platform | Silk Soar OR ( ( Dash AND Scuttlebrace ) AND ( Clawline OR Sharpdart ) ) OR ( Cling grip AND ( Dash OR Clawline OR Sharpdart OR Beast Crest OR Faydown Cloak OR Drifters Cloak ) ) |  |  |  |
| SD | Shard Detour | Shard Platform | Start | None |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Crustnut | End | None |  |  | Included |  |
| Shard Cache: Sands of Karak #11 | Shard Platform | None |  |  | Included |  |

### Sands of Karak Bellshrine (Bellshrine_Coral)

**Game ID:** Bellshrine_Coral

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 |  | [Sands of Karak Elevator to Blasted Steps (Coral_38)](#sands-of-karak-elevator-to-blasted-steps-coral38) | R | None |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Simple key: Sands of Karak east bench |  | None |  |  | Included |  |

### Sands of Karak Elevator to Blasted Steps (Coral_38)

**Game ID:** Coral_38

**Contributors:** Pyxl

#### Subrooms

- Left
- Right
- Bottom
- Shardilard Ledge

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Left | [Sands of Karak Right Side Tall room (Coral_26)](#sands-of-karak-right-side-tall-room-coral26) | R | None |  |  |  |
| R | right1 | Right | [Sands of Karak Bellshrine (Bellshrine_Coral)](#sands-of-karak-bellshrine-bellshrinecoral) | L | None |  |  |  |
| F | bot1 | Bottom | [Pre Last Judge Room (Coral_32)](#pre-last-judge-room-coral32) | T | None | TODO |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| OE | Over Elevator | Left | Right | Shamen Crest OR Ledge Grab OR Cling Grip OR Sprint OR ( Dash AND Scuttlebrace ) OR Silk Soar OR Beast Crest OR Clawline OR Elevator Activated OR ( ( Reaper Crest OR Hunter Crest ) AND Needle Strike ) |  |  |  |
| OE | Over Elevator | Right | Left | None |  |  |  |
| EL | Elevator | Right | Bottom | Elevator Activated |  |  |  |
| EL | Elevator | Bottom | Right | Elevator Activated |  |  |  |
| SH | Shaft | Bottom | Shardilard Ledge | Silk Soar OR ( Cling grip AND ( Faydown Cloak OR Drifters Cloak OR Clawline OR Sharpdart OR ( Dash AND ( Beast Crest OR Shaman Crest ) OR ( Architect crest AND Needle Strike ) ) ) OR ( Dash AND Scuttlebrace AND Clawline AND ( Faydown Cloak OR Drifters Cloak ) ) |  |  |  |
| SH | Shaft | Shardilard Ledge | Bottom | None |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Shell shard cache: Sands of Karak #5 | Shardilard Ledge | None |  |  | Included |  |
| Shell shard cache: Sands of Karak #6 | Shardilard Ledge | None |  |  | Included |  |
| Shell shard cache: Sands of Karak #7 | Shardilard Ledge | None |  |  | Included |  |
| Shell Shard cache: Not in Archi No id | Shardilard Ledge | None |  |  | Not included |  |
| Shardilard | Shardilard Ledge | None |  |  | Not included | Should these be included? |

### Sands of Karak Entrance (Coral_25)

**Game ID:** Coral_25

**Contributors:** Pyxl

#### Subrooms

- Top
- Bottom

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | bot1 | Bottom | [Windy Pinstress Entrance (Coral_34)](#windy-pinstress-entrance-coral34) | T | None | TODO |  |  |
| R | right1 | Top | [Sands of Karak Lower Left Long Room (Coral_23)](#sands-of-karak-lower-left-long-room-coral23) | LL | None |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BS | Big Shaft | Bottom | Top | Silk soar OR ( Cling Grip AND ( Easy Skips OR  Clawline ) ) |  |  |  |
| BS | Big Shaft | Top | Bottom | None |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Lore | Top | Silk soar OR ( Cling grip AND ( Faydown Cloak OR Dash OR Drifters Cloak OR Clawline OR Sharpdart ) ) or ( Scuttlebrace and faydown Cloak ) |  |  | Not included |  |

### Sands of Karak Lower Left Long Room (Coral_23)

**Game ID:** Coral_23

**Contributors:** Pyxl

#### Subrooms

- Lower Entrance
- Centre Platform
- Upper Left Platform
- Hidden Exit
- Right Exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | left2 | Hidden Exit | [Watcher at the Edge (Coral_39)](#watcher-at-the-edge-coral39) | R | None |  |  |  |
| R | right1 | Right Exit | [Sands of Karak Tall Centre Room (Coral_35b)](#sands-of-karak-tall-centre-room-coral35b) | LL | None |  |  |  |
| LL | left1 | Lower Entrance | [Sands of Karak Entrance (Coral_25)](#sands-of-karak-entrance-coral25) | R | None |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LN | Lower Nut Platforming | Lower Entrance | Centre Platform | Dash OR Clawline OR Drifters Cloak OR Faydown Cloak OR Beast Crest OR Sharpdart OR ( Reaper Crest AND Ledge Grab ) |  |  |  |
| LN | Lower Nut Platforming | Centre Platform | Lower Entrance | Clawline OR ( Dash AND Sprint AND Faydown Cloak AND Drifters Cloak ) |  |  |  |
| UP | Upper Left Nut Platforming | Centre Platform | Upper Left Platform | ( Cling grip OR Silk Soar ) AND ( Dash OR Clawline OR Sharpdart OR Faydown Cloak OR Drifters Cloak ) OR ( Silk Soar AND Beast Crest ) |  |  |  |
| UP | Upper Left Nut Platforming | Upper Left Platform | Centre Platform | Dash OR Clawline OR Beast Crest OR Drifters Cloak OR Faydown Cloak OR Sharpdart |  |  |  |
| HD | Hidden Shaft | Upper Left Platform | Hidden Exit | Silk Soar |  |  |  |
| HD | Hidden Shaft | Hidden Exit | Upper Left Platform | None |  |  |  |
| RN | Right Nut Platforming | Centre Platform | Right Exit | Cling Grip AND ( Dash OR Drifters Cloak OR Clawline OR Sharpdart OR ( Faydown Cloak AND Beast Crest  ) ) |  |  |  |
| RN | Right Nut Platforming | Right Exit | Centre Platform | Clawline AND ( Dash OR Drifters Cloak OR Faydown Cloak OR Sharpdart ) OR ( Drifters Cloak AND Sharpdart AND 16 Max silk ) |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Memory Locket #15 | Upper Left Platform | None |  |  | Included |  |

### Sands of Karak Lower Right Long Room (Coral_24)

**Game ID:** Coral_24

**Contributors:** Pyxl

#### Subrooms

- Left Exit
- Flea Ledge
- Lower Centre Platform
- Upper Centre Platform
- Right Exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Left Exit | [Sands of Karak Tall Centre Room (Coral_35b)](#sands-of-karak-tall-centre-room-coral35b) | LR | None |  |  |  |
| R | right1 | Right Exit | [Sands of Karak Right Side Tall room (Coral_26)](#sands-of-karak-right-side-tall-room-coral26) | LL | None |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LW | Left Wall | Left Exit | Flea Ledge | Silk Soar |  |  |  |
| LW | Left Wall | Flea Ledge | Left Exit | None |  |  |  |
| LN | Lower Left Nut Platforms | Left Exit | Lower Centre Platform | Beast Crest OR Dash OR Clawline OR Faydown Cloak OR Drifters Cloak OR Sharpdart OR ( Ledge grab AND ( Reaper crest OR Shamen Crest OR Hunters Crest OR Wanderers Crest ) ) |  |  |  |
| LN | Lower Left Nut Platforms | Lower Centre Platform | Left Exit | ( Drifters Cloak AND ( Clawline OR Beastcrest OR Dash OR Faydown Cloak ) ) OR ( Clawline AND ( Shamen crest OR Faydown Cloak OR Silk Soar OR Beast Crest ) ) OR ( Faydown Cloak AND ( Beast Crest OR Sharpdart ) ) |  |  |  |
| UN | Upper Left Nut Platforms | Upper Centre Platform | Flea Ledge | "( Cling grip AND Clawline ) OR ( Clawline AND ( Drifters Cloak AND ( hunter Crest OR Reaper Crest OR Wanderer Crest OR Shaman Crest ) ) OR Faydown Cloak ) " |  |  |  |
| UN | Upper Left Nut Platforms | Flea Ledge | Upper Centre Platform | Not happening |  | Needs verification |  |
| RN | Right Nut Platforms | Upper Centre Platform | Right Exit | ( Cling grip AND  ( ( Clawline OR Drifters Cloak ) OR Beast Crest ) ) |  |  |  |
| RN | Right Nut Platforms | Right Exit | Upper Centre Platform | None |  |  |  |
| CN | Centre Platforms | Lower Centre Platform | Upper Centre Platform | Faydown Cloak OR Sprint OR ( Dash AND ( Ledge grab OR Cling grip ) ) OR Drifters Cloak OR Clawline OR Sharpdart OR Silksoar OR Beast Crest OR ( Architect Crest AND Needle Strike ) |  |  |  |
| CN | Centre Platforms | Upper Centre Platform | Lower Centre Platform | None |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Shell Shard Cache: Sands of Karak #1 | Lower Centre Platform | None |  |  | Included |  |
| Shell Shard Cache: Sands of Karak #2 | Lower Centre Platform | None |  |  | Included |  |
| Flea: Sands of Karak | Flea Ledge | None |  |  | Included |  |

### Sands of Karak Right Side Tall room (Coral_26)

**Game ID:** Coral_26

**Contributors:** Pyxl

#### Subrooms

- Centre
- Bottom
- Top

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | left2 | Top | [Sands of Karak Upper Right Long Room (Coral_44)](#sands-of-karak-upper-right-long-room-coral44) | R | None |  |  |  |
| LL | left1 | Centre | [Sands of Karak Lower Right Long Room (Coral_24)](#sands-of-karak-lower-right-long-room-coral24) | R | None |  |  |  |
| R | right1 | Centre | [Sands of Karak Elevator to Blasted Steps (Coral_38)](#sands-of-karak-elevator-to-blasted-steps-coral38) | L | None |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TS1 | Tall Shaft1 | Centre | Bottom | None |  |  |  |
| TS1 | Tall Shaft1 | Bottom | Centre | Cling Grip |  |  |  |
| TS2 | Tall Shaft2 | Top | Bottom | None |  |  |  |
| TS2 | Tall Shaft2 | Bottom | Top | Cling Grip AND ( Clawline OR Faydown Cloak OR ( Ledge Grab AND ( Drifters Cloak OR Dash ) OR ( Beast Crest AND Needle Strike ) ) |  |  |  |
| TS3 | Tall Shaft3 | Top | Centre | None |  |  |  |
| TS3 | Tall Shaft3 | Centre | Top | Silk Soar AND Cling grip AND ( Dash OR Clawline OR Sharpdart OR Faydown Cloak OR Drifters Cloak ) OR ( Beast Crest AND Needle Strike ) |  |  |  |

#### Check Locations

No check locations defined.

### Sands of Karak Tall Centre Room (Coral_35b)

**Game ID:** Coral_35b

**Contributors:** Pyxl

#### Subrooms

- Ground Level
- Shakra Ledge
- Stalactite
- Crust Nut Ledge
- Bridge Level
- Voltnest Level

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| D | door1 | Voltnest Level | TODO |  | None |  |  |  |
| LL | left3 | Ground Level | [Sands of Karak Lower Left Long Room (Coral_23)](#sands-of-karak-lower-left-long-room-coral23) | R | None |  |  |  |
| F | bot1 | Ground Level | [Blasted Steps Thin Long Vertical (Coral_35)](#blasted-steps-thin-long-vertical-coral35) | T | Giant Stalactite Above broken | TODO |  |  |
| LR | right2 | Ground Level | [Sands of Karak Lower Right Long Room (Coral_24)](#sands-of-karak-lower-right-long-room-coral24) | L | Break Wall |  |  |  |
| UL | left2 | Bridge Level | [Sands of Karak Upper Left Long Room (Coral_27)](#sands-of-karak-upper-left-long-room-coral27) | R | None |  |  |  |
| UML | left5 | Crust Nut Ledge | [Crustnut (Coral_41)](#crustnut-coral41) | R | Break Wall |  |  |  |
| UR | right1 | Bridge Level | [Sands of Karak Upper Right Long Room (Coral_44)](#sands-of-karak-upper-right-long-room-coral44) | L | None |  |  |  |
| ULL | left4 | Shakra Ledge | [Sands of Shakra (Coral_40)](#sands-of-shakra-coral40) | R | None |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LS | Lower Shaft | Ground Level | Shakra Ledge | Silk Soar OR ( Faydown Cloak AND ( Cling grip OR ( Dash AND Scuttlebrace ) ) ) OR ( Cling grip AND ( Dash OR Sprint OR Drifters Cloak OR Clawline OR Sharpdart ) OR ( ( Beast Crest OR Architect Crest ) AND Needle Strike ) |  |  |  |
| LS | Lower Shaft | Shakra Ledge | Ground Level | None |  |  |  |
| ST1 | Stalactite | Ground Level | Stalactite | Silk Soar |  |  |  |
| ST1 | Stalactite | Stalactite | Ground Level | None |  |  |  |
| ST2 | Stalactite2 | Shakra Ledge | Stalactite | ( ( Dash AND Scuttlebrace ) OR Cling grip ) AND ( Dash OR Sprint OR Drifters Cloak OR Faydown Cloak OR Sharp Dart OR Clawline )  OR ( Cling Grip AND ( Beast Crest OR Hunter Crest OR Shaman Crest OR ( ( Reaper Crest OR Architect Crest ) AND Needle Strike ) ) |  |  |  |
| St2 | Stalactite2 | Stalactite | Shakra Ledge | None |  |  |  |
| US1 | Upper Shaft1 | Shakra Ledge | Crust Nut Ledge | ( Dash AND Scuttlebrace ) OR ( Cling grip AND ( Dash AND ( Ledge Grab OR Shamen Crest ) ) OR Clawline OR Faydown Cloak OR Sharpdart ) OR ( Cling Grip AND ( Beast Crest OR Hunter Crest OR ( Reaper Crest AND Needle Strike ) ) |  |  |  |
| US1 | Upper Shaft1 | Crust Nut Ledge | Shakra Ledge | None |  |  |  |
| US2 | Upper Shaft2 | Crust Nut Ledge | Bridge Level | Upper Stalactite Broken AND ( ( Dash AND Scuttlebrace AND Faydown Cloak ) OR Cling grip OR ( Silk Soar AND Faydown Cloak AND ( Ledge Grab OR Clawline OR Sharp Dart ) ) ) OR Faydown Cloak OR ( ( Silk Soar ) AND ( Architect Crest OR Witch Crest OR Reaper Crest OR Shaman Crest OR ( Wanderer Crest AND ( ledge grab or Dash OR Sharp Dart OR Clawline OR Drifters Cloak ) ) ) ) |  |  |  |
| US2 | Upper Shaft2 | Bridge Level | Crust Nut Ledge | Upper Stalactite Broken |  |  |  |
| VS | Voltwyrm Shaft | Bridge Level | Voltnest Level | ( Cling Grip AND Faydown Cloak AND ( Clawline OR Dash OR Sharpdart )  ) OR(  Silk soar AND ( Cling Grip OR Faydown Cloak OR ( Dash AND Scuttlebrace ) ) ) OR ( Faydown Cloak AND Beast Crest AND Needle Strike AND Cling Grip ) OR ( ( ( ( Architect Crest OR Reaper Crest ) AND Needle strike ) OR Shaman Crest ) AND Cling Grip AND Faydown Cloak ) |  |  |  |
| VS | VoltWyrm Shaft | Voltnest Level | Bridge Level | None |  |  |  |

#### Check Locations

No check locations defined.

### Sands of Karak Upper Left Long Room (Coral_27)

**Game ID:** Coral_27

**Contributors:** Pyxl

#### Subrooms

- Right Ledge
- Left Ledge
- Shell Ledge

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Left Ledge | [Coral Tower Entrance (Coral_28)](#coral-tower-entrance-coral28) | R | None |  |  |  |
| R | right1 | Right Ledge | [Sands of Karak Tall Centre Room (Coral_35b)](#sands-of-karak-tall-centre-room-coral35b) | UL | None |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| WR | Whole Room | Left Ledge | Right Ledge | Beast Crest OR Clawline OR Faydown Cloak OR Drifters Cloak OR Sharpdart OR Dash |  |  |  |
| WR | Whole Room | Right Ledge | Left Ledge | Cling Grip AND ( ( ( Dash OR Drifters Cloak OR Faydown Cloak ) AND Sprint ) OR Clawline OR Sharpdart ) OR ( Faydown Cloak AND Clawline ) |  |  |  |
| DR | Drop | Left Ledge | Shell Ledge | Hunters Crest OR Beast Crest OR Architect Crest OR Shamen Crest OR ( Ledge grab AND ( Reaper crest OR Witch Crest ) ) OR Dash OR Clawline OR Sharpdart OR Drifters Cloak OR Faydown Cloak OR ( Wanderer crest AND Needle Strike ) |  |  |  |
| DR | Drop | Shell Ledge | Left Ledge | Ledge Grab OR Clawline OR Faydown Cloak OR Beast Crest |  |  |  |

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Shell shard cache: Sands of Karak #3 | Shell Ledge | None |  |  | Included |  |
| Shell Shard cache: Not included | Shell Ledge | None |  |  | Not included |  |
| Boss: Raging Conchfly | Left Ledge | Proficient Combat OR 2 x Needle Upgrade |  |  | Included |  |

### Sands of Karak Upper Right Long Room (Coral_44)

**Game ID:** Coral_44

**Contributors:** Pyxl

#### Subrooms

- Left Exit
- Right Exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Left Exit | [Sands of Karak Tall Centre Room (Coral_35b)](#sands-of-karak-tall-centre-room-coral35b) | UR | None |  |  |  |
| R | right1 | Right Exit | [Sands of Karak Right Side Tall room (Coral_26)](#sands-of-karak-right-side-tall-room-coral26) | UL | None |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| WR | Whole Room | Left Exit | Right Exit | Cling grip AND ( Clawline OR ( Faydown Cloak AND ( Dash OR Sharpdart OR Drifters Cloak ) ) |  |  |  |
| WR | Whole Room | Right Exit | Left Exit | Clawline AND ( Drifters Cloak OR Shamen Crest ) AND ( Cling grip OR Silk Soar ) |  |  |  |

#### Check Locations

No check locations defined.

### Sands of Shakra (Coral_40)

**Game ID:** Coral_40

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Sands of Karak Tall Centre Room (Coral_35b)](#sands-of-karak-tall-centre-room-coral35b) | ULL | None |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Map: Sands of Karak |  | None |  |  | Included |  |
| Shell Shard Cache: Sands of Karak #9 |  | Faydown Cloak OR Cling Grip OR Silk Soar OR Thread Storm OR Rune Rage OR ( Beast Crest AND Needle Strike ) |  |  | Included |  |
| Shell Shard Cache: Sands of Karak #10 |  | Faydown Cloak OR Cling Grip OR Silk Soar OR Thread Storm OR Rune Rage OR ( Beast Crest AND Needle Strike ) |  |  | Included |  |

### Watcher at the Edge (Coral_39)

**Game ID:** Coral_39

**Contributors:** Pyxl

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 |  | [Sands of Karak Lower Left Long Room (Coral_23)](#sands-of-karak-lower-left-long-room-coral23) | UL | None |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Watcher at the edge |  | Needolin AND ( 2 x Needle upgrade OR Proficient combat ) |  |  | Included |  |
| Grey Memento |  | Needolin AND ( 2 x Needle upgrade OR Proficient combat ) |  |  | Included |  |

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

## Mount Fay

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
| BB | bone bottom |  | [Bone Bottom Bellway (Bellway_01)](#bone-bottom-bellway-bellway01) | BB | bone bottom bellway unlocked |  |  |  |
| TM | the marrow |  | [The Marrow Bellway (Bone_05)](#the-marrow-bellway-bone05) | BB | the marrow bellway unlocked | TODO |  |  |
| DD | deep docks |  | [Deep Docks Bellway (Bellway_02)](#deep-docks-bellway-bellway02) | BB | deep docks bellway unlocked |  |  |  |
| FF | far fields |  | [Far Fields Bellway (Bellway_03)](#far-fields-bellway-bellway03) | BB | far fields bellway unlocked |  |  |  |
| GM | greymoor |  | TODO |  | greymoor bellway unlocked | TODO |  |  |
| BH | bellhart |  | [Bellhart Bellway (Belltown_basement)](#bellhart-bellway-belltownbasement) | BH | bellhart bellway unlocked |  |  |  |
| SW | shellwood |  | [Shellwood Bellway  (Shellwood_19)](#shellwood-bellway) | BB | shellwood bellway unlocked |  |  |  |
| BS | blasted steps |  | [Blasted Steps Bellway (Bellway_08)](#blasted-steps-bellway-bellway08) | BB | blasted steps bellway unlocked |  |  |  |
| TS | the slab |  | TODO |  | the slab bellway unlocked | TODO |  |  |
| GB | grand bellway |  | [Grand Bellway (Bellway_City)](#grand-bellway-bellwaycity) | BW | grand bellway bellway unlocked | TODO |  |  |
| BW | bilewater |  | TODO |  | bilewater bellway unlocked | TODO |  |  |
| PD | putrified ducts |  | TODO |  | putrified ducts bellway unlocked | TODO |  |  |

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
| HH | high halls |  | [High Halls Ventrica (Hang_06b)](#high-halls-ventrica-hang06b) | V |  | TODO |  |  |
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
