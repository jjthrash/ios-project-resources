## Application images

The application includes a number of resources that are displayed by the OS
rather than the application itself. Most of these are required for submission
to the App Store.

All must be PNG format.

### Splash Screen/Launch Image

Shown while the application is loading.

- iPhone, 320x480 (not supported by iOS7)
- iPhone Retina, 640x960
- iPhone Retina 4-inch, 640x1136
- iPad Portrait, 768x1024 (includes iPad mini)
- iPad Landscape, 1024x768 (includes iPad mini)
- iPad Retina Portrait, 1536x2048
- iPad Retina Landscape, 2048x1536

### Application Icon

Shown on the home screen.

- iPhone, 60x60 (not supported by iOS7)
- iPhone Retina, 120x120
- iPad, 76x76
- iPad Retina, 152x152

### Spotlight Icon

Shown while searching for the application.

- iPhone, 40x40 (not supported by iOS7)
- iPhone Retina, 80x80
- iPad, 29x29
- iPad Retina, 58x58

### Settings Icon

Shown in the settings application, if the application is configured for it.

- iPhone, 29x29 (not supported by iOS7)
- iPhone Retina, 58x58
- iPad, 29x29
- iPad Retina, 58x58

## In-Application Raster Images

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
