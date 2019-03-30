# Description

Small repository for hosting background pictures for Cisco SPA300- and SPA500-series IP telephones.

# File Requirements

| Parameter | Requirement |
| --- | --- |
| Format | BMP |
| Bit Depth | 1 |
| Canvas Dimensions | 128 x 48 |
| Content Dimensions | 95 x 37\* |

_\*This value is disputed; actual usable area may vary slightly._

# Converting a File to 1-Bit Depth

`convert inputfile.bmp -depth 1 -type Bilevel BMP3:outputfile.bmp`

_`convert` is a component of ImageMagick._
