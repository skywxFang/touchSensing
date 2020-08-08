Get Started
=============

This document is intended to show you how to build a prototype in Arduino IDE using an ESP32 development board.

What You Need
-------------------

**Hardware:**

* An ESP32 development board, such as ESP32-DevKitC
* USB cable - Type A to micro Type B 
* Computer running macOS

**Software:**

* Arduino IDE
* `Arduino core for ESP32 <https://github.com/espressif/arduino-esp32/blob/master/docs/arduino-ide/mac.md>`__

Please follow the `Installation Instructions for macOS <https://github.com/espressif/arduino-esp32/blob/master/docs/arduino-ide/mac.md#installation-instructions-for-mac-os>`__ to include ESP32 library in your Arduino.


Let's Do It Step by Step
----------------------------

This part help you go through the whole development process step by step.

Step 1: Connect Your Device
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Now connect your ESP32 board to the computer and check under what serial part the board is visible.

To check the device name for the serial port of your ESP32 board, run the following command twice, 
first with the board unplugged, then with it plugged in. The port which appears the second time is the one you need::
    ls /dev/cu.*


