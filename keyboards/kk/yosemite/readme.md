# Yosemite

![Yosemite](https://i.imgur.com/5xmcZ3b.jpeg)

Yosemite is a hot-swappable 75% keyboard with rotary encoder designed and manufactured in the USA.

* Keyboard Maintainer: [Kory Hicks](https://github.com/apricity-spam)
* Hardware Supported: Yosemite PCB, STM32F072CB
* Hardware Availability: Coming soon!

Make example for this keyboard (after setting up your build environment):

    make kk/yosemite:default

Flashing example for this keyboard:

    make kk/yosemite:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

* No pre-flashed firmware, option 1: Bridge `BOOT` labeled pads below spacebar while plugging the board in
* No pre-flashed firmware, option 2: Bridge `BOOT` labeled pads below spacebar, then quickly short `RST` labeled pads
* Pre-flashed firmware: Use Bootmagic - keep the `ESC` (top left most) key pressed while plugging the board in