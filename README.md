
# EEE3096S 2024 Practicals

This repository contains all the practicals for the EEE3096S Embedded Systems course for the year 2024. Each practical folder contains the necessary code files, reports, and additional documentation required for submission.

## Practical List:

### Practical 1: Timers and LED Control
- **Description**: This practical focuses on using timers and interrupts to control the behavior of LEDs on the STM32 microcontroller.
- **Main Files**:
  - `main.c`: Code to control the LED patterns using timers.
  - `report.pdf`: Documentation of the implementation and demo results.
  
### Practical 2: PWM-based DAC and Filtering
- **Description**: A crude DAC is implemented using PWM, and different waveforms are generated using a low-pass filter. The practical also explores pushbutton interrupts.
- **Main Files**:
  - `main.c`: Code to generate PWM signals and switch between waveform LUTs.
  - `report.pdf`: Explanation of the filtering and waveform generation.
  
### Practical 3: ADC, PWM, and SPI Communication
- **Description**: This practical involves reading data from an ADC, controlling LEDs via PWM, and writing/reading data to/from EEPROM using SPI.
- **Main Files**:
  - `main.c`: Code to handle ADC, PWM, and SPI operations.
  - `report.pdf`: Description of the ADC setup, SPI communication, and implementation of the tasks.
  
### Practical 4: Assembly Programming with GPIO Control
- **Description**: This practical uses assembly language to control LEDs and respond to pushbutton inputs on the STM32 microcontroller.
- **Main Files**:
  - `assembly.s`: Assembly code controlling GPIO for LEDs and pushbuttons.
  - `report.pdf`: Documentation of the assembly code and performance analysis.
  
---

## Cloning and Setup Instructions:

1. Clone the repository using:
   ```bash
   git clone https://github.com/yourusername/EEE3096S_2024_Practicals.git


## Acknowledgments

- **STM32CubeIDE** - The integrated development environment used for this project.
- **STMicroelectronics** - For providing the STM32 development platform and HAL libraries.

## License

This repository is licensed under the MIT License. See the LICENSE file for more information.
