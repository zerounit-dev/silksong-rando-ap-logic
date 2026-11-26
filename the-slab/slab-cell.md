# Slab Cell (Slab_03)

**Game ID:** Slab_03

**Contributors:** MayaXTG

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | Arena | ✓ |
| S2 | Why1 | ✓ |
| S3 | Why2 | ✓ |
| S4 | Upper | ✓ |
| S5 | Chilly | ✓ |
| S6 | Secret | ✓ |
| S7 | Mid | ✓ |
| S8 | Indolent | ✓ |
| S9 | Grindle | ✓ |
| S10 | Before Indolent | ✓ |
| S11 | Before Bridge | ✓ |
| S12 | Bridge Upper | ✓ |
| S13 | Bridge Upper Internal | ✓ |
| S14 | Bridge Center | ✓ |
| S15 | Bridge Center Top | ✓ |
| S16 | Flea2 | ✓ |
| S17 | Cavern | ✓ |
| S18 | Prelude1 | ✓ |
| S19 | Prelude2 | ✓ |
| S20 | Poodle Top | ✓ |
| S21 | Poodle Bottom | ✓ |
| S22 | Window | ✓ |
| S23 | Almost Bottom | ✓ |

- **Why2:** Entering via WHY will block you behind a door you can't open from that side

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| CPT | door_slabCaged | Upper | [Slab Capture](../fast-travel/slab-capture.md) | CG | invalid |  | Verified | ✓ | one way only |
| ARN | left1 | Arena | [Slab Arena (Slab_16)](slab-arena.md) | R | none |  | Verified | ✓ |  |
| WHY | right1 | Why1 | [Slab Why Room (Slab_17)](slab-why-room.md) | L | none |  | Verified | ✓ | the "lock" is defined in the subroom connection between Why1 and Why2 |
| CHL | left2 | Chilly | [Slab Chilly Prison (Slab_15)](slab-chilly-prison.md) | R | none |  | Verified | ✓ |  |
| SCR | right2 | Secret | [Slab Secret Side Room (Slab_18)](slab-secret-side-room.md) | L | clear Breakable Wall Blockade IN slab secret side room |  | Verified | ✓ | opens from other side mid blockade not necessary |
| IND | left3 | Indolent | [Slab Indolent Room (Slab_14)](slab-indolent-room.md) | R | none |  | Verified | ✓ |  |
| GRN | right3 | Grindle | [Slab Grindle (Slab_20)](slab-grindle.md) | L | none |  | Verified | ✓ |  |
| FL1 | left4 | Bridge Upper | [Slab Flea Prison (Slab_13)](slab-flea-prison.md) | R | none |  | Verified | ✓ |  |
| CVN | right4 | Bridge Upper | [Slab Cavern Exit (Slab_23)](slab-cavern-exit.md) | L | none |  | Verified | ✓ |  |
| F2T | left5 | Bridge Center | [Slab Infleatween Top (Slab_04)](slab-infleatween-top.md) | R | none |  | Verified | ✓ |  |
| ENT | right5 | Bridge Center | [Slab Entrance (Slab_02)](slab-entrance.md) | L | activate slab entrance switch IN slab entrance |  | Verified | ✓ |  |
| F2B | left6 | Flea2 | [Slab Infleatween Bottom (Slab_05)](slab-infleatween-bottom.md) | R | have Key of Apostate |  | Verified | ✓ |  |
| CAV | right8 | Cavern | [Slab Cave Entrance (Slab_08)](slab-cave-entrance.md) | L | none |  | Verified | ✓ |  |
| PRL | right7 | Prelude1 | [Slab Prelude (Slab_19b)](slab-prelude.md) | L | unlock heretic door first sinner |  | Verified | ✓ |  |
| PDT | left7 | Poodle Top | [Slab Poodle (Slab_07)](slab-poodle.md) | R1 | none |  | Verified | ✓ |  |
| PDB | left8 | Poodle Bottom | [Slab Poodle (Slab_07)](slab-poodle.md) | R2 | none |  | Verified | ✓ |  |
| WND | right9 | Window | [Slab Window (Slab_12)](slab-window.md) | L | break wall right |  | Verified | ✓ | will take damage upon entering |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| A | ArenaUpper | Arena | Upper | none (falling) |  | Verified | ✓ |  |
| A | ArenaUpper | Upper | Arena | ledge grab left OR cling grip left OR faydown cloak OR silk soar |  | Verified | ✓ |  |
| B | WhyUpper | Why2 | Upper | none (falling) |  | Verified | ✓ |  |
| B | WhyUpper | Upper | Why2 | ledge grab right OR cling grip right OR faydown cloak OR silk soar |  | Verified | ✓ |  |
| WHY | WhyInternal | Why1 | Why2 | unlock apostate door mask shard |  | Verified |  | ping maya for info as to why i did this |
| WHY | WhyInternal | Why2 | Why1 | unlock apostate door mask shard |  | Verified |  |  |
| C | UpperChilly | Upper | Chilly | none (falling) |  | Verified | ✓ |  |
| C | UpperChilly | Chilly | Upper | ledge grab right OR cling grip right OR scuttlebrace OR faydown cloak OR silk soar OR medium shaman pogo OR ((clear Breakable Wall Blockade IN slab secret side room OR clear upper blockade) AND (ledge grab left OR cling grip left)) |  | Verified | ✓ | right side is only available if you remove the blockade inside Mid |
| D | UpperSecret | Upper | Secret | clear Breakable Wall Blockade IN slab secret side room AND clear upper blockade |  | Verified | ✓ |  |
| D | UpperSecret | Secret | Upper | (clear Breakable Wall Blockade IN slab secret side room AND clear upper blockade) AND (ledge grab any OR cling grip any OR scuttlebrace OR faydown cloak OR silk soar OR medium shaman pogo) |  | Verified | ✓ |  |
| E | ChillyMid | Chilly | Mid | clear Breakable Wall Blockade IN slab secret side room OR clear upper blockade |  | Verified | ✓ | falling |
| E | ChillyMid | Mid | Chilly | (clear Breakable Wall Blockade IN slab secret side room OR clear upper blockade) AND (cling grip any OR faydown cloak OR scuttlebrace OR silk soar) |  | Verified | ✓ |  |
| F | SecretMid | Secret | Mid | clear Breakable Wall Blockade IN slab secret side room AND clear upper blockade |  | Verified | ✓ | falling |
| F | SecretMid | Mid | Secret | clear Breakable Wall Blockade IN slab secret side room AND clear upper blockade AND (cling grip any OR faydown cloak OR scuttlebrace OR silk soar) |  | Verified | ✓ |  |
| G | MidIndolent | Mid | Indolent | none (falling) |  | Verified | ✓ |  |
| G | MidIndolent | Indolent | Mid | cling grip left OR silk soar OR (faydown cloak AND cling grip right) OR scuttlebrace |  | Verified | ✓ |  |
| H | MidGrindle | Mid | Grindle | none (falling) |  | Verified | ✓ |  |
| H | MidGrindle | Grindle | Mid | cling grip right OR silk soar OR (faydown cloak AND cling grip left) OR scuttlebrace |  | Verified | ✓ |  |
| I | IndolentBefore | Indolent | Before Indolent | none (falling) |  | Verified | ✓ |  |
| I | IndolentBefore | Before Indolent | Indolent | cling grip left OR ledge grab left OR silk soar OR faydown cloak OR medium shaman pogo |  | Verified | ✓ |  |
| J | GrindleBefore | Grindle | Before Indolent | none (falling) |  | Verified | ✓ |  |
| J | GrindleBefore | Before Indolent | Grindle | cling grip right OR ledge grab right OR silk soar OR faydown cloak OR medium shaman pogo |  | Verified | ✓ |  |
| K | IndoBridge | Before Indolent | Before Bridge | none (falling) |  | Verified | ✓ |  |
| K | IndoBridge | Before Bridge | Before Indolent | cling grip any OR scuttlebrace OR faydown cloak OR silk soar |  | Verified | ✓ |  |
| L | BeforeUpper | Before Bridge | Bridge Upper | none (falling) |  | Verified | ✓ |  |
| L | BeforeUpper | Bridge Upper | Before Bridge | cling grip any OR ledge grab any OR faydown cloak OR scuttlebrace |  | Verified | ✓ |  |
| M | UpperInternal | Bridge Upper | Bridge Upper Internal | unlock upper bridge key |  | Verified | ✓ | falling |
| M | UpperInternal | Bridge Upper Internal | Bridge Upper | unlock upper bridge key AND (cling grip any OR silk soar OR scuttlebrace) |  | Verified | ✓ |  |
| N | InternalCenter | Bridge Upper Internal | Bridge Center | activate heretic lever upper |  | Verified | ✓ | falling |
| N | InternalCenter | Bridge Center | Bridge Upper Internal | activate heretic lever upper AND (cling grip any OR (faydown cloak AND ledge grab left) OR scuttlebrace OR silk soar) |  | Verified | ✓ |  |
| O | CenterTop | Bridge Center | Bridge Center Top | activate heretic lever lower |  | Verified | ✓ | falling |
| O | CenterTop | Bridge Center Top | Bridge Center | activate heretic lever lower AND (cling grip any OR scuttlebrace OR faydown) |  | Verified | ✓ |  |
| P | Center Cavern | Bridge Center Top | Cavern | none (falling) |  | Verified | ✓ |  |
| P | Center Cavern | Cavern | Bridge Center Top | cling grip either OR silk soar OR (easy scuttlebrace AND (faydown OR medium shaman pogo OR medium beast bind stall)) |  | Verified | ✓ |  |
| R | CavernCrossing | Flea2 | Cavern | sprint right OR faydown OR sharpdart OR clawline right OR cling grip either OR easy beast pogo OR flea brew OR (medium [hunter,architect] pogo AND (medium voltvessels stall OR medium plasmium stall x 2 OR ((medium silkshot original stall OR easy plasmium stall) AND ledge grab right))) |  | Verified | ✓ |  |
| R | CavernCrossing | Cavern | Flea2 | sprint left OR cling grip left OR ledge grab left OR sharpdart OR clawline left OR easy flea brew stall OR (easy [hunter,architect] pogo AND medium silkshot original stall) OR easy [voltvessels,plasmium] stall OR easy shaman pogo OR easy beast pogo |  | Verified | ✓ |  |
| S | DropPrelude | Flea2 | Prelude1 | none (falling) |  | Verified | ✓ |  |
| T | FallPrelude | Cavern | Prelude1 | none (falling) |  | Verified | ✓ |  |
| T | FallPrelude | Prelude1 | Cavern | cling grip right  OR (medium scuttlebrace AND (medium shaman pogo OR easy beast bind stall))  OR (faydown cloak AND cling grip left) OR silk soar |  | Verified | ✓ |  |
| U | PreludePoodle | Prelude1 | Almost Bottom | none (falling) |  | Verified | ✓ |  |
| U | PreludePoodle | Almost Bottom | Prelude1 | (cling grip any OR scuttlebrace) |  | Verified | ✓ |  |
| V | PreludeBottom | Almost Bottom | Window | swim OR dash right OR clawline right OR faydown OR drifters OR sharpdart |  | Verified | ✓ |  |
| W | PoodleBottom | Almost Bottom | Poodle Bottom | swim OR dash left OR clawline left OR faydown OR drifters OR sharpdart |  | Verified | ✓ |  |
| W | PoodleBottom | Poodle Bottom | Almost Bottom | (proficient movement AND faydown AND dash left AND cling grip left) OR (cling grip either AND ((faydown AND easy [hunter,wanderer] voltwater pogo) OR medium wanderer voltwater pogo)) OR (cling grip left AND medium hunter voltwater pogo x 2) |  | Verified | ✓ |  |
| X | PoodleBB | Poodle Bottom | Window | swim  OR sprint right  OR clawline right  OR faydown  OR drifters OR easy beast pogo OR easy [architect,beast] charge OR (ledge grab right AND (medium architect pogo OR easy voltvessels stall x 2 OR ((medium hunter pogo OR hard shaman pogo) AND cling grip left AND proficient movement))) OR (easy [hunter,architect] pogo AND medium [voltvessels,silkshot original] stall) OR easy [hunter,wanderer] voltwater pogo |  | Verified | ✓ |  |
| X | PoodleBB | Window | Poodle Bottom | swim  OR sprint left  OR clawline left  OR faydown  OR drifters  OR easy beast pogo  OR ((ledge grab left OR cling grip left) AND (easy architect charge)) OR (easy [hunter,architect] pogo AND medium [voltvessels,silkshot original] stall) OR easy [hunter,wanderer] voltwater pogo |  | Verified | ✓ |  |
| PRE | PreludeInternal | Prelude1 | Prelude2 | unlock heretic door first sinner |  | Verified |  |  |
| PRE | PreludeInternal | Prelude2 | Prelude1 | unlock heretic door first sinner |  | Verified |  |  |
| Y | PoodleTopCross | Poodle Top | Almost Bottom | unlock poodle blockade |  | Verified | ✓ |  |
| Y | PoodleTopCross | Almost Bottom | Poodle Top | unlock poodle blockade |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | poodle blockade | Poodle Top | none |  | Verified | blockade | ✓ |  |
| 2 | heretic lever upper | Bridge Upper Internal | none |  | Verified | switch | ✓ |  |
| 3 | heretic lever lower | Bridge Center Top | none |  | Verified | switch | ✓ |  |
| 4 | apostate door mask shard | Why2 | have key of apostate |  | Verified | lock |  |  |
| 5 | heretic door first sinner | Prelude1 | have key of heretic |  | Verified | lock |  |  |
| 6 | upper blockade | Mid | none |  | Verified | blockade | ✓ |  |
| 7 | upper bridge key | Bridge Upper | have key of heretic |  | Verified | lock | ✓ |  |
| 8 | Guardfly 1 | Before Indolent | none |  | Verified | enemy | ✓ |  |
| 9 | Guardfly 2 | Flea2 | none |  | Verified | enemy | ✓ |  |

## Notes

I'll go over this when I'm more sane

## Room Images

### Connections

[![Connections for Slab Cell (Slab_03)](../00-annotations/the-slab/slab-cell-connections.png)](../00-annotations/the-slab/slab-cell-connections.png)

### Checks

[![Checks for Slab Cell (Slab_03)](../00-annotations/the-slab/slab-cell-checks.png)](../00-annotations/the-slab/slab-cell-checks.png)

### Scene

[![Scene for Slab Cell (Slab_03)](../00-annotations/the-slab/slab-cell-scene.png)](../00-annotations/the-slab/slab-cell-scene.png)
