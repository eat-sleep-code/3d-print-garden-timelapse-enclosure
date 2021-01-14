# 3D Printer: Garden Timelapse Enclosure
An enclosure for Raspberry Pi HQ camera, up to two Raspberry Pi Zero's and a 40mm fan

## Overview

This collection of files will allow you to print a 3D print an enclosure for a Timelapse Camera.  This enclosure case will hold a Raspberry Pi HQ Camera (or similar dimensioned camera from Arducam), one to two Raspberry Pi Zero WH boards, and optionally a Trinket M0 board.  

The case also supports mounting a **5v** 40mm fan.   Noctua fans are suggested due to their quiet operation and lengthy warranty.   They also included the 3-pin to 2-pin adapter which will allow you connect it directly to pins 4 and 6 of your Raspberry Pi's GPIO.

## Getting Started

You will need at least the following non-included parts:
- [Raspberry Pi Zero WH](https://www.adafruit.com/product/3708)
- [Arducam Noir Camera](https://smile.amazon.com/Arducam-Camera-Raspberry-Interchangeable-LS-2717CS/dp/B013JV4Z7K/) or [Raspberry Pi HQ camera)(https://www.canakit.com/raspberry-pi-hq-camera.html) and a comparable lens.
- [SD Card](https://smile.amazon.com/gp/product/B07FCMKK5X)
- [6mm CS-mount Lens](https://smile.amazon.com/gp/product/B088GWZPL1)
- [Ribbon Flex Extension Cables for Pi Zero](https://smile.amazon.com/Arducam-Raspberry-Camera-Ribbon-Extension/dp/B085RW9K13)
- [Noctua 40mm 5V Fan (3-pin)](https://smile.amazon.com/gp/product/B00NEMGCIA) (includes 3-pin to 2-pin adapter)
- *Screws, Nuts, Bolts*
  - (4x) M2.5 x 30mm (or M2.5 x 35mm) 
  - (8x) M2.5 nuts
  - (8x) M2.5 washers
  - (1x) M4 x 15mm screw
  - (2x) M4 x ? scews for mounting (choose a screw long enough for your mounting surface)
  - (2x) M4 Washers
  - (4x - 8x) M2.5 x 6mm 
  - (4x - 8x) M2.5 Nylon Washers
  - (1x) - Sheet of black felt

You will need the following additional tools:
- Screwdriver for M2.5 screws
- Screwdriver for M4 screws
- M2.5 micro tap set for cleaning up threads of holes.


## Printing Instructions

:warning: **IMPORTANT:** Please review each part in your slicing software before printing to ensure a logical face is touching the build plate!      

These print settings were used to print using a Creality CR-6 SE using Hatchbox Cool Gray 1.75mm PLA.   You may need to adjust these settings slightly for other printer and filament combinations.

- Print Resolution: 0.2
- Infill (unless otherwise noted below): 30%
- Supports (unless otherwise noted below): No
- Printing Temperature: 200C
- Build Plate Temperature: 60C
- Part-specific notes:
  - **Main Box.stl** For this piece you will need to print a "Touching Buildplate" support for overhanging angles exceeding 47°.  This is the only piece that needs to be printed with supports.
  
## Cutting Instructions.
The **Camera Lens Felt Seal.studio3** file can be used to cut a felt seal using a Silhouette Cameo cutting machine.   You may need to make multiple cut passes to cut through the felt.   This seal can also cut by hand with a steady hand.

