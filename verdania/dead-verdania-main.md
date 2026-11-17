# Dead Verdania Main (Clover_01)

**Game ID:** Clover_01

**Contributors:** Pyxl

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | Left Transition | ✓ |
| S2 | Green Prince | ✓ |
| S3 | Right Transition | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Left Transition | [Greymoor Craw Lake (Greymoor_15b)](../greymoor/greymoor-craw-lake.md) | LR | None |  | Verified | ✓ | Unless wall on other side is broken you cant go further than 2 steps out the room |
| R | right1 | Right Transition | [Dead Verdania Bench (Clover_20)](dead-verdania-bench.md) | L | None |  | Verified | ✓ |  |
| DR | door_wakeOnGround | Green Prince | [Verdania Entrance (Clover_01b)](verdania-entrance.md) | L | Needolin AND Elegy of the deep |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| SP | Spikes | Left Transition | Green Prince | spike pogo OR Clawline right X 3 OR ( Faydown Cloak AND ( Drifters Cloak OR ( Sprint AND ( Ledge Grab right OR Cling Grip right OR Dash right ) ) OR ( Dash right AND Cling Grip right ) OR Sharpdart ) ) OR ( Sprint AND ( ( Ledge Grab right AND Medium Beast Needle Strike  ) OR Drifters Cloak ) ) OR ( Drifters Cloak AND ( Cling Grip right OR Scuttlebrace ) ) OR  ( Sharpdart AND ( Drifters Cloak OR Sprint OR Dash right OR Easy Beast Crest Pogo OR Easy air bind Stall OR Medium Flea Brew Stall OR Easy Flintslate Stall OR Easy Plasmium Phial Stall OR Medium Voltvessels Stall OR  Easy Shaman Crest Pogo ) ) |  | Verified | ✓ |  |
| SP | Spikes | Green Prince | Left Transition | spike pogo OR Clawline left X 3 OR ( Faydown Cloak AND ( Drifters Cloak OR ( Sprint AND ( Ledge Grab left OR Cling Grip left OR Dash left ) ) OR ( Dash left AND Cling Grip left ) OR Sharpdart ) ) OR ( Sprint AND ( ( Ledge Grab left AND Medium Beast Needle Strike  ) OR Drifters Cloak ) ) OR ( Drifters Cloak AND ( Cling Grip left OR Scuttlebrace ) ) OR  ( Sharpdart AND ( Drifters Cloak OR Sprint OR Dash left OR Easy Beast Crest Pogo OR Easy air bind Stall OR Medium Flea Brew Stall OR Easy Flintslate Stall OR Easy Plasmium Phial Stall OR Medium Voltvessels Stall OR  Easy Shaman Crest Pogo ) ) |  | Verified | ✓ |  |
| BW | Breakable Wall | Green Prince | Right Transition | Prereq Dead Verdania Breakable Wall Left Side OR Prereq Dead Verdania Breakable Wall Right Side |  | Verified | ✓ |  |
| BW | Breakable Wall | Right Transition | Green Prince | Prereq Dead Verdania Breakable Wall Left Side OR Prereq Dead Verdania Breakable Wall Right Side |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Dead Verdania Breakable Wall Left Side | Green Prince | Needle Up OR Needle Right OR Needle Down |  | Verified | blockade | ✓ | Same Wall |
| 2 | Dead Verdania Breakable Wall Right Side | Right Transition | Needle Up OR Needle Left OR Needle Down |  | Verified | blockade | ✓ | Same Wall |

## Room Images

### Connections

[![Connections for Dead Verdania Main (Clover_01)](../00-annotations/verdania/dead-verdania-main-connections.png)](../00-annotations/verdania/dead-verdania-main-connections.png)

### Checks

[![Checks for Dead Verdania Main (Clover_01)](../00-annotations/verdania/dead-verdania-main-checks.png)](../00-annotations/verdania/dead-verdania-main-checks.png)

### Scene

[![Scene for Dead Verdania Main (Clover_01)](../00-annotations/verdania/dead-verdania-main-scene.png)](../00-annotations/verdania/dead-verdania-main-scene.png)
