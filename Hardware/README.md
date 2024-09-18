
# Hadware [Cocket Nova](https://github.com/UNIT-Electronics/Cocket-Nova_CH552G-Development-Board) 


<a href="https://github.com/UNIT-Electronics/Cocket-Nova_CH552G-Development-Board/tree/main/Hardware/UE0025_Cocket-Nova_Schematic.pdf"><img src="Resources/Schematics_icon.jpg?raw=false" width="500px"><br/> Schematics</a>

# Power Tree

<img src="Resources/CocketNova-Power-Tree-V1.2.jpg?raw=false" width="650px"><br/>

# Block Diagram

<img src="Resources/CocketNova-Block Diagram.jpg?raw=false" width="650px"><br/>

# Pinout

<img src="Resources/UE0025-CocketNova-Pinout.jpg?raw=false" width="1000px"><br/>

# Board Topology

**Front View**<img src="Resources/Front View DualMCU Topology.jpg?raw=false" width="800px"><br/>

| Ref. | Description | Ref. | Description
|----------|----------|----------|-------|
|  U1  | Raspberry pi RP2040 Microcontroller   |   U4  | CH340C USB bus convert IC |
|  U2  | Espressif ESP32 WROOM Wi-Fi/Bluetooth® Module   |   U5  | MCP73831 Battery Charge Management IC |
|  U3  | W25Q16JVUXIQ 2MB Flash IC   |   U6  | AP2112K 3v3 LDO Voltage Regulator |
|  L1  | Power On LED   |   L2  | Charge LED |
|  L3  | Builtin LED (GPIO25)   |   L4  | WS2812B LED |
|  L5  |RGB 2020 LED   |   J1  | Male USB Type C Connector |
|  PB1  |RP2040 Reset Button   |   PB2  | RP2040 Boot Button |
|  PB3  |ESP32 Flash Button    |   PB4  | ESP32 Reset Button |
|  JP1  |RP2040 GPIO Header    |   JP2  | ESP32 GPIO Header |
|  JP3  |RP2040 (SWD) Debug Header    |   JST1  | RP2040 I2C JST Connector |
|  JST2  |ESP32 I2C JST Conector   |   JST3  | JST Connector for LiPo Battery |
|  SW2  |USB Communication Selector   |   SW3  | UART DIP Switch |

**Back View**<img src="Resources/Back View DualMCU Topology.jpg?raw=false" width="800px"><br/>

| Ref. | Description | Ref. | Description
|----------|----------|----------|-------|
|  U7  | Support for the ATECC608A-MAHDA-T Crypto IC   |   J2  | Micro SD Card Connector |
|  SW1  | Power Switch   |   SB1  | Charge LED Solder Bridge (default disconnected) |
|  SB2  | VBUS Sense Solder Bridge (default disconnected) |   SB3  | AP2112K 3v3 LDO Voltage Regulator |
|  SB4  | ESP32 Reset Solder Bridge (default disconnected)   |   SB5  | SCL Signal Selector Solder Bridge for ATECC608A-MAHDA-T (default disconnected)|
|  SB6  | SDA Signal Selector Solder Bridge forATECC608A-MAHDA-T (default disconnected)|   B1  | Lipo Battery Solder Pads |



For more details, check out the product pages at
* https://uelectronics.com/
