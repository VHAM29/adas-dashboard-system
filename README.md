# 🚗 ADAS Dashboard System

Welcome to the **ADAS Dashboard System** repository! This project showcases a multi-microcontroller vehicle dashboard system equipped with Advanced Driver Assistance Systems (ADAS) features. The system utilizes ESP32, STM32, Arduino, and Python to deliver a real-time user interface and AI-based speed limit detection. 

![ADAS Dashboard](https://img.shields.io/badge/ADAS%20Dashboard%20System-Ready-brightgreen)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Releases](#releases)
- [Contact](#contact)

## Introduction

The ADAS Dashboard System aims to enhance vehicle safety and driver experience through intelligent features. By integrating multiple microcontrollers, this project provides a robust solution for modern automotive needs. The system focuses on real-time data processing and user-friendly interfaces to keep drivers informed and safe.

## Features

- **Real-Time User Interface**: Displays essential vehicle information.
- **AI-Based Speed Limit Detection**: Uses machine learning algorithms to detect speed limits.
- **Multi-Microcontroller Support**: Built on ESP32, STM32, and Arduino platforms.
- **Data Logging**: Records vehicle performance metrics for later analysis.
- **Customizable Dashboard**: Users can tailor the interface to their preferences.
- **Cross-Platform Compatibility**: Works with various operating systems.

## Technologies Used

- **ESP32**: For Wi-Fi and Bluetooth connectivity.
- **STM32**: For robust processing capabilities.
- **Arduino**: To manage sensor data and control interfaces.
- **Python**: For backend processing and AI algorithms.
- **HTML/CSS/JavaScript**: For front-end user interface design.

## Installation

To set up the ADAS Dashboard System, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/VHAM29/adas-dashboard-system.git
   cd adas-dashboard-system
   ```

2. **Install Dependencies**:
   Make sure you have the required libraries for Arduino and Python. Use the following commands to install them:
   ```bash
   pip install -r requirements.txt
   ```

3. **Upload Code to Microcontrollers**:
   - Use the Arduino IDE to upload the relevant code to the Arduino and ESP32.
   - Use STM32CubeIDE for STM32 configurations.

4. **Configure Settings**:
   Modify the configuration files as needed to suit your hardware setup.

5. **Run the Application**:
   Execute the main Python script to start the dashboard system:
   ```bash
   python main.py
   ```

## Usage

Once the installation is complete, you can start using the ADAS Dashboard System. The dashboard will display real-time data such as speed, engine temperature, and fuel level. The AI module will analyze speed limits based on the current location and alert the driver accordingly.

### Dashboard Interface

The dashboard interface consists of:

- **Speedometer**: Displays current speed.
- **Fuel Gauge**: Shows fuel levels.
- **Temperature Indicator**: Monitors engine temperature.
- **Alerts Section**: Provides notifications for speed limits and other warnings.

### Customization

Users can customize the dashboard by editing the configuration files. This includes changing the layout, colors, and the information displayed.

## Project Structure

Here's a brief overview of the project structure:

```
adas-dashboard-system/
│
├── src/
│   ├── arduino/
│   ├── esp32/
│   ├── stm32/
│   └── python/
│
├── config/
│   ├── settings.json
│   └── dashboard_layout.json
│
├── requirements.txt
└── README.md
```

- **src/**: Contains source code for each microcontroller and the Python application.
- **config/**: Holds configuration files for settings and layout.
- **requirements.txt**: Lists Python dependencies.

## Contributing

We welcome contributions to enhance the ADAS Dashboard System. If you have ideas or improvements, please follow these steps:

1. Fork the repository.
2. Create a new branch.
3. Make your changes and commit them.
4. Push to your fork and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Releases

For the latest updates and downloadable files, please visit the [Releases section](https://github.com/VHAM29/adas-dashboard-system/releases). You can download the latest version and execute the necessary files.

## Contact

For questions or feedback, feel free to reach out:

- **Email**: your-email@example.com
- **GitHub**: [VHAM29](https://github.com/VHAM29)

Thank you for your interest in the ADAS Dashboard System! We hope you find this project useful and informative.