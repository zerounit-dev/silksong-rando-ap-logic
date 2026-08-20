# Sands of Karak Lower Right Long Room (Coral_24)

**Game ID:** Coral_24

**Contributors:** Pyxl

## Subrooms

- Left Exit
- Flea Ledge
- Lower Centre Platform
- Upper Centre Platform
- Right Exit

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Left Exit | [Sands of Karak Tall Centre Room (Coral_35b)](sands-of-karak-tall-centre-room.md) | LR | None |  |  |  |
| R | right1 | Right Exit | [Sands of Karak Right Side Tall room (Coral_26)](sands-of-karak-right-side-tall-room.md) | LL | None |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LW | Left Wall | Left Exit | Flea Ledge | Silk Soar |  |  |  |
| LW | Left Wall | Flea Ledge | Left Exit | None |  |  |  |
| LN | Lower Left Nut Platforms | Left Exit | Lower Centre Platform | Beast Crest OR Dash OR Clawline OR Faydown Cloak OR Drifters Cloak OR Sharpdart OR ( Ledge grab AND ( Reaper crest OR Shamen Crest OR Hunters Crest OR Wanderers Crest ) ) |  |  |  |
| LN | Lower Left Nut Platforms | Lower Centre Platform | Left Exit | ( Drifters Cloak AND ( Clawline OR Beastcrest OR Dash OR Faydown Cloak ) ) OR ( Clawline AND ( Shamen crest OR Faydown Cloak OR Silk Soar OR Beast Crest ) ) OR ( Faydown Cloak AND ( Beast Crest OR Sharpdart ) ) |  |  |  |
| UN | Upper Left Nut Platforms | Upper Centre Platform | Flea Ledge | "( Cling grip AND Clawline ) OR ( Clawline AND ( Drifters Cloak AND ( hunter Crest OR Reaper Crest OR Wanderer Crest OR Shaman Crest ) ) OR Faydown Cloak ) " |  |  |  |
| UN | Upper Left Nut Platforms | Flea Ledge | Upper Centre Platform | Not happening |  | Needs verification |  |
| RN | Right Nut Platforms | Upper Centre Platform | Right Exit | ( Cling grip AND  ( ( Clawline OR Drifters Cloak ) OR Beast Crest ) ) |  |  |  |
| RN | Right Nut Platforms | Right Exit | Upper Centre Platform | None |  |  |  |
| CN | Centre Platforms | Lower Centre Platform | Upper Centre Platform | Faydown Cloak OR Sprint OR ( Dash AND ( Ledge grab OR Cling grip ) ) OR Drifters Cloak OR Clawline OR Sharpdart OR Silksoar OR Beast Crest OR ( Architect Crest AND Needle Strike ) |  |  |  |
| CN | Centre Platforms | Upper Centre Platform | Lower Centre Platform | None |  |  |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Shell Shard Cache: Sands of Karak #1 | Lower Centre Platform | None |  |  | Included |  |
| Shell Shard Cache: Sands of Karak #2 | Lower Centre Platform | None |  |  | Included |  |
| Flea: Sands of Karak | Flea Ledge | None |  |  | Included |  |
