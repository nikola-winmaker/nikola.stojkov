+++
title = "HMI For motor control system"
type = "post"
date = 2023-05-12
draft = false
+++

As a tech enthusiast, I have always been interested in creating new and innovative systems that can make our lives easier and more efficient. Recently, I worked on an HMI (Human Machine Interface) system that uses the ESP32S3 WROOM 1U as the main controller and an RGB LCD display to control a variable frequency drive (VFD - 3 Phase Adjustable Speed Controller Inverter). 

To begin with, let me explain what an HMI system is. An HMI system is a graphical interface that allows users to interact with a machine or device. It typically consists of a display and a controller that can be used to control various functions by user interactions. An HMI system is used in a wide range of applications, from industrial automation to consumer electronics.

The HMI system that I created uses an ESP32S3 WROOM 1U microcontroller as the main controller. The ESP32S3 is a powerful microcontroller that is based on the RISC architecture. It has a dual-core processor, built-in Wi-Fi and Bluetooth, and a wide range of GPIO pins that can be used to interface with other components, as in my case all GPIOs are utilized.

The ESP32S3 WROOM 1U is connected to an RGB LCD display via RGB interface, and stack used for graphics is based on LVGL library. The HMI has buttons that are located on the sides of the LCD display which are used to control the GUI (Graphical User Interface) of the system and to control the VFD.

The system is powered using a 12V power supply which is used to create 3.3V for ESP32 and 25,8V for LCD screen.


![HMI Front](/post/images/frontHMI.jpg)
![HMI Back](/post/images/backHMI.jpg)

Video of the device with LVGL stress-demo:

{{< youtube PWmhP1ujk8A>}}

