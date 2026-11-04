# Grand Bellway (Bellway_City)

**Game ID:** Bellway_City

**Contributors:** samupo, Gallos

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | Base | ✓ |
| S2 | Secret Tunnel | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Secret Tunnel | [Vaults & Bellway Cauldron Entrance (Library_11)](../underworks/vaults-bellway-cauldron-entrance.md) | HL | none |  | Verified | ✓ |  |
| L | left1 | Base | [Grand Bellway Shaft (Song_20)](grand-bellway-shaft.md) | BR | none |  | Verified | ✓ |  |
| BW | door_fastTravelExit | Base | [Bellway Menu](../fast-travel/bellway-menu.md) | GB | unlock Bellway: Grand Bellway |  | Verified | ✓ |  |
| VT | door_tubeEnter | Base | [Ventrica Menu](../fast-travel/ventrica-menu.md) | GB | unlock Ventrica: Grand Bellway |  | Verified | ✓ |  |
| BB | BE Arena | Base | [Bellway Centipede Arena (Bellway_Centipede_Arena)](bellway-centipede-arena.md) | T | defeat Bell Eater IN Bellway Centipede Arena AND ACT 3 |  | Verified | ✓ | And Beastling = false |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| V | Vertical | Secret Tunnel | Base | activate Grand Bellway - lever |  | Verified | ✓ |  |
| V | Vertical | Base | Secret Tunnel | activate Grand Bellway - lever AND (easy scuttlebrace OR cling grip right OR (faydown AND cling grip left) OR silk soar) |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Memory Locket: Choral Chambers | Secret Tunnel | clear Grand Bellway - wall 2 AND clear Grand Bellway - wall 2 |  | Verified | collectible | ✓ |  |
| 2 | Map Purchase: Choral Chambers | Base | spend 70 rosaries |  | Verified | collectible | ✓ | one of two possible locations - hero, 9/26 |
| 3 | Ventrica: Grand Bellway Rosary Lock | Base | spend 80 rosaries |  | Verified | lock | ✓ |  |
| 4 | Ventrica: Grand Bellway | Base | Unlock Ventrica: Grand Bellway Rosary Lock |  | Verified | travel |  |  |
| 5 | Bellway: Grand Bellway Rosary Lock | Base | spend 80 rosaries |  | Verified | lock | ✓ |  |
| 6 | Bellway: Grand Bellway | Base | Unlock Bellway Grand Bellway Rosary Lock |  | Verified | travel |  |  |
| 7 | Beastling Call | Base | defeat Bell Eater IN Bellway Centipede Arena AND ACT 3 |  | Verified | collectible | ✓ |  |
| 8 | Bellway bench | Base | none |  | Verified | bench | ✓ |  |
| 9 | Grand Bellway - lever | Secret Tunnel | attack either |  | Verified | switch | ✓ |  |
| 10 | Grand Bellway - wall 1 | Secret Tunnel | break wall left |  | Verified | blockade | ✓ |  |
| 11 | Grand Bellway - wall 2 | Secret Tunnel | break wall left |  | Verified | blockade | ✓ |  |

## Room Images

### Connections

[![Connections for Grand Bellway (Bellway_City)](../00-annotations/choral-chambers/grand-bellway-connections.png)](../00-annotations/choral-chambers/grand-bellway-connections.png)

### Checks

[![Checks for Grand Bellway (Bellway_City)](../00-annotations/choral-chambers/grand-bellway-checks.png)](../00-annotations/choral-chambers/grand-bellway-checks.png)

### Scene

[![Scene for Grand Bellway (Bellway_City)](../00-annotations/choral-chambers/grand-bellway-scene.png)](../00-annotations/choral-chambers/grand-bellway-scene.png)
