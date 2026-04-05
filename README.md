# Smart Air Transmitter System using DHT11 and FreeRTOS

This repository contains the STM32F429ZI-based Smart Air Transmitter System project.
It uses a DHT11 temperature and humidity sensor with FreeRTOS on the STM32F4 platform.

## Project Contents

- `Core/Inc` and `Core/Src`: main application source files and headers
- `Drivers`: STM32Cube HAL drivers and CMSIS device headers
- `Middlewares/Third_Party/FreeRTOS`: FreeRTOS kernel source
- `.ioc`, `.project`, and IDE settings for STM32CubeIDE
- `STM32F429ZITX_FLASH.ld`, `STM32F429ZITX_RAM.ld`: linker scripts

## Features

- Reads temperature and humidity using DHT11 sensor
- Uses FreeRTOS tasks for sensor reading and data processing
- Built for STM32F429ZI development board

## How to use

1. Open `PR1_smart_air_TX_IOT_SENSOR_NODE.ioc` in STM32CubeIDE.
2. Build the project.
3. Flash to the STM32F429ZI board.

## Notes

- This repository includes HAL drivers and FreeRTOS sources required for building the project.
- The `.gitignore` already excludes build output and temporary files.
