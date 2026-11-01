# Sinner's Road Vertical Hall West (Dust_02)

**Game ID:** Dust_02

**Contributors:** herchey's going to bed

## Subrooms

| No. | Subroom | Annotated |
| --- | --- | --- |
| S1 | basement | ✓ |
| S2 | lower | ✓ |
| S3 | middle right | ✓ |
| S4 | middle left | ✓ |
| S5 | upper right | ✓ |
| S6 | top | ✓ |
| S7 | rosary cage | ✓ |
| S8 | lever room | ✓ |
| S9 | above lever | ✓ |

## Room Transitions

| Alias | Name | From subroom | Destination | Destination alias | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| LL | lower left | lower | [Sinner's Road Entrance (Dust_01)](sinner-s-road-entrance.md) | R | none |  | Verified | ✓ |  |
| ML | middle left | middle left | [Sinner's Road Bench (Dust_10)](sinner-s-road-bench.md) | R | none |  | Verified | ✓ |  |
| C | ceiling | top | [Sinner's Road North Hall (Dust_05)](sinner-s-road-north-hall.md) | C | none |  | Verified | ✓ |  |
| LR | lower right | lower | [Sinner's Road Muckroach Cages (Dust_03)](sinner-s-road-muckroach-cages.md) | L | none |  | Verified | ✓ |  |
| MR | middle right | middle right | [Sinner's Road Hanging Cages (Dust_04)](sinner-s-road-hanging-cages.md) | LL | none |  | Verified | ✓ |  |
| UR | upper right | upper right | [Sinner's Road Hanging Cages (Dust_04)](sinner-s-road-hanging-cages.md) | UL | prereq Upper Entry Switch IN Sinner's Road Hanging Cages |  | Verified | ✓ |  |

## Subroom Connections

| Alias | Name | Source | Destination | Requirements | TODO | Verification | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| BL | basement to lower | lower | basement | none |  | Verified | ✓ | Technically "any attack" is a requirement |
| BL | basement to lower | basement | lower | cling grip right OR (faydown cloak AND cling grip left) |  | Verified | ✓ |  |
| LMR | low to mid right | lower | middle right | silk soar OR (Cling grip right AND ledge grab left) OR  (faydown cloak AND (cling grip left OR scuttlebrace)) OR  cling grip both |  | Verified | ✓ |  |
| LMR | low to mid right | middle right | lower | none |  | Verified | ✓ |  |
| MRL | mid right to upper right | middle right | upper right | silk soar OR (complete Lever That Gets You A Shortcut To The Bullshit Bench Door AND (cling grip either OR (faydown cloak AND ledge grab either))) |  | Verified | ✓ |  |
| MRL | mid right to upper right | upper right | middle right | none |  | Verified | ✓ |  |
| LUR | mid left to upper right | middle left | upper right | Cling grip right OR faydown cloak |  | Verified | ✓ |  |
| LUR | mid left to upper right | upper right | middle left | none |  | Verified | ✓ |  |
| URT | upper right to top | upper right | top | Silk soar |  | Verified | ✓ |  |
| URT | upper right to top | top | upper right | none |  | Verified | ✓ |  |
| MRR | mid right to rosaries | middle right | rosary cage | silk soar |  | Verified | ✓ |  |
| MRR | mid right to rosaries | rosary cage | middle right | none |  | Verified | ✓ |  |
| MLR | mid left to rosaries | middle left | rosary cage | faydown cloak OR cling grip right OR (scuttlebrace AND proficient movement) |  | Verified | ✓ |  |
| MLR | mid left to rosaries | rosary cage | middle left | faydown cloak OR cling grip either |  | Verified | ✓ |  |
| TL | top to lever | top | above lever | none |  | Verified | ✓ |  |
| TL | top to lever | above lever | top | silk soar OR (cling grip right AND (faydown cloak OR drifter's cloak OR (dash left AND proficient movement) OR (dash left AND ledge grab left) OR sharpdart OR clawline left OR easy beast pogo)) |  | Verified | ✓ |  |
| LR | lever room | above lever | lever room | none |  | Verified | ✓ |  |
| LR | lever room | lever room | above lever | silk soar OR cling grip either OR scuttlebrace |  | Verified | ✓ |  |
| URL | upper right to lever | upper right | above lever | cling grip right OR scuttlebrace |  | Verified | ✓ |  |
| URL | upper right to lever | above lever | upper right | none |  | Verified | ✓ |  |

## Check Locations

| No. | Check | Subroom | Requirements | TODO | Verification | Location Type | Annotated | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Gross Rosaries In the Sinner's Basement | basement | (swim AND (Ledge grab left OR cling grip left))  OR  (faydown cloak AND ((drifter's cloak AND ledge grab left) OR clawline left OR sharpdart OR swim)) OR (clawline left AND (drifter's cloak AND ledge grab left)) |  | Verified | collectible | ✓ | Formerly: Rosary Cache: Sinner’s Road #1 |
| 2 | First Half of the Rosaries They Took From the Gay Frog When They Put Him In Prison | rosary cage | none |  | Verified | collectible | ✓ | Formerly: Rosary Cache: Sinner’s Road #2 |
| 3 | Second Half of the Rosaries They Took From the Gay Frog When They Put Him In Prison | rosary cage | none |  | Verified | collectible | ✓ | Formerly: Rosary Cache: Sinner’s Road #3 |
| 4 | Lever That Gets You A Shortcut To The Bullshit Bench Door | lever room | flip switch either |  | Verified | lock | ✓ |  |
| 5 | Amy, the Roachcatcher | middle right | none |  | Verified | enemy | ✓ | Formerly: Roachcatcher 1 |
| 6 | Puddles, the Mite | basement | none |  | Verified | enemy | ✓ | Formerly: Mite 1 |
| 7 | Dickson, the Roachfeeder | top | Normal World Spawn |  | Verified | enemy | ✓ | Formerly: Roachfeeder 1 |
| 8 | Liam, the Roachfeeder | rosary cage | Normal World Spawn |  | Verified | enemy | ✓ | Formerly: Roachfeeder 2 |
| 9 | Aiden, the Roachfeeder | rosary cage | Black Thread World Spawn |  | Verified | enemy | ✓ | Formerly: Roachfeeder 3 |
| 10 | Creed, the Roachfeeder | upper right | Black Thread World Spawn |  | Verified | enemy | ✓ | Formerly: Roachfeeder 4 |

## Room Images

### Connections

[![Connections for Sinner's Road Vertical Hall West (Dust_02)](../00-annotations/sinner-s-road/sinner-s-road-vertical-hall-west-connections.png)](../00-annotations/sinner-s-road/sinner-s-road-vertical-hall-west-connections.png)

### Checks

[![Checks for Sinner's Road Vertical Hall West (Dust_02)](../00-annotations/sinner-s-road/sinner-s-road-vertical-hall-west-checks.png)](../00-annotations/sinner-s-road/sinner-s-road-vertical-hall-west-checks.png)

### Scene

[![Scene for Sinner's Road Vertical Hall West (Dust_02)](../00-annotations/sinner-s-road/sinner-s-road-vertical-hall-west-scene.png)](../00-annotations/sinner-s-road/sinner-s-road-vertical-hall-west-scene.png)
