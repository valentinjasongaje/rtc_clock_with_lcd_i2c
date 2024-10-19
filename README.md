# Arduino RTC Module with LCD Display

![RTC Module](link-to-image)  <!-- Replace with an actual image URL -->

## Description

This repository contains code and resources for interfacing an Arduino with a Real-Time Clock (RTC) module and an I2C LCD display. The RTC module keeps track of the current time and date even when the Arduino is powered off, using a small battery for backup. The LCD display shows the current date and time.

## Features

- Accurate timekeeping using RTC modules like DS1307, DS3231, etc.
- Easy integration with Arduino using I2C communication.
- Display current date and time on an I2C LCD.
- Ability to set, read, and display the current time and date.

## Hardware Requirements

- Arduino board (e.g., Arduino Uno, Nano, etc.)
- RTC module (e.g., DS1307, DS3231)
- I2C LCD display (e.g., 16x2)
- Jumper wires
- Breadboard (optional)

## Wiring Diagram

RTC Module Arduino
Arduino           RTC Module(DS1302)
5V --------------- VCC
GND -------------- GND
D5 --------------- CLK
D4 --------------- DATA
D2 --------------- RST

I2C LCD Arduino
Arduino           LCD I2C
5V --------------- VCC
GND -------------- GND
SDA -------------- A4
SCL --------------- A5

## Software Requirements

- Arduino IDE
- [RTClib Library](https://github.com/Makuna/Rtc) (install via Library Manager)
- [LiquidCrystal I2C Library](https://github.com/johnrickman/LiquidCrystal_I2C) (install via Library Manager)

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/valentinjasongaje/rtc_clock_with_lcd_i2c.git
