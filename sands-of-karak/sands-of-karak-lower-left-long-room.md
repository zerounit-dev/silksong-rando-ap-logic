# Sands of Karak Lower Left Long Room (Coral_23)

**Game ID:** Coral_23

**Contributors:** Pyxl

## Subrooms

- Lower Entrance
- Centre Platform
- Upper Left Platform
- Hidden Exit
- Right Exit

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| UL | left2 | Hidden Exit | [Watcher at the Edge (Coral_39)](watcher-at-the-edge.md) | R | None |  |  |  |
| R | right1 | Right Exit | [Sands of Karak Tall Centre Room (Coral_35b)](sands-of-karak-tall-centre-room.md) | LL | None |  |  |  |
| LL | left1 | Lower Entrance | [Sands of Karak Entrance (Coral_25)](sands-of-karak-entrance.md) | R | None |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LN | Lower Nut Platforming | Lower Entrance | Centre Platform | Dash OR Clawline OR Drifters Cloak OR Faydown Cloak OR Beast Crest OR Sharpdart OR ( Reaper Crest AND Ledge Grab ) |  |  |  |
| LN | Lower Nut Platforming | Centre Platform | Lower Entrance | Clawline OR ( Dash AND Sprint AND Faydown Cloak AND Drifters Cloak ) |  |  |  |
| UP | Upper Left Nut Platforming | Centre Platform | Upper Left Platform | ( Cling grip OR Silk Soar ) AND ( Dash OR Clawline OR Sharpdart OR Faydown Cloak OR Drifters Cloak ) OR ( Silk Soar AND Beast Crest ) |  |  |  |
| UP | Upper Left Nut Platforming | Upper Left Platform | Centre Platform | Dash OR Clawline OR Beast Crest OR Drifters Cloak OR Faydown Cloak OR Sharpdart |  |  |  |
| HD | Hidden Shaft | Upper Left Platform | Hidden Exit | Silk Soar |  |  |  |
| HD | Hidden Shaft | Hidden Exit | Upper Left Platform | None |  |  |  |
| RN | Right Nut Platforming | Centre Platform | Right Exit | Cling Grip AND ( Dash OR Drifters Cloak OR Clawline OR Sharpdart OR ( Faydown Cloak AND Beast Crest  ) ) |  |  |  |
| RN | Right Nut Platforming | Right Exit | Centre Platform | Clawline AND ( Dash OR Drifters Cloak OR Faydown Cloak OR Sharpdart ) OR ( Drifters Cloak AND Sharpdart AND 16 Max silk ) |  |  |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Memory Locket #15 | Upper Left Platform | None |  |  | Included |  |
