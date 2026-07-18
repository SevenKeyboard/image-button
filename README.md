# image-button
GDI+ based image/gradient pushbutton renderer.

This repository is a maintained fork of [AHK-just-me/Class_ImageButton](https://github.com/AHK-just-me/Class_ImageButton),
with small enhancements for my own projects.

## Fork notes
- v1.0.0: Added `FontFamily` support and preserved the original button caption (no longer hides/removes it).
- v1.1.0: Added optional left, right, top, and bottom edge overlays via the `0x10` mode flag. Existing modes `0` through `7` and eight-field option arrays remain compatible.
