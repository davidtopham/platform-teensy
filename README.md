# Teensy: development platform for [PlatformIO](http://platformio.org)
[![Build Status](https://travis-ci.org/platformio/platform-teensy.svg?branch=develop)](https://travis-ci.org/platformio/platform-teensy)
[![Build status](https://ci.appveyor.com/api/projects/status/vb91x3g5xujtorf9/branch/develop?svg=true)](https://ci.appveyor.com/project/ivankravets/platform-teensy/branch/develop)

Teensy is a complete USB-based microcontroller development system, in a very small footprint, capable of implementing many types of projects. All programming is done via the USB port. No special programmer is needed, only a standard USB cable and a PC or Macintosh with a USB port.

* [Home](http://platformio.org/platforms/teensy) (home page in PlatformIO Platform Registry)
* [Documentation](http://docs.platformio.org/page/platforms/teensy.html) (advanced usage, packages, boards, frameworks, etc.)

# Usage

1. [Install PlatformIO](http://platformio.org)
2. Create PlatformIO project and configure a platform option in [platformio.ini](http://docs.platformio.org/page/projectconf.html) file:

## Stable version

```ini
[env:stable]
platform = teensy
board = ...
...
```

## Development version

```ini
[env:development]
platform = https://github.com/platformio/platform-teensy.git
board = ...
...
```

# Configuration

Please navigate to [documentation](http://docs.platformio.org/page/platforms/teensy.html).
