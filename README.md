# Sweep

## What is sweep?

Sweep is a version of the more fabulous [Ferris](https://github.com/pierrechevalier83/ferris) by [Pierre Chevalier](https://github.com/pierrechevalier83/) that uses a daughter board like a promicro, elite-c, bit-c, nice!nano etc. instead of using onboard components.

## What are the different types?

| Device | Bluetooth Support<sup>[1]</sup> | On/Off Switch | Reversible PCB | Choc V1 | Choc V2 | Choc Mini | MX & Alps | Choc Spacing<sup>[2]</sup> | Tenting<sup>[3]</sup> |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Sweep2.x            | ✔ | ✔ |   | ✔ |   |   |   | ✔ | ✔ |
| Sweep High        | ✔ | ✔ |   | ✔ | ✔ |   | ✔ |   | ✔ |
| Sweep Half Swept     | ✔ | ✔ | ✔ | ✔ |   |   |   | ✔ | ✔ |
| Sweep Compact     | ✔ |   | ✔ | ✔ |   |   |   | ✔ |   |
| Sweep Compact Low | ✔ |   | ✔ |   |   | ✔ |   | ✔ |   |
| Sweep Compact BLE | ✔ |   | ✔ | ✔ |   |   |   | ✔ |   |

*<sup>[1]</sup> It simply means that it supports the nice!nano. An on/off switch is recommended for bluetooth*  
*<sup>[2]</sup> Choc spaced boards have the switches in a tighter grid. This provides a better final look but is only compatible with some choc keycaps (e.g. MBK)*  
*<sup>[3]</sup> Supports splitkb's [tenting puck](https://splitkb.com/products/tenting-puck?_pos=1&_psq=tenting%20&_ss=e&_v=1.0)*

* Sweep2 - Recommended Choc v1 board with all the features.
* Sweep High - Same as the Sweep2 but trades choc spacing for compatibility with more switches and keycaps.
* Sweep Half Swept - Half of a Sweep2 with double pro-micro footprint (letting you avoid having one daughter-board flipped upside-down)
* Sweep Compact - A reversible sweep with Choc v1 support.
  * ⚠ *Left* half of the Sweep the promicro's USB port must face *towards* the PCB, and on the *right* half the USB port must face *away* from the PCB (so that the promicro's components are visible)
* Sweep Compact Low - The only version that supports Choc minis.
* Sweep Compact BLE - Same as the compact but without the TRRS Jack footprint.
* Sweep34 [deprecated] - This was the OG Sweep, before there was a choc spaced Ferris. Use the Sweep Half Swept instead.

## Firmware

The firmware can be found with the Ferris firmware as part of QMK. 

Firmware for zmk and bluemicro_ble is called "Cradio".

## BOM

To build a Sweep you will need:

* 2x promicro compatible boards or 2 nice!nanos.
* 34 switches of a compatible type (refer to the compatibility table)
* 34 keycaps
* 2x reset switches (optional)
* Some little rubber feet/bumpers
* Optional (if supported) 2x power switches (MSK 12C02)

## How do I make this thing?

I, lazily, haven't made any documentation, but thankfully there is [this tutorial on youtube](https://www.youtube.com/watch?v=fBPu7AyDtkM) by Kyek.

## Who made this?

* Pierre Chevalier
* David Barr
* [Ibnu Daru Aji](https://github.com/ibnuda/)
* [Duccio](https://github.com/duckyb)

