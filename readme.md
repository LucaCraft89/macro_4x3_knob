# macro_4x3_knob

![macro_4x3_knob](imgur.com image replace me!)
Image Coming soon

* Keyboard Creators: 
- [Luca Dall'Acqua](https://github.com/lucacraft89) PCB and FW
- [Simone Folino](https://github.com/Simone02472) 3D Modeling
* Hardware Supported: Arduino Pro Micro, Custom PCB
* Hardware Availability: AliExpress or any mayor online store

Make example for this keyboard (after setting up your build environment):
```bash
    make macro_4x3_knob:default
```
Flashing example for this keyboard:
```bash
    make macro_4x3_knob:default:flash
```
See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## 3D models 
    | :---        |    :----:   | 
    | TOP      | [V1.0](https://github.com/LucaCraft89/macro_4x3_knob/3D/V1/top1.0.STL)      | 
    | BOTTOM   | [V1.0](https://github.com/LucaCraft89/macro_4x3_knob/3D/V1/bottom1.0.STL)      | 

## Gerber files

[V1](https://github.com/LucaCraft89/macro_4x3_knob/PCB/betterDisplay/production/betterDisplay.zip)
- NOTE: PCB has space for oled display that was never implemented, ignore it

## VIAL
VIAL is supported just flash the layout
```bash
    make macro_4x3_knob:vial:flash
```

## Bootloader
Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
