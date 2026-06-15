# FLIGHT-CONTROLLER

# STM32 Flight Controller

A custom flight controller PCB built around an STM32 microcontroller, designed for small to mid-sized multirotor and fixed-wing builds. The board integrates IMU sensing, motor/ESC outputs, RC input, USB connectivity, and status indicators on a compact 2-layer design.

![Top View](Docs/Images/top-view.png)

## Overview

This project started as a way to get a fully custom flight controller working from scratch — designing the schematic, laying out the PCB, and routing everything by hand (including a dedicated ground plane on the bottom layer for noise reduction and cleaner signal integrity).

The board is designed in EasyEDA and is fully open for anyone who wants to build, modify, or learn from it.

## Features

- STM32-based main processor
- Onboard status LEDs and user switches
- Multiple connector headers for peripherals (UART, sensors, motor outputs, etc.)
- USB connectivity for programming/debugging
- Test points broken out for debugging
- 2-layer PCB with bottom-layer ground plane
- Mounting holes for standard frame compatibility

## Repository Structure

```
.
├── Hardware/
│   ├── PCB/              # PCB layout files (EasyEDA)
│   ├── Schematic/        # Schematic files (EasyEDA)
│   ├── Gerbers/          # Manufacturing files (Gerber/drill)
│   ├── 3D-Renders/       # Board renders (top/bottom/iso views)
│   └── Datasheets/       # Component datasheets used in design
├── BOM/
│   └── bom.csv           # Bill of materials
├── Docs/
│   └── Images/           # Photos, screenshots, build images
└── README.md
```

## Design Tool

Designed in **EasyEDA / EasyEDA Pro**. Source design files are included under `Hardware/PCB` and `Hardware/Schematic` so the project can be opened, edited, or forked directly.

## Manufacturing

Gerber files for fabrication are located in `Hardware/Gerbers`. These can be uploaded directly to most PCB fab houses (JLCPCB, PCBWay, etc.) for production.

Recommended fab specs:
- 2 layers
- 1oz copper
- Minimum trace/space: 0.2mm / 0.2mm
- Minimum via drill: 0.3mm

## Bill of Materials

A full BOM is provided in `BOM/bom.csv`, listing all components, values, footprints, and reference designators used on the board.

## Status

Routing complete, DRC clean (0 errors). Bottom layer routed with dedicated ground plane pour. Board has been generated and is ready for fabrication/assembly.

## Renders & Images

See `Hardware/3D-Renders` for top/bottom isometric views, and `Docs/Images` for additional build photos and progress shots.

## Notes

This is a personal/hobby project shared for reference and learning purposes. Feel free to open issues if you spot something that could be improved in the design.

## License

All rights reserved. This design is shared for reference purposes only. Please do not redistribute or sell without permission.
