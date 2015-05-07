# ADB-Wireless.app
Mac Only!  For Android devices running KitKat 4.4 or XE22.

Automates registation process for Android Debug Bridge over WiFi.  

The purpose of this build is to streamline the registration of USB and WiFi connected Android devices to the Android Debug Bridge --> (ADB). It is designed to be an all in one, lightweight, ready to use setup to quickly register and allow commandline input for ADB through the terminal application.

How to use:

Make sure the android device has WiFi enabled and is connected to the same WiFi network as the mac being used.  It will be necessary to trust the connected Mac during this process, at some point the device will ask to trust the computer.  Select --Trust--.

First time, connect your Android device to Mac with a USB cable.  Run ADB-Wireless.app application.  A terminal window should open and near the bottom display the IP address of the connected android device.  Wait for it to process, when the dialog box appears select --Configure--. Copy the IP Address of the device (it should look something like this 192.168.1.13) and enter it into IP dialog window.  The registration process will repeat in terminal the device is then ready to go.

The device's IP is now stored and it can be quickly registered with ADB by opening the application ADB-Wireless.app and selecting WiFi from the dialog box.

If the network, location or device used is changed simply connect the device to the mac with a usb cable and run ADB Wireless and select configure.

This application uses applescript to run the terminal processes necessary to register an Android device to ADB.  The ADB files from the most recent version of SDK are included in the application. There is no need to download SDK to use ADB.

To see the applications contents right click on the app icon and select Show Package Contents.
