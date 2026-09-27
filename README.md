# EV Control System (AKS)
![AKS PCB](Images/aks_pcb_top.jpeg)
Custom vehicle control system PCB developed for an electric vehicle project.

## Overview

The AKS (Araç Kontrol Sistemi) is a custom vehicle control and monitoring board designed for an electric vehicle platform.

The system integrates vehicle communication, telemetry, data logging, power management and control interfaces on a single embedded hardware platform.

## Key Features

- ATmega2560-based control architecture
- CAN Bus communication using MCP2515
- GSM telemetry using SIM800C
- SD card data logging
- DS3231 Real-Time Clock
- Relay and contactor control
- 12 V vehicle power input
- Regulated 5 V and 3.3 V power rails
- Modular communication and peripheral interfaces

## Communication Interfaces

| Interface | Application |
|---|---|
| CAN Bus | Vehicle and BMS communication |
| UART | GSM and external peripherals |
| SPI | MCP2515 CAN controller and SD card |
| I2C | DS3231 RTC |

## My Contribution

- System architecture design
- Schematic design
- PCB layout
- Component selection
- Power distribution design
- CAN communication hardware integration
- GSM telemetry hardware integration
- Relay and contactor interface design
- PCB manufacturing preparation
- Hardware testing and debugging

## Tools & Technologies

- KiCad
- ATmega2560 / Arduino Mega platform
- CAN Bus
- MCP2515
- SIM800C
- Embedded Systems
- PCB Design
- Git / GitHub
