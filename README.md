# Motorola Moto G72 Magisk Boot Images

This repository provides prebuilt Magisk patched boot images for the Motorola Moto G72. The Magisk patched boot images can be used to root the device and modify the system.

## Use Cases

The prebuilt Magisk boot images can be useful for the following purposes:

- Rooting the Motorola Moto G72: By flashing the Magisk patched boot image, you can gain root access on your device, allowing you to install root-enabled apps and perform advanced system modifications.

- System Modifications: The Magisk patched boot images can be used to apply various system modifications, such as installing custom ROMs, kernels, or mods that require modifications at the boot level.

## Prerequisites

Before flashing the Magisk patched boot image, ensure that you have the following prerequisites:

- A Motorola Moto G72 device
- A compatible USB cable
- A computer with Fastboot installed (part of the Android SDK Platform Tools)

## Flashing Guide

To flash the Magisk patched boot image on your Motorola Moto G72, follow these steps:

1. Download the prebuilt Magisk patched boot image for your specific device model from the "Releases" section of this repository.

2. Enable USB Debugging on your Motorola Moto G72. To do this, go to "Settings" > "About phone" > Tap on "Build number" 7 times to enable Developer options. Then, go to "Settings" > "Developer options" > Enable "USB Debugging".

3. Boot your Motorola Moto G72 into Fastboot mode. Power off your device, then press and hold the Power button and the Volume Down button simultaneously until you see the Fastboot mode screen.

4. Connect your Motorola Moto G72 to the computer using a USB cable.

5. Open a command prompt or terminal on your computer.

6. Navigate to the directory where you have the Fastboot tool installed (e.g., Android SDK Platform Tools).

7. Verify that your device is properly detected by Fastboot by running the following command:

`fastboot flash boot <path_to_patched_boot_image>`

Replace `<path_to_patched_boot_image>` with the actual path to the downloaded Magisk patched boot image file.

8. Once the flashing process is complete, reboot your device by running the following command:
`fastboot reboot`

After the device reboots, you should have Magisk installed and root access on your Motorola Moto G72.

## Credits

This repository was created by [FiniteCode](https://github.com/FiniteCode) on GitHub, Telegram, and Twitter.

If you encounter any issues or have any questions, feel free to open an issue in this repository.

