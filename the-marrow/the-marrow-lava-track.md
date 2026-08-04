# The Marrow Lava Track (Bone_16)

## Subrooms

- left track
- right track
- left maze
- right maze

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| L | left | left track | [The Marrow Lava Intro (Bone_02)](the-marrow-lava-intro.md) | R | none |  |
| R | right | right track | [The Marrow Lava Docks (Bone_09)](the-marrow-lava-docks.md) | L | none |  |
| C | ceiling | left maze | [The Marrow Skull Tyrant Arena (Bone_15)](the-marrow-skull-tyrant-arena.md) | F | none |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | Notes |
| --- | --- | --- | --- | --- | --- |
| LT | lava track | right track | left track | activate track |  |
| LT | lava track | left track | right track | activate track |  |
| CR | climb right | right track | right maze | cling grip OR silk soar |  |
| CR | climb right | right maze | right track | none (falling) |  |
| CL | climb left | right maze | left maze | cling grip OR faydown cloak |  |
| CL | climb left | left maze | right maze | none (falling) |  |

## Check Locations

| Check | Subroom | Requirements | Notes |
| --- | --- | --- | --- |
| activate track | right track | none | Not included in Archipelago world |
| rosary cache the marrow 11 |  | none | one of these is in right maze; TODO; Not included in Archipelago world |
| rosary cache the marrow 12 |  | none | one of these is in right maze; TODO; Not included in Archipelago world |
| rosary cache the marrow 13 |  | none | one of these is in right maze; TODO; Not included in Archipelago world |
