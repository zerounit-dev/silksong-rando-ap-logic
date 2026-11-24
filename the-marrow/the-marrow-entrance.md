# The Marrow Entrance (Bone_01)

**Game ID:** Bone_01

**Contributors:** herounit, Pyxl

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | ceiling exit | ✓ |
| S2 | gauntlet arena | ✓ |
| S3 | passage left | ✓ |
| S4 | passage right | ✓ |
| S5 | middle left | ✓ |
| S6 | above gauntlet | ✓ |
| S7 | left of gauntlet | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LL | lower left | passage left | [Bone Bottom Town (Bonetown)](../bone-bottom/bone-bottom-town.md) | LR | none |  | Verified | ✓ |  |
| LR | lower right | passage right | [The Marrow Bell Bench (Bone_01c)](the-marrow-bell-bench.md) | LL | none |  | Verified | ✓ |  |
| UR | upper right | above gauntlet | [The Marrow Bell Bench (Bone_01c)](the-marrow-bell-bench.md) | UL | break wall right |  | Verified | ✓ |  |
| C | ceiling | ceiling exit | [The Marrow Map Shop (Bone_04)](the-marrow-map-shop.md) | F | none |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| DS | door switch | passage left | passage right | activate sherma door switch |  | Verified | ✓ |  |
| DS | door switch | passage right | passage left | activate sherma door switch |  | Verified | ✓ |  |
| UG | upper gauntlet entrance | above gauntlet | gauntlet arena | none (starts gauntlet) |  | Verified | ✓ |  |
| UG | upper gauntlet entrance | gauntlet arena | above gauntlet | defeat gauntlet fight AND ( silk soar  OR cling grip left OR easy scuttlebrace ) |  | Verified | ✓ |  |
| SG | side gauntlet entrance | left of gauntlet | gauntlet arena | defeat gauntlet fight |  | Verified | ✓ |  |
| SG | side gauntlet entrance | gauntlet arena | left of gauntlet | defeat gauntlet fight |  | Verified | ✓ |  |
| LG | lower gauntlet entrance | gauntlet arena | passage right | defeat gauntlet fight |  | Verified | ✓ |  |
| LG | lower gauntlet entrance | passage right | gauntlet arena | defeat gauntlet fight AND ( ledge grab both OR cling grip left OR ( ledge grab left AND ( cling grip right OR easy shaman pogo ) ) OR faydown OR silk soar ) |  | Verified | ✓ |  |
| LP | lowered platform | above gauntlet | ceiling exit | silk soar  OR ( faydown AND ledge grab right ) OR ( faydown AND easy pogo off skull scuttler AND easy shaman pogo ) OR ( faydown AND run AND ( cling grip right OR dash right OR flea brew  OR easy beast pogo) ) OR ( run AND ( clawline right OR sharpdart ) AND ( ledge grab right OR cling grip right ) ) OR ( medium pogo off beastfly AND ( ledge grab right OR cling grip right ) ) OR hard pogo off beastfly OR ( activate lower platform switch other room IN the marrow map shop AND ( ledge grab either OR cling grip either OR faydown OR easy shaman pogo ) ) OR ( hard shaman pogo AND medium scuttlebrace AND CBT pale nails stall x 4 ) |  | Verified | ✓ | The platform lowering switch has the possibility of making this non-monotonic because it *seems* to require ledge grab to hop over the lowered platform.   Can we remove the bottom chunk of the block so you can still walk under it? |
| LP | lowered platform | ceiling exit | above gauntlet | none (falling) |  | Verified | ✓ |  |
| LG1 | ledge grab 1 | passage left | middle left | ledge grab right OR cling grip right OR faydown cloak OR silk soar OR ( CBT pale nails stall x 1 AND Medium shaman pogo ) OR ( easy beast heal stall AND medium plasmium stall x 1 ) |  | Verified | ✓ |  |
| LG1 | ledge grab 1 | middle left | passage left | none (falling) |  | Verified | ✓ |  |
| LG2 | ledge grab 2 | left of gauntlet | middle left | ledge grab left OR cling grip either OR faydown cloak OR silk soar OR easy scuttlebrace |  | Verified | ✓ |  |
| LG2 | ledge grab 2 | middle left | left of gauntlet | none (falling) |  | Verified | ✓ |  |
| LG3 | ledge grab 3 | middle left | above gauntlet | ledge grab left OR cling grip left OR ( ( cling grip right OR easy shaman pogo ) AND easy scuttlebrace ) OR ( cling grip right AND proficient movement ) OR faydown OR silk soar |  | Verified | ✓ |  |
| LG3 | ledge grab 3 | above gauntlet | middle left | none (falling) |  | Verified | ✓ |  |
| V1 | vertical 1 | passage left | left of gauntlet | silk soar |  | Verified | ✓ |  |
| V1 | vertical 1 | left of gauntlet | passage left | none (falling) |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | the marrow shell shard cache 1 | above gauntlet | none |  | Verified | collectible |  |  |
| 2 | volatile flintbeetle 1 | above gauntlet | complete THE volatile flintbeetles wish promised |  | Verified | miniboss | ✓ | stable position |
| 3 | gauntlet fight | gauntlet arena | Combat Requirements |  | Verified | gauntlet | ✓ |  |
| 4 | sherma door switch | passage right | flip switch up |  | Verified | switch |  |  |
| 5 | the marrow rosary cache 1 | passage right | none |  | Verified | collectible |  |  |
| 6 | the marrow rosary cache 2 | passage right | none |  | Verified | collectible |  |  |
| 7 | Skull Scuttler 1 | above gauntlet | None |  | Verified | enemy | ✓ |  |
| 8 | Skull Brute 1 | above gauntlet | None |  | Verified | enemy | ✓ |  |
| 9 | Beastfly 1 | gauntlet arena | None |  | Verified | enemy | ✓ |  |
| 10 | Beastfly 2 | gauntlet arena | None |  | Verified | enemy | ✓ |  |
| 11 | Beastfly 3 | gauntlet arena | None |  | Verified | enemy | ✓ |  |
| 12 | Skull Scuttler 2 | gauntlet arena | None |  | Verified | enemy | ✓ |  |
| 13 | Skull Scuttler 3 | gauntlet arena | None |  | Verified | enemy | ✓ |  |
| 14 | Skull Brute 2 | gauntlet arena | None |  | Verified | enemy | ✓ |  |
| 15 | Beastfly 4 | gauntlet arena | None |  | Verified | enemy | ✓ |  |
| 16 | Beastfly 5 | above gauntlet | None |  | Verified | enemy | ✓ |  |
| 17 | Skull Scuttler 4 | middle left | None |  | Verified | enemy | ✓ |  |
| 18 | Skull Scuttler 5 | middle left | None |  | Verified | enemy | ✓ |  |

## Room Images

### Connections

[![Connections for The Marrow Entrance (Bone_01)](../00-annotations/the-marrow/the-marrow-entrance-connections.png)](../00-annotations/the-marrow/the-marrow-entrance-connections.png)

### Checks

[![Checks for The Marrow Entrance (Bone_01)](../00-annotations/the-marrow/the-marrow-entrance-checks.png)](../00-annotations/the-marrow/the-marrow-entrance-checks.png)

### Scene

[![Scene for The Marrow Entrance (Bone_01)](../00-annotations/the-marrow/the-marrow-entrance-scene.png)](../00-annotations/the-marrow/the-marrow-entrance-scene.png)
