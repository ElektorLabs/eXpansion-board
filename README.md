# Elektor eXpansion Board v1.01 🚀

Welcome to the GitHub repository for the Elektor eXpansion Board v1.01! This repository contains all the necessary files and documentation for the expansion board designed for Seeed Studio XIAO microcontroller boards.


## What's New in v1.01? ✨
### 🛠️ Improved PCB Layout for Better Performance
We've fine-tuned the overall PCB design to boost both performance and usability.

### 🔗 Enhanced XIAO Board Footprint
Now supports both SMD and THT soldering for greater flexibility in your projects.

### ⚡ Optimized Track Routing
Power, I2C, and UART tracks have been optimized to deliver better signal integrity.

### 🎛️ Improved Button and LED Placement
Enjoy easier accessibility with a more user-friendly layout.

  
## Overview 🌟

The Elektor eXpansion Board v1.0 is designed to enhance the functionality and connectivity of the Seeed Studio XIAO microcontroller lineup, including models like the SMD21, ESP32C3, C6, ESP32S3, and more. This board features multiple connectors and robust protection features, making it ideal for a wide range of applications, from prototyping and educational projects to IoT solutions and field applications.

## Features ✨

- **Multiple Connectivity Options**:
  - 4 Grove I2C connectors 🔌
  - 2 Qwiic connectors 🔌
  - UART output with switchable RX and TX pins via jumpers 🛠️

- **Power Management**:
  - Screw terminal connector for 3V, 5V, and ground ⚡
  - 2mm pitch connector for batteries 🔋

- **Additional Features**:
  - Button and LED for basic input/output functionality 💡
  - ESD protection on 3V, 5V, I2C, and SPI lines to prevent damage from electrostatic discharge 🛡️

## Repository Structure 🗂️

- **hardware**:
  - **elektor-eXpansion-board-V1-0**:
    - **production**: Contains production and Gerber files for the expansion board 🏭
    - **kicad_files**: Contains the KiCad project files for the expansion board 📁

## Getting Started 🛠️

To get started with the Elektor eXpansion Board v1.0, you can clone this repository and open the KiCad project files found in the `hardware/elektor-eXpansion-board-V1-0/kicad_files` directory. The production and Gerber files required for manufacturing the board are located in the `hardware/elektor-eXpansion-board-V1-0/production` directory.

### Cloning the Repository 📥

```bash
git clone https://github.com/elektorLabs/elektor-eXpansion-board-v1.0.git
```

### Opening the Project in KiCad 💻

1. Open KiCad.
2. Navigate to the cloned repository folder.
3. Open the KiCad project file located in `hardware/elektor-eXpansion-board-V1-0/`.

### Manufacturing the Board 🏭

To manufacture the Elektor eXpansion Board v1.0, use the Gerber files located in the `hardware/elektor-eXpansion-board-V1-0/production` directory. These files can be uploaded to any PCB manufacturing service.

## Contribution 🤝

Contributions to this project are welcome! If you have any suggestions, improvements, or bug fixes, please submit a pull request or open an issue.

## License 📜

This project is licensed under the CC BY-NC 4.0 LEGAL CODE - Attribution-NonCommercial 4.0 International. See the [LICENSE](https://creativecommons.org/licenses/by-nc/4.0/legalcode.en) file for more details.

## Contact 📧

If you have any questions or need further assistance, feel free to open an issue on this repository or contact the project maintainer.

Happy tinkering! 🛠️✨
