# Deep Docks Chains Lower East (Dock_03c)

**Game ID:** Dock_03c

**Contributors:** herounit

## Subrooms

- upper chains
- spool fragment area
- lower chains
- middle chains
- upper lava platform
- lower lava platform
- gauntlet
- upper left of gauntlet

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| RC | top2 | upper chains | [Deep Docks Chains Upper East (Dock_03)](deep-docks-chains-upper-east.md) | F |  |  |  |  |
| LC | top1 | upper left of gauntlet | [Deep Docks Chains Flea Rescue (Dock_03d)](deep-docks-chains-flea-rescue.md) | F |  |  |  |  |
| L | left2 | lower lava platform | [Deep Docks Chains Center (Dock_02b)](deep-docks-chains-center.md) | LR | none (hit blast rock on this side to open exit for both sides) |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SP | open spool door | spool fragment area | upper chains | open airlock door |  |  | one-way |
| SP | open spool door | upper chains | spool fragment area | can pogo  AND cling grip  AND ( clawline OR ( dash AND ( run OR sharpdart OR drifter's cloak ) ) ) |  | Needs verification | run or sharpdart or drifter's cloak  or clawline to get to the initial wall to cling grip. clawline or dash to get to pogo area. then free. |
| C1 | upper to middle chains | middle chains | upper chains | run OR dash OR drifter's cloak OR faydown cloak OR cling grip OR silk soar OR clawline OR sharpdart |  |  |  |
| C1 | upper to middle chains | upper chains | middle chains | none (falling) |  |  |  |
| C2 | lower to middle chains | lower chains | middle chains | silk soar OR cling grip OR faydown cloak |  |  |  |
| C2 | lower to middle chains | middle chains | lower chains | none (falling) |  |  |  |
| UC | upper clawline area | lower chains | upper lava platform | clawline |  |  |  |
| UC | upper clawline area | upper lava platform | lower chains | clawline OR drifter's cloak |  |  |  |
| LG | cross lava gap | lower chains | lower lava platform | clawline OR ( drifter's cloak AND faydown cloak ) |  | Needs verification | seems just out of reach of drifter's cloak and dash |
| LG | cross lava gap | lower lava platform | lower chains | clawline OR ( drifter's cloak AND faydown cloak ) |  |  |  |
| UL | upper lava platform to lower lava platform | upper lava platform | lower lava platform | none (falling) |  |  |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| silk spool deep docks 1 | spool fragment area | none |  |  | Included |  |
