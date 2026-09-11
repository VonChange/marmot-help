# TV Remote Guide

Control your smart TV with your phone using natural touch gestures such as swipe, tap, and touch and hold.

## Before You Start

### 1. Enable ADB Debugging on the TV

TV Remote requires ADB debugging on the TV. On most Google TV / Android TV devices the steps are the same. See [How to Enable ADB Debugging](adb.md).

### 2. Use the Same Wi-Fi Network

Your phone and TV must be connected to the **same Wi-Fi network**.

## How to Use It

The TV Remote page has **one device entry point**: tap **Devices** ![Devices button](../image/fx.jpg) in the upper-right corner. The app searches for every TV on the local network at the same time. TVs with the service already installed and TVs that require first-time pairing appear in the same list.

### First Connection (One-Time Setup)

1. Open Marmot TV Remote and tap **TV Remote**.
2. Tap **Devices** in the upper-right corner and wait for your TV to appear.
3. If the TV shows **Install Service**, tap it. When the TV asks for authorization, select **Allow**.
4. The TV component is **installed automatically** after authorization. **When installation is complete**, the TV appears at the top of the list. Tap it again to connect.

### Daily Use

1. Open Marmot TV Remote and tap **TV Remote**.
2. Tap **Devices** in the upper-right corner and select your TV.
3. After connecting, you can use the air mouse and touch remote.

> 💡 Each TV only needs to be authorized and installed once. If the list reports a service problem, tap **Repair**. If your TV is not found, enter its IP address manually at the bottom of the list.

## Controls

### 🖱️ Air Mouse Remote

Tap the **Air Mouse** button in the bottom toolbar to enable touch controls:

- **Move the pointer:** Slide your finger across the touchpad.
- **Click:** Tap the touchpad.
- **Touch and hold:** Touch and hold the touchpad.
- **Scroll vertically:** Swipe up or down in the vertical area on the right.
- **Scroll horizontally:** Swipe left or right in the horizontal area at the bottom.

### 🎮 Directional Controls

- **Up, down, left, and right:** Move the TV focus.
- **OK:** Confirm the selected item.

### 📺 Quick Actions

- **Back:** Go back to the previous screen.
- **Home:** Return to the TV home screen.
- **Volume +/-:** Adjust the volume.
- **Mute:** Mute or unmute the TV.

### ⌨️ Real-Time Text Input

When a text field on the TV receives focus, an input field automatically appears on your phone. Text entered on the phone is **synchronized in real time** with the TV.

### 📱 App Management

- **Install apps:** Upload and install an APK through **File Manager**, or upload it directly from **Utilities**.
- **Uninstall apps:** Remove apps from the TV.
- **Disable apps:** Disable unwanted preinstalled apps.
- **Set the default launcher:** Open **Utilities > Set Default Launcher** and select an installed launcher to open when the Home button is pressed. Some TVs require confirmation in the system chooser. If only the system launcher is listed, install another launcher app first.

## Frequently Asked Questions

### Q: Why can I not find my TV?

1. Tap **Devices** in the upper-right corner and wait for the list to update. If the TV is not found, enter its IP address manually at the bottom, or tap **Repair** or **Install Service**.
2. Check that:
   - **ADB debugging** is enabled on the TV.
   - Your phone and TV are on the **same Wi-Fi network**.

### Q: Why did the authorization prompt not appear during the first connection?

Some TVs require both **USB debugging** and **network debugging** to be enabled in Developer options.

### Q: How can I enable ADB without a computer?

If your phone runs a version **earlier than Android 11**, use the in-app [ADB OTG](marmot://adb-otg-page) feature. Connect another Android phone that supports OTG to the TV with an OTG cable to enable debugging **without using ADB on a computer**.

### Q: What settings are required on Android 11 or later?

In **Developer options**, turn on **USB debugging**. If available, also turn on **Wireless debugging** or **Network debugging**.

On a few devices you may also need:

- **USB debugging (Security settings)**
- **Install via USB** / allow installs via ADB

Then return to the app and connect.

### Q: How do I enable ADB?

See [How to Enable ADB Debugging](adb.md).

## Need More Help?

- See the [FAQ](faq.md).
- Return to the [Help Home](README.md).
