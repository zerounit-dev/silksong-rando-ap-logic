# The Big Fall (Aspid_01)

**Game ID:** Aspid_01

**Contributors:** herounit

## Subrooms

- top area
- upper right ledge
- upper left ledge
- wish ledge
- middle right ledge
- lower left area
- lower right area
- bottom area
- upper silk soar only zone
- lower silk soar only zone

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | ceiling | top area | blasted bridge | F | silk soar |  |  |  |
| UR | upper right | upper right ledge | shellwood grand gate bell | L | none |  |  |  |
| MR | middle right | middle right ledge | [Mosshome Upper (Mosstown_02)](mosshome-upper.md) | L | breakable wall -must be opened from the other side (NEEDS VERIFICATION) | TODO | Needs verification | NEEDS VERIFICATION |
| LR | lower right | lower right area | [Mosshome Lower (Bone_11)](mosshome-lower.md) | L | none |  |  |  |
| UL | upper left | upper left ledge | [Wormways Upper East (Crawl_01)](../wormways/wormways-upper-east.md) | R | none |  |  |  |
| LL | lower left | lower left area | [Wormways Craggler Hallway (Crawl_04)](../wormways/wormways-craggler-hallway.md) | R | none |  |  |  |
| LF | left floor | bottom area | [Bone Bottom Town (Bonetown)](bone-bottom-town.md) | LC | none |  |  |  |
| RF | right floor | lower right area | [Bone Bottom Town (Bonetown)](bone-bottom-town.md) | RC | none |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| F1 | top fall | top area | upper right ledge | none (falling) |  |  |  |
| F2 | upper right ledge fall | upper right ledge | upper left ledge | none (falling |  |  |  |
| F3 | upper left ledge fall | upper left ledge | wish ledge | none (falling) |  |  |  |
| F4 | wish ledge fall | wish ledge | upper silk soar only zone | none (falling) |  |  |  |
| F5 | upper silk soar zone fall | upper silk soar only zone | middle right ledge | none (falling) |  |  |  |
| F6 | middle right ledge fall | middle right ledge | lower silk soar only zone | none (falling) |  |  |  |
| F7 | lower silk soar zone fall | lower silk soar only zone | bottom area | none (falling) |  |  |  |
| F8 | lower left area fall | lower left area | bottom area | none (falling) |  |  |  |
| F9 | lower right area fall | lower right area | bottom area | none (falling) |  |  |  |
| S1 | bottom silk soar | bottom area | lower silk soar only zone | silk soar |  |  |  |
| S2 | lower zone silk soar | lower silk soar only zone | upper silk soar only zone | silk soar |  |  |  |
| S3 | upper zone silk soar | upper silk soar only zone | top area | silk soar |  |  |  |
| LC | lower crossing | lower left area | lower right area | easy skips enabled OR silk soar OR horizontal movement tech OR dash OR run OR cling grip OR faydown cloak OR silk soar |  |  |  |
| LC | lower crossing | lower right area | lower left area | easy skips enabled OR silk soar OR horizontal movement tech OR dash OR run OR cling grip OR faydown cloak |  |  |  |
| WC | wish climb | wish ledge | upper left ledge | silk soar OR cling grip |  |  | can't be collected unless the wish has been started from bellhart |
| UC | upper crossing | upper left ledge | upper right ledge | silk soar OR cling grip OR faydown cloak OR clawline OR sharpdart OR dash |  |  |  |
| UC | upper crossing | upper right ledge | upper left ledge | silk soar OR cling grip OR faydown cloak OR clawline OR sharpdart OR dash |  |  |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| rosary cache moss grotto | lower left area | none |  |  | Included |  |
| choral commandment moss grotto | middle right ledge | none |  |  | Included |  |
| wish my missing courier | wish ledge | none |  |  | Included |  |
