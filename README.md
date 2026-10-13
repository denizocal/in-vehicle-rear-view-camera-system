# Raspberry Pi In-Vehicle Rear-View Camera System

This Raspberry Pi-based in-vehicle display system automatically switches from navigation to a rear-view camera feed when reverse gear is selected.

During normal driving, the display supports navigation. When the vehicle is reversing, the camera view takes priority to provide a more useful view behind the vehicle.

## Project Overview

The system uses a Raspberry Pi as its main processing unit and a compatible camera module to capture live video. The display changes according to the reverse-gear signal.

In normal operation, the navigation screen is active. When reverse is selected, the system automatically displays the camera feed so the driver can see behind the vehicle while maneuvering.

## Project Goals

- Develop a Raspberry Pi-based embedded system
- Integrate a camera module
- Create a display system for an in-vehicle use case
- Switch automatically between operating modes
- Combine hardware and software around a practical use case

## Operating Modes

### Navigation Mode

During normal driving, the display shows the navigation interface.

### Rear-View Mode

When reverse gear is selected, the system detects the relevant signal and automatically switches the display to the live rear-view camera feed.

This removes the need for the driver to switch the display manually.

## Main Components

- Raspberry Pi
- Raspberry Pi-compatible camera module
- In-vehicle display
- Reverse-gear trigger signal
- Display switching software
- Power and system connections

## Work Completed

- Designed the Raspberry Pi-based system architecture
- Integrated a compatible camera module
- Set up live video capture
- Planned the transition between navigation and camera views
- Implemented the reverse-triggered display switching logic
- Planned a test setup for the in-vehicle use case

## Technologies and Tools

- Raspberry Pi
- Raspberry Pi camera module
- Embedded Linux
- Display and interface-control logic
- In-vehicle integration connections

## Skills Applied

- Camera-based embedded systems
- Real-time video capture
- Scenario-based interface switching
- Hardware-software integration
- Automotive electronics system design

## Potential Applications

- In-vehicle rear-view camera systems
- Smart vehicle displays
- Vision-based driving assistance
- Raspberry Pi automotive prototypes

## Project Photos

![System overview](images/sistem-gorunumu.png)

![Camera module](images/kamera-modulu.png)

![Display interface](images/ekran-arayuzu.png)

![Rear-view mode](images/geri-gorus-modu.png)

## Possible Extensions

- Improve low-light performance
- Make screen switching faster
- Add parking guide lines
- Design a more compact enclosure
- Add video recording
- Integrate a wireless camera
- Build a more advanced in-vehicle multimedia interface

## Summary

This project is a Raspberry Pi application for in-vehicle display and driver-assistance use cases. Its automatic transition between navigation and rear-view camera modes makes it a practical example of hardware-software integration for automotive applications.
