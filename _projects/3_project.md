---
layout: page
title: Nunchuk to iPad
description: Adapting a Nintendo Nunchuk into an alternative pointing device.
permalink: /projects/nunchuk-ipad/
importance: 3
---

**January–June 2026 · Hardware and software prototyping**

## Motivation

Touchscreen interaction is not suitable for everyone.
This project explored using a Nintendo Nunchuk as an alternative
way to control an iPad pointer and issue clicks.

## My contribution

Using the open-source ANAVI Handle platform and CircuitPython
libraries, I adapted the firmware to translate joystick movement
into pointer movement and button presses into mouse clicks.

The implementation reads the controller over I²C and sends
mouse commands through USB HID. A dead zone reduces unintended
movement near the joystick's resting position.

## What I learned

- Connecting physical controls to a digital interface.
- Adapting existing embedded software.
- Working with I²C and USB HID.
- Investigating pointer and button behaviour on an iPad.

## Technologies

CircuitPython · ANAVI Handle · RP2040 · I²C · USB HID

## Credits

Built using ANAVI Handle and Adafruit CircuitPython libraries.
My contribution focuses on firmware adaptation and experimentation
for iPad interaction.