# LVGL ESPhome Waveshare-ESP32-P4-86-Panel-ETH-2RO custom firmware

<p align="center">
 <img width="200px" src="/doc/images/loading.png">
 <img width="200px" src="/doc/images/home.png">
 <img width="200px" src="/doc/images/forecasts.png">
 <img width="200px" src="/doc/images/info.png">
 <img width="200px" src="/doc/images/settings.png">
 <img width="200px" src="/doc/images/light0.png">
 <img width="200px" src="/doc/images/light1.png">
 <img width="200px" src="/doc/images/climate0.png">
 <img width="200px" src="/doc/images/climate1.png">
 <img width="200px" src="/doc/images/climate2.png">
 <img width="200px" src="/doc/images/climate3.png">
 <img width="200px" src="/doc/images/media_player.png">
 <img width="200px" src="/doc/images/vacuum.png">
</p>

<p align="center">
    <img alt="Static Badge" src="https://img.shields.io/badge/made%20by-alaltitov-blue">
    <img alt="Static Badge" src="https://img.shields.io/badge/version-v1.0%20Dev-green">
    <img alt="Static Badge" src="https://img.shields.io/badge/esphome min version-2025.11.0-red">
    <img alt="Static Badge" src="https://img.shields.io/badge/license-MIT-orange">
</p>

## Support the Project

<img src="/doc/images/donate.png" alt="QR Code" width="150" align="left" hspace="10"/>

<div style="padding-top: 40px;">
  <b>Support me on</b>
  <div style="height: 30px;"></div>
  <a href="https://boosty.to/altitov/donate">
    <img src="/doc/images/boosty.png" alt="Boosty" width="160"/>
  </a>
</div>

<br clear="all"/>

## Questions, Discussions, Ideas

<a href="https://t.me/esphome_lvgl_chats">
  <img src="/doc/images/t_me-esphome_lvgl_chats.jpg" alt="QR Code" width="150" align="left" hspace="10"/>
</a>

## ⚠️ Important Notice
- You'll need the DEV version of ESPHome 2025.11.0.

## ✨ Features

- Status indicators for Wi-Fi, Home Assistant API, thermostat, air conditioner, touchscreen lock, alarm panel
- Weather icons with current conditions and temperature
- Weather Forecasts daily and hourly
- Date and time
- Sensor readings from Home Assistant
- Voice Assistant (testing...)
- Lights control
- Alarm Panels control
- Climate control
- Covers control
- Fans control
- Media Player control
- Radio control (testing...)
- Vacuum control
- Settings:
  * Backlight adjustment
  * Screen timeout settings
  * Language selection:
    - ru (from [alaltitov](https://github.com/alaltitov))
    - en (from [alaltitov](https://github.com/alaltitov))
    - pl (from [reaper7](https://github.com/reaper7))
    - fr (from [lboue](https://github.com/lboue))
    - es (from Antonio)
    - nl (from [zjean](https://github.com/zjean))
    - si (from [Protoncek](https://github.com/Protoncek))
    - it (from [echopage1964](https://github.com/echopage1964))
    - de (from [MATZE-MAN](https://github.com/MATZE-MAN))

## 📦 Installation
> 📹 **Video [instruction](https://youtu.be/HYN_2hvcbes?si=JfYQH4vCuFlr8Q9r)**

<img width="400px" src="/doc/images/ha_options.png">

- You must enable the "Allow the device to perform Home Assistant actions." option in the ESPHome integration to Home Assistant to control devices.
- Install custom component for forecasts and covers for media player from [here](https://github.com/alaltitov/homeassistant-display-tools).
- Copy repository to vscode or to esphome folder of your Home Assistant. Change substitutions.yaml and config.yaml your entities in all widgets (only in substitution, in code everything will be substituted automatically).

## 📖 Documentation
- [ESPHome LVGL 8.4](https://esphome.io/components/lvgl/)

## 🤝 Thanks for your help
- Thanks to [ZHNovell](https://github.com/ZHNovell) for financial support of the project, as well as for help with testing and ideas.
- Thanks, [сlydebarrow](https://github.com/clydebarrow), [jesserockz](https://github.com/jesserockz), [ssieb](https://github.com/ssieb) for helping me with the project!

