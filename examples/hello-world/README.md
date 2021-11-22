How to build PlatformIO based project
=====================================

1. [Install PlatformIO Core](http://docs.platformio.org/page/core.html)
2. Download [development platform with examples](https://github.com/platformio/platform-windows_x86/archive/develop.zip)
3. Extract ZIP archive
4. Run these commands:

```shell
# Change directory to example
$ cd platform-windows_x86/examples/hello-world

# Build project
$ pio run

# Run program
> .pioenvs/native/program

# Clean build files
$ pio run --target clean
```
