# OpenBook

## Block Diagram:
![Block Diagram](https://github.com/user-attachments/assets/87b4854a-b251-4871-b7d1-cd670edd2ce4)

## Bill of Materials:

|Component    |Footprint                                    |Link                                                                                                        |
|-------------|---------------------------------------------|------------------------------------------------------------------------------------------------------------|
|BOOT_BUTTON  |BUTTON_CUSYOMV1                              |https://industry.panasonic.com/global/en/products/control/switch/light-touch/number/evqpuj02k               |
|C1           |ESP32_WROVER_EAGLE-LTSPICE_CC0402            |https://eu.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106?qs=zEY9bCHj09eCmUJdZuS5Lg%3D%3D                 |
|C1_BAT       |ESP32_WROVER_EAGLE-LTSPICE_CC0402            |n/a                                                                                                         |
|C1_BAT1      |EAGLE-LTSPICE_CC0402                         |n/a                                                                                                         |
|C1_BAT2      |EAGLE-LTSPICE_CC0402                         |n/a                                                                                                         |
|C2           |ESP32_WROVER_EAGLE-LTSPICE_CC0402            |n/a                                                                                                         |
|C2_BAT\      |ESP32_WROVER_EAGLE-LTSPICE_CC0402            |n/a                                                                                                         |
|C3           |RCL_CPOL-EUCT3528                            |n/a                                                                                                         |
|C4           |ESP32_WROVER_EAGLE-LTSPICE_CC0402            |n/a                                                                                                         |
|C4_USB       |ESP32_WROVER_EAGLE-LTSPICE_CC0402            |n/a                                                                                                         |
|C5           |ESP32_WROVER_EAGLE-LTSPICE_CC0402            |n/a                                                                                                         |
|C5_USB       |ESP32_WROVER_EAGLE-LTSPICE_CC0402            |n/a                                                                                                         |
|C6           |ESP32_WROVER_EAGLE-LTSPICE_CC0402            |n/a                                                                                                         |
|C7           |ESP32_WROVER_EAGLE-LTSPICE_CC0402            |n/a                                                                                                         |
|C8           |ESP32_WROVER_EAGLE-LTSPICE_CC0402            |n/a                                                                                                         |
|C9           |EAGLE-LTSPICE_CC0402                         |n/a                                                                                                         |
|C10          |ESP32_WROVER_EAGLE-LTSPICE_CC0402            |n/a                                                                                                         |
|C10_SUPERCAP |CPH3225A                                     |https://www.snapeda.com/parts/CPH3225A/Seiko+Instruments/view-part/?ref=eda                                 |
|CHANGE_BUTTON|BUTTON_CUSYOMV1                              |https://industry.panasonic.com/global/en/products/control/switch-light-touch/number/evqpuj02k               |
|CHG_LED      |ADAFRUIT_LEDCHIP-LED0603                     |https://www.snapeda.com/parts/KP-1608SURCK/Kingbright/view-part/?ref=search&t=LED%200603                    |
|C_DELAY      |ESP32_WROVER_EAGLE-LTSPICE_CC0402            |n/a                                                                                                         |
|D1           |USBLC6-2SC6Y                                 |https://www.snapeda.com/parts/USBLC6-2SC6Y/STMicroelectronics/view-part/?ref=eda                            |
|D2           |ESP32_WROVER_AVX---SD0805S020S1R0_AVX_...    |https://eu.mouser.com/ProductDetail/KYOCERA-AVX/SD0805S020S1R0?qs=jCA%252BPfw4LHbpkAoSnwrdjw%3D%3D          |
|D3           |MBR0530                                      |https://eu.mouser.com/ProductDetail/KYOCERA-AVX/SD0805S020S1R0?qs=jCA%252BPfw4LHbpkAoSnwrdjw%3D%3D          |
|D4           |MBR0530                                      |https://www.snapeda.com/parts/MBR0530/Onsemi/view-part/?ref=eda                                             |
|D5           |MBR0530                                      |https://www.snapeda.com/parts/MBR0530/Onsemi/view-part/?ref=eda                                             |
|D6           |PGB1010603MR                                 |https://www.snapeda.com/parts/PGB1010603MR/Littelfuse/view-part/?ref=eda                                    |
|D7           |ESP32_WROVER_AVX---SD0805S020S1R0_AVX_...    |https://eu.mouser.com/ProductDetail/KYOCERA-AVX/SD0805S020S1R0?qs=jCA%252BPfw4LHbpkAoSnwrdjw%3D%3D          |
|D8           |PGB1010603MR                                 |https://www.snapeda.com/parts/PGB1010603MR/Littelfuse/view-part/?ref=eda                                    |
|D9           |PGB1010603MR                                 |https://www.snapeda.com/parts/PGB1010603MR/Littelfuse/view-part/?ref=eda                                    |
|D10          |PGB1010603MR                                 |https://www.snapeda.com/parts/PGB1010603MR/Littelfuse/view-part/?ref=eda                                    |
|D11          |PGB1010603MR                                 |https://www.snapeda.com/parts/PGB1010603MR/Littelfuse/view-part/?ref=eda                                    |
|D12          |PGB1010603MR                                 |https://www.snapeda.com/parts/PGB1010603MR/Littelfuse/view-part/?ref=eda                                    |
|EPD_C1       |ESP32_WROVER_EAGLE-LTSPICE_CC0402            |n/a                                                                                                         |
|EPD_C2       |ESP32_WROVER_EAGLE-LTSPICE_CC0402            |n/a                                                                                                         |
|EPD_C5       |ESP32_WROVER_EAGLE-LTSPICE_CC0402            |n/a                                                                                                         |
|EPD_C6       |ESP32_WROVER_EAGLE-LTSPICE_CC0402            |n/a                                                                                                         |
|EPD_C7       |ESP32_WROVER_EAGLE-LTSPICE_CC0402            |n/a                                                                                                         |
|EPD_C8       |ESP32_WROVER_EAGLE-LTSPICE_CC0402            |n/a                                                                                                         |
|EPD_C9       |ESP32_WROVER_EAGLE-LTSPICE_CC0402            |n/a                                                                                                         |
|EPD_C10      |ESP32_WROVER_EAGLE-LTSPICE_CC0402            |n/a                                                                                                         |
|EPD_C11      |ESP32_WROVER_EAGLE-LTSPICE_CC0402            |n/a                                                                                                         |
|EPD_C12      |ESP32_WROVER_EAGLE-LTSPICE_CC0402            |n/a                                                                                                         |
|IC1          |BD5229G-TR                                   |https://componentsearchengine.com/part-view/BD5229G-TR/ROHM%20Semiconductor                                 |
|IC4          |XC6220A331MR-G                               |https://componentsearchengine.com/part-view/XC6220A331MR-G/Torex                                            |
|J1           |FH34SRJ-24S-0.5SH_99_                        |https://componentsearchengine.com/part-view/XC6220A331MR-G/Torex                                            |
|J2           |SAMACSYS_PARTS_USB4110-GF-A                  |https://componentsearchengine.com/part-view/USB4110-GF-A/GCT%20(GLOBAL%20CONNECTOR%20TECHNOLOGY             |
|J3           |QWIIC_CONNECTORJS-1MM                        |n/a                                                                                                         |
|J4           |112A-TAAR-R03_ATTEND                         |https://store.comet.srl.ro/Catalogue/Product/43497/                                                         |
|L1           |744043680IND_4828-WE-TPC_WRE                 |https://eu.mouser.com/ProductDetail/Wurth-Elektronik/744043680?qs=PGXP4M47uW6VkZq%252BkzjrHA%3D%3D          |
|PFMF.050.1   |ESP32C6_VARISTORCN1812                       |https://www.mouser.co.uk/ProductDetail/EPCOS-TDK/B72520T0350K062?qs=dEfas%2FXlABIszF52uu7vrg%3D%3D          |
|Q1           |ESP32_WROVER_SPARKFUN-DISCRETESEMI_MOSFET_...|https://componentsearchengine.com/part-view/DMG2305UX-7/Diodes%20Incorporated                               |
|Q2           |ESP32_WROVER_SPARKFUN-DISCRETESEMI_MOSFET_...|n/a                                                                                                         |
|Q3           |D8                                           |https://componentsearchengine.com/part-view/SI1308EDL-T1-GE3/Vishay                                         |
|R1           |ESP32_WROVER_EAGLE-LTSPICE_RR0402            |n/a                                                                                                         |
|R1-PINH      |ESP32_WROVER_EAGLE-LTSPICE_RR0402            |n/a                                                                                                         |
|R1-PINH1     |ESP32_WROVER_EAGLE-LTSPICE_RR0402            |n/a                                                                                                         |
|R1_BAT       |ESP32_WROVER_EAGLE-LTSPICE_RR0402            |n/a                                                                                                         |
|R1_PWRUSB    |ESP32_WROVER_EAGLE-LTSPICE_RR0402            |n/a                                                                                                         |
|R2           |ESP32_WROVER_EAGLE-LTSPICE_RR0402            |https://componentsearchengine.com/part-view/R0402%201%25%20100%20K%20(RC0402FR-07100KL                      |
|R2-PINH      |ESP32_WROVER_EAGLE-LTSPICE_RR0402            |n/a                                                                                                         |
|R2-PINH1     |ESP32_WROVER_EAGLE-LTSPICE_RR0402            |n/a                                                                                                         |
|R2-USB       |ESP32_WROVER_EAGLE-LTSPICE_RR0402            |n/a                                                                                                         |
|R2-USB1      |ESP32_WROVER_EAGLE-LTSPICE_RR0402            |n/a                                                                                                         |
|R2_BAT       |ESP32_WROVER_EAGLE-LTSPICE_RR0402            |n/a                                                                                                         |
|R3           |ESP32_WROVER_EAGLE-LTSPICE_RR0402            |n/a                                                                                                         |
|R4           |ESP32_WROVER_EAGLE-LTSPICE_RR0402            |n/a                                                                                                         |
|R5           |ESP32_WROVER_EAGLE-LTSPICE_RR0402            |n/a                                                                                                         |
|R6           |ESP32_WROVER_EAGLE-LTSPICE_RR0402            |n/a                                                                                                         |
|R7           |ESP32_WROVER_EAGLE-LTSPICE_RR0402            |n/a                                                                                                         |
|R8           |ESP32_WROVER_EAGLE-LTSPICE_RR0402            |n/a                                                                                                         |
|R9           |ESP32_WROVER_EAGLE-LTSPICE_RR0402            |n/a                                                                                                         |
|R10          |ESP32_WROVER_EAGLE-LTSPICE_RR0402            |n/a                                                                                                         |
|RESET_BUTTON |BUTTON_CUSYOMV1                              |https://industry.panasonic.com/global/en/products/control/switch/light-touch/number/evqpuj02k               |
|R_BOOT       |ESP32_WROVER_EAGLE-LTSPICE_RR0402            |n/a                                                                                                         |
|R_CAPACITOR  |ESP32_WROVER_EAGLE-LTSPICE_RR0402            |n/a                                                                                                         |
|R_CHANGE     |ESP32_WROVER_EAGLE-LTSPICE_RR0402            |n/a                                                                                                         |
|R_CL1        |ESP32_WROVER_EAGLE-LTSPICE_RR0402            |n/a                                                                                                         |
|R_RESET      |ESP32_WROVER_EAGLE-LTSPICE_RR0402            |n/a                                                                                                         |
|SENSOR2      |ESP32_WROVER_BME680_BME680                   |https://www.snapeda.com/parts/BME680/Bosch/view-part/?welcome=home                                          |
|SJ1          |SJ                                           |https://grabcad.com/library/solder-jumpers-1                                                                |
|U1           |W25Q512JVEIQ                                 |https://www.snapeda.com/parts/W25Q512JVEIQ/Winbond+Electronics/view-part/?ref=eda                           |
|U2           |ESP32-C6-WROOM-1-N8                          |https://www.snapeda.com/parts/ESP32-C6-WROOM-1-N8/Espressif+Systems/view-part/?ref=eda                      |
|U3           |DS3231SN#                                    |https://www.snapeda.com/parts/DS3231SN%23/Analog+Devices/view-part/?ref=eda                                 |
|U4           |MAX17048G+T10                                |https://www.snapeda.com/parts/MAX17048G+T10/Analog+Devices/view-part/?ref=eda                               |
|U5           |ESP32_WROVER_SPARKFUN-IC-POWER_MCP73831      |https://eu.mouser.com/ProductDetail/Microchip-Technology/MCP73831T-2ACI-OT?qs=yUQqVecv4qvbBQBGbHx0Mw%3D%3Dcf|

## Detailed Hardware Description/Specs:


### Microcontroller – ESP32-C6-WROOM-1-N8

- **Processor:** 32-bit RISC-V, up to 160 MHz  
- **Memory:** 512 KB internal SRAM, 8 MB external flash (W25Q512JVEIQ)  
- **Connectivity:** Wi-Fi 6 (802.11ax), Bluetooth 5 (LE), IEEE 802.15.4 (Thread/Zigbee), USB 2.0 (Full-Speed)  
- **Peripherals:** SPI, I²C, UART, PWM, ADC, multiple GPIOs  

### External Memory – W25Q512JVEIQ

- **Capacity:** 512 Mbit (64 MB)  
- **Interface:** Quad SPI (QPI)  
- **Operating Frequency:** Up to 133 MHz  
- **Supply Voltage:** 2.7 V to 3.6 V  
- **Features:** high endurance (100k write/erase cycles)

### Real-Time Clock – DS3231SN#

- **Accuracy:** ±2 ppm from 0°C to +40°C  
- **Interface:** I²C  
- **Features:** Integrated temperature-compensated crystal oscillator (TCXO)  
- **Voltage Range:** 2.3 V to 5.5 V  
- **Additional:** Battery backup support, 2 programmable alarms, 1Hz square wave output

### Battery Monitor – MAX17048G+T10

- **Function:** Fuel gauge for single-cell Li-ion/Li-Po batteries
- **Interface:** I²C  
- **Voltage Range:** 2.5 V to 4.5 V  
- **Power Consumption:** Ultra-low quiescent current (~23 µA)

### Charge Controller – MCP73831

- **Battery Type:** Single-cell Li-ion/Li-Po  
- **Charging Current:** Programmable up to 500 mA  
- **Interface:** Standalone (no I²C/SPI)  
- **Input Voltage:** 3.75 V to 6 V  
- **Status Output:** Charge status indication via LED

### Environmental Sensor – BME688

- **Measurements:** Temperature, humidity, pressure, gas (VOC, air quality)  
- **Interface:** I²C, SPI  
- **Temperature Range:** -40 °C to +85 °C  
- **Gas Sensor:** AI-based VOC and gas mixture detection  
- **Power Consumption:** Ultra-low power (ideal for mobile/wearables)

### E-Paper Display

- **Interface:** SPI  
- **Resolution:** 800×480
- **Power Usage:** Extremely low (only consumes power during refresh)  
- **Features:** Excellent sunlight readability, wide viewing angles

### Qwiic Connector

- **Type:** JST SH 1.0 mm 4-pin connector  
- **Purpose:** Standardized I²C interconnect for sensors/modules  
- **Voltage:** 3.3 V logic  
- **Pins:** SDA, SCL, VCC, GND  

### SD Memory Card Connector – 112A-TAAR-R03

- **Type:** MicroSD card socket
- **Interface:** SPI or SDIO  
- **Voltage:** Typically 3.3 V logic  
- **Features:** Push-push eject mechanism, card detect switch  
- **Use Case:** Data logging, file storage, media playback

## ESP32-C6 Pin Usage:

| Device        | ESP32-C6 Pin   | Connected Component        | Function                                    |
|:--------------|:---------------|:---------------------------|:--------------------------------------------|
| U2 - ESP32-C6 | GPIO0          | BOOT button                | Enables bootloader mode on startup (input)  |
| U2 - ESP32-C6 | GPIO1          | UART TX                    | Serial communication for debugging/flashing |
| U2 - ESP32-C6 | GPIO2          | UART RX                    | Serial communication for debugging/flashing |
| U2 - ESP32-C6 | GPIO3          | BME688 (I²C SDA)           | Environmental sensor data line              |
| U2 - ESP32-C6 | GPIO4          | BME688 (I²C SCL)           | Environmental sensor clock line             |
| U2 - ESP32-C6 | GPIO5          | MAX17048 (I²C SDA)         | Battery monitor data line (shared bus)      |
| U2 - ESP32-C6 | GPIO6          | MAX17048 (I²C SCL)         | Battery monitor clock line (shared bus)     |
| U2 - ESP32-C6 | GPIO7          | Qwiic Connector SDA        | I²C communication (shared with sensors)     |
| U2 - ESP32-C6 | GPIO8          | Qwiic Connector SCL        | I²C communication (shared with sensors)     |
| U2 - ESP32-C6 | GPIO9          | DS3231 RTC SDA             | I²C data line for real-time clock           |
| U2 - ESP32-C6 | GPIO10         | DS3231 RTC SCL             | I²C clock line for real-time clock          |
| U2 - ESP32-C6 | GPIO18         | E-Paper Display (SPI MOSI) | Serial data out to display                  |
| U2 - ESP32-C6 | GPIO19         | E-Paper Display (SPI CLK)  | Serial clock for display communication      |
| U2 - ESP32-C6 | GPIO20         | E-Paper Display (CS)       | Chip select line                            |
| U2 - ESP32-C6 | GPIO21         | E-Paper Display (DC)       | Data/Command control pin                    |
| U2 - ESP32-C6 | GPIO22         | E-Paper Display (RST)      | Reset line for display                      |
| U2 - ESP32-C6 | GPIO23         | E-Paper Display (BUSY)     | Busy status signal input                    |
| U2 - ESP32-C6 | GPIO13         | SD Card (SPI CS)           | Chip select line for SD card                |
| U2 - ESP32-C6 | GPIO14         | SD Card (SPI MISO)         | Master In Slave Out - reads from SD         |
| U2 - ESP32-C6 | GPIO15         | SD Card (SPI MOSI)         | Master Out Slave In - writes to SD          |
| U2 - ESP32-C6 | GPIO16         | SD Card (SPI CLK)          | SPI clock for SD card communication         |

