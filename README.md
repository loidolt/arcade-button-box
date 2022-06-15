---
published: true
status: complete
date: 11/01/2021
tags: 3d-printing, electronics
description: Arcade button in a box for the sake of clicky satisfaction
slug: arcade-button-box
---
# Arcade Button Box
Arcade button in a box for the sake of clicky satisfaction.

## Table of Contents
- [Arcade Button Box](#arcade-button-box)
  - [Table of Contents](#table-of-contents)
  - [General Info](#general-info)
  - [Technologies](#technologies)
  - [Setup](#setup)
  - [Usage](#usage)
  - [Notes](#notes)

## General Info
Our son (1 year old) loves to click and press tactile things, so this box was made to house an arcade button and simply increment a counter every time it is pressed. The total count is stored in EEPROM for data persistence and is displayed on a small OLED panel using an attiny85.

Theo presses button, counter goes up and inverts colors, everyone is happy.

## Technologies
- Fusion 360
- Arduino

## Setup
Print the box and wire the attiny85 to an 18650 for power and to a 32x128 OLED for the output, reference the Arduino code for pin definitions. 

This is a very simple bit of code so feel free to modify as needed or desired.

## Usage
Power on the device and start clicking!

## Notes
Occasionally the count is not stored reliably, I suspect this is due to my relative inexperience with EEPROM.