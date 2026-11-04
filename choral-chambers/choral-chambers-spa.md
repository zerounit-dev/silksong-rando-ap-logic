# Choral Chambers Spa (Song_10)

**Game ID:** Song_10

**Contributors:** samupo, Gallos

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | Lower Showers | ✓ |
| S2 | High Showers | ✓ |
| S3 | Spa | ✓ |
| S4 | Entrance | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| L | left1 | Lower Showers | [Choral Chambers Outside Spa (Song_04)](choral-chambers-outside-spa.md) | R2 | none |  | Verified | ✓ |  |
| R | right1 | Spa | [Choral Chambers Flea Shaft (Song_11)](choral-chambers-flea-shaft.md) | BLB | activate Spa - Lever Chambers 2 |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| V1 | Vertical | Entrance | High Showers | ledge grab right OR easy shaman pogo OR faydown cloak OR cling grip right OR easy [voltvessels,plasmium] stall OR (easy [flea brew, rune rage, heal] stall AND easy beast pogo) OR easy scuttlebrace |  | Verified | ✓ |  |
| V1 | Vertical | High Showers | Entrance | none |  | Verified | ✓ |  |
| V2 | Vertical2 | Entrance | Lower Showers | activate Spa block |  | Verified | ✓ | falling |
| V2 | Vertical2 | Lower Showers | Entrance | activate Spa block AND (cling grip either OR silk soar OR easy scuttlebrace) |  | Verified | ✓ |  |
| H | Horizontal | High Showers | Spa | activate Spa - Lever Chambers  AND (easy scuttlebrace OR ledge grab either OR easy shaman pogo OR faydown cloak OR (cling grip right AND (architect attack right OR easy beast pogo)) OR easy plasmium stall OR cling grip left OR medium voltvessels stall OR (easy [flea brew, rune rage, heal] stall AND easy beast pogo)) |  | Verified | ✓ |  |
| H | Horizontal | Spa | High Showers | activate Spa - Lever Chambers |  | Verified | ✓ | lever shortcut |
| V3 | lower to spa | Lower Showers | Spa | cling grip either OR silk soar OR easy scuttlebrace |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Spa - Lever Chambers | Spa | none |  | Verified | switch | ✓ |  |
| 2 | Spa - Lever Chambers 2 | Spa | none |  | Verified | switch | ✓ |  |
| 3 | Spa - bench | High Showers | none |  | Verified | bench | ✓ |  |
| 4 | Spa - block | High Showers | attack either AND clear Spa - Breakable wall |  | Verified | resource | ✓ |  |
| 5 | Spa - Breakable wall | High Showers | break wall left |  | Verified | blockade | ✓ |  |

## Room Images

### Connections

[![Connections for Choral Chambers Spa (Song_10)](../00-annotations/choral-chambers/choral-chambers-spa-connections.png)](../00-annotations/choral-chambers/choral-chambers-spa-connections.png)

### Checks

[![Checks for Choral Chambers Spa (Song_10)](../00-annotations/choral-chambers/choral-chambers-spa-checks.png)](../00-annotations/choral-chambers/choral-chambers-spa-checks.png)

### Scene

[![Scene for Choral Chambers Spa (Song_10)](../00-annotations/choral-chambers/choral-chambers-spa-scene.png)](../00-annotations/choral-chambers/choral-chambers-spa-scene.png)
