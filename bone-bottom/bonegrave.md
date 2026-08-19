# Bonegrave (Bonegrave)

**Game ID:** Bonegrave

**Contributors:** herounit

## Subrooms

- upper left exit
- upper right exit
- graveyard

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UR | upper right | upper right exit | [Bone Bottom Town (Bonetown)](bone-bottom-town.md) | UL | none |  |  |  |
| LR | lower right | graveyard | [Bone Bottom Town (Bonetown)](bone-bottom-town.md) | LL | none |  |  |  |
| C | ceiling | upper left exit | [Wormways Lower East (Crawl_07)](../wormways/wormways-lower-east.md) | F | silk soar OR cling grip |  |  |  |
| CD | chapel door | graveyard | [Chapel of the Wanderer (Chapel_Wanderer)](chapel-of-the-wanderer.md) | CD | no wanderer's crest OR wanderer's door override |  |  | "wanderer's door override" is meant to cover any situation that would require the door to stay open, such as rosary cache rando |
| LL | lower left | graveyard | [Bonegrave Passage](bonegrave-passage.md) | R | steel soul |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CL | climb | graveyard | upper right exit | cling grip OR silk soar |  |  |  |
| CL | climb | upper right exit | graveyard | none (falling) |  |  |  |
| BW | breakable wall | upper left exit | upper right exit | none (break wall from this side) |  |  |  |
| BW | breakable wall | upper right exit | upper left exit | wall broken from other side |  |  |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| boneyard mossberry | graveyard | none |  |  | Included | can be gotten with only jump -tested |
| rosary cache bone bottom 6 | upper right exit | none |  |  | Included |  |
| rosary cache bone bottom 7 | upper right exit | none |  |  | Included |  |
| rosaries on grave | graveyard | none |  |  | Not included | NOT CURRENTLY RANDOMIZED |
