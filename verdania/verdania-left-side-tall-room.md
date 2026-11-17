# Verdania Left Side Tall Room (Clover_05c)

**Game ID:** Clover_05c

**Contributors:** Pyxl

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | Ground Level | ✓ |
| S2 | Lower Level | ✓ |
| S3 | Switch Level | ✓ |
| S4 | Central Level | ✓ |
| S5 | Level which exists cause of a single leaf roller | ✓ |
| S6 | Top Level | ✓ |

- **Switch Level:** only accessible from verdania capital before switch is pressed

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | right2 | Top Level | [Palestag (Clover_19)](palestag.md) | L | None |  | Verified | ✓ |  |
| LL | left2 | Lower Level | [Verdania Left Side Essence Shrine (Clover_21)](verdania-left-side-essence-shrine.md) | R | None |  | Verified | ✓ |  |
| UL | left1 | Central Level | [Verdania Cloverstag Steps (Clover_16)](verdania-cloverstag-steps.md) | R | None |  | Verified | ✓ |  |
| MR | right1 | Switch Level | [Verdania Capital (Clover_04b)](verdania-capital.md) | LL | None |  | Verified | ✓ |  |
| LR | right3 | Ground Level | [Verdania Big Room (Clover_02c)](verdania-big-room.md) | UL | None |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| GL | Ground To Lower | Ground Level | Lower Level | Silk Soar OR ( Faydown Cloak AND Cling Grip Left ) |  | Verified | ✓ |  |
| GL | Ground To Lower | Lower Level | Ground Level | None |  | Verified | ✓ |  |
| LC | Lower to Central | Lower Level | Central Level | Silk Soar OR ( Faydown Cloak AND Cling Grip both AND ( Easy Pogo OFF Pendra OR Clawline Right ) ) |  | Verified | ✓ |  |
| LC | Lower to Central | Central Level | Lower Level | None |  | Verified | ✓ |  |
| CS | Central to Switch | Central Level | Switch Level | prereq verdania gate AND ( Ledge grab right OR Cling Grip left OR Cling Grip Right OR Dash RIght OR ( Easy beast pogo AND easy air bind stall ) OR easy beast charge OR Faydown Cloak OR silk soar) |  | Verified | ✓ |  |
| CS | Central to Switch | Switch Level | Central Level | prereq verdania gate |  | Verified | ✓ |  |
| CL | Central To Roller | Central Level | Level which exists cause of a single leaf roller | ( Silk Soar AND Proficient movement ) OR Cling Grip Left OR Cling Grip Right |  | Verified | ✓ |  |
| CL | Central To Roller | Level which exists cause of a single leaf roller | Central Level | None |  | Verified | ✓ |  |
| SL | Switch To Roller | Switch Level | Level which exists cause of a single leaf roller | prereq verdania gate AND ( cling grip right OR Cling Grip Left OR ( Silk Soar AND Proficient movement ) ) |  | Verified | ✓ |  |
| SL | Switch To Roller | Level which exists cause of a single leaf roller | Switch Level | prereq verdania gate |  | Verified | ✓ |  |
| TL | Top To Roller | Top Level | Level which exists cause of a single leaf roller | None |  | Verified | ✓ | One Way |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Verdania Gate | Switch Level | None |  | Verified | switch | ✓ |  |
| 2 | Pendra 1 | Lower Level | None |  | Verified | enemy | ✓ |  |
| 3 | Leaf Roller 1 | Level which exists cause of a single leaf roller | None |  | Verified | enemy | ✓ |  |
| 4 | Leaf Roller 2 | Ground Level | None |  | Verified | enemy | ✓ |  |

## Room Images

### Connections

[![Connections for Verdania Left Side Tall Room (Clover_05c)](../00-annotations/verdania/verdania-left-side-tall-room-connections.png)](../00-annotations/verdania/verdania-left-side-tall-room-connections.png)

### Checks

[![Checks for Verdania Left Side Tall Room (Clover_05c)](../00-annotations/verdania/verdania-left-side-tall-room-checks.png)](../00-annotations/verdania/verdania-left-side-tall-room-checks.png)

### Scene

[![Scene for Verdania Left Side Tall Room (Clover_05c)](../00-annotations/verdania/verdania-left-side-tall-room-scene.png)](../00-annotations/verdania/verdania-left-side-tall-room-scene.png)
