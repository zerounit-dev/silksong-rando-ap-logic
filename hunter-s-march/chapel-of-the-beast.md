# Chapel of the Beast (Ant_19)

**Game ID:** Ant_19

**Contributors:** herounit

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | chapel entrance | ✓ |
| S2 | boss arena | ✓ |
| S3 | crest area | ✓ |
| S4 | right of boss fight | ✓ |
| S5 | zoo | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | chapel entrance | [Hunter's March Chapel Passage (Ant_20)](hunter-s-march-chapel-passage.md) | D | none |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| DS | door switch | chapel entrance | right of boss fight | activate door switch |  | Verified | ✓ |  |
| DS | door switch | right of boss fight | chapel entrance | activate door switch |  | Verified | ✓ |  |
| BR | boss right entrance | right of boss fight | boss arena | none (starts boss fight) |  | Verified | ✓ |  |
| BR | boss right entrance | boss arena | right of boss fight | defeat savage beastfly boss fight |  | Verified | ✓ |  |
| BL | boss left entrance | crest area | boss arena | defeat savage beastfly boss fight |  | Verified | ✓ |  |
| BL | boss left entrance | boss arena | crest area | defeat savage beastfly boss fight |  | Verified | ✓ |  |
| TZ | too zoo | chapel entrance | zoo | drifters AND ( faydown OR ledge grab left OR cling grip left OR easy [ hunter, wanderer, beast, reaper, shaman ] pogo ) |  | Verified | ✓ |  |
| EZ | exit zoo | zoo | right of boss fight | none (falling) |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | door switch | right of boss fight | flip switch down |  | Verified | switch | ✓ |  |
| 2 | crest beast | crest area | none |  | Verified | collectible | ✓ |  |
| 3 | Savage Beastfly Boss Fight | boss arena | Combat Requirements |  | Verified | boss | ✓ | FSM Boolean flags: defeatedBoneFlyerGiant |
| 4 | Caranid 1 | chapel entrance | defeat savage beastfly boss fight |  | Verified | enemy | ✓ | Spawn conditions: defeatedBoneFlyerGiant=true |
| 5 | Vicious Caranid 1 | chapel entrance | defeat savage beastfly boss fight |  | Verified | enemy | ✓ | Spawn conditions: defeatedBoneFlyerGiant=true |
| 6 | Kilik 1 | boss arena | invalid |  | Verified | enemy | ✓ | Boss fight summon - missable |
| 7 | Vicious Caranid 2 | boss arena | invalid |  | Verified | enemy | ✓ | Boss fight summon - missable |
| 8 | Beastfly 1 | boss arena | invalid |  | Verified | enemy | ✓ | Boss fight summon - missable |
| 9 | Beastfly 2 | boss arena | invalid |  | Verified | enemy | ✓ | Boss fight summon - missable |
| 10 | Kilik 2 | boss arena | invalid |  | Verified | enemy | ✓ | Boss fight summon - missable |
| 11 | Kilik 3 | zoo | none |  | Verified | enemy | ✓ |  |
| 12 | Beastfly 3 | zoo | invalid |  | Verified | enemy | ✓ | disabled |
| 13 | Vicious Caranid 3 | zoo | none |  | Verified | enemy | ✓ |  |
| 14 | Beastfly 4 | chapel entrance | invalid |  | Verified | enemy | ✓ | disabled |
| 15 | Vicious Caranid 4 | zoo | invalid |  | Verified | enemy | ✓ | disabled |
| 16 | Vicious Caranid 5 | zoo | invalid |  | Verified | enemy | ✓ | disabled |
| 17 | Vicious Caranid 6 | zoo | invalid |  | Verified | enemy | ✓ | disabled |
| 18 | Beastfly 5 | zoo | none |  | Verified | enemy | ✓ |  |

## Room Images

### Connections

[![Connections for Chapel of the Beast (Ant_19)](../00-annotations/hunter-s-march/chapel-of-the-beast-connections.png)](../00-annotations/hunter-s-march/chapel-of-the-beast-connections.png)

### Checks

[![Checks for Chapel of the Beast (Ant_19)](../00-annotations/hunter-s-march/chapel-of-the-beast-checks.png)](../00-annotations/hunter-s-march/chapel-of-the-beast-checks.png)

### Scene

[![Scene for Chapel of the Beast (Ant_19)](../00-annotations/hunter-s-march/chapel-of-the-beast-scene.png)](../00-annotations/hunter-s-march/chapel-of-the-beast-scene.png)
