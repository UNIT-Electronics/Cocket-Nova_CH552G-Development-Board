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

## Get Started :star: 

To learn more about how to begin using Cocket-Nova, please check out the user manual. You can download it from this :point_right: **link** 👈.

Additionally, we offer a course on programming this development board. Find it right :point_right: <a href="https://unit-electronics.github.io/CH552_Curso_introductorio/">**here**</a> 👈. The course includes examples demonstrating how to explore Cocket Nova's capabilities.

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