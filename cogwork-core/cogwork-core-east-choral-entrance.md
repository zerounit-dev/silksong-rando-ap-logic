# Cogwork Core East Choral Entrance (Cog_06)

**Game ID:** Cog_06

**Contributors:** Rebel

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | Left Side | ✓ |
| S2 | Right Side | ✓ |
| S3 | Right Exit | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| R | right1 | Right Exit | [Rotating Tunnel (Song_20b)](../choral-chambers/rotating-tunnel.md) | LH | none |  | Verified | ✓ |  |
| L | left2 | Left Side | [Cogwork Core South Main (Cog_04)](cogwork-core-south-main.md) | MR | Nothing |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| J | Jump | Left Side | Right Side | Spike Pogo OR (Clawline AND (Drifter's Cloak OR Faydown Cloak OR (Faydown Cloak AND Swift Step 2 AND (Drifter's Cloak OR Spike Pogo)))) |  | Verified | ✓ |  |
| J | Jump | Right Side | Left Side | Spike Pogo OR (Clawline AND (Drifter's Cloak OR Faydown Cloak OR (Faydown Cloak AND Swift Step 2 AND (Drifter's Cloak OR Spike Pogo)))) |  | Verified | ✓ |  |
| D | Door | Right Side | Right Exit | Activate Cogwork Core Right Entrance Door Switch |  | Verified | ✓ |  |
| D | Door | Right Exit | Right Side | Activate Cogwork Core Right Entrance Door Switch |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Cogwork Core Right Entrance Door Switch | Right Side | Flip Switch Up |  | Verified | switch | ✓ |  |
| 2 | import enemies |  |  | TODO | Needs verification |  |  |  |

## Room Images

### Connections

[![Connections for Cogwork Core East Choral Entrance (Cog_06)](../00-annotations/cogwork-core/cogwork-core-east-choral-entrance-connections.png)](../00-annotations/cogwork-core/cogwork-core-east-choral-entrance-connections.png)

### Checks

[![Checks for Cogwork Core East Choral Entrance (Cog_06)](../00-annotations/cogwork-core/cogwork-core-east-choral-entrance-checks.png)](../00-annotations/cogwork-core/cogwork-core-east-choral-entrance-checks.png)

### Scene

[![Scene for Cogwork Core East Choral Entrance (Cog_06)](../00-annotations/cogwork-core/cogwork-core-east-choral-entrance-scene.png)](../00-annotations/cogwork-core/cogwork-core-east-choral-entrance-scene.png)
