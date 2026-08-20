# Upper Bellhart (Belltown_04)

**Game ID:** Belltown_04

**Contributors:** Pyxl

## Subrooms

- Lower Exits
- Lower Big Room
- Silver Bell Cubby
- Central Passage
- Upper Big room

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LL | left2 | Lower Exits | [Shellwood Hidden Bellhart Connection (Shellwood_15)](../shellwood/shellwood-hidden-bellhart-connection.md) | R | None |  |  |  |
| F | bot1 | Lower Exits | [Widow Boss Fight (Belltown_Shrine)](widow-boss-fight.md) | C | None |  |  |  |
| UL | left1 | Upper Big room | [Shellwood Upper Bellhart Entrance (Shellwood_13)](../shellwood/shellwood-upper-bellhart-entrance.md) | R | None |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| TS1 | Tall Shaft1 | Lower Exits | Lower Big Room | Break wall AND ( Ledge Grab OR Clawline OR Faydown Cloak OR ( Dash AND Scuttlebrace ) OR Damage Knockback OR Cling Grip ) |  |  |  |
| TS1 | Tall Shaft1 | Lower Big Room | Lower Exits | Break wall AND ( Ledge Grab OR Clawline OR Faydown Cloak OR ( Dash AND Scuttlebrace ) OR Cling grip ) |  |  |  |
| TS2 | Tall Shaft2 | Lower Exits | Silver Bell Cubby | Break wall AND ( Cling Grip OR ( Dash AND Scuttlebrace ) ) |  |  |  |
| TS2 | Tall Shaft2 | Silver Bell Cubby | Lower Exits | Break wall |  |  |  |
| TS3 | Tall Shaft3 | Lower Big Room | Silver Bell Cubby | None |  |  |  |
| TS3 | Tall Shaft3 | Silver Bell Cubby | Lower Big Room | Cling Grip OR ( Dash AND Scuttlebrace ) |  |  |  |
| TS4 | Tall Shaft4 | Silver Bell Cubby | Central Passage | Cling Grip OR ( Dash AND Scuttlebrace ) |  |  |  |
| TS4 | Tall Shaft4 | Central Passage | Silver Bell Cubby | None |  |  |  |
| US | Upper Shafts | Central Passage | Upper Big room | Break wall AND ( Cling Grip OR ( Dash AND Scuttlebrace ) ) |  |  |  |
| US | Upper Shafts | Upper Big room | Central Passage | None |  |  |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Silver Bell Spawn Location #1 | Lower Big Room | None |  |  | Included |  |
| Silver Bell Spawn Location #2 | Lower Big Room | Cling Grip OR Silk Soar OR ( Dash AND Scuttlebrace ) |  |  | Included |  |
| Rosary Cache: Bellhart #1 | Lower Big Room | Cling Grip OR Silk Soar OR ( Dash AND Scuttlebrace ) |  |  | Included |  |
| Rosary Cache: Bellhart #2 | Lower Big Room | Cling Grip OR Silk Soar OR ( Dash AND Scuttlebrace ) |  |  | Included |  |
| Silver Bell Spawn Location #3 | Silver Bell Cubby | None |  |  | Included |  |
| Silver Bell Spawn Location #4 | Central Passage | Break wall |  |  | Included |  |
| Rosary Cache: Bellhart #3 | Central Passage | Break wall |  |  | Included |  |
| Silver Bell Spawn Location #5 | Upper Big room | None |  |  | Included |  |
| Flea: Bellhart | Upper Big room | Silk Soar OR Cling Grip OR ( Dash AND Scuttlebrace ) OR ( Easy skips AND ( Faydown Cloak OR Drifters Cloak ) ) |  |  | Included |  |
