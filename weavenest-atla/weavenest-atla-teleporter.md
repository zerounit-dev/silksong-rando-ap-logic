# Weavenest Atla Teleporter (Weave_02)

**Game ID:** Weave_02

**Contributors:** herounit

## Subrooms

- upper telepad
- upper shaft
- lower shaft
- lower telepad

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | upper left | upper telepad | [Weavenest Atla Entrance (Weave_04)](weavenest-atla-entrance.md) | R | none |  |  |  |
| UR | upper right | upper telepad | [Weavenest Atla Power (Weave_12)](weavenest-atla-power.md) | L | none |  |  |  |
| MR | middle right | upper shaft | [Weavenest Atla Hallway (Weave_13)](weavenest-atla-hallway.md) | L | none |  |  |  |
| ML | middle left | lower shaft | [Weavenest Atla Spool (Weave_11)](weavenest-atla-spool.md) | R | none |  |  |  |
| LL | lower left | lower telepad | [Weavenest Atla Bench (Weave_07)](weavenest-atla-bench.md) | R | none |  |  |  |
| LR | lower right | lower telepad | [Weavenest Atla Eva (Weave_10)](weavenest-atla-eva.md) | L | break walls |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TP | teleporter | upper telepad | lower telepad | weavenest atla power activation |  |  |  |
| TP | teleporter | lower telepad | upper telepad | weavenest atla power activation |  |  |  |
| SM | shaft middle | lower telepad | upper shaft | cling grip OR silk soar |  |  |  |
| SM | shaft middle | upper shaft | lower telepad | none (falling) |  |  |  |
| SB | shaft base | lower telepad | lower shaft | cling grip OR silk soar |  |  |  |
| SB | shaft base | lower shaft | lower telepad | none (falling) |  |  |  |

## Check Locations

No check locations defined.
