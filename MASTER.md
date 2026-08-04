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

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| LL | lower left | rock bottom | [Moss Grotto West (Tut_02)](#moss-grotto-west-tut02) | LR | break vines |  |
| ML | middle left | lower crossing | [Moss Grotto West (Tut_02)](#moss-grotto-west-tut02) | UR | none |  |
| UL | upper left | upper crossing | [Ruined Chapel (Tut_03)](#ruined-chapel-tut03) | R | break vines |  |
| LR | lower right | lower crossing | [Moss Grotto East (Tut_01b)](#moss-grotto-east-tut01b) | LL | none |  |
| UR | upper right | upper crossing | [Moss Grotto East (Tut_01b)](#moss-grotto-east-tut01b) | UL | none |  |
| C | ceiling | up and away | [Bone Bottom (Bonetown)](#bone-bottom-bonetown) | F | has loading zone blocker until you first leave moss grotto | maybe see if removing this loading zone makes sense? |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | Notes |
| --- | --- | --- | --- | --- | --- |
| S1 | shaft 1 | up and away | upper crossing | none (falling) |  |
| S1 | shaft 1 | upper crossing | up and away | silk soar OR ( cling grip AND ( faydown cloak OR run OR dash OR sharpdart OR clawline) ) | might be some crest options - basically anything that give ANY horizontal distance will enable this claw grip |
| S2 | shaft 2 | upper crossing | center shaft | none (falling) |  |
| S2 | shaft 2 | center shaft | upper crossing | silk soar OR cling grip |  |
| SV | side room vines | center shaft | side room | break vines |  |
| SV | side room vines | side room | center shaft | break vines |  |
| S3 | shaft 3 | center shaft | lower crossing | none (falling) |  |
| S3 | shaft 3 | lower crossing | center shaft | silk soar OR cling grip |  |
| S4 | shaft 4 | lower crossing | rock bottom | none (falling) |  |
| S4 | shaft 4 | rock bottom | lower crossing | silk soar OR ( cling grip AND faydown cloak ) |  |

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| frayed rosary string moss grotto | rock bottom | none |  |
| shell shard cache moss grotto 1 | lower crossing | none |  |
| moss grotto beast shard | rock bottom | none | NOT YET RANDOMIZED right at game start jump into right room and again into right into upper right room ; Not included in Archipelago world |
| moss grotto rosary chest | side room | none | NOT YET RANDOMIZED; Not included in Archipelago world |

#### Notes

renamed from "moss grotto west" - was mistakenly marked as same room as west room
not having the west part as part of this area causes the graph to be more complex

### Moss Grotto West (Tut_02)

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| UR | upper right |  | [Moss Grotto Center (Tut_01)](#moss-grotto-center-tut01) | ML | none |  |
| LR | lower right |  | [Moss Grotto Center (Tut_01)](#moss-grotto-center-tut01) | LL | none |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| shell shard cache moss grotto 5 |  | none |  |
| shell shard cache moss grotto 6 |  | none |  |
| shell shard cache moss grotto 7 |  | none |  |
| moss grotto west mossberry |  | none |  |

#### Notes

somehow missed this being its own room before

### Moss Grotto East (Tut_01b)

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| UL | upper left |  | [Moss Grotto Center (Tut_01)](#moss-grotto-center-tut01) | UR | none |  |
| LL | lower left |  | [Moss Grotto Center (Tut_01)](#moss-grotto-center-tut01) | LR | none |  |
| WD | weavenest door |  | [Weavenest Atla Entrance (Weave_04)](#weavenest-atla-entrance-weave04) | WD | needolin |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| shell shard cache moss grotto 2 |  | none |  |
| shell shard cache moss grotto 3 |  | none |  |
| shell shard cache moss grotto 4 |  | none |  |
| moss grotto east mossberry |  | easy skips enabled OR ( run OR dash OR drifter's cloak OR faydown cloak OR silk soar OR clawline OR sharpdart OR shaman crest OR ) |  |

### Ruined Chapel (Tut_03)

#### Subrooms

- chapel
- boss room
- bench room

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| R | right | bench room | [Moss Grotto Center (Tut_01)](#moss-grotto-center-tut01) | UL | none |  |
| AR | ascend rope | chapel | [Bone Bottom (Bonetown)](#bone-bottom-bonetown) | DR | none |  |
| CD | chapel door | chapel | [Ruined Chapel Interior](#ruined-chapel-interior) | CD | unknown OR ruined chapel access override | randomizer currently forces the door open under some conditions |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | Notes |
| --- | --- | --- | --- | --- | --- |
| RB | right boss entrance | bench room | boss room | break vines |  |
| RB | right boss entrance | boss room | bench room | moss mother defeated |  |
| LB | left boss entrance | chapel | boss room | none |  |
| LB | left boss entrance | boss room | chapel | moss mother defeated |  |

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| moss mother boss fight | boss room |  |  |

#### Notes

ROOM BUG: fighting moss mother without breaking the vines on the right side of the arena (by approaching from the left), you get locked into the arena with darkness still covering the area.

### Ruined Chapel Interior

#### Subrooms

- ritual chamber
- crest chamber

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| CD | chapel door | ritual chamber | [Ruined Chapel (Tut_03)](#ruined-chapel-tut03) | CD | TODO | TODO |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | Notes |
| --- | --- | --- | --- | --- | --- |
| SS | silk soar spot | ritual chamber | crest chamber | silk soar |  |
| SS | silk soar spot | crest chamber | ritual chamber | silk soar |  |

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

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| UL | upper left | upper left platforms | [Bonegrave (Bonegrave)](#bonegrave-bonegrave) | UR | none |  |
| LL | lower left | ground level | [Bonegrave (Bonegrave)](#bonegrave-bonegrave) | LR | door opened from other side |  |
| DR | descend rope | ground level | [Ruined Chapel (Tut_03)](#ruined-chapel-tut03) | AR | none |  |
| F | floor | ground level | [Moss Grotto Center (Tut_01)](#moss-grotto-center-tut01) | C | none |  |
| BD | bellway door | ground level | [Bone Bottom Bellway (Bellway_01)](#bone-bottom-bellway-bellway01) | BD | none |  |
| LR | lower right | ground level | [The Marrow Entrance (Bone_01)](#the-marrow-entrance-bone01) | LL | none |  |
| UR | upper right | upper right platforms | [Mosshome Basement (Bone_01b)](#mosshome-basement-bone01b) | LL | none |  |
| RC | right ceiling | upper right platforms | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | RF | none |  |
| LC | left ceiling | sky | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | LF | silk soar |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | Notes |
| --- | --- | --- | --- | --- | --- |
| CC | climb chapel | ground level | chapel roof | silk soar OR ( cling grip AND ( LL door NOT opened OR faydown cloak ) ) |  |
| SM | soar to middle platforms | ground level | upper middle platforms | silk soar |  |
| SS | soar to sky exit | ground level | sky | silk soar |  |
| SR | soar to right platforms | ground level | upper right platforms | silk soar |  |
| EV | elevator | ground level | upper right platforms | elevator switch flipped |  |
| CC | climb chapel | chapel roof | ground level | none |  |
| CR | climb roof | chapel roof | upper left platforms | silk soar OR cling grip |  |
| CR | climb roof | upper left platforms | chapel roof | none |  |
| MD | middle platform drift | upper middle platforms | chapel roof | drifter's cloak OR clawline OR ( dash + sharpdart ) |  |
| SM | soar to middle platforms | upper middle platforms | ground level | none |  |
| CL | clawline across the sky | upper middle platforms | upper right platforms | clawline |  |
| CL | clawline across the sky | upper right platforms | upper middle platforms | clawline |  |
| SR | soar to right platforms | upper right platforms | ground level | none |  |
| DL | sky drift to right platforms | sky | upper right platforms | drifter's cloak OR horizontal movement tech |  |
| DR | sky drift to middle platforms | sky | upper middle platforms | drifter's cloak OR horizontal movement tech |  |
| SS | soar to sky exit | sky | ground level | none |  |

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| bone bottom mossberry | upper right platforms | none |  |
| elevator switch | upper right platforms | none | Not included in Archipelago world |
| rosary cache bone bottom 8 | upper right platforms | none |  |
| rosary cache bone bottom 9 | upper right platforms | none |  |
| weaver effigy camora moss grotto | upper middle platforms | none |  |
| rosary dish bone bottom | upper middle platforms | none | NOT CURRENTLY RANDOMIZED; Not included in Archipelago world |
| mask shard pebbs shop grindle act 3 | ground level |  | pebb's shop |
| simple key | ground level |  | pebb's shop |
| bone bottom shop craft metal | ground level |  | pebb's shop |
| magnetite broach | ground level |  | pebb's shop |
| wish bone bottom repairs | ground level |  |  |
| wish a life saving bridge | ground level |  |  |
| wish an icon of hope | ground level |  |  |
| wish garb of the pilgrims | ground level |  |  |
| wish volatile flintbeetles | ground level |  |  |
| wish the terrible tyrant | ground level |  |  |
| wish bone bottom supplies | ground level |  |  |
| boss skull tyrant | ground level |  |  |
| shell shard cache bone bottom | ground level |  | is this breaking the statue? STILL MARKED AS ??? ON TRACKER |

### Bone Bottom Bellway (Bellway_01)

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| BD | bellway door |  | [Bone Bottom (Bonetown)](#bone-bottom-bonetown) | BD | none |  |
| BB | bell beast |  | [Bellway Menu](#bellway-menu) | BB | bell beast available AND bone bottom bellway unlocked | TODO |

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

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| UR | upper right | upper right exit | [Bone Bottom (Bonetown)](#bone-bottom-bonetown) | UL | none |  |
| LR | lower right | graveyard | [Bone Bottom (Bonetown)](#bone-bottom-bonetown) | LL | none |  |
| C | ceiling | upper left exit | [Wormways Lower East (Crawl_07)](#wormways-lower-east-crawl07) | F | silk soar OR cling grip |  |
| CD | chapel door | graveyard | [Chapel of the Wanderer (Chapel_Wanderer)](#chapel-of-the-wanderer-chapelwanderer) | CD | no wanderer's crest OR wanderer's door override | "wanderer's door override" is meant to cover any situation that would require the door to stay open, such as rosary cache rando |
| LL | lower left | graveyard | [Bonegrave Passage](#bonegrave-passage) | R | steel soul |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | Notes |
| --- | --- | --- | --- | --- | --- |
| CL | climb | graveyard | upper right exit | cling grip OR silk soar |  |
| CL | climb | upper right exit | graveyard | none (falling) |  |
| BW | breakable wall | upper left exit | upper right exit | none (break wall from this side) |  |
| BW | breakable wall | upper right exit | upper left exit | wall broken from other side |  |

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| boneyard mossberry | graveyard | none | can be gotten with only jump -tested |
| rosary cache bone bottom 6 | upper right exit | none |  |
| rosary cache bone bottom 7 | upper right exit | none |  |
| rosaries on grave | graveyard | none | NOT CURRENTLY RANDOMIZED; Not included in Archipelago world |

### Bonegrave Passage

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| R | right |  | [Bonegrave (Bonegrave)](#bonegrave-bonegrave) | LL | steel soul | Needs verification |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| summoned savior boss fight |  | TODO (steel soul only?) | TODO |

### Chapel of the Wanderer (Chapel_Wanderer)

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| CD | chapel door |  | [Bonegrave (Bonegrave)](#bonegrave-bonegrave) | CD | none | apworld may force open; Needs verification |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| wanderer's crest |  | none | Needs verification |
| rosary cache bongrave 1 |  | none |  |
| rosary cache bongrave 2 |  | none |  |
| rosary cache bongrave 3 |  | none |  |
| rosary cache bongrave 4 |  | none |  |

#### Notes

need see if there are other checks in here

### Mosshome Upper (Mosstown_02)

#### Subrooms

- main area
- bottom right area
- upper left area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| LF | left floor | main area | [Mosshome Middle (Mosstown_01)](#mosshome-middle-mosstown01) | C | none |  |
| L | left | main area | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | MR | none |  |
| RF | right floor | bottom right area | [Mosshome Side Room (Bone_05b)](#mosshome-side-room-bone05b) | C | none |  |
| R | right | bottom right area | [Mosshome Druid (Mosstown_02c)](#mosshome-druid-mosstown02c) | L | none |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | Notes |
| --- | --- | --- | --- | --- | --- |
| RS | right silk blockade | main area | bottom right area | can break silk blockade |  |
| RS | right silk blockade | bottom right area | main area | can break silk blockade |  |
| LS | left silk blockade | main area | upper left area | can break silk blockade |  |
| LS | left silk blockade | upper left area | main area | none (cut to open pathway) |  |

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| silkspear | main area | none |  |
| frayed rosary string bone bottom silkspear passage | upper left area | none | seems to be misnamed in the apworld |
| rosary cache mosshome 3 | main area | none |  |
| rosary cache mosshome 4 | main area | none |  |

### Mosshome Middle (Mosstown_01)

#### Subrooms

- main area
- upper right area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| LR | lower right | main area | [The Marrow Bellway (Bone_05)](#the-marrow-bellway-bone05) | L | none |  |
| UR | upper right | upper right area | [Mosshome Side Room (Bone_05b)](#mosshome-side-room-bone05b) | L | none |  |
| F | floor | main area | [Mosshome Lower (Bone_11)](#mosshome-lower-bone11) | C | flip the switch in this area |  |
| C | ceiling | main area | [Mosshome Upper (Mosstown_02)](#mosshome-upper-mosstown02) | LF |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | Notes |
| --- | --- | --- | --- | --- | --- |
| RJ | running jump | main area | upper right area | run OR dash OR silk soar OR faydown cloak OR clawline or sharpdart |  |
| RJ | running jump | upper right area | main area | none |  |

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| flip switch to open floor exit | main area | none |  |
| rosary cache mosshome 1 | main area | none |  |
| rosary cache mosshome 2 | main area | none |  |

### Mosshome Lower (Bone_11)

#### Subrooms

- main area
- upper left exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| LR | lower right | main area | [The Marrow Shakra Intro (Bone_04)](#the-marrow-shakra-intro-bone04) | LL | none |  |
| UR | upper right | main area | [The Marrow Shakra Intro (Bone_04)](#the-marrow-shakra-intro-bone04) | UL | none |  |
| L | left | upper left exit | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | LR | none |  |
| C | ceiling | upper left exit | [Mosshome Middle (Mosstown_01)](#mosshome-middle-mosstown01) | F | must be opened from the other side |  |
| F | floor | main area | [Mosshome Spool (Bone_11b)](#mosshome-spool-bone11b) | C | must be opened from the other side |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | Notes |
| --- | --- | --- | --- | --- | --- |
| RJ | running jump | main area | upper left exit | easy skips enabled OR run OR dash OR  faydown cloak OR silk soar OR clawline OR sharpdart OR beast crest OR shaman crest |  |
| RJ | running jump | upper left exit | main area | none (falling) |  |

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| rosary cache bone bottom 4 | main area | none |  |
| rosary cache bone bottom 5 | main area | none |  |

### Mosshome Side Room (Bone_05b)

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [Mosshome Middle (Mosstown_01)](#mosshome-middle-mosstown01) | UR | none |  |
| C | ceiling |  | [Mosshome Upper (Mosstown_02)](#mosshome-upper-mosstown02) | RF | none |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| mosshome mossberry |  | none |  |

### Mosshome Druid (Mosstown_02c)

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [Mosshome Upper (Mosstown_02)](#mosshome-upper-mosstown02) | R | none |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| wish berry picking |  | TODO | this just gets you druid's eye; Not included in Archipelago world |
| druid's eye |  | progressive mossberry (3) | TRACKER WRONG POSITION |
| druid's eyes |  | progressive mossberry (7) | TRACKER WRONG POSITION |

### Mosshome Spool (Bone_11b)

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| R | right |  | [Mosshome Basement (Bone_01b)](#mosshome-basement-bone01b) | UL | none |  |
| C | ceiling |  | [Mosshome Lower (Bone_11)](#mosshome-lower-bone11) | F | switch in room activated |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| bone bottom spool fragment |  | none |  |
| floor switch to open ceiling exit |  | none |  |

### Mosshome Basement (Bone_01b)

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| LL | lower left |  | [Bone Bottom (Bonetown)](#bone-bottom-bonetown) | UR | none |  |
| UL | upper left |  | [Mosshome Spool (Bone_11b)](#mosshome-spool-bone11b) | R | none | Imported destination text: mosshome spool fragment |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| rosary cache the marrow mosslands passage 1 |  | none |  |
| rosary cache the marrow mosslands passage 2 |  | none |  |
| rosary dish |  |  | NOT CURRENTLY RANDOMIZED; Not included in Archipelago world |

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

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| C | ceiling | top area | blasted bridge | F | silk soar |  |
| UR | upper right | upper right ledge | shellwood grand gate bell | L | none |  |
| MR | middle right | middle right ledge | [Mosshome Upper (Mosstown_02)](#mosshome-upper-mosstown02) | L | breakable wall -must be opened from the other side (NEEDS VERIFICATION) | Needs verification |
| LR | lower right | lower right area | [Mosshome Lower (Bone_11)](#mosshome-lower-bone11) | L | none |  |
| UL | upper left | upper left ledge | [Wormways Upper East (Crawl_01)](#wormways-upper-east-crawl01) | R | none |  |
| LL | lower left | lower left area | [Wormways Craggler Hallway (Crawl_04)](#wormways-craggler-hallway-crawl04) | R | none |  |
| LF | left floor | bottom area | [Bone Bottom (Bonetown)](#bone-bottom-bonetown) | LC | none |  |
| RF | right floor | lower right area | [Bone Bottom (Bonetown)](#bone-bottom-bonetown) | RC | none |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | Notes |
| --- | --- | --- | --- | --- | --- |
| F1 | top fall | top area | upper right ledge | none (falling) |  |
| F2 | upper right ledge fall | upper right ledge | upper left ledge | none (falling |  |
| F3 | upper left ledge fall | upper left ledge | wish ledge | none (falling) |  |
| F4 | wish ledge fall | wish ledge | upper silk soar only zone | none (falling) |  |
| F5 | upper silk soar zone fall | upper silk soar only zone | middle right ledge | none (falling) |  |
| F6 | middle right ledge fall | middle right ledge | lower silk soar only zone | none (falling) |  |
| F7 | lower silk soar zone fall | lower silk soar only zone | bottom area | none (falling) |  |
| F8 | lower left area fall | lower left area | bottom area | none (falling) |  |
| F9 | lower right area fall | lower right area | bottom area | none (falling) |  |
| S1 | bottom silk soar | bottom area | lower silk soar only zone | silk soar |  |
| S2 | lower zone silk soar | lower silk soar only zone | upper silk soar only zone | silk soar |  |
| S3 | upper zone silk soar | upper silk soar only zone | top area | silk soar |  |
| LC | lower crossing | lower left area | lower right area | easy skips enabled OR silk soar OR horizontal movement tech OR dash OR run OR cling grip OR faydown cloak OR silk soar |  |
| LC | lower crossing | lower right area | lower left area | easy skips enabled OR silk soar OR horizontal movement tech OR dash OR run OR cling grip OR faydown cloak |  |
| WC | wish climb | wish ledge | upper left ledge | silk soar OR cling grip |  |
| UC | upper crossing | upper left ledge | upper right ledge | silk soar OR cling grip OR faydown cloak OR clawline OR sharpdart OR dash |  |
| UC | upper crossing | upper right ledge | upper left ledge | silk soar OR cling grip OR faydown cloak OR clawline OR sharpdart OR dash |  |

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| rosary cache moss grotto | lower left area | none |  |
| choral commandment moss grotto | middle right ledge | none |  |
| wish my missing courier | wish ledge | none |  |

## The Marrow

### The Marrow Entrance (Bone_01)

#### Subrooms

- before gauntlet
- gauntlet room
- after gauntlet
- ceiling exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| LL | lower left | before gauntlet | [Bone Bottom (Bonetown)](#bone-bottom-bonetown) | LR | none |  |
| LR | lower right | after gauntlet | [The Marrow Bell Bench (Bone_01c)](#the-marrow-bell-bench-bone01c) | LL | none |  |
| UR | upper right | before gauntlet | [The Marrow Bell Bench (Bone_01c)](#the-marrow-bell-bench-bone01c) | UL | none (breakable wall) |  |
| C | ceiling | ceiling exit | [The Marrow Shakra Intro (Bone_04)](#the-marrow-shakra-intro-bone04) | F | none |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | Notes |
| --- | --- | --- | --- | --- | --- |
| DS | door switch | before gauntlet | after gauntlet | flipped door switch |  |
| DS | door switch | after gauntlet | before gauntlet | none (can flip door switch) |  |
| UG | upper gauntlet entrance | before gauntlet | gauntlet room | none |  |
| UG | upper gauntlet entrance | gauntlet room | before gauntlet | defeat gauntlet |  |
| LG | lower gauntlet entrance | gauntlet room | after gauntlet | defeat gauntlet |  |
| LG | lower gauntlet entrance | after gauntlet | gauntlet room | defeat gauntlet |  |
| LP | lowered platform | before gauntlet | ceiling exit | platform lowered OR silk soar OR faydown cloak OR ( run AND clawline ) |  |

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| shell shard cache the marrow 1 | before gauntlet | none |  |
| rosary cache the marrow 1 | after gauntlet | none |  |
| rosary cache the marrow 2 | after gauntlet | none |  |
| door switch | after gauntlet | none | Not included in Archipelago world |

### The Marrow Bell Bench (Bone_01c)

#### Subrooms

- falling rocks
- bell bench

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| UL | upper left | falling rocks | [The Marrow Entrance (Bone_01)](#the-marrow-entrance-bone01) | UR | none |  |
| LL | left left | bell bench | [The Marrow Entrance (Bone_01)](#the-marrow-entrance-bone01) | LR | none |  |
| R | right | bell bench | [The Marrow Lava Intro (Bone_02)](#the-marrow-lava-intro-bone02) | L | none |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| rosary cache the marrow 5 | falling rocks | none |  |
| rosary cache the marrow 6 | falling rocks | none |  |
| rosary cache the marrow 3 | bell bench | none |  |
| rosary cache the marrow 4 | bell bench | none |  |
| bench unlock | bell bench | pay monies | NOT CURRENTLY RANDOMIZED; Not included in Archipelago world |

#### Notes

While falling rocks and the bell bench are the same in-game room, there is no connection between them. So no subroom connections here is to be expected.

### The Marrow Lava Intro (Bone_02)

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [The Marrow Bell Bench (Bone_01c)](#the-marrow-bell-bench-bone01c) | R | none |  |
| R | right |  | [The Marrow Lava Track (Bone_16)](#the-marrow-lava-track-bone16) | L | none |  |
| LC | left ceiling |  | [The Marrow Shaft (Bone_03)](#the-marrow-shaft-bone03) | F | none |  |
| RC | right ceiling |  | [The Marrow Flea Caravan (Bone_10)](#the-marrow-flea-caravan-bone10) | F | none |  |

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

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| L | left | left track | [The Marrow Lava Intro (Bone_02)](#the-marrow-lava-intro-bone02) | R | none |  |
| R | right | right track | [The Marrow Lava Docks (Bone_09)](#the-marrow-lava-docks-bone09) | L | none |  |
| C | ceiling | left maze | [The Marrow Skull Tyrant Arena (Bone_15)](#the-marrow-skull-tyrant-arena-bone15) | F | none |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | Notes |
| --- | --- | --- | --- | --- | --- |
| LT | lava track | right track | left track | activate track |  |
| LT | lava track | left track | right track | activate track |  |
| CR | climb right | right track | right maze | cling grip OR silk soar |  |
| CR | climb right | right maze | right track | none (falling) |  |
| CL | climb left | right maze | left maze | cling grip OR faydown cloak |  |
| CL | climb left | left maze | right maze | none (falling) |  |

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| activate track | right track | none | Not included in Archipelago world |
| rosary cache the marrow 11 |  | none | one of these is in right maze; TODO; Not included in Archipelago world |
| rosary cache the marrow 12 |  | none | one of these is in right maze; TODO; Not included in Archipelago world |
| rosary cache the marrow 13 |  | none | one of these is in right maze; TODO; Not included in Archipelago world |

### The Marrow Flea Caravan (Bone_10)

#### Subrooms

- main area
- behind metal gate

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| L | left | main area | [The Marrow Shaft (Bone_03)](#the-marrow-shaft-bone03) | LR | none |  |
| R | right | behind metal gate | [The Marrow Skull Tyrant Arena (Bone_15)](#the-marrow-skull-tyrant-arena-bone15) | L | none |  |
| F | floor | main area | [The Marrow Lava Intro (Bone_02)](#the-marrow-lava-intro-bone02) | RC | none |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | Notes |
| --- | --- | --- | --- | --- | --- |
| DS | door switch | main area | behind metal gate | door switch activated |  |
| DS | door switch | behind metal gate | main area | none (can flip switch from this side) |  |

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| frayed rosary string the marrow flea caravan passage |  | none |  |
| rosary dish |  | none | NOT CURRENTLY RANDOMIZED; TODO; Not included in Archipelago world |
| wish survivor's camp supplies |  | TODO | TODO; TODO |

### The Marrow Shaft (Bone_03)

#### Subrooms

- lower shaft
- upper shaft

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| F | floor | lower shaft | [The Marrow Lava Intro (Bone_02)](#the-marrow-lava-intro-bone02) | LC | none |  |
| LL | lower left | lower shaft | [The Marrow Shaft Side Room (Bone_17)](#the-marrow-shaft-side-room-bone17) | R | none |  |
| ML | middle left | lower shaft | [The Marrow Shakra Intro (Bone_04)](#the-marrow-shakra-intro-bone04) | R | none |  |
| UL | upper left | upper shaft | [The Marrow Bellshrine](#the-marrow-bellshrine) | R | bell must be rung |  |
| LR | lower right | lower shaft | [The Marrow Flea Caravan (Bone_10)](#the-marrow-flea-caravan-bone10) | L | none |  |
| UR | upper right | upper shaft | [The Marrow Mr Burns House (Bone_14)](#the-marrow-mr-burns-house-bone14) | L | none |  |
| C | ceiling | upper shaft | [The Marrow Skull Wall (Bone_06)](#the-marrow-skull-wall-bone06) | F | none |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | Notes |
| --- | --- | --- | --- | --- | --- |
| DS | door switch | lower shaft | upper shaft | door switch flipped |  |
| DS | door switch | upper shaft | lower shaft | none (can flip switch from here) |  |

#### Check Locations

No check locations defined.

#### Notes

no checks

### The Marrow Shaft Side Room (Bone_17)

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| R | right |  | [The Marrow Shaft (Bone_03)](#the-marrow-shaft-bone03) | LL | none |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| shard pendant |  | none |  |

### The Marrow Shakra Intro (Bone_04)

#### Subrooms

- behind gate
- main area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| R | right | main area | [The Marrow Shaft (Bone_03)](#the-marrow-shaft-bone03) | ML | none |  |
| F | floor | main area | [The Marrow Entrance (Bone_01)](#the-marrow-entrance-bone01) | C | none |  |
| LL | lower left | main area | [Mosshome Lower (Bone_11)](#mosshome-lower-bone11) | LR | none |  |
| UL | upper right | behind gate | [Mosshome Lower (Bone_11)](#mosshome-lower-bone11) | UR | none |  |
| C | ceiling | main area | [The Marrow Bellway (Bone_05)](#the-marrow-bellway-bone05) | F | none |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | Notes |
| --- | --- | --- | --- | --- | --- |
| DS | door switch | main area | behind gate | door switch flipped |  |
| DS | door switch | behind gate | main area | none (can flip door switch from this side) |  |

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| lower platform switch (into floor) | main area | lowers platform into the marrow entrance | NOT CURRENTLY RANDOMIZED; Not included in Archipelago world |
| rosary cache the marrow 7 | main area | none |  |
| shell shard cache the marrow 2 | main area | none |  |
| shell shard cache the marrow 3 | main area | none |  |
| quill | main area |  | shakra's shop |
| compass | main area |  | shakra's shop |
| map mosslands | main area |  | shakra's shop |
| map the marrow | main area |  | shakra's shop |
| map bench pins | main area |  | shakra's shop |
| map bellway pins | main area |  | shakra's shop \| appears to be bugged in availability logic still. shows available but isn't |
| mosshome middle door switch | behind gate | none | Not included in Archipelago world |

### The Marrow Bellway (Bone_05)

#### Subrooms

- left area
- boss room
- right area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| L | left | left area | [Mosshome Middle (Mosstown_01)](#mosshome-middle-mosstown01) | LR | none |  |
| F | floor | left area | [The Marrow Shakra Intro (Bone_04)](#the-marrow-shakra-intro-bone04) | C | none |  |
| R | right | right area | [The Marrow Bellshrine](#the-marrow-bellshrine) | L | none |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | Notes |
| --- | --- | --- | --- | --- | --- |
| LB | left boss fight | left area | boss room | none |  |
| LB | left boss fight | boss room | left area | none | boss fight doesn't start automatically so can leave any time |
| RB | right boss fight | right area | boss room | bell beast defeated | can't enter the arena from this side |
| RB | right boss fight | boss room | right area | bell beast defeated | bell beast defeated needs to be here to gate this from seemingly like a straight passthrough |

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| bell beast boss fight | boss room | silk spear | sharpdart doesn't work |
| silk heart bell beast | boss room | bell beast defeated |  |

### The Marrow Bellshrine

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [The Marrow Bellway (Bone_05)](#the-marrow-bellway-bone05) | R | none |  |
| R | right |  | [The Marrow Shaft (Bone_03)](#the-marrow-shaft-bone03) | UL | bell must be rung |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| ring bell switch |  |  | this opens the right exit |

### The Marrow Skull Wall (Bone_06)

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| F | floor |  | [The Marrow Shaft (Bone_03)](#the-marrow-shaft-bone03) | C | none |  |
| R | right |  | [The Marrow Skull Wall Side Room (Bone_18)](#the-marrow-skull-wall-side-room-bone18) | L | none |  |
| L | left |  | TODO |  | opens from the other side | shellwood; TODO |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| flea the marrow |  | none |  |

### The Marrow Skull Wall Side Room (Bone_18)

#### Subrooms

- lower level
- upper level

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| L | left | lower level | [The Marrow Skull Wall (Bone_06)](#the-marrow-skull-wall-bone06) | R | none |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | Notes |
| --- | --- | --- | --- | --- | --- |
| CG | climb | lower level | upper level | cling grip or silk soar |  |
| CG | climb | upper level | lower level | cling grip or silk soar |  |

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| lore tablet | lower level |  | NOT ACTUALLY A CHECK; Not included in Archipelago world |
| memory locket the marrow | upper level |  | on the tracker but appears to be inaccessible ; TODO |
| gauntlet fight | upper level |  | not on the tracker / what are the trigger conditions?; TODO; Not included in Archipelago world |

### The Marrow Mr Burns House (Bone_14)

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [The Marrow Shaft (Bone_03)](#the-marrow-shaft-bone03) | UR | none |  |
| R | right |  | [The Marrow Lower Pogo (Bone_07)](#the-marrow-lower-pogo-bone07) | L | none |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| rosary cache the marrow 10 |  | none |  |
| shell shard cache the marrow 5 |  |  |  |
| shell shard cache the marrow 6 |  |  |  |

### The Marrow Lower Pogo (Bone_07)

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [The Marrow Mr Burns House (Bone_14)](#the-marrow-mr-burns-house-bone14) | R | none |  |
| UR | upper right |  | [The Marrow Jail Pathway (Bone_08)](#the-marrow-jail-pathway-bone08) | UL | none |  |
| LR | upper left |  | [The Marrow Jail Pathway (Bone_08)](#the-marrow-jail-pathway-bone08) | LL | none |  |
| C | ceiling |  | [The Marrow Upper Pogo (Bone_19)](#the-marrow-upper-pogo-bone19) | F | none |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| craft metal |  | none |  |
| shell shard cache the marrow 4 |  | none | MARKED AS ??? ON TRACKER |

### The Marrow Upper Pogo (Bone_19)

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| F | floor |  | [The Marrow Lower Pogo (Bone_07)](#the-marrow-lower-pogo-bone07) | C | none |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| rosary cache the marrow 14 |  | none |  |
| rosary cache the marrow 15 |  | none |  |
| rosary cache the marrow 16 |  | none |  |
| rosary chest |  | none | NOT RANDOMIZED YET; Not included in Archipelago world |

### The Marrow Jail Pathway (Bone_08)

#### Subrooms

- upper area
- lower area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| UL | upper left | upper area | [The Marrow Lower Pogo (Bone_07)](#the-marrow-lower-pogo-bone07) | UR |  |  |
| LL | lower left | lower area | [The Marrow Lower Pogo (Bone_07)](#the-marrow-lower-pogo-bone07) | LR |  |  |
| UR | upper right | upper area | TODO |  |  | bellhart |
| MR | middle right | lower area | TODO |  |  | hunter's march |
| JD | lower right | lower area | [The Marrow Jail (Bone_12)](#the-marrow-jail-bone12) | L |  |  |
| F | floor | lower area | [The Marrow Lava Docks (Bone_09)](#the-marrow-lava-docks-bone09) | C |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | Notes |
| --- | --- | --- | --- | --- | --- |
| PS | platform switch | upper area | lower area | none (falling) |  |
| PS | platform switch | lower area | upper area | platform switch activated (at top of area) |  |

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| platform switch | upper area | none |  |
| rosary cache the marrow 8 | lower area | none |  |
| rosary cache the marrow 9 | lower area | none |  |

### The Marrow Jail (Bone_12)

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [The Marrow Jail Pathway (Bone_08)](#the-marrow-jail-pathway-bone08) | JD | none |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| straight pin |  | none |  |
| pin minigame 1 |  |  | straight pin minigame either missing or too early |
| pin minigame 2 |  |  |  |

### The Marrow Lava Docks (Bone_09)

#### Subrooms

- elevated platforms
- main area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| C | ceiling | main area | [The Marrow Jail Pathway (Bone_08)](#the-marrow-jail-pathway-bone08) | F | none |  |
| L | left | main area | [The Marrow Lava Track (Bone_16)](#the-marrow-lava-track-bone16) | R | none |  |
| LR | lower right | main area | TODO |  |  |  |
| UR | upper right | elevated platforms | TODO |  |  |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | Notes |
| --- | --- | --- | --- | --- | --- |
| CG | climb | main area | elevated platforms | cling grip OR silk soar OR faydown cloak |  |
| CG | climb | elevated platforms | main area | none (falling) |  |

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| rosary spike | main area | none | NOT RANDOMIZED YET |

### The Marrow Skull Tyrant Arena (Bone_15)

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| F | floor |  | [The Marrow Lava Track (Bone_16)](#the-marrow-lava-track-bone16) | C | none |  |
| L | left |  | [The Marrow Flea Caravan (Bone_10)](#the-marrow-flea-caravan-bone10) | R | none |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| silk spool |  | none | NOT RANDOMIZED YET |
| skull tyrant boss fight |  | none | NOT RANDOMIZED YET |
| crown fragment |  | defeat skull tyrant | NOT RANDOMIZED YET |

## Weavenest Atla

### Weavenest Atla Entrance (Weave_04)

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| WD | weavenest door |  | [Moss Grotto East (Tut_01b)](#moss-grotto-east-tut01b) | WD | needolin |  |
| R | right |  | [Weavenest Atla Teleporter (Weave_02)](#weavenest-atla-teleporter-weave02) | UL | none |  |

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

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| UL | upper left | upper telepad | [Weavenest Atla Entrance (Weave_04)](#weavenest-atla-entrance-weave04) | R | none |  |
| UR | upper right | upper telepad | [Weavenest Atla Power (Weave_12)](#weavenest-atla-power-weave12) | L | none |  |
| MR | middle right | upper shaft | [Weavenest Atla Hallway (Weave_13)](#weavenest-atla-hallway-weave13) | L | none |  |
| ML | middle left | lower shaft | [Weavenest Atla Spool (Weave_11)](#weavenest-atla-spool-weave11) | R | none |  |
| LL | lower left | lower telepad | [Weavenest Atla Bench (Weave_07)](#weavenest-atla-bench-weave07) | R | none |  |
| LR | lower right | lower telepad | [Weavenest Atla Eva (Weave_10)](#weavenest-atla-eva-weave10) | L | break walls |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | Notes |
| --- | --- | --- | --- | --- | --- |
| TP | teleporter | upper telepad | lower telepad | weavenest atla power activation |  |
| TP | teleporter | lower telepad | upper telepad | weavenest atla power activation |  |
| SM | shaft middle | lower telepad | upper shaft | cling grip OR silk soar |  |
| SM | shaft middle | upper shaft | lower telepad | none (falling) |  |
| SB | shaft base | lower telepad | lower shaft | cling grip OR silk soar |  |
| SB | shaft base | lower shaft | lower telepad | none (falling) |  |

#### Check Locations

No check locations defined.

### Weavenest Atla Power (Weave_12)

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [Weavenest Atla Teleporter (Weave_02)](#weavenest-atla-teleporter-weave02) | UR | none |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| power activation |  | none | NOT CURRENTLY RANDOMIZED; Not included in Archipelago world |
| weavenest atla map |  | none | weavenest atla power activation |

### Weavenest Atla Eva (Weave_10)

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [Weavenest Atla Teleporter (Weave_02)](#weavenest-atla-teleporter-weave02) | LR | break walls AND ( cling grip OR silk soar ) |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| crest of the hunter |  | TODO | TODO |
| yellow vesticrest |  | TODO | TODO |
| blue vesticrest |  | TODO | TODO |
| crest of the hunter 2 |  | TODO | TODO |
| sylphsong |  | TODO | TODO |

### Weavenest Atla Bench (Weave_07)

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| R | right |  | [Weavenest Atla Teleporter (Weave_02)](#weavenest-atla-teleporter-weave02) | LL | none |  |
| L | left |  | [Weavenest Atla Grotto (Weave_03)](#weavenest-atla-grotto-weave03) | R | none |  |

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

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| R | right | pathway | [Weavenest Atla Bench (Weave_07)](#weavenest-atla-bench-weave07) | L | break vines |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | Notes |
| --- | --- | --- | --- | --- | --- |
| MP | mossberry platform jump | pathway | mossberry platform | run OR dash OR drifter's cloak OR faydown cloak OR sharpdart OR clawline OR silk soar OR air stall pogo crest | air stall crest = shaman, beast, reaper, architect; couldn't make it work with the other three |
| MP | mossberry platform jump | mossberry platform | pathway | none (falling) |  |
| BR | boss room jump | pathway | boss room | break vines AND ( run OR dash OR drifter's cloak OR faydown cloak OR sharpdart OR clawline OR beast crest ) | beast pogo clears this easily |
| BR | boss room jump | boss room | pathway | none (falling) |  |

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| weavenest atla mossberry | mossberry platform |  |  |
| double moss mother boss fight | boss room |  | NOT CURRENTLY TRACKED |
| weavelight | boss room | defeat double moss mother |  |

### Weavenest Atla Hallway (Weave_13)

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [Weavenest Atla Teleporter (Weave_02)](#weavenest-atla-teleporter-weave02) | MR | none |  |
| R | right |  | [Weavenest Atla Lore (Weave_08)](#weavenest-atla-lore-weave08) | L | none |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

### Weavenest Atla Lore (Weave_08)

#### Subrooms

- main area
- right exit

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| L | left | main area | [Weavenest Atla Hallway (Weave_13)](#weavenest-atla-hallway-weave13) | R | none |  |
| R | right | right exit | [Weavenest Atla Mask Shard (Weave_05b)](#weavenest-atla-mask-shard-weave05b) | L | none |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | Notes |
| --- | --- | --- | --- | --- | --- |
| CL | climb pit | main area | right exit | none (falling) | need to pogo spikes to get down without movement tech |
| CL | climb pit | right exit | main area | cling grip AND ( dash OR horizontal movement tech OR faydown cloak ) |  |

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| rune harp weavenest atla | main area | none |  |
| readable lore tablet | main area | none | NOT ACTUALLY A CHECK |

### Weavenest Atla Mask Shard (Weave_05b)

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [Weavenest Atla Lore (Weave_08)](#weavenest-atla-lore-weave08) | R | none |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| weavenest alta mask shard |  | silk soar OR ( cling grip AND ( drifter's cloak OR faydown cloak OR clawline OR sharpdart OR  ) ) | NEEDS VERIFICATION BY SOMEONE BETTER THAN ME |

### Weavenest Atla Snare (Weave_14)

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| F | floor |  | [Weavenest Atla Spool (Weave_11)](#weavenest-atla-spool-weave11) | C | none (falling) |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| snare setter |  | none |  |

### Weavenest Atla Spool (Weave_11)

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| R | right |  | [Weavenest Atla Teleporter (Weave_02)](#weavenest-atla-teleporter-weave02) | ML | none | Imported destination text: weavenest atla teleporter - ML |
| C | ceiling |  | [Weavenest Atla Snare (Weave_14)](#weavenest-atla-snare-weave14) | F | silk soar OR ( faydown cloak + cling grip ) |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| weavenest atla spool fragment |  | none |  |

## Wormways

### Wormways Craggler Hallway (Crawl_04)

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| L | left |  | [Wormways Shaft (Crawl_02)](#wormways-shaft-crawl02) | LR | none |  |
| R | right |  | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | LL | none |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| craggler mini boss fight |  | none |  |
| beast shard |  | defeat craggler | NOT CURRENTLY RANDOMIZED; Not included in Archipelago world |

### Wormways Shaft (Crawl_02)

#### Subrooms

- lower area
- middle platform area
- upper platform area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| LR | lower right | lower area | [Wormways Craggler Hallway (Crawl_04)](#wormways-craggler-hallway-crawl04) | L | none |  |
| LL | lower left | lower area | [Wormways Middle (Crawl_03b)](#wormways-middle-crawl03b) | R | door unlocked |  |
| UL | upper left | upper platform area | [Wormways Upper West (Crawl_03)](#wormways-upper-west-crawl03) | R | breakable wall -must be opened from the other side (verified) |  |
| UR | upper right | middle platform area | [Wormways Upper East (Crawl_01)](#wormways-upper-east-crawl01) | L | none |  |
| MR | middle right | middle platform area | [Wormways Flea Rescue (Crawl_06)](#wormways-flea-rescue-crawl06) | L | none |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | Notes |
| --- | --- | --- | --- | --- | --- |
| DS | door switch | middle platform area | lower area | none (door switch is on this side) |  |
| DS | door switch | lower area | middle platform area | door switch needs to be flipped |  |
| CG | platform gaps | middle platform area | upper platform area | silk soar OR cling grip |  |
| CG | platform gaps | upper platform area | middle platform area | none (falling) |  |

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| use simple key on lock | lower area | simple key | unlocks the LL room exit |
| mask shard wormways | lower area | none |  |
| frayed rosary string wormways | upper platform area | cling grip OR silk soar |  |
| flip door switch | middle platform area | none | unlocks the middle/lower shortcut; Not included in Archipelago world |

### Wormways Flea Rescue (Crawl_06)

#### Subrooms

- entrance
- main area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| L | left | entrance | [Wormways Shaft (Crawl_02)](#wormways-shaft-crawl02) | MR | none |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | Notes |
| --- | --- | --- | --- | --- | --- |
| D | dash | entrance | main area | none | spike pogo |
| D | dash | main area | entrance | none | spike pogo |

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| flea wormways snacc | main area | none |  |

### Wormways Middle (Crawl_03b)

#### Subrooms

- right area
- left area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| R | right | right area | [Wormways Shaft (Crawl_02)](#wormways-shaft-crawl02) | LL | door must be unlocked from the other side |  |
| F | floor | right area | [Wormways Lower East (Crawl_07)](#wormways-lower-east-crawl07) | C | none | Imported destination text: wormways lower east - C |
| C | ceiling | left area | [Wormways Upper West (Crawl_03)](#wormways-upper-west-crawl03) | F | none |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | Notes |
| --- | --- | --- | --- | --- | --- |
| RJ | running jump | left area | right area | run OR dash OR drifter's cloak OR faydown cloak OR sharpdart OR clawline |  |
| RJ | running jump | right area | left area | none (falling) |  |

#### Check Locations

No check locations defined.

### Wormways Upper West (Crawl_03)

#### Subrooms

- main area
- plasmium spot
- weavenest landing

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| F | floor | main area | [Wormways Middle (Crawl_03b)](#wormways-middle-crawl03b) | C |  |  |
| R | right | main area | [Wormways Shaft (Crawl_02)](#wormways-shaft-crawl02) | UL |  |  |
| C | ceiling | main area | [Wormways Laboratory (Crawl_08)](#wormways-laboratory-crawl08) | F | silk soar OR cling grip |  |
| WD | weaver door | weavenest landing | [Wormways Weavenest](#wormways-weavenest) | WD | needolin |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | Notes |
| --- | --- | --- | --- | --- | --- |
| CG | climb | main area | plasmium spot | cling grip OR silk soar OR faydown cloak |  |
| CG | climb | plasmium spot | main area | cling grip OR silk soar OR faydown cloak |  |
| BJ | big jump | main area | weavenest landing | silk soar OR faydown cloak OR ( run AND dash AND clawline ) |  |
| BJ | big jump | weavenest landing | main area | none (falling) |  |

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| plasmium pustule upper west | plasmium spot | needle phial AND red tool slot | NOT RANDOMIZED YET |

### Wormways Upper East (Crawl_01)

#### Subrooms

- lower area
- upper area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| L | left | lower area | [Wormways Shaft (Crawl_02)](#wormways-shaft-crawl02) | UR | none |  |
| R | right | upper area | [The Big Fall (Aspid_01)](#the-big-fall-aspid01) | UL | none |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | Notes |
| --- | --- | --- | --- | --- | --- |
| LD | left dash | lower area | upper area | run OR dash OR cling grip OR drifter's cloak OR faydown cloak OR sharpdart OR clawline |  |
| LD | left dash | upper area | lower area | none (falling) |  |

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| dead bugs purse | upper area | none | STILL MARKED AS ??? ON TRACKER |
| shakra shop items | upper area |  | :) |

### Wormways Laboratory (Crawl_08)

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| F | floor |  | [Wormways Upper West (Crawl_03)](#wormways-upper-west-crawl03) | C |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| needle phial |  | none |  |
| plasmium phial |  | filled needle phial |  |
| wish missing assitant |  | TODO | TODO |
| wish alchemist assistant |  |  | Not included in Archipelago world |

### Wormways Lower East (Crawl_07)

#### Subrooms

- ceiling exit area
- left exit area
- tunnels
- floor exit area

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| C | ceiling | ceiling exit area | [Wormways Middle (Crawl_03b)](#wormways-middle-crawl03b) | F | none |  |
| L | left | left exit area | [Wormways Lower West (Crawl_09)](#wormways-lower-west-crawl09) | R | none |  |
| F | floor | floor exit area | [Bonegrave (Bonegrave)](#bonegrave-bonegrave) | C | none |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | Notes |
| --- | --- | --- | --- | --- | --- |
| CC | ceiling climb | ceiling exit area | tunnels | cling grip |  |
| CC | ceiling climb | tunnels | ceiling exit area | cling grip |  |
| LC | left climb | left exit area | tunnels | cling grip |  |
| LC | left climb | tunnels | left exit area | cling grip |  |
| RC | floor climb | floor exit area | tunnels | cling grip |  |
| RC | floor climb | tunnels | floor exit area | cling grip |  |

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| plasmium pustule lower east | tunnels | needle phial AND red tool slot | NOT CURRENTLY RANDOMIZED; Not included in Archipelago world |

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

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| R | right | right exit area | [Wormways Lower East (Crawl_07)](#wormways-lower-east-crawl07) | L | none |  |
| L | left | left exit area | [Wormways Zango Arena (Crawl_10)](#wormways-zango-arena-crawl10) | R | none |  |

#### Subroom Connections

| Alias | Name | Source | Destination | Requirements | Notes |
| --- | --- | --- | --- | --- | --- |
| LC | left climb | left exit area | tunnels | cling grip |  |
| LC | left climb | tunnels | left exit area | cling grip |  |
| RC | right climb | right exit area | tunnels | cling grip |  |
| RC | right climb | tunnels | right exit area | cling grip |  |

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| memory locket | tunnels | none |  |
| plasmium pustule lower west | tunnels | needle phial AND red tool slot | NOT RANDOMIZED YET |

#### Notes

this one seems a bit tricky, but also it's just a bit late

i think you need cling grip to from any one point to another in here

TODO: review the mapping in here

### Wormways Weavenest

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| WD | weaver door |  | [Wormways Upper West (Crawl_03)](#wormways-upper-west-crawl03) | WD | needolin |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| sharpdart |  | none |  |

### Wormways Zango Arena (Crawl_10)

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| R | right |  | [Wormways Lower West (Crawl_09)](#wormways-lower-west-crawl09) | L | none |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| plasmified zango boss fight |  | TODO (act 3?) | TODO |

## Deep Docks

## Far Fields

## Hunter's March

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

### Test room

#### Subrooms

- testing

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| T | testing |  | TODO |  |  |  |
| ? | testing |  | TODO |  |  |  |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

#### Notes

this is a **test** page

## Fast Travel

### Bellway Menu

#### Subrooms

No subrooms defined.

#### Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| BB | bone bottom |  | [Bone Bottom Bellway (Bellway_01)](#bone-bottom-bellway-bellway01) | BB |  | TODO |
| TM | the marrow |  | TODO |  |  | TODO |
| DD | deep docks |  | TODO |  |  | TODO |
| FF | far fields |  | TODO |  |  | TODO |
| GM | greymoor |  | TODO |  |  | TODO |
| BH | bellhart |  | TODO |  |  | TODO |
| SW | shellwood |  | TODO |  |  | TODO |
| BS | blasted steps |  | TODO |  |  | TODO |
| TS | the slab |  | TODO |  |  | TODO |
| GB | grand bellway |  | TODO |  |  | TODO |
| BW | bilewater |  | TODO |  |  | TODO |
| PD | putrified ducts |  | TODO |  |  | TODO |

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

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| T | terminus |  | TODO |  |  | TODO |
| M | memorium |  | TODO |  |  | TODO |
| HH | high halls |  | TODO |  |  | TODO |
| FS | first shrine |  | TODO |  |  | TODO |
| CC | choral chambers |  | TODO |  |  | TODO |
| GB | grand bellway |  | TODO |  |  | TODO |
| UW | underworks |  | TODO |  |  | TODO |

#### Subroom Connections

No subroom connections defined.

#### Check Locations

No check locations defined.

#### Notes

a virtual room to represent the ventrica fast travel menu
