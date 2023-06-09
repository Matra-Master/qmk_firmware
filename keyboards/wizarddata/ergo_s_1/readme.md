# wizarddata/ergo_s_1

![wizarddata/ergo_s_1](https://raw.githubusercontent.com/wizarddata/Ergo-S-1/main/Ergo_S-1_Layout.png)

The Ergo S-1 is a fully wireless, split ergonomic keyboard that is compatible with cherry/gateron switches and cherry/oem/dcs keycaps.
The real project uses ZMK firmware and is awesome, but I have a couple promicros laying around and want to use them in this form factor.


* Keyboard Maintainer: [Franco Carabajal](https://github.com/Matra-Master)
* Hardware Supported: Arduino ProMicro atmega32u4

Make example for this keyboard (after setting up your build environment):

    make wizarddata/ergo_s_1:default

Flashing example for this keyboard:

    make wizarddata/ergo_s_1:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
