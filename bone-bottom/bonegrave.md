# Bonegrave

## Subrooms

- upper left exit
- upper right exit
- graveyard

## Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| UR | upper right | upper right exit | [bone bottom](./bone-bottom.md) -UL | none |
| LR | lower right | graveyard | [bone bottom](./bone-bottom.md) -LL | none |
| C | ceiling | upper left exit | [wormways lower east](../wormways/wormways-lower-east.md) -F | none |
| GD | grave door | graveyard | TODO | no wanderer's crest |
| LL | lower left | graveyard | [bonegrave passage](./bonegrave-passage.md) -R | TODO (steel soul only?) |

## Subroom Connections

| alias | name | source | destination | requirements |
| --- | --- | --- | --- | --- |
| CL | climb | graveyard | upper right exit | cling grip OR silk soar |
| CL | climb | upper right exit | graveyard | none (falling) |
| BW | breakable wall | upper left exit | upper right exit | none (break wall from this side) |
| BW | breakable wall | upper right exit | upper left exit | wall broken from other side |

## Check Locations

| check | subroom | requirements | notes |
| --- | --- | --- | --- |
| boneyard mossberry | graveyard | none | can be gotten with only jump -tested |
| rosaries on grave | graveyard | none | NOT CURRENTLY RANDOMIZED |
| rosary cache bone bottom 6 | upper right exit | none | MARKED AS ??? ON TRACKER |
| rosary cache bone bottom 7 | upper right exit | none | MARKED AS ??? ON TRACKER |
