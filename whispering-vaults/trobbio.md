# Trobbio (Library_13)

**Game ID:** Library_13

**Contributors:** Rebel, Gallos

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | Top | ✓ |
| S2 | Top right | ✓ |
| S3 | Bottom Left Entrance | ✓ |
| S4 | Arena | ✓ |
| S5 | Bottom Right | ✓ |
| S6 | Bottom Center | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TR | right1 | Top right | [Trobbio Entrance (Library_13b)](trobbio-entrance.md) | L | Nothing. |  | Verified | ✓ |  |
| L | left1 | Bottom Left Entrance | [Grand Bellway Shaft (Song_20)](../choral-chambers/grand-bellway-shaft.md) | RS | Nothing. |  | Verified | ✓ |  |
| BR | right2 | Bottom Right | [Vaults & Bellway Cauldron Entrance (Library_11)](../underworks/vaults-bellway-cauldron-entrance.md) | TL | Nothing. |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| VR | Vertical Right | Top | Bottom Right | Activate Whispering Vaults: Trobio switch 2 |  | Verified | ✓ |  |
| VR | Vertical Right | Bottom Right | Top | Activate Whispering Vaults: Trobio switch 2 AND (silk soar OR faydown OR ledge grab left  OR medium [shaman,beast] pogo OR cling grip left OR (easy [hunter,wanderer,reaper,architect] pogo AND (clawline left x 2 OR dash left))) |  | Verified | ✓ |  |
| VL | Vertical Left | Top | Bottom Center | Nothing. (Fall) |  | Verified | ✓ |  |
| VL | Vertical Left | Bottom Center | Top | Silk Soar  OR (Faydown Cloak AND (Cling Grip either OR easy Scuttlebrace)) |  | Verified | ✓ |  |
| LL | Leave Left | Bottom Center | Bottom Left Entrance | Activate Whispering Vaults: Trobio switch 1 |  | Verified | ✓ |  |
| LL | Leave Left | Bottom Left Entrance | Bottom Center | Activate Whispering Vaults: Trobio switch 1 |  | Verified | ✓ |  |
| ESL | Enter Stage Left | Bottom Center | Arena | Nothing. |  | Verified | ✓ |  |
| ESL | Enter Stage Left | Arena | Bottom Center | Defeat Trobbio OR (Act 3 AND Defeat Tormented Trobbio) |  | Verified | ✓ |  |
| ESR | Enter Stage Right | Bottom Right | Arena | Nothing. |  | Verified | ✓ |  |
| ESR | Enter Stage Right | Arena | Bottom Right | Defeat Trobbio OR (Act 3 AND Defeat Tormented Trobbio) |  | Verified | ✓ |  |
| TT | top to right | Top | Top right | run  OR silk soar OR dash right OR ledge grab right OR cling grip right OR faydown  OR easy [beast,shaman] pogo OR clawline right OR sharpdart OR easy architect charge OR easy [plasmium,flea brew,voltvessels] stall |  | Verified | ✓ |  |
| TT | top to right | Top right | Top | none |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Whispering Vaults: Trobio lore | Bottom Left Entrance | Nothing. |  | Verified | lore | ✓ | can be missed if you kill trobio first |
| 2 | Progressive Claw Mirror 1 | Arena | Defeat Trobbio |  | Verified | collectible | ✓ |  |
| 3 | Whispering Vaults: Trobio switch 1 | Bottom Center | Nothing. |  | Verified | switch | ✓ |  |
| 4 | Whispering Vaults: Trobio switch 2 | Bottom Right | Nothing. |  | Verified | switch | ✓ |  |
| 5 | AP Minor Cache - Whispering Vaults - Trobio's bone pile | Top | Nothing. |  | Verified | collectible | ✓ |  |
| 6 | Pain, Anguish and Misery Wish Granted | Arena | Defeat Tormented Trobbio |  | Verified | event | ✓ |  |
| 7 | Progressive Claw Mirror 2 | Arena | Defeat Tormented Trobbio |  | Verified | collectible | ✓ |  |
| 8 | Trobbio | Arena | Combat Requirements |  | Verified | boss | ✓ |  |
| 9 | Tormented Trobbio | Arena | complete THE Pain Anguish and Misery Wish Promised AND defeat Trobbio AND Act 3 AND Combat Requirements |  | Verified | boss | ✓ |  |

## Room Images

### Connections

[![Connections for Trobbio (Library_13)](../00-annotations/whispering-vaults/trobbio-connections.png)](../00-annotations/whispering-vaults/trobbio-connections.png)

### Checks

[![Checks for Trobbio (Library_13)](../00-annotations/whispering-vaults/trobbio-checks.png)](../00-annotations/whispering-vaults/trobbio-checks.png)

### Scene

[![Scene for Trobbio (Library_13)](../00-annotations/whispering-vaults/trobbio-scene.png)](../00-annotations/whispering-vaults/trobbio-scene.png)
