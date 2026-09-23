# 3-Wheel Omni Robot

A 3-wheel omni-directional mobile robot based on a Raspberry Pi Pico, DC geared encoder motors, L298N motor drivers and RPLIDAR.

## Project Status

🚧 In development

## Hardware

- Raspberry Pi Pico
- 3 × GB37 12V 180 RPM DC geared encoder motors
- 3 × 60 mm omni wheels
- 2 × L298N motor drivers
- RPLIDAR A1M8-R6
- LM2596 buck converter
- 20A 300W CC-CV buck converter
- 210 mm diameter circular chassis

## Software

- C/C++
- Raspberry Pi Pico firmware
- ROS 2
- Ubuntu 22.04
- VS Code
- Git/GitHub

## Planned Development

1. Pico motor control
2. Encoder feedback
3. RPM measurement
4. PID motor control
5. Omni-wheel kinematics
6. Robot odometry
7. ROS 2 integration
8. RPLIDAR integration
9. Localization and mapping
10. Autonomous navigation

## Repository Structure

```text
firmware/    Pico firmware
src/         ROS 2 software
hardware/    CAD and hardware files
docs/        Project documentation