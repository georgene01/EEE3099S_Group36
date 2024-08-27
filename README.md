# EEE3096S Practical Repository

This repository contains the source code and reports for the EEE3096S course practicals. The code is implemented on the STM32 development board using C and the STM32CubeIDE environment.

## Practical 2 Overview

### Objective

The primary objective of Practical 2 was to create a simple DAC using Pulse Width Modulation (PWM) and a low-pass filter. The code implements:
- Generation of sinusoidal, sawtooth, and triangular waveforms using Lookup Tables (LUTs).
- Configuration of timers to manage PWM output and LUT cycling.
- Implementation of Direct Memory Access (DMA) for efficient waveform generation.
- Handling pushbutton interrupts for switching between different waveforms.

### How to Use

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/EEE3096S_Practical_Repo.git
    ```

2. **Import the Project**:
    - Open STM32CubeIDE.
    - Import the project from the `2024-main.zip` archive.
    - Ensure the proper setup of all peripherals and the system clock as defined in the `.ioc` file.

3. **Build and Run**:
    - Build the project using STM32CubeIDE.
    - Flash the code to your STM32 development board.
    - Use an oscilloscope to observe the generated waveforms from the DAC output (Pin PB0).

### Practical 2 Report

The Practical 2 report (`practical2_report_DWTGEO002_DPRARE001.pdf`) provides a comprehensive overview of the tasks completed, including:
- The methodology used for configuring the DAC.
- Results observed through waveform generation.
- Analysis of the signal integrity and the effects of filtering.
- Conclusions and potential improvements for future implementations.

## Acknowledgments

- **STM32CubeIDE** - The integrated development environment used for this project.
- **STMicroelectronics** - For providing the STM32 development platform and HAL libraries.

## License

This repository is licensed under the MIT License. See the LICENSE file for more information.
