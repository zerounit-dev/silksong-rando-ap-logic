# Coral Tower Memory (Memory_Coral_Tower)

**Game ID:** Memory_Coral_Tower

**Contributors:** Pyxl

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | Khan |  |
| S2 | Bottom |  |
| S3 | Gauntlets |  |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| D | door_wakeInMemory | Bottom | [Coral Tower (Coral_Tower_01)](coral-tower.md) | DR | None |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BG | Epic Transition | Bottom | Gauntlets | Silk Soar |  | Verified |  |  |
| BG | Epic Transition | Gauntlets | Bottom | None |  | Verified |  |  |
| KH | Khan | Gauntlets | Khan | Silk Soar |  | Verified |  | One way |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Encrusted Heart | Khan | Prereq crust king khann boss fight |  | Verified | collectible |  |  |
| 2 | Crust King Khann Boss Fight | Khan | combat requirements |  | Verified | boss | ✓ | FSM Boolean flags: encounteredCoralKing |
| 3 | Karaka 1 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 4 | Karaka 2 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 5 | Yago 1 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 6 | Corrcrust Karaka 1 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 7 | Driznarga 1 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 8 | Driznarga 2 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 9 | Karaka 3 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 10 | Alita 1 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 11 | Yumama 1 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 12 | Yuma 1 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 13 | Yuma 2 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 14 | Yuma 3 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 15 | Yuma 4 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 16 | Yuma 5 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 17 | Kakri 1 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 18 | Yago 2 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 19 | Karaka 4 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 20 | Alita 2 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 21 | Spinebeak Kai 1 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 22 | Spinebeak Kai 2 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 23 | Steelspine Kai 1 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 24 | Kai 1 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 25 | Kai 2 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 26 | Driznarga 3 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 27 | Driznarga 4 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 28 | Karaka 5 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 29 | Karaka 6 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 30 | Conchfly 1 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 31 | Conchfly 2 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 32 | Conchfly 3 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 33 | Yago 3 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 34 | Karaka 7 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 35 | Karaka 8 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 36 | Yago 4 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 37 | Kai 3 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 38 | Kai 4 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 39 | Kai 5 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 40 | Kai 6 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 41 | Kai 7 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 42 | Kakri 2 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 43 | Karaka 9 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 44 | Kakri 3 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 45 | Alita 3 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 46 | Alita 4 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 47 | Karaka 10 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 48 | Karaka 11 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 49 | Karaka 12 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 50 | Kakri 4 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 51 | Yumama 2 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 52 | Yuma 6 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 53 | Yuma 7 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 54 | Yuma 8 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 55 | Yuma 9 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 56 | Yuma 10 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 57 | Driznarga 5 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 58 | Driznarga 6 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 59 | Yago 5 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 60 | Kakri 5 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 61 | Karak Gor 1 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 62 | Karak Gor 2 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 63 | Karak Gor 3 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 64 | Yago 6 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 65 | Conchfly 4 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 66 | Conchfly 5 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 67 | Kai 8 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 68 | Kai 9 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 69 | Kai 10 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 70 | Steelspine Kai 2 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 71 | Steelspine Kai 3 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 72 | Alita 5 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 73 | Karaka 13 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 74 | Karaka 14 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 75 | Alita 6 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 76 | Alita 7 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 77 | Karaka 15 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 78 | Yumama 3 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 79 | Yuma 11 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 80 | Yuma 12 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 81 | Yuma 13 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 82 | Yuma 14 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 83 | Yuma 15 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 84 | Yumama 4 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 85 | Yuma 16 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 86 | Yuma 17 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 87 | Yuma 18 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 88 | Yuma 19 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 89 | Yuma 20 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 90 | Yago 7 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 91 | Kakri 6 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 92 | Conchfly 6 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 93 | Conchfly 7 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 94 | Corrcrust Karaka 2 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 95 | Yago 8 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 96 | Kai 11 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 97 | Kai 12 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 98 | Kai 13 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 99 | Spinebeak Kai 3 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 100 | Spinebeak Kai 4 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 101 | Kai 14 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 102 | Kai 15 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 103 | Kai 16 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 104 | Kai 17 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 105 | Steelspine Kai 4 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 106 | Karaka 16 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 107 | Karaka 17 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 108 | Yumama 5 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 109 | Yuma 21 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 110 | Yuma 22 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 111 | Yuma 23 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 112 | Yuma 24 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 113 | Yuma 25 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 114 | Alita 8 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 115 | Karak Gor 4 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 116 | Karak Gor 5 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 117 | Corrcrust Karaka 3 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled; no activation found. |
| 118 | Karaka 18 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 119 | Kakri 7 | Gauntlets | Silk Soar |  | Verified | enemy | ✓ |  |
| 120 | Yuma 26 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 121 | Yuma 27 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 122 | Yuma 28 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 123 | Yuma 29 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 124 | Yuma 30 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 125 | Yuma 31 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 126 | Yuma 32 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 127 | Yuma 33 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 128 | Yuma 34 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 129 | Coral Goombas 1 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 130 | Coral Goombas 2 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 131 | Yuma 35 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 132 | Yuma 36 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 133 | Yuma 37 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 134 | Yuma 38 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 135 | Yuma 39 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 136 | Yuma 40 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 137 | Coral Goombas 3 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |
| 138 | Coral Goombas 4 | Gauntlets | Invalid |  | Verified | enemy | ✓ | Disabled ancestor; no activation found. |

## Notes

Group in with sands of karak
dont even ask me about the enemys i just uploaded the scene dump and got given the entiriety of china to verify

## Room Images

### Connections

[![Connections for Coral Tower Memory (Memory_Coral_Tower)](../00-annotations/sands-of-karak/coral-tower-memory-connections.png)](../00-annotations/sands-of-karak/coral-tower-memory-connections.png)

### Checks

[![Checks for Coral Tower Memory (Memory_Coral_Tower)](../00-annotations/sands-of-karak/coral-tower-memory-checks.png)](../00-annotations/sands-of-karak/coral-tower-memory-checks.png)

### Scene

[![Scene for Coral Tower Memory (Memory_Coral_Tower)](../00-annotations/sands-of-karak/coral-tower-memory-scene.png)](../00-annotations/sands-of-karak/coral-tower-memory-scene.png)
