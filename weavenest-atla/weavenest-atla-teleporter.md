# Weavenest Atla Teleporter

## Subrooms

- upper telepad
- upper shaft
- lower shaft
- lower telepad

## Room Transitions

| alias | name | from subroom | destination | requirements |
| --- | --- | --- | --- | --- |
| UL | upper left | upper telepad | [weavenest atla entrance](./weavenest-atla-entrance.md) -R | none |
| ML | middle left | lower shaft | [weavenest atla spool](./weavenest-atla-spool.md) -R | none |
| LL | lower left | lower telepad | [weavenest atla bench](./weavenest-atla-bench.md) -R | none |
| UR | upper right | upper telepad | [weavenest atla power](./weavenest-atla-power.md) -L | none |
| MR | middle right | upper shaft | [weavenest atla hallway](./weavenest-atla-hallway.md) -L | none |
| LR | lower right | lower telepad | [weavenest atla eva](./weavenest-atla-eva.md) -L | none |

## Subroom Connections

| alias | name | source | destination | requirements |
| --- | --- | --- | --- | --- |
| TP | teleporter | upper telepad | lower telepad | weavenest atla power activation |
| TP | teleporter | lower telepad | upper telepad | weavenest atla power activation |
| SM | shaft middle | lower telepad | upper shaft | requires cling grip OR silk soar |
| SM | shaft middle | upper shaft | lower telepad | none (falling) |
| SB | shaft base | lower telepad | lower shaft | requires cling grip OR silk soar |
| SB | shaft base | lower shaft | lower telepad | none (falling) |

## Check Locations

| check | subroom |
| --- | --- |
| none |  |
|  |  |
|  |  |
|  |  |
|  |  |
