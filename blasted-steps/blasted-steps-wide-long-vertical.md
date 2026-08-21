# Blasted Steps Wide Long Vertical (Coral_03)

**Game ID:** Coral_03

**Contributors:** skai

## Subrooms

- Pit
- Bottom Third (Left)
- Bottom Third (Right)
- Middle Left (Entrance)
- Middle Right (Entrance)
- Middle Section 1
- Middle Section 2
- Top Third Entrances
- Top Third

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BL | Bottom Left | Bottom Third (Left) | [Blasted Steps Toll Bench Bottom (Coral_02)](blasted-steps-toll-bench-bottom.md) | TR | Nothing |  |  |  |
| B3 | Bottom (3) | Pit | [Blasted Steps Map Edge (Coral_19)](blasted-steps-map-edge.md) | TR3 | Nothing |  |  |  |
| B4 | Bottom (4) | Pit | [Blasted Steps Map Edge (Coral_19)](blasted-steps-map-edge.md) | TR4 | Nothing |  |  |  |
| B5 | Bottom (5) | Pit | [Blasted Steps Map Edge (Coral_19)](blasted-steps-map-edge.md) | TR5 | Nothing |  |  |  |
| B6 | Bottom (6) | Pit | [Blasted Steps Map Edge (Coral_19)](blasted-steps-map-edge.md) | TR6 | Nothing |  |  |  |
| B7 | Bottom (7) | Pit | [Blasted Steps Map Edge (Coral_19)](blasted-steps-map-edge.md) | TR7 | Nothing |  |  |  |
| B8 | Bottom (8) | Pit | [Blasted Steps Map Edge (Coral_19)](blasted-steps-map-edge.md) | TR8 | Nothing |  |  |  |
| BR | Bottom Right | Bottom Third (Right) | [Blasted Steps Shakra Room (Coral_12)](blasted-steps-shakra-room.md) | BL | Nothing |  |  |  |
| ML | Middle Left | Middle Left (Entrance) | [Great Conchflies (Coral_11)](great-conchflies.md) | R | Nothing |  |  |  |
| MR | Middle Right | Middle Right (Entrance) | [Blasted Steps Shakra Room (Coral_12)](blasted-steps-shakra-room.md) | TL | Nothing |  |  |  |
| TR | Top Right | Top Third Entrances | [Pre Last Judge Room (Coral_32)](pre-last-judge-room.md) | L | Nothing |  |  |  |
| TL | Top Left | Top Third Entrances | [Blasted Steps Bellway (Bellway_08)](blasted-steps-bellway.md) | R | Nothing |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| BLR | Bottom Left to Right | Bottom Third (Left) | Bottom Third (Right) | Swift Step OR Faydown OR Enemy Pogo OR Silk Soar OR Clawline OR (Flea Brew AND (Crest Pogo OR Flew Brew Stall)) |  |  |  |
| BLR | Bottom Left to Right | Bottom Third (Right) | Bottom Third (Left) | Swift Step OR Faydown OR Enemy Pogo OR Silk Soar OR Clawline OR (Flea Brew AND (Crest Pogo OR Flew Brew Stall)) |  |  |  |
| BLM | Bottom Left to Middle 1 | Bottom Third (Left) | Middle Section 1 | ((Enemy Pogo AND Faydown AND Ledge Grab) OR (Swift Step OR Faydown OR Clawline OR Drifter's Cloak OR Enemy Pogo OR (Flea Brew AND (Crest Pogo OR Flea Brew Stall)) AND CLING) OR (Swift Step AND Scuttlebrace AND Faydown) OR Silk Soar |  |  |  |
| BLM | Bottom Left to Middle 1 | Middle Section 1 | Bottom Third (Left) | Nothing (Falling) |  |  |  |
| BRM | Bottom Right to Middle | Bottom Third (Right) | Middle Section 1 | ((Enemy Pogo AND Faydown AND Ledge Grab) OR (Swift Step OR Faydown OR Clawline OR Drifter's Cloak OR Enemy Pogo OR (Flea Brew AND (Crest Pogo OR Flea Brew Stall)) AND CLING) OR (Swift Step AND Scuttlebrace AND Faydown) OR Silk Soar |  |  |  |
| BRM | Bottom Right to Middle | Middle Section 1 | Bottom Third (Right) | Nothing (Falling) |  |  |  |
| M12 | Middle 1 to Middle 2 | Middle Section 1 | Middle Section 2 | Nothing (Jumping) |  |  |  |
| M12 | Middle 1 to Middle 2 | Middle Section 2 | Middle Section 1 | Nothing (Falling) |  |  |  |
| MLE | Middle to Middle Left | Middle Section 2 | Middle Left (Entrance) | Enemy Pogo OR Silk Soar OR Swift Step OR Clawline OR Sharpdart (Drifter's Cloak AND Ledge Grab) OR (Flea Brew AND (Cling OR Flea Brew Stall OR Heal Stall)) |  |  |  |
| MLE | Middle to Middle Left | Middle Left (Entrance) | Middle Section 2 | Enemy Pogo OR Swift Step OR Clawline OR Sharpdart OR Drifter's Cloak OR Faydown OR Flea Brew OR Silk Soar OR (Crest Pogo and Cling Grip) |  |  |  |
| MRE | Middle to Middle Right | Middle Section 2 | Middle Right (Entrance) | (Easy Skip AND Drifter's Cloak) OR (Easy Skip AND Swift Step AND Clawline AND Cling AND Ledge Grab) OR (Faydown AND ((Swift Step AND Ledge Grab) OR (Drifter's Cloak AND Wind AND Ledge Grab) OR Clawline)) OR Silk Soar |  |  |  |
| MRE | Middle to Middle Right | Middle Right (Entrance) | Middle Section 2 | Nothing (Falling) |  |  |  |
| PTB | Pit to Bottom | Pit | Bottom Third (Left) | Cling Grip OR Scuttle OR Silk Soar |  |  |  |
| PTB | Pit to Bottom | Bottom Third (Left) | Pit | Nothing (Falling) |  |  |  |
| MRT | Middle Right to Top | Middle Right (Entrance) | Top Third | Ledge Grab OR Cling Grip OR Faydown OR Silk Soar OR Scuttle |  |  |  |
| MRT | Middle Right to Top | Top Third | Middle Right (Entrance) | Nothing (Falling) |  |  |  |
| TTE | Top Third to Entrances | Top Third | Top Third Entrances | (Ledge Grab AND (Cling Grip OR (Scuttlebrace AND Proficient Movement)) AND ((Lever Hit AND Flea Brew) OR Swift Step OR Clawline)) OR Silk Soar |  |  |  |
| TTE | Top Third to Entrances | Top Third Entrances | Top Third | Nothing (Falling) |  |  |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Frayed Rosary String: Blasted Steps | Pit | Nothing (Falling) |  |  | Included |  |
| Lever | Top Third | Ledge Grab AND (Cling Grip OR Scuttlebrace) OR Faydown OR Silk Soar |  |  | Included |  |
