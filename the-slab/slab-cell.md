# Slab Cell (Slab_03)

**Game ID:** Slab_03

## Subrooms

- L0L
- L0R
- L1
- L2L
- L2R
- L3L
- L3R
- Key of Heretic Bridge
- L4
- L5L
- L5R
- L6
- L7
- L8

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| CPT | door_slabCaged | L1 | TODO |  | Captured Event |  |  | no destination, logically equivalent to L1 since you need to go up to reach L0 |
| L0L | left1 | L0L | [Slab Arena (Slab_16)](slab-arena.md) | R | none |  |  |  |
| L0R | right1 | L0R | [Slab Why Room (Slab_17)](slab-why-room.md) | L | Apostate Key Owned |  |  |  |
| L1L | left2 | L1 | [Slab Chilly Prison (Slab_15)](slab-chilly-prison.md) | R | none |  |  |  |
| L1R | right2 | L1 | [Slab Secret Side Room (Slab_18)](slab-secret-side-room.md) | L | One way (opens from the other side) |  |  | One way (opens from the other side) |
| L2L | left3 | L2L | [Slab Indolent Room (Slab_14)](slab-indolent-room.md) | R | none |  |  |  |
| L2R | right3 | L2R | [Slab Grindle (Slab_20)](slab-grindle.md) | L | none |  |  |  |
| L3L | left4 | L3L | [Slab Flea Prison (Slab_13)](slab-flea-prison.md) | R | none |  |  |  |
| L3R | right4 | L3R | [Slab Cavern Exit (Slab_23)](slab-cavern-exit.md) | L | none |  |  |  |
| L4L | left5 | L4 | [Slab Infleatween Top (Slab_04)](slab-infleatween-top.md) | R | none |  |  |  |
| L4R | right5 | L4 | [Slab Entrance (Slab_02)](slab-entrance.md) | L | opens from the other side |  |  |  |
| L5L | left6 | L5L | [Slab Infleatween Bottom (Slab_05)](slab-infleatween-bottom.md) | R | Key of Apostate Owned |  |  |  |
| L5R | right8 | L5R | [Slab Cave Entrance (Slab_08)](slab-cave-entrance.md) | L | none |  |  |  |
| L6R | right7 | L6 | [Slab Prelude (Slab_19b)](slab-prelude.md) | L | Key of Heretic Owned |  |  |  |
| L7L | left7 | L7 | [Slab Poodle (Slab_07)](slab-poodle.md) | R1 | Breakable Wall (opened from the other side) |  |  |  |
| L8L | left8 | L8 | [Slab Poodle (Slab_07)](slab-poodle.md) | R2 | none |  |  |  |
| L8R | right9 | L8 | [Slab Window (Slab_12)](slab-window.md) | L | Breakable Wall (from this side) |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| L0 | L0 - L0 | L0L | L0R | ledge grab or cling grip |  |  | Naked |
| 0L1 | L0l - L1 | L0L | L1 | none |  |  | falling |
| 0R1 | L0R - L1 | L0R | L1 | none |  |  | falling |
| 0L1 | L0l - L1 | L1 | L0L | cling grip or silk soar |  |  | Naked |
| 0R1 | L0R - L1 | L1 | L0R | cling grip or silk soar |  |  | Naked |
| 2L1 | L2L - L1 | L2L | L1 | cling grip or silk soar |  |  | Naked. One way only |
| 2R1 | L2R - L1 | L2R | L1 | cling grip or silk soar |  |  | Naked. One way only |
| L2 | L2 - L2 | L2L | L2R | ledge grab or silk soar |  |  | Naked |
| L2 | L2 - L2 | L2R | L2L | ledge grab or silk soar |  |  | Naked |
| 2FL | L2L to L3L | L2L | L3L | none |  |  | falling |
| 2FR | L2L to L3R | L2L | L3R | none |  |  | falling |
| 2DL | L2R to L3L | L2R | L3L | none |  |  | falling |
| 2DR | L2R to L3R | L2R | L3R | none |  |  | falling |
| L3 | L3 - L3 | L3L | L3R | cling grip or silk soar or dash |  |  | Naked. When you are still naked the bridge should be closed enabling you to just walk over it but added prior transitions to still have a valid path. |
| BR1 | Bridge1 | L3L | Key of Heretic Bridge | Key of Heretic Owned |  |  |  |
| BR2 | Bridge2 | L3R | Key of Heretic Bridge | Key of Heretic Owned |  |  |  |
| BL4 | Bridge to L4 | L4 | Key of Heretic Bridge | none |  |  | falling, one way lever |
| 5R4 | L5R to L4 | L5R | L4 | cling grip |  |  | one way lever |
| 5L4 | L5L to L4 | L5L | L4 | cling grip and faydown |  |  | one way lever |
| L5 | L5 | L5L | L5R | (dash and ledge grab) or faydown or clawline or cling grip |  |  |  |
| L5 | L5 | L5R | L5L | ledge grab or faydown or clawline or dash |  |  |  |
| 5LF | L5L to L6 | L5L | L6 | none |  |  | falling |
| 5LF | L5L to L6 | L6 | L5L | (cling grip or silk soar) and (ledge grab or faydown or clawline or dash) |  |  |  |
| 5RF | L5R to L6 | L5R | L6 | none |  |  | falling |
| 5RF | L5R to L6 | L6 | L5R | cling grip or silk soar |  |  |  |
| L6F | L6 to L8 | L6 | L8 | swim |  |  | L7 is non existant until opened |
| L7F | L7 to L8 | L7 | L8 | swim |  |  | falling |
| L7U | L7 to L6 | L7 | L6 | cling grip |  |  |  |

## Check Locations

No check locations defined.
