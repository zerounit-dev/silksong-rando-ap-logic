# Verdania Entrance (Clover_01b)

**Game ID:** Clover_01b

**Contributors:** Pyxl

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | Entrance | ✓ |
| S2 | Right Side | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Right Side | [Verdania Big Room (Clover_02c)](verdania-big-room.md) | LL | None |  | Verified | ✓ |  |
| L | door_wakeInMemory | Entrance | [Dead Verdania Main (Clover_01)](dead-verdania-main.md) | DR | None |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| GP | Green Prince | Entrance | Right Side | ( Swim AND ( Ledge Grab Right OR Cling Grip Right OR ( Easy air bind Stall AND Easy Beast Crest Pogo ) OR Dash Right OR Scuttlebrace OR Faydown Cloak OR Easy Enemy Pogo OR Easy Shaman Pogo ) ) OR Clawline Right OR ( Faydown Cloak AND ( Drifters Cloak OR Easy Beast Crest Pogo OR Sharpdart OR ( Sprint Right AND Dash Right ) OR Easy Enemy Pogo ) ) OR ( Drifters Cloak AND ( Cling Grip Right OR Sprint Right OR ( Dash Right AND Proficient Movement ) OR Sharpdart ) ) OR ( Easy Beast Crest Pogo AND ( Sharpdart OR ( Sprint Right AND Dash RIght ) ) ) |  | Verified | ✓ |  |
| GP | Green Prince | Right Side | Entrance | Swim OR ( Drifters Cloak AND ( Proficient Movement OR Dash Left OR Sprint Left OR Cling Grip Left OR Ledge Grab Left ) ) OR Clawline Left OR ( Easy Enemy pogo AND ( Easy Beast Crest Pogo ) ) OR ( Faydown Cloak AND ( Sharpdart OR Dash Left ) ) |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Pendra 1 | Entrance | None |  | Verified | enemy | ✓ |  |
| 2 | Pendra 2 | Right Side | None |  | Verified | enemy | ✓ |  |

## Room Images

### Connections

[![Connections for Verdania Entrance (Clover_01b)](../00-annotations/verdania/verdania-entrance-connections.png)](../00-annotations/verdania/verdania-entrance-connections.png)

### Checks

[![Checks for Verdania Entrance (Clover_01b)](../00-annotations/verdania/verdania-entrance-checks.png)](../00-annotations/verdania/verdania-entrance-checks.png)

### Scene

[![Scene for Verdania Entrance (Clover_01b)](../00-annotations/verdania/verdania-entrance-scene.png)](../00-annotations/verdania/verdania-entrance-scene.png)
