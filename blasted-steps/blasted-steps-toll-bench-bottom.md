# Blasted Steps Toll Bench Bottom (Coral_02)

**Game ID:** Coral_02

**Contributors:** skai

## Subrooms

- Bottom Right
- Middle
- Bottom Left
- Top Left
- Top Right
- Top Right Pit (Right)
- Top Right Pit (Left)

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BR | Bottom Right | Bottom Right | [Blasted Steps Map Edge (Coral_19)](blasted-steps-map-edge.md) | TM | Nothing |  | Verified |  |
| TR | Top Right | Top Right | [Blasted Steps Wide Long Vertical (Coral_03)](blasted-steps-wide-long-vertical.md) | BL | Nothing |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BRM | Bottom Right to Middle | Bottom Right | Middle | Swift Step OR Faydown OR Clawline OR Flea Brew OR Sharpdart |  |  |  |
| BRM | Bottom Right to Middle | Middle | Bottom Right | Nothing (Falling) |  |  |  |
| BLM | Bottom Left to Middle | Bottom Left | Middle | ((Swift Step OR Proficient Beast OR Clawline OR Sharpdart OR (Flea Brew AND Flew Brew Stall AND Ledge Grab)) AND (Faydown OR Cling Grip OR Silk Soar)) OR Scuttlebrace OR (Drifter's Cloak AND ((Faydown AND Enemy Pogo AND Ledge Grab) OR Silk Soar)) |  |  |  |
| BLM | Bottom Left to Middle | Middle | Bottom Left | Nothing (Falling) |  |  |  |
| MTL | Middle to Top Left | Middle | Top Left | ((Swift Step OR Proficient Beast OR Clawline OR Sharpdart OR (Flea Brew AND Flew Brew Stall AND Ledge Grab)) AND (Faydown OR Cling Grip OR Silk Soar)) OR Scuttlebrace OR (Drifter's Cloak AND ((Faydown AND Enemy Pogo AND Ledge Grab) OR Silk Soar)) |  |  |  |
| MTL | Middle to Top Left | Top Left | Middle | Swift Step OR Faydown OR Clawline OR Flea Brew OR Sharpdart OR Crest Pogo |  |  |  |
| TLR | Top Left to Top Right | Top Left | Top Right | ((Swift Step OR Proficient Beast OR Clawline OR Sharpdart OR (Flea Brew AND Flew Brew Stall AND Ledge Grab)) AND (Faydown OR Cling Grip OR Silk Soar)) OR Scuttlebrace OR (Drifter's Cloak AND ((Faydown AND Enemy Pogo AND Ledge Grab) OR Silk Soar)) |  |  |  |
| TLR | Top Left to Top Right | Top Right | Top Left | ((Swift Step OR Proficient Beast OR Clawline OR Sharpdart OR (Flea Brew AND Flew Brew Stall AND Ledge Grab)) AND (Faydown OR Cling Grip OR Silk Soar)) OR Scuttlebrace OR (Drifter's Cloak AND ((Faydown AND Enemy Pogo AND Ledge Grab) OR Silk Soar)) |  |  |  |
| PLT | Pit Left to Top Right | Top Right Pit (Left) | Top Right | Cling Grip OR Scuttlebrace OR Silk Soar OR (Faydown AND Ledge Grab AND (Heal Stall or Flea Brew Stall)) |  |  |  |
| PLT | Pit Left to Top Right | Top Right | Top Right Pit (Left) | Nothing (Falling) |  |  |  |
| PRT | Pit Right to Top RIght | Top Right Pit (Right) | Top Right | Cling Grip OR Scuttlebrace OR Faydown |  |  |  |
| PRT | Pit Right to Top RIght | Top Right | Top Right Pit (Right) | Nothing (Falling) |  |  |  |
| BRP | Bottom Right to Pit | Top Right Pit (Left) | Bottom Right | Nothing (Falling) |  |  |  |
| LPM | Left Pit to Middle | Top Right Pit (Left) | Middle | Hit Lever OR Crest Pogo OR Clawline OR Flea Brew OR Sharpdart OR Swift Step OR Faydown |  |  |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Memory Locket: Blasted Steps | Top Right Pit (Right) | ((Swift Step OR Proficient Beast OR Clawline OR Sharpdart) AND (Faydown OR Cling Grip)) OR (Swift Step AND Scuttlebrace) OR (Drifter's Cloak AND (Faydown OR Silk Soar) OR (Silk Soar AND Faydown) |  |  | Included |  |
| Shell Shard Cache: Blasted Steps #1 | Bottom Left | (Cling Grip AND (Swift Step OR Flea Brew OR Faydown OR Clawline)) OR (Swift Step and Scuttlebrace) |  |  | Included |  |
| Shell Shard Cache: Blasted Steps #2 | Bottom Left | (Cling Grip AND (Swift Step OR Flea Brew OR Faydown OR Clawline)) OR (Swift Step and Scuttlebrace) |  |  | Included |  |
| Shell Shard Cache: Blasted Steps #3 | Bottom Left | (Cling Grip AND (Swift Step OR Flea Brew OR Faydown OR Clawline)) OR (Swift Step and Scuttlebrace) |  |  | Included |  |
