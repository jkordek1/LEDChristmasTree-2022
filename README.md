# LEDChristmasTree-2022

[![Version](https://img.shields.io/github/v/release/jkordek1/LEDChristmasTree-2022)](https://github.com/jkordek1/LEDChristmasTree-2022/releases/tag/Initial)
[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/jkordek1/LEDChristmasTree-2022)](https://github.com/jkordek1/LEDChristmasTree-2022/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/jkordek1/LEDChristmasTree-2022)](https://github.com/jkordek1/LEDChristmasTree-2022/pulls)

## About
LED Christmas tree powered by 2xAAA batteries. It uses self-flashing LEDs (fast and slow). Device draws ~5 mA of current so the batteries should last through holidays!

There are a lot of LED christmas trees but this one is just a perfect size, uses small amount of power and it gives a really nice effect.

## GIFs and images
<img src="https://github.com/jkordek1/LEDChristmasTree-2022/blob/main/Graphics/lightup.gif?raw=true" width="400"/>

<img src="https://raw.githubusercontent.com/jkordek1/LEDChristmasTree-2022/main/Graphics/back.jpg" width="400"/>

## YouTube
https://www.youtube.com/shorts/3aN1jUx8Kqs


## BOM
| #  | QTY | Component | Link
| ------------- | ------------- | ------------- | ------------- |
| 1  | 6 | 0807 RGB LED Fast  | [Aliexpress](https://www.aliexpress.com/item/32816748212.html?spm=a2g0o.order_detail.0.0.6c50f19cJa7Ddi) |
| 2  | 6 | 0807 RGB LED Slow  | [Aliexpress](https://www.aliexpress.com/item/32816748212.html?spm=a2g0o.order_detail.0.0.6c50f19cJa7Ddi) |
| 3  | 1 | 2xAAA Battery holder  | [Aliexpress](https://www.aliexpress.com/item/4001139676299.html?spm=a2g0o.order_list.0.0.21ef18022NrTgV) |
| 4  | 1 |  Slide switch  | [LCSC](https://lcsc.com/product-detail/Slide-Switches_Korean-Hroparts-Elec-K3-1296S-E2_C136659.html) |
| 5  | 12 | 2k 0603 resistor  | - |

## Project folder structure
    .
    ├── ...
    ├── Graphics                # Images and graphics
    ├── KiCadFiles              # Main folder
    │   ├── 3D models           # 3d models of components
    │   ├── BoardGame           # KiCAD project for main PCB
    │   ├── Dice                # KiCAD project for dice
    │   └── Touchpad            # KiCAD project for touchpad controls
    └── ...
