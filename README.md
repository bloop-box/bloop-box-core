# bloop-box-core

[![CI](https://github.com/bloop-box/bloop-box-core/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/bloop-box/bloop-box-core/actions/workflows/ci.yml)

![3D Render](https://bloop-box.github.io/bloop-box-core/3D/bloop-box-core-3D_top.png)

[Hardware Documentation](https://bloop-box.github.io/bloop-box-core)

### !!! THIS IS A PROTOTYPE WORK IN PROGRESS !!!


## What does it do?

This board is supposed to replace the Raspberry Pi Zero 2W in the bloop box with a cheaper alternative, using an ESP32-C5.

It will support all functions of the bloop box and can be used as a drop-in-replacement for the Raspi. In addition, due to the capabilities of the ESP32-C5 this will have support for 5GHz WiFi.

## GPIO

| Function       | ESP-Pin |
|:---------------|:--------|
| Button1 (BOOT) | GPIO 28 |
| Button2        | GPIO 27 |
| LED1           | GPIO 25 |
| LED2           | GPIO 26 |
| I2C SCL        | GPIO 3  |
| I2C SDA        | GPIO 2  |
| I2S BCLK       | GPIO 23 |
| I2S DIN        | GPIO 4  |
| I2S LRCLK      | GPIO 24 |
| SPI MISO       | GPIO 9  |
| SPI MOSI       | GPIO 8  |
| SPI SCK        | GPIO 6  |
| NFC CS         | GPIO 10 |
| NFC IRQ        | GPIO 0  |
| NFC RST        | GPIO 1  |
| SD CS          | GPIO 5  |
| SD Detect      | GPIO 7  |
| Serial RX      | GPIO 12 |
| Serial TX      | GPIO 11 |
