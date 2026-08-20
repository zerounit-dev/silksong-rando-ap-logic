# Crustnut (Coral_41)

**Game ID:** Coral_41

**Contributors:** Pyxl

## Subrooms

- Start
- End
- Shard Platform

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Start | [Sands of Karak Tall Centre Room (Coral_35b)](sands-of-karak-tall-centre-room.md) | UML | None |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| WR | Whole Room | Start | End | Cling grip AND ( Clawline OR Sharpdart OR ( Dash AND ( Drifters Cloak OR Beast Crest ) ) ) OR ( Beast crest AND Faydown Cloak AND Needle Strike ) |  |  |  |
| WR | Whole Room | End | Start | Cling grip AND ( Clawline OR Sharpdart OR ( Dash AND ( Drifters Cloak OR Beast Crest ) ) ) OR ( Beast crest AND Faydown Cloak AND Needle Strike ) |  |  |  |
| SD | Shard Detour | Start | Shard Platform | Silk Soar OR ( ( Dash AND Scuttlebrace ) AND ( Clawline OR Sharpdart ) ) OR ( Cling grip AND ( Dash OR Clawline OR Sharpdart OR Beast Crest OR Faydown Cloak OR Drifters Cloak ) ) |  |  |  |
| SD | Shard Detour | Shard Platform | Start | None |  |  |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Crustnut | End | None |  |  | Included |  |
| Shard Cache: Sands of Karak #11 | Shard Platform | None |  |  | Included |  |
