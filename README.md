# 💥OpenPCB: Manufacturing Double Layer PCBs Using Commodity Laser Engraver💥
This guide shows you how to manufacture a double layer PCB with vias and through holes using a relatively low cost (<$2k) commodity fiber laser engraver (ComMarker B4 20W). We provide custom enclosure design files to improve the safety of the engraver as well as 3D-printable clamp rigs to enable repeatable lasing operations on both sides of the PCB with minimal tuning.

## Bill of Materials:
### Equipment Needed
| Name | Description | Amount | Vendor |
| :---: | :---: | :---: | :---: |
| Arduino Teensy 4.0 | Microcontroller to run the system, read sensor value, and drive display screen | 1 | [Sparkfun](https://www.sparkfun.com/products/15583) |
| ST7789 1.3" LCD Display Screen | Displays graphics | 1 | [Makerfabs](https://www.makerfabs.com/1.3-inch-colorful-tft-module-st7789.html) |
| 3.7v LiPo Battery | Powers the system when not connected via USB | 1 | [Amazon](https://www.amazon.com/gp/product/B07C9RQQMX/ref=ppx_yo_dt_b_asin_title_o01_s00?ie=UTF8&psc=1) |
| TP4056 Lithium Battery Charging Board | Ensures battery is charging/discharging at proper conditions | 1 | [Amazon](https://www.amazon.com/gp/product/B00LTQU2RK/ref=ppx_yo_dt_b_asin_title_o01_s00?ie=UTF8&psc=1) |
| GUVA-S12SD | Breakout board for an analog UV sensor | 1 | [Adafruit](https://www.adafruit.com/product/1918) |
| S7V8F3 | Provides regulated 3.3v from battery voltage to power the system | 1 | [Pololu](https://www.pololu.com/product/2122) |
| Rocker Switch | Turns overall device on or off | 1 | [DigiKey](https://www.digikey.com/en/products/detail/e-switch/RA812C1121/3778076?utm_adgroup=Rocker%20Switches&utm_source=google&utm_medium=cpc&utm_campaign=Shopping_Product_Switches_NEW&utm_term=&utm_content=Rocker%20Switches) |



