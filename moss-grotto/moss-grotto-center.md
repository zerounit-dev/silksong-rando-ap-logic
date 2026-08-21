# Moss Grotto Center (Tut_01)

**Game ID:** Tut_01

**Contributors:** herounit, super epicguy

## Subrooms

- rock bottom
- upper crossing
- center shaft
- side room
- lower crossing
- up and away

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LL | lower left | rock bottom | [Moss Grotto West (Tut_02)](moss-grotto-west.md) | LR | break vines |  |  |  |
| ML | middle left | lower crossing | [Moss Grotto West (Tut_02)](moss-grotto-west.md) | UR | none |  |  |  |
| UL | upper left | upper crossing | [Ruined Chapel (Tut_03)](ruined-chapel.md) | R | break vines |  |  |  |
| LR | lower right | lower crossing | [Moss Grotto East (Tut_01b)](moss-grotto-east.md) | LL | none |  |  |  |
| UR | upper right | upper crossing | [Moss Grotto East (Tut_01b)](moss-grotto-east.md) | UL | none |  |  |  |
| C | ceiling | up and away | [Bone Bottom Town (Bonetown)](../bone-bottom/bone-bottom-town.md) | RF | has loading zone blocker until you first leave moss grotto |  |  | maybe see if removing this loading zone makes sense? |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| S1 | shaft 1 | up and away | upper crossing | none (falling) |  |  |  |
| S1 | shaft 1 | upper crossing | up and away | silk soar OR ( cling grip AND ( easy skips OR faydown cloak OR run OR dash OR sharpdart OR clawline) OR (scuttlebrace AND dash) |  |  | Easy skip is a heal boost or a reverse dslash boost with Shaman's |
| S2 | shaft 2 | upper crossing | center shaft | none (falling) |  |  |  |
| S2 | shaft 2 | center shaft | upper crossing | silk soar OR cling grip OR (dash AND scuttlebrace) |  |  |  |
| SV | side room vines | center shaft | side room | break vines |  |  |  |
| SV | side room vines | side room | center shaft | break vines |  |  |  |
| S3 | shaft 3 | center shaft | lower crossing | none (falling) |  |  |  |
| S3 | shaft 3 | lower crossing | center shaft | silk soar OR cling grip OR (scuttlebrace AND dash AND (sharpdart OR clawline OR faydown cloak) AND easy skips) |  |  |  |
| S4 | shaft 4 | lower crossing | rock bottom | none (falling) |  |  |  |
| S4 | shaft 4 | rock bottom | lower crossing | silk soar OR ( cling grip AND faydown cloak ) OR (scuttlebrace AND dash AND faydown cloak AND ((drifters cloak AND ledge grab) OR clawline OR sharpdart) AND easy skips) |  |  |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| frayed rosary string moss grotto | rock bottom | none |  | Verified | Included |  |
| shell shard cache moss grotto 1 | lower crossing | none |  |  | Included |  |
| moss grotto beast shard | rock bottom | none |  |  | Not included | NOT YET RANDOMIZED  right at game start jump into right room and again into right into upper right room |
| moss grotto rosary chest | side room | none |  |  | Not included | NOT YET RANDOMIZED |

## Notes

renamed from "moss grotto west" - was mistakenly marked as same room as west room
not having the west part as part of this area causes the graph to be more complex
