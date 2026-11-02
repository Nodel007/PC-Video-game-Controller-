# PC-Video-game-Controller-

# Custom ESP32-S3 Gaming Controller

A custom-designed PC gaming controller featuring a custom PCB, wireless connectivity, motion sensing, and a rechargeable battery system.

## Overview

This project focuses on the design and development of a custom PC gaming controller built around the ESP32-S3 microcontroller.

The controller is designed to combine traditional gamepad functionality with additional hardware capabilities, including gyroscopic motion sensing, Bluetooth connectivity, and USB-C wired operation.

The project currently focuses on hardware development, including circuit design, PCB layout, and mechanical CAD modeling.

## Design Goals

- Develop a custom-designed controller PCB.
- Implement traditional gamepad controls, including analog sticks and physical buttons.
- Integrate gyroscopic motion sensing.
- Support Bluetooth wireless connectivity.
- Support USB-C wired connectivity.
- Incorporate a rechargeable battery system.
- Develop a custom physical enclosure.

## Hardware Features

| Component | Function |
|---|---|
| ESP32-S3 | Main microcontroller |
| Analog Sticks | Analog directional input |
| Physical Buttons | Standard gamepad input |
| Gyroscope | Motion and orientation sensing |
| USB-C | Wired connectivity |
| Bluetooth | Wireless connectivity |
| Rechargeable Battery | Portable power |

## Hardware Design

The controller's electronic circuitry and PCB layout were designed using KiCad.

The hardware design files include:

- Circuit schematics
- PCB layout
- Component footprints
- Supporting hardware design files

## Mechanical Design

The physical design of the controller is developed using CAD software.

The CAD directory contains the 3D models and mechanical design files associated with the controller enclosure and components.

## Technologies & Tools

- **Microcontroller:** ESP32-S3
- **PCB Design:** KiCad
- **Mechanical Design:** CAD software
- **Connectivity:** Bluetooth and USB
- **Programming:** Embedded C/C++ (planned)

## Repository Structure

```text
custom-game-controller/
│
├── hardware/
│   ├── kicad/
│   └── datasheets/
│
├── cad/
│   ├── source/
│   └── exports/
│
├── images/
│
├── docs/
│
├── README.md
└── LICENSE
```

## Current Project Status

**PCB Design — In Progress**

The electronic design and PCB layout have been developed. The project has not yet reached the PCB manufacturing and physical assembly stage.

## Future Improvements

- Manufacture the custom PCB.
- Assemble and integrate electronic components.
- Develop controller firmware.
- Implement analog stick and button input processing.
- Integrate gyroscope input.
- Implement Bluetooth and USB communication.
- Test controller compatibility with PC games.
- Refine the mechanical enclosure and ergonomics.

## License

License information to be determined.
