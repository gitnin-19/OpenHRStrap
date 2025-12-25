# 🚀 OpenHRStrap - Track Your Heart Rate Easily

## 📥 Download Now
[![Download OpenHRStrap](https://img.shields.io/badge/Download-OpenHRStrap-brightgreen)](https://github.com/gitnin-19/OpenHRStrap/releases)

## 📖 Overview
OpenHRStrap is an open-source DIY chest-strap heart-rate tracker built around the ESP32. It measures real biosignals through electrodes, filters the signal, and applies the Pan–Tompkins algorithm to detect R-peaks and compute heart rate in real-time. This device is perfect for anyone looking to monitor their heart rate during workouts or daily activities.

## 🚀 Getting Started
To use OpenHRStrap, you will need the following:

- An ESP32 microcontroller
- Electrodes for measuring biosignals
- A compatible power source (battery or USB)
- Basic knowledge of using Arduino IDE

## 📦 System Requirements
- **Operating System:** Windows, macOS, or Linux
- **Software:** Arduino IDE installed on your device
- **Memory:** At least 512 MB of RAM
- **Storage:** 100 MB of free space

## 🔧 Features
- Real-time heart rate monitoring
- Accurate biosignal filtering
- Easy setup and configuration
- Open-source and customizable

## 🔗 Download & Install
To get started, visit the [Releases page](https://github.com/gitnin-19/OpenHRStrap/releases) to download the latest version. Follow these steps:

1. Go to the Releases page through this link: [OpenHRStrap Releases](https://github.com/gitnin-19/OpenHRStrap/releases).
2. Find the latest release version. It will be at the top of the page.
3. Click on the download link for the appropriate file, usually in a format like `.zip` or `.tar.gz`.
4. Once the file has downloaded, extract it to your desired location on your computer.

Make sure you have the Arduino IDE set up. If you don’t have it yet, you can download it from the [Arduino website](https://www.arduino.cc/en/software).

## 💻 Setup Instructions
1. Open the Arduino IDE.
2. Install the ESP32 board package by going to **File > Preferences**, and adding the following URL in the "Additional Board Manager URLs" field:
   ```
   https://dl.espressif.com/dl/package_esp32_index.json
   ```
3. Navigate to **Tools > Board > Boards Manager** and search for "ESP32". Install it.
4. Download the OpenHRStrap code from the extracted folder.
5. Open the `.ino` file in Arduino IDE.
6. Select the right board type under **Tools > Board** (choose "ESP32 Dev Module").
7. Connect your ESP32 to your computer using a USB cable.
8. Set the appropriate COM port under **Tools > Port**.
9. Upload the code by clicking the right arrow button at the top left of the Arduino IDE.

## 📱 Using OpenHRStrap
Once you've set everything up, put on the chest strap and turn on your ESP32 device. You should see real-time heart rate data on your connected monitor. Adjust the sensor placement as needed for the best readings.

## ⚙️ Troubleshooting
If you encounter issues:
- Ensure your ESP32 is connected properly.
- Double-check all connections and settings.
- Make sure the Arduino IDE is up to date.
- Look for common errors in the output console of the IDE for guidance.

## 📞 Support
If you need help, visit our GitHub page to report issues or ask questions in the community section. 

## 💬 Contributing
We welcome contributions! If you want to help improve OpenHRStrap:
1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Make your changes and test them.
4. Submit a pull request with a clear description of your changes.

## 🌐 Join the Community
Stay connected with other users and developers. Join our discussions and share your experiences in the relevant online forums and social media groups related to OpenHRStrap.

## 🔗 Links
- **Source Code**: [OpenHRStrap GitHub Repository](https://github.com/gitnin-19/OpenHRStrap)
- **Releases**: [OpenHRStrap Releases Page](https://github.com/gitnin-19/OpenHRStrap/releases)

Thank you for choosing OpenHRStrap! Your feedback helps us improve the experience. Happy tracking!