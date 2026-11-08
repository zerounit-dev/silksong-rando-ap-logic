# Hunter's March Map Shop (Ant_04_mid)

**Game ID:** Ant_04_mid

**Contributors:** herounit

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | left of gauntlet | ✓ |
| S2 | gauntlet | ✓ |
| S3 | right of gauntlet | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | left of gauntlet | [Hunter's March Early Pathway West (Ant_04_left)](hunter-s-march-early-pathway-west.md) | R | none |  | Verified | ✓ |  |
| R | right1 | right of gauntlet | [Hunter's March Early Pathway East (Ant_04)](hunter-s-march-early-pathway-east.md) | L | none |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LG | left gauntlet entrance | left of gauntlet | gauntlet | none (starts gauntlet) |  | Verified | ✓ |  |
| LG | left gauntlet entrance | gauntlet | left of gauntlet | defeat gauntlet fight |  | Verified | ✓ |  |
| RG | right of gauntlet entrance | right of gauntlet | gauntlet | none (starts gauntlet) |  | Verified | ✓ |  |
| RG | right of gauntlet entrance | gauntlet | right of gauntlet | defeat gauntlet fight |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | gauntlet fight | gauntlet | Combat Requirements |  | Verified | gauntlet | ✓ |  |
| 2 | map purchase hunter's march | gauntlet | defeat gauntlet fight |  | Verified | collectible | ✓ |  |
| 3 | Skarr Stalker 1 | gauntlet | Normal World Spawn |  | Verified | enemy | ✓ |  |
| 4 | Skarrwing 1 | gauntlet | Normal World Spawn |  | Verified | enemy | ✓ |  |
| 5 | Skarrwing 2 | gauntlet | Normal World Spawn |  | Verified | enemy | ✓ |  |
| 6 | Spear Skarr 1 | gauntlet | Normal World Spawn |  | Verified | enemy | ✓ |  |
| 7 | Skarr Scout 1 | gauntlet | Normal World Spawn |  | Verified | enemy | ✓ |  |
| 8 | Skarr Scout 2 | gauntlet | Normal World Spawn |  | Verified | enemy | ✓ |  |
| 9 | Skarr Scout 3 | gauntlet | Normal World Spawn |  | Verified | enemy | ✓ |  |
| 10 | Skarr Stalker 2 | gauntlet | Normal World Spawn |  | Verified | enemy | ✓ |  |
| 11 | Spear Skarr 2 | gauntlet | Normal World Spawn |  | Verified | enemy | ✓ |  |
| 12 | Skarr Stalker 3 | gauntlet | Normal World Spawn |  | Verified | enemy | ✓ | FSM Boolean flags: ant04_enemiesReturn, visitedCitadel |
| 13 | Spear Skarr 3 | gauntlet | Normal World Spawn |  | Verified | enemy | ✓ | FSM Boolean flags: ant04_enemiesReturn, visitedCitadel |
| 14 | Skarr Scout 4 | gauntlet | Normal World Spawn |  | Verified | enemy | ✓ | FSM Boolean flags: ant04_enemiesReturn, visitedCitadel |
| 15 | Skarr Scout 5 | gauntlet | Normal World Spawn |  | Verified | enemy | ✓ | FSM Boolean flags: ant04_enemiesReturn, visitedCitadel |
| 16 | Skarr Stalker 4 | gauntlet | Black Thread World Spawn |  | Verified | enemy | ✓ |  |
| 17 | Skarr Scout 6 | gauntlet | Black Thread World Spawn |  | Verified | enemy | ✓ |  |
| 18 | Spear Skarr 4 | gauntlet | Black Thread World Spawn |  | Verified | enemy | ✓ |  |
| 19 | Spear Skarr 5 | gauntlet | Black Thread World Spawn |  | Verified | enemy | ✓ |  |
| 20 | Skarr Stalker 5 | gauntlet | Black Thread World Spawn |  | Verified | enemy | ✓ |  |
| 21 | Spear Skarr 6 | gauntlet | Black Thread World Spawn |  | Verified | enemy | ✓ |  |

## Room Images

### Connections

[![Connections for Hunter's March Map Shop (Ant_04_mid)](../00-annotations/hunter-s-march/hunter-s-march-map-shop-connections.png)](../00-annotations/hunter-s-march/hunter-s-march-map-shop-connections.png)

### Checks

[![Checks for Hunter's March Map Shop (Ant_04_mid)](../00-annotations/hunter-s-march/hunter-s-march-map-shop-checks.png)](../00-annotations/hunter-s-march/hunter-s-march-map-shop-checks.png)

### Scene

[![Scene for Hunter's March Map Shop (Ant_04_mid)](../00-annotations/hunter-s-march/hunter-s-march-map-shop-scene.png)](../00-annotations/hunter-s-march/hunter-s-march-map-shop-scene.png)
