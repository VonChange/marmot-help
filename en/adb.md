# How to Enable ADB Debugging

ADB (Android Debug Bridge) lets Marmot TV Remote connect to your TV or TV box over the local network.

On most **Google TV** and **Android TV** devices sold internationally, the steps are the same. You do **not** need brand-specific factory codes.

**Common devices this guide covers:**

- Chromecast with Google TV / Google TV Streamer
- NVIDIA Shield TV
- Onn Google TV / Walmart streaming devices
- TCL, Hisense, Sony, Philips, and other TVs running **Google TV** or **Android TV**
- Many Android TV boxes sold outside China

> Keep your phone and TV on the **same Wi-Fi** network before connecting in the app.

---

## Google TV / Android TV (recommended)

### 1. Open Developer options

1. Open **Settings** on the TV.
2. Go to **System** → **About** (sometimes **Device Preferences** → **About**).
3. Select **Build** / **Build number** and press **OK** about **7 times** until you see a message that developer mode is enabled.

### 2. Enable debugging

1. Go back to **Settings**.
2. Open **System** → **Developer options**  
   (on some devices: **Device Preferences** → **Developer options**).
3. Turn on **USB debugging**.
4. If you see **Network debugging**, **Wireless debugging**, or **ADB over network**, turn that on too.

### 3. Allow the connection

1. Open Marmot TV Remote on your phone and connect to the TV.
2. When the TV shows an authorization prompt, choose **Allow** / **OK**.
3. Optionally check **Always allow from this computer** so you do not need to approve again.

That is usually all you need for overseas Google TV and Android TV devices.

---

## Menu names may look slightly different

Different brands keep the same flow, but labels can vary:

| Look for | Also called |
|----------|-------------|
| About | About device / Device information |
| Build number | Android TV OS build / System version |
| Developer options | Developer settings |
| USB debugging | ADB debugging / USB debugging mode |
| Network / Wireless debugging | ADB over network / Network ADB |

If you cannot find **Developer options**, search Settings for `developer` or `ADB`.

---

## Amazon Fire TV (optional)

1. Open **Settings** → **My Fire TV** → **About**.
2. Select **Your Fire TV** (or the device name) and press the remote **OK** button **7 times**.
3. Go back and open **Developer options**.
4. Enable **ADB debugging**.
5. Enable **Apps from Unknown Sources** if the TV asks for it during install.

---

## Tips

- Prefer **Wi-Fi**, not guest networks or phone hotspots that isolate devices.
- After enabling ADB, restart the TV if it does not appear in the app.
- First connection needs a one-time **Allow** on the TV screen.
- Some hotels or enterprise Wi-Fi block device discovery; try a home network.

---

## Still stuck?

1. Confirm the TV runs **Google TV**, **Android TV**, or **Fire TV**.
2. Confirm **USB debugging** (and network/wireless debugging if available) is on.
3. Confirm phone and TV share the same Wi-Fi name.
4. In Marmot TV Remote, open **TV Remote** → **Devices**, then try again or enter the TV IP manually.

See also [Getting Started](getting-started.md) and the [FAQ](faq.md).
