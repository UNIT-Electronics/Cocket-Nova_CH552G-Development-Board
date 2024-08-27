# Cocket-Nova_CH552G-Development-Board
Explore the amazing features of the Cocket Nova development board, which runs on the CH552G microcontroller. This handy board makes it easy to kickstart your embedded projects.

It fits perfectly onto standard breadboards and can be programmed via USB Type C. Plus, it comes with a built-in Neopixel LED at pin 3.3 and two header outputs for extra Neopixels. You'll also find features like an LED at pin 3.4, reset and boot buttons, a power supply selector, and two 1mm JST connectors that support QWIIC, STEMMA QT protocols, and more.

This board is great for beginners dipping their toes into microcontrollers and DIY enthusiasts working on projects with an affordable 8-bit USB device.

![Static Badge](https://img.shields.io/badge/1.2-blue?style=plastic&label=Version)
## What You Need 📋

- A USB Type C cable for data transfer
- Arduino IDE or a similar compiler that works with the CH552 MCU
- Zadig Software
- CH372DRV Driver

## Key Features 📝

- Runs on CH552 Microcontroller
- Built-in USB transceiver enables programming via USB type C
- Operates on either 5V or 3.3V with selectable voltage
- Incorporates LED on pin 3.4
- Includes Neopixel LED on pin 3.3
- Equipped with two headers for additional Neopixels
- Compatible with standard breadboards
- Features two 1mm JST connectors supporting QWIIC and STEMMA QT protocols

## Technical Features 🚀

- Processor Core 💾: Powered by the e8051 core with full support for the MCS51 instruction set.

- Memory 🧠:
  - 16 KB ROM, divisible into 14 KB for program storage and 2 KB for bootloader or ISP programming.
  - 128 bytes of flash memory.
  - 256 bytes of internal RAM for data storage. 

- Peripheral 💻:
  - 2 outputs capable of 8-bit PWM generation.
  - 4 channels dedicated to 8-bit ADC functionality.
  - 6 capacitance detection channels supporting up to 15 touch buttons.
  - 17 GPIOs for versatile interfacing.
  - 14 groups of interruptions along with an 8-bit Watch Dog timer.
  - External reset and boot buttons provided for system control.
  - External clock signal reception via multiplexing GPIOs.
   
- USB 🔌:
  - Integrated USB controller and transceiver facilitating programming via USB without external controllers.
  - Supports USB 2.0 with a maximum data rate of 12 Mbps.
  
- Energy ⚡:
  - Compatible with power supply voltages of 5V or 3.3V.
  - Operates within a voltage range of 2.8V to 3.5V.
  
- Communication 📟:
  - 2 UART groups for serial communication.
  - SPI interface.
  - Soft I2C simulable at GPIOs.
  
- Connectors 🔧:
  - 2 JST connectors supporting protocols like QWIIC, STEMMA QT, or similar.
  - Ability to power the board or other devices via these ports.

- Built-in LEDs 💡:
  - Neopixel connected at GPIO 3.3 with expandable headers for additional Neopixels.
  - LED connected at GPIO 3.4.


## Get Started ⭐

To learn more about how to begin using Cocket-Nova, please check out the following resources:

1. **[Manual](link)**: Check out the user manual 👈.

2.  **[Cocket Nova & Arduino IDE](https://unit-electronics.github.io/CH552_Curso_introductorio/)**: This course provides a comprehensive introduction to programming the Cocket Nova development board using the Arduino IDE. It includes examples and demonstrations to help you explore the board's capabilities effectively.

- **[Introducción al CH552](https://github.com/UNIT-Electronics/CH552_Curso_introductorio?tab=readme-ov-file)**

3. **[Cocket Nova Getting Started Guide](https://github.com/UNIT-Electronics/CH55x_SDCC_Doc)**: A manual for using the SDCC compiler with the CH55x microcontroller. It helps users explore features, start projects, and configure settings. Compatible with Cocket Nova CH552 boards for easy and innovative project implementation.

4. **[Cocket Nova CH552 Examples using SDCC](https://github.com/UNIT-Electronics/CH55x_SDCC_Examples)**: Examples for CH55x microcontroller development in C with the SDCC compiler. Covers various topics including Blink, ADC, PWM, Timer, Interrupts, and I2C. Updated regularly to improve project development.

5. **[ue_loadupch_Loader_Firmware](https://github.com/UNIT-Electronics/ue_loadupch_Loader_Firmware)**: A project dedicated to uploading firmware to the CH552 microcontroller. Designed for compatibility with the Cocket Nova development board, it features a simple design and uses a USB communication interface, developed with Python 3.9 for use on both Windows and Linux platforms.

Feel free to explore these resources to get the most out of your Cocket Nova development board!


## Contributions Welcome! 🙌

We appreciate any contributions you can make! If you'd like to collaborate and contribute to this project, please feel free to open a pull request in this repository. Your input is valued and helps improve the project for everyone. Thank you!

## License 📜

This project is licensed under the <a href="https://www.gnu.org/licenses/gpl-3.0.html">**GPL-3.0 License** </a>

## Contact Us ☎️

If you have any questions or ideas, don't hesitate to email us at ventas@uelectronics.com. Also, we encourage you to check out our website at <a href="www.uelectronics.com">**www.uelectronics.com**</a>, where you can explore a variety of modules, sensors, shields, and other devices to help you bring your projects to life.

## Authors 🎓

The material was assembled by the UNIT Electronics Team.

- <a href="https://github.com/AlbertoVillanuevaEsquivel">Alberto Villanueva: </a> Hardware design.
- <a href="https://github.com/Cesarbautista10">Cesar Bautista:</a> Software design.

<hr>

⌨️ With ❤️ by <a href="www.uelectronics.com">UNIT Electronics </a>