# KonteX License Updater
Updates the capabilities of your XDAQ

## Tested on
- Windows
  - 10
  - 11
- macOS
  - 13 (Ventura)
- Ubuntu
  - 22.04

## Installation
First, Download the latest release from the GitHub releases page [here](https://github.com/kontex-neuro/License-Updater/releases) for your operating system, then follow the instructions below.

### Windows
1. Install Front Panel USB Drivers from [Opalkelly](https://pins.opalkelly.com/downloads) if you haven't already. It's most likely already installed if you can run any acquisition software.
2. Open the zip file and run the installer
   * If you get a warning from Windows Defender, click on "More info" and then "Run anyway"

### macOS
1. Extract the app bundle by double-clicking on the zip file
2. **Right-click** on the app bundle and click on "Open"
   * If you get a warning from macOS, click on "Open"

### Ubuntu
1. Extract the zip file and give extracted .AppImage the executable permissions by `chmod +x`.
2. Make sure you have the right permissions for your device. `sudo chmod 666 /dev/bus/usb/YOUR_DEVICE`
