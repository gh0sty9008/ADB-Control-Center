# ADB Control Center

A lightweight Windows-based Android device management toolkit built with Batch scripting and Android Debug Bridge (ADB).

## Features

### Device Management

* List connected Android devices.
* Connect to devices over Wi-Fi.
* Disconnect devices.
* Restart the ADB server.

### Installation & Reboot

* Open an ADB shell.
* Install APK files.
* Reboot the device.
* Reboot into Recovery Mode.
* Reboot into Bootloader Mode.

### Backup & Restore

* Copy DCIM folders to the PC.
* Copy Pictures folders to the PC.
* Back up both folders.

### Diagnostics

* Live Logcat viewer.
* Export Logcat logs.
* Battery information.
* Storage information.
* Device information.

### Screen Tools

* Take screenshots.
* Record the device screen.

### Package Manager

* List third-party applications.
* Uninstall applications for the current Android user.

### Custom Commands

* Execute custom ADB commands.
* Execute custom Fastboot commands.

## Requirements

* Windows 10 or Windows 11.
* Android device with USB Debugging enabled.
* Android SDK Platform-Tools.
* USB cable or a supported wireless ADB connection.
* Android SDK Platform-Tools are required.

Download them from the official Google website:
https://developer.android.com/tools/releases/platform-tools

Extract Platform-Tools into the expected project directory.

## Installation

1. Download the project.
2. Extract the archive.
3. Make sure Android Platform-Tools are available in the expected folder.
4. Connect your Android device.
5. Enable USB Debugging.
6. Run `ADB_Launcher.bat`.

## Tested Devices

* Samsung Galaxy S7 (SM-G930F)

Other Android devices may work depending on their Android version, manufacturer and supported ADB features.

## Important Notes

* This project is not an official Google or Android product.
* Some functions may behave differently depending on the device.
* Fastboot is not supported by every Android device.
* The backup functions copy accessible media folders; they do not create a complete device backup.
* Uninstalling packages may affect device functionality. Use caution.

## Disclaimer

This software is provided "as is", without warranty of any kind.

The author is not responsible for data loss, device malfunction or other issues resulting from the use of this software.

## License

This project is licensed under the MIT License.

See the `LICENSE` file for details.

## Author

Developed independently by [gh0sty9008].

## Version

**Current version: 1.1**
