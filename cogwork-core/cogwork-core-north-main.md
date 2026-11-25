# Cogwork Core North Main (Cog_08)

**Game ID:** Cog_08

**Contributors:** Rebel, Gallos

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | Lower Entrance | ✓ |
| S2 | First safe platform | ✓ |
| S3 | Second safe platform | ✓ |
| S4 | third safe platform | ✓ |
| S5 | fourth safe platform | ✓ |
| S6 | fifth safe platform | ✓ |
| S7 | Upper Entrance | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| B | bot1 | Lower Entrance | [Cog Dancers (Cog_Dancers)](cog-dancers.md) | T | none |  | Verified | ✓ |  |
| T | top1 | Upper Entrance | [Cogwork Core Architect's Melody (Cog_09)](cogwork-core-architect-s-melody.md) | B | cling grip left OR easy scuttlebrace OR faydown OR (easy shaman pogo AND hard pale nails stall) OR silk soar |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LF | lower <> First | Lower Entrance | First safe platform | ((clawline right OR (medium [reaper, architect,shaman] pogo AND spike pogo)) AND (ledge grab right OR cling grip right) AND (clawline left OR sharpdart OR ledge grab left OR easy beast pogo OR easy [flea brew, voltvessels,plasmium ] stall OR easy shaman scuttle slide)) OR (proficient movement AND medium shaman pogo) OR (faydown AND spike pogo) |  | Verified | ✓ |  |
| LF | lower <> First | First safe platform | Lower Entrance | spike pogo OR easy naked pogo |  | Verified | ✓ |  |
| FS | first <> second | First safe platform | Second safe platform | easy [beast,reaper, shaman] pogo  OR (faydown AND spike pogo) OR (spike pogo AND cling grip either AND (dash left OR clawline left OR sharpdart)) OR (hard Silk Soar Cancel AND (clawline left OR dash left OR sharpdart)) |  | Verified | ✓ |  |
| FS | first <> second | Second safe platform | First safe platform | spike pogo OR easy naked pogo |  | Verified | ✓ |  |
| ST | second <> third | Second safe platform | third safe platform | (easy shaman pogo AND spike pogo AND (faydown OR clawline left OR (clawline right AND (ledge grab left OR proficient movement)) OR (medium shaman scuttle slide AND proficient movement))) OR (spike pogo AND faydown) OR (clawline both AND cling grip both) |  | Verified | ✓ |  |
| V1 | fourth to first | fourth safe platform | First safe platform | none |  | Verified | ✓ |  |
| V2 | fourth to second | fourth safe platform | Second safe platform | activate Cogwork Core: North switch AND (spike pogo OR proficient movement OR drifters) |  | Verified | ✓ |  |
| V2 | fourth to second | Second safe platform | fourth safe platform | (easy Silk Soar Cancel AND elite ball knowledge) |  | Verified | ✓ |  |
| TF | third to fourth | third safe platform | fourth safe platform | spike pogo AND (easy shaman pogo OR ledge grab right OR cling grip right OR faydown OR easy silk soar cancel OR (cling grip left AND (dash right OR clawline right OR sharpdart))) |  | Verified | ✓ |  |
| TF | third to fourth | fourth safe platform | third safe platform | none |  | Verified | ✓ |  |
| FU | fourth to upper | fourth safe platform | Upper Entrance | (activate Cogwork Core: North switch AND ((easy shaman pogo AND spike pogo AND (faydown OR (clawline right AND medium shaman scuttle slide AND dash left))) OR (medium silk soar cancel AND proficient movement AND spike pogo) OR (medium reaper pogo AND faydown AND spike pogo))) OR (easy shaman pogo AND faydown AND spike pogo AND easy pogo off [cogwork cleanser, cogwork defender]) |  | Verified | ✓ |  |
| FU | fourth to upper | Upper Entrance | fourth safe platform | spike pogo OR medium naked pogo |  | Verified | ✓ |  |
| FF | fourth to fifth | fourth safe platform | fifth safe platform | (((clawline both AND cling grip both AND spike pogo) OR (cling grip right AND faydown)) AND activate Cogwork Core: North switch) OR easy silk soar cancel |  | Verified | ✓ |  |
| FF | fourth to fifth | fifth safe platform | fourth safe platform | none |  | Verified | ✓ |  |
| LU | fifth to upper | fifth safe platform | Upper Entrance | (cling grip left AND clawline either x 3 AND faydown AND spike pogo) OR (clawline both x 4 AND cling grip both AND spike pogo) OR  (clawline both x 9 AND proficient movement AND spike pogo) OR (clawline either x 4 AND faydown AND spike pogo AND easy pogo off cogwork spine) OR (medium beast pogo AND faydown AND spike pogo) OR (run AND dash both AND faydown AND spike pogo) OR (hard shaman scuttle slide AND spike pogo AND proficient movement) |  | Verified | ✓ |  |
| LU | fifth to upper | Upper Entrance | fifth safe platform | spike pogo AND (clawline right x 2 OR drifters OR faydown) |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Cogwork Core: North switch | fourth safe platform | attack up |  | Verified | switch | ✓ |  |
| 2 | Cogwork Crawler 1 | third safe platform | none |  | Verified | enemy | ✓ |  |
| 3 | Cogwork Crawler 2 | Upper Entrance | none |  | Verified | enemy | ✓ |  |
| 4 | Cogwork Crawler 3 | First safe platform | none |  | Verified | enemy | ✓ |  |
| 5 | Cogwork Cleanser 1 | First safe platform | none |  | Verified | enemy | ✓ |  |
| 6 | Cogwork Spine 1 | Upper Entrance | none |  | Verified | enemy | ✓ |  |
| 7 | Cogwork Spine 2 | First safe platform | none |  | Verified | enemy | ✓ |  |
| 8 | Cogwork Defender 1 | fourth safe platform | none |  | Verified | enemy | ✓ |  |
| 9 | Cogwork Spine 3 | fourth safe platform | none |  | Verified | enemy | ✓ |  |
| 10 | Cogwork Choirbug 1 | First safe platform | none |  | Verified | enemy | ✓ |  |
| 11 | Cogwork Cleanser 2 | fourth safe platform | none |  | Verified | enemy | ✓ |  |
| 12 | Cogwork Spine 4 | First safe platform | none |  | Verified | enemy | ✓ |  |

## Notes

enemies will be done later; this is just to fix the current logic connections.

## Room Images

### Connections

[![Connections for Cogwork Core North Main (Cog_08)](../00-annotations/cogwork-core/cogwork-core-north-main-connections.png)](../00-annotations/cogwork-core/cogwork-core-north-main-connections.png)

### Checks

[![Checks for Cogwork Core North Main (Cog_08)](../00-annotations/cogwork-core/cogwork-core-north-main-checks.png)](../00-annotations/cogwork-core/cogwork-core-north-main-checks.png)

### Scene

[![Scene for Cogwork Core North Main (Cog_08)](../00-annotations/cogwork-core/cogwork-core-north-main-scene.png)](../00-annotations/cogwork-core/cogwork-core-north-main-scene.png)
