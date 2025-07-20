# Waveshare ESP32-P4-86-Panel-ETH-2RO & ESPHome  
*First Tests and Integration Guide*

---

## 🚀 Overview

This project showcases the **first tests of the Waveshare ESP32-P4-86-Panel-ETH-2RO** running on [ESPHome](https://esphome.io/).  
All core components are functional. You can experiment with [LVGL](https://esphome.io/components/lvgl/) and freely modify the configuration.

> **Tested on ESPHome version: `2025.7.2`**

---

## ✨ Features

- **Ethernet & WiFi support**  
  *(Switch between them via configuration)*
- **Voice Assistant Integration**  
  *(Works with Home Assistant voice assistant – see video below)*
- **Online Radio Playback**  
  *(Russian radio station demo – see video below)*
- **LVGL UI experiments**  
  *(Open for your creativity!)*

---

## ⚙️ Getting Started

### 1. Hardware

- [Waveshare ESP32-P4-86-Panel-ETH-2RO](https://www.waveshare.com/wiki/ESP32-P4-86-Panel-ETH-2RO)

### 2. ESPHome Configuration

- **WiFi or Ethernet:**  
  - To use **WiFi**:  
    - Uncomment `esp32_hosted` and `wifi` sections  
    - Comment out the `ethernet` section
  - To use **Ethernet**:  
    - Uncomment the `ethernet` section  
    - Comment out `esp32_hosted` and `wifi`

> **Note:**  
> ESP32-P4 support in ESPHome is still experimental. Bugs may occur!

### 3. Flashing / Installation

**Option 1:**  
Copy the contents of this repository into the `esphome` folder of your Home Assistant installation.

**Option 2:**  
Clone this repository directly using Visual Studio Code (VSCode)

---

## 🗣️ Voice Assistant

- Integrates with Home Assistant’s voice assistant.
- Requires additional configuration in Home Assistant for full functionality.

**Demo Video:**  
[![Voice Assistant Demo](https://img.youtube.com/vi/v7quMFinaK0/0.jpg)](https://youtube.com/shorts/v7quMFinaK0?si=J8VmZL8C5pM8W2Lc)

---

## 📻 Online Radio

- Plays a Russian online radio station.
- Easily customizable for other streams.

**Demo Video:**  
[![Online Radio Demo](https://img.youtube.com/vi/_DiCLF-6ztk/0.jpg)](https://youtube.com/shorts/_DiCLF-6ztk?si=kzCkzMouhMckeV-K)

---

## 🧪 LVGL UI Experiments

- Feel free to experiment with LVGL widgets and layouts.
- Contributions and creative ideas are welcome!

---

## 📝 Notes

- ESP32-P4 support is **experimental** in ESPHome.
- Some features may be unstable or buggy.
- Tested and working on ESPHome version `2025.7.2`.

---

## 📬 Feedback & Contributions

- Found a bug? Have an idea?  
  Open an issue or submit a pull request!

---

## 📚 Useful Links

- [ESPHome Documentation](https://esphome.io/)
- [Waveshare ESP32-P4-86-Panel-ETH-2RO](https://www.waveshare.com/wiki/ESP32-P4-86-Panel-ETH-2RO)
- [LVGL Documentation](https://esphome.io/components/lvgl/)

---

**Enjoy experimenting with your Waveshare ESP32-P4-86-Panel and ESPHome!**
