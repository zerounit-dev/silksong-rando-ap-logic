# Greymoor West Bellshrine Room  (Greymoor_01)

**Game ID:** Greymoor_01

**Contributors:** isssma

## Subrooms

- main path
- middle section left
- middle section right
- upper path right
- upper path left

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| TL | top left | upper path left | greymoor upper halfway home path | R | Ledge grab OR cling grip OR enemy pogo OR faydown cloak OR scuttlebrace OR (progressive swftstep 1 AND claw line OR sharpdart) OR silk soar |  | Verified |  |
| TR | top right | upper path right | greymoor east bellshrine room | BL | cling grip OR progressive swift step 1 OR faydown cloak OR silk soar OR clawline OR sharp dart OR (drifter cloak AND ledge grab) |  | Verified |  |
| LR | lower right | main path | greymoor east bellshrine room | LSL | IF (lever switch was activated) => ledge grab OR Shaman crest OR faydown cloak OR silk soar |  | Verified |  |
| LL | lower left | main path | [Greymoor Lower Halfway Home Path (Greymoor_13)](greymoor-lower-halfway-home-path.md) | R | none |  | Verified |  |
| MR | middle right | middle section right | [Greymoor Bellshrine (Bellshrine_02)](greymoor-bellshrine.md) | L | Bellshrine: Greymoor check |  | Verified |  |
| D | down | main path | TODO |  | Enter from far fields using drifter cloak |  | Verified |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LS | Lever Switch | main path | middle section right | cling grip OR silk soar OR (lever switch AND (faydown cloak OR ledge grab OR shaman crest pogo)) |  | Verified |  |
| LS | Lever Switch | middle section right | main path | none (Switch is on this sidel) |  | Verified | the switch can be missed and fall to Main Pathway |
| P | Platform | middle section left | upper path right | ledge grab OR faydown cloak OR silk soar OR shaman crest pogo OR cling grip |  | Verified | the platform can be missed and fall to main pathway |
| P | Platform | upper path right | middle section left | none (can fall to reach it) |  | Verified | the platform can be missed and fall to main pathway |
| F1 | Fall 1 | middle section right | upper path right | Silk soar |  | Verified |  |
| F1 | Fall 1 | upper path right | middle section right | none (can fall to reach it) |  | Verified |  |
| BG | Big Gap | middle section right | middle section left | progressive swift step 1 AND clawline AND drifter cloak AND faydown cloak |  | Verified |  |
| BG | Big Gap | middle section left | middle section right | progressive swift step 1 AND clawline AND drifter cloak AND faydown cloak |  | Verified |  |
| G | Gap | upper path right | upper path left | faydown cloak OR OR drifter cloak OR flea brew OR progressive swift step 1 OR clawline OR sharpdart OR scuttlebrace |  | Verified |  |
| G | Gap | upper path left | upper path right | ledge grab OR enemy pogo OR progressive swift step 1 OR clawline OR sharpdart OR faydown cloak OR beast crest pogo OR shaman crest pogo |  | Verified |  |
| F2 | Fall 2 | middle section right | main path | none (can fall to reach it) |  | Verified |  |
| F2 | Fall 2 | main path | middle section right | silk soar |  | Verified |  |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Greymoor #1 - Rosary Cache | middle section left | Silk soar OR none OR (progressive swift step 1 AND faydown cloak AND clawline AND drifter cloak) |  | Verified | Not included | it really dpeends a lot from the entrance to the room to define the requirements so i placed subroom transitions that matter |
| lever switch | middle section right | silk soar OR cling grip |  | Verified | Not included | this drops down a platform that alters subroom connection LS and room connection LR |
