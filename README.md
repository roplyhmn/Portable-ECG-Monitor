# Portable-ECG-Monitor

## Overview
This project is a portable ECG monitoring system using STM32 to measure heart rate (BPM) in real-time.

## Features
- Real-time ECG signal acquisition
- BPM calculation using peak detection
- OLED display (SSD1306 via I2C)

- ## Tech Stack
- STM32 (ARM Cortex-M4)
- Embedded C
- ADC, I2C

## Hardware Components
- STM32 board
- AD8232 ECG Sensor
- OLED Display

## How It Works
1. Sensor reads ECG signal
2. ADC processes signal
3. Peak detection calculates BPM
4. Display shows result
