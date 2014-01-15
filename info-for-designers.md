## Application images

*TODO*

## Raster images

### Supporting Retina

For iOS, to support retina displays, you have to provide two copies of each
image, one normal size, and one at twice the resolution, named with @2x in the
name.

E.g. if you have a user.png which is 80x60, you would provide:

- user.png, 80x60
- user@2x.png, 160x120

This goes for *every* raster image used in the app.

### Gradual Gradients not Supported Well

One more gotcha with iOS is that it reencodes PNG files, and one of the side
effects is that gradual gradients end up banding, so it’s best to stay away
from them.
