# Conexio Stratus Pro nRF9151-LACA-A1A V1.4

**Conexio Stratus Pro** is a tiny-yet-powerful development kit for creating cellular-connected electronic projects and products. Powered by the cutting-edge nRF9151 cellular modem from Nordic Semiconductor, Stratus Pro offers unparalleled versatility, reliability, and ease of use, making it the go-to solution for IoT developers worldwide. It is a battery-operated platform, making it ideal for prototyping cellular IoT systems, such as asset tracking, environmental monitoring, smart metering, and even industrial automation.

With LTE-M, NB-IoT, DECT NR+, NTN, and GPS connectivity packed into a compact form factor, Stratus Pro ensures your devices stay connected in any environment. It enables real-time data transmission and location tracking with minimal power consumption. Future-proof your IoT projects with DECT NR+ readiness, ensuring compatibility with emerging cellular standards for enhanced performance and longevity.

## Built-In Battery Charging, Monitoring and Energy-Harvesting

Thanks to the nPM1300 PMIC and fuel gauge, you can remotely monitor your Stratus Pro’s battery vitals and charging status. Stratus Pro also has built-in charging circuitry that makes it easier to connect to and recharge the Li-Po battery, creating fully energy-autonomous applications.

## Conexio Stratus Pro nRF9151 Pinouts

[Stratus Pro nRF9151 Pinouts](https://docs.conexiotech.com/master/stratus-overview/stratus-pro-nrf9151-pin-diagram)

## Features & Specifications

**MCU**: Nordic nRF9151 Microcontroller 
- ARM Cortex-M33 with 1 MB Flash
- 256 kB RAM
- Pre-programmed MCUBoot bootloader

**Modem**
- Transceiver and baseband
- 3GPP LTE release 14 LTE-M/NB-IoT support
- DECT NR+ ready
- NTN ready
- GPS/GNSS receiver
- RF Transceiver for global coverage supporting bands:
- B1, B2, B3, B4, B5, B8, B12, B13, B17, B18, B19, B20, B25, B26, B28, B65 (new), B66, and B85 (new)
- Supports 4FF Nano SIM, optional eSIM, or software SIM

**Power Management IC: Nordic nPM1300**
- 800 mA battery charger
- Dual 200 mA buck DC/DC regulator
- Charging IC: Texas Instruments BQ25185
- Charge inputs: 3 V to 18 V
- Supports Li-ion, Li-Poly, and LiFePO4 battery chemistries

**Power**
- Operating range 1.8 to 5.5 V
- External LiPo battery connection (2 Pin JST type)
- Maximum output current: 800 mA
- Output voltages (via headers): 1.8 V, 3.3 V, 5 V (VUSB), VBAT
- SPDT slide switch for turning Stratus Pro on or off
- Quiescent current of entire board < 9 μA

**Onboard sensors and storage**
- Battery fuel gauge enabled by nPM1300
- 16 KBit I2C EEPROM memory (24CW160T)

**I/O**
- USB Type-C, for USB-to-Serial, DFU, and application firmware programming and debugging or battery charging
- 1 x U.FL for LTE-M/NB-IoT antenna
- 1 x U.FL for passive GPS antenna
- Total I/O pinouts: 36
- User I/O: Feather-compatible header, 28 programmable GPIO pins, 2 push buttons (1 reset, 1 programmable), 1 programmable LED, 1x RGB LED
- QWIIC connector for external peripherals
- Supports J-Link and CMSIS-DAP-based programmers
- Onboard 10-pin 0.05 " (1.27 mm) mini SWD/JTAG pin connector

**Size**
- 67.04 mm x 22 mm

## Hardware Revision Changes V1.4 (2026)
**Addition**
- RGB LED to NPM1300
- Hardware jumper for voltage selection (1.8V/3.3V)

**Removed**
- LIS2DH sensor

**Bug**
- Fixed backpower introduced by the CP2102N chipset when USB is connected

## Purchase

Conexio Stratus devices and accessories can be purchased directly from our [online store](https://conexiotech.com/shop/).

Please contact [info@conexiotech.com](mailto:info@conexiotech.com) if you would like to arrange help with your manufacturing and custom PCB design based on Stratus Pro platform. 

## Hardware Lineage and License

This board is released under the [CERN OHL-P (v2) license](https://opensource.org/license/cern-ohl-p). See LICENSE for more info.


Copyright (c) 2026 Conexio Technologies, Inc.
