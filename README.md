# Embedded Systems and Robotics Summer School 

This repository contains the code and resources from the 20-day project-based learning course designed to solve Embedded Systems and Robotics problems with a pragmatic approach.

## Table of Contents

- [Program Layout and Details](#program-layout-and-details)
- [Deployment](#deployment)
- [Tech Stack](#tech-stack)
- [Authors](#authors)
- [License](#license)

## Program Layout and Details

### Week 1: I/O Interfacing
- Familiarize with Microchip Studio/VSCode
- Program and debug C code snippets
- Interface I/O peripherals: Switch, Buzzer, Bar graph LEDs, and LCD
- Understand various LCD commands and ASCII encoding
- Display text at different positions on the LCD and implement a simple scrolling display

### Week 2: Working with Sensors
- Interface Sharp sensors and Proximity sensor
- Understand ADC (Analog to Digital conversion) on Firebird V
- Implement Interrupt and Position encoder for traversal of Firebird V

### Week 3: Motor Interfacing
- Control direction of DC motors on Firebird V Robot
- Understand TIMERs and associated registers in ATmega2560 for configuring TIMERs
- Implement Interrupt and Position encoder for traversal of Firebird V Robot

### Week 4: Challenge Activity
  - Challenge Activity 1: Custom character display on the LCD
  - Challenge Activity 2: Display waveforms from function generator on GLCD with switches representing Digital Oscilloscope (DSO)

## Deployment

1. **Start Microchip Studio**
2. **Build the Project**
   - Use the shortcut key `Ctrl+Alt+F7` or navigate to `Build > Rebuild solution` from the menu bar.
3. **Select Device**
   - In Project settings, choose `Change Device` and select `ATmega328P`.
4. **Compile and Verify**
   - If the build is successful, you will see the message `======== Rebuild All: 1 succeeded, 0 failed, 0 skipped ========` in the Output window.
   - A `Debug` folder will be created in the project directory containing the `Experiment-'name'.hex` file along with other build files.
5. **Load the Hex File**
   - Load the hex file onto the Firebird V robot or simulator circuit once the program is successfully built.

## Tech Stack

- **Language Used:** C
- **IDE Used:** Microchip Studio

