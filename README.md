# STM32 Line Follower Robot

## Overview

A custom STM32-based Line Follower Robot PCB designed using KiCad.

## Features

- STM32 microcontroller-based control
- Line sensor interface
- Motor driver interface
- Compact custom PCB
- Designed using KiCad

## Hardware

- STM32 Microcontroller
- IR Line Sensors
- Motor Driver
- DC Motors
- Power Supply
- Custom PCB

## PCB Design

The PCB was designed using KiCad, including:

- Schematic design
- Component placement
- PCB layout
- Routing
- Design rule checking (DRC)

## Project Files

This repository contains:

- `STM_LFR.kicad_pro` — KiCad project file
- `STM_LFR.kicad_sch` — Schematic
- `STM_LFR.kicad_pcb` — PCB layout

## Tools Used

- KiCad
- STM32
- PCB Design

## Hardware Components

| Component | Quantity | Purpose |
|---|---:|---|
| STM32 Blue Pill (STM32F103C8T6) | 1 | Main microcontroller |
| TB6612FNG Motor Driver | 1 | Controls two DC motors |
| Mini-360 Buck Converter | 1 | Steps down the input voltage |
| Push Button | 2 | User input |
| DIP Switch | 1 | Configuration and control |
| IR Sensor Header | 1 | Connection for line sensors |
| Power Input Terminal Block | 1 | Battery/power input |
| Motor Output Terminal Block | 2 | Left and right motor connections |

## Board Features

- STM32-based control
- Dual DC motor control using TB6612FNG
- Dedicated IR sensor interface
- On-board buck converter
- Two push buttons
- DIP switch for configuration
- Screw terminal for power input
- Screw terminals for motor outputs
- Custom PCB designed using KiCad

## Author

Jayanth Balaji
