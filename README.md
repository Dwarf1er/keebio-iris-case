<div align="center">
  <img alt="Keebio Iris Case Logo" src="/assets/keebio-iris-case-logo.png" />
</div>

# Description

This repository serves as a compilation of instructions for the Keebio Iris Phoenix Edition (PE) keyboard, encompassing revisions 5 to 8. It is meant to gather all the information needed to build and configure your Keebio Iris keyboard all in one place. The original authors of all the files and documents used will be linked to in the [Acknowledgements](#Acknowledgements).

# Parts List

**An important note regarding the top plate:** since the top plate is responsible for holding the switches in place it is not advisable to 3D print it since the final piece could lack in rigidity and provide an unpleasant typing experience but the STL file will also be linked.

## Parts Bought from Keebio
1. Iris Rev. 8 Hotswap PCBs [1x kit]
2. 3mm Thick Top Plate Kit [1x kit] (Not needed if printing top plate)
3. Coiled USB C to USB C Cable [1x cable]
4. SKUF Rubber Feet [1x 12 pack]
5. Silicone Hotswap PCB Bumpers [1x 12 pack]
6. 9mm Standoffs + M2 6mm Stainless Steel Screws [1x 25 pack] **included with the top plate kit if bought from keebio**

## Parts Bought from Other Sources
1. Any cherry mx 5 pin style switches [56x switches]
2. Any cherry mx compatible keycaps [56x keycaps]
3. M3 x 16 mm screws [4x for the tenting legs]
4. M3 nuts [4x for the tenting legs]

## Printed Parts
1. [Bottom plate](keebio-iris-pe-bottom-plate-3mm.stl) [2x bottom plates]
2. [Middle layer](keebio-iris-pe-middle-layer-3mm.stl) [2x middle layers]
3. [Tenting leg](keebio-iris-pe-ergodox-tenting-leg.stl) [4x legs] **Optional**
4. [Tenting leg adapter](keebio-iris-pe-ergodox-tenting-leg-adapter.stl) [4x adapters] **Optional**
5. [Top plate]() [2x top plates] **Optional and not recommended**
6. [SKUF feet alignment guide](keebio-iris-pe-skuf-alignment-guide.stl) [1x skuf guide] **Optional to stick the SKUF rubber feet nicely under the keyboard**

# Printing Instructions

The printing instructions are based on a [Creality Ender3 Pro](https://www.creality.com/products/ender-3-pro-3d-printer) and the STL files were sliced in [Ultimaker Cura 5.7](https://ultimaker.com/software/ultimaker-cura/), modify accordingly for different printers and slicing software.

## Bottom Plate

Print the [bottom plate](keebio-iris-pe-bottom-plate-3mm.stl) **twice**. Print the bottom plate once in the original orientation (left side) and then print it a second time by using the mirror function of your slicing software to print it again (right side).

- Material: PLA
- Layer Height: 0.2mm
- Infill: 20%
- Supports: None

Notes: 20% infill was used to save material and time but 100% could be adviseable since this is the frame of the keyboard and strength is important.

## Middle Layer

Print the [middle layer](keebio-iris-pe-middle-layer-3mm.stl) **twice**. Print the middle layer once in the original orientation (left side) and then print it a second time by using the mirror function of your slicing software to print it again (right side).

- Material: PLA
- Layer Height: 0.2mm
- Infill: 20%
- Supports: 15% in zig zag pattern

Notes: Supports are required due to 90 degree overhangs. at 15% the cleanup wasn't hard at all but lower % of supports would be just fine too. As for the infill, again, 20% was used to save material and time but different patterns and % can achieve different effects if using transparent PLA.

## Tenting Kit

You can add all [4 legs](keebio-iris-pe-ergodox-tenting-leg.stl) and [4 adapters](keebio-iris-pe-ergodox-tenting-leg-adapter.stl) to be printed simultaneously. There is the possibilty

- Material: PLA
- Layer Height: 0.16mm
- Infill: 100%
- Supports: None

Notes: 100% infill was used to make sure that the legs and adapters were strong as they will be holding the keyboard up and taking impacts from typing.

## Top plate

If you do decide to print the [top plate](keebio-iris-pe-top-plate-3mm.stl), make sure to **use 100% infill** because otherwise the plate will lack rigidity and lead to an unpleasant typing experience.

- Material: PLA
- Layer Height: 0.2mm
- Infill: 100%
- Supports: None

Notes: 100% infill was used to make sure that the top plate will be as strong as possible.

# Assembly Instructions



# Configuration

To configure your keyboard you have 2 options:
- [VIA Configurator](https://www.caniusevia.com/) **recommended method**
- [QMK Configurator](https://config.qmk.fm)

The VIA Configurator is the recommended method because it's much easier to use and doesn't require you to reflash your keyboard to apply new keymaps. By default, the left thumb key is mapped to `enter` and the right thumb key is mapped to `space`, it's recommended to swap them around if you play video games for obvious reasons.

- [VIA Configurator documentation](https://docs.keeb.io/via)
- [QMK Configurator documentation](https://docs.keeb.io/remapping-keyboard#qmk-configurator)
- [Keyboard flashing documentation](https://docs.keeb.io/flashing-firmware)

# Acknowledgements

- [Original 3D files for the keyboard case](https://github.com/keebio/iris-case) - Courtesy of [Keebio](https://keeb.io)
- [Keyboard documentation](https://docs.keeb.io) - Courtesy of [Keebio](https://keeb.io)
- [Original 3D files for the tenting kit](https://www.thingiverse.com/thing:5259983) - Courtesy of [Dave Lehman](https://www.thingiverse.com/davelehman)
