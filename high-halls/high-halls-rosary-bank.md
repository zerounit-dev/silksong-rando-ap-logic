# High Halls Rosary Bank (Hang_06_bank)

**Game ID:** Hang_06_bank

**Contributors:** rebel

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | Main Room | ✓ |
| S2 | Upper Vents | ✓ |
| S3 | Side Vents | ✓ |
| S4 | Lower Vents | ✓ |
| S5 | Vault | ✓ |
| S6 | Rosary Dropper | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Main Room | [High Halls Vault (Hang_06)](high-halls-vault.md) | D | Unlock Rosary Bank Door IN High Halls Vault |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| MV1 | Main <> Vents | Main Room | Upper Vents | (clear Rosary Bank - Breakable Ceiling  AND (Cling Grip left OR (easy Scuttlebrace AND (faydown OR easy flea brew stall OR (own crest beast AND medium heal stall))) OR Silk Soar OR (faydown AND cling grip right))) |  | Verified | ✓ |  |
| MV1 | Main <> Vents | Upper Vents | Main Room | clear Rosary Bank - Breakable Ceiling |  | Verified | ✓ |  |
| US | Upper <> Side | Upper Vents | Side Vents | spike pogo |  | Verified | ✓ |  |
| US | Upper <> Side | Side Vents | Upper Vents | spike pogo AND (cling grip left OR faydown OR cling grip right) |  | Verified | ✓ |  |
| SL | Side <> Lower | Side Vents | Lower Vents | spike pogo OR easy naked pogo OR clawline left OR sharpdart OR dash left OR drifter's OR (cling grip right AND (medium [plasmium,voltvessels, rune rage, flea brew, heal, thread storm] stall OR faydown)) |  | Verified | ✓ |  |
| SL | Side <> Lower | Lower Vents | Side Vents | (spike pogo OR easy naked pogo) AND cling grip right |  | Verified | ✓ |  |
| LV | Lower <> Vault | Lower Vents | Vault | ((Dash OR Clawline OR Sharpdart) AND (Cling Grip OR Easy Scuttlebrace OR (Faydown Cloak AND Ledge Grab))) |  | Verified | ✓ |  |
| LV | Lower <> Vault | Vault | Lower Vents | Nothing (Fall) |  | Verified | ✓ |  |
| LC | Lower <> Cannon | Lower Vents | Rosary Dropper | (clear Rosary Bank - Cannon Wall AND (spike pogo OR easy naked pogo OR clawline left OR cling grip right OR sharpdart OR dash left OR drifter's OR faydown)) |  | Verified | ✓ |  |
| LC | Lower <> Cannon | Rosary Dropper | Lower Vents | (clear Rosary Bank - Cannon Wall AND (Faydown Cloak OR Cling Grip right OR easy scuttlebrace)) |  | Verified | ✓ |  |
| MV2 | Main <> Vault | Main Room | Vault | Activate Rosary Bank - Vault Switch |  | Verified | ✓ |  |
| MV2 | Main <> Vault | Vault | Main Room | Activate Rosary Bank - Vault Switch |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Rosary Bank - Breakable Ceiling | Main Room | Break Wall up |  | Verified | blockade | ✓ |  |
| 2 | Rosary Bank - Cannon Wall | Lower Vents | Break Wall Left |  | Verified | blockade | ✓ |  |
| 3 | Rosary Bank - Vault Switch | Vault | Flip Lever Left |  | Verified | switch | ✓ |  |
| 4 | Rosary Cannon | Rosary Dropper | clear Rosary Bank - Cannon Wall AND (cling grip left OR faydown OR ledge grab left OR easy hazard respawn) |  | Verified | collectible | ✓ |  |
| 5 | Rosary Bank - Chest 1 | Vault | Free |  | Verified | collectible | ✓ |  |
| 6 | Rosary Bank - Chest 2 | Vault | Zilch |  | Verified | collectible | ✓ |  |
| 7 | Rosary Bank - Chest 3 | Vault | Nada |  | Verified | collectible | ✓ |  |
| 8 | Rosary Bank - Vault String 1 | Vault | Nothing |  | Verified | collectible | ✓ |  |
| 9 | Rosary Bank - Vault String 2 | Vault | Nothing |  | Verified | collectible | ✓ |  |
| 10 | Rosary Bank - Missable String 1 | Vault | ACT 2 |  | Verified | collectible | ✓ | only exists in act 2 |
| 11 | Rosary Bank - Missable String 2 | Vault | ACT 2 |  | Verified | collectible | ✓ | only exists in act 2 |
| 12 | Rosary Bank - Missable String 3 | Vault | ACT 2 |  | Verified | collectible | ✓ | only exists in act 2 |
| 13 | Rosary Bank - Missable String 4 | Vault | ACT 2 |  | Verified | collectible | ✓ | only exists in act 2 |
| 14 | Snitchfly 1 | Vault | Act 3 |  | Verified | enemy | ✓ | idk maybe its random? |
| 15 | Drapefly 1 | Upper Vents | nada |  | Verified | enemy | ✓ |  |
| 16 | Giant Drapemite 1 | Lower Vents | zilch |  | Verified | enemy | ✓ |  |
| 17 | Drapemite 1 | Upper Vents | free |  | Verified | enemy | ✓ |  |

## Room Images

### Connections

[![Connections for High Halls Rosary Bank (Hang_06_bank)](../00-annotations/high-halls/high-halls-rosary-bank-connections.png)](../00-annotations/high-halls/high-halls-rosary-bank-connections.png)

### Checks

[![Checks for High Halls Rosary Bank (Hang_06_bank)](../00-annotations/high-halls/high-halls-rosary-bank-checks.png)](../00-annotations/high-halls/high-halls-rosary-bank-checks.png)

### Scene

[![Scene for High Halls Rosary Bank (Hang_06_bank)](../00-annotations/high-halls/high-halls-rosary-bank-scene.png)](../00-annotations/high-halls/high-halls-rosary-bank-scene.png)
