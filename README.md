ESPHome LD2450 mmWave Radar Sensor Custom Component

## Installation
Set wifi_ssid and wifi_password in your esphome's secrets.yaml first

1. Place ld2450_uart.h into the components of your esphome configuration folder
2. Create new device with the yaml in this repository

## Wiring
ESP8266  | | LD2450
---------|-|-------|
5V      |<->| VCC
GND     |<->| GND
TX      |<->| RX
RX      |<->| TX

## Notice
1. The RX, TX need pull-up resister.
2. Need to upgrade to firmware 1.1.230605 (recommended)
3. Use hardware serial if use ESP8266.
