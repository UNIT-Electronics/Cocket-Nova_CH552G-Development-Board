# Cocket-Nova_CH552G-Development-Board
Explore the amazing features of the Cocket Nova development board, which runs on the CH552G microcontroller. This handy board makes it easy to kickstart your embedded projects.

It fits perfectly onto standard breadboards and can be programmed via USB Type C. Plus, it comes with a built-in Neopixel LED at pin 3.3 and two header outputs for extra Neopixels. You'll also find features like an LED at pin 3.4, reset and boot buttons, a power supply selector, and two 1mm JST connectors that support QWIIC, STEMMA QT protocols, and more.

This board is great for beginners dipping their toes into microcontrollers and DIY enthusiasts working on projects with an affordable 8-bit USB device.

![Logo](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/th5xamgrr6se0x5ro4g6.png)


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

- e8051 Core supported by the instruction set of MCS51
- 🧠 Memory:
  - 16 KB ROM, it clould be divided in 14 KB for programm and 2 KB for bootoader or ISP programming
  - 128 bytes for flash memory
  - 256 bytes of internal RAM
- 💻 Peripheral:
  - 2 outputs for 8 bit PWM 
  - 4 channels for 8 bit ADC
  - 6 capacitance detección channels, it supports until 15 touch buttons
  - 17 GPIOS
  - 14 groups of interruptions and an 8 bit Watch Dog timer
  - External reset and boot buttons
  - External clock signal through multiplexing GPIOS
- 🔌 USB:
  - Internal USB controller and transceiver, it allows programming via USB without external controllers
  - USB 2.0 support at maximum 12 mbps
- ⚡ Energy:
  - Power supply voltage of 5V or 3.3V
  - It could be powered by voltage between 2.8V and 3.5V