# Verdania Big Room (Clover_02c)

**Game ID:** Clover_02c

**Contributors:** Pyxl

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | Start | ✓ |
| S2 | Main | ✓ |
| S3 | Top Left | ✓ |
| S4 | Verdanir Arena | ✓ |
| S5 | Escalion Encounter | ✓ |
| S6 | Top Right Exit | ✓ |
| S7 | Nuphar Lake | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Top Right Exit | [Verdania Right Side Tall Room (Clover_03)](verdania-right-side-tall-room.md) | LL | None |  | Verified | ✓ |  |
| UL | left2 | Top Left | [Verdania Left Side Tall Room (Clover_05c)](verdania-left-side-tall-room.md) | LR | None |  | Verified | ✓ |  |
| LL | left1 | Start | [Verdania Entrance (Clover_01b)](verdania-entrance.md) | R | None |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| SM | Start Main | Start | Main | Easy Beast Crest Pogo OR ( Silk Soar AND ( Ledge Grab Right OR Cling Grip Right OR Dash Right OR Faydown Cloak OR Drifters Cloak OR Sharpdart OR Clawline Right OR Easy air bind Stall OR   Easy Hunter Crest Pogo OR Easy Reaper Crest Pogo OR Medium Witch Crest Pogo OR Easy Architect Crest Pogo OR Hard Shaman Crest Pogo OR Easy Naked Crest Pogo ) ) OR Clawline Right OR Drifters Cloak OR Faydown Cloak OR ( Dash Right AND ( Ledge Grab Right OR Cling Grip RIght ) ) |  | Verified | ✓ | I |
| SM | Start Main | Main | Start | None |  | Verified | ✓ | Hate |
| STL | Start Top Left | Start | Top Left | prereq Verdania Big Room Shortcut AND ( Silk Soar OR  ( Cling Grip left AND ( Faydown Cloak OR Drifters Cloak OR Clawline Left OR Dash Left ) ) ) |  | Verified | ✓ | This |
| STL | Start Top Left | Top Left | Start | prereq Verdania Big Room Shortcut |  | Verified | ✓ | Entire |
| TLV | Top Left Verdanir Arena | Top Left | Verdanir Arena | Silk Soar OR Cling Grip Right OR Scuttlebrace OR ( Faydown Cloak AND Cling Grip Right ) |  | Verified | ✓ | Room |
| TLV | Top Left Verdanir Arena | Verdanir Arena | Top Left | None |  | Verified | ✓ | And |
| MVA | Main Verdanir Arena | Main | Verdanir Arena | Faydown Cloak |  | Verified | ✓ | All |
| MVA | Main Verdanir Arena | Verdanir Arena | Main | None |  | Verified | ✓ | Its |
| MEE | Naub Escalion Encounter | Main | Escalion Encounter | Faydown Cloak |  | Verified | ✓ | Enemys |
| MEE | Naub Escalion Encounter | Escalion Encounter | Main | None |  | Verified | ✓ |  |
| MNL | Escalion encounter Nuphar Lake | Escalion Encounter | Nuphar Lake | ( Faydown Cloak AND Proficient Movement ) OR Clawline Right OR Drifters Cloak OR Swim OR Sharpdart OR Dash RIght OR Sprint Right |  | Verified | ✓ |  |
| MNL | Escalion encounter Nuphar Lake | Nuphar Lake | Escalion Encounter | ( Faydown Cloak AND Proficient Movement ) OR Clawline left OR Drifters Cloak OR Swim OR Sharpdart OR Dash left OR Sprint left |  | Verified | ✓ |  |
| NLR | Nuphar Lake Right | Nuphar Lake | Top Right Exit | Clawline both OR ( Ledge Grab Right AND ( Drifters Cloak OR ( Faydown Cloak AND Proficient movement ) OR ( Swim AND SIlk Soar AND SPrint Right AND Proficient Movement ) ) ) |  | Verified | ✓ |  |
| NLR | Nuphar Lake Right | Top Right Exit | Nuphar Lake | None |  | Verified | ✓ |  |
| VAE | Verdanir Arena Escalion | Verdanir Arena | Escalion Encounter | Clawline RIght OR Faydown Cloak OR Sprint Right OR Sharpdart OR Drifters Cloak  OR ( medium Beast Crest Pogo AND Ledge grab right ) |  | Verified | ✓ |  |
| VAE | Verdanir Arena Escalion | Escalion Encounter | Verdanir Arena | Clawline left OR Faydown Cloak OR Sprint left OR Sharpdart OR Drifters Cloak  OR ( medium Beast Crest Pogo AND Ledge grab left ) |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Verdania Essence 1 | Main | Faydown Cloak AND Ledge Grab Right |  | Verified | resource | ✓ |  |
| 2 | Verdania Big Room Shortcut | Top Left | None |  | Verified | blockade | ✓ |  |
| 3 | Leaf Glider 1 | Start | sharpdart OR Clawline Right |  | Verified | enemy | ✓ |  |
| 4 | Leaf Glider 2 | Start | sharpdart OR Clawline Right |  | Verified | enemy | ✓ |  |
| 5 | Leaf Glider 3 | Start | sharpdart OR Clawline Right |  | Verified | enemy | ✓ |  |
| 6 | Leaf Roller 1 | Main | None |  | Verified | enemy | ✓ |  |
| 7 | Leaf Glider 4 | Main | ( Swim OR Drifters Cloak OR Faydown Cloak OR Easy Beast Crest Pogo OR ( Sprint Right AND Dash Right ) ) AND ( Clawline Right OR Sharpdart ) |  | Verified | enemy | ✓ |  |
| 8 | Leaf Roller 2 | Nuphar Lake | Clawline both OR ( Ledge Grab Right AND ( Drifters Cloak OR ( Faydown Cloak AND Proficient movement ) OR ( Swim AND SIlk Soar AND SPrint Right AND Proficient Movement ) ) ) |  | Verified | enemy | ✓ |  |
| 9 | Nuphar 1 | Nuphar Lake | None |  | Verified | enemy | ✓ |  |
| 10 | Leaf Glider 5 | Nuphar Lake | sharpdart OR Clawline either |  | Verified | enemy | ✓ |  |
| 11 | Leaf Glider 6 | Nuphar Lake | sharpdart OR Clawline either |  | Verified | enemy | ✓ |  |
| 12 | Leaf Glider 7 | Nuphar Lake | sharpdart OR Clawline either |  | Verified | enemy | ✓ |  |
| 13 | Escalion 1 | Escalion Encounter | None |  | Verified | enemy | ✓ |  |
| 14 | Leaf Roller 3 | Escalion Encounter | None |  | Verified | enemy | ✓ |  |
| 15 | Verdanir 1 | Verdanir Arena | None |  | Verified | enemy | ✓ |  |
| 16 | Verdanir 2 | Verdanir Arena | None |  | Verified | enemy | ✓ |  |

## Room Images

### Connections

[![Connections for Verdania Big Room (Clover_02c)](../00-annotations/verdania/verdania-big-room-connections.png)](../00-annotations/verdania/verdania-big-room-connections.png)

### Checks

[![Checks for Verdania Big Room (Clover_02c)](../00-annotations/verdania/verdania-big-room-checks.png)](../00-annotations/verdania/verdania-big-room-checks.png)

### Scene

[![Scene for Verdania Big Room (Clover_02c)](../00-annotations/verdania/verdania-big-room-scene.png)](../00-annotations/verdania/verdania-big-room-scene.png)
