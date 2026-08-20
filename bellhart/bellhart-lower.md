# Bellhart Lower (Belltown_basement_03)

**Game ID:** Belltown_basement_03

**Contributors:** Pyxl

## Subrooms

- Top Exit
- Hermit
- Upper Hall
- Under Hermit Hall
- Rosary Room
- Passage below rosary
- Breakable Wall Passage
- Lower Passage 1
- Lower Passage 2
- Bottom Exit

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| C | top1 |  | [Bellhart Bellway (Belltown_basement)](bellhart-bellway.md) | F | None |  |  |  |
| L | left1 |  | [The Marrow Jail Pathway (Bone_08)](../the-marrow/the-marrow-jail-pathway.md) | UR | None |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| PL | Platforms Upper | Top Exit | Hermit | None |  |  |  |
| PL | Platforms Upper | Hermit | Top Exit | Clawline OR Ledge Grab OR Shamen Crest OR ( Dash AND Scuttlebrace ) OR Faydown Cloak OR Silk Soar OR  Cling Grip |  |  |  |
| UP | Upper Hall | Hermit | Upper Hall | Cling Grip OR Silk Soar OR ( Scuttlebrace AND Dash ) |  |  |  |
| UP | Upper Hall | Upper Hall | Hermit | None |  |  |  |
| TL | Tall Passage Left | Upper Hall | Under Hermit Hall | None |  |  |  |
| TL | Tall Passage Left | Under Hermit Hall | Upper Hall | Cling Grip OR ( Scuttlebrace AND Dash ) |  |  |  |
| HH | Hermit Hole | Hermit | Under Hermit Hall | One way wall broken From Underneath |  |  |  |
| HH | Hermit Hole | Under Hermit Hall | Hermit | Cling Grip OR Silk Soar OR ( Scuttlebrace AND Dash ) AND One way wall broken |  |  |  |
| TR | Tall Passage Right | Under Hermit Hall | Rosary Room | None |  |  |  |
| TR | Tall Passage Right | Rosary Room | Under Hermit Hall | Cling Grip OR ( Scuttlebrace AND Dash ) |  |  |  |
| WS | Wide Shaft | Rosary Room | Passage below rosary | None |  |  |  |
| WS | Wide Shaft | Passage below rosary | Rosary Room | Cling Grip OR Silk Soar OR ( Scuttlebrace AND Dash ) |  |  |  |
| RS | Shaft near Rosary Cache | Passage below rosary | Breakable Wall Passage | Cling Grip OR Silk Soar OR ( Scuttlebrace AND Dash ) |  |  |  |
| RS | Shaft near Rosary Cache | Breakable Wall Passage | Passage below rosary | None |  |  |  |
| BW | Broken Floor Shaft | Breakable Wall Passage | Under Hermit Hall | Cling Grip OR ( Scuttlebrace AND Dash ) |  |  |  |
| BW | Broken Floor Shaft | Under Hermit Hall | Breakable Wall Passage | One way wall broken From Underneath |  |  |  |
| BL | Tall Passage Bottom Left | Breakable Wall Passage | Lower Passage 1 | None |  |  |  |
| BL | Tall Passage Bottom Left | Lower Passage 1 | Breakable Wall Passage | Cling Grip OR ( Scuttlebrace AND Dash ) |  |  |  |
| LV | Lower Passages Shaft | Lower Passage 1 | Lower Passage 2 | None |  |  |  |
| LV | Lower Passages Shaft | Lower Passage 2 | Lower Passage 1 | Cling Grip OR ( Scuttlebrace AND Dash ) |  |  |  |
| WP | Wide Platform Shaft | Lower Passage 2 | Passage below rosary | Cling Grip OR Silk Soar OR ( Dash AND Scuttlebrace AND ( Ledge Grab OR Clawline OR Faydown Cloak OR Sharpdart OR Beast Crest ) ) AND Breakable Floor Opened |  |  |  |
| WP | Wide Platform Shaft | Passage below rosary | Lower Passage 2 | One way wall broken From Underneath AND ( Dash OR Sprint OR Ledge grab OR Clawline OR Drifters Cloak OR Faydown Cloak OR Cling grip OR Shamen Crest OR Architect Crest OR Beast Crest ) |  |  |  |
| ES | Exit Shaft | Lower Passage 2 | Bottom Exit | Break One way wall |  |  |  |
| ES | Exit Shaft | Bottom Exit | Lower Passage 2 | One way wall broken from above AND ( Cling Grip OR Silk Soar ( Dash AND Scuttlebrace AND Faydown Cloak ) ) |  |  |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Hermits Soul | Hermit | Silk and Soul Wish Started |  |  | Not included |  |
| Silver Bell Spawn Location #6 | Upper Hall | Silver Bells Wish Started |  |  | Not included |  |
| Rosary Cache: Bellhart #6 | Upper Hall | None |  |  | Included |  |
| Silver Bell Spawn Location #7 | Upper Hall | Silver Bells Wish Started |  |  | Not included |  |
| Silver Bell Spawn Location #8 | Under Hermit Hall | Silver Bells Wish Started |  |  | Not included |  |
| Silver Bell Spawn Location #12 | Under Hermit Hall | Silver Bells Wish Started |  |  | Not included |  |
| Rosary Cache: Bellhart #7 | Rosary Room | None |  |  | Included |  |
| Silver Bell Spawn Location #9 | Passage below rosary | Silver Bells Wish Started |  |  | Not included |  |
| Silver Bell Spawn Location #10 | Lower Passage 1 | Silver Bells Wish Started |  |  | Not included |  |
| Silver Bell Spawn Location #11 | Lower Passage 2 | Silver Bells Wish Started |  |  | Not included |  |
| Rosary Cache: Bellhart #5 | Bottom Exit | None |  |  | Included |  |
