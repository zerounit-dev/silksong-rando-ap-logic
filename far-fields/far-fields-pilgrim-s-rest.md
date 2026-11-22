# Far Fields Pilgrim's Rest (Bone_East_10)

**Game ID:** Bone_East_10

**Contributors:** herounit

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | main floor | ✓ |
| S2 | upper left exit | ✓ |
| S3 | upper right exit | ✓ |
| S4 | lower right exit | ✓ |
| S5 | middle upper platform | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | left1 | upper left exit | [Far Fields Upper Shaft (Bone_East_11)](far-fields-upper-shaft.md) | LR | none |  | Verified | ✓ |  |
| LL | left2 | main floor | [Far Fields Wind Shaft (Bone_East_07)](far-fields-wind-shaft.md) | R1 | none |  | Verified | ✓ |  |
| D | door1 | main floor | [Far Fields Pilgrim's Rest Shop (Bone_East_10_Room)](far-fields-pilgrim-s-rest-shop.md) | R | none (rosary gated) |  | Verified | ✓ | 10 rosaries (vanilla price) toll, repeated everytime unless inner door broken |
| UR | right1 | upper right exit | [Far Fields Pilgrim's Rest Deep Passage (Bone_East_18c)](far-fields-pilgrim-s-rest-deep-passage.md) | L | clear blast rock exit block IN hunters march pilgrims rest deep passage |  | Verified | ✓ |  |
| LR | right2 | lower right exit | [Far Fields Pilgrim's Rest Church (Bone_East_10_Church)](far-fields-pilgrim-s-rest-church.md) | L | activate Far Fields - Pilgrim's Rest Church - Door Switch IN far fields pilgrims rest church |  | Verified | ✓ | safe inbound without gate opened, you are spawned in front of the gate when entering |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | vertical 1 | main floor | upper left exit | silk soar OR faydown cloak |  | Verified | ✓ | platform can be dropped to make it only ledge grab after middle platform access is granted |
| V1 | vertical 1 | upper left exit | main floor | none (falling) |  | Verified | ✓ |  |
| G1 | gap 1 | middle upper platform | upper left exit | run left  OR ledge grab left  OR clawline left  OR faydown cloak  OR drifter's cloak   OR sharpdart  OR easy hunter pogo  OR easy beast pogo  OR (architect slash left AND easy architect pogo) |  | Verified | ✓ | based on after platform falls |
| V2 | vertical 2 | main floor | lower right exit | ledge grab right  OR faydown cloak  OR silk soar  OR scuttlebrace  OR easy shaman pogo  OR easy beast needle strike  OR cling grip right  OR (easy beast pogo AND easy [flea brew, thread storm, rune rage, air bind, cross stitch] stall ) OR (elite ball knowledge AND dash right AND (easy beast pogo OR (easy [flea brew, thread storm, rune rage, air bind, cross stitch] stall))) |  | Verified | ✓ |  |
| V2 | vertical 2 | lower right exit | main floor | none (falling) |  | Verified | ✓ |  |
| V3 | vertical 3 | main floor | upper right exit | ledge grab right OR faydown cloak OR silk soar OR scuttlebrace OR cling grip right |  | Verified |  |  |
| V3 | vertical 3 | upper right exit | main floor | none (falling) |  | Verified |  |  |
| G2 | gap 2 | upper right exit | middle upper platform | run left  OR cling grip both OR dash left  OR drifter's cloak  OR faydown cloak  OR silk soar  OR clawline left  OR sharpdart OR scuttlebrace  OR (proficient movement AND (architect slash left OR cling grip right OR easy wanderer needle strike))  OR easy beast pogo  OR easy [beast, architect] needle strike |  | Verified | ✓ |  |
| G2 | gap 2 | middle upper platform | upper right exit | none (jump) |  | Verified | ✓ |  |
| V4 | vertical 4 | main floor | middle upper platform | silk soar |  | Verified | ✓ |  |
| V4 | vertical 4 | middle upper platform | main floor | none (falling) |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | pilgrim's rest board | main floor | none (interact) |  | Verified | lore | ✓ |  |
| 2 | Snitchfly 1 | main floor | Black Thread World Spawn |  | Verified | enemy | ✓ |  |
| 3 | Snitchfly 2 | main floor | Black Thread World Spawn |  | Verified | enemy | ✓ |  |
| 4 | Pilgrim Hulk 1 | main floor | Normal World Spawn |  | Verified | enemy | ✓ |  |

## Room Images

### Connections

[![Connections for Far Fields Pilgrim's Rest (Bone_East_10)](../00-annotations/far-fields/far-fields-pilgrim-s-rest-connections.png)](../00-annotations/far-fields/far-fields-pilgrim-s-rest-connections.png)

### Checks

[![Checks for Far Fields Pilgrim's Rest (Bone_East_10)](../00-annotations/far-fields/far-fields-pilgrim-s-rest-checks.png)](../00-annotations/far-fields/far-fields-pilgrim-s-rest-checks.png)

### Scene

[![Scene for Far Fields Pilgrim's Rest (Bone_East_10)](../00-annotations/far-fields/far-fields-pilgrim-s-rest-scene.png)](../00-annotations/far-fields/far-fields-pilgrim-s-rest-scene.png)
