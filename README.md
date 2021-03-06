# 3D Printer: Garden Timelapse Enclosure
An enclosure for Raspberry Pi HQ camera, up to two Raspberry Pi Zero's and a 40mm fan. 

If you are looking for a *software* solution to capture continuous timelapses and automatically upload them to YouTube, please see the [Camera.Timelapse](https://github.com/eat-sleep-code/camera.timelapse?utm_source=github.com&utm_medium=referral&utm_campaign=garden-timelapse-enclosure) repository.   For a view of this in practice, see our [**Garden Timelapse** YouTube channel](https://www.youtube.com/channel/UCXcfq71HTgGrijyWVqovT3g?utm_source=github.com&utm_medium=referral&utm_campaign=garden-timelapse-enclosure).

## Overview

This collection of files will allow you to print a 3D print an enclosure for a Timelapse Camera.  This enclosure case will hold a Raspberry Pi HQ Camera (or similar dimensioned camera from Arducam), one to two Raspberry Pi Zero WH boards, and optionally a Trinket M0 board.  

![Front](/images/Front.jpg)

The case also supports mounting a **5v** 40mm fan.   Noctua fans are suggested due to their quiet operation and lengthy warranty.   They also included the 3-pin to 2-pin adapter which will allow you connect it directly to pins 4 and 6 of your Raspberry Pi's GPIO.

## Getting Started

You will need at least the following non-included parts:
- [Raspberry Pi Zero WH](https://www.adafruit.com/product/3708)
- Camera Module:
   - 24-hour capture:   [Arducam Noir Camera](https://smile.amazon.com/Arducam-Camera-Raspberry-Interchangeable-LS-2717CS/dp/B013JV4Z7K/) and [IR Light Source](https://smile.amazon.com/gp/product/B075F7NV56)
   - Daylight capture: [Raspberry Pi HQ camera](https://www.canakit.com/raspberry-pi-hq-camera.html) and [6mm CS-mount Lens](https://smile.amazon.com/gp/product/B088GWZPL1)
- [SD Card](https://smile.amazon.com/gp/product/B07FCMKK5X)
- [Ribbon Flex Extension Cables for Pi Zero](https://smile.amazon.com/Arducam-Raspberry-Camera-Ribbon-Extension/dp/B085RW9K13)
- [Noctua 40mm 5V Fan (3-pin)](https://smile.amazon.com/gp/product/B00NEMGCIA) (includes 3-pin to 2-pin adapter)
- quality Micro USB power cable in an appropriate length  
- *Screws, Nuts, Bolts*
  - (4x) M2.5 x 30mm (or M2.5 x 35mm) 
  - (8x) M2.5 nuts
  - (8x) M2.5 washers
  - (1x) M4 x 15mm screw
  - (2x) M4 Washers
  - (4x - 8x) M2.5 x 6mm 
  - (4x - 8x) M2.5 Nylon Washers
  - (1x) M2 x 4mm screw
  - (1x) - Sheet of black felt
  - (2x) M4 x ? scews for mounting (choose a screw long enough for your mounting surface)

You will need the following additional tools:
- Screwdriver for M2 and M2.5 screws
- Screwdriver for M4 screws
- M2 and M2.5 micro tap set for cleaning up threads of holes.


## Printing Instructions

:warning: **IMPORTANT:** Please review each part in your slicing software before printing to ensure a logical face is touching the build plate!      

These print settings were used to print using a Creality CR-6 SE using Hatchbox Cool Gray 1.75mm PLA.   You may need to adjust these settings slightly for other printer and filament combinations.

- Print Resolution: 0.2
- Infill (unless otherwise noted below): 30%
- Supports (unless otherwise noted below): No
- Printing Temperature: 200C
- Build Plate Temperature: 60C
- Part-specific notes:
  - **Main Box.stl:** For this piece you will need to print a "Touching Buildplate" support for overhanging angles exceeding 47°.  This is the only piece that needs to be printed with supports.
  
## Cutting Instructions
**Camera Lens Felt Seal.studio3:** This file can be used to cut a felt seal using a Silhouette Cameo cutting machine.   You may need to make multiple cut passes to cut through the felt.   This seal can also cut by hand with a steady hand.

![Inside](/images/Inside.jpg)

![Left Side](/images/Left%20Side.jpg)
