# Silksong Randomizer Logic

Compiled from the room notes in this repository.

## Bone Bottom

### Bone Bottom Bellway

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| BD | bellway door |  | [bone bottom](#bone-bottom) -BD | none |
| BB | bell beast |  | [bone bottom](#bone-bottom) -bell beast | bell beast available AND bone bottom bellway unlocked |

### Bone Bottom

#### Subrooms

- ground level
- sky
- upper right platforms
- upper middle platforms
- upper left platforms
- chapel roof

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| UL | upper left | upper left platforms | [bonegrave](#bonegrave) -UR | none |
| LL | lower left | ground level | [bonegrave](#bonegrave) -LR | door opened from other side |
| DR | descend rope | ground level | [ruined chapel](#ruined-chapel) -AR | none |
| F | floor | ground level | [moss grotto west](#moss-grotto-west) -C | none |
| BD | bellway door | ground level | [bone bottom bellway](#bone-bottom-bellway) -BD | none |
| LR | lower right | ground level | TODO | none |
| UR | upper right | upper right platforms | TODO | none |
| RC | right ceiling | upper right platforms | TODO | none |
| LC | left ceiling | sky | TODO | silk soar |

#### Subroom Connections

| source | alias | name | destination | requirements |
| --- | --- | --- | --- | --- |
| ground level | CC | climb chapel | chapel roof | silk soar OR ( cling grip AND ( LL door NOT opened OR faydown cloak ) ) |
| ground level | SM | soar to middle platforms | upper middle platforms | silk soar |
| ground level | SS | soar to sky exit | sky | silk soar |
| ground level | SR | soar to right platforms | upper right platforms | silk soar |
| ground level | EV | elevator | upper right platforms | elevator switch flipped |
| chapel roof | CC | climb chapel | ground level | none |
| chapel roof | CR | climb roof | upper left platforms | silk soar OR cling grip |
| upper left platforms | CR | climb roof | chapel roof | none |
| upper middle platforms | MD | middle platform drift | chapel roof | drifter's cloak OR clawline OR ( dash + sharpdart ) |
| upper middle platforms | SM | soar to the middle platforms | ground level | none |
| upper middle platforms | CL | clawline across the sky | upper right platforms | clawline |
| upper right platforms | CL | clawline across the sky | upper middle platforms | clawline |
| upper right platforms | SR | soar to right platforms | ground level | none |
| sky | DL | sky drift to right platforms | upper right platforms | drifter's cloak OR horizontal movement tech |
| sky | DR | sky drift to middle platforms | upper middle platforms | drifter's cloak OR horizontal movement tech |
| sky | SS | soar to the sky | ground level | none |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| bone bottom mossberry | upper right platforms | none |  |
| rosary cache bone bottom 8 | upper right platforms | none |  |
| rosary cache bone bottom 9 | upper right platforms | none |  |
| weaver effigy camora moss grotto | upper middle platforms | none |  |
| rosary dish | upper middle platforms | none | NOT CURRENTLY RANDOMIZED |
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

### Bonegrave Passage

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| R | right |  | [bonegrave](#bonegrave) -LL | TODO |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| summoned savior boss fight |  | TODO (steel soul only?) |  |

### Bonegrave

#### Subrooms

- upper left exit
- upper right exit
- graveyard

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| UR | upper right | upper right exit | [bone bottom](#bone-bottom) -UL | none |
| LR | lower right | graveyard | [bone bottom](#bone-bottom) -LL | none |
| C | ceiling | upper left exit | [wormways lower east](#wormways-lower-east) -F | none |
| GD | grave door | graveyard | TODO | no wanderer's crest |
| LL | lower left | graveyard | [bonegrave passage](#bonegrave-passage) -R | TODO (steel soul only?) |

#### Subroom Connections

| alias | name | source | destination | requirements |
| --- | --- | --- | --- | --- |
| CL | climb | graveyard | upper right exit | cling grip OR silk soar |
| CL | climb | upper right exit | graveyard | none (falling) |
| BW | breakable wall | upper left exit | upper right exit | none (break wall from this side) |
| BW | breakable wall | upper right exit | upper left exit | wall broken from other side |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| boneyard mossberry | graveyard | none | can be gotten with only jump -tested |
| rosaries on grave | graveyard | none | NOT CURRENTLY RANDOMIZED |
| rosary cache bone bottom 6 | upper right exit | none | MARKED AS ??? ON TRACKER |
| rosary cache bone bottom 7 | upper right exit | none | MARKED AS ??? ON TRACKER |

### Moss Grotto East

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| UL | upper left |  | [moss grotto west](#moss-grotto-west) -UR | none |
| LL | lower left |  | [moss grotto west](#moss-grotto-west) -LR | none |
| WD | weavenest door |  | [weavenest atla entrance](#weavenest-atla-entrance) -WD | needolin |

#### Check Locations

| check | subroom | notes |
| --- | --- | --- |
| frayed rosary string moss grotto |  |  |
| shell shard cache moss grotto 2 |  |  |
| shell shard cache moss grotto 3 |  | STILL MARKED AS ??? ON TRACKER |
| shell shard cache moss grotto 4 |  | STILL MARKED AS ??? ON TRACKER |
| moss grotto east mossberry |  | NOT YET RANDOMIZED |

### Moss Grotto West

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| UR | upper right |  | [moss grotto east](#moss-grotto-east) -UL | none |
| LR | lower right |  | [moss grotto east](#moss-grotto-east) -LL | none |
| UL | upper left |  | [ruined chapel](#ruined-chapel) -R | none |
| C | ceiling |  | [bone bottom](#bone-bottom) -F | silk soar OR cling grip |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| frayed rosary string moss grotto |  |  |  |
| shell shard cache moss grotto 1 |  |  |  |
| shell shard cache moss grotto 5 |  |  |  |
| shell shard cache moss grotto 6 |  |  |  |
| shell shard cache moss grotto 7 |  |  |  |
| moss grotto west mossberry |  |  |  |
| moss grotto west beast shard |  |  | right at game start jump into right room and again into right into upper right room NOT YET RANDOMIZED |

### Mosshome Basement

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| LL | lower left |  | [bone bottom](#bone-bottom) -UR | none |
| UL | upper left |  | [mosshome spool](#mosshome-spool) fragment | none |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| rosary cache bone bottom ? |  | none |  |
| rosary cache bone bottom ? |  | none |  |
| rosary dish |  |  | NOT CURRENTLY RANDOMIZED |

### Mosshome Druid

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| L | left |  | [mosshome upper](#mosshome-upper) -R | none |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| wish berry picking |  | TODO |  |
| druid's eye |  | TODO | MARKED AS ??? ON THE TRACKER / WRONG POSITION |
| druid's eyes |  | TODO | MARKED AS ??? ON THE TRACKER / WRONG POSITION |

### Mosshome Lower

#### Subrooms

- main area
- upper left exit

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| LR | lower right | main area | [the marrow shakra intro](#the-marrow-shakra-intro) -LL | none |
| UR | upper right | main area | [the marrow shakra intro](#the-marrow-shakra-intro) -UL | none |
| L | left | upper left exit | [the big fall](#the-big-fall) | none |
| C | ceiling | upper left exit | [mosshome upper](#mosshome-upper) -F | must be opened from the other side |
| F | floor | main area | [mosshome spool](#mosshome-spool) -C | must be opened from the other side |

#### Subroom Connections

| alias | name | source | destination | requirements |
| --- | --- | --- | --- | --- |
| RJ | running jump | main area | upper left exit | easy skips enabled OR run OR horizontal movement tech OR faydown cloak OR silk soar |
| RJ | running jump | upper left exit | main area | none (falling) |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| rosary cache bone bottom 4 | main area | none |  |
| rosary cache bone bottom 5 | main area | none |  |

### Mosshome Middle

#### Subrooms

- main area
- upper right area

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| LR | lower right | main area | [the marrow bellway](#the-marrow-bellway) -L | none |
| UR | upper right | upper right area | [mosshome side room](#mosshome-side-room) -L | none |
| F | floor | main area | [mosshome lower](#mosshome-lower) -C | flip the switch in this area |
| C | ceiling | main area | [mosshome upper](#mosshome-upper) -LF |  |

#### Subroom Connections

| alias | name | source | destination | requirements |
| --- | --- | --- | --- | --- |
| RJ | running jump | main area | upper right area | run OR dash OR silk soar OR horizontal movement tech |
| RJ | running jump | upper right area | main area | none |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| flip switch to open floor exit | main area | none |  |
| rosary cache bone bottom 14 | main area | none |  |
| rosary cache bone bottom 15 | main area | none |  |

### Mosshome Side Room

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| L | left |  | [mosshome middle](#mosshome-middle) -UR | none |
| C | ceiling |  | [mosshome upper](#mosshome-upper) -RF | none |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| mosshome mossberry |  | none |  |

### Mosshome Spool

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| R | right |  | [mosshome basement](#mosshome-basement) -UL | none |
| C | ceiling |  | [mosshome lower](#mosshome-lower) -F | switch in room activated |

#### Subroom Connections

| alias | name | source | destination | requirements |
| --- | --- | --- | --- | --- |
|  |  |  |  |  |
|  |  |  |  |  |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| bone bottom spool fragment |  | none |  |
| floor switch to open ceiling exit |  | none |  |

### Mosshome Upper

#### Subrooms

- main area
- bottom right area
- upper left area

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| LF | left floor | main area | [mosshome middle](#mosshome-middle) -C | none |
| L | left | main area | [the big fall](#the-big-fall) -UR | none |
| RF | right floor | bottom right area | [mosshome side room](#mosshome-side-room) -C | none |
| R | right | bottom right area | [mosshome druid](#mosshome-druid) -L | none |

#### Subroom Connections

| alias | name | source | destination | requirements |
| --- | --- | --- | --- | --- |
| RS | right silk blockade | main area | bottom right area | can break silk blockade |
| RS | right silk blockade | bottom right area | main area | can break silk blockade |
| LS | left silk blockade | main area | upper left area | can break silk blockade |
| LS | left silk blockade | upper left area | main area | none (cut to open pathway) |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| silk spear | main area | none |  |
| frayed rosary string the marrow | upper left area | none | seems to be misnamed in the apworld |
| rosary cache bone bottom 16 | main area | none |  |
| rosary cache bone bottom 17 | main area | none |  |

### Ruined Chapel Interior

#### Subrooms

- ritual chamber
- crest chamber

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| CD | chapel door | ritual chamber | [ruined chapel](#ruined-chapel) -CD | TODO |

#### Subroom Connections

| source | alias | name | destination | requirements |
| --- | --- | --- | --- | --- |
| ritual chamber | SS | silk soar spot | crest chamber | silk soar |
| crest chamber | SS | silk soar spot | ritual chamber | silk soar |

### Ruined Chapel

#### Subrooms

- chapel
- boss room
- bench room

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| R | right | bench room | [moss grotto west](#moss-grotto-west) -UL | none |
| AR | ascend rope | chapel | [bone bottom](#bone-bottom) -DR | none |
| CD | chapel door | chapel | [ruined chapel interior](#ruined-chapel-interior) -CD | TODO |

#### Subroom Connections

| alias | name | source | destination | requirements |
| --- | --- | --- | --- | --- |
| BF | boss fight | bench room | boss room | none |
| BF | boss fight | boss room | bench room | moss mother defeated |
| BF | boss fight | chapel | boss room | none |
| BF | boss fight | bench room | chapel | moss mother defeated |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| moss mother boss fight | boss room |  |  |
|  |  |  |  |

### The Big Fall

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

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| C | ceiling | top area | blasted bridge -F | silk soar |
| UR | upper right | upper right ledge | shellwood grand gate bell -L | none |
| MR | middle right | middle right ledge | [mosshome upper](#mosshome-upper) -L | breakable wall -must be opened from the other side (NEEDS VERIFICATION) |
| LR | lower right | lower right area | [mosshome lower](#mosshome-lower) -L | none |
| UL | upper left | upper left ledge | TODO | none |
| LL | lower left | lower left area | wormways entrance -R | none |
| LF | left floor | bottom area | [bone bottom](#bone-bottom) -LC | none |
| RF | right floor | lower right area | [bone bottom](#bone-bottom) -RC | none |

#### Subroom Connections

| alias | name | source | destination | requirements |
| --- | --- | --- | --- | --- |
| F1 | top fall | top area | upper right ledge | none (falling) |
| F2 | upper right ledge fall | upper right ledge | upper left ledge | none (falling |
| F3 | upper left ledge fall | upper left ledge | wish ledge | none (falling) |
| F4 | wish ledge fall | wish ledge | upper silk soar only zone | none (falling) |
| F5 | upper silk soar zone fall | upper silk soar only zone | middle right ledge | none (falling) |
| F6 | middle right ledge fall | middle right ledge | lower silk soar only zone | none (falling) |
| F7 | lower silk soar zone fall | lower silk soar only zone | bottom area | none (falling) |
| F8 | lower left area fall | lower left area | bottom area | none (falling) |
| F9 | lower right area fall | lower right area | bottom area | none (falling) |
| S1 | bottom silk soar | bottom area | lower silk soar zone | silk soar |
| S2 | lower zone silk soar | lower silk soar only zone | upper silk soar only zone | silk soar |
| S3 | upper zone silk soar | upper silk soar only zone | top area | silk soar |
| LC | lower crossing | lower left area | lower right area | easy skips enabled OR silk soar OR horizontal movement tech OR dash OR run OR cling grip OR faydown cloak OR silk soar |
| LC | lower crossing | lower right area | lower left area | easy skips enabled OR silk soar OR horizontal movement tech OR dash OR run OR cling grip OR faydown cloak |
| WC | wish climb | wish ledge | upper left ledge | silk soar OR cling grip |
| UC | upper crossing | upper left ledge | upper right ledge | silk soar OR cling grip OR faydown cloak OR clawline OR sharpdart OR dash |
| UC | upper crossing | upper right ledge | upper left ledge | silk soar OR cling grip OR faydown cloak OR clawline OR sharpdart OR dash |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| rosary cache bone bottom 1 | lower left area | none | STILL MARKED AS ??? ON TRACKER |
| choral commandment moss grotto | middle right area | none |  |
| wish my missing courier | wish ledge | none | STILL MARKED AS ??? ON TRACKER |

### Wanderer'S Grave

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| GD | grave door |  | [bonegrave](#bonegrave) -GD | none |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| wanderer's crest |  | none |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |

## The Marrow

### The Marrow Bell Bench

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| L | left |  | [the marrow entrance](#the-marrow-entrance) -LR | none |
| R | right |  | [the marrow lava intro](#the-marrow-lava-intro) -L | none |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| rosary cache the marrow 3 |  | none |  |
| rosary cache the marrow 4 |  | none |  |
| bench unlock |  | pay monies | NOT CURRENTLY RANDOMIZED |

### The Marrow Bellway

#### Subrooms

- left area
- boss room
- right area

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| L | left | left area | [mosshome middle](#mosshome-middle) -LR | none |
| F | floor | left area | [the marrow shakra intro](#the-marrow-shakra-intro) -C | none |
| R | right | right area | [the marrow grand gate bell](#the-marrow-grand-gate-bell) -L | none |

#### Subroom Connections

| alias | name | source | destination | requirements | notes |
| --- | --- | --- | --- | --- | --- |
| LB | left boss fight | left area | boss room | none |  |
| LB | left boss fight | boss room | left area | none | boss fight doesn't start automatically so can leave any time |
| RB | right boss fight | right area | boss room | bell beast defeated | can't enter the arena from this side |
| RB | right boss fight | boss room | right area | bell beast defeated | bell beast defeated needs to be here to gate this from seemingly like a straight passthrough |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| bell beast boss fight | boss room | silk spear | sharpdart doesn't work |
| silk heart bell beast | boss room | bell beast defeated |  |

### The Marrow Entrance

#### Subrooms

- before gauntlet
- gauntlet room
- after gauntlet
- ceiling exit

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| LL | lower left | before gauntlet | [bone bottom](#bone-bottom) -LR | none |
| LR | lower right | after gauntlet | [the marrow bell bench](#the-marrow-bell-bench) -L | none |
| UR | upper right | before gauntlet | [the marrow falling rocks](#the-marrow-falling-rocks) -L | none (breakable wall) |
| C | ceiling | ceiling exit | [the marrow shakra intro](#the-marrow-shakra-intro) -F | none |

#### Subroom Connections

| alias | name | source | destination | requirements |
| --- | --- | --- | --- | --- |
| DS | door switch | before gauntlet | after gauntlet | flipped door switch |
| DS | door switch | after gauntlet | before gauntlet | none (can flip door switch) |
| GF | gauntlet fight | before gauntlet | gauntlet room | none |
| GF | gauntlet fight | gauntlet room | after gauntlet | defeat gauntlet |
| GF | gauntlet fight | gauntlet room | before gauntlet | defeat gauntlet |
| LP | lowered platform | before gauntlet | ceiling exit | platform lowered OR silk soar OR faydown cloak OR ( run AND clawline ) |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| shell shard cache the marrow 1 | before gauntlet | none | MARKED AS ??? ON TRACKER |
| rosary cache the marrow 1 | after gauntlet | none |  |
| rosary cache the marrow 2 | after gauntlet | none |  |

### The Marrow Falling Rocks

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| L | left |  | [the marrow entrance](#the-marrow-entrance) -UR | none |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| the marrow rosary cache 5 |  | none |  |
| the marrow rosary cache 6 |  | none |  |

### The Marrow Flea Caravan

#### Subrooms

- main area
- behind metal gate

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| L | left | main area | [the marrow shaft](#the-marrow-shaft) -LR | none |
| R | right | behind metal gate | [the marrow skull tyrant arena](#the-marrow-skull-tyrant-arena) -L | none |
| F | floor | main area | [the marrow lava intro](#the-marrow-lava-intro) -RC | none |

#### Subroom Connections

| alias | name | source | destination | requirements |
| --- | --- | --- | --- | --- |
| DS | door switch | main area | behind metal gate | door switch activated |
| DS | door switch | behind metal gate | main area | none (can flip switch from this side) |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| "frayed rosary string bone bottom" |  | none | probably misnamed in the apworld |
| rosary dish |  | none | NOT CURRENTLY RANDOMIZED |
| wish survivor's camp supplies |  | TODO | TODO |

### The Marrow Grand Gate Bell

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| L | left |  | [the marrow bellway](#the-marrow-bellway) -R | none |
| R | right |  | [the marrow shaft](#the-marrow-shaft) -UL | bell must be rung |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| ring bell switch |  |  | this opens the right exit |

### The Marrow Jail Pathway

#### Subrooms

- upper area
- lower area

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| UL | upper left | upper area | [the marrow lower pogo](#the-marrow-lower-pogo) -UR |  |
| LL | lower left | lower area | [the marrow lower pogo](#the-marrow-lower-pogo) -LR |  |
| UR | upper right | upper area | TODO |  |
| MR | middle right | lower area | TODO |  |
| LR | lower right | lower area | [the marrow jail](#the-marrow-jail) -L |  |
| F | floor | lower area | the marrow lava dock -C |  |

#### Subroom Connections

| alias | name | source | destination | requirements |
| --- | --- | --- | --- | --- |
| PS | platform switch | upper area | lower area | none (falling) |
| PS | platform switch | lower area | upper area | platform switch activated (at top of area) |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| platform switch | upper area | none |  |
| rosary cache the marrow 8 | lower area | none |  |
| rosary cache the marrow 9 | lower area | none |  |

### The Marrow Jail

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| L | left |  | [the marrow jail pathway](#the-marrow-jail-pathway) -JD | none |
|  |  |  |  |  |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| straight pin |  | none |  |
| pin minigame 1 |  |  | straight pin minigame either missing or too early |
| pin minigame 2 |  |  |  |

### The Marrow Lava Docks

#### Subrooms

- elevated platforms
- main area

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| C | ceiling | main area | [the marrow jail](#the-marrow-jail) -F | none |
| L | left | main area | the marrow track -R | none |
| LR | lower right | main area | TODO |  |
| UR | upper right | elevated platforms | TODO |  |

#### Subroom Connections

| alias | name | source | destination | requirements |
| --- | --- | --- | --- | --- |
| CG | climb | main area | elevated platforms | cling grip OR silk soar OR faydown cloak |
| CG | climb | elevated platforms | main area | none (falling) |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| rosary spike | main area | none | NOT RANDOMIZED YET |

### The Marrow Lava Intro

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| L | left |  | [the marrow bell bench](#the-marrow-bell-bench) -R | none |
| R | right |  | the marrow lava lake -L | none |
| LC | left ceiling |  | [the marrow shaft](#the-marrow-shaft) -F | none |
| RC | right ceiling |  | [the marrow flea caravan](#the-marrow-flea-caravan) -F | none |

#### Notes

no checks

### The Marrow Lower Pogo

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| L | left |  | [the marrow mr burns house](#the-marrow-mr-burns-house) -R | none |
| UR | upper right |  | [the marrow jail pathway](#the-marrow-jail-pathway) -UL | none |
| LR | upper left |  | [the marrow jail pathway](#the-marrow-jail-pathway) -LL | none |
| C | ceiling |  | [the marrow upper pogo](#the-marrow-upper-pogo) -F | none |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| craft metal |  | none | NOT RANDOMIZED YET |
| shell shard cache the marrow 4 |  | none | MARKED AS ??? ON TRACKER |

### The Marrow Mr Burns House

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| L | left |  | [the marrow shaft](#the-marrow-shaft) -UR | none |
| R | right |  |  | none |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| rosary cache the marrow 10 |  | none | MARKED AS ??? ON TRACKER |
| rosary cache the marrow 14 |  | none | MARKED AS ??? ON TRACKER |
| rosary cache the marrow 15 |  | none | MARKED AS ??? ON TRACKER |

### The Marrow Shaft

#### Subrooms

- lower shaft
- upper shaft

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| F | floor | lower shaft | [the marrow lava intro](#the-marrow-lava-intro) -LC | none |
| LL | lower left | lower shaft | [the marrow shaft](#the-marrow-shaft) side room -R | none |
| ML | middle left | lower shaft | [the marrow shakra intro](#the-marrow-shakra-intro) -R | none |
| UL | upper left | upper shaft | [the marrow grand gate bell](#the-marrow-grand-gate-bell) -R | bell must be rung |
| LR | lower right | lower shaft | [the marrow flea caravan](#the-marrow-flea-caravan) -L | none |
| UR | upper right | upper shaft | [the marrow mr burns house](#the-marrow-mr-burns-house) -L | none |
| C | ceiling | upper shaft | the marrow skull -F | none |

#### Subroom Connections

| alias | name | source | destination | requirements |
| --- | --- | --- | --- | --- |
| DS | door switch | lower shaft | upper shaft | door switch flipped |
| DS | door switch | upper shaft | lower shaft | none (can flip switch from here) |

#### Notes

no checks

### The Marrow Shakra Intro

#### Subrooms

- behind gate
- main area

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| R | right | main area | [the marrow shaft](#the-marrow-shaft) -ML | none |
| F | floor | main area | [the marrow entrance](#the-marrow-entrance) -C | none |
| LL | lower left | main area | [mosshome lower](#mosshome-lower) -LR | none |
| UL | upper right | behind gate | [mosshome lower](#mosshome-lower) -UR | none |
| C | ceiling | main area | [the marrow bellway](#the-marrow-bellway) -F | none |

#### Subroom Connections

| alias | name | source | destination | requirements |
| --- | --- | --- | --- | --- |
| DS | door switch | main area | behind gate | door switch flipped |
| DS | door switch | behind gate | main area | none (can flip door switch from this side) |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| lower platform switch (into floor) | main area | lowers platform into the marrow entrance |  |
| rosary cache the marrow 7 | main area |  |  |
| shell shard cache the marrow 2 | main area |  |  |
| "rosary cache bone bottom 2" | main area |  | probably misnamed in the apworld |
| "rosary cache bone bottom 3" | main area |  | probably misnamed in the apworld |
| quill | main area |  | shakra's shop |
| compass | main area |  | shakra's shop |
| map mosslands | main area |  | shakra's shop |
| map the marrow | main area |  | shakra's shop |
| map bench pins | main area |  | shakra's shop |
| map bellway pins | main area |  | shakra's shop |

### The Marrow Skull Tyrant Arena

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| F | floor |  | the marrow lava track -C | none |
| L | left |  | [the marrow flea caravan](#the-marrow-flea-caravan) -R | none |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| silk spool |  | none | NOT RANDOMIZED YET |
| skull tyrant boss fight |  | none | NOT RANDOMIZED YET |
| crown fragment |  | defeat skull tyrant | NOT RANDOMIZED YET |

### The Marrow Skull Wall Side Room

#### Subrooms

- lower level
- upper level

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| L | left | lower level | [the marrow skull wall](#the-marrow-skull-wall) -R | none |

#### Subroom Connections

| alias | name | source | destination | requirements |
| --- | --- | --- | --- | --- |
| CG | climb | lower level | upper level | cling grip or silk soar |
| CG | climb | upper level | lower level | cling grip or silk soar |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| lore tablet | lower level |  | NOT ACTUALLY A CHECK |
| memory locket 3 | upper level |  | not on the tracker |
| gauntlet fight | upper level |  | not on the tracker / what are the trigger conditions? |

### The Marrow Skull Wall

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| F | floor |  | [the marrow shaft](#the-marrow-shaft) -C | none |
| R | right |  | [the marrow skull wall side room](#the-marrow-skull-wall-side-room) -L | none |
| L | left |  | TODO |  |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| flea the marrow tangle |  | none |  |

### The Marrow Upper Pogo

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| F | floor |  | [the marrow lower pogo](#the-marrow-lower-pogo) | none |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| rosary cache the marrow 14 |  | none | MARKED AS ??? ON TRACKER |
| rosary cache the marrow 15 |  | none | MARKED AS ??? ON TRACKER |
| rosary cache the marrow 16 |  | none | MARKED AS ??? ON TRACKER |
| rosary chest |  | none | NOT RANDOMIZED YET |

### The Marrow Vertical Shaft Side Room

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| R | right |  | [the marrow shaft](#the-marrow-shaft) -LL | none |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| shard pendant |  | none |  |

## Weavenest Atla

### Weavenest Atla Bench

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| R | right |  | [weavenest atla teleporter](#weavenest-atla-teleporter) -LL | none |
| L | left |  | [weavenest atla grotto](#weavenest-atla-grotto) -R | none |

#### Notes

no checks but there is a bench

### Weavenest Atla Entrance

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| WD | weavenest door |  | [moss grotto east](#moss-grotto-east) -WD | needolin |
| R | right |  | [weavenest atla teleporter](#weavenest-atla-teleporter) -UL | none |

### Weavenest Atla Eva

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| L | left |  | [weavenest atla teleporter](#weavenest-atla-teleporter) -LR | cling grip OR silk soar |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| crest of the hunter |  | TODO |  |
| yellow vesticrest |  | TODO |  |
| blue vesticrest |  | TODO |  |
| crest of the hunter 2 |  | TODO |  |
| sylphsong |  | TODO |  |

### Weavenest Atla Grotto

#### Subrooms

- pathway
- mossberry platform
- boss room

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| R | right | pathway | [weavenest atla bench](#weavenest-atla-bench) -L | none |

#### Subroom Connections

| alias | name | source | destination | requirements |
| --- | --- | --- | --- | --- |
| MP | mossberry platform jump | pathway | mossberry platform | run OR dash OR faydown cloak OR horizontal movement tech OR silksoar |
| MP | mossberry platform jump | mossberry platform | pathway | none (falling) |
| BR | boss room jump | pathway | boss room | run OR dash OR faydown cloak OR horizontal movement tech |
| BR | boss room jump | boss room | pathway | none (falling) |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| mossberry | mossberry platform |  |  |
| double moss mother boss fight | boss room |  | NOT CURRENTLY TRACKED |
| weavelight | boss room | defeat double moss mother |  |

### Weavenest Atla Hallway

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| L | left |  | [weavenest atla teleporter](#weavenest-atla-teleporter)-MR | none |
| R | right |  | [weavenest atla lore](#weavenest-atla-lore) -L | none |

### Weavenest Atla Lore

#### Subrooms

- main area
- right exit

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| L | left | main area | [weavenest atla hallway](#weavenest-atla-hallway) -R | none |
| R | right | right exit | [weavenest atla mask shard](#weavenest-atla-mask-shard) -L | none |

#### Subroom Connections

| alias | name | source | destinatio n | requirements |
| --- | --- | --- | --- | --- |
| CL | climb pit | main area | right exit | dash OR horizontal movement tech OR faydown cloak |
| CL | climb pit | right exit | main area | cling grip AND ( dash OR horizontal movement tech OR faydown cloak ) |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| rune harp weavenest atla |  | none |  |
| readable lore tablet |  | none | NOT ACTUALL A CHECK |

### Weavenest Atla Mask Shard

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| L | left |  | [weavenest atla lore](#weavenest-atla-lore) -R | none |

#### Check Locations

| check | subroo m | requirements | notes |
| --- | --- | --- | --- |
| weavenest alta mask shard |  | cling grip AND ( clawline OR ( faydown cloak AND dash ) ) | NEEDS VERIFICATION BY SOMEONE BETTER THAN ME |

### Weavenest Atla Power

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| L | left |  | [weavenest atla teleporter](#weavenest-atla-teleporter) -UR | none |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| power activation |  | none | NOT CURRENTLY RANDOMIZED |
| weavenest atla map |  | none | weavenest atla power activation |

### Weavenest Atla Snare

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| F | floor |  | [weavenest atla spool](#weavenest-atla-spool) -C | none (falling) |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| snare setter |  | none |  |

### Weavenest Atla Spool

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| R | right |  | [weavenest atla teleporter](#weavenest-atla-teleporter) - ML | none |
| C | ceiling |  | [weavenest atla snare](#weavenest-atla-snare) -F | silk soar OR ( faydown cloak + cling grip ) |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| weavenest atla spool fragment |  | none |  |

### Weavenest Atla Teleporter

#### Subrooms

- upper telepad
- upper shaft
- lower shaft
- lower telepad

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| UL | upper left | upper telepad | [weavenest atla entrance](#weavenest-atla-entrance) -R | none |
| ML | middle left | lower shaft | [weavenest atla spool](#weavenest-atla-spool) -R | none |
| LL | lower left | lower telepad | [weavenest atla bench](#weavenest-atla-bench) -R | none |
| UR | upper right | upper telepad | [weavenest atla power](#weavenest-atla-power) -L | none |
| MR | middle right | upper shaft | [weavenest atla hallway](#weavenest-atla-hallway) -L | none |
| LR | lower right | lower telepad | [weavenest atla eva](#weavenest-atla-eva) -L | none |

#### Subroom Connections

| alias | name | source | destination | requirements |
| --- | --- | --- | --- | --- |
| TP | teleporter | upper telepad | lower telepad | weavenest atla power activation |
| TP | teleporter | lower telepad | upper telepad | weavenest atla power activation |
| SM | shaft middle | lower telepad | upper shaft | requires cling grip OR silk soar |
| SM | shaft middle | upper shaft | lower telepad | none (falling) |
| SB | shaft base | lower telepad | lower shaft | requires cling grip OR silk soar |
| SB | shaft base | lower shaft | lower telepad | none (falling) |

#### Check Locations

| check | subroom |
| --- | --- |
| none |  |
|  |  |
|  |  |
|  |  |
|  |  |

## Wormways

### Wormways Craggler Hallway

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| L | left |  | [wormways shaft](#wormways-shaft) -LR | none |
| R | right |  | [the big fall](#the-big-fall) -LL | none |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| craggler mini boss fight |  | none |  |
| beast shard |  | defeat craggler | NOT CURRENTLY RANDOMIZED |

### Wormways Flea Rescue

#### Subrooms

- entrance
- main area

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| L | left | entrance | [wormways shaft](#wormways-shaft) -MR | none |

#### Subroom Connections

| alias | name | source | destination | requirements |
| --- | --- | --- | --- | --- |
| D | dash | entrance | main area | any horizontal movement tech (small low gap) |
| D | dash | main area | entrance | any horizontal movement tech (small low gap) |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| flea wormways snacc | main area | none |  |

### Wormways Laboratory

#### Room Transitions

| alias | name | from subroom | destination |
| --- | --- | --- | --- |
| F | floor |  | [wormways upper west](#wormways-upper-west) |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| needle phial |  | none |  |
| plasmium phial |  | filled needle phial |  |
| wish missing assitant |  | TODO |  |

### Wormways Lower East

#### Subrooms

- ceiling exit area
- left exit area
- tunnels
- floor exit area

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| C | ceiling | ceiling exit area | [wormways middle](#wormways-middle) -F | none |
| L | left | left exit area | [wormways lower west](#wormways-lower-west) -R | none |
| F | floor | floor exit area | [bonegrave](#bonegrave) -C | none |

#### Subroom Connections

| alias | name | source | destination | requirements |
| --- | --- | --- | --- | --- |
| CC | ceiling climb | ceiling exit area | tunnels | cling grip |
| CC | ceiling climb | tunnels | ceiling exit area | cling grip |
| LC | left climb | left exit area | tunnels | cling grip |
| LC | left climb | tunnels | left exit area | cling grip |
| RC | floor climb | floor exit area | tunnels | cling grip |
| RC | floor climb | tunnels | floor exit area | cling grip |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| plasmium spot | tunnels | need phial | NOT CURRENTLY RANDOMIZED |

#### Notes

this one seems a bit tricky, but also it's just a bit late
i think you need cling grip to from any one point to another in here
TODO: review the mapping in here

### Wormways Lower West

#### Subrooms

- left exit area
- right exit area
- tunnels

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| R | right | right exit area | [wormways lower east](#wormways-lower-east) -L | none |
| L | left | left exit area | [wormways zango arena](#wormways-zango-arena) -R | none |

#### Subroom Connections

| alias | name | source | destination | requirements |
| --- | --- | --- | --- | --- |
| LC | left climb | left exit area | tunnels | cling grip |
| LC | left climb | tunnels | left exit area | cling grip |
| RC | right climb | right exit area | tunnels | cling grip |
| RC | right climb | tunnels | right exit area | cling grip |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| memory locket | tunnels | none | NOT RANDOMIZED YET |
| plasmium pustule | tunnels | needle phial | NOT RANDOMIZED YET |

#### Notes

this one seems a bit tricky, but also it's just a bit late
i think you need cling grip to from any one point to another in here
TODO: review the mapping in here

### Wormways Middle

#### Subrooms

- right area
- left area

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| R | right | right area | [wormways shaft](#wormways-shaft) -LL | door must be unlocked from the other side |
| F | floor | right area | [wormways lower east](#wormways-lower-east) - C | none |
| C | ceiling | left area | [wormways upper west](#wormways-upper-west) -F | none |

#### Subroom Connections

| alias | name | source | destination | requirements |
| --- | --- | --- | --- | --- |
| RJ | running jump | left area | right area | run OR dash OR faydown cloak OR sharpdart OR clawline |
| RJ | running jump | right area | left area | none (falling) |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |

### Wormways Shaft

#### Subrooms

- lower area
- middle platform area
- upper platform area

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| LR | lower right | lower area | [wormways craggler hallway](#wormways-craggler-hallway) -L | none |
| LL | lower left | lower area | [wormways middle](#wormways-middle) -R | door unlocked |
| UL | upper left | upper platform area | [wormways upper west](#wormways-upper-west) -R | breakable wall -must be opened from the other side (verified) |
| UR | upper right | middle platform area | [wormways upper east](#wormways-upper-east) -L | none |
| MR | middle right | middle platform area | [wormways flea rescue](#wormways-flea-rescue) -L | none |

#### Subroom Connections

| alias | name | source | destination | requirements |
| --- | --- | --- | --- | --- |
| DS | door switch | platform area | lower area | none (door switch is on this side) |
| DS | door switch | lower area | platform area | door switch needs to be flipped |
| CG | platform gaps | middle platform area | upper platform area | silk soar OR ( cling grip AND (faydown cloak or horizontal movement tech) ) |
| CG | platform gaps | upper platform area | middle platform area | none (falling) |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| use simple key on lock | lower area | simple key | unlocks the LL room exit |
| mask shard | lower area | none |  |
| frayed rosary string wormways | upper platform area | cling grip OR silk soar |  |

### Wormways Upper East

#### Subrooms

- lower area
- upper area

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| L | left | lower area | [wormways shaft](#wormways-shaft) -UR | none |
| R | right | upper area | [the big fall](#the-big-fall) -UL | none |

#### Subroom Connections

| alias | name | source | destinatio n | requirements |
| --- | --- | --- | --- | --- |
| LD | left dash | lower area | upper area | run OR dash OR cling grip OR faydown cloak OR sharpdart OR clawline |
| LD | left dash | upper area | lower area | none (falling) |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| dead bugs purse | upper area | none | STILL MARKED AS ??? ON TRACKER |
| shakra shop items | upper area |  | :) |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |

### Wormways Upper West

#### Subrooms

- main area
- plasmium spot
- weavenest landing

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| F | floor | main area | [wormways middle](#wormways-middle) -C |  |
| R | right | main area | [wormways shaft](#wormways-shaft) -UL |  |
| C | ceiling | main area | [wormways laboratory](#wormways-laboratory) -F | silk soar OR cling grip |
| WD | weaver door | weavenest landing | [wormways weavenest](#wormways-weavenest) -WD | needolin |

#### Subroom Connections

| alias | name | source | destination | requirements |
| --- | --- | --- | --- | --- |
| CG | climb | main area | plasmium spot | cling grip OR silk soar OR faydown cloak |
| CG | climb | plasmium spot | main area | cling grip OR silk soar OR faydown cloak |
| BJ | big jump | main area | weavenest landing | silk soar OR faydown cloak OR ( run AND dash AND clawline ) |
| BJ | big jump | weavenest landing | main area | none (falling) |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| plasmium pustule | plasmium spot | needle phial | NOT RANDOMIZED YET |

### Wormways Weavenest

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| WD | weaver door |  | [wormways upper west](#wormways-upper-west) -WD | needolin |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| sharpdart |  | none |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |

### Wormways Zango Arena

#### Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| R | right |  | [wormways lower west](#wormways-lower-west) -L | none |

#### Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| plasmified zango boss fight |  | TODO (act 3?) |  |
