# G6\_Panels\_Test\_Firmware  
Some test firmware for the G6 Panels.

## Getting Started

The only prerequisite is [pixi](https://pixi.sh). Once pixi is installed, it manages all other dependencies (including PlatformIO) automatically. This works on **Windows, macOS, and Linux** and no platform-specific setup required.

To compile and upload the firmware to a connected G6 panel, run:

```
pixi run deploy-single-led
```

This single command will install all dependencies, compile the firmware, and upload it to the G6 panel if it is connected via USB. The same command works across all platforms.

## License
MIT
