
# Embedded Systems Lab 1 - Timer and LED Patterns

## Overview
This repository contains the code and related resources for **Group 36** of the EEE3099S Embedded Systems II Lab. The project focuses on utilizing timers and interrupts to control LED patterns and responding to pushbutton inputs on an STM32 microcontroller. This README outlines the structure of the repository and provides essential information for navigating and understanding the project.

### Contributors
- **Georgene de Wet** (DWTGEO002)
- **Arend Jacques du Preez** (DPRARE001)

## Project Description
The primary goal of this project is to enhance our understanding of embedded systems by working with the STM32CubeIDE and the Hardware Abstraction Layer (HAL) libraries. We implemented a series of LED patterns that change at specified intervals using a timer interrupt and responded to various pushbutton inputs to alter the timing and reset the sequence.

## Repository Structure
- **/main.c**: The main C source file containing the implementation of the LED patterns, timer configuration, and pushbutton handling.
- **/README.md**: This file, containing an overview of the project and instructions for use.
- **/EEE3096S_2024-main.zip**: Compressed folder containing all project files, including the main.c file and any additional resources.
- **/practical1_report_DWTGEO002_DPRARE001.pdf**: The final report submitted for the practical, detailing the implementation and outcomes.

## Setup and Usage
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/EmbeddedSystems_Lab1_TimerProject_Group36.git
   ```

2. **Import the Project:**
   - Open **STM32CubeIDE**.
   - Navigate to `File > Import > Existing Code as Makefile Project`.
   - Select `MCU ARM GCC` as the toolchain and finish the setup.

3. **Run the Code:**
   - Navigate to `Core/src/main.c` and complete any remaining TODOs.
   - Compile and flash the code onto your STM32 board.

4. **Testing:**
   - Use the pushbuttons to test different timer delays:
     - **PA0:** 0.5s delay
     - **PA1:** 2s delay
     - **PA2:** 1s delay (default)
     - **PA3:** Reset to pattern 1

5. **Version Control:**
   - Ensure regular commits are made at significant milestones.
   - Both contributors should have commit histories in the repository.

## Documentation
- **Timers and Interrupts:** The use of timers to generate delays and trigger interrupts is explained, allowing the LED patterns to change at defined intervals.
- **Pushbuttons:** The code handles different delays based on pushbutton presses and includes a reset function to restart the pattern sequence.

## Resources
- [STM32CubeIDE Documentation](https://www.st.com/en/development-tools/stm32cubeide.html)
- [Git Setup Guide](http://wiki.ee.uct.ac.za/Git)
- [HAL Libraries Documentation](https://www.st.com/resource/en/user_manual/um1785-description-of-stm32f0-hal-and-lowlayer-drivers-stmicroelectronics.pdf)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

