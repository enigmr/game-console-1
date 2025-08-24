## Game Console Project 1

Hobby handheld game console from scratch.


## Features

- Display: 4.3", 480x272, 16:9, 1200cd/m2, non-touch
- Processor: STM32N657X0
  - Arm Cortex-M55 @ 800 MHz
  - 2D GPU with scaling, rotating, alpha blending, texture mapping
- RAM:
  - 4.2MB on-chip SRAM
  - 32MB off-chip PSRAM
- Storage:
  - 32MB SLC NOR flash
  - Micro SD card slot
- Audio:
  - Stereo DAC with Class-D amplifiers
  - Stereo 1W speakers
- Haptics:
  - Dual vibration motors
- Input:
  - IMU (accelerometer and gyroscope)
  - D-pad
  - A / B / X / Y buttons
  - Start / Select buttons
  - Right and left bumpers
- Battery:
  - 500mAh Li-Po battery
- Connectivity:
  - USB-C for charging and accessing storage
  - Wi-Fi and Bluetooth via STM32-C6
- Mechanicals:
  - 3D printed where possible
- Software:
  - Zephyr RTOS
  - Old game console emulators


## Development Tooling

- Schematics and PCB design: KiCad
- 3D modeling: Fusion 360


## Hardware Block Design

TODO

## Mechanicals

### Top View
<img src="./doc/images/mechanicals/render-1.png">

### Insides
<img src="./doc/images/mechanicals/insides.png">

## PCBs

### Top
<img src="./doc/images/pcb/left-board-top.png">
<img src="./doc/images/pcb/main-board-top.png">
<img src="./doc/images/pcb/right-board-top.png">

### Top Bottom
<img src="./doc/images/pcb/left-board-bottom.png">
<img src="./doc/images/pcb/main-board-bottom.png">
<img src="./doc/images/pcb/right-board-bottom.png">


## Schematics 

### Top Sheet
<img src="./doc/images/schematics/main-board.svg">

### Audio
<img src="./doc/images/schematics/main-board-Audio.svg">

### ESP32
<img src="./doc/images/schematics/main-board-ESP32.svg">

### Flash
<img src="./doc/images/schematics/main-board-Flash.svg">

### Haptics
<img src="./doc/images/schematics/main-board-Haptics.svg">

### IMU
<img src="./doc/images/schematics/main-board-IMU.svg">

### LCD
<img src="./doc/images/schematics/main-board-LCD.svg">

### MCU
<img src="./doc/images/schematics/main-board-MCU.svg">

### Micro SD
<img src="./doc/images/schematics/main-board-Micro SD.svg">

### Power
<img src="./doc/images/schematics/main-board-Power.svg">

### RAM
<img src="./doc/images/schematics/main-board-RAM.svg">

### USB Switch
<img src="./doc/images/schematics/main-board-USB Switch.svg">

### USB
<img src="./doc/images/schematics/main-board-USB.svg">

### Controllers
<img src="./doc/images/schematics/main-board-Buttons.svg">

### Left Board
<img src="./doc/images/schematics/left-board.svg">

### Right Board
<img src="./doc/images/schematics/right-board.svg">
