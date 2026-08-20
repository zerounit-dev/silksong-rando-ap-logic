# Coral Tower Entrance (Coral_28)

**Game ID:** Coral_28

**Contributors:** Pxyl

## Subrooms

- Exit
- Door

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Exit | [Sands of Karak Upper Left Long Room (Coral_27)](sands-of-karak-upper-left-long-room.md) | L | None |  |  |  |
| D | door1 | Door | [Coral Tower (Coral_Tower_01)](coral-tower.md) | L | None |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| SC | Sandcarver Pit | Door | Exit | "Clawline OR Sharpdart OR Drifters Cloak OR ( Sprint AND ( Dash OR Faydown Cloak OR Beast Crest ) ) OR  ( Faydown Cloak AND ( Beast Crest OR Hunter Crest OR Architect Crest OR Shaman Crest ( Wanderer Crest AND Needle strike ) ) ) " |  |  |  |
| SC | Sandcarver Pit | Exit | Door | Clawline OR Sharpdart OR ( Sprint AND ( Dash OR Faydown Cloak OR Drifters Cloak OR Beast Crest OR Architect Crest ) )  OR ( Sprint AND ( Shaman Crest OR Hunter crest OR Heal stall OR ( Wanderers Crest AND Needle Strike AND Ledge Grab ) ) ) OR ( Dash AND ( Reaper Crest OR Beast Crest OR Faydown Cloak OR Drifters Cloak OR ( Architect Crest AND ( Ledge Grab OR Needle Strike ) ) ) ) OR ( Faydown Cloak AND ( Beast Crest OR Architect Crest OR Shaman Crest OR Hunter Crest OR Drifters Cloak OR ( Reaper Crest AND Ledge Grab ) OR ( Wanderer Crest AND Needle strike ) ) ) OR ( Drifters Cloak And ( Beast Crest OR Architect Crest OR Shaman Crest OR Wanderer Crest OR Heal Stall OR Ledge Grab OR Silk Soar OR ( Reaper Crest AND Needle Strike ) ) ) OR ( Silk Soar AND ( Beast Crest OR Architect Crest ) ) |  |  |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Resting Site | Door | Wish: A vassal lost started AND Steel soul AND ( Sprint AND ( Dash OR Drifters Cloak OR Faydown Cloak OR Beast Crest ) OR Clawline OR ( Silk soar AND Ledge Grab ) |  |  | Not included | Not Included for the better |
