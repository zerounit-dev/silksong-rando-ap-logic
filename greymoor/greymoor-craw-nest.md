# Greymoor Craw Nest (Room_CrowCourt)

**Game ID:** Room_CrowCourt

**Contributors:** Isssma

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | craw lower nest | ✓ |
| S2 | craw arena | ✓ |
| S3 | craw nest entrance | ✓ |
| S4 | balloon control room | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | bottom | craw lower nest | [Greymoor Craw Court (Room_CrowCourt_02)](greymoor-craw-court.md) | T | craw summons ready |  | Verified | ✓ | i can confirm the door stays open even after craw father is defeated |
| L | left | craw nest entrance | [Greymoor Craw Lake (Greymoor_15b)](greymoor-craw-lake.md) | CN | none |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| f1 | fall 1 | craw nest entrance | craw lower nest | none (just fall) |  | Verified | ✓ |  |
| f1 | fall 1 | craw lower nest | craw nest entrance | silk soar OR prereq balloon lever |  | Verified | ✓ |  |
| f2 | fall 2 | craw arena | craw lower nest | none (just fall) |  | Verified | ✓ |  |
| f2 | fall 2 | craw lower nest | craw arena | ledge grab either OR silk soar OR faydown cloak OR easy pogo off mite OR cling grip either |  | Verified | ✓ |  |
| PG1 | platform gap 1 | craw arena | balloon control room | clear Craw Lake Gauntlet AND (easy shaman pogo OR easy reaper pogo OR easy wanderer pogo OR easy hunter pogo OR faydown cloak OR ledge grab either OR silk soar) |  | Verified | ✓ |  |
| PG1 | platform gap 1 | balloon control room | craw arena | clear Craw Lake Gauntlet |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | balloon lever | balloon control room | flip lever up OR flip lever left OR flip lever right |  | Verified | switch | ✓ |  |
| 2 | Greymoor - entrance rosary stash | craw nest entrance | nothing |  | Verified | resource | ✓ |  |
| 3 | Greymoor - entrance food savings | craw nest entrance | nothing |  | Verified | resource | ✓ |  |
| 4 | Greymoor - nest savings at the extreme left | craw lower nest | (faydown cloak AND (progressive swift step 1 left OR sharpdart x 1 OR clawline left x 1)) OR ((ledge grab either OR cling grip either OR easy pogo off mite) AND drifters cloak AND (progressive swift step 2 left OR sharpdart x 1 OR clawline left x 1)) OR prereq balloon lever |  | Verified | resource | ✓ |  |
| 5 | Greymoor - nest savings at the extreme right | craw lower nest | ((ledge grab either OR cling grip either OR easy pogo off mite) AND (progressive swift step 1 left OR sharpdart x 1 OR clawline left x 1)) OR faydown cloak OR prereq balloon lever |  | Verified | resource | ✓ |  |
| 6 | Greymoor - nest mortage at the inner right | craw lower nest | ((ledge grab either OR cling grip either OR easy pogo off mite) AND (progressive swift step 1 left OR sharpdart x 1 OR clawline left x 1)) OR faydown cloak OR prereq balloon lever |  | Verified | resource | ✓ |  |
| 7 | Greymoor - nest mortage at the inner left | craw lower nest | (faydown cloak AND (progressive swift step 1 left OR sharpdart x 1 OR clawline left x 1)) OR ((ledge grab either OR cling grip either OR easy pogo off mite) AND drifters cloak AND (progressive swift step 2 left OR sharpdart x 1 OR clawline left x 1)) OR prereq balloon lever |  | Verified | resource | ✓ |  |
| 8 | Greymoor - some dumb bird life savings left outside in the nest | craw arena | none |  | Verified | resource | ✓ |  |
| 9 | Craw Lake Gauntlet | craw arena | Combat Requirements |  | Verified | gauntlet | ✓ |  |
| 10 | Squatcraw 1 | craw arena | nothing |  | Verified | enemy | ✓ | Spawn conditions: CrowCourtInSession=false |
| 11 | Craw 1 | craw arena | nothing |  | Verified | enemy | ✓ | Spawn conditions: hitCrowCourtSwitch=false |
| 12 | Craw 2 | craw arena | nothing |  | Verified | enemy | ✓ | Spawn conditions: hitCrowCourtSwitch=false |
| 13 | Craw 3 | craw arena | nothing |  | Verified | enemy | ✓ | Spawn conditions: hitCrowCourtSwitch=false |
| 14 | Tallcraw 1 | craw arena | nothing |  | Verified | enemy | ✓ | Spawn conditions: CrowCourtInSession=false |
| 15 | Craw 4 | craw arena | nothing |  | Verified | enemy | ✓ | Spawn conditions: hitCrowCourtSwitch=false |
| 16 | Craw 5 | craw arena | nothing |  | Verified | enemy | ✓ | Spawn conditions: hitCrowCourtSwitch=false |
| 17 | Craw 6 | craw arena | nothing |  | Verified | enemy | ✓ | Spawn conditions: hitCrowCourtSwitch=false |
| 18 | Craw 7 | craw arena | nothing |  | Verified | enemy | ✓ | Spawn conditions: hitCrowCourtSwitch=false |
| 19 | Craw 8 | craw arena | nothing |  | Verified | enemy | ✓ | Spawn conditions: hitCrowCourtSwitch=false |
| 20 | Tallcraw 2 | craw arena | nothing |  | Verified | enemy | ✓ | Spawn conditions: CrowCourtInSession=false |
| 21 | Squatcraw 2 | craw arena | nothing |  | Verified | enemy | ✓ | Spawn conditions: CrowCourtInSession=false |
| 22 | Tallcraw 3 | craw arena | Normal World Spawn |  | Verified | enemy | ✓ | Spawn conditions: CrowCourtInSession=false |
| 23 | Squatcraw 3 | craw arena | Normal World Spawn |  | Verified | enemy | ✓ | Spawn conditions: CrowCourtInSession=false |
| 24 | Mite 1 | craw lower nest | nothing |  | Verified | enemy | ✓ | FSM Boolean flags: CrowCourtInSession |
| 25 | Mite 2 | craw lower nest | nothing |  | Verified | enemy | ✓ | FSM Boolean flags: CrowCourtInSession |
| 26 | Mite 3 | craw lower nest | nothing |  | Verified | enemy | ✓ | FSM Boolean flags: CrowCourtInSession |

## Notes

One of the small craw here is an impostor

## Room Images

### Connections

[![Connections for Greymoor Craw Nest (Room_CrowCourt)](../00-annotations/greymoor/greymoor-craw-nest-connections.png)](../00-annotations/greymoor/greymoor-craw-nest-connections.png)

### Checks

[![Checks for Greymoor Craw Nest (Room_CrowCourt)](../00-annotations/greymoor/greymoor-craw-nest-checks.png)](../00-annotations/greymoor/greymoor-craw-nest-checks.png)

### Scene

[![Scene for Greymoor Craw Nest (Room_CrowCourt)](../00-annotations/greymoor/greymoor-craw-nest-scene.png)](../00-annotations/greymoor/greymoor-craw-nest-scene.png)
