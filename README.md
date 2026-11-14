# <img src="https://raw.githubusercontent.com/MiaClaire7/Clickr/main/assets/clickr_logo.png" width="48" height="48" align="middle" alt="Clickr Logo"/> Clickr

<p align="center">
  <strong>Bluetooth LE Kindle Page Turner Remote for Android</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android Platform"/>
  &nbsp;&nbsp;
  <a href="https://github.com/MiaClaire7/Clickr/releases/latest"><img src="https://img.shields.io/badge/Release-APK%20Download-7C3AED?style=for-the-badge&logo=android&logoColor=white" alt="Download APK"/></a>
</p>

---

## 📖 Overview

**Clickr** is a modern, minimalist Android application that transforms your smartphone into a dedicated Bluetooth LE (BLE) HID remote control designed specifically for Kindle e-readers. Whether you are reading in bed with your phone on a bedside stand or holding it in one hand, Clickr lets you effortlessly turn pages, adjust screen brightness, and put your Kindle to sleep.

---

## ✨ Key Features

* **📖 Ergonomic Page Controls**: Side-by-side, touch-optimized **Page Back** and **Page Forward** buttons designed for effortless one-handed reading.
* **🔊 Screen-Off Volume Key Turning**: Use your phone's physical hardware volume keys to turn pages (Volume Down = Forward, Volume Up = Back) even when the phone screen is completely off.
* **🔒 Lockscreen Integration**: Operates directly over your phone's lock screen so you can wake and click instantly without unlocking your device.
* **💡 Display & Power Management**: Quick controls for **Light −** / **Light +** brightness adjustment and **Hold-to-Sleep** for your Kindle.
* **⚡ Battery Level Reporting**: Broadcast your phone's current battery level (or a custom slider value) to display directly on your Kindle.
* **🎨 Modern Minimalist Design**: Flat, shadow-free cards, smooth rounded bezel edges, and a calming soft lavender light theme.

---

## ⚙️ Requirements & Compatible Devices

### Android Requirements
* **Android Version**: Android 5.0 (API Level 21) or higher.
* **Hardware**: Android device with Bluetooth LE (BLE) Peripheral advertising support.

### Compatible Kindle Devices
Clickr works with Kindle models supporting Bluetooth accessibility features and remote accessories (based on [Amazon's Official Kindle Bluetooth Guide](https://www.amazon.com/gp/help/customer/display.html?nodeId=T4Es1zUH4B8nnqvRfS)):
* Kindle 2026
* Kindle Paperwhite 2026
* Kindle Colorsoft 2026
* Kindle 2024
* Kindle Paperwhite 2024
* Kindle Colorsoft 2024
* Kindle Scribe - 2024 Release
* Kindle Scribe (without Front Light)
* Kindle Scribe - 3rd Generation
* Kindle Scribe Colorsoft (1st Generation)

---

## 🔗 Bluetooth Pairing Guide

1. On your Kindle, navigate to **Settings › Wi-Fi & Bluetooth › Bluetooth devices**.
2. Open **Clickr** on your Android phone.
3. Select your phone from the list of available Bluetooth devices on your Kindle and confirm the pairing code on both devices.
4. Once connected, Clickr will automatically maintain the BLE HID link.

---

## 👨‍💻 Original Creator & Acknowledgments

* **Original BLE HID Library**: Created by **K. Shoji** ([kshoji/BLE-HID-Peripheral-for-Android](https://github.com/kshoji/BLE-HID-Peripheral-for-Android)).
* **Kindle Click Implementation / Base**: Based on [zuyan9/Open-Kindle-Click-Android](https://github.com/zuyan9/Open-Kindle-Click-Android).
* **UI Redesign & Modernization**: Rebranded and redesigned as **Clickr** with a modern light aesthetic, custom vector iconography, and optimized screen-off ergonomics.

---

## 📄 License

```text
Copyright (C) K. Shoji
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
