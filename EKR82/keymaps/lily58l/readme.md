# EKR82L
<img src="https://keycapsss.com/media/image/21/2b/68/EKR82l-split-keyboard-rgb-led-1.jpg" width="400">

A modified EKR82 pcb, with underglow, per key rgb light and rotary encoder support.
- SK6812 Mini-E per key led's (58x) for easy soldering
- 6x SK6812 Mini led's per side for underglow
- Support for 1 rotary encoder on each side

Left encoder: volume up/down, next/previous track on RAISE layer  
Right encoder: cursor down/up, right/left on LOWER layer

* Keyboard Maintainer: BenRoe [GitHub](https://github.com/BenRoe) / [Twitter](https://twitter.com/keycapsss)
* Hardware Supported: Pro Micro, or Elite-C
* Hardware Availability: [Keycapsss.com](https://keycapsss.com)

Make example for this keyboard (after setting up your build environment):
 
    make EKR82/light:EKR82l

Flashing example for this keyboard:

    make EKR82/light:EKR82l:flash
    
See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).
