# Greymoor Eastern Tower (Greymoor_04)

**Game ID:** Greymoor_04

**Contributors:** Isssma

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | arena encounter | ✓ |
| S2 | middle section | ✓ |
| S3 | lower airstream section | ✓ |
| S4 | upper section | ✓ |
| S5 | tower top | ✓ |
| S6 | upper airstream section | ✓ |
| S7 | silly platform | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LR | lower right | arena encounter | [Greymoor Halfway Home Exterior (Greymoor_03)](greymoor-halfway-home-exterior.md) | LL | clear Greymoor Tower Gaunlet |  | Verified | ✓ |  |
| LL | lower left | arena encounter | [Greymoor Towers Patio (Greymoor_05)](greymoor-towers-patio.md) | MR | clear Greymoor Tower Gaunlet |  | Verified | ✓ |  |
| MR | middle right | middle section | [Greymoor Halfway Home Exterior (Greymoor_03)](greymoor-halfway-home-exterior.md) | ML | nothing |  | Verified | ✓ |  |
| ML | middle left | middle section | [Greymoor Middle Passage (Greymoor_10)](greymoor-middle-passage.md) | R | nothing |  | Verified | ✓ |  |
| UL | upper left | tower top | [Greymoor Upper Towers Path (Greymoor_11)](greymoor-upper-towers-path.md) | R | nothing |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| F1 | fall 1 | arena encounter | lower airstream section | silk soar |  | Verified | ✓ |  |
| F1 | fall 1 | lower airstream section | arena encounter | nothing (just fall) |  | Verified | ✓ |  |
| S1 | shaft 1 | lower airstream section | middle section | silk soar OR (activate lower airstream AND drifters cloak) OR (easy pogo off fluttermite AND (faydown cloak OR ledge grab left OR ledge grab right)) |  | Verified | ✓ |  |
| S1 | shaft 1 | middle section | lower airstream section | nothing (just fall) |  | Verified | ✓ |  |
| S2 | shaft 2 | middle section | upper section | silk soar OR (drifters cloak  AND (activate lower airstream OR (faydown cloak AND (ledge grab right OR cling grip either OR easy scuttlebrace))) AND activate middle airstream) OR (faydown cloak AND (cling grip left OR easy scuttlebrace) AND progressive swift step 1 AND (clawline right x 1 OR sharpdart x 1)) |  | Verified | ✓ |  |
| S2 | shaft 2 | upper section | middle section | nothing (just fall) |  | Verified | ✓ |  |
| PG1 | platform gap 1 | upper section | upper airstream section | nothing (just fall) |  | Verified | ✓ |  |
| PG1 | platform gap 1 | upper airstream section | upper section | ledge grab right OR cling grip right OR faydown cloak OR silk soar OR (medium pogo off silk snipper) |  | Verified | ✓ |  |
| S3 | shaft 3 | upper section | tower top | (proficient movement AND spike pogo) OR silk soar OR ((drifters cloak AND (spike pogo OR ledge grab left OR faydown cloak OR cling grip left)) AND activate upper airstream) |  | Verified | ✓ |  |
| S3 | shaft 3 | tower top | upper section | none (just fall) |  | Verified | ✓ |  |
| F2 | fall 2 | arena encounter | silly platform | (easy shaman pogo AND ledge grab left) OR silk soar |  | Verified | ✓ |  |
| F2 | fall 2 | silly platform | arena encounter | nothing |  | Verified | ✓ |  |
| PG2 | platform gap 2 | silly platform | lower airstream section | (ledge grab right AND (faydown cloak OR cling grip right)) OR silk soar OR (faydown cloak AND ledge grab right) |  | Verified | ✓ |  |
| PG2 | platform gap 2 | lower airstream section | silly platform | nothing |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Greymoor - Rosary Cache next to the lowest airstream | lower airstream section | nothing |  | Verified | resource | ✓ |  |
| 2 | Greymoor - Silkeater | tower top | silk soar OR (proficient movement AND spike pogo) OR (drifters cloak AND (spike pogo OR faydown cloak OR ((clawline left x 1 OR sharpdart x 1) AND ledge grab left)) AND activate top airstream) |  | Verified | collectible | ✓ |  |
| 3 | Greymoor Tower Gaunlet | arena encounter | Combat Requirements |  | Verified | gauntlet | ✓ | THe enemy souls required are: dregt catcher and thread raker plus a roachcatcher for the act 3 version |
| 4 | lower airstream | lower airstream section | hit lever right OR hit lever up OR hit lever down |  | Verified | switch | ✓ |  |
| 5 | middle airstream | middle section | ((drifters cloak AND activate lower airstream) OR ledge grab left OR ledge grab right OR cling grip left OR cling grip right OR silk soar OR faydown cloak) AND (hit lever right OR hit lever up OR hit lever left) |  | Verified | switch | ✓ |  |
| 6 | upper airstream | upper airstream section | hit lever right OR hit lever down |  | Verified | switch | ✓ |  |
| 7 | top airstream | tower top | (hit lever right OR hit lever up OR hit lever left) AND ((activate upper airstream AND drifters cloak) OR (proficient movement AND spike pogo)) |  | Verified | switch | ✓ |  |
| 8 | Silk Snipper 1 | upper section | nothing |  | Verified | enemy | ✓ | spawns in the subroom bellow but he instantly agros and goes inside upper section sub room |
| 9 | Fluttermite 1 | lower airstream section | Normal World Spawn |  | Verified | enemy | ✓ |  |
| 10 | Fluttermite 2 | lower airstream section | Normal World Spawn |  | Verified | enemy | ✓ |  |
| 11 | Dreg Catcher 1 | arena encounter | Normal World Spawn |  | Verified | enemy | ✓ |  |
| 12 | Dreg Catcher 2 | arena encounter | Normal World Spawn |  | Verified | enemy | ✓ |  |
| 13 | Thread Raker 1 | arena encounter | Normal World Spawn |  | Verified | enemy | ✓ |  |
| 14 | Dreg Catcher 3 | arena encounter | Black Thread World Spawn |  | Verified | enemy | ✓ |  |
| 15 | Dreg Catcher 4 | arena encounter | Black Thread World Spawn |  | Verified | enemy | ✓ |  |
| 16 | Roachcatcher 1 | arena encounter | Black Thread World Spawn |  | Verified | enemy | ✓ |  |
| 17 | Dreg Catcher 5 | arena encounter | Black Thread World Spawn |  | Verified | enemy | ✓ |  |
| 18 | Thread Raker 2 | arena encounter | Black Thread World Spawn |  | Verified | enemy | ✓ |  |
| 19 | Thread Raker 3 | arena encounter | Black Thread World Spawn |  | Verified | enemy | ✓ |  |

## Room Images

### Connections

[![Connections for Greymoor Eastern Tower (Greymoor_04)](../00-annotations/greymoor/greymoor-eastern-tower-connections.png)](../00-annotations/greymoor/greymoor-eastern-tower-connections.png)

### Checks

[![Checks for Greymoor Eastern Tower (Greymoor_04)](../00-annotations/greymoor/greymoor-eastern-tower-checks.png)](../00-annotations/greymoor/greymoor-eastern-tower-checks.png)

### Scene

[![Scene for Greymoor Eastern Tower (Greymoor_04)](../00-annotations/greymoor/greymoor-eastern-tower-scene.png)](../00-annotations/greymoor/greymoor-eastern-tower-scene.png)
