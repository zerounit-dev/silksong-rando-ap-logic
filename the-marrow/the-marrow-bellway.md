# The Marrow Bellway (Bone_05)

**Game ID:** Bone_05

## Subrooms

- left area
- boss room
- right area

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left | left area | [Mosshome Middle (Mosstown_01)](../bone-bottom/mosshome-middle.md) | LR | none |  |  |  |
| F | floor | left area | [The Marrow Shakra Intro (Bone_04)](the-marrow-shakra-intro.md) | C | none |  |  |  |
| R | right | right area | [The Marrow Bellshrine (Bellshrine)](the-marrow-bellshrine.md) | L | none |  |  |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| LB | left boss fight | left area | boss room | none |  |  |  |
| LB | left boss fight | boss room | left area | none |  |  | boss fight doesn't start automatically so can leave any time |
| RB | right boss fight | right area | boss room | bell beast defeated |  |  | can't enter the arena from this side |
| RB | right boss fight | boss room | right area | bell beast defeated |  |  | bell beast defeated needs to be here to gate this from seemingly like a straight passthrough |

## Check Locations

| Check | Subroom | Requirements | TODO | Verification | Archipelago | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| bell beast boss fight | boss room | silk spear |  |  | Included | sharpdart doesn't work |
| silk heart bell beast | boss room | bell beast defeated |  |  | Included |  |
