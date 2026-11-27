# Whispering Vaults Jumps (Library_09)

**Game ID:** Library_09

**Contributors:** Rebel

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | Flea Chase | ✓ |
| S2 | Flea | ✓ |
| S3 | Annoying Ass Jump (Left) | ✓ |
| S4 | Annoying Ass Jump (Right) | ✓ |
| S5 | Jump 2 (Right) | ✓ |
| S6 | Jump 2 (Left) | ✓ |
| S7 | Rosary Necklace | ✓ |
| S8 | Room With Stuff | ✓ |
| S9 | Bottom Right Entrance | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | bot1 | Bottom Right Entrance | [Whispering Vaults Totally Not White Palace (Library_07)](whispering-vaults-totally-not-white-palace.md) | T | None |  | Verified | ✓ | Changed it from Flea Chase to Bottom Right Entrance  - Moriko |
| L | left1 | Room With Stuff | [Whispering Vaults Hell (Library_04)](whispering-vaults-hell.md) | TR | Activate Whispering Vaults: Flip Switch #6 |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| FG | Flea Get | Flea Chase | Flea | Silk Soar OR (Clawline AND Cling Grip) OR (Clawline AND Scuttlebrace AND (Spike Pogo OR Faydown Cloak)) |  | Verified | ✓ |  |
| FG | Flea Get | Flea | Flea Chase | Nothing. (BIG fall) |  | Verified | ✓ |  |
| AJ | Annoying Jump | Annoying Ass Jump (Right) | Annoying Ass Jump (Left) | Sprint OR Dash OR Drifter's Cloak OR Faydown Cloak OR Clawline OR Scuttlebrace OR Sharpdart OR Easy Enemy Pogo OR Spike Pogo OR Easy Hazard Respawn |  | Verified | ✓ |  |
| AJ | Annoying Jump | Annoying Ass Jump (Left) | Annoying Ass Jump (Right) | Dash OR Sprint OR Faydown Cloak OR Scuttlebrace OR Clawline OR Sharpdart OR (Spike Pogo OR Enemy Pogo (Easy Skip))  OR (Drifter's Cloak AND Ledge Grab) |  | Verified | ✓ | this side you CANT damage boost. |
| JT | Jump Two | Jump 2 (Left) | Jump 2 (Right) | Dash OR Sprint OR Faydown Cloak OR Scuttlebrace OR Clawline OR Sharpdart OR (Spike Pogo OR Enemy Pogo (Easy Skip))  OR (Drifter's Cloak AND Ledge Grab) |  | Verified | ✓ | its literally the SAME jump again. |
| JT | Jump Two | Jump 2 (Right) | Jump 2 (Left) | Dash OR Sprint OR Faydown Cloak OR Scuttlebrace OR Clawline OR Sharpdart OR (Spike Pogo OR Enemy Pogo (Easy Skip))  OR (Drifter's Cloak AND Ledge Grab) |  | Verified | ✓ |  |
| RP | Rosary Pickup | Jump 2 (Right) | Rosary Necklace | (Sprint AND Clawline) OR (Sprint AND Faydown Cloak AND Spike Pogo AND (Drifter's Cloak OR Dash)) |  | Verified | ✓ |  |
| EC | Enter to Chase | Bottom Right Entrance | Flea Chase | Silk Soar OR Scuttlebrace OR Cling Grip |  | Verified | ✓ |  |
| EC | Enter to Chase | Flea Chase | Bottom Right Entrance | Nothing. (Fall) |  | Verified | ✓ |  |
| CJ1 | Chase to Jump 1 | Flea Chase | Annoying Ass Jump (Right) | Nothing. |  | Verified | ✓ |  |
| CJ1 | Chase to Jump 1 | Annoying Ass Jump (Right) | Flea Chase | Nothing. |  | Verified | ✓ |  |
| J12 | Jump 1 to Jump 2 | Annoying Ass Jump (Left) | Jump 2 (Right) | Nothing. |  | Verified | ✓ |  |
| J12 | Jump 1 to Jump 2 | Jump 2 (Right) | Annoying Ass Jump (Left) | Nothing. |  | Verified | ✓ |  |
| RP | Rosary Pickup | Rosary Necklace | Jump 2 (Right) | (Sprint AND (Clawline OR (Faydown Cloak AND Drifter's Cloak))) |  | Verified | ✓ |  |
| J2S | Jump 2 to Stuff | Jump 2 (Left) | Room With Stuff | Nothing. |  | Verified | ✓ |  |
| J2S | Jump 2 to Stuff | Room With Stuff | Jump 2 (Left) | Nothing. |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Whispering Vaults: Flip Switch #6 | Room With Stuff | Nothing. |  | Verified | switch | ✓ |  |
| 2 | Whispering Vaults: Heavy Rosary Necklace #1 | Rosary Necklace | Nothing. |  | Verified | resource | ✓ |  |
| 3 | Whispering Vaults: Psalm Cylinder #2 | Room With Stuff | Nothing. |  | Verified | collectible | ✓ |  |
| 4 | import enemies |  |  | TODO | Needs verification |  |  |  |

## Room Images

### Connections

[![Connections for Whispering Vaults Jumps (Library_09)](../00-annotations/whispering-vaults/whispering-vaults-jumps-connections.png)](../00-annotations/whispering-vaults/whispering-vaults-jumps-connections.png)

### Checks

[![Checks for Whispering Vaults Jumps (Library_09)](../00-annotations/whispering-vaults/whispering-vaults-jumps-checks.png)](../00-annotations/whispering-vaults/whispering-vaults-jumps-checks.png)

### Scene

[![Scene for Whispering Vaults Jumps (Library_09)](../00-annotations/whispering-vaults/whispering-vaults-jumps-scene.png)](../00-annotations/whispering-vaults/whispering-vaults-jumps-scene.png)
