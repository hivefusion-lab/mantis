# Mantis

Mantis is an open-source USB automation platform built by HiveFusion Lab. It allows you to create and run automation scripts on a simple STM32 Blue Pill development board with an external SPI flash memory.

> **Note:** The firmware source code is currently not available. This repository provides the official firmware releases, documentation, and setup guides.

---

## Learn More

🌐 Product Page
https://lab.hivefusion.in/mantis

📖 Documentation
https://lab.hivefusion.in/mantis-documentation

---

# Features

* USB automation
* Easy firmware updates
* External SPI flash storage
* DIY friendly hardware
* Open-source hardware platform

---

# Hardware Required

* STM32 Blue Pill (STM32F103C8T6)
* W25Q Series SPI Flash Memory
* USB Cable
* ST-Link or USB-to-UART programmer (for flashing firmware)

---

# Wiring

Connect the SPI flash to the STM32 Blue Pill as shown below.

| STM32 Pin | Function         | SPI Flash Pin |
| --------- | ---------------- | ------------- |
| PA4       | Chip Select (CS) | CS            |
| PA5       | SPI Clock (SCK)  | CLK           |
| PA6       | SPI MISO         | DO            |
| PA7       | SPI MOSI         | DI            |

### Buttons & Indicators

| STM32 Pin | Function                        |
| --------- | ------------------------------- |
| PA0       | Mode Select Button (Active LOW) |
| PC13      | Onboard Status LED (Active LOW) |

---

# Firmware

You can download the latest firmware from the **Releases** section of this repository.

Each release includes:

* Firmware binary
* Release notes
* Version information

---

# Flashing the Firmware

1. Download the latest firmware from the Releases page.
2. Connect your STM32 Blue Pill using an ST-Link or USB-to-UART programmer.
3. Flash the firmware to the board.
4. Power cycle the board.
5. Your Mantis device is now ready to use.

A detailed flashing guide will be added soon.

---

# DIY Setup

Mantis is designed to be easy to build yourself.

The complete DIY guide includes:

* Hardware assembly
* Wiring
* Firmware flashing
* First boot
* Troubleshooting

For the complete guide, visit:

https://lab.hivefusion.in/mantis-documentation

---

# Uploading Programs

Once the firmware is installed, you can upload and manage your automation scripts using the Mantis software.

The complete guide for creating and uploading programs is available in the documentation.

https://lab.hivefusion.in/mantis-documentation

---

# Documentation

For detailed information, including setup guides, scripting, troubleshooting, and updates, visit:

https://lab.hivefusion.in/mantis-documentation

---

# Product Page

Learn more about Mantis:

https://lab.hivefusion.in/mantis

---

# License

The firmware binaries in this repository are provided by HiveFusion Lab.

The source code is not included at this time.
