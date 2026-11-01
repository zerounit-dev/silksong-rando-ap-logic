# Far Fields Deep Entrance (Bone_East_24)

**Game ID:** Bone_East_24

**Contributors:** herounit

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | left exit area | ✓ |
| S2 | bottom exit area | ✓ |
| S3 | right exit area | ✓ |
| S4 | lower left alcove | ✓ |
| S5 | middle left platform | ✓ |
| S6 | plains | ✓ |
| S7 | lower right area | ✓ |
| S8 | lower right alcove | ✓ |
| S9 | upper right alcove | ✓ |
| S10 | left of right exit gate | ✓ |
| S11 | plains upper right platform | ✓ |
| S12 | plains upper left platform | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F | bot1 | bottom exit area | [Far Fields Deep Lower West (Bone_East_18)](far-fields-deep-lower-west.md) | C | none |  | Verified | ✓ |  |
| L | left1 | left exit area | [Far Fields Upper Shaft (Bone_East_11)](far-fields-upper-shaft.md) | UR | none |  | Verified | ✓ |  |
| R | right1 | right exit area | [Far Fields Deep Fort Bench (Bone_East_27)](far-fields-deep-fort-bench.md) | L | none |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | vertical 1 | left exit area | middle left platform | none (falling) |  | Verified | ✓ |  |
| V1 | vertical 1 | middle left platform | left exit area | silk soar OR faydown cloak OR (ledge grab AND proficient movement AND (easy shaman pogo OR (easy flea brew stall AND clawline))) |  | Verified | ✓ |  |
| V2 | vertical 2 | middle left platform | lower left alcove | run OR dash OR easy beast pogo OR drifter's cloak OR faydown cloak OR clawline OR sharpdart OR scuttlebrace |  | Verified | ✓ |  |
| V2 | vertical 2 | lower left alcove | middle left platform | (faydown cloak AND (flea brew OR ledge grab right OR easy voltvessels stall OR easy architect needle strike OR easy beast pogo OR easy beast needle strike OR architect slash right))  OR ( cling grip right AND ( run right OR dash right OR drifter's cloak OR faydown cloak OR clawline right OR sharpdart OR flea brew OR easy beast needle strike OR easy architect needle strike OR architect slash right)) |  | Verified | ✓ |  |
| G1 | gap 1 | middle left platform | plains | run OR dash right  OR drifter's cloak  OR faydown cloak  OR clawline right  OR sharpdart  OR easy scuttlebrace  OR easy [beast, architect, hunter] pogo OR easy naked pogo OR easy [beast, architect, witch] needle strike OR flea brew  OR (proficient movement AND (cling grip both OR (cling grip left AND (easy shaman pogo OR easy wanderer needle strike)))) |  | Verified | ✓ |  |
| G1 | gap 1 | plains | middle left platform | run left  OR dash left  OR drifter's cloak  OR faydown cloak  OR clawline left  OR sharpdart  OR (ledge grab left AND (dash left OR easy architect needle strike))  OR (proficient movement AND cling grip both AND (easy architect needle strike OR (flea brew AND easy wanderer needle strike))) OR (proficient movement AND flea brew AND (easy architect needle strike OR architect slash left)) |  | Verified | ✓ |  |
| V3 | vertical 3 | plains | lower right area | none (falling) |  | Verified | ✓ |  |
| V3 | vertical 3 | lower right area | plains | silk soar  OR faydown OR ( ledge grab left AND ( run left OR clawline left ) ) |  | Verified | ✓ |  |
| V4 | vertical 4 | lower right area | lower right alcove | break blast rock left AND ( spike pogo OR cling grip either OR faydown cloak OR scuttlebrace OR easy hazard respawn ) |  | Verified | ✓ | can just break it, reset from thorns and jump down again - won't work with 1 hp though :) |
| V4 | vertical 4 | lower right alcove | lower right area | cling grip either OR faydown cloak OR scuttlebrace |  | Verified | ✓ |  |
| V5 | vertical 5 | lower right area | bottom exit area | none (falling) |  | Verified | ✓ |  |
| V5 | vertical 5 | bottom exit area | lower right area | silk soar OR cling grip OR scuttlebrace ( faydown cloak AND ledge grab ) |  | Verified | ✓ |  |
| DS | door switch | right exit area | left of right exit gate | activate right exit door switch |  | Verified | ✓ |  |
| DS | door switch | left of right exit gate | right exit area | activate right exit door switch |  | Verified | ✓ |  |
| V6 | vertical 6 | lower right area | left of right exit gate | silk soar OR faydown cloak OR ( ledge grab AND ( run OR drifter's cloak OR clawline ) ) |  | Verified | ✓ |  |
| V6 | vertical 6 | left of right exit gate | lower right area | none (falling) |  | Verified | ✓ |  |
| S1 | silk soar 1 | plains | plains upper left platform | silk soar OR ( faydown cloak AND clawline ) |  | Verified | ✓ | can hop up from the ground here or cross over from the plains upper right platform - requirements are the same |
| S1 | silk soar 1 | plains upper left platform | plains | none (falling) |  | Verified | ✓ |  |
| S2 | silk soar 2 | plains | plains upper right platform | silk soar |  | Verified | ✓ |  |
| S2 | silk soar 2 | plains upper right platform | plains | none (falling) |  | Verified | ✓ |  |
| S3 | silk soar 3 | lower right area | upper right alcove | silk soar |  | Verified | ✓ |  |
| S3 | silk soar 3 | upper right alcove | lower right area | none (falling) |  | Verified | ✓ |  |
| G2 | gap 2 | left of right exit gate | plains upper right platform | faydown cloak AND ( run left OR dash left OR drifter's cloak OR clawline left OR sharpdart OR easy scuttlebrace ) |  | Verified | ✓ |  |
| G2 | gap 2 | plains upper right platform | left of right exit gate | run right OR dash right OR drifter's cloak OR faydown cloak OR clawline right OR scuttlebrace OR sharpdart |  | Verified | ✓ |  |
| V7 | vertical 7 | plains upper right platform | upper right alcove | (cling grip right AND faydown cloak AND (ledge grab right OR run OR dash right OR drifter's cloak OR sharpdart OR easy scuttlebrace ))  OR (proficient movement AND cling grip both AND ((clawline both AND clawline x 3) OR faydown cloak OR (clawline AND easy beast pogo) OR (run AND dash right) )) |  | Verified | ✓ |  |
| V7 | vertical 7 | upper right alcove | plains upper right platform | none (falling) |  | Verified | ✓ |  |
| G3 | gap 3 | plains upper left platform | plains upper right platform | faydown cloak AND clawline right |  | Verified | ✓ |  |
| G3 | gap 3 | plains upper right platform | plains upper left platform | faydown cloak AND clawline left |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | right exit door switch | right exit area | flip switch down |  | Verified | switch | ✓ |  |
| 2 | Far Fields - Deep Entrance Skarr Gate Watch Spears | lower left alcove | none |  | Verified | collectible | ✓ | formely AP Minor Cache - Shell Shard Cache: Far Fields #4 |
| 3 | Far Fields - Deep Entrance Skarr Sentinel's Trap Shards | lower left alcove | none |  | Verified | collectible | ✓ | formerly AP Minor Cache - Shell Shard Cache: Far Fields #5 |
| 4 | Far Fields - Deep Entrance -Cage Materials | plains upper left platform | none |  | Verified | collectible | ✓ | formerly AP Minor Cache - Shell Shard Cache: Far Fields #6 |
| 5 | Far Fields - Deep Entrance - Curveclaw Reserve | lower right alcove | none |  | Verified | collectible | ✓ | formerly AP Minor Cache - Shell Shard Cache: Far Fields #7 |
| 6 | Far Fields - Deep Entrance -Queen's Gate Sentry Funds | upper right alcove | none |  | Verified | collectible | ✓ | formerly AP Minor Cache - Rosary Cache: Far Fields #20 |
| 7 | Far Fields - Deep Entrance -Bounty Rosary Stash - "To be paid in full to the Hunter who fells Gurr" | upper right alcove | none |  | Verified | collectible | ✓ | formerly AP Minor Cache - Rosary Cache: Far Fields #21 |
| 8 | Far Fields - Deep Entrance -Last Beads - "Stand strong my child, forgive the burden I leave on you" | upper right alcove | none |  | Verified | collectible | ✓ | formerly AP Minor Cache - Rosary Cache: Far Fields #22 |
| 9 | Far Fields - Deep Entrance -Queen's Pearls of Hero | upper right alcove | none |  | Verified | collectible | ✓ | formerly far fields pale rosary necklace |
| 10 | Hardbone Elder 1ffde | plains | none |  | Verified | enemy | ✓ | shell shards |
| 11 | Hardbone Hopper 1ffde | plains | none |  | Verified | enemy | ✓ | shell shards |
| 12 | Hardbone Hopper 2ffde | plains | none |  | Verified | enemy | ✓ | shell shards |
| 13 | Hardbone Elder 2ffde | plains | none |  | Verified | enemy | ✓ | shell shards |
| 14 | Skarr Scout 1ffde | plains | none |  | Verified | enemy | ✓ | rosaries |
| 15 | Skarr Scout 2ffde | plains | none |  | Verified | enemy | ✓ | rosaries |
| 16 | Skarr Stalker 1ffde | upper right alcove | none |  | Verified | enemy | ✓ | rosaries |
| 17 | Fertid 1ffde | lower right area | none |  | Verified | enemy | ✓ | shell shards |
| 18 | Flapping Fertid 1ffde | plains upper right platform | none |  | Verified | enemy | ✓ | shell shards |
| 19 | Flapping Fertid 2ffde | plains upper right platform | none |  | Verified | enemy | ✓ | shell shards |

## Room Images

### Connections

[![Connections for Far Fields Deep Entrance (Bone_East_24)](../00-annotations/far-fields/far-fields-deep-entrance-connections.png)](../00-annotations/far-fields/far-fields-deep-entrance-connections.png)

### Checks

[![Checks for Far Fields Deep Entrance (Bone_East_24)](../00-annotations/far-fields/far-fields-deep-entrance-checks.png)](../00-annotations/far-fields/far-fields-deep-entrance-checks.png)

### Scene

[![Scene for Far Fields Deep Entrance (Bone_East_24)](../00-annotations/far-fields/far-fields-deep-entrance-scene.png)](../00-annotations/far-fields/far-fields-deep-entrance-scene.png)
