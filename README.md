# USB Worm

This project contains a malicious software called USB Worm that spreads through USB drives. This worm aims to spread itself and secretly record the user's keystrokes by performing certain actions on the system.

## Features

- **USB Connection Detection:** Monitors USB drive connections and creates a list of connected USB drives.
- **Writing and Copying to USB:** Copies specific files and script files to infected USB drives.
- **Auto-Execution at Startup:** Makes necessary adjustments to automatically run infected files at Windows startup.
- **Disabling Antivirus:** Executes necessary PowerShell commands to disable Windows Defender.
- **Placing Malicious Files:** Creates copies of malicious files on the system and places them in necessary directories.
- **Keystroke Logging:** Listens to the user's keystrokes in the background and records them to a log file.

## How to Use

1. **Infecting USB Drives:** Once copied to a USB drive, USB Worm automatically runs when the drive is plugged in and initiates spreading processes.
2. **Keystroke Logging:** USB Worm listens to the user's keystrokes in the background and records them to a log file.
3. **Connection and Spreading:** USB Worm infects another USB drive and repeats this process to expand the spreading network.

## Security Warning

The use of this software is illegal and unethical. It is for educational purposes only and should not be used for any malicious activities.
