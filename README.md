<div align="center">
  <img alt="Keebio Iris Case Logo" src="" />
</div>

# Description

This repository serves as a compilation of instructions for the Keebio Iris Phoenix Edition (PE) keyboard, encompassing revisions 5 to 8. It is meant to gather all the information needed to build and configure your Keebio Iris keyboard all in one place. The original authors of all the files and documents used will be linked to in the [Acknowledgements](#-Acknowledgements).

# Parts List

**An important note regarding the top plate:** since the top plate is responsible for holding the switches in place it is not advisable to 3D print it since the final piece could lack in rigidity and provide an unpleasant typing experience but the STL file will also be linked.

## Parts Bought from Keebio
1. Iris Rev. 8 Hotswap PCBs: [1x kit]
2. 3mm Thick Top Plate Kit: [1x kit] (Not needed if printing top plate)
3. Coiled USB C to USB C Cable: [1x cable]
4. SKUF Rubber Feet: [1x 12 pack]
5. Silicone Hotswap PCB Bumpers: [1x 12 pack]
6. 9mm Standoffs + M2 6mm Stainless Steel Screws: [1x 25 pack] **included with the top plate kit if you buy it**

## Parts Bought from Other Sources
1. Any cherry mx 5 pin style switches [56x switches]
2. Any cherry mx compatible keycaps [56x keycaps]

## Printed Parts
1. [Bottom plate](keebio-iris-pe-bottom-plate-3mm.stl) [2x plates]
2. [Middle layer](keebio-iris-pe-middle-layer-3mm.stl) [2x middle layers]
3. [Tenting leg](keebio-iris-pe-ergodox-tenting-leg.stl) [4x legs] **Optional**
4. [Tenting leg adapter](keebio-iris-pe-ergodox-tenting-leg-adapter.stl) [4x adapters] **Optional**
5. [Top plate]() [2x top plates] **Optional and not recommended**
6. [SKUF feet alignment guide](keebio-iris-pe-skuf-alignment-guide.stl) **Optional to stick the SKUF rubber feet nicely under the keyboard**

# Printing Instructions

The printing instructions are based on a [Creality Ender3 Pro](https://www.creality.com/products/ender-3-pro-3d-printer) and the STL files were sliced in [Ultimaker Cura 5.7](https://ultimaker.com/software/ultimaker-cura/), modify accordingly for different printers and slicing software.

## Bottom Plate

```stl
solid Mesh
  facet normal -0.998729 0.050394 0.000000
    outer loop
      vertex 179.637527 117.602249 3.000000
      vertex 179.637527 117.602249 0.000000
      vertex 179.632111 117.494896 0.000000
    endloop
  endfacet
  facet normal -0.998729 0.050394 0.000000
    outer loop
      vertex 179.632111 117.494896 3.000000
      vertex 179.637527 117.602249 3.000000
      vertex 179.632111 117.494896 0.000000
    endloop
  endfacet
  facet normal -0.988548 0.150905 0.000000
    outer loop
      vertex 179.616196 117.390640 0.000000
      vertex 179.632111 117.494896 3.000000
      vertex 179.632111 117.494896 0.000000
    endloop
  endfacet
  facet normal -0.988548 0.150905 0.000000
    outer loop
      vertex 179.616196 117.390640 3.000000
      vertex 179.632111 117.494896 3.000000
      vertex 179.616196 117.390640 0.000000
    endloop
  endfacet
  facet normal -0.968519 0.248941 0.000000
    outer loop
      vertex 179.590332 117.290016 0.000000
      vertex 179.616196 117.390640 3.000000
      vertex 179.616196 117.390640 0.000000
    endloop
  endfacet
  facet normal -0.968519 0.248941 0.000000
    outer loop
      vertex 179.590332 117.290016 3.000000
      vertex 179.616196 117.390640 3.000000
      vertex 179.590332 117.290016 0.000000
    endloop
  endfacet
  facet normal -0.939080 0.343698 0.000000
    outer loop
      vertex 179.555023 117.193542 0.000000
      vertex 179.590332 117.290016 3.000000
      vertex 179.590332 117.290016 0.000000
    endloop
  endfacet
  facet normal -0.939080 0.343698 0.000000
    outer loop
      vertex 179.555023 117.193542 3.000000
      vertex 179.590332 117.290016 3.000000
      vertex 179.555023 117.193542 0.000000
    endloop
  endfacet
  facet normal -0.900891 0.434045 0.000000
    outer loop
      vertex 179.510803 117.101761 0.000000
      vertex 179.555023 117.193542 3.000000
      vertex 179.555023 117.193542 0.000000
    endloop
  endfacet
  facet normal -0.900891 0.434045 0.000000
    outer loop
      vertex 179.510803 117.101761 3.000000
      vertex 179.555023 117.193542 3.000000
      vertex 179.510803 117.101761 0.000000
    endloop
  endfacet
  facet normal -0.854629 0.519240 0.000000
    outer loop
      vertex 179.458206 117.015190 0.000000
      vertex 179.510803 117.101761 3.000000
      vertex 179.510803 117.101761 0.000000
    endloop
  endfacet
  facet normal -0.854629 0.519240 0.000000
    outer loop
      vertex 179.458206 117.015190 3.000000
      vertex 179.510803 117.101761 3.000000
      vertex 179.458206 117.015190 0.000000
    endloop
  endfacet
  facet normal -0.800879 0.598826 0.000000
    outer loop
      vertex 179.397766 116.934357 0.000000
      vertex 179.458206 117.015190 3.000000
      vertex 179.458206 117.015190 0.000000
    endloop
  endfacet
  facet normal -0.800879 0.598826 0.000000
    outer loop
      vertex 179.397766 116.934357 3.000000
      vertex 179.458206 117.015190 3.000000
      vertex 179.397766 116.934357 0.000000
    endloop
  endfacet
  facet normal -0.740070 0.672530 0.000000
    outer loop
      vertex 179.330002 116.859787 0.000000
      vertex 179.397766 116.934357 3.000000
      vertex 179.397766 116.934357 0.000000
    endloop
  endfacet
  facet normal -0.740070 0.672530 0.000000
    outer loop
      vertex 179.330002 116.859787 3.000000
      vertex 179.397766 116.934357 3.000000
      vertex 179.330002 116.859787 0.000000
    endloop
  endfacet
  facet normal -0.672530 0.740070 0.000000
    outer loop
      vertex 179.255432 116.792023 0.000000
      vertex 179.330002 116.859787 3.000000
      vertex 179.330002 116.859787 0.000000
    endloop
  endfacet
  facet normal -0.672530 0.740070 0.000000
    outer loop
      vertex 179.255432 116.792023 3.000000
      vertex 179.330002 116.859787 3.000000
      vertex 179.255432 116.792023 0.000000
    endloop
  endfacet
  facet normal -0.598911 0.800816 0.000000
    outer loop
      vertex 179.174606 116.731575 0.000000
      vertex 179.255432 116.792023 3.000000
      vertex 179.255432 116.792023 0.000000
    endloop
  endfacet
  facet normal -0.598911 0.800816 0.000000
    outer loop
      vertex 179.174606 116.731575 3.000000
      vertex 179.255432 116.792023 3.000000
      vertex 179.174606 116.731575 0.000000
    endloop
  endfacet
  facet normal -0.519206 0.854649 0.000000
    outer loop
      vertex 179.088028 116.678978 0.000000
      vertex 179.174606 116.731575 3.000000
      vertex 179.174606 116.731575 0.000000
    endloop
  endfacet
  facet normal -0.519206 0.854649 0.000000
    outer loop
      vertex 179.088028 116.678978 3.000000
      vertex 179.174606 116.731575 3.000000
      vertex 179.088028 116.678978 0.000000
    endloop
  endfacet
  facet normal -0.433984 0.900920 0.000000
    outer loop
      vertex 178.996246 116.634766 0.000000
      vertex 179.088028 116.678978 3.000000
      vertex 179.088028 116.678978 0.000000
    endloop
  endfacet
  facet normal -0.433984 0.900920 0.000000
    outer loop
      vertex 178.996246 116.634766 3.000000
      vertex 179.088028 116.678978 3.000000
      vertex 178.996246 116.634766 0.000000
    endloop
  endfacet
  facet normal -0.343674 0.939089 0.000000
    outer loop
      vertex 178.899765 116.599457 0.000000
      vertex 178.996246 116.634766 3.000000
      vertex 178.996246 116.634766 0.000000
    endloop
  endfacet
  facet normal -0.343674 0.939089 0.000000
    outer loop
      vertex 178.899765 116.599457 3.000000
      vertex 178.996246 116.634766 3.000000
      vertex 178.899765 116.599457 0.000000
    endloop
  endfacet
  facet normal -0.249027 0.968496 0.000000
    outer loop
      vertex 178.799149 116.573586 0.000000
      vertex 178.899765 116.599457 3.000000
      vertex 178.899765 116.599457 0.000000
    endloop
  endfacet
  facet normal -0.249027 0.968496 0.000000
    outer loop
      vertex 178.799149 116.573586 3.000000
      vertex 178.899765 116.599457 3.000000
      vertex 178.799149 116.573586 0.000000
    endloop
  endfacet
  facet normal -0.150894 0.988550 0.000000
    outer loop
      vertex 178.694885 116.557671 0.000000
      vertex 178.799149 116.573586 3.000000
      vertex 178.799149 116.573586 0.000000
    endloop
  endfacet
  facet normal -0.150894 0.988550 0.000000
    outer loop
      vertex 178.694885 116.557671 3.000000
      vertex 178.799149 116.573586 3.000000
      vertex 178.694885 116.557671 0.000000
    endloop
  endfacet
  facet normal -0.050398 0.998729 0.000000
    outer loop
      vertex 178.587540 116.552254 0.000000
      vertex 178.694885 116.557671 3.000000
      vertex 178.694885 116.557671 0.000000
    endloop
  endfacet
  facet normal -0.050398 0.998729 0.000000
    outer loop
      vertex 178.587540 116.552254 3.000000
      vertex 178.694885 116.557671 3.000000
      vertex 178.587540 116.552254 0.000000
    endloop
  endfacet
  facet normal 0.050391 0.998730 0.000000
    outer loop
      vertex 178.480179 116.557671 0.000000
      vertex 178.587540 116.552254 3.000000
      vertex 178.587540 116.552254 0.000000
    endloop
  endfacet
  facet normal 0.050391 0.998730 0.000000
    outer loop
      vertex 178.480179 116.557671 3.000000
      vertex 178.587540 116.552254 3.000000
      vertex 178.480179 116.557671 0.000000
    endloop
  endfacet
  facet normal 0.150894 0.988550 0.000000
    outer loop
      vertex 178.375916 116.573586 0.000000
      vertex 178.480179 116.557671 3.000000
      vertex 178.480179 116.557671 0.000000
    endloop
  endfacet
  facet normal 0.150894 0.988550 0.000000
    outer loop
      vertex 178.375916 116.573586 3.000000
      vertex 178.480179 116.557671 3.000000
      vertex 178.375916 116.573586 0.000000
    endloop
  endfacet
  facet normal 0.249027 0.968496 0.000000
    outer loop
      vertex 178.275299 116.599457 0.000000
      vertex 178.375916 116.573586 3.000000
      vertex 178.375916 116.573586 0.000000
    endloop
  endfacet
  facet normal 0.249027 0.968496 0.000000
    outer loop
      vertex 178.275299 116.599457 3.000000
      vertex 178.375916 116.573586 3.000000
      vertex 178.275299 116.599457 0.000000
    endloop
  endfacet
  facet normal 0.343722 0.939071 0.000000
    outer loop
      vertex 178.178833 116.634766 0.000000
      vertex 178.275299 116.599457 3.000000
      vertex 178.275299 116.599457 0.000000
    endloop
  endfacet
  facet normal 0.343722 0.939071 0.000000
    outer loop
      vertex 178.178833 116.634766 3.000000
      vertex 178.275299 116.599457 3.000000
      vertex 178.178833 116.634766 0.000000
    endloop
  endfacet
  facet normal 0.433926 0.900949 0.000000
    outer loop
      vertex 178.087036 116.678978 0.000000
      vertex 178.178833 116.634766 3.000000
      vertex 178.178833 116.634766 0.000000
    endloop
  endfacet
  facet normal 0.433926 0.900949 0.000000
    outer loop
      vertex 178.087036 116.678978 3.000000
      vertex 178.178833 116.634766 3.000000
      vertex 178.087036 116.678978 0.000000
    endloop
  endfacet
  facet normal 0.519273 0.854608 0.000000
    outer loop
      vertex 178.000473 116.731575 0.000000
      vertex 178.087036 116.678978 3.000000
      vertex 178.087036 116.678978 0.000000
    endloop
  endfacet
  facet normal 0.519273 0.854608 0.000000
    outer loop
      vertex 178.000473 116.731575 3.000000
      vertex 178.087036 116.678978 3.000000
      vertex 178.000473 116.731575 0.000000
    endloop
  endfacet
  facet normal 0.598838 0.800870 0.000000
    outer loop
      vertex 177.919632 116.792023 0.000000
      vertex 178.000473 116.731575 3.000000
      vertex 178.000473 116.731575 0.000000
    endloop
  endfacet
  facet normal 0.598838 0.800870 0.000000
    outer loop
      vertex 177.919632 116.792023 3.000000
      vertex 178.000473 116.731575 3.000000
      vertex 177.919632 116.792023 0.000000
    endloop
  endfacet
  facet normal 0.672605 0.740002 0.000000
    outer loop
      vertex 177.845078 116.859787 0.000000
      vertex 177.919632 116.792023 3.000000
      vertex 177.919632 116.792023 0.000000
    endloop
  endfacet
  facet normal 0.672605 0.740002 0.000000
    outer loop
      vertex 177.845078 116.859787 3.000000
      vertex 177.919632 116.792023 3.000000
      vertex 177.845078 116.859787 0.000000
    endloop
  endfacet
  facet normal 0.739995 0.672612 0.000000
    outer loop
      vertex 177.777298 116.934357 0.000000
      vertex 177.845078 116.859787 3.000000
      vertex 177.845078 116.859787 0.000000
    endloop
  endfacet
  facet normal 0.739995 0.672612 0.000000
    outer loop
      vertex 177.777298 116.934357 3.000000
      vertex 177.845078 116.859787 3.000000
      vertex 177.777298 116.934357 0.000000
    endloop
  endfacet
  facet normal 0.800879 0.598826 0.000000
    outer loop
      vertex 177.716858 117.015190 0.000000
      vertex 177.777298 116.934357 3.000000
      vertex 177.777298 116.934357 0.000000
    endloop
  endfacet
  facet normal 0.800879 0.598826 0.000000
    outer loop
      vertex 177.716858 117.015190 3.000000
      vertex 177.777298 116.934357 3.000000
      vertex 177.716858 117.015190 0.000000
    endloop
  endfacet
  facet normal 0.854629 0.519240 0.000000
    outer loop
      vertex 177.664261 117.101761 0.000000
      vertex 177.716858 117.015190 3.000000
      vertex 177.716858 117.015190 0.000000
    endloop
  endfacet
  facet normal 0.854629 0.519240 0.000000
    outer loop
      vertex 177.664261 117.101761 3.000000
      vertex 177.716858 117.015190 3.000000
      vertex 177.664261 117.101761 0.000000
    endloop
  endfacet
  facet normal 0.900950 0.433924 0.000000
    outer loop
      vertex 177.620056 117.193542 0.000000
      vertex 177.664261 117.101761 3.000000
      vertex 177.664261 117.101761 0.000000
    endloop
  endfacet
  facet normal 0.900950 0.433924 0.000000
    outer loop
      vertex 177.620056 117.193542 3.000000
      vertex 177.664261 117.101761 3.000000
      vertex 177.620056 117.193542 0.000000
    endloop
  endfacet
  facet normal 0.939080 0.343698 0.000000
    outer loop
      vertex 177.584747 117.290016 0.000000
      vertex 177.620056 117.193542 3.000000
      vertex 177.620056 117.193542 0.000000
    endloop
  endfacet
  facet normal 0.939080 0.343698 0.000000
    outer loop
      vertex 177.584747 117.290016 3.000000
      vertex 177.620056 117.193542 3.000000
      vertex 177.584747 117.290016 0.000000
    endloop
  endfacet
  facet normal 0.968483 0.249078 0.000000
    outer loop
      vertex 177.558868 117.390640 0.000000
      vertex 177.584747 117.290016 3.000000
      vertex 177.584747 117.290016 0.000000
    endloop
  endfacet
  facet normal 0.968483 0.249078 0.000000
    outer loop
      vertex 177.558868 117.390640 3.000000
      vertex 177.584747 117.290016 3.000000
      vertex 177.558868 117.390640 0.000000
    endloop
  endfacet
  facet normal 0.988548 0.150905 0.000000
    outer loop
      vertex 177.542953 117.494896 0.000000
      vertex 177.558868 117.390640 3.000000
      vertex 177.558868 117.390640 0.000000
    endloop
  endfacet
  facet normal 0.988548 0.150905 0.000000
    outer loop
      vertex 177.542953 117.494896 3.000000
      vertex 177.558868 117.390640 3.000000
      vertex 177.542953 117.494896 0.000000
    endloop
  endfacet
  facet normal 0.998729 0.050394 0.000000
    outer loop
      vertex 177.537537 117.602249 0.000000
      vertex 177.542953 117.494896 3.000000
      vertex 177.542953 117.494896 0.000000
    endloop
  endfacet
  facet normal 0.998729 0.050394 0.000000
    outer loop
      vertex 177.537537 117.602249 3.000000
      vertex 177.542953 117.494896 3.000000
      vertex 177.537537 117.602249 0.000000
    endloop
  endfacet
  facet normal 0.998730 -0.050391 0.000000
    outer loop
      vertex 177.542953 117.709610 0.000000
      vertex 177.537537 117.602249 3.000000
      vertex 177.537537 117.602249 0.000000
    endloop
  endfacet
  facet normal 0.998730 -0.050391 0.000000
    outer loop
      vertex 177.542953 117.709610 3.000000
      vertex 177.537537 117.602249 3.000000
      vertex 177.542953 117.709610 0.000000
    endloop
  endfacet
  facet normal 0.988548 -0.150905 0.000000
    outer loop
      vertex 177.558868 117.813866 0.000000
      vertex 177.542953 117.709610 3.000000
      vertex 177.542953 117.709610 0.000000
    endloop
  endfacet
  facet normal 0.988548 -0.150905 0.000000
    outer loop
      vertex 177.558868 117.813866 3.000000
      vertex 177.542953 117.709610 3.000000
      vertex 177.558868 117.813866 0.000000
    endloop
  endfacet
  facet normal 0.968483 -0.249078 0.000000
    outer loop
      vertex 177.584747 117.914490 0.000000
      vertex 177.558868 117.813866 3.000000
      vertex 177.558868 117.813866 0.000000
    endloop
  endfacet
  facet normal 0.968483 -0.249078 0.000000
    outer loop
      vertex 177.584747 117.914490 3.000000
      vertex 177.558868 117.813866 3.000000
      vertex 177.584747 117.914490 0.000000
    endloop
  endfacet
  facet normal 0.939071 -0.343722 0.000000
    outer loop
      vertex 177.620056 118.010956 0.000000
      vertex 177.584747 117.914490 3.000000
      vertex 177.584747 117.914490 0.000000
    endloop
  endfacet
  facet normal 0.939071 -0.343722 0.000000
    outer loop
      vertex 177.620056 118.010956 3.000000
      vertex 177.584747 117.914490 3.000000
      vertex 177.620056 118.010956 0.000000
    endloop
  endfacet
  facet normal 0.900964 -0.433894 0.000000
    outer loop
      vertex 177.664261 118.102745 0.000000
      vertex 177.620056 118.010956 3.000000
      vertex 177.620056 118.010956 0.000000
    endloop
  endfacet
  facet normal 0.900964 -0.433894 0.000000
    outer loop
      vertex 177.664261 118.102745 3.000000
      vertex 177.620056 118.010956 3.000000
      vertex 177.664261 118.102745 0.000000
    endloop
  endfacet
  facet normal 0.854629 -0.519240 0.000000
    outer loop
      vertex 177.716858 118.189316 0.000000
      vertex 177.664261 118.102745 3.000000
      vertex 177.664261 118.102745 0.000000
    endloop
  endfacet
  facet normal 0.854629 -0.519240 0.000000
    outer loop
      vertex 177.716858 118.189316 3.000000
      vertex 177.664261 118.102745 3.000000
      vertex 177.716858 118.189316 0.000000
    endloop
  endfacet
  facet normal 0.800879 -0.598826 0.000000
    outer loop
      vertex 177.777298 118.270149 0.000000
      vertex 177.716858 118.189316 3.000000
      vertex 177.716858 118.189316 0.000000
    endloop
  endfacet
  facet normal 0.800879 -0.598826 0.000000
    outer loop
      vertex 177.777298 118.270149 3.000000
      vertex 177.716858 118.189316 3.000000
      vertex 177.777298 118.270149 0.000000
    endloop
  endfacet
  facet normal 0.739961 -0.672650 0.000000
    outer loop
      vertex 177.845078 118.344711 0.000000
      vertex 177.777298 118.270149 3.000000
      vertex 177.777298 118.270149 0.000000
    endloop
  endfacet
  facet normal 0.739961 -0.672650 0.000000
    outer loop
      vertex 177.845078 118.344711 3.000000
      vertex 177.777298 118.270149 3.000000
      vertex 177.845078 118.344711 0.000000
    endloop
  endfacet
  facet normal 0.672646 -0.739964 0.000000
    outer loop
      vertex 177.919632 118.412483 0.000000
      vertex 177.845078 118.344711 3.000000
      vertex 177.845078 118.344711 0.000000
    endloop
  endfacet
  facet normal 0.672646 -0.739964 0.000000
    outer loop
      vertex 177.919632 118.412483 3.000000
      vertex 177.845078 118.344711 3.000000
      vertex 177.919632 118.412483 0.000000
    endloop
  endfacet
  facet normal 0.598838 -0.800870 0.000000
    outer loop
      vertex 178.000473 118.472931 0.000000
      vertex 177.919632 118.412483 3.000000
      vertex 177.919632 118.412483 0.000000
    endloop
  endfacet
  facet normal 0.598838 -0.800870 0.000000
    outer loop
      vertex 178.000473 118.472931 3.000000
      vertex 177.919632 118.412483 3.000000
      vertex 178.000473 118.472931 0.000000
    endloop
  endfacet
  facet normal 0.519218 -0.854642 0.000000
    outer loop
      vertex 178.087036 118.525520 0.000000
      vertex 178.000473 118.472931 3.000000
      vertex 178.000473 118.472931 0.000000
    endloop
  endfacet
  facet normal 0.519218 -0.854642 0.000000
    outer loop
      vertex 178.087036 118.525520 3.000000
      vertex 178.000473 118.472931 3.000000
      vertex 178.087036 118.525520 0.000000
    endloop
  endfacet
  facet normal 0.433987 -0.900919 0.000000
    outer loop
      vertex 178.178833 118.569740 0.000000
      vertex 178.087036 118.525520 3.000000
      vertex 178.087036 118.525520 0.000000
    endloop
  endfacet
  facet normal 0.433987 -0.900919 0.000000
    outer loop
      vertex 178.178833 118.569740 3.000000
      vertex 178.087036 118.525520 3.000000
      vertex 178.178833 118.569740 0.000000
    endloop
  endfacet
  facet normal 0.343722 -0.939071 0.000000
    outer loop
      vertex 178.275299 118.605049 0.000000
      vertex 178.178833 118.569740 3.000000
      vertex 178.178833 118.569740 0.000000
    endloop
  endfacet
  facet normal 0.343722 -0.939071 0.000000
    outer loop
      vertex 178.275299 118.605049 3.000000
      vertex 178.178833 118.569740 3.000000
      vertex 178.275299 118.605049 0.000000
    endloop
  endfacet
  facet normal 0.249027 -0.968496 0.000000
    outer loop
      vertex 178.375916 118.630920 0.000000
      vertex 178.275299 118.605049 3.000000
      vertex 178.275299 118.605049 0.000000
    endloop
  endfacet
  facet normal 0.249027 -0.968496 0.000000
    outer loop
      vertex 178.375916 118.630920 3.000000
      vertex 178.275299 118.605049 3.000000
      vertex 178.375916 118.630920 0.000000
    endloop
  endfacet
  facet normal 0.150823 -0.988561 0.000000
    outer loop
      vertex 178.480179 118.646828 0.000000
      vertex 178.375916 118.630920 3.000000
      vertex 178.375916 118.630920 0.000000
    endloop
  endfacet
  facet normal 0.150823 -0.988561 0.000000
    outer loop
      vertex 178.480179 118.646828 3.000000
      vertex 178.375916 118.630920 3.000000
      vertex 178.480179 118.646828 0.000000
    endloop
  endfacet
  facet normal 0.050461 -0.998726 0.000000
    outer loop
      vertex 178.587540 118.652252 0.000000
      vertex 178.480179 118.646828 3.000000
      vertex 178.480179 118.646828 0.000000
    endloop
  endfacet
  facet normal 0.050461 -0.998726 0.000000
    outer loop
      vertex 178.587540 118.652252 3.000000
      vertex 178.480179 118.646828 3.000000
      vertex 178.587540 118.652252 0.000000
    endloop
  endfacet
  facet normal -0.050469 -0.998726 0.000000
    outer loop
      vertex 178.694885 118.646828 0.000000
      vertex 178.587540 118.652252 3.000000
      vertex 178.587540 118.652252 0.000000
    endloop
  endfacet
  facet normal -0.050469 -0.998726 -0.000000
    outer loop
      vertex 178.694885 118.646828 3.000000
      vertex 178.587540 118.652252 3.000000
      vertex 178.694885 118.646828 0.000000
    endloop
  endfacet
  facet normal -0.150823 -0.988561 0.000000
    outer loop
      vertex 178.799149 118.630920 0.000000
      vertex 178.694885 118.646828 3.000000
      vertex 178.694885 118.646828 0.000000
    endloop
  endfacet
  facet normal -0.150823 -0.988561 -0.000000
    outer loop
      vertex 178.799149 118.630920 3.000000
      vertex 178.694885 118.646828 3.000000
      vertex 178.799149 118.630920 0.000000
    endloop
  endfacet
  facet normal -0.249027 -0.968496 0.000000
    outer loop
      vertex 178.899765 118.605049 0.000000
      vertex 178.799149 118.630920 3.000000
      vertex 178.799149 118.630920 0.000000
    endloop
  endfacet
  facet normal -0.249027 -0.968496 -0.000000
    outer loop
      vertex 178.899765 118.605049 3.000000
      vertex 178.799149 118.630920 3.000000
      vertex 178.899765 118.605049 0.000000
    endloop
  endfacet
  facet normal -0.343674 -0.939089 0.000000
    outer loop
      vertex 178.996246 118.569740 0.000000
      vertex 178.899765 118.605049 3.000000
      vertex 178.899765 118.605049 0.000000
    endloop
  endfacet
  facet normal -0.343674 -0.939089 -0.000000
    outer loop
      vertex 178.996246 118.569740 3.000000
      vertex 178.899765 118.605049 3.000000
      vertex 178.996246 118.569740 0.000000
    endloop
  endfacet
  facet normal -0.434045 -0.900891 0.000000
    outer loop
      vertex 179.088028 118.525520 0.000000
      vertex 178.996246 118.569740 3.000000
      vertex 178.996246 118.569740 0.000000
    endloop
  endfacet
  facet normal -0.434045 -0.900891 -0.000000
    outer loop
      vertex 179.088028 118.525520 3.000000
      vertex 178.996246 118.569740 3.000000
      vertex 179.088028 118.525520 0.000000
    endloop
  endfacet
  facet normal -0.519151 -0.854683 0.000000
    outer loop
      vertex 179.174606 118.472931 0.000000
      vertex 179.088028 118.525520 3.000000
      vertex 179.088028 118.525520 0.000000
    endloop
  endfacet
  facet normal -0.519151 -0.854683 -0.000000
    outer loop
      vertex 179.174606 118.472931 3.000000
      vertex 179.088028 118.525520 3.000000
      vertex 179.174606 118.472931 0.000000
    endloop
  endfacet
  facet normal -0.598911 -0.800816 0.000000
    outer loop
      vertex 179.255432 118.412483 0.000000
      vertex 179.174606 118.472931 3.000000
      vertex 179.174606 118.472931 0.000000
    endloop
  endfacet
  facet normal -0.598911 -0.800816 -0.000000
    outer loop
      vertex 179.255432 118.412483 3.000000
      vertex 179.174606 118.472931 3.000000
      vertex 179.255432 118.412483 0.000000
    endloop
  endfacet
  facet normal -0.672571 -0.740033 0.000000
    outer loop
      vertex 179.330002 118.344711 0.000000
      vertex 179.255432 118.412483 3.000000
      vertex 179.255432 118.412483 0.000000
    endloop
  endfacet
  facet normal -0.672571 -0.740033 -0.000000
    outer loop
      vertex 179.330002 118.344711 3.000000
      vertex 179.255432 118.412483 3.000000
      vertex 179.330002 118.344711 0.000000
    endloop
  endfacet
  facet normal -0.740036 -0.672567 0.000000
    outer loop
      vertex 179.397766 118.270149 0.000000
      vertex 179.330002 118.344711 3.000000
      vertex 179.330002 118.344711 0.000000
    endloop
  endfacet
  facet normal -0.740036 -0.672567 -0.000000
    outer loop
      vertex 179.397766 118.270149 3.000000
      vertex 179.330002 118.344711 3.000000
      vertex 179.397766 118.270149 0.000000
    endloop
  endfacet
  facet normal -0.800879 -0.598826 0.000000
    outer loop
      vertex 179.458206 118.189316 0.000000
      vertex 179.397766 118.270149 3.000000
      vertex 179.397766 118.270149 0.000000
    endloop
  endfacet
  facet normal -0.800879 -0.598826 -0.000000
    outer loop
      vertex 179.458206 118.189316 3.000000
      vertex 179.397766 118.270149 3.000000
      vertex 179.458206 118.189316 0.000000
    endloop
  endfacet
  facet normal -0.854629 -0.519240 0.000000
    outer loop
      vertex 179.510803 118.102745 0.000000
      vertex 179.458206 118.189316 3.000000
      vertex 179.458206 118.189316 0.000000
    endloop
  endfacet
  facet normal -0.854629 -0.519240 -0.000000
    outer loop
      vertex 179.510803 118.102745 3.000000
      vertex 179.458206 118.189316 3.000000
      vertex 179.510803 118.102745 0.000000
    endloop
  endfacet
  facet normal -0.900905 -0.434016 0.000000
    outer loop
      vertex 179.555023 118.010956 0.000000
      vertex 179.510803 118.102745 3.000000
      vertex 179.510803 118.102745 0.000000
    endloop
  endfacet
  facet normal -0.900905 -0.434016 -0.000000
    outer loop
      vertex 179.555023 118.010956 3.000000
      vertex 179.510803 118.102745 3.000000
      vertex 179.555023 118.010956 0.000000
    endloop
  endfacet
  facet normal -0.939071 -0.343722 0.000000
    outer loop
      vertex 179.590332 117.914490 0.000000
      vertex 179.555023 118.010956 3.000000
      vertex 179.555023 118.010956 0.000000
    endloop
  endfacet
  facet normal -0.939071 -0.343722 -0.000000
    outer loop
      vertex 179.590332 117.914490 3.000000
      vertex 179.555023 118.010956 3.000000
      vertex 179.590332 117.914490 0.000000
    endloop
  endfacet
  facet normal -0.968519 -0.248941 0.000000
    outer loop
      vertex 179.616196 117.813866 0.000000
      vertex 179.590332 117.914490 3.000000
      vertex 179.590332 117.914490 0.000000
    endloop
  endfacet
  facet normal -0.968519 -0.248941 -0.000000
    outer loop
      vertex 179.616196 117.813866 3.000000
      vertex 179.590332 117.914490 3.000000
      vertex 179.616196 117.813866 0.000000
    endloop
  endfacet
  facet normal -0.988548 -0.150905 0.000000
    outer loop
      vertex 179.632111 117.709610 0.000000
      vertex 179.616196 117.813866 3.000000
      vertex 179.616196 117.813866 0.000000
    endloop
  endfacet
  facet normal -0.988548 -0.150905 -0.000000
    outer loop
      vertex 179.632111 117.709610 3.000000
      vertex 179.616196 117.813866 3.000000
      vertex 179.632111 117.709610 0.000000
    endloop
  endfacet
  facet normal -0.998730 -0.050391 0.000000
    outer loop
      vertex 179.637527 117.602249 0.000000
      vertex 179.632111 117.709610 3.000000
      vertex 179.632111 117.709610 0.000000
    endloop
  endfacet
  facet normal -0.998730 -0.050391 -0.000000
    outer loop
      vertex 179.637527 117.602249 3.000000
      vertex 179.632111 117.709610 3.000000
      vertex 179.637527 117.602249 0.000000
    endloop
  endfacet
  facet normal -0.998726 0.050465 0.000000
    outer loop
      vertex 34.300442 110.333557 3.000000
      vertex 34.300442 110.333557 0.000000
      vertex 34.295017 110.226204 0.000000
    endloop
  endfacet
  facet normal -0.998726 0.050465 0.000000
    outer loop
      vertex 34.295017 110.226204 3.000000
      vertex 34.300442 110.333557 3.000000
      vertex 34.295017 110.226204 0.000000
    endloop
  endfacet
  facet normal -0.988554 0.150869 0.000000
    outer loop
      vertex 34.279106 110.121948 0.000000
      vertex 34.295017 110.226204 3.000000
      vertex 34.295017 110.226204 0.000000
    endloop
  endfacet
  facet normal -0.988554 0.150869 0.000000
    outer loop
      vertex 34.279106 110.121948 3.000000
      vertex 34.295017 110.226204 3.000000
      vertex 34.279106 110.121948 0.000000
    endloop
  endfacet
  facet normal -0.968506 0.248992 0.000000
    outer loop
      vertex 34.253235 110.021317 0.000000
      vertex 34.279106 110.121948 3.000000
      vertex 34.279106 110.121948 0.000000
    endloop
  endfacet
  facet normal -0.968506 0.248992 0.000000
    outer loop
      vertex 34.253235 110.021317 3.000000
      vertex 34.279106 110.121948 3.000000
      vertex 34.253235 110.021317 0.000000
    endloop
  endfacet
  facet normal -0.939071 0.343722 0.000000
    outer loop
      vertex 34.217926 109.924850 0.000000
      vertex 34.253235 110.021317 3.000000
      vertex 34.253235 110.021317 0.000000
    endloop
  endfacet
  facet normal -0.939071 0.343722 0.000000
    outer loop
      vertex 34.217926 109.924850 3.000000
      vertex 34.253235 110.021317 3.000000
      vertex 34.217926 109.924850 0.000000
    endloop
  endfacet
  facet normal -0.900906 0.434015 0.000000
    outer loop
      vertex 34.173710 109.833069 0.000000
      vertex 34.217926 109.924850 3.000000
      vertex 34.217926 109.924850 0.000000
    endloop
  endfacet
  facet normal -0.900906 0.434015 0.000000
    outer loop
      vertex 34.173710 109.833069 3.000000
      vertex 34.217926 109.924850 3.000000
      vertex 34.173710 109.833069 0.000000
    endloop
  endfacet
  facet normal -0.854666 0.519179 0.000000
    outer loop
      vertex 34.121117 109.746490 0.000000
      vertex 34.173710 109.833069 3.000000
      vertex 34.173710 109.833069 0.000000
    endloop
  endfacet
  facet normal -0.854666 0.519179 0.000000
    outer loop
      vertex 34.121117 109.746490 3.000000
      vertex 34.173710 109.833069 3.000000
      vertex 34.121117 109.746490 0.000000
    endloop
  endfacet
  facet normal -0.800816 0.598911 0.000000
    outer loop
      vertex 34.060669 109.665665 0.000000
      vertex 34.121117 109.746490 3.000000
      vertex 34.121117 109.746490 0.000000
    endloop
  endfacet
  facet normal -0.800816 0.598911 0.000000
    outer loop
      vertex 34.060669 109.665665 3.000000
      vertex 34.121117 109.746490 3.000000
      vertex 34.060669 109.665665 0.000000
    endloop
  endfacet
  facet normal -0.740051 0.672550 0.000000
    outer loop
      vertex 33.992901 109.591095 0.000000
      vertex 34.060669 109.665665 3.000000
      vertex 34.060669 109.665665 0.000000
    endloop
  endfacet
  facet normal -0.740051 0.672550 0.000000
    outer loop
      vertex 33.992901 109.591095 3.000000
      vertex 34.060669 109.665665 3.000000
      vertex 33.992901 109.591095 0.000000
    endloop
  endfacet
  facet normal -0.672567 0.740036 0.000000
    outer loop
      vertex 33.918339 109.523331 0.000000
      vertex 33.992901 109.591095 3.000000
      vertex 33.992901 109.591095 0.000000
    endloop
  endfacet
  facet normal -0.672567 0.740036 0.000000
    outer loop
      vertex 33.918339 109.523331 3.000000
      vertex 33.992901 109.591095 3.000000
      vertex 33.918339 109.523331 0.000000
    endloop
  endfacet
  facet normal -0.598875 0.800843 0.000000
    outer loop
      vertex 33.837505 109.462883 0.000000
      vertex 33.918339 109.523331 3.000000
      vertex 33.918339 109.523331 0.000000
    endloop
  endfacet
  facet normal -0.598875 0.800843 0.000000
    outer loop
      vertex 33.837505 109.462883 3.000000
      vertex 33.918339 109.523331 3.000000
      vertex 33.837505 109.462883 0.000000
    endloop
  endfacet
  facet normal -0.519223 0.854639 0.000000
    outer loop
      vertex 33.750931 109.410286 0.000000
      vertex 33.837505 109.462883 3.000000
      vertex 33.837505 109.462883 0.000000
    endloop
  endfacet
  facet normal -0.519223 0.854639 0.000000
    outer loop
      vertex 33.750931 109.410286 3.000000
      vertex 33.837505 109.462883 3.000000
      vertex 33.750931 109.410286 0.000000
    endloop
  endfacet
  facet normal -0.433970 0.900927 0.000000
    outer loop
      vertex 33.659145 109.366074 0.000000
      vertex 33.750931 109.410286 3.000000
      vertex 33.750931 109.410286 0.000000
    endloop
  endfacet
  facet normal -0.433970 0.900927 0.000000
    outer loop
      vertex 33.659145 109.366074 3.000000
      vertex 33.750931 109.410286 3.000000
      vertex 33.659145 109.366074 0.000000
    endloop
  endfacet
  facet normal -0.343710 0.939076 0.000000
    outer loop
      vertex 33.562675 109.330765 0.000000
      vertex 33.659145 109.366074 3.000000
      vertex 33.659145 109.366074 0.000000
    endloop
  endfacet
  facet normal -0.343710 0.939076 0.000000
    outer loop
      vertex 33.562675 109.330765 3.000000
      vertex 33.659145 109.366074 3.000000
      vertex 33.562675 109.330765 0.000000
    endloop
  endfacet
  facet normal -0.249010 0.968501 0.000000
    outer loop
      vertex 33.462051 109.304893 0.000000
      vertex 33.562675 109.330765 3.000000
      vertex 33.562675 109.330765 0.000000
    endloop
  endfacet
  facet normal -0.249010 0.968501 0.000000
    outer loop
      vertex 33.462051 109.304893 3.000000
      vertex 33.562675 109.330765 3.000000
      vertex 33.462051 109.304893 0.000000
    endloop
  endfacet
  facet normal -0.150905 0.988548 0.000000
    outer loop
      vertex 33.357796 109.288979 0.000000
      vertex 33.462051 109.304893 3.000000
      vertex 33.462051 109.304893 0.000000
    endloop
  endfacet
  facet normal -0.150905 0.988548 0.000000
    outer loop
      vertex 33.357796 109.288979 3.000000
      vertex 33.462051 109.304893 3.000000
      vertex 33.357796 109.288979 0.000000
    endloop
  endfacet
  facet normal -0.050392 0.998729 0.000000
    outer loop
      vertex 33.250439 109.283562 0.000000
      vertex 33.357796 109.288979 3.000000
      vertex 33.357796 109.288979 0.000000
    endloop
  endfacet
  facet normal -0.050392 0.998729 0.000000
    outer loop
      vertex 33.250439 109.283562 3.000000
      vertex 33.357796 109.288979 3.000000
      vertex 33.250439 109.283562 0.000000
    endloop
  endfacet
  facet normal 0.050392 0.998729 0.000000
    outer loop
      vertex 33.143082 109.288979 0.000000
      vertex 33.250439 109.283562 3.000000
      vertex 33.250439 109.283562 0.000000
    endloop
  endfacet
  facet normal 0.050392 0.998729 0.000000
    outer loop
      vertex 33.143082 109.288979 3.000000
      vertex 33.250439 109.283562 3.000000
      vertex 33.143082 109.288979 0.000000
    endloop
  endfacet
  facet normal 0.150905 0.988548 0.000000
    outer loop
      vertex 33.038826 109.304893 0.000000
      vertex 33.143082 109.288979 3.000000
      vertex 33.143082 109.288979 0.000000
    endloop
  endfacet
  facet normal 0.150905 0.988548 0.000000
    outer loop
      vertex 33.038826 109.304893 3.000000
      vertex 33.143082 109.288979 3.000000
      vertex 33.038826 109.304893 0.000000
    endloop
  endfacet
  facet normal 0.249010 0.968501 0.000000
    outer loop
      vertex 32.938202 109.330765 0.000000
      vertex 33.038826 109.304893 3.000000
      vertex 33.038826 109.304893 0.000000
    endloop
  endfacet
  facet normal 0.249010 0.968501 0.000000
    outer loop
      vertex 32.938202 109.330765 3.000000
      vertex 33.038826 109.304893 3.000000
      vertex 32.938202 109.330765 0.000000
    endloop
  endfacet
  facet normal 0.343710 0.939076 0.000000
    outer loop
      vertex 32.841732 109.366074 0.000000
      vertex 32.938202 109.330765 3.000000
      vertex 32.938202 109.330765 0.000000
    endloop
  endfacet
  facet normal 0.343710 0.939076 0.000000
    outer loop
      vertex 32.841732 109.366074 3.000000
      vertex 32.938202 109.330765 3.000000
      vertex 32.841732 109.366074 0.000000
    endloop
  endfacet
  facet normal 0.433970 0.900927 0.000000
    outer loop
      vertex 32.749947 109.410286 0.000000
      vertex 32.841732 109.366074 3.000000
      vertex 32.841732 109.366074 0.000000
    endloop
  endfacet
  facet normal 0.433970 0.900927 0.000000
    outer loop
      vertex 32.749947 109.410286 3.000000
      vertex 32.841732 109.366074 3.000000
      vertex 32.749947 109.410286 0.000000
    endloop
  endfacet
  facet normal 0.519240 0.854629 0.000000
    outer loop
      vertex 32.663376 109.462883 0.000000
      vertex 32.749947 109.410286 3.000000
      vertex 32.749947 109.410286 0.000000
    endloop
  endfacet
  facet normal 0.519240 0.854629 0.000000
    outer loop
      vertex 32.663376 109.462883 3.000000
      vertex 32.749947 109.410286 3.000000
      vertex 32.663376 109.462883 0.000000
    endloop
  endfacet
  facet normal 0.598875 0.800843 0.000000
    outer loop
      vertex 32.582542 109.523331 0.000000
      vertex 32.663376 109.462883 3.000000
      vertex 32.663376 109.462883 0.000000
    endloop
  endfacet
  facet normal 0.598875 0.800843 0.000000
    outer loop
      vertex 32.582542 109.523331 3.000000
      vertex 32.663376 109.462883 3.000000
      vertex 32.582542 109.523331 0.000000
    endloop
  endfacet
  facet normal 0.672548 0.740053 0.000000
    outer loop
      vertex 32.507977 109.591095 0.000000
      vertex 32.582542 109.523331 3.000000
      vertex 32.582542 109.523331 0.000000
    endloop
  endfacet
  facet normal 0.672548 0.740053 0.000000
    outer loop
      vertex 32.507977 109.591095 3.000000
      vertex 32.582542 109.523331 3.000000
      vertex 32.507977 109.591095 0.000000
    endloop
  endfacet
  facet normal 0.740051 0.672550 0.000000
    outer loop
      vertex 32.440208 109.665665 0.000000
      vertex 32.507977 109.591095 3.000000
      vertex 32.507977 109.591095 0.000000
    endloop
  endfacet
  facet normal 0.740051 0.672550 0.000000
    outer loop
      vertex 32.440208 109.665665 3.000000
      vertex 32.507977 109.591095 3.000000
      vertex 32.440208 109.665665 0.000000
    endloop
  endfacet
  facet normal 0.800834 0.598887 0.000000
    outer loop
      vertex 32.379765 109.746490 0.000000
      vertex 32.440208 109.665665 3.000000
      vertex 32.440208 109.665665 0.000000
    endloop
  endfacet
  facet normal 0.800834 0.598887 0.000000
    outer loop
      vertex 32.379765 109.746490 3.000000
      vertex 32.440208 109.665665 3.000000
      vertex 32.379765 109.746490 0.000000
    endloop
  endfacet
  facet normal 0.854649 0.519206 0.000000
    outer loop
      vertex 32.327168 109.833069 0.000000
      vertex 32.379765 109.746490 3.000000
      vertex 32.379765 109.746490 0.000000
    endloop
  endfacet
  facet normal 0.854649 0.519206 0.000000
    outer loop
      vertex 32.327168 109.833069 3.000000
      vertex 32.379765 109.746490 3.000000
      vertex 32.327168 109.833069 0.000000
    endloop
  endfacet
  facet normal 0.900920 0.433984 0.000000
    outer loop
      vertex 32.282955 109.924850 0.000000
      vertex 32.327168 109.833069 3.000000
      vertex 32.327168 109.833069 0.000000
    endloop
  endfacet
  facet normal 0.900920 0.433984 0.000000
    outer loop
      vertex 32.282955 109.924850 3.000000
      vertex 32.327168 109.833069 3.000000
      vertex 32.282955 109.924850 0.000000
    endloop
  endfacet
  facet normal 0.939071 0.343722 0.000000
    outer loop
      vertex 32.247646 110.021317 0.000000
      vertex 32.282955 109.924850 3.000000
      vertex 32.282955 109.924850 0.000000
    endloop
  endfacet
  facet normal 0.939071 0.343722 0.000000
    outer loop
      vertex 32.247646 110.021317 3.000000
      vertex 32.282955 109.924850 3.000000
      vertex 32.247646 110.021317 0.000000
    endloop
  endfacet
  facet normal 0.968497 0.249026 0.000000
    outer loop
      vertex 32.221771 110.121948 0.000000
      vertex 32.247646 110.021317 3.000000
      vertex 32.247646 110.021317 0.000000
    endloop
  endfacet
  facet normal 0.968497 0.249026 0.000000
    outer loop
      vertex 32.221771 110.121948 3.000000
      vertex 32.247646 110.021317 3.000000
      vertex 32.221771 110.121948 0.000000
    endloop
  endfacet
  facet normal 0.988554 0.150869 0.000000
    outer loop
      vertex 32.205860 110.226204 0.000000
      vertex 32.221771 110.121948 3.000000
      vertex 32.221771 110.121948 0.000000
    endloop
  endfacet
  facet normal 0.988554 0.150869 0.000000
    outer loop
      vertex 32.205860 110.226204 3.000000
      vertex 32.221771 110.121948 3.000000
      vertex 32.205860 110.226204 0.000000
    endloop
  endfacet
  facet normal 0.998728 0.050430 0.000000
    outer loop
      vertex 32.200439 110.333557 0.000000
      vertex 32.205860 110.226204 3.000000
      vertex 32.205860 110.226204 0.000000
    endloop
  endfacet
  facet normal 0.998728 0.050430 0.000000
    outer loop
      vertex 32.200439 110.333557 3.000000
      vertex 32.205860 110.226204 3.000000
      vertex 32.200439 110.333557 0.000000
    endloop
  endfacet
  facet normal 0.998728 -0.050430 0.000000
    outer loop
      vertex 32.205860 110.440910 0.000000
      vertex 32.200439 110.333557 3.000000
      vertex 32.200439 110.333557 0.000000
    endloop
  endfacet
  facet normal 0.998728 -0.050430 0.000000
    outer loop
      vertex 32.205860 110.440910 3.000000
      vertex 32.200439 110.333557 3.000000
      vertex 32.205860 110.440910 0.000000
    endloop
  endfacet
  facet normal 0.988554 -0.150869 0.000000
    outer loop
      vertex 32.221771 110.545166 0.000000
      vertex 32.205860 110.440910 3.000000
      vertex 32.205860 110.440910 0.000000
    endloop
  endfacet
  facet normal 0.988554 -0.150869 0.000000
    outer loop
      vertex 32.221771 110.545166 3.000000
      vertex 32.205860 110.440910 3.000000
      vertex 32.221771 110.545166 0.000000
    endloop
  endfacet
  facet normal 0.968497 -0.249026 0.000000
    outer loop
      vertex 32.247646 110.645798 0.000000
      vertex 32.221771 110.545166 3.000000
      vertex 32.221771 110.545166 0.000000
    endloop
  endfacet
  facet normal 0.968497 -0.249026 0.000000
    outer loop
      vertex 32.247646 110.645798 3.000000
      vertex 32.221771 110.545166 3.000000
      vertex 32.247646 110.645798 0.000000
    endloop
  endfacet
  facet normal 0.939071 -0.343722 0.000000
    outer loop
      vertex 32.282955 110.742264 0.000000
      vertex 32.247646 110.645798 3.000000
      vertex 32.247646 110.645798 0.000000
    endloop
  endfacet
  facet normal 0.939071 -0.343722 0.000000
    outer loop
      vertex 32.282955 110.742264 3.000000
      vertex 32.247646 110.645798 3.000000
      vertex 32.282955 110.742264 0.000000
    endloop
  endfacet
  facet normal 0.900934 -0.433955 0.000000
    outer loop
      vertex 32.327168 110.834053 0.000000
      vertex 32.282955 110.742264 3.000000
      vertex 32.282955 110.742264 0.000000
    endloop
  endfacet
  facet normal 0.900934 -0.433955 0.000000
    outer loop
      vertex 32.327168 110.834053 3.000000
      vertex 32.282955 110.742264 3.000000
      vertex 32.327168 110.834053 0.000000
    endloop
  endfacet
  facet normal 0.854629 -0.519240 0.000000
    outer loop
      vertex 32.379765 110.920624 0.000000
      vertex 32.327168 110.834053 3.000000
      vertex 32.327168 110.834053 0.000000
    endloop
  endfacet
  facet normal 0.854629 -0.519240 0.000000
    outer loop
      vertex 32.379765 110.920624 3.000000
      vertex 32.327168 110.834053 3.000000
      vertex 32.379765 110.920624 0.000000
    endloop
  endfacet
  facet normal 0.800861 -0.598850 0.000000
    outer loop
      vertex 32.440208 111.001457 0.000000
      vertex 32.379765 110.920624 3.000000
      vertex 32.379765 110.920624 0.000000
    endloop
  endfacet
  facet normal 0.800861 -0.598850 0.000000
    outer loop
      vertex 32.440208 111.001457 3.000000
      vertex 32.379765 110.920624 3.000000
      vertex 32.440208 111.001457 0.000000
    endloop
  endfacet
  facet normal 0.740017 -0.672588 0.000000
    outer loop
      vertex 32.507977 111.076019 0.000000
      vertex 32.440208 111.001457 3.000000
      vertex 32.440208 111.001457 0.000000
    endloop
  endfacet
  facet normal 0.740017 -0.672588 0.000000
    outer loop
      vertex 32.507977 111.076019 3.000000
      vertex 32.440208 111.001457 3.000000
      vertex 32.507977 111.076019 0.000000
    endloop
  endfacet
  facet normal 0.672590 -0.740015 0.000000
    outer loop
      vertex 32.582542 111.143791 0.000000
      vertex 32.507977 111.076019 3.000000
      vertex 32.507977 111.076019 0.000000
    endloop
  endfacet
  facet normal 0.672590 -0.740015 0.000000
    outer loop
      vertex 32.582542 111.143791 3.000000
      vertex 32.507977 111.076019 3.000000
      vertex 32.582542 111.143791 0.000000
    endloop
  endfacet
  facet normal 0.598875 -0.800843 0.000000
    outer loop
      vertex 32.663376 111.204239 0.000000
      vertex 32.582542 111.143791 3.000000
      vertex 32.582542 111.143791 0.000000
    endloop
  endfacet
  facet normal 0.598875 -0.800843 0.000000
    outer loop
      vertex 32.663376 111.204239 3.000000
      vertex 32.582542 111.143791 3.000000
      vertex 32.663376 111.204239 0.000000
    endloop
  endfacet
  facet normal 0.519184 -0.854662 0.000000
    outer loop
      vertex 32.749947 111.256828 0.000000
      vertex 32.663376 111.204239 3.000000
      vertex 32.663376 111.204239 0.000000
    endloop
  endfacet
  facet normal 0.519184 -0.854662 0.000000
    outer loop
      vertex 32.749947 111.256828 3.000000
      vertex 32.663376 111.204239 3.000000
      vertex 32.749947 111.256828 0.000000
    endloop
  endfacet
  facet normal 0.434031 -0.900898 0.000000
    outer loop
      vertex 32.841732 111.301048 0.000000
      vertex 32.749947 111.256828 3.000000
      vertex 32.749947 111.256828 0.000000
    endloop
  endfacet
  facet normal 0.434031 -0.900898 0.000000
    outer loop
      vertex 32.841732 111.301048 3.000000
      vertex 32.749947 111.256828 3.000000
      vertex 32.841732 111.301048 0.000000
    endloop
  endfacet
  facet normal 0.343710 -0.939076 0.000000
    outer loop
      vertex 32.938202 111.336357 0.000000
      vertex 32.841732 111.301048 3.000000
      vertex 32.841732 111.301048 0.000000
    endloop
  endfacet
  facet normal 0.343710 -0.939076 0.000000
    outer loop
      vertex 32.938202 111.336357 3.000000
      vertex 32.841732 111.301048 3.000000
      vertex 32.938202 111.336357 0.000000
    endloop
  endfacet
  facet normal 0.249010 -0.968501 0.000000
    outer loop
      vertex 33.038826 111.362228 0.000000
      vertex 32.938202 111.336357 3.000000
      vertex 32.938202 111.336357 0.000000
    endloop
  endfacet
  facet normal 0.249010 -0.968501 0.000000
    outer loop
      vertex 33.038826 111.362228 3.000000
      vertex 32.938202 111.336357 3.000000
      vertex 33.038826 111.362228 0.000000
    endloop
  endfacet
  facet normal 0.150834 -0.988559 0.000000
    outer loop
      vertex 33.143082 111.378136 0.000000
      vertex 33.038826 111.362228 3.000000
      vertex 33.038826 111.362228 0.000000
    endloop
  endfacet
  facet normal 0.150834 -0.988559 0.000000
    outer loop
      vertex 33.143082 111.378136 3.000000
      vertex 33.038826 111.362228 3.000000
      vertex 33.143082 111.378136 0.000000
    endloop
  endfacet
  facet normal 0.050463 -0.998726 0.000000
    outer loop
      vertex 33.250439 111.383560 0.000000
      vertex 33.143082 111.378136 3.000000
      vertex 33.143082 111.378136 0.000000
    endloop
  endfacet
  facet normal 0.050463 -0.998726 0.000000
    outer loop
      vertex 33.250439 111.383560 3.000000
      vertex 33.143082 111.378136 3.000000
      vertex 33.250439 111.383560 0.000000
    endloop
  endfacet
  facet normal -0.050463 -0.998726 0.000000
    outer loop
      vertex 33.357796 111.378136 0.000000
      vertex 33.250439 111.383560 3.000000
      vertex 33.250439 111.383560 0.000000
    endloop
  endfacet
  facet normal -0.050463 -0.998726 -0.000000
    outer loop
      vertex 33.357796 111.378136 3.000000
      vertex 33.250439 111.383560 3.000000
      vertex 33.357796 111.378136 0.000000
    endloop
  endfacet
  facet normal -0.150834 -0.988559 0.000000
    outer loop
      vertex 33.462051 111.362228 0.000000
      vertex 33.357796 111.378136 3.000000
      vertex 33.357796 111.378136 0.000000
    endloop
  endfacet
  facet normal -0.150834 -0.988559 -0.000000
    outer loop
      vertex 33.462051 111.362228 3.000000
      vertex 33.357796 111.378136 3.000000
      vertex 33.462051 111.362228 0.000000
    endloop
  endfacet
  facet normal -0.249010 -0.968501 0.000000
    outer loop
      vertex 33.562675 111.336357 0.000000
      vertex 33.462051 111.362228 3.000000
      vertex 33.462051 111.362228 0.000000
    endloop
  endfacet
  facet normal -0.249010 -0.968501 -0.000000
    outer loop
      vertex 33.562675 111.336357 3.000000
      vertex 33.462051 111.362228 3.000000
      vertex 33.562675 111.336357 0.000000
    endloop
  endfacet
  facet normal -0.343710 -0.939076 0.000000
    outer loop
      vertex 33.659145 111.301048 0.000000
      vertex 33.562675 111.336357 3.000000
      vertex 33.562675 111.336357 0.000000
    endloop
  endfacet
  facet normal -0.343710 -0.939076 -0.000000
    outer loop
      vertex 33.659145 111.301048 3.000000
      vertex 33.562675 111.336357 3.000000
      vertex 33.659145 111.301048 0.000000
    endloop
  endfacet
  facet normal -0.434031 -0.900898 0.000000
    outer loop
      vertex 33.750931 111.256828 0.000000
      vertex 33.659145 111.301048 3.000000
      vertex 33.659145 111.301048 0.000000
    endloop
  endfacet
  facet normal -0.434031 -0.900898 -0.000000
    outer loop
      vertex 33.750931 111.256828 3.000000
      vertex 33.659145 111.301048 3.000000
      vertex 33.750931 111.256828 0.000000
    endloop
  endfacet
  facet normal -0.519168 -0.854672 0.000000
    outer loop
      vertex 33.837505 111.204239 0.000000
      vertex 33.750931 111.256828 3.000000
      vertex 33.750931 111.256828 0.000000
    endloop
  endfacet
  facet normal -0.519168 -0.854672 -0.000000
    outer loop
      vertex 33.837505 111.204239 3.000000
      vertex 33.750931 111.256828 3.000000
      vertex 33.837505 111.204239 0.000000
    endloop
  endfacet
  facet normal -0.598875 -0.800843 0.000000
    outer loop
      vertex 33.918339 111.143791 0.000000
      vertex 33.837505 111.204239 3.000000
      vertex 33.837505 111.204239 0.000000
    endloop
  endfacet
  facet normal -0.598875 -0.800843 -0.000000
    outer loop
      vertex 33.918339 111.143791 3.000000
      vertex 33.837505 111.204239 3.000000
      vertex 33.918339 111.143791 0.000000
    endloop
  endfacet
  facet normal -0.672609 -0.739998 0.000000
    outer loop
      vertex 33.992901 111.076019 0.000000
      vertex 33.918339 111.143791 3.000000
      vertex 33.918339 111.143791 0.000000
    endloop
  endfacet
  facet normal -0.672609 -0.739998 -0.000000
    outer loop
      vertex 33.992901 111.076019 3.000000
      vertex 33.918339 111.143791 3.000000
      vertex 33.992901 111.076019 0.000000
    endloop
  endfacet
  facet normal -0.740017 -0.672588 0.000000
    outer loop
      vertex 34.060669 111.001457 0.000000
      vertex 33.992901 111.076019 3.000000
      vertex 33.992901 111.076019 0.000000
    endloop
  endfacet
  facet normal -0.740017 -0.672588 -0.000000
    outer loop
      vertex 34.060669 111.001457 3.000000
      vertex 33.992901 111.076019 3.000000
      vertex 34.060669 111.001457 0.000000
    endloop
  endfacet
  facet normal -0.800843 -0.598875 0.000000
    outer loop
      vertex 34.121117 110.920624 0.000000
      vertex 34.060669 111.001457 3.000000
      vertex 34.060669 111.001457 0.000000
    endloop
  endfacet
  facet normal -0.800843 -0.598875 -0.000000
    outer loop
      vertex 34.121117 110.920624 3.000000
      vertex 34.060669 111.001457 3.000000
      vertex 34.121117 110.920624 0.000000
    endloop
  endfacet
  facet normal -0.854645 -0.519212 0.000000
    outer loop
      vertex 34.173710 110.834053 0.000000
      vertex 34.121117 110.920624 3.000000
      vertex 34.121117 110.920624 0.000000
    endloop
  endfacet
  facet normal -0.854645 -0.519212 -0.000000
    outer loop
      vertex 34.173710 110.834053 3.000000
      vertex 34.121117 110.920624 3.000000
      vertex 34.173710 110.834053 0.000000
    endloop
  endfacet
  facet normal -0.900920 -0.433986 0.000000
    outer loop
      vertex 34.217926 110.742264 0.000000
      vertex 34.173710 110.834053 3.000000
      vertex 34.173710 110.834053 0.000000
    endloop
  endfacet
  facet normal -0.900920 -0.433986 -0.000000
    outer loop
      vertex 34.217926 110.742264 3.000000
      vertex 34.173710 110.834053 3.000000
      vertex 34.217926 110.742264 0.000000
    endloop
  endfacet
  facet normal -0.939071 -0.343722 0.000000
    outer loop
      vertex 34.253235 110.645798 0.000000
      vertex 34.217926 110.742264 3.000000
      vertex 34.217926 110.742264 0.000000
    endloop
  endfacet
  facet normal -0.939071 -0.343722 -0.000000
    outer loop
      vertex 34.253235 110.645798 3.000000
      vertex 34.217926 110.742264 3.000000
      vertex 34.253235 110.645798 0.000000
    endloop
  endfacet
  facet normal -0.968506 -0.248992 0.000000
    outer loop
      vertex 34.279106 110.545166 0.000000
      vertex 34.253235 110.645798 3.000000
      vertex 34.253235 110.645798 0.000000
    endloop
  endfacet
  facet normal -0.968506 -0.248992 -0.000000
    outer loop
      vertex 34.279106 110.545166 3.000000
      vertex 34.253235 110.645798 3.000000
      vertex 34.279106 110.545166 0.000000
    endloop
  endfacet
  facet normal -0.988554 -0.150869 0.000000
    outer loop
      vertex 34.295017 110.440910 0.000000
      vertex 34.279106 110.545166 3.000000
      vertex 34.279106 110.545166 0.000000
    endloop
  endfacet
  facet normal -0.988554 -0.150869 -0.000000
    outer loop
      vertex 34.295017 110.440910 3.000000
      vertex 34.279106 110.545166 3.000000
      vertex 34.295017 110.440910 0.000000
    endloop
  endfacet
  facet normal -0.998726 -0.050465 0.000000
    outer loop
      vertex 34.300442 110.333557 0.000000
      vertex 34.295017 110.440910 3.000000
      vertex 34.295017 110.440910 0.000000
    endloop
  endfacet
  facet normal -0.998726 -0.050465 -0.000000
    outer loop
      vertex 34.300442 110.333557 3.000000
      vertex 34.295017 110.440910 3.000000
      vertex 34.300442 110.333557 0.000000
    endloop
  endfacet
  facet normal -0.998722 0.050532 0.000000
    outer loop
      vertex 153.252701 192.585907 3.000000
      vertex 153.252701 192.585907 0.000000
      vertex 153.247269 192.478546 0.000000
    endloop
  endfacet
  facet normal -0.998722 0.050532 0.000000
    outer loop
      vertex 153.247269 192.478546 3.000000
      vertex 153.252701 192.585907 3.000000
      vertex 153.247269 192.478546 0.000000
    endloop
  endfacet
  facet normal -0.988568 0.150774 0.000000
    outer loop
      vertex 153.231369 192.374298 0.000000
      vertex 153.247269 192.478546 3.000000
      vertex 153.247269 192.478546 0.000000
    endloop
  endfacet
  facet normal -0.988568 0.150774 0.000000
    outer loop
      vertex 153.231369 192.374298 3.000000
      vertex 153.247269 192.478546 3.000000
      vertex 153.231369 192.374298 0.000000
    endloop
  endfacet
  facet normal -0.968488 0.249061 0.000000
    outer loop
      vertex 153.205490 192.273666 0.000000
      vertex 153.231369 192.374298 3.000000
      vertex 153.231369 192.374298 0.000000
    endloop
  endfacet
  facet normal -0.968488 0.249061 0.000000
    outer loop
      vertex 153.205490 192.273666 3.000000
      vertex 153.231369 192.374298 3.000000
      vertex 153.205490 192.273666 0.000000
    endloop
  endfacet
  facet normal -0.939071 0.343722 0.000000
    outer loop
      vertex 153.170181 192.177200 0.000000
      vertex 153.205490 192.273666 3.000000
      vertex 153.205490 192.273666 0.000000
    endloop
  endfacet
  facet normal -0.939071 0.343722 0.000000
    outer loop
      vertex 153.170181 192.177200 3.000000
      vertex 153.205490 192.273666 3.000000
      vertex 153.170181 192.177200 0.000000
    endloop
  endfacet
  facet normal -0.900919 0.433987 0.000000
    outer loop
      vertex 153.125961 192.085403 0.000000
      vertex 153.170181 192.177200 3.000000
      vertex 153.170181 192.177200 0.000000
    endloop
  endfacet
  facet normal -0.900919 0.433987 0.000000
    outer loop
      vertex 153.125961 192.085403 3.000000
      vertex 153.170181 192.177200 3.000000
      vertex 153.125961 192.085403 0.000000
    endloop
  endfacet
  facet normal -0.854675 0.519163 0.000000
    outer loop
      vertex 153.073380 191.998840 0.000000
      vertex 153.125961 192.085403 3.000000
      vertex 153.125961 192.085403 0.000000
    endloop
  endfacet
  facet normal -0.854675 0.519163 0.000000
    outer loop
      vertex 153.073380 191.998840 3.000000
      vertex 153.125961 192.085403 3.000000
      vertex 153.073380 191.998840 0.000000
    endloop
  endfacet
  facet normal -0.800834 0.598887 0.000000
    outer loop
      vertex 153.012924 191.917999 0.000000
      vertex 153.073380 191.998840 3.000000
      vertex 153.073380 191.998840 0.000000
    endloop
  endfacet
  facet normal -0.800834 0.598887 0.000000
    outer loop
      vertex 153.012924 191.917999 3.000000
      vertex 153.073380 191.998840 3.000000
      vertex 153.012924 191.917999 0.000000
    endloop
  endfacet
  facet normal -0.740002 0.672605 0.000000
    outer loop
      vertex 152.945160 191.843445 0.000000
      vertex 153.012924 191.917999 3.000000
      vertex 153.012924 191.917999 0.000000
    endloop
  endfacet
  facet normal -0.740002 0.672605 0.000000
    outer loop
      vertex 152.945160 191.843445 3.000000
      vertex 153.012924 191.917999 3.000000
      vertex 152.945160 191.843445 0.000000
    endloop
  endfacet
  facet normal -0.672612 0.739995 0.000000
    outer loop
      vertex 152.870590 191.775665 0.000000
      vertex 152.945160 191.843445 3.000000
      vertex 152.945160 191.843445 0.000000
    endloop
  endfacet
  facet normal -0.672612 0.739995 0.000000
    outer loop
      vertex 152.870590 191.775665 3.000000
      vertex 152.945160 191.843445 3.000000
      vertex 152.870590 191.775665 0.000000
    endloop
  endfacet
  facet normal -0.598862 0.800852 0.000000
    outer loop
      vertex 152.789764 191.715225 0.000000
      vertex 152.870590 191.775665 3.000000
      vertex 152.870590 191.775665 0.000000
    endloop
  endfacet
  facet normal -0.598862 0.800852 0.000000
    outer loop
      vertex 152.789764 191.715225 3.000000
      vertex 152.870590 191.775665 3.000000
      vertex 152.789764 191.715225 0.000000
    endloop
  endfacet
  facet normal -0.519206 0.854649 0.000000
    outer loop
      vertex 152.703186 191.662628 0.000000
      vertex 152.789764 191.715225 3.000000
      vertex 152.789764 191.715225 0.000000
    endloop
  endfacet
  facet normal -0.519206 0.854649 0.000000
    outer loop
      vertex 152.703186 191.662628 3.000000
      vertex 152.789764 191.715225 3.000000
      vertex 152.703186 191.662628 0.000000
    endloop
  endfacet
  facet normal -0.433924 0.900950 0.000000
    outer loop
      vertex 152.611404 191.618423 0.000000
      vertex 152.703186 191.662628 3.000000
      vertex 152.703186 191.662628 0.000000
    endloop
  endfacet
  facet normal -0.433924 0.900950 0.000000
    outer loop
      vertex 152.611404 191.618423 3.000000
      vertex 152.703186 191.662628 3.000000
      vertex 152.611404 191.618423 0.000000
    endloop
  endfacet
  facet normal -0.343722 0.939071 0.000000
    outer loop
      vertex 152.514938 191.583115 0.000000
      vertex 152.611404 191.618423 3.000000
      vertex 152.611404 191.618423 0.000000
    endloop
  endfacet
  facet normal -0.343722 0.939071 0.000000
    outer loop
      vertex 152.514938 191.583115 3.000000
      vertex 152.611404 191.618423 3.000000
      vertex 152.514938 191.583115 0.000000
    endloop
  endfacet
  facet normal -0.249061 0.968488 0.000000
    outer loop
      vertex 152.414307 191.557236 0.000000
      vertex 152.514938 191.583115 3.000000
      vertex 152.514938 191.583115 0.000000
    endloop
  endfacet
  facet normal -0.249061 0.968488 0.000000
    outer loop
      vertex 152.414307 191.557236 3.000000
      vertex 152.514938 191.583115 3.000000
      vertex 152.414307 191.557236 0.000000
    endloop
  endfacet
  facet normal -0.150915 0.988547 0.000000
    outer loop
      vertex 152.310059 191.541321 0.000000
      vertex 152.414307 191.557236 3.000000
      vertex 152.414307 191.557236 0.000000
    endloop
  endfacet
  facet normal -0.150915 0.988547 0.000000
    outer loop
      vertex 152.310059 191.541321 3.000000
      vertex 152.414307 191.557236 3.000000
      vertex 152.310059 191.541321 0.000000
    endloop
  endfacet
  facet normal -0.050391 0.998730 0.000000
    outer loop
      vertex 152.202698 191.535904 0.000000
      vertex 152.310059 191.541321 3.000000
      vertex 152.310059 191.541321 0.000000
    endloop
  endfacet
  facet normal -0.050391 0.998730 0.000000
    outer loop
      vertex 152.202698 191.535904 3.000000
      vertex 152.310059 191.541321 3.000000
      vertex 152.202698 191.535904 0.000000
    endloop
  endfacet
  facet normal 0.050391 0.998730 0.000000
    outer loop
      vertex 152.095337 191.541321 0.000000
      vertex 152.202698 191.535904 3.000000
      vertex 152.202698 191.535904 0.000000
    endloop
  endfacet
  facet normal 0.050391 0.998730 0.000000
    outer loop
      vertex 152.095337 191.541321 3.000000
      vertex 152.202698 191.535904 3.000000
      vertex 152.095337 191.541321 0.000000
    endloop
  endfacet
  facet normal 0.150915 0.988547 0.000000
    outer loop
      vertex 151.991089 191.557236 0.000000
      vertex 152.095337 191.541321 3.000000
      vertex 152.095337 191.541321 0.000000
    endloop
  endfacet
  facet normal 0.150915 0.988547 0.000000
    outer loop
      vertex 151.991089 191.557236 3.000000
      vertex 152.095337 191.541321 3.000000
      vertex 151.991089 191.557236 0.000000
    endloop
  endfacet
  facet normal 0.249061 0.968488 0.000000
    outer loop
      vertex 151.890457 191.583115 0.000000
      vertex 151.991089 191.557236 3.000000
      vertex 151.991089 191.557236 0.000000
    endloop
  endfacet
  facet normal 0.249061 0.968488 0.000000
    outer loop
      vertex 151.890457 191.583115 3.000000
      vertex 151.991089 191.557236 3.000000
      vertex 151.890457 191.583115 0.000000
    endloop
  endfacet
  facet normal 0.343722 0.939071 0.000000
    outer loop
      vertex 151.793991 191.618423 0.000000
      vertex 151.890457 191.583115 3.000000
      vertex 151.890457 191.583115 0.000000
    endloop
  endfacet
  facet normal 0.343722 0.939071 0.000000
    outer loop
      vertex 151.793991 191.618423 3.000000
      vertex 151.890457 191.583115 3.000000
      vertex 151.793991 191.618423 0.000000
    endloop
  endfacet
  facet normal 0.433924 0.900950 0.000000
    outer loop
      vertex 151.702209 191.662628 0.000000
      vertex 151.793991 191.618423 3.000000
      vertex 151.793991 191.618423 0.000000
    endloop
  endfacet
  facet normal 0.433924 0.900950 0.000000
    outer loop
      vertex 151.702209 191.662628 3.000000
      vertex 151.793991 191.618423 3.000000
      vertex 151.702209 191.662628 0.000000
    endloop
  endfacet
  facet normal 0.519206 0.854649 0.000000
    outer loop
      vertex 151.615631 191.715225 0.000000
      vertex 151.702209 191.662628 3.000000
      vertex 151.702209 191.662628 0.000000
    endloop
  endfacet
  facet normal 0.519206 0.854649 0.000000
    outer loop
      vertex 151.615631 191.715225 3.000000
      vertex 151.702209 191.662628 3.000000
      vertex 151.615631 191.715225 0.000000
    endloop
  endfacet
  facet normal 0.598862 0.800852 0.000000
    outer loop
      vertex 151.534805 191.775665 0.000000
      vertex 151.615631 191.715225 3.000000
      vertex 151.615631 191.715225 0.000000
    endloop
  endfacet
  facet normal 0.598862 0.800852 0.000000
    outer loop
      vertex 151.534805 191.775665 3.000000
      vertex 151.615631 191.715225 3.000000
      vertex 151.534805 191.775665 0.000000
    endloop
  endfacet
  facet normal 0.672612 0.739995 0.000000
    outer loop
      vertex 151.460236 191.843445 0.000000
      vertex 151.534805 191.775665 3.000000
      vertex 151.534805 191.775665 0.000000
    endloop
  endfacet
  facet normal 0.672612 0.739995 0.000000
    outer loop
      vertex 151.460236 191.843445 3.000000
      vertex 151.534805 191.775665 3.000000
      vertex 151.460236 191.843445 0.000000
    endloop
  endfacet
  facet normal 0.740002 0.672605 0.000000
    outer loop
      vertex 151.392471 191.917999 0.000000
      vertex 151.460236 191.843445 3.000000
      vertex 151.460236 191.843445 0.000000
    endloop
  endfacet
  facet normal 0.740002 0.672605 0.000000
    outer loop
      vertex 151.392471 191.917999 3.000000
      vertex 151.460236 191.843445 3.000000
      vertex 151.392471 191.917999 0.000000
    endloop
  endfacet
  facet normal 0.800834 0.598887 0.000000
    outer loop
      vertex 151.332016 191.998840 0.000000
      vertex 151.392471 191.917999 3.000000
      vertex 151.392471 191.917999 0.000000
    endloop
  endfacet
  facet normal 0.800834 0.598887 0.000000
    outer loop
      vertex 151.332016 191.998840 3.000000
      vertex 151.392471 191.917999 3.000000
      vertex 151.332016 191.998840 0.000000
    endloop
  endfacet
  facet normal 0.854608 0.519273 0.000000
    outer loop
      vertex 151.279419 192.085403 0.000000
      vertex 151.332016 191.998840 3.000000
      vertex 151.332016 191.998840 0.000000
    endloop
  endfacet
  facet normal 0.854608 0.519273 0.000000
    outer loop
      vertex 151.279419 192.085403 3.000000
      vertex 151.332016 191.998840 3.000000
      vertex 151.279419 192.085403 0.000000
    endloop
  endfacet
  facet normal 0.900978 0.433865 0.000000
    outer loop
      vertex 151.235214 192.177200 0.000000
      vertex 151.279419 192.085403 3.000000
      vertex 151.279419 192.085403 0.000000
    endloop
  endfacet
  facet normal 0.900978 0.433865 0.000000
    outer loop
      vertex 151.235214 192.177200 3.000000
      vertex 151.279419 192.085403 3.000000
      vertex 151.235214 192.177200 0.000000
    endloop
  endfacet
  facet normal 0.939071 0.343722 0.000000
    outer loop
      vertex 151.199905 192.273666 0.000000
      vertex 151.235214 192.177200 3.000000
      vertex 151.235214 192.177200 0.000000
    endloop
  endfacet
  facet normal 0.939071 0.343722 0.000000
    outer loop
      vertex 151.199905 192.273666 3.000000
      vertex 151.235214 192.177200 3.000000
      vertex 151.199905 192.273666 0.000000
    endloop
  endfacet
  facet normal 0.968488 0.249061 0.000000
    outer loop
      vertex 151.174026 192.374298 0.000000
      vertex 151.199905 192.273666 3.000000
      vertex 151.199905 192.273666 0.000000
    endloop
  endfacet
  facet normal 0.968488 0.249061 0.000000
    outer loop
      vertex 151.174026 192.374298 3.000000
      vertex 151.199905 192.273666 3.000000
      vertex 151.174026 192.374298 0.000000
    endloop
  endfacet
  facet normal 0.988547 0.150915 0.000000
    outer loop
      vertex 151.158112 192.478546 0.000000
      vertex 151.174026 192.374298 3.000000
      vertex 151.174026 192.374298 0.000000
    endloop
  endfacet
  facet normal 0.988547 0.150915 0.000000
    outer loop
      vertex 151.158112 192.478546 3.000000
      vertex 151.174026 192.374298 3.000000
      vertex 151.158112 192.478546 0.000000
    endloop
  endfacet
  facet normal 0.998730 0.050391 0.000000
    outer loop
      vertex 151.152695 192.585907 0.000000
      vertex 151.158112 192.478546 3.000000
      vertex 151.158112 192.478546 0.000000
    endloop
  endfacet
  facet normal 0.998730 0.050391 0.000000
    outer loop
      vertex 151.152695 192.585907 3.000000
      vertex 151.158112 192.478546 3.000000
      vertex 151.152695 192.585907 0.000000
    endloop
  endfacet
  facet normal 0.998729 -0.050398 0.000000
    outer loop
      vertex 151.158112 192.693253 0.000000
      vertex 151.152695 192.585907 3.000000
      vertex 151.152695 192.585907 0.000000
    endloop
  endfacet
  facet normal 0.998729 -0.050398 0.000000
    outer loop
      vertex 151.158112 192.693253 3.000000
      vertex 151.152695 192.585907 3.000000
      vertex 151.158112 192.693253 0.000000
    endloop
  endfacet
  facet normal 0.988550 -0.150894 0.000000
    outer loop
      vertex 151.174026 192.797516 0.000000
      vertex 151.158112 192.693253 3.000000
      vertex 151.158112 192.693253 0.000000
    endloop
  endfacet
  facet normal 0.988550 -0.150894 0.000000
    outer loop
      vertex 151.174026 192.797516 3.000000
      vertex 151.158112 192.693253 3.000000
      vertex 151.174026 192.797516 0.000000
    endloop
  endfacet
  facet normal 0.968488 -0.249061 0.000000
    outer loop
      vertex 151.199905 192.898148 0.000000
      vertex 151.174026 192.797516 3.000000
      vertex 151.174026 192.797516 0.000000
    endloop
  endfacet
  facet normal 0.968488 -0.249061 0.000000
    outer loop
      vertex 151.199905 192.898148 3.000000
      vertex 151.174026 192.797516 3.000000
      vertex 151.199905 192.898148 0.000000
    endloop
  endfacet
  facet normal 0.939071 -0.343722 0.000000
    outer loop
      vertex 151.235214 192.994614 0.000000
      vertex 151.199905 192.898148 3.000000
      vertex 151.199905 192.898148 0.000000
    endloop
  endfacet
  facet normal 0.939071 -0.343722 0.000000
    outer loop
      vertex 151.235214 192.994614 3.000000
      vertex 151.199905 192.898148 3.000000
      vertex 151.235214 192.994614 0.000000
    endloop
  endfacet
  facet normal 0.900950 -0.433924 0.000000
    outer loop
      vertex 151.279419 193.086395 0.000000
      vertex 151.235214 192.994614 3.000000
      vertex 151.235214 192.994614 0.000000
    endloop
  endfacet
  facet normal 0.900950 -0.433924 0.000000
    outer loop
      vertex 151.279419 193.086395 3.000000
      vertex 151.235214 192.994614 3.000000
      vertex 151.279419 193.086395 0.000000
    endloop
  endfacet
  facet normal 0.854649 -0.519206 0.000000
    outer loop
      vertex 151.332016 193.172974 0.000000
      vertex 151.279419 193.086395 3.000000
      vertex 151.279419 193.086395 0.000000
    endloop
  endfacet
  facet normal 0.854649 -0.519206 0.000000
    outer loop
      vertex 151.332016 193.172974 3.000000
      vertex 151.279419 193.086395 3.000000
      vertex 151.332016 193.172974 0.000000
    endloop
  endfacet
  facet normal 0.800779 -0.598959 0.000000
    outer loop
      vertex 151.392471 193.253799 0.000000
      vertex 151.332016 193.172974 3.000000
      vertex 151.332016 193.172974 0.000000
    endloop
  endfacet
  facet normal 0.800779 -0.598959 0.000000
    outer loop
      vertex 151.392471 193.253799 3.000000
      vertex 151.332016 193.172974 3.000000
      vertex 151.392471 193.253799 0.000000
    endloop
  endfacet
  facet normal 0.740070 -0.672530 0.000000
    outer loop
      vertex 151.460236 193.328369 0.000000
      vertex 151.392471 193.253799 3.000000
      vertex 151.392471 193.253799 0.000000
    endloop
  endfacet
  facet normal 0.740070 -0.672530 0.000000
    outer loop
      vertex 151.460236 193.328369 3.000000
      vertex 151.392471 193.253799 3.000000
      vertex 151.460236 193.328369 0.000000
    endloop
  endfacet
  facet normal 0.672530 -0.740070 0.000000
    outer loop
      vertex 151.534805 193.396133 0.000000
      vertex 151.460236 193.328369 3.000000
      vertex 151.460236 193.328369 0.000000
    endloop
  endfacet
  facet normal 0.672530 -0.740070 0.000000
    outer loop
      vertex 151.534805 193.396133 3.000000
      vertex 151.460236 193.328369 3.000000
      vertex 151.534805 193.396133 0.000000
    endloop
  endfacet
  facet normal 0.598862 -0.800852 0.000000
    outer loop
      vertex 151.615631 193.456573 0.000000
      vertex 151.534805 193.396133 3.000000
      vertex 151.534805 193.396133 0.000000
    endloop
  endfacet
  facet normal 0.598862 -0.800852 0.000000
    outer loop
      vertex 151.615631 193.456573 3.000000
      vertex 151.534805 193.396133 3.000000
      vertex 151.615631 193.456573 0.000000
    endloop
  endfacet
  facet normal 0.519206 -0.854649 0.000000
    outer loop
      vertex 151.702209 193.509171 0.000000
      vertex 151.615631 193.456573 3.000000
      vertex 151.615631 193.456573 0.000000
    endloop
  endfacet
  facet normal 0.519206 -0.854649 0.000000
    outer loop
      vertex 151.702209 193.509171 3.000000
      vertex 151.615631 193.456573 3.000000
      vertex 151.702209 193.509171 0.000000
    endloop
  endfacet
  facet normal 0.434045 -0.900891 0.000000
    outer loop
      vertex 151.793991 193.553391 0.000000
      vertex 151.702209 193.509171 3.000000
      vertex 151.702209 193.509171 0.000000
    endloop
  endfacet
  facet normal 0.434045 -0.900891 0.000000
    outer loop
      vertex 151.793991 193.553391 3.000000
      vertex 151.702209 193.509171 3.000000
      vertex 151.793991 193.553391 0.000000
    endloop
  endfacet
  facet normal 0.343722 -0.939071 0.000000
    outer loop
      vertex 151.890457 193.588699 0.000000
      vertex 151.793991 193.553391 3.000000
      vertex 151.793991 193.553391 0.000000
    endloop
  endfacet
  facet normal 0.343722 -0.939071 0.000000
    outer loop
      vertex 151.890457 193.588699 3.000000
      vertex 151.793991 193.553391 3.000000
      vertex 151.890457 193.588699 0.000000
    endloop
  endfacet
  facet normal 0.249061 -0.968488 0.000000
    outer loop
      vertex 151.991089 193.614578 0.000000
      vertex 151.890457 193.588699 3.000000
      vertex 151.890457 193.588699 0.000000
    endloop
  endfacet
  facet normal 0.249061 -0.968488 0.000000
    outer loop
      vertex 151.991089 193.614578 3.000000
      vertex 151.890457 193.588699 3.000000
      vertex 151.991089 193.614578 0.000000
    endloop
  endfacet
  facet normal 0.150774 -0.988568 0.000000
    outer loop
      vertex 152.095337 193.630478 0.000000
      vertex 151.991089 193.614578 3.000000
      vertex 151.991089 193.614578 0.000000
    endloop
  endfacet
  facet normal 0.150774 -0.988568 0.000000
    outer loop
      vertex 152.095337 193.630478 3.000000
      vertex 151.991089 193.614578 3.000000
      vertex 152.095337 193.630478 0.000000
    endloop
  endfacet
  facet normal 0.050532 -0.998722 0.000000
    outer loop
      vertex 152.202698 193.635910 0.000000
      vertex 152.095337 193.630478 3.000000
      vertex 152.095337 193.630478 0.000000
    endloop
  endfacet
  facet normal 0.050532 -0.998722 0.000000
    outer loop
      vertex 152.202698 193.635910 3.000000
      vertex 152.095337 193.630478 3.000000
      vertex 152.202698 193.635910 0.000000
    endloop
  endfacet
  facet normal -0.050532 -0.998722 0.000000
    outer loop
      vertex 152.310059 193.630478 0.000000
      vertex 152.202698 193.635910 3.000000
      vertex 152.202698 193.635910 0.000000
    endloop
  endfacet
  facet normal -0.050532 -0.998722 -0.000000
    outer loop
      vertex 152.310059 193.630478 3.000000
      vertex 152.202698 193.635910 3.000000
      vertex 152.310059 193.630478 0.000000
    endloop
  endfacet
  facet normal -0.150774 -0.988568 0.000000
    outer loop
      vertex 152.414307 193.614578 0.000000
      vertex 152.310059 193.630478 3.000000
      vertex 152.310059 193.630478 0.000000
    endloop
  endfacet
  facet normal -0.150774 -0.988568 -0.000000
    outer loop
      vertex 152.414307 193.614578 3.000000
      vertex 152.310059 193.630478 3.000000
      vertex 152.414307 193.614578 0.000000
    endloop
  endfacet
  facet normal -0.249061 -0.968488 0.000000
    outer loop
      vertex 152.514938 193.588699 0.000000
      vertex 152.414307 193.614578 3.000000
      vertex 152.414307 193.614578 0.000000
    endloop
  endfacet
  facet normal -0.249061 -0.968488 -0.000000
    outer loop
      vertex 152.514938 193.588699 3.000000
      vertex 152.414307 193.614578 3.000000
      vertex 152.514938 193.588699 0.000000
    endloop
  endfacet
  facet normal -0.343722 -0.939071 0.000000
    outer loop
      vertex 152.611404 193.553391 0.000000
      vertex 152.514938 193.588699 3.000000
      vertex 152.514938 193.588699 0.000000
    endloop
  endfacet
  facet normal -0.343722 -0.939071 -0.000000
    outer loop
      vertex 152.611404 193.553391 3.000000
      vertex 152.514938 193.588699 3.000000
      vertex 152.611404 193.553391 0.000000
    endloop
  endfacet
  facet normal -0.434045 -0.900891 0.000000
    outer loop
      vertex 152.703186 193.509171 0.000000
      vertex 152.611404 193.553391 3.000000
      vertex 152.611404 193.553391 0.000000
    endloop
  endfacet
  facet normal -0.434045 -0.900891 -0.000000
    outer loop
      vertex 152.703186 193.509171 3.000000
      vertex 152.611404 193.553391 3.000000
      vertex 152.703186 193.509171 0.000000
    endloop
  endfacet
  facet normal -0.519206 -0.854649 0.000000
    outer loop
      vertex 152.789764 193.456573 0.000000
      vertex 152.703186 193.509171 3.000000
      vertex 152.703186 193.509171 0.000000
    endloop
  endfacet
  facet normal -0.519206 -0.854649 -0.000000
    outer loop
      vertex 152.789764 193.456573 3.000000
      vertex 152.703186 193.509171 3.000000
      vertex 152.789764 193.456573 0.000000
    endloop
  endfacet
  facet normal -0.598862 -0.800852 0.000000
    outer loop
      vertex 152.870590 193.396133 0.000000
      vertex 152.789764 193.456573 3.000000
      vertex 152.789764 193.456573 0.000000
    endloop
  endfacet
  facet normal -0.598862 -0.800852 -0.000000
    outer loop
      vertex 152.870590 193.396133 3.000000
      vertex 152.789764 193.456573 3.000000
      vertex 152.870590 193.396133 0.000000
    endloop
  endfacet
  facet normal -0.672530 -0.740070 0.000000
    outer loop
      vertex 152.945160 193.328369 0.000000
      vertex 152.870590 193.396133 3.000000
      vertex 152.870590 193.396133 0.000000
    endloop
  endfacet
  facet normal -0.672530 -0.740070 -0.000000
    outer loop
      vertex 152.945160 193.328369 3.000000
      vertex 152.870590 193.396133 3.000000
      vertex 152.945160 193.328369 0.000000
    endloop
  endfacet
  facet normal -0.740070 -0.672530 0.000000
    outer loop
      vertex 153.012924 193.253799 0.000000
      vertex 152.945160 193.328369 3.000000
      vertex 152.945160 193.328369 0.000000
    endloop
  endfacet
  facet normal -0.740070 -0.672530 -0.000000
    outer loop
      vertex 153.012924 193.253799 3.000000
      vertex 152.945160 193.328369 3.000000
      vertex 153.012924 193.253799 0.000000
    endloop
  endfacet
  facet normal -0.800779 -0.598959 0.000000
    outer loop
      vertex 153.073380 193.172974 0.000000
      vertex 153.012924 193.253799 3.000000
      vertex 153.012924 193.253799 0.000000
    endloop
  endfacet
  facet normal -0.800779 -0.598959 -0.000000
    outer loop
      vertex 153.073380 193.172974 3.000000
      vertex 153.012924 193.253799 3.000000
      vertex 153.073380 193.172974 0.000000
    endloop
  endfacet
  facet normal -0.854716 -0.519096 0.000000
    outer loop
      vertex 153.125961 193.086395 0.000000
      vertex 153.073380 193.172974 3.000000
      vertex 153.073380 193.172974 0.000000
    endloop
  endfacet
  facet normal -0.854716 -0.519096 -0.000000
    outer loop
      vertex 153.125961 193.086395 3.000000
      vertex 153.073380 193.172974 3.000000
      vertex 153.125961 193.086395 0.000000
    endloop
  endfacet
  facet normal -0.900891 -0.434045 0.000000
    outer loop
      vertex 153.170181 192.994614 0.000000
      vertex 153.125961 193.086395 3.000000
      vertex 153.125961 193.086395 0.000000
    endloop
  endfacet
  facet normal -0.900891 -0.434045 -0.000000
    outer loop
      vertex 153.170181 192.994614 3.000000
      vertex 153.125961 193.086395 3.000000
      vertex 153.170181 192.994614 0.000000
    endloop
  endfacet
  facet normal -0.939071 -0.343722 0.000000
    outer loop
      vertex 153.205490 192.898148 0.000000
      vertex 153.170181 192.994614 3.000000
      vertex 153.170181 192.994614 0.000000
    endloop
  endfacet
  facet normal -0.939071 -0.343722 -0.000000
    outer loop
      vertex 153.205490 192.898148 3.000000
      vertex 153.170181 192.994614 3.000000
      vertex 153.205490 192.898148 0.000000
    endloop
  endfacet
  facet normal -0.968488 -0.249061 0.000000
    outer loop
      vertex 153.231369 192.797516 0.000000
      vertex 153.205490 192.898148 3.000000
      vertex 153.205490 192.898148 0.000000
    endloop
  endfacet
  facet normal -0.968488 -0.249061 -0.000000
    outer loop
      vertex 153.231369 192.797516 3.000000
      vertex 153.205490 192.898148 3.000000
      vertex 153.231369 192.797516 0.000000
    endloop
  endfacet
  facet normal -0.988572 -0.150752 0.000000
    outer loop
      vertex 153.247269 192.693253 0.000000
      vertex 153.231369 192.797516 3.000000
      vertex 153.231369 192.797516 0.000000
    endloop
  endfacet
  facet normal -0.988572 -0.150752 -0.000000
    outer loop
      vertex 153.247269 192.693253 3.000000
      vertex 153.231369 192.797516 3.000000
      vertex 153.247269 192.693253 0.000000
    endloop
  endfacet
  facet normal -0.998722 -0.050539 0.000000
    outer loop
      vertex 153.252701 192.585907 0.000000
      vertex 153.247269 192.693253 3.000000
      vertex 153.247269 192.693253 0.000000
    endloop
  endfacet
  facet normal -0.998722 -0.050539 -0.000000
    outer loop
      vertex 153.252701 192.585907 3.000000
      vertex 153.247269 192.693253 3.000000
      vertex 153.252701 192.585907 0.000000
    endloop
  endfacet
  facet normal -0.998730 0.050391 0.000000
    outer loop
      vertex 100.094131 203.012619 3.000000
      vertex 100.094131 203.012619 0.000000
      vertex 100.088715 202.905258 0.000000
    endloop
  endfacet
  facet normal -0.998730 0.050391 0.000000
    outer loop
      vertex 100.088715 202.905258 3.000000
      vertex 100.094131 203.012619 3.000000
      vertex 100.088715 202.905258 0.000000
    endloop
  endfacet
  facet normal -0.988550 0.150894 0.000000
    outer loop
      vertex 100.072800 202.800995 0.000000
      vertex 100.088715 202.905258 3.000000
      vertex 100.088715 202.905258 0.000000
    endloop
  endfacet
  facet normal -0.988550 0.150894 0.000000
    outer loop
      vertex 100.072800 202.800995 3.000000
      vertex 100.088715 202.905258 3.000000
      vertex 100.072800 202.800995 0.000000
    endloop
  endfacet
  facet normal -0.968496 0.249027 0.000000
    outer loop
      vertex 100.046928 202.700378 0.000000
      vertex 100.072800 202.800995 3.000000
      vertex 100.072800 202.800995 0.000000
    endloop
  endfacet
  facet normal -0.968496 0.249027 0.000000
    outer loop
      vertex 100.046928 202.700378 3.000000
      vertex 100.072800 202.800995 3.000000
      vertex 100.046928 202.700378 0.000000
    endloop
  endfacet
  facet normal -0.939089 0.343674 0.000000
    outer loop
      vertex 100.011620 202.603897 0.000000
      vertex 100.046928 202.700378 3.000000
      vertex 100.046928 202.700378 0.000000
    endloop
  endfacet
  facet normal -0.939089 0.343674 0.000000
    outer loop
      vertex 100.011620 202.603897 3.000000
      vertex 100.046928 202.700378 3.000000
      vertex 100.011620 202.603897 0.000000
    endloop
  endfacet
  facet normal -0.900920 0.433984 0.000000
    outer loop
      vertex 99.967407 202.512115 0.000000
      vertex 100.011620 202.603897 3.000000
      vertex 100.011620 202.603897 0.000000
    endloop
  endfacet
  facet normal -0.900920 0.433984 0.000000
    outer loop
      vertex 99.967407 202.512115 3.000000
      vertex 100.011620 202.603897 3.000000
      vertex 99.967407 202.512115 0.000000
    endloop
  endfacet
  facet normal -0.854608 0.519273 0.000000
    outer loop
      vertex 99.914810 202.425552 0.000000
      vertex 99.967407 202.512115 3.000000
      vertex 99.967407 202.512115 0.000000
    endloop
  endfacet
  facet normal -0.854608 0.519273 0.000000
    outer loop
      vertex 99.914810 202.425552 3.000000
      vertex 99.967407 202.512115 3.000000
      vertex 99.914810 202.425552 0.000000
    endloop
  endfacet
  facet normal -0.800870 0.598838 0.000000
    outer loop
      vertex 99.854362 202.344711 0.000000
      vertex 99.914810 202.425552 3.000000
      vertex 99.914810 202.425552 0.000000
    endloop
  endfacet
  facet normal -0.800870 0.598838 0.000000
    outer loop
      vertex 99.854362 202.344711 3.000000
      vertex 99.914810 202.425552 3.000000
      vertex 99.854362 202.344711 0.000000
    endloop
  endfacet
  facet normal -0.740002 0.672605 0.000000
    outer loop
      vertex 99.786598 202.270157 0.000000
      vertex 99.854362 202.344711 3.000000
      vertex 99.854362 202.344711 0.000000
    endloop
  endfacet
  facet normal -0.740002 0.672605 0.000000
    outer loop
      vertex 99.786598 202.270157 3.000000
      vertex 99.854362 202.344711 3.000000
      vertex 99.786598 202.270157 0.000000
    endloop
  endfacet
  facet normal -0.672650 0.739961 0.000000
    outer loop
      vertex 99.712036 202.202377 0.000000
      vertex 99.786598 202.270157 3.000000
      vertex 99.786598 202.270157 0.000000
    endloop
  endfacet
  facet normal -0.672650 0.739961 0.000000
    outer loop
      vertex 99.712036 202.202377 3.000000
      vertex 99.786598 202.270157 3.000000
      vertex 99.712036 202.202377 0.000000
    endloop
  endfacet
  facet normal -0.598826 0.800879 0.000000
    outer loop
      vertex 99.631203 202.141937 0.000000
      vertex 99.712036 202.202377 3.000000
      vertex 99.712036 202.202377 0.000000
    endloop
  endfacet
  facet normal -0.598826 0.800879 0.000000
    outer loop
      vertex 99.631203 202.141937 3.000000
      vertex 99.712036 202.202377 3.000000
      vertex 99.631203 202.141937 0.000000
    endloop
  endfacet
  facet normal -0.519206 0.854649 0.000000
    outer loop
      vertex 99.544624 202.089340 0.000000
      vertex 99.631203 202.141937 3.000000
      vertex 99.631203 202.141937 0.000000
    endloop
  endfacet
  facet normal -0.519206 0.854649 0.000000
    outer loop
      vertex 99.544624 202.089340 3.000000
      vertex 99.631203 202.141937 3.000000
      vertex 99.544624 202.089340 0.000000
    endloop
  endfacet
  facet normal -0.434045 0.900891 0.000000
    outer loop
      vertex 99.452843 202.045120 0.000000
      vertex 99.544624 202.089340 3.000000
      vertex 99.544624 202.089340 0.000000
    endloop
  endfacet
  facet normal -0.434045 0.900891 0.000000
    outer loop
      vertex 99.452843 202.045120 3.000000
      vertex 99.544624 202.089340 3.000000
      vertex 99.452843 202.045120 0.000000
    endloop
  endfacet
  facet normal -0.343722 0.939071 0.000000
    outer loop
      vertex 99.356377 202.009811 0.000000
      vertex 99.452843 202.045120 3.000000
      vertex 99.452843 202.045120 0.000000
    endloop
  endfacet
  facet normal -0.343722 0.939071 0.000000
    outer loop
      vertex 99.356377 202.009811 3.000000
      vertex 99.452843 202.045120 3.000000
      vertex 99.356377 202.009811 0.000000
    endloop
  endfacet
  facet normal -0.248923 0.968523 0.000000
    outer loop
      vertex 99.255745 201.983948 0.000000
      vertex 99.356377 202.009811 3.000000
      vertex 99.356377 202.009811 0.000000
    endloop
  endfacet
  facet normal -0.248923 0.968523 0.000000
    outer loop
      vertex 99.255745 201.983948 3.000000
      vertex 99.356377 202.009811 3.000000
      vertex 99.255745 201.983948 0.000000
    endloop
  endfacet
  facet normal -0.150905 0.988548 0.000000
    outer loop
      vertex 99.151489 201.968033 0.000000
      vertex 99.255745 201.983948 3.000000
      vertex 99.255745 201.983948 0.000000
    endloop
  endfacet
  facet normal -0.150905 0.988548 0.000000
    outer loop
      vertex 99.151489 201.968033 3.000000
      vertex 99.255745 201.983948 3.000000
      vertex 99.151489 201.968033 0.000000
    endloop
  endfacet
  facet normal -0.050394 0.998729 0.000000
    outer loop
      vertex 99.044136 201.962616 0.000000
      vertex 99.151489 201.968033 3.000000
      vertex 99.151489 201.968033 0.000000
    endloop
  endfacet
  facet normal -0.050394 0.998729 0.000000
    outer loop
      vertex 99.044136 201.962616 3.000000
      vertex 99.151489 201.968033 3.000000
      vertex 99.044136 201.962616 0.000000
    endloop
  endfacet
  facet normal 0.050391 0.998730 0.000000
    outer loop
      vertex 98.936775 201.968033 0.000000
      vertex 99.044136 201.962616 3.000000
      vertex 99.044136 201.962616 0.000000
    endloop
  endfacet
  facet normal 0.050391 0.998730 0.000000
    outer loop
      vertex 98.936775 201.968033 3.000000
      vertex 99.044136 201.962616 3.000000
      vertex 98.936775 201.968033 0.000000
    endloop
  endfacet
  facet normal 0.150915 0.988547 0.000000
    outer loop
      vertex 98.832527 201.983948 0.000000
      vertex 98.936775 201.968033 3.000000
      vertex 98.936775 201.968033 0.000000
    endloop
  endfacet
  facet normal 0.150915 0.988547 0.000000
    outer loop
      vertex 98.832527 201.983948 3.000000
      vertex 98.936775 201.968033 3.000000
      vertex 98.832527 201.983948 0.000000
    endloop
  endfacet
  facet normal 0.248923 0.968523 0.000000
    outer loop
      vertex 98.731895 202.009811 0.000000
      vertex 98.832527 201.983948 3.000000
      vertex 98.832527 201.983948 0.000000
    endloop
  endfacet
  facet normal 0.248923 0.968523 0.000000
    outer loop
      vertex 98.731895 202.009811 3.000000
      vertex 98.832527 201.983948 3.000000
      vertex 98.731895 202.009811 0.000000
    endloop
  endfacet
  facet normal 0.343722 0.939071 0.000000
    outer loop
      vertex 98.635429 202.045120 0.000000
      vertex 98.731895 202.009811 3.000000
      vertex 98.731895 202.009811 0.000000
    endloop
  endfacet
  facet normal 0.343722 0.939071 0.000000
    outer loop
      vertex 98.635429 202.045120 3.000000
      vertex 98.731895 202.009811 3.000000
      vertex 98.635429 202.045120 0.000000
    endloop
  endfacet
  facet normal 0.434016 0.900905 0.000000
    outer loop
      vertex 98.543640 202.089340 0.000000
      vertex 98.635429 202.045120 3.000000
      vertex 98.635429 202.045120 0.000000
    endloop
  endfacet
  facet normal 0.434016 0.900905 0.000000
    outer loop
      vertex 98.543640 202.089340 3.000000
      vertex 98.635429 202.045120 3.000000
      vertex 98.543640 202.089340 0.000000
    endloop
  endfacet
  facet normal 0.519240 0.854629 0.000000
    outer loop
      vertex 98.457069 202.141937 0.000000
      vertex 98.543640 202.089340 3.000000
      vertex 98.543640 202.089340 0.000000
    endloop
  endfacet
  facet normal 0.519240 0.854629 0.000000
    outer loop
      vertex 98.457069 202.141937 3.000000
      vertex 98.543640 202.089340 3.000000
      vertex 98.457069 202.141937 0.000000
    endloop
  endfacet
  facet normal 0.598826 0.800879 0.000000
    outer loop
      vertex 98.376236 202.202377 0.000000
      vertex 98.457069 202.141937 3.000000
      vertex 98.457069 202.141937 0.000000
    endloop
  endfacet
  facet normal 0.598826 0.800879 0.000000
    outer loop
      vertex 98.376236 202.202377 3.000000
      vertex 98.457069 202.141937 3.000000
      vertex 98.376236 202.202377 0.000000
    endloop
  endfacet
  facet normal 0.672650 0.739961 0.000000
    outer loop
      vertex 98.301674 202.270157 0.000000
      vertex 98.376236 202.202377 3.000000
      vertex 98.376236 202.202377 0.000000
    endloop
  endfacet
  facet normal 0.672650 0.739961 0.000000
    outer loop
      vertex 98.301674 202.270157 3.000000
      vertex 98.376236 202.202377 3.000000
      vertex 98.301674 202.270157 0.000000
    endloop
  endfacet
  facet normal 0.739964 0.672646 0.000000
    outer loop
      vertex 98.233902 202.344711 0.000000
      vertex 98.301674 202.270157 3.000000
      vertex 98.301674 202.270157 0.000000
    endloop
  endfacet
  facet normal 0.739964 0.672646 0.000000
    outer loop
      vertex 98.233902 202.344711 3.000000
      vertex 98.301674 202.270157 3.000000
      vertex 98.233902 202.344711 0.000000
    endloop
  endfacet
  facet normal 0.800906 0.598790 0.000000
    outer loop
      vertex 98.173462 202.425552 0.000000
      vertex 98.233902 202.344711 3.000000
      vertex 98.233902 202.344711 0.000000
    endloop
  endfacet
  facet normal 0.800906 0.598790 0.000000
    outer loop
      vertex 98.173462 202.425552 3.000000
      vertex 98.233902 202.344711 3.000000
      vertex 98.173462 202.425552 0.000000
    endloop
  endfacet
  facet normal 0.854608 0.519273 0.000000
    outer loop
      vertex 98.120865 202.512115 0.000000
      vertex 98.173462 202.425552 3.000000
      vertex 98.173462 202.425552 0.000000
    endloop
  endfacet
  facet normal 0.854608 0.519273 0.000000
    outer loop
      vertex 98.120865 202.512115 3.000000
      vertex 98.173462 202.425552 3.000000
      vertex 98.120865 202.512115 0.000000
    endloop
  endfacet
  facet normal 0.900920 0.433984 0.000000
    outer loop
      vertex 98.076653 202.603897 0.000000
      vertex 98.120865 202.512115 3.000000
      vertex 98.120865 202.512115 0.000000
    endloop
  endfacet
  facet normal 0.900920 0.433984 0.000000
    outer loop
      vertex 98.076653 202.603897 3.000000
      vertex 98.120865 202.512115 3.000000
      vertex 98.076653 202.603897 0.000000
    endloop
  endfacet
  facet normal 0.939089 0.343674 0.000000
    outer loop
      vertex 98.041344 202.700378 0.000000
      vertex 98.076653 202.603897 3.000000
      vertex 98.076653 202.603897 0.000000
    endloop
  endfacet
  facet normal 0.939089 0.343674 0.000000
    outer loop
      vertex 98.041344 202.700378 3.000000
      vertex 98.076653 202.603897 3.000000
      vertex 98.041344 202.700378 0.000000
    endloop
  endfacet
  facet normal 0.968479 0.249096 0.000000
    outer loop
      vertex 98.015465 202.800995 0.000000
      vertex 98.041344 202.700378 3.000000
      vertex 98.041344 202.700378 0.000000
    endloop
  endfacet
  facet normal 0.968479 0.249096 0.000000
    outer loop
      vertex 98.015465 202.800995 3.000000
      vertex 98.041344 202.700378 3.000000
      vertex 98.015465 202.800995 0.000000
    endloop
  endfacet
  facet normal 0.988561 0.150823 0.000000
    outer loop
      vertex 97.999557 202.905258 0.000000
      vertex 98.015465 202.800995 3.000000
      vertex 98.015465 202.800995 0.000000
    endloop
  endfacet
  facet normal 0.988561 0.150823 0.000000
    outer loop
      vertex 97.999557 202.905258 3.000000
      vertex 98.015465 202.800995 3.000000
      vertex 97.999557 202.905258 0.000000
    endloop
  endfacet
  facet normal 0.998726 0.050461 0.000000
    outer loop
      vertex 97.994133 203.012619 0.000000
      vertex 97.999557 202.905258 3.000000
      vertex 97.999557 202.905258 0.000000
    endloop
  endfacet
  facet normal 0.998726 0.050461 0.000000
    outer loop
      vertex 97.994133 203.012619 3.000000
      vertex 97.999557 202.905258 3.000000
      vertex 97.994133 203.012619 0.000000
    endloop
  endfacet
  facet normal 0.998726 -0.050469 0.000000
    outer loop
      vertex 97.999557 203.119965 0.000000
      vertex 97.994133 203.012619 3.000000
      vertex 97.994133 203.012619 0.000000
    endloop
  endfacet
  facet normal 0.998726 -0.050469 0.000000
    outer loop
      vertex 97.999557 203.119965 3.000000
      vertex 97.994133 203.012619 3.000000
      vertex 97.999557 203.119965 0.000000
    endloop
  endfacet
  facet normal 0.988561 -0.150823 0.000000
    outer loop
      vertex 98.015465 203.224228 0.000000
      vertex 97.999557 203.119965 3.000000
      vertex 97.999557 203.119965 0.000000
    endloop
  endfacet
  facet normal 0.988561 -0.150823 0.000000
    outer loop
      vertex 98.015465 203.224228 3.000000
      vertex 97.999557 203.119965 3.000000
      vertex 98.015465 203.224228 0.000000
    endloop
  endfacet
  facet normal 0.968479 -0.249096 0.000000
    outer loop
      vertex 98.041344 203.324844 0.000000
      vertex 98.015465 203.224228 3.000000
      vertex 98.015465 203.224228 0.000000
    endloop
  endfacet
  facet normal 0.968479 -0.249096 0.000000
    outer loop
      vertex 98.041344 203.324844 3.000000
      vertex 98.015465 203.224228 3.000000
      vertex 98.041344 203.324844 0.000000
    endloop
  endfacet
  facet normal 0.939089 -0.343674 0.000000
    outer loop
      vertex 98.076653 203.421326 0.000000
      vertex 98.041344 203.324844 3.000000
      vertex 98.041344 203.324844 0.000000
    endloop
  endfacet
  facet normal 0.939089 -0.343674 0.000000
    outer loop
      vertex 98.076653 203.421326 3.000000
      vertex 98.041344 203.324844 3.000000
      vertex 98.076653 203.421326 0.000000
    endloop
  endfacet
  facet normal 0.900920 -0.433984 0.000000
    outer loop
      vertex 98.120865 203.513107 0.000000
      vertex 98.076653 203.421326 3.000000
      vertex 98.076653 203.421326 0.000000
    endloop
  endfacet
  facet normal 0.900920 -0.433984 0.000000
    outer loop
      vertex 98.120865 203.513107 3.000000
      vertex 98.076653 203.421326 3.000000
      vertex 98.120865 203.513107 0.000000
    endloop
  endfacet
  facet normal 0.854608 -0.519273 0.000000
    outer loop
      vertex 98.173462 203.599670 0.000000
      vertex 98.120865 203.513107 3.000000
      vertex 98.120865 203.513107 0.000000
    endloop
  endfacet
  facet normal 0.854608 -0.519273 0.000000
    outer loop
      vertex 98.173462 203.599670 3.000000
      vertex 98.120865 203.513107 3.000000
      vertex 98.173462 203.599670 0.000000
    endloop
  endfacet
  facet normal 0.800906 -0.598790 0.000000
    outer loop
      vertex 98.233902 203.680511 0.000000
      vertex 98.173462 203.599670 3.000000
      vertex 98.173462 203.599670 0.000000
    endloop
  endfacet
  facet normal 0.800906 -0.598790 0.000000
    outer loop
      vertex 98.233902 203.680511 3.000000
      vertex 98.173462 203.599670 3.000000
      vertex 98.233902 203.680511 0.000000
    endloop
  endfacet
  facet normal 0.740033 -0.672571 0.000000
    outer loop
      vertex 98.301674 203.755081 0.000000
      vertex 98.233902 203.680511 3.000000
      vertex 98.233902 203.680511 0.000000
    endloop
  endfacet
  facet normal 0.740033 -0.672571 0.000000
    outer loop
      vertex 98.301674 203.755081 3.000000
      vertex 98.233902 203.680511 3.000000
      vertex 98.301674 203.755081 0.000000
    endloop
  endfacet
  facet normal 0.672567 -0.740036 0.000000
    outer loop
      vertex 98.376236 203.822845 0.000000
      vertex 98.301674 203.755081 3.000000
      vertex 98.301674 203.755081 0.000000
    endloop
  endfacet
  facet normal 0.672567 -0.740036 0.000000
    outer loop
      vertex 98.376236 203.822845 3.000000
      vertex 98.301674 203.755081 3.000000
      vertex 98.376236 203.822845 0.000000
    endloop
  endfacet
  facet normal 0.598826 -0.800879 0.000000
    outer loop
      vertex 98.457069 203.883286 0.000000
      vertex 98.376236 203.822845 3.000000
      vertex 98.376236 203.822845 0.000000
    endloop
  endfacet
  facet normal 0.598826 -0.800879 0.000000
    outer loop
      vertex 98.457069 203.883286 3.000000
      vertex 98.376236 203.822845 3.000000
      vertex 98.457069 203.883286 0.000000
    endloop
  endfacet
  facet normal 0.519240 -0.854629 0.000000
    outer loop
      vertex 98.543640 203.935883 0.000000
      vertex 98.457069 203.883286 3.000000
      vertex 98.457069 203.883286 0.000000
    endloop
  endfacet
  facet normal 0.519240 -0.854629 0.000000
    outer loop
      vertex 98.543640 203.935883 3.000000
      vertex 98.457069 203.883286 3.000000
      vertex 98.543640 203.935883 0.000000
    endloop
  endfacet
  facet normal 0.434016 -0.900905 0.000000
    outer loop
      vertex 98.635429 203.980103 0.000000
      vertex 98.543640 203.935883 3.000000
      vertex 98.543640 203.935883 0.000000
    endloop
  endfacet
  facet normal 0.434016 -0.900905 0.000000
    outer loop
      vertex 98.635429 203.980103 3.000000
      vertex 98.543640 203.935883 3.000000
      vertex 98.635429 203.980103 0.000000
    endloop
  endfacet
  facet normal 0.343722 -0.939071 0.000000
    outer loop
      vertex 98.731895 204.015411 0.000000
      vertex 98.635429 203.980103 3.000000
      vertex 98.635429 203.980103 0.000000
    endloop
  endfacet
  facet normal 0.343722 -0.939071 0.000000
    outer loop
      vertex 98.731895 204.015411 3.000000
      vertex 98.635429 203.980103 3.000000
      vertex 98.731895 204.015411 0.000000
    endloop
  endfacet
  facet normal 0.248923 -0.968523 0.000000
    outer loop
      vertex 98.832527 204.041275 0.000000
      vertex 98.731895 204.015411 3.000000
      vertex 98.731895 204.015411 0.000000
    endloop
  endfacet
  facet normal 0.248923 -0.968523 0.000000
    outer loop
      vertex 98.832527 204.041275 3.000000
      vertex 98.731895 204.015411 3.000000
      vertex 98.832527 204.041275 0.000000
    endloop
  endfacet
  facet normal 0.150915 -0.988547 0.000000
    outer loop
      vertex 98.936775 204.057190 0.000000
      vertex 98.832527 204.041275 3.000000
      vertex 98.832527 204.041275 0.000000
    endloop
  endfacet
  facet normal 0.150915 -0.988547 0.000000
    outer loop
      vertex 98.936775 204.057190 3.000000
      vertex 98.832527 204.041275 3.000000
      vertex 98.936775 204.057190 0.000000
    endloop
  endfacet
  facet normal 0.050391 -0.998730 0.000000
    outer loop
      vertex 99.044136 204.062607 0.000000
      vertex 98.936775 204.057190 3.000000
      vertex 98.936775 204.057190 0.000000
    endloop
  endfacet
  facet normal 0.050391 -0.998730 0.000000
    outer loop
      vertex 99.044136 204.062607 3.000000
      vertex 98.936775 204.057190 3.000000
      vertex 99.044136 204.062607 0.000000
    endloop
  endfacet
  facet normal -0.050394 -0.998729 0.000000
    outer loop
      vertex 99.151489 204.057190 0.000000
      vertex 99.044136 204.062607 3.000000
      vertex 99.044136 204.062607 0.000000
    endloop
  endfacet
  facet normal -0.050394 -0.998729 -0.000000
    outer loop
      vertex 99.151489 204.057190 3.000000
      vertex 99.044136 204.062607 3.000000
      vertex 99.151489 204.057190 0.000000
    endloop
  endfacet
  facet normal -0.150905 -0.988548 0.000000
    outer loop
      vertex 99.255745 204.041275 0.000000
      vertex 99.151489 204.057190 3.000000
      vertex 99.151489 204.057190 0.000000
    endloop
  endfacet
  facet normal -0.150905 -0.988548 -0.000000
    outer loop
      vertex 99.255745 204.041275 3.000000
      vertex 99.151489 204.057190 3.000000
      vertex 99.255745 204.041275 0.000000
    endloop
  endfacet
  facet normal -0.248923 -0.968523 0.000000
    outer loop
      vertex 99.356377 204.015411 0.000000
      vertex 99.255745 204.041275 3.000000
      vertex 99.255745 204.041275 0.000000
    endloop
  endfacet
  facet normal -0.248923 -0.968523 -0.000000
    outer loop
      vertex 99.356377 204.015411 3.000000
      vertex 99.255745 204.041275 3.000000
      vertex 99.356377 204.015411 0.000000
    endloop
  endfacet
  facet normal -0.343722 -0.939071 0.000000
    outer loop
      vertex 99.452843 203.980103 0.000000
      vertex 99.356377 204.015411 3.000000
      vertex 99.356377 204.015411 0.000000
    endloop
  endfacet
  facet normal -0.343722 -0.939071 -0.000000
    outer loop
      vertex 99.452843 203.980103 3.000000
      vertex 99.356377 204.015411 3.000000
      vertex 99.452843 203.980103 0.000000
    endloop
  endfacet
  facet normal -0.434045 -0.900891 0.000000
    outer loop
      vertex 99.544624 203.935883 0.000000
      vertex 99.452843 203.980103 3.000000
      vertex 99.452843 203.980103 0.000000
    endloop
  endfacet
  facet normal -0.434045 -0.900891 -0.000000
    outer loop
      vertex 99.544624 203.935883 3.000000
      vertex 99.452843 203.980103 3.000000
      vertex 99.544624 203.935883 0.000000
    endloop
  endfacet
  facet normal -0.519206 -0.854649 0.000000
    outer loop
      vertex 99.631203 203.883286 0.000000
      vertex 99.544624 203.935883 3.000000
      vertex 99.544624 203.935883 0.000000
    endloop
  endfacet
  facet normal -0.519206 -0.854649 -0.000000
    outer loop
      vertex 99.631203 203.883286 3.000000
      vertex 99.544624 203.935883 3.000000
      vertex 99.631203 203.883286 0.000000
    endloop
  endfacet
  facet normal -0.598826 -0.800879 0.000000
    outer loop
      vertex 99.712036 203.822845 0.000000
      vertex 99.631203 203.883286 3.000000
      vertex 99.631203 203.883286 0.000000
    endloop
  endfacet
  facet normal -0.598826 -0.800879 -0.000000
    outer loop
      vertex 99.712036 203.822845 3.000000
      vertex 99.631203 203.883286 3.000000
      vertex 99.712036 203.822845 0.000000
    endloop
  endfacet
  facet normal -0.672567 -0.740036 0.000000
    outer loop
      vertex 99.786598 203.755081 0.000000
      vertex 99.712036 203.822845 3.000000
      vertex 99.712036 203.822845 0.000000
    endloop
  endfacet
  facet normal -0.672567 -0.740036 -0.000000
    outer loop
      vertex 99.786598 203.755081 3.000000
      vertex 99.712036 203.822845 3.000000
      vertex 99.786598 203.755081 0.000000
    endloop
  endfacet
  facet normal -0.740070 -0.672530 0.000000
    outer loop
      vertex 99.854362 203.680511 0.000000
      vertex 99.786598 203.755081 3.000000
      vertex 99.786598 203.755081 0.000000
    endloop
  endfacet
  facet normal -0.740070 -0.672530 -0.000000
    outer loop
      vertex 99.854362 203.680511 3.000000
      vertex 99.786598 203.755081 3.000000
      vertex 99.854362 203.680511 0.000000
    endloop
  endfacet
  facet normal -0.800870 -0.598838 0.000000
    outer loop
      vertex 99.914810 203.599670 0.000000
      vertex 99.854362 203.680511 3.000000
      vertex 99.854362 203.680511 0.000000
    endloop
  endfacet
  facet normal -0.800870 -0.598838 -0.000000
    outer loop
      vertex 99.914810 203.599670 3.000000
      vertex 99.854362 203.680511 3.000000
      vertex 99.914810 203.599670 0.000000
    endloop
  endfacet
  facet normal -0.854608 -0.519273 0.000000
    outer loop
      vertex 99.967407 203.513107 0.000000
      vertex 99.914810 203.599670 3.000000
      vertex 99.914810 203.599670 0.000000
    endloop
  endfacet
  facet normal -0.854608 -0.519273 -0.000000
    outer loop
      vertex 99.967407 203.513107 3.000000
      vertex 99.914810 203.599670 3.000000
      vertex 99.967407 203.513107 0.000000
    endloop
  endfacet
  facet normal -0.900920 -0.433984 0.000000
    outer loop
      vertex 100.011620 203.421326 0.000000
      vertex 99.967407 203.513107 3.000000
      vertex 99.967407 203.513107 0.000000
    endloop
  endfacet
  facet normal -0.900920 -0.433984 -0.000000
    outer loop
      vertex 100.011620 203.421326 3.000000
      vertex 99.967407 203.513107 3.000000
      vertex 100.011620 203.421326 0.000000
    endloop
  endfacet
  facet normal -0.939089 -0.343674 0.000000
    outer loop
      vertex 100.046928 203.324844 0.000000
      vertex 100.011620 203.421326 3.000000
      vertex 100.011620 203.421326 0.000000
    endloop
  endfacet
  facet normal -0.939089 -0.343674 -0.000000
    outer loop
      vertex 100.046928 203.324844 3.000000
      vertex 100.011620 203.421326 3.000000
      vertex 100.046928 203.324844 0.000000
    endloop
  endfacet
  facet normal -0.968496 -0.249027 0.000000
    outer loop
      vertex 100.072800 203.224228 0.000000
      vertex 100.046928 203.324844 3.000000
      vertex 100.046928 203.324844 0.000000
    endloop
  endfacet
  facet normal -0.968496 -0.249027 -0.000000
    outer loop
      vertex 100.072800 203.224228 3.000000
      vertex 100.046928 203.324844 3.000000
      vertex 100.072800 203.224228 0.000000
    endloop
  endfacet
  facet normal -0.988550 -0.150894 0.000000
    outer loop
      vertex 100.088715 203.119965 0.000000
      vertex 100.072800 203.224228 3.000000
      vertex 100.072800 203.224228 0.000000
    endloop
  endfacet
  facet normal -0.988550 -0.150894 -0.000000
    outer loop
      vertex 100.088715 203.119965 3.000000
      vertex 100.072800 203.224228 3.000000
      vertex 100.088715 203.119965 0.000000
    endloop
  endfacet
  facet normal -0.998729 -0.050398 0.000000
    outer loop
      vertex 100.094131 203.012619 0.000000
      vertex 100.088715 203.119965 3.000000
      vertex 100.088715 203.119965 0.000000
    endloop
  endfacet
  facet normal -0.998729 -0.050398 -0.000000
    outer loop
      vertex 100.094131 203.012619 3.000000
      vertex 100.088715 203.119965 3.000000
      vertex 100.094131 203.012619 0.000000
    endloop
  endfacet
  facet normal -0.998729 0.050398 0.000000
    outer loop
      vertex 153.693665 148.355209 3.000000
      vertex 153.693665 148.355209 0.000000
      vertex 153.688248 148.247864 0.000000
    endloop
  endfacet
  facet normal -0.998729 0.050398 0.000000
    outer loop
      vertex 153.688248 148.247864 3.000000
      vertex 153.693665 148.355209 3.000000
      vertex 153.688248 148.247864 0.000000
    endloop
  endfacet
  facet normal -0.988550 0.150894 0.000000
    outer loop
      vertex 153.672333 148.143600 0.000000
      vertex 153.688248 148.247864 3.000000
      vertex 153.688248 148.247864 0.000000
    endloop
  endfacet
  facet normal -0.988550 0.150894 0.000000
    outer loop
      vertex 153.672333 148.143600 3.000000
      vertex 153.688248 148.247864 3.000000
      vertex 153.672333 148.143600 0.000000
    endloop
  endfacet
  facet normal -0.968523 0.248923 0.000000
    outer loop
      vertex 153.646469 148.042969 0.000000
      vertex 153.672333 148.143600 3.000000
      vertex 153.672333 148.143600 0.000000
    endloop
  endfacet
  facet normal -0.968523 0.248923 0.000000
    outer loop
      vertex 153.646469 148.042969 3.000000
      vertex 153.672333 148.143600 3.000000
      vertex 153.646469 148.042969 0.000000
    endloop
  endfacet
  facet normal -0.939071 0.343722 0.000000
    outer loop
      vertex 153.611160 147.946503 0.000000
      vertex 153.646469 148.042969 3.000000
      vertex 153.646469 148.042969 0.000000
    endloop
  endfacet
  facet normal -0.939071 0.343722 0.000000
    outer loop
      vertex 153.611160 147.946503 3.000000
      vertex 153.646469 148.042969 3.000000
      vertex 153.611160 147.946503 0.000000
    endloop
  endfacet
  facet normal -0.900891 0.434045 0.000000
    outer loop
      vertex 153.566940 147.854721 0.000000
      vertex 153.611160 147.946503 3.000000
      vertex 153.611160 147.946503 0.000000
    endloop
  endfacet
  facet normal -0.900891 0.434045 0.000000
    outer loop
      vertex 153.566940 147.854721 3.000000
      vertex 153.611160 147.946503 3.000000
      vertex 153.566940 147.854721 0.000000
    endloop
  endfacet
  facet normal -0.854649 0.519206 0.000000
    outer loop
      vertex 153.514343 147.768143 0.000000
      vertex 153.566940 147.854721 3.000000
      vertex 153.566940 147.854721 0.000000
    endloop
  endfacet
  facet normal -0.854649 0.519206 0.000000
    outer loop
      vertex 153.514343 147.768143 3.000000
      vertex 153.566940 147.854721 3.000000
      vertex 153.514343 147.768143 0.000000
    endloop
  endfacet
  facet normal -0.800852 0.598862 0.000000
    outer loop
      vertex 153.453903 147.687317 0.000000
      vertex 153.514343 147.768143 3.000000
      vertex 153.514343 147.768143 0.000000
    endloop
  endfacet
  facet normal -0.800852 0.598862 0.000000
    outer loop
      vertex 153.453903 147.687317 3.000000
      vertex 153.514343 147.768143 3.000000
      vertex 153.453903 147.687317 0.000000
    endloop
  endfacet
  facet normal -0.739995 0.672612 0.000000
    outer loop
      vertex 153.386124 147.612747 0.000000
      vertex 153.453903 147.687317 3.000000
      vertex 153.453903 147.687317 0.000000
    endloop
  endfacet
  facet normal -0.739995 0.672612 0.000000
    outer loop
      vertex 153.386124 147.612747 3.000000
      vertex 153.453903 147.687317 3.000000
      vertex 153.386124 147.612747 0.000000
    endloop
  endfacet
  facet normal -0.672605 0.740002 0.000000
    outer loop
      vertex 153.311569 147.544983 0.000000
      vertex 153.386124 147.612747 3.000000
      vertex 153.386124 147.612747 0.000000
    endloop
  endfacet
  facet normal -0.672605 0.740002 0.000000
    outer loop
      vertex 153.311569 147.544983 3.000000
      vertex 153.386124 147.612747 3.000000
      vertex 153.311569 147.544983 0.000000
    endloop
  endfacet
  facet normal -0.598790 0.800906 0.000000
    outer loop
      vertex 153.230728 147.484543 0.000000
      vertex 153.311569 147.544983 3.000000
      vertex 153.311569 147.544983 0.000000
    endloop
  endfacet
  facet normal -0.598790 0.800906 0.000000
    outer loop
      vertex 153.230728 147.484543 3.000000
      vertex 153.311569 147.544983 3.000000
      vertex 153.230728 147.484543 0.000000
    endloop
  endfacet
  facet normal -0.519273 0.854608 0.000000
    outer loop
      vertex 153.144165 147.431946 0.000000
      vertex 153.230728 147.484543 3.000000
      vertex 153.230728 147.484543 0.000000
    endloop
  endfacet
  facet normal -0.519273 0.854608 0.000000
    outer loop
      vertex 153.144165 147.431946 3.000000
      vertex 153.230728 147.484543 3.000000
      vertex 153.144165 147.431946 0.000000
    endloop
  endfacet
  facet normal -0.434045 0.900891 0.000000
    outer loop
      vertex 153.052383 147.387726 0.000000
      vertex 153.144165 147.431946 3.000000
      vertex 153.144165 147.431946 0.000000
    endloop
  endfacet
  facet normal -0.434045 0.900891 0.000000
    outer loop
      vertex 153.052383 147.387726 3.000000
      vertex 153.144165 147.431946 3.000000
      vertex 153.052383 147.387726 0.000000
    endloop
  endfacet
  facet normal -0.343674 0.939089 0.000000
    outer loop
      vertex 152.955902 147.352417 0.000000
      vertex 153.052383 147.387726 3.000000
      vertex 153.052383 147.387726 0.000000
    endloop
  endfacet
  facet normal -0.343674 0.939089 0.000000
    outer loop
      vertex 152.955902 147.352417 3.000000
      vertex 153.052383 147.387726 3.000000
      vertex 152.955902 147.352417 0.000000
    endloop
  endfacet
  facet normal -0.248958 0.968514 0.000000
    outer loop
      vertex 152.855286 147.326553 0.000000
      vertex 152.955902 147.352417 3.000000
      vertex 152.955902 147.352417 0.000000
    endloop
  endfacet
  facet normal -0.248958 0.968514 0.000000
    outer loop
      vertex 152.855286 147.326553 3.000000
      vertex 152.955902 147.352417 3.000000
      vertex 152.855286 147.326553 0.000000
    endloop
  endfacet
  facet normal -0.150894 0.988550 0.000000
    outer loop
      vertex 152.751022 147.310638 0.000000
      vertex 152.855286 147.326553 3.000000
      vertex 152.855286 147.326553 0.000000
    endloop
  endfacet
  facet normal -0.150894 0.988550 0.000000
    outer loop
      vertex 152.751022 147.310638 3.000000
      vertex 152.855286 147.326553 3.000000
      vertex 152.751022 147.310638 0.000000
    endloop
  endfacet
  facet normal -0.050532 0.998722 0.000000
    outer loop
      vertex 152.643661 147.305206 0.000000
      vertex 152.751022 147.310638 3.000000
      vertex 152.751022 147.310638 0.000000
    endloop
  endfacet
  facet normal -0.050532 0.998722 0.000000
    outer loop
      vertex 152.643661 147.305206 3.000000
      vertex 152.751022 147.310638 3.000000
      vertex 152.643661 147.305206 0.000000
    endloop
  endfacet
  facet normal 0.050539 0.998722 0.000000
    outer loop
      vertex 152.536316 147.310638 0.000000
      vertex 152.643661 147.305206 3.000000
      vertex 152.643661 147.305206 0.000000
    endloop
  endfacet
  facet normal 0.050539 0.998722 0.000000
    outer loop
      vertex 152.536316 147.310638 3.000000
      vertex 152.643661 147.305206 3.000000
      vertex 152.536316 147.310638 0.000000
    endloop
  endfacet
  facet normal 0.150894 0.988550 0.000000
    outer loop
      vertex 152.432053 147.326553 0.000000
      vertex 152.536316 147.310638 3.000000
      vertex 152.536316 147.310638 0.000000
    endloop
  endfacet
  facet normal 0.150894 0.988550 0.000000
    outer loop
      vertex 152.432053 147.326553 3.000000
      vertex 152.536316 147.310638 3.000000
      vertex 152.432053 147.326553 0.000000
    endloop
  endfacet
  facet normal 0.248958 0.968514 0.000000
    outer loop
      vertex 152.331436 147.352417 0.000000
      vertex 152.432053 147.326553 3.000000
      vertex 152.432053 147.326553 0.000000
    endloop
  endfacet
  facet normal 0.248958 0.968514 0.000000
    outer loop
      vertex 152.331436 147.352417 3.000000
      vertex 152.432053 147.326553 3.000000
      vertex 152.331436 147.352417 0.000000
    endloop
  endfacet
  facet normal 0.343674 0.939089 0.000000
    outer loop
      vertex 152.234955 147.387726 0.000000
      vertex 152.331436 147.352417 3.000000
      vertex 152.331436 147.352417 0.000000
    endloop
  endfacet
  facet normal 0.343674 0.939089 0.000000
    outer loop
      vertex 152.234955 147.387726 3.000000
      vertex 152.331436 147.352417 3.000000
      vertex 152.234955 147.387726 0.000000
    endloop
  endfacet
  facet normal 0.434045 0.900891 0.000000
    outer loop
      vertex 152.143173 147.431946 0.000000
      vertex 152.234955 147.387726 3.000000
      vertex 152.234955 147.387726 0.000000
    endloop
  endfacet
  facet normal 0.434045 0.900891 0.000000
    outer loop
      vertex 152.143173 147.431946 3.000000
      vertex 152.234955 147.387726 3.000000
      vertex 152.143173 147.431946 0.000000
    endloop
  endfacet
  facet normal 0.519273 0.854608 0.000000
    outer loop
      vertex 152.056610 147.484543 0.000000
      vertex 152.143173 147.431946 3.000000
      vertex 152.143173 147.431946 0.000000
    endloop
  endfacet
  facet normal 0.519273 0.854608 0.000000
    outer loop
      vertex 152.056610 147.484543 3.000000
      vertex 152.143173 147.431946 3.000000
      vertex 152.056610 147.484543 0.000000
    endloop
  endfacet
  facet normal 0.598790 0.800906 0.000000
    outer loop
      vertex 151.975769 147.544983 0.000000
      vertex 152.056610 147.484543 3.000000
      vertex 152.056610 147.484543 0.000000
    endloop
  endfacet
  facet normal 0.598790 0.800906 0.000000
    outer loop
      vertex 151.975769 147.544983 3.000000
      vertex 152.056610 147.484543 3.000000
      vertex 151.975769 147.544983 0.000000
    endloop
  endfacet
  facet normal 0.672530 0.740070 0.000000
    outer loop
      vertex 151.901199 147.612747 0.000000
      vertex 151.975769 147.544983 3.000000
      vertex 151.975769 147.544983 0.000000
    endloop
  endfacet
  facet normal 0.672530 0.740070 0.000000
    outer loop
      vertex 151.901199 147.612747 3.000000
      vertex 151.975769 147.544983 3.000000
      vertex 151.901199 147.612747 0.000000
    endloop
  endfacet
  facet normal 0.740070 0.672530 0.000000
    outer loop
      vertex 151.833435 147.687317 0.000000
      vertex 151.901199 147.612747 3.000000
      vertex 151.901199 147.612747 0.000000
    endloop
  endfacet
  facet normal 0.740070 0.672530 0.000000
    outer loop
      vertex 151.833435 147.687317 3.000000
      vertex 151.901199 147.612747 3.000000
      vertex 151.833435 147.687317 0.000000
    endloop
  endfacet
  facet normal 0.800852 0.598862 0.000000
    outer loop
      vertex 151.772995 147.768143 0.000000
      vertex 151.833435 147.687317 3.000000
      vertex 151.833435 147.687317 0.000000
    endloop
  endfacet
  facet normal 0.800852 0.598862 0.000000
    outer loop
      vertex 151.772995 147.768143 3.000000
      vertex 151.833435 147.687317 3.000000
      vertex 151.772995 147.768143 0.000000
    endloop
  endfacet
  facet normal 0.854649 0.519206 0.000000
    outer loop
      vertex 151.720398 147.854721 0.000000
      vertex 151.772995 147.768143 3.000000
      vertex 151.772995 147.768143 0.000000
    endloop
  endfacet
  facet normal 0.854649 0.519206 0.000000
    outer loop
      vertex 151.720398 147.854721 3.000000
      vertex 151.772995 147.768143 3.000000
      vertex 151.720398 147.854721 0.000000
    endloop
  endfacet
  facet normal 0.900891 0.434045 0.000000
    outer loop
      vertex 151.676178 147.946503 0.000000
      vertex 151.720398 147.854721 3.000000
      vertex 151.720398 147.854721 0.000000
    endloop
  endfacet
  facet normal 0.900891 0.434045 0.000000
    outer loop
      vertex 151.676178 147.946503 3.000000
      vertex 151.720398 147.854721 3.000000
      vertex 151.676178 147.946503 0.000000
    endloop
  endfacet
  facet normal 0.939071 0.343722 0.000000
    outer loop
      vertex 151.640869 148.042969 0.000000
      vertex 151.676178 147.946503 3.000000
      vertex 151.676178 147.946503 0.000000
    endloop
  endfacet
  facet normal 0.939071 0.343722 0.000000
    outer loop
      vertex 151.640869 148.042969 3.000000
      vertex 151.676178 147.946503 3.000000
      vertex 151.640869 148.042969 0.000000
    endloop
  endfacet
  facet normal 0.968523 0.248923 0.000000
    outer loop
      vertex 151.615005 148.143600 0.000000
      vertex 151.640869 148.042969 3.000000
      vertex 151.640869 148.042969 0.000000
    endloop
  endfacet
  facet normal 0.968523 0.248923 0.000000
    outer loop
      vertex 151.615005 148.143600 3.000000
      vertex 151.640869 148.042969 3.000000
      vertex 151.615005 148.143600 0.000000
    endloop
  endfacet
  facet normal 0.988550 0.150894 0.000000
    outer loop
      vertex 151.599091 148.247864 0.000000
      vertex 151.615005 148.143600 3.000000
      vertex 151.615005 148.143600 0.000000
    endloop
  endfacet
  facet normal 0.988550 0.150894 0.000000
    outer loop
      vertex 151.599091 148.247864 3.000000
      vertex 151.615005 148.143600 3.000000
      vertex 151.599091 148.247864 0.000000
    endloop
  endfacet
  facet normal 0.998729 0.050398 0.000000
    outer loop
      vertex 151.593674 148.355209 0.000000
      vertex 151.599091 148.247864 3.000000
      vertex 151.599091 148.247864 0.000000
    endloop
  endfacet
  facet normal 0.998729 0.050398 0.000000
    outer loop
      vertex 151.593674 148.355209 3.000000
      vertex 151.599091 148.247864 3.000000
      vertex 151.593674 148.355209 0.000000
    endloop
  endfacet
  facet normal 0.998730 -0.050391 0.000000
    outer loop
      vertex 151.599091 148.462570 0.000000
      vertex 151.593674 148.355209 3.000000
      vertex 151.593674 148.355209 0.000000
    endloop
  endfacet
  facet normal 0.998730 -0.050391 0.000000
    outer loop
      vertex 151.599091 148.462570 3.000000
      vertex 151.593674 148.355209 3.000000
      vertex 151.599091 148.462570 0.000000
    endloop
  endfacet
  facet normal 0.988547 -0.150915 0.000000
    outer loop
      vertex 151.615005 148.566818 0.000000
      vertex 151.599091 148.462570 3.000000
      vertex 151.599091 148.462570 0.000000
    endloop
  endfacet
  facet normal 0.988547 -0.150915 0.000000
    outer loop
      vertex 151.615005 148.566818 3.000000
      vertex 151.599091 148.462570 3.000000
      vertex 151.615005 148.566818 0.000000
    endloop
  endfacet
  facet normal 0.968523 -0.248923 0.000000
    outer loop
      vertex 151.640869 148.667450 0.000000
      vertex 151.615005 148.566818 3.000000
      vertex 151.615005 148.566818 0.000000
    endloop
  endfacet
  facet normal 0.968523 -0.248923 0.000000
    outer loop
      vertex 151.640869 148.667450 3.000000
      vertex 151.615005 148.566818 3.000000
      vertex 151.640869 148.667450 0.000000
    endloop
  endfacet
  facet normal 0.939071 -0.343722 0.000000
    outer loop
      vertex 151.676178 148.763916 0.000000
      vertex 151.640869 148.667450 3.000000
      vertex 151.640869 148.667450 0.000000
    endloop
  endfacet
  facet normal 0.939071 -0.343722 0.000000
    outer loop
      vertex 151.676178 148.763916 3.000000
      vertex 151.640869 148.667450 3.000000
      vertex 151.676178 148.763916 0.000000
    endloop
  endfacet
  facet normal 0.900919 -0.433987 0.000000
    outer loop
      vertex 151.720398 148.855713 0.000000
      vertex 151.676178 148.763916 3.000000
      vertex 151.676178 148.763916 0.000000
    endloop
  endfacet
  facet normal 0.900919 -0.433987 0.000000
    outer loop
      vertex 151.720398 148.855713 3.000000
      vertex 151.676178 148.763916 3.000000
      vertex 151.720398 148.855713 0.000000
    endloop
  endfacet
  facet normal 0.854608 -0.519273 0.000000
    outer loop
      vertex 151.772995 148.942276 0.000000
      vertex 151.720398 148.855713 3.000000
      vertex 151.720398 148.855713 0.000000
    endloop
  endfacet
  facet normal 0.854608 -0.519273 0.000000
    outer loop
      vertex 151.772995 148.942276 3.000000
      vertex 151.720398 148.855713 3.000000
      vertex 151.772995 148.942276 0.000000
    endloop
  endfacet
  facet normal 0.800906 -0.598790 0.000000
    outer loop
      vertex 151.833435 149.023117 0.000000
      vertex 151.772995 148.942276 3.000000
      vertex 151.772995 148.942276 0.000000
    endloop
  endfacet
  facet normal 0.800906 -0.598790 0.000000
    outer loop
      vertex 151.833435 149.023117 3.000000
      vertex 151.772995 148.942276 3.000000
      vertex 151.833435 149.023117 0.000000
    endloop
  endfacet
  facet normal 0.740002 -0.672605 0.000000
    outer loop
      vertex 151.901199 149.097672 0.000000
      vertex 151.833435 149.023117 3.000000
      vertex 151.833435 149.023117 0.000000
    endloop
  endfacet
  facet normal 0.740002 -0.672605 0.000000
    outer loop
      vertex 151.901199 149.097672 3.000000
      vertex 151.833435 149.023117 3.000000
      vertex 151.901199 149.097672 0.000000
    endloop
  endfacet
  facet normal 0.672612 -0.739995 0.000000
    outer loop
      vertex 151.975769 149.165451 0.000000
      vertex 151.901199 149.097672 3.000000
      vertex 151.901199 149.097672 0.000000
    endloop
  endfacet
  facet normal 0.672612 -0.739995 0.000000
    outer loop
      vertex 151.975769 149.165451 3.000000
      vertex 151.901199 149.097672 3.000000
      vertex 151.975769 149.165451 0.000000
    endloop
  endfacet
  facet normal 0.598790 -0.800906 0.000000
    outer loop
      vertex 152.056610 149.225891 0.000000
      vertex 151.975769 149.165451 3.000000
      vertex 151.975769 149.165451 0.000000
    endloop
  endfacet
  facet normal 0.598790 -0.800906 0.000000
    outer loop
      vertex 152.056610 149.225891 3.000000
      vertex 151.975769 149.165451 3.000000
      vertex 152.056610 149.225891 0.000000
    endloop
  endfacet
  facet normal 0.519273 -0.854608 0.000000
    outer loop
      vertex 152.143173 149.278488 0.000000
      vertex 152.056610 149.225891 3.000000
      vertex 152.056610 149.225891 0.000000
    endloop
  endfacet
  facet normal 0.519273 -0.854608 0.000000
    outer loop
      vertex 152.143173 149.278488 3.000000
      vertex 152.056610 149.225891 3.000000
      vertex 152.143173 149.278488 0.000000
    endloop
  endfacet
  facet normal 0.433924 -0.900950 0.000000
    outer loop
      vertex 152.234955 149.322693 0.000000
      vertex 152.143173 149.278488 3.000000
      vertex 152.143173 149.278488 0.000000
    endloop
  endfacet
  facet normal 0.433924 -0.900950 0.000000
    outer loop
      vertex 152.234955 149.322693 3.000000
      vertex 152.143173 149.278488 3.000000
      vertex 152.234955 149.322693 0.000000
    endloop
  endfacet
  facet normal 0.343674 -0.939089 0.000000
    outer loop
      vertex 152.331436 149.358002 0.000000
      vertex 152.234955 149.322693 3.000000
      vertex 152.234955 149.322693 0.000000
    endloop
  endfacet
  facet normal 0.343674 -0.939089 0.000000
    outer loop
      vertex 152.331436 149.358002 3.000000
      vertex 152.234955 149.322693 3.000000
      vertex 152.331436 149.358002 0.000000
    endloop
  endfacet
  facet normal 0.249096 -0.968479 0.000000
    outer loop
      vertex 152.432053 149.383881 0.000000
      vertex 152.331436 149.358002 3.000000
      vertex 152.331436 149.358002 0.000000
    endloop
  endfacet
  facet normal 0.249096 -0.968479 0.000000
    outer loop
      vertex 152.432053 149.383881 3.000000
      vertex 152.331436 149.358002 3.000000
      vertex 152.432053 149.383881 0.000000
    endloop
  endfacet
  facet normal 0.150894 -0.988550 0.000000
    outer loop
      vertex 152.536316 149.399796 0.000000
      vertex 152.432053 149.383881 3.000000
      vertex 152.432053 149.383881 0.000000
    endloop
  endfacet
  facet normal 0.150894 -0.988550 0.000000
    outer loop
      vertex 152.536316 149.399796 3.000000
      vertex 152.432053 149.383881 3.000000
      vertex 152.536316 149.399796 0.000000
    endloop
  endfacet
  facet normal 0.050398 -0.998729 0.000000
    outer loop
      vertex 152.643661 149.405212 0.000000
      vertex 152.536316 149.399796 3.000000
      vertex 152.536316 149.399796 0.000000
    endloop
  endfacet
  facet normal 0.050398 -0.998729 0.000000
    outer loop
      vertex 152.643661 149.405212 3.000000
      vertex 152.536316 149.399796 3.000000
      vertex 152.643661 149.405212 0.000000
    endloop
  endfacet
  facet normal -0.050391 -0.998730 0.000000
    outer loop
      vertex 152.751022 149.399796 0.000000
      vertex 152.643661 149.405212 3.000000
      vertex 152.643661 149.405212 0.000000
    endloop
  endfacet
  facet normal -0.050391 -0.998730 -0.000000
    outer loop
      vertex 152.751022 149.399796 3.000000
      vertex 152.643661 149.405212 3.000000
      vertex 152.751022 149.399796 0.000000
    endloop
  endfacet
  facet normal -0.150894 -0.988550 0.000000
    outer loop
      vertex 152.855286 149.383881 0.000000
      vertex 152.751022 149.399796 3.000000
      vertex 152.751022 149.399796 0.000000
    endloop
  endfacet
  facet normal -0.150894 -0.988550 -0.000000
    outer loop
      vertex 152.855286 149.383881 3.000000
      vertex 152.751022 149.399796 3.000000
      vertex 152.855286 149.383881 0.000000
    endloop
  endfacet
  facet normal -0.249096 -0.968479 0.000000
    outer loop
      vertex 152.955902 149.358002 0.000000
      vertex 152.855286 149.383881 3.000000
      vertex 152.855286 149.383881 0.000000
    endloop
  endfacet
  facet normal -0.249096 -0.968479 -0.000000
    outer loop
      vertex 152.955902 149.358002 3.000000
      vertex 152.855286 149.383881 3.000000
      vertex 152.955902 149.358002 0.000000
    endloop
  endfacet
  facet normal -0.343674 -0.939089 0.000000
    outer loop
      vertex 153.052383 149.322693 0.000000
      vertex 152.955902 149.358002 3.000000
      vertex 152.955902 149.358002 0.000000
    endloop
  endfacet
  facet normal -0.343674 -0.939089 -0.000000
    outer loop
      vertex 153.052383 149.322693 3.000000
      vertex 152.955902 149.358002 3.000000
      vertex 153.052383 149.322693 0.000000
    endloop
  endfacet
  facet normal -0.433924 -0.900950 0.000000
    outer loop
      vertex 153.144165 149.278488 0.000000
      vertex 153.052383 149.322693 3.000000
      vertex 153.052383 149.322693 0.000000
    endloop
  endfacet
  facet normal -0.433924 -0.900950 -0.000000
    outer loop
      vertex 153.144165 149.278488 3.000000
      vertex 153.052383 149.322693 3.000000
      vertex 153.144165 149.278488 0.000000
    endloop
  endfacet
  facet normal -0.519273 -0.854608 0.000000
    outer loop
      vertex 153.230728 149.225891 0.000000
      vertex 153.144165 149.278488 3.000000
      vertex 153.144165 149.278488 0.000000
    endloop
  endfacet
  facet normal -0.519273 -0.854608 -0.000000
    outer loop
      vertex 153.230728 149.225891 3.000000
      vertex 153.144165 149.278488 3.000000
      vertex 153.230728 149.225891 0.000000
    endloop
  endfacet
  facet normal -0.598790 -0.800906 0.000000
    outer loop
      vertex 153.311569 149.165451 0.000000
      vertex 153.230728 149.225891 3.000000
      vertex 153.230728 149.225891 0.000000
    endloop
  endfacet
  facet normal -0.598790 -0.800906 -0.000000
    outer loop
      vertex 153.311569 149.165451 3.000000
      vertex 153.230728 149.225891 3.000000
      vertex 153.311569 149.165451 0.000000
    endloop
  endfacet
  facet normal -0.672688 -0.739926 0.000000
    outer loop
      vertex 153.386124 149.097672 0.000000
      vertex 153.311569 149.165451 3.000000
      vertex 153.311569 149.165451 0.000000
    endloop
  endfacet
  facet normal -0.672688 -0.739926 -0.000000
    outer loop
      vertex 153.386124 149.097672 3.000000
      vertex 153.311569 149.165451 3.000000
      vertex 153.386124 149.097672 0.000000
    endloop
  endfacet
  facet normal -0.739926 -0.672688 0.000000
    outer loop
      vertex 153.453903 149.023117 0.000000
      vertex 153.386124 149.097672 3.000000
      vertex 153.386124 149.097672 0.000000
    endloop
  endfacet
  facet normal -0.739926 -0.672688 -0.000000
    outer loop
      vertex 153.453903 149.023117 3.000000
      vertex 153.386124 149.097672 3.000000
      vertex 153.453903 149.023117 0.000000
    endloop
  endfacet
  facet normal -0.800906 -0.598790 0.000000
    outer loop
      vertex 153.514343 148.942276 0.000000
      vertex 153.453903 149.023117 3.000000
      vertex 153.453903 149.023117 0.000000
    endloop
  endfacet
  facet normal -0.800906 -0.598790 -0.000000
    outer loop
      vertex 153.514343 148.942276 3.000000
      vertex 153.453903 149.023117 3.000000
      vertex 153.514343 148.942276 0.000000
    endloop
  endfacet
  facet normal -0.854608 -0.519273 0.000000
    outer loop
      vertex 153.566940 148.855713 0.000000
      vertex 153.514343 148.942276 3.000000
      vertex 153.514343 148.942276 0.000000
    endloop
  endfacet
  facet normal -0.854608 -0.519273 -0.000000
    outer loop
      vertex 153.566940 148.855713 3.000000
      vertex 153.514343 148.942276 3.000000
      vertex 153.566940 148.855713 0.000000
    endloop
  endfacet
  facet normal -0.900919 -0.433987 0.000000
    outer loop
      vertex 153.611160 148.763916 0.000000
      vertex 153.566940 148.855713 3.000000
      vertex 153.566940 148.855713 0.000000
    endloop
  endfacet
  facet normal -0.900919 -0.433987 -0.000000
    outer loop
      vertex 153.611160 148.763916 3.000000
      vertex 153.566940 148.855713 3.000000
      vertex 153.611160 148.763916 0.000000
    endloop
  endfacet
  facet normal -0.939071 -0.343722 0.000000
    outer loop
      vertex 153.646469 148.667450 0.000000
      vertex 153.611160 148.763916 3.000000
      vertex 153.611160 148.763916 0.000000
    endloop
  endfacet
  facet normal -0.939071 -0.343722 -0.000000
    outer loop
      vertex 153.646469 148.667450 3.000000
      vertex 153.611160 148.763916 3.000000
      vertex 153.646469 148.667450 0.000000
    endloop
  endfacet
  facet normal -0.968523 -0.248923 0.000000
    outer loop
      vertex 153.672333 148.566818 0.000000
      vertex 153.646469 148.667450 3.000000
      vertex 153.646469 148.667450 0.000000
    endloop
  endfacet
  facet normal -0.968523 -0.248923 -0.000000
    outer loop
      vertex 153.672333 148.566818 3.000000
      vertex 153.646469 148.667450 3.000000
      vertex 153.672333 148.566818 0.000000
    endloop
  endfacet
  facet normal -0.988547 -0.150915 0.000000
    outer loop
      vertex 153.688248 148.462570 0.000000
      vertex 153.672333 148.566818 3.000000
      vertex 153.672333 148.566818 0.000000
    endloop
  endfacet
  facet normal -0.988547 -0.150915 -0.000000
    outer loop
      vertex 153.688248 148.462570 3.000000
      vertex 153.672333 148.566818 3.000000
      vertex 153.688248 148.462570 0.000000
    endloop
  endfacet
  facet normal -0.998730 -0.050391 0.000000
    outer loop
      vertex 153.693665 148.355209 0.000000
      vertex 153.688248 148.462570 3.000000
      vertex 153.688248 148.462570 0.000000
    endloop
  endfacet
  facet normal -0.998730 -0.050391 -0.000000
    outer loop
      vertex 153.693665 148.355209 3.000000
      vertex 153.688248 148.462570 3.000000
      vertex 153.693665 148.355209 0.000000
    endloop
  endfacet
  facet normal -0.998729 0.050394 0.000000
    outer loop
      vertex 156.096970 76.709427 3.000000
      vertex 156.096970 76.709427 0.000000
      vertex 156.091553 76.602074 0.000000
    endloop
  endfacet
  facet normal -0.998729 0.050394 0.000000
    outer loop
      vertex 156.091553 76.602074 3.000000
      vertex 156.096970 76.709427 3.000000
      vertex 156.091553 76.602074 0.000000
    endloop
  endfacet
  facet normal -0.988548 0.150905 0.000000
    outer loop
      vertex 156.075638 76.497818 0.000000
      vertex 156.091553 76.602074 3.000000
      vertex 156.091553 76.602074 0.000000
    endloop
  endfacet
  facet normal -0.988548 0.150905 0.000000
    outer loop
      vertex 156.075638 76.497818 3.000000
      vertex 156.091553 76.602074 3.000000
      vertex 156.075638 76.497818 0.000000
    endloop
  endfacet
  facet normal -0.968488 0.249061 0.000000
    outer loop
      vertex 156.049759 76.397186 0.000000
      vertex 156.075638 76.497818 3.000000
      vertex 156.075638 76.497818 0.000000
    endloop
  endfacet
  facet normal -0.968488 0.249061 0.000000
    outer loop
      vertex 156.049759 76.397186 3.000000
      vertex 156.075638 76.497818 3.000000
      vertex 156.049759 76.397186 0.000000
    endloop
  endfacet
  facet normal -0.939071 0.343722 0.000000
    outer loop
      vertex 156.014450 76.300720 0.000000
      vertex 156.049759 76.397186 3.000000
      vertex 156.049759 76.397186 0.000000
    endloop
  endfacet
  facet normal -0.939071 0.343722 0.000000
    outer loop
      vertex 156.014450 76.300720 3.000000
      vertex 156.049759 76.397186 3.000000
      vertex 156.014450 76.300720 0.000000
    endloop
  endfacet
  facet normal -0.900950 0.433924 0.000000
    outer loop
      vertex 155.970245 76.208939 0.000000
      vertex 156.014450 76.300720 3.000000
      vertex 156.014450 76.300720 0.000000
    endloop
  endfacet
  facet normal -0.900950 0.433924 0.000000
    outer loop
      vertex 155.970245 76.208939 3.000000
      vertex 156.014450 76.300720 3.000000
      vertex 155.970245 76.208939 0.000000
    endloop
  endfacet
  facet normal -0.854649 0.519206 0.000000
    outer loop
      vertex 155.917648 76.122360 0.000000
      vertex 155.970245 76.208939 3.000000
      vertex 155.970245 76.208939 0.000000
    endloop
  endfacet
  facet normal -0.854649 0.519206 0.000000
    outer loop
      vertex 155.917648 76.122360 3.000000
      vertex 155.970245 76.208939 3.000000
      vertex 155.917648 76.122360 0.000000
    endloop
  endfacet
  facet normal -0.800807 0.598923 0.000000
    outer loop
      vertex 155.857193 76.041527 0.000000
      vertex 155.917648 76.122360 3.000000
      vertex 155.917648 76.122360 0.000000
    endloop
  endfacet
  facet normal -0.800807 0.598923 0.000000
    outer loop
      vertex 155.857193 76.041527 3.000000
      vertex 155.917648 76.122360 3.000000
      vertex 155.857193 76.041527 0.000000
    endloop
  endfacet
  facet normal -0.740036 0.672567 0.000000
    outer loop
      vertex 155.789429 75.966965 0.000000
      vertex 155.857193 76.041527 3.000000
      vertex 155.857193 76.041527 0.000000
    endloop
  endfacet
  facet normal -0.740036 0.672567 0.000000
    outer loop
      vertex 155.789429 75.966965 3.000000
      vertex 155.857193 76.041527 3.000000
      vertex 155.789429 75.966965 0.000000
    endloop
  endfacet
  facet normal -0.672571 0.740033 0.000000
    outer loop
      vertex 155.714859 75.899193 0.000000
      vertex 155.789429 75.966965 3.000000
      vertex 155.789429 75.966965 0.000000
    endloop
  endfacet
  facet normal -0.672571 0.740033 0.000000
    outer loop
      vertex 155.714859 75.899193 3.000000
      vertex 155.789429 75.966965 3.000000
      vertex 155.714859 75.899193 0.000000
    endloop
  endfacet
  facet normal -0.598862 0.800852 0.000000
    outer loop
      vertex 155.634033 75.838753 0.000000
      vertex 155.714859 75.899193 3.000000
      vertex 155.714859 75.899193 0.000000
    endloop
  endfacet
  facet normal -0.598862 0.800852 0.000000
    outer loop
      vertex 155.634033 75.838753 3.000000
      vertex 155.714859 75.899193 3.000000
      vertex 155.634033 75.838753 0.000000
    endloop
  endfacet
  facet normal -0.519206 0.854649 0.000000
    outer loop
      vertex 155.547455 75.786156 0.000000
      vertex 155.634033 75.838753 3.000000
      vertex 155.634033 75.838753 0.000000
    endloop
  endfacet
  facet normal -0.519206 0.854649 0.000000
    outer loop
      vertex 155.547455 75.786156 3.000000
      vertex 155.634033 75.838753 3.000000
      vertex 155.547455 75.786156 0.000000
    endloop
  endfacet
  facet normal -0.433984 0.900920 0.000000
    outer loop
      vertex 155.455673 75.741943 0.000000
      vertex 155.547455 75.786156 3.000000
      vertex 155.547455 75.786156 0.000000
    endloop
  endfacet
  facet normal -0.433984 0.900920 0.000000
    outer loop
      vertex 155.455673 75.741943 3.000000
      vertex 155.547455 75.786156 3.000000
      vertex 155.455673 75.741943 0.000000
    endloop
  endfacet
  facet normal -0.343722 0.939071 0.000000
    outer loop
      vertex 155.359207 75.706635 0.000000
      vertex 155.455673 75.741943 3.000000
      vertex 155.455673 75.741943 0.000000
    endloop
  endfacet
  facet normal -0.343722 0.939071 0.000000
    outer loop
      vertex 155.359207 75.706635 3.000000
      vertex 155.455673 75.741943 3.000000
      vertex 155.359207 75.706635 0.000000
    endloop
  endfacet
  facet normal -0.248992 0.968506 0.000000
    outer loop
      vertex 155.258575 75.680763 0.000000
      vertex 155.359207 75.706635 3.000000
      vertex 155.359207 75.706635 0.000000
    endloop
  endfacet
  facet normal -0.248992 0.968506 0.000000
    outer loop
      vertex 155.258575 75.680763 3.000000
      vertex 155.359207 75.706635 3.000000
      vertex 155.258575 75.680763 0.000000
    endloop
  endfacet
  facet normal -0.150915 0.988547 0.000000
    outer loop
      vertex 155.154327 75.664848 0.000000
      vertex 155.258575 75.680763 3.000000
      vertex 155.258575 75.680763 0.000000
    endloop
  endfacet
  facet normal -0.150915 0.988547 0.000000
    outer loop
      vertex 155.154327 75.664848 3.000000
      vertex 155.258575 75.680763 3.000000
      vertex 155.154327 75.664848 0.000000
    endloop
  endfacet
  facet normal -0.050461 0.998726 0.000000
    outer loop
      vertex 155.046967 75.659424 0.000000
      vertex 155.154327 75.664848 3.000000
      vertex 155.154327 75.664848 0.000000
    endloop
  endfacet
  facet normal -0.050461 0.998726 0.000000
    outer loop
      vertex 155.046967 75.659424 3.000000
      vertex 155.154327 75.664848 3.000000
      vertex 155.046967 75.659424 0.000000
    endloop
  endfacet
  facet normal 0.050461 0.998726 0.000000
    outer loop
      vertex 154.939606 75.664848 0.000000
      vertex 155.046967 75.659424 3.000000
      vertex 155.046967 75.659424 0.000000
    endloop
  endfacet
  facet normal 0.050461 0.998726 0.000000
    outer loop
      vertex 154.939606 75.664848 3.000000
      vertex 155.046967 75.659424 3.000000
      vertex 154.939606 75.664848 0.000000
    endloop
  endfacet
  facet normal 0.150915 0.988547 0.000000
    outer loop
      vertex 154.835358 75.680763 0.000000
      vertex 154.939606 75.664848 3.000000
      vertex 154.939606 75.664848 0.000000
    endloop
  endfacet
  facet normal 0.150915 0.988547 0.000000
    outer loop
      vertex 154.835358 75.680763 3.000000
      vertex 154.939606 75.664848 3.000000
      vertex 154.835358 75.680763 0.000000
    endloop
  endfacet
  facet normal 0.248992 0.968506 0.000000
    outer loop
      vertex 154.734726 75.706635 0.000000
      vertex 154.835358 75.680763 3.000000
      vertex 154.835358 75.680763 0.000000
    endloop
  endfacet
  facet normal 0.248992 0.968506 0.000000
    outer loop
      vertex 154.734726 75.706635 3.000000
      vertex 154.835358 75.680763 3.000000
      vertex 154.734726 75.706635 0.000000
    endloop
  endfacet
  facet normal 0.343722 0.939071 0.000000
    outer loop
      vertex 154.638260 75.741943 0.000000
      vertex 154.734726 75.706635 3.000000
      vertex 154.734726 75.706635 0.000000
    endloop
  endfacet
  facet normal 0.343722 0.939071 0.000000
    outer loop
      vertex 154.638260 75.741943 3.000000
      vertex 154.734726 75.706635 3.000000
      vertex 154.638260 75.741943 0.000000
    endloop
  endfacet
  facet normal 0.433984 0.900920 0.000000
    outer loop
      vertex 154.546478 75.786156 0.000000
      vertex 154.638260 75.741943 3.000000
      vertex 154.638260 75.741943 0.000000
    endloop
  endfacet
  facet normal 0.433984 0.900920 0.000000
    outer loop
      vertex 154.546478 75.786156 3.000000
      vertex 154.638260 75.741943 3.000000
      vertex 154.546478 75.786156 0.000000
    endloop
  endfacet
  facet normal 0.519206 0.854649 0.000000
    outer loop
      vertex 154.459900 75.838753 0.000000
      vertex 154.546478 75.786156 3.000000
      vertex 154.546478 75.786156 0.000000
    endloop
  endfacet
  facet normal 0.519206 0.854649 0.000000
    outer loop
      vertex 154.459900 75.838753 3.000000
      vertex 154.546478 75.786156 3.000000
      vertex 154.459900 75.838753 0.000000
    endloop
  endfacet
  facet normal 0.598862 0.800852 0.000000
    outer loop
      vertex 154.379074 75.899193 0.000000
      vertex 154.459900 75.838753 3.000000
      vertex 154.459900 75.838753 0.000000
    endloop
  endfacet
  facet normal 0.598862 0.800852 0.000000
    outer loop
      vertex 154.379074 75.899193 3.000000
      vertex 154.459900 75.838753 3.000000
      vertex 154.379074 75.899193 0.000000
    endloop
  endfacet
  facet normal 0.672571 0.740033 0.000000
    outer loop
      vertex 154.304504 75.966965 0.000000
      vertex 154.379074 75.899193 3.000000
      vertex 154.379074 75.899193 0.000000
    endloop
  endfacet
  facet normal 0.672571 0.740033 0.000000
    outer loop
      vertex 154.304504 75.966965 3.000000
      vertex 154.379074 75.899193 3.000000
      vertex 154.304504 75.966965 0.000000
    endloop
  endfacet
  facet normal 0.740036 0.672567 0.000000
    outer loop
      vertex 154.236740 76.041527 0.000000
      vertex 154.304504 75.966965 3.000000
      vertex 154.304504 75.966965 0.000000
    endloop
  endfacet
  facet normal 0.740036 0.672567 0.000000
    outer loop
      vertex 154.236740 76.041527 3.000000
      vertex 154.304504 75.966965 3.000000
      vertex 154.236740 76.041527 0.000000
    endloop
  endfacet
  facet normal 0.800807 0.598923 0.000000
    outer loop
      vertex 154.176285 76.122360 0.000000
      vertex 154.236740 76.041527 3.000000
      vertex 154.236740 76.041527 0.000000
    endloop
  endfacet
  facet normal 0.800807 0.598923 0.000000
    outer loop
      vertex 154.176285 76.122360 3.000000
      vertex 154.236740 76.041527 3.000000
      vertex 154.176285 76.122360 0.000000
    endloop
  endfacet
  facet normal 0.854716 0.519096 0.000000
    outer loop
      vertex 154.123703 76.208939 0.000000
      vertex 154.176285 76.122360 3.000000
      vertex 154.176285 76.122360 0.000000
    endloop
  endfacet
  facet normal 0.854716 0.519096 0.000000
    outer loop
      vertex 154.123703 76.208939 3.000000
      vertex 154.176285 76.122360 3.000000
      vertex 154.123703 76.208939 0.000000
    endloop
  endfacet
  facet normal 0.900891 0.434045 0.000000
    outer loop
      vertex 154.079483 76.300720 0.000000
      vertex 154.123703 76.208939 3.000000
      vertex 154.123703 76.208939 0.000000
    endloop
  endfacet
  facet normal 0.900891 0.434045 0.000000
    outer loop
      vertex 154.079483 76.300720 3.000000
      vertex 154.123703 76.208939 3.000000
      vertex 154.079483 76.300720 0.000000
    endloop
  endfacet
  facet normal 0.939071 0.343722 0.000000
    outer loop
      vertex 154.044174 76.397186 0.000000
      vertex 154.079483 76.300720 3.000000
      vertex 154.079483 76.300720 0.000000
    endloop
  endfacet
  facet normal 0.939071 0.343722 0.000000
    outer loop
      vertex 154.044174 76.397186 3.000000
      vertex 154.079483 76.300720 3.000000
      vertex 154.044174 76.397186 0.000000
    endloop
  endfacet
  facet normal 0.968488 0.249061 0.000000
    outer loop
      vertex 154.018295 76.497818 0.000000
      vertex 154.044174 76.397186 3.000000
      vertex 154.044174 76.397186 0.000000
    endloop
  endfacet
  facet normal 0.968488 0.249061 0.000000
    outer loop
      vertex 154.018295 76.497818 3.000000
      vertex 154.044174 76.397186 3.000000
      vertex 154.018295 76.497818 0.000000
    endloop
  endfacet
  facet normal 0.988570 0.150763 0.000000
    outer loop
      vertex 154.002396 76.602074 0.000000
      vertex 154.018295 76.497818 3.000000
      vertex 154.018295 76.497818 0.000000
    endloop
  endfacet
  facet normal 0.988570 0.150763 0.000000
    outer loop
      vertex 154.002396 76.602074 3.000000
      vertex 154.018295 76.497818 3.000000
      vertex 154.002396 76.602074 0.000000
    endloop
  endfacet
  facet normal 0.998722 0.050536 0.000000
    outer loop
      vertex 153.996964 76.709427 0.000000
      vertex 154.002396 76.602074 3.000000
      vertex 154.002396 76.602074 0.000000
    endloop
  endfacet
  facet normal 0.998722 0.050536 0.000000
    outer loop
      vertex 153.996964 76.709427 3.000000
      vertex 154.002396 76.602074 3.000000
      vertex 153.996964 76.709427 0.000000
    endloop
  endfacet
  facet normal 0.998722 -0.050532 0.000000
    outer loop
      vertex 154.002396 76.816788 0.000000
      vertex 153.996964 76.709427 3.000000
      vertex 153.996964 76.709427 0.000000
    endloop
  endfacet
  facet normal 0.998722 -0.050532 0.000000
    outer loop
      vertex 154.002396 76.816788 3.000000
      vertex 153.996964 76.709427 3.000000
      vertex 154.002396 76.816788 0.000000
    endloop
  endfacet
  facet normal 0.988568 -0.150774 0.000000
    outer loop
      vertex 154.018295 76.921036 0.000000
      vertex 154.002396 76.816788 3.000000
      vertex 154.002396 76.816788 0.000000
    endloop
  endfacet
  facet normal 0.988568 -0.150774 0.000000
    outer loop
      vertex 154.018295 76.921036 3.000000
      vertex 154.002396 76.816788 3.000000
      vertex 154.018295 76.921036 0.000000
    endloop
  endfacet
  facet normal 0.968488 -0.249061 0.000000
    outer loop
      vertex 154.044174 77.021667 0.000000
      vertex 154.018295 76.921036 3.000000
      vertex 154.018295 76.921036 0.000000
    endloop
  endfacet
  facet normal 0.968488 -0.249061 0.000000
    outer loop
      vertex 154.044174 77.021667 3.000000
      vertex 154.018295 76.921036 3.000000
      vertex 154.044174 77.021667 0.000000
    endloop
  endfacet
  facet normal 0.939071 -0.343722 0.000000
    outer loop
      vertex 154.079483 77.118134 0.000000
      vertex 154.044174 77.021667 3.000000
      vertex 154.044174 77.021667 0.000000
    endloop
  endfacet
  facet normal 0.939071 -0.343722 0.000000
    outer loop
      vertex 154.079483 77.118134 3.000000
      vertex 154.044174 77.021667 3.000000
      vertex 154.079483 77.118134 0.000000
    endloop
  endfacet
  facet normal 0.900905 -0.434016 0.000000
    outer loop
      vertex 154.123703 77.209923 0.000000
      vertex 154.079483 77.118134 3.000000
      vertex 154.079483 77.118134 0.000000
    endloop
  endfacet
  facet normal 0.900905 -0.434016 0.000000
    outer loop
      vertex 154.123703 77.209923 3.000000
      vertex 154.079483 77.118134 3.000000
      vertex 154.123703 77.209923 0.000000
    endloop
  endfacet
  facet normal 0.854696 -0.519129 0.000000
    outer loop
      vertex 154.176285 77.296494 0.000000
      vertex 154.123703 77.209923 3.000000
      vertex 154.123703 77.209923 0.000000
    endloop
  endfacet
  facet normal 0.854696 -0.519129 0.000000
    outer loop
      vertex 154.176285 77.296494 3.000000
      vertex 154.123703 77.209923 3.000000
      vertex 154.176285 77.296494 0.000000
    endloop
  endfacet
  facet normal 0.800807 -0.598923 0.000000
    outer loop
      vertex 154.236740 77.377327 0.000000
      vertex 154.176285 77.296494 3.000000
      vertex 154.176285 77.296494 0.000000
    endloop
  endfacet
  facet normal 0.800807 -0.598923 0.000000
    outer loop
      vertex 154.236740 77.377327 3.000000
      vertex 154.176285 77.296494 3.000000
      vertex 154.236740 77.377327 0.000000
    endloop
  endfacet
  facet normal 0.740036 -0.672567 0.000000
    outer loop
      vertex 154.304504 77.451889 0.000000
      vertex 154.236740 77.377327 3.000000
      vertex 154.236740 77.377327 0.000000
    endloop
  endfacet
  facet normal 0.740036 -0.672567 0.000000
    outer loop
      vertex 154.304504 77.451889 3.000000
      vertex 154.236740 77.377327 3.000000
      vertex 154.304504 77.451889 0.000000
    endloop
  endfacet
  facet normal 0.672571 -0.740033 0.000000
    outer loop
      vertex 154.379074 77.519661 0.000000
      vertex 154.304504 77.451889 3.000000
      vertex 154.304504 77.451889 0.000000
    endloop
  endfacet
  facet normal 0.672571 -0.740033 0.000000
    outer loop
      vertex 154.379074 77.519661 3.000000
      vertex 154.304504 77.451889 3.000000
      vertex 154.379074 77.519661 0.000000
    endloop
  endfacet
  facet normal 0.598862 -0.800852 0.000000
    outer loop
      vertex 154.459900 77.580101 0.000000
      vertex 154.379074 77.519661 3.000000
      vertex 154.379074 77.519661 0.000000
    endloop
  endfacet
  facet normal 0.598862 -0.800852 0.000000
    outer loop
      vertex 154.459900 77.580101 3.000000
      vertex 154.379074 77.519661 3.000000
      vertex 154.459900 77.580101 0.000000
    endloop
  endfacet
  facet normal 0.519206 -0.854649 0.000000
    outer loop
      vertex 154.546478 77.632698 0.000000
      vertex 154.459900 77.580101 3.000000
      vertex 154.459900 77.580101 0.000000
    endloop
  endfacet
  facet normal 0.519206 -0.854649 0.000000
    outer loop
      vertex 154.546478 77.632698 3.000000
      vertex 154.459900 77.580101 3.000000
      vertex 154.546478 77.632698 0.000000
    endloop
  endfacet
  facet normal 0.433984 -0.900920 0.000000
    outer loop
      vertex 154.638260 77.676910 0.000000
      vertex 154.546478 77.632698 3.000000
      vertex 154.546478 77.632698 0.000000
    endloop
  endfacet
  facet normal 0.433984 -0.900920 0.000000
    outer loop
      vertex 154.638260 77.676910 3.000000
      vertex 154.546478 77.632698 3.000000
      vertex 154.638260 77.676910 0.000000
    endloop
  endfacet
  facet normal 0.343722 -0.939071 0.000000
    outer loop
      vertex 154.734726 77.712219 0.000000
      vertex 154.638260 77.676910 3.000000
      vertex 154.638260 77.676910 0.000000
    endloop
  endfacet
  facet normal 0.343722 -0.939071 0.000000
    outer loop
      vertex 154.734726 77.712219 3.000000
      vertex 154.638260 77.676910 3.000000
      vertex 154.734726 77.712219 0.000000
    endloop
  endfacet
  facet normal 0.249061 -0.968488 0.000000
    outer loop
      vertex 154.835358 77.738098 0.000000
      vertex 154.734726 77.712219 3.000000
      vertex 154.734726 77.712219 0.000000
    endloop
  endfacet
  facet normal 0.249061 -0.968488 0.000000
    outer loop
      vertex 154.835358 77.738098 3.000000
      vertex 154.734726 77.712219 3.000000
      vertex 154.835358 77.738098 0.000000
    endloop
  endfacet
  facet normal 0.150845 -0.988558 0.000000
    outer loop
      vertex 154.939606 77.754005 0.000000
      vertex 154.835358 77.738098 3.000000
      vertex 154.835358 77.738098 0.000000
    endloop
  endfacet
  facet normal 0.150845 -0.988558 0.000000
    outer loop
      vertex 154.939606 77.754005 3.000000
      vertex 154.835358 77.738098 3.000000
      vertex 154.939606 77.754005 0.000000
    endloop
  endfacet
  facet normal 0.050461 -0.998726 0.000000
    outer loop
      vertex 155.046967 77.759430 0.000000
      vertex 154.939606 77.754005 3.000000
      vertex 154.939606 77.754005 0.000000
    endloop
  endfacet
  facet normal 0.050461 -0.998726 0.000000
    outer loop
      vertex 155.046967 77.759430 3.000000
      vertex 154.939606 77.754005 3.000000
      vertex 155.046967 77.759430 0.000000
    endloop
  endfacet
  facet normal -0.050461 -0.998726 0.000000
    outer loop
      vertex 155.154327 77.754005 0.000000
      vertex 155.046967 77.759430 3.000000
      vertex 155.046967 77.759430 0.000000
    endloop
  endfacet
  facet normal -0.050461 -0.998726 -0.000000
    outer loop
      vertex 155.154327 77.754005 3.000000
      vertex 155.046967 77.759430 3.000000
      vertex 155.154327 77.754005 0.000000
    endloop
  endfacet
  facet normal -0.150845 -0.988558 0.000000
    outer loop
      vertex 155.258575 77.738098 0.000000
      vertex 155.154327 77.754005 3.000000
      vertex 155.154327 77.754005 0.000000
    endloop
  endfacet
  facet normal -0.150845 -0.988558 -0.000000
    outer loop
      vertex 155.258575 77.738098 3.000000
      vertex 155.154327 77.754005 3.000000
      vertex 155.258575 77.738098 0.000000
    endloop
  endfacet
  facet normal -0.249061 -0.968488 0.000000
    outer loop
      vertex 155.359207 77.712219 0.000000
      vertex 155.258575 77.738098 3.000000
      vertex 155.258575 77.738098 0.000000
    endloop
  endfacet
  facet normal -0.249061 -0.968488 -0.000000
    outer loop
      vertex 155.359207 77.712219 3.000000
      vertex 155.258575 77.738098 3.000000
      vertex 155.359207 77.712219 0.000000
    endloop
  endfacet
  facet normal -0.343722 -0.939071 0.000000
    outer loop
      vertex 155.455673 77.676910 0.000000
      vertex 155.359207 77.712219 3.000000
      vertex 155.359207 77.712219 0.000000
    endloop
  endfacet
  facet normal -0.343722 -0.939071 -0.000000
    outer loop
      vertex 155.455673 77.676910 3.000000
      vertex 155.359207 77.712219 3.000000
      vertex 155.455673 77.676910 0.000000
    endloop
  endfacet
  facet normal -0.433984 -0.900920 0.000000
    outer loop
      vertex 155.547455 77.632698 0.000000
      vertex 155.455673 77.676910 3.000000
      vertex 155.455673 77.676910 0.000000
    endloop
  endfacet
  facet normal -0.433984 -0.900920 -0.000000
    outer loop
      vertex 155.547455 77.632698 3.000000
      vertex 155.455673 77.676910 3.000000
      vertex 155.547455 77.632698 0.000000
    endloop
  endfacet
  facet normal -0.519206 -0.854649 0.000000
    outer loop
      vertex 155.634033 77.580101 0.000000
      vertex 155.547455 77.632698 3.000000
      vertex 155.547455 77.632698 0.000000
    endloop
  endfacet
  facet normal -0.519206 -0.854649 -0.000000
    outer loop
      vertex 155.634033 77.580101 3.000000
      vertex 155.547455 77.632698 3.000000
      vertex 155.634033 77.580101 0.000000
    endloop
  endfacet
  facet normal -0.598862 -0.800852 0.000000
    outer loop
      vertex 155.714859 77.519661 0.000000
      vertex 155.634033 77.580101 3.000000
      vertex 155.634033 77.580101 0.000000
    endloop
  endfacet
  facet normal -0.598862 -0.800852 -0.000000
    outer loop
      vertex 155.714859 77.519661 3.000000
      vertex 155.634033 77.580101 3.000000
      vertex 155.714859 77.519661 0.000000
    endloop
  endfacet
  facet normal -0.672571 -0.740033 0.000000
    outer loop
      vertex 155.789429 77.451889 0.000000
      vertex 155.714859 77.519661 3.000000
      vertex 155.714859 77.519661 0.000000
    endloop
  endfacet
  facet normal -0.672571 -0.740033 -0.000000
    outer loop
      vertex 155.789429 77.451889 3.000000
      vertex 155.714859 77.519661 3.000000
      vertex 155.789429 77.451889 0.000000
    endloop
  endfacet
  facet normal -0.740036 -0.672567 0.000000
    outer loop
      vertex 155.857193 77.377327 0.000000
      vertex 155.789429 77.451889 3.000000
      vertex 155.789429 77.451889 0.000000
    endloop
  endfacet
  facet normal -0.740036 -0.672567 -0.000000
    outer loop
      vertex 155.857193 77.377327 3.000000
      vertex 155.789429 77.451889 3.000000
      vertex 155.857193 77.377327 0.000000
    endloop
  endfacet
  facet normal -0.800807 -0.598923 0.000000
    outer loop
      vertex 155.917648 77.296494 0.000000
      vertex 155.857193 77.377327 3.000000
      vertex 155.857193 77.377327 0.000000
    endloop
  endfacet
  facet normal -0.800807 -0.598923 -0.000000
    outer loop
      vertex 155.917648 77.296494 3.000000
      vertex 155.857193 77.377327 3.000000
      vertex 155.917648 77.296494 0.000000
    endloop
  endfacet
  facet normal -0.854629 -0.519240 0.000000
    outer loop
      vertex 155.970245 77.209923 0.000000
      vertex 155.917648 77.296494 3.000000
      vertex 155.917648 77.296494 0.000000
    endloop
  endfacet
  facet normal -0.854629 -0.519240 -0.000000
    outer loop
      vertex 155.970245 77.209923 3.000000
      vertex 155.917648 77.296494 3.000000
      vertex 155.970245 77.209923 0.000000
    endloop
  endfacet
  facet normal -0.900964 -0.433894 0.000000
    outer loop
      vertex 156.014450 77.118134 0.000000
      vertex 155.970245 77.209923 3.000000
      vertex 155.970245 77.209923 0.000000
    endloop
  endfacet
  facet normal -0.900964 -0.433894 -0.000000
    outer loop
      vertex 156.014450 77.118134 3.000000
      vertex 155.970245 77.209923 3.000000
      vertex 156.014450 77.118134 0.000000
    endloop
  endfacet
  facet normal -0.939071 -0.343722 0.000000
    outer loop
      vertex 156.049759 77.021667 0.000000
      vertex 156.014450 77.118134 3.000000
      vertex 156.014450 77.118134 0.000000
    endloop
  endfacet
  facet normal -0.939071 -0.343722 -0.000000
    outer loop
      vertex 156.049759 77.021667 3.000000
      vertex 156.014450 77.118134 3.000000
      vertex 156.049759 77.021667 0.000000
    endloop
  endfacet
  facet normal -0.968488 -0.249061 0.000000
    outer loop
      vertex 156.075638 76.921036 0.000000
      vertex 156.049759 77.021667 3.000000
      vertex 156.049759 77.021667 0.000000
    endloop
  endfacet
  facet normal -0.968488 -0.249061 -0.000000
    outer loop
      vertex 156.075638 76.921036 3.000000
      vertex 156.049759 77.021667 3.000000
      vertex 156.075638 76.921036 0.000000
    endloop
  endfacet
  facet normal -0.988547 -0.150915 0.000000
    outer loop
      vertex 156.091553 76.816788 0.000000
      vertex 156.075638 76.921036 3.000000
      vertex 156.075638 76.921036 0.000000
    endloop
  endfacet
  facet normal -0.988547 -0.150915 -0.000000
    outer loop
      vertex 156.091553 76.816788 3.000000
      vertex 156.075638 76.921036 3.000000
      vertex 156.091553 76.816788 0.000000
    endloop
  endfacet
  facet normal -0.998730 -0.050391 0.000000
    outer loop
      vertex 156.096970 76.709427 0.000000
      vertex 156.091553 76.816788 3.000000
      vertex 156.091553 76.816788 0.000000
    endloop
  endfacet
  facet normal -0.998730 -0.050391 -0.000000
    outer loop
      vertex 156.096970 76.709427 3.000000
      vertex 156.091553 76.816788 3.000000
      vertex 156.096970 76.709427 0.000000
    endloop
  endfacet
  facet normal -0.998726 0.050465 0.000000
    outer loop
      vertex 100.071449 91.467072 3.000000
      vertex 100.071449 91.467072 0.000000
      vertex 100.066025 91.359718 0.000000
    endloop
  endfacet
  facet normal -0.998726 0.050465 0.000000
    outer loop
      vertex 100.066025 91.359718 3.000000
      vertex 100.071449 91.467072 3.000000
      vertex 100.066025 91.359718 0.000000
    endloop
  endfacet
  facet normal -0.988559 0.150834 0.000000
    outer loop
      vertex 100.050117 91.255463 0.000000
      vertex 100.066025 91.359718 3.000000
      vertex 100.066025 91.359718 0.000000
    endloop
  endfacet
  facet normal -0.988559 0.150834 0.000000
    outer loop
      vertex 100.050117 91.255463 3.000000
      vertex 100.066025 91.359718 3.000000
      vertex 100.050117 91.255463 0.000000
    endloop
  endfacet
  facet normal -0.968483 0.249078 0.000000
    outer loop
      vertex 100.024239 91.154839 0.000000
      vertex 100.050117 91.255463 3.000000
      vertex 100.050117 91.255463 0.000000
    endloop
  endfacet
  facet normal -0.968483 0.249078 0.000000
    outer loop
      vertex 100.024239 91.154839 3.000000
      vertex 100.050117 91.255463 3.000000
      vertex 100.024239 91.154839 0.000000
    endloop
  endfacet
  facet normal -0.939080 0.343698 0.000000
    outer loop
      vertex 99.988930 91.058365 0.000000
      vertex 100.024239 91.154839 3.000000
      vertex 100.024239 91.154839 0.000000
    endloop
  endfacet
  facet normal -0.939080 0.343698 0.000000
    outer loop
      vertex 99.988930 91.058365 3.000000
      vertex 100.024239 91.154839 3.000000
      vertex 99.988930 91.058365 0.000000
    endloop
  endfacet
  facet normal -0.900920 0.433984 0.000000
    outer loop
      vertex 99.944717 90.966583 0.000000
      vertex 99.988930 91.058365 3.000000
      vertex 99.988930 91.058365 0.000000
    endloop
  endfacet
  facet normal -0.900920 0.433984 0.000000
    outer loop
      vertex 99.944717 90.966583 3.000000
      vertex 99.988930 91.058365 3.000000
      vertex 99.944717 90.966583 0.000000
    endloop
  endfacet
  facet normal -0.854629 0.519240 0.000000
    outer loop
      vertex 99.892120 90.880013 0.000000
      vertex 99.944717 90.966583 3.000000
      vertex 99.944717 90.966583 0.000000
    endloop
  endfacet
  facet normal -0.854629 0.519240 0.000000
    outer loop
      vertex 99.892120 90.880013 3.000000
      vertex 99.944717 90.966583 3.000000
      vertex 99.892120 90.880013 0.000000
    endloop
  endfacet
  facet normal -0.800879 0.598826 0.000000
    outer loop
      vertex 99.831680 90.799179 0.000000
      vertex 99.892120 90.880013 3.000000
      vertex 99.892120 90.880013 0.000000
    endloop
  endfacet
  facet normal -0.800879 0.598826 0.000000
    outer loop
      vertex 99.831680 90.799179 3.000000
      vertex 99.892120 90.880013 3.000000
      vertex 99.831680 90.799179 0.000000
    endloop
  endfacet
  facet normal -0.740033 0.672571 0.000000
    outer loop
      vertex 99.763908 90.724609 0.000000
      vertex 99.831680 90.799179 3.000000
      vertex 99.831680 90.799179 0.000000
    endloop
  endfacet
  facet normal -0.740033 0.672571 0.000000
    outer loop
      vertex 99.763908 90.724609 3.000000
      vertex 99.831680 90.799179 3.000000
      vertex 99.763908 90.724609 0.000000
    endloop
  endfacet
  facet normal -0.672567 0.740036 0.000000
    outer loop
      vertex 99.689346 90.656845 0.000000
      vertex 99.763908 90.724609 3.000000
      vertex 99.763908 90.724609 0.000000
    endloop
  endfacet
  facet normal -0.672567 0.740036 0.000000
    outer loop
      vertex 99.689346 90.656845 3.000000
      vertex 99.763908 90.724609 3.000000
      vertex 99.689346 90.656845 0.000000
    endloop
  endfacet
  facet normal -0.598875 0.800843 0.000000
    outer loop
      vertex 99.608513 90.596397 0.000000
      vertex 99.689346 90.656845 3.000000
      vertex 99.689346 90.656845 0.000000
    endloop
  endfacet
  facet normal -0.598875 0.800843 0.000000
    outer loop
      vertex 99.608513 90.596397 3.000000
      vertex 99.689346 90.656845 3.000000
      vertex 99.608513 90.596397 0.000000
    endloop
  endfacet
  facet normal -0.519184 0.854662 0.000000
    outer loop
      vertex 99.521942 90.543808 0.000000
      vertex 99.608513 90.596397 3.000000
      vertex 99.608513 90.596397 0.000000
    endloop
  endfacet
  facet normal -0.519184 0.854662 0.000000
    outer loop
      vertex 99.521942 90.543808 3.000000
      vertex 99.608513 90.596397 3.000000
      vertex 99.521942 90.543808 0.000000
    endloop
  endfacet
  facet normal -0.434016 0.900905 0.000000
    outer loop
      vertex 99.430153 90.499588 0.000000
      vertex 99.521942 90.543808 3.000000
      vertex 99.521942 90.543808 0.000000
    endloop
  endfacet
  facet normal -0.434016 0.900905 0.000000
    outer loop
      vertex 99.430153 90.499588 3.000000
      vertex 99.521942 90.543808 3.000000
      vertex 99.430153 90.499588 0.000000
    endloop
  endfacet
  facet normal -0.343722 0.939071 0.000000
    outer loop
      vertex 99.333687 90.464279 0.000000
      vertex 99.430153 90.499588 3.000000
      vertex 99.430153 90.499588 0.000000
    endloop
  endfacet
  facet normal -0.343722 0.939071 0.000000
    outer loop
      vertex 99.333687 90.464279 3.000000
      vertex 99.430153 90.499588 3.000000
      vertex 99.333687 90.464279 0.000000
    endloop
  endfacet
  facet normal -0.248992 0.968506 0.000000
    outer loop
      vertex 99.233055 90.438408 0.000000
      vertex 99.333687 90.464279 3.000000
      vertex 99.333687 90.464279 0.000000
    endloop
  endfacet
  facet normal -0.248992 0.968506 0.000000
    outer loop
      vertex 99.233055 90.438408 3.000000
      vertex 99.333687 90.464279 3.000000
      vertex 99.233055 90.438408 0.000000
    endloop
  endfacet
  facet normal -0.150905 0.988548 0.000000
    outer loop
      vertex 99.128799 90.422493 0.000000
      vertex 99.233055 90.438408 3.000000
      vertex 99.233055 90.438408 0.000000
    endloop
  endfacet
  facet normal -0.150905 0.988548 0.000000
    outer loop
      vertex 99.128799 90.422493 3.000000
      vertex 99.233055 90.438408 3.000000
      vertex 99.128799 90.422493 0.000000
    endloop
  endfacet
  facet normal -0.050394 0.998729 0.000000
    outer loop
      vertex 99.021446 90.417076 0.000000
      vertex 99.128799 90.422493 3.000000
      vertex 99.128799 90.422493 0.000000
    endloop
  endfacet
  facet normal -0.050394 0.998729 0.000000
    outer loop
      vertex 99.021446 90.417076 3.000000
      vertex 99.128799 90.422493 3.000000
      vertex 99.021446 90.417076 0.000000
    endloop
  endfacet
  facet normal 0.050394 0.998729 0.000000
    outer loop
      vertex 98.914093 90.422493 0.000000
      vertex 99.021446 90.417076 3.000000
      vertex 99.021446 90.417076 0.000000
    endloop
  endfacet
  facet normal 0.050394 0.998729 0.000000
    outer loop
      vertex 98.914093 90.422493 3.000000
      vertex 99.021446 90.417076 3.000000
      vertex 98.914093 90.422493 0.000000
    endloop
  endfacet
  facet normal 0.150905 0.988548 0.000000
    outer loop
      vertex 98.809837 90.438408 0.000000
      vertex 98.914093 90.422493 3.000000
      vertex 98.914093 90.422493 0.000000
    endloop
  endfacet
  facet normal 0.150905 0.988548 0.000000
    outer loop
      vertex 98.809837 90.438408 3.000000
      vertex 98.914093 90.422493 3.000000
      vertex 98.809837 90.438408 0.000000
    endloop
  endfacet
  facet normal 0.248992 0.968506 0.000000
    outer loop
      vertex 98.709206 90.464279 0.000000
      vertex 98.809837 90.438408 3.000000
      vertex 98.809837 90.438408 0.000000
    endloop
  endfacet
  facet normal 0.248992 0.968506 0.000000
    outer loop
      vertex 98.709206 90.464279 3.000000
      vertex 98.809837 90.438408 3.000000
      vertex 98.709206 90.464279 0.000000
    endloop
  endfacet
  facet normal 0.343722 0.939071 0.000000
    outer loop
      vertex 98.612740 90.499588 0.000000
      vertex 98.709206 90.464279 3.000000
      vertex 98.709206 90.464279 0.000000
    endloop
  endfacet
  facet normal 0.343722 0.939071 0.000000
    outer loop
      vertex 98.612740 90.499588 3.000000
      vertex 98.709206 90.464279 3.000000
      vertex 98.612740 90.499588 0.000000
    endloop
  endfacet
  facet normal 0.434045 0.900891 0.000000
    outer loop
      vertex 98.520958 90.543808 0.000000
      vertex 98.612740 90.499588 3.000000
      vertex 98.612740 90.499588 0.000000
    endloop
  endfacet
  facet normal 0.434045 0.900891 0.000000
    outer loop
      vertex 98.520958 90.543808 3.000000
      vertex 98.612740 90.499588 3.000000
      vertex 98.520958 90.543808 0.000000
    endloop
  endfacet
  facet normal 0.519151 0.854683 0.000000
    outer loop
      vertex 98.434380 90.596397 0.000000
      vertex 98.520958 90.543808 3.000000
      vertex 98.520958 90.543808 0.000000
    endloop
  endfacet
  facet normal 0.519151 0.854683 0.000000
    outer loop
      vertex 98.434380 90.596397 3.000000
      vertex 98.520958 90.543808 3.000000
      vertex 98.434380 90.596397 0.000000
    endloop
  endfacet
  facet normal 0.598875 0.800843 0.000000
    outer loop
      vertex 98.353546 90.656845 0.000000
      vertex 98.434380 90.596397 3.000000
      vertex 98.434380 90.596397 0.000000
    endloop
  endfacet
  facet normal 0.598875 0.800843 0.000000
    outer loop
      vertex 98.353546 90.656845 3.000000
      vertex 98.434380 90.596397 3.000000
      vertex 98.353546 90.656845 0.000000
    endloop
  endfacet
  facet normal 0.672567 0.740036 0.000000
    outer loop
      vertex 98.278984 90.724609 0.000000
      vertex 98.353546 90.656845 3.000000
      vertex 98.353546 90.656845 0.000000
    endloop
  endfacet
  facet normal 0.672567 0.740036 0.000000
    outer loop
      vertex 98.278984 90.724609 3.000000
      vertex 98.353546 90.656845 3.000000
      vertex 98.278984 90.724609 0.000000
    endloop
  endfacet
  facet normal 0.740033 0.672571 0.000000
    outer loop
      vertex 98.211212 90.799179 0.000000
      vertex 98.278984 90.724609 3.000000
      vertex 98.278984 90.724609 0.000000
    endloop
  endfacet
  facet normal 0.740033 0.672571 0.000000
    outer loop
      vertex 98.211212 90.799179 3.000000
      vertex 98.278984 90.724609 3.000000
      vertex 98.211212 90.799179 0.000000
    endloop
  endfacet
  facet normal 0.800879 0.598826 0.000000
    outer loop
      vertex 98.150772 90.880013 0.000000
      vertex 98.211212 90.799179 3.000000
      vertex 98.211212 90.799179 0.000000
    endloop
  endfacet
  facet normal 0.800879 0.598826 0.000000
    outer loop
      vertex 98.150772 90.880013 3.000000
      vertex 98.211212 90.799179 3.000000
      vertex 98.150772 90.880013 0.000000
    endloop
  endfacet
  facet normal 0.854629 0.519240 0.000000
    outer loop
      vertex 98.098175 90.966583 0.000000
      vertex 98.150772 90.880013 3.000000
      vertex 98.150772 90.880013 0.000000
    endloop
  endfacet
  facet normal 0.854629 0.519240 0.000000
    outer loop
      vertex 98.098175 90.966583 3.000000
      vertex 98.150772 90.880013 3.000000
      vertex 98.098175 90.966583 0.000000
    endloop
  endfacet
  facet normal 0.900920 0.433984 0.000000
    outer loop
      vertex 98.053963 91.058365 0.000000
      vertex 98.098175 90.966583 3.000000
      vertex 98.098175 90.966583 0.000000
    endloop
  endfacet
  facet normal 0.900920 0.433984 0.000000
    outer loop
      vertex 98.053963 91.058365 3.000000
      vertex 98.098175 90.966583 3.000000
      vertex 98.053963 91.058365 0.000000
    endloop
  endfacet
  facet normal 0.939080 0.343698 0.000000
    outer loop
      vertex 98.018654 91.154839 0.000000
      vertex 98.053963 91.058365 3.000000
      vertex 98.053963 91.058365 0.000000
    endloop
  endfacet
  facet normal 0.939080 0.343698 0.000000
    outer loop
      vertex 98.018654 91.154839 3.000000
      vertex 98.053963 91.058365 3.000000
      vertex 98.018654 91.154839 0.000000
    endloop
  endfacet
  facet normal 0.968501 0.249010 0.000000
    outer loop
      vertex 97.992783 91.255463 0.000000
      vertex 98.018654 91.154839 3.000000
      vertex 98.018654 91.154839 0.000000
    endloop
  endfacet
  facet normal 0.968501 0.249010 0.000000
    outer loop
      vertex 97.992783 91.255463 3.000000
      vertex 98.018654 91.154839 3.000000
      vertex 97.992783 91.255463 0.000000
    endloop
  endfacet
  facet normal 0.988548 0.150905 0.000000
    outer loop
      vertex 97.976868 91.359718 0.000000
      vertex 97.992783 91.255463 3.000000
      vertex 97.992783 91.255463 0.000000
    endloop
  endfacet
  facet normal 0.988548 0.150905 0.000000
    outer loop
      vertex 97.976868 91.359718 3.000000
      vertex 97.992783 91.255463 3.000000
      vertex 97.976868 91.359718 0.000000
    endloop
  endfacet
  facet normal 0.998726 0.050465 0.000000
    outer loop
      vertex 97.971443 91.467072 0.000000
      vertex 97.976868 91.359718 3.000000
      vertex 97.976868 91.359718 0.000000
    endloop
  endfacet
  facet normal 0.998726 0.050465 0.000000
    outer loop
      vertex 97.971443 91.467072 3.000000
      vertex 97.976868 91.359718 3.000000
      vertex 97.971443 91.467072 0.000000
    endloop
  endfacet
  facet normal 0.998726 -0.050461 0.000000
    outer loop
      vertex 97.976868 91.574432 0.000000
      vertex 97.971443 91.467072 3.000000
      vertex 97.971443 91.467072 0.000000
    endloop
  endfacet
  facet normal 0.998726 -0.050461 0.000000
    outer loop
      vertex 97.976868 91.574432 3.000000
      vertex 97.971443 91.467072 3.000000
      vertex 97.976868 91.574432 0.000000
    endloop
  endfacet
  facet normal 0.988548 -0.150905 0.000000
    outer loop
      vertex 97.992783 91.678688 0.000000
      vertex 97.976868 91.574432 3.000000
      vertex 97.976868 91.574432 0.000000
    endloop
  endfacet
  facet normal 0.988548 -0.150905 0.000000
    outer loop
      vertex 97.992783 91.678688 3.000000
      vertex 97.976868 91.574432 3.000000
      vertex 97.992783 91.678688 0.000000
    endloop
  endfacet
  facet normal 0.968501 -0.249010 0.000000
    outer loop
      vertex 98.018654 91.779312 0.000000
      vertex 97.992783 91.678688 3.000000
      vertex 97.992783 91.678688 0.000000
    endloop
  endfacet
  facet normal 0.968501 -0.249010 0.000000
    outer loop
      vertex 98.018654 91.779312 3.000000
      vertex 97.992783 91.678688 3.000000
      vertex 98.018654 91.779312 0.000000
    endloop
  endfacet
  facet normal 0.939080 -0.343698 0.000000
    outer loop
      vertex 98.053963 91.875786 0.000000
      vertex 98.018654 91.779312 3.000000
      vertex 98.018654 91.779312 0.000000
    endloop
  endfacet
  facet normal 0.939080 -0.343698 0.000000
    outer loop
      vertex 98.053963 91.875786 3.000000
      vertex 98.018654 91.779312 3.000000
      vertex 98.053963 91.875786 0.000000
    endloop
  endfacet
  facet normal 0.900920 -0.433984 0.000000
    outer loop
      vertex 98.098175 91.967567 0.000000
      vertex 98.053963 91.875786 3.000000
      vertex 98.053963 91.875786 0.000000
    endloop
  endfacet
  facet normal 0.900920 -0.433984 0.000000
    outer loop
      vertex 98.098175 91.967567 3.000000
      vertex 98.053963 91.875786 3.000000
      vertex 98.098175 91.967567 0.000000
    endloop
  endfacet
  facet normal 0.854629 -0.519240 0.000000
    outer loop
      vertex 98.150772 92.054138 0.000000
      vertex 98.098175 91.967567 3.000000
      vertex 98.098175 91.967567 0.000000
    endloop
  endfacet
  facet normal 0.854629 -0.519240 0.000000
    outer loop
      vertex 98.150772 92.054138 3.000000
      vertex 98.098175 91.967567 3.000000
      vertex 98.150772 92.054138 0.000000
    endloop
  endfacet
  facet normal 0.800879 -0.598826 0.000000
    outer loop
      vertex 98.211212 92.134972 0.000000
      vertex 98.150772 92.054138 3.000000
      vertex 98.150772 92.054138 0.000000
    endloop
  endfacet
  facet normal 0.800879 -0.598826 0.000000
    outer loop
      vertex 98.211212 92.134972 3.000000
      vertex 98.150772 92.054138 3.000000
      vertex 98.211212 92.134972 0.000000
    endloop
  endfacet
  facet normal 0.739998 -0.672609 0.000000
    outer loop
      vertex 98.278984 92.209534 0.000000
      vertex 98.211212 92.134972 3.000000
      vertex 98.211212 92.134972 0.000000
    endloop
  endfacet
  facet normal 0.739998 -0.672609 0.000000
    outer loop
      vertex 98.278984 92.209534 3.000000
      vertex 98.211212 92.134972 3.000000
      vertex 98.278984 92.209534 0.000000
    endloop
  endfacet
  facet normal 0.672609 -0.739998 0.000000
    outer loop
      vertex 98.353546 92.277306 0.000000
      vertex 98.278984 92.209534 3.000000
      vertex 98.278984 92.209534 0.000000
    endloop
  endfacet
  facet normal 0.672609 -0.739998 0.000000
    outer loop
      vertex 98.353546 92.277306 3.000000
      vertex 98.278984 92.209534 3.000000
      vertex 98.353546 92.277306 0.000000
    endloop
  endfacet
  facet normal 0.598875 -0.800843 0.000000
    outer loop
      vertex 98.434380 92.337753 0.000000
      vertex 98.353546 92.277306 3.000000
      vertex 98.353546 92.277306 0.000000
    endloop
  endfacet
  facet normal 0.598875 -0.800843 0.000000
    outer loop
      vertex 98.434380 92.337753 3.000000
      vertex 98.353546 92.277306 3.000000
      vertex 98.434380 92.337753 0.000000
    endloop
  endfacet
  facet normal 0.519151 -0.854683 0.000000
    outer loop
      vertex 98.520958 92.390343 0.000000
      vertex 98.434380 92.337753 3.000000
      vertex 98.434380 92.337753 0.000000
    endloop
  endfacet
  facet normal 0.519151 -0.854683 0.000000
    outer loop
      vertex 98.520958 92.390343 3.000000
      vertex 98.434380 92.337753 3.000000
      vertex 98.520958 92.390343 0.000000
    endloop
  endfacet
  facet normal 0.434045 -0.900891 0.000000
    outer loop
      vertex 98.612740 92.434563 0.000000
      vertex 98.520958 92.390343 3.000000
      vertex 98.520958 92.390343 0.000000
    endloop
  endfacet
  facet normal 0.434045 -0.900891 0.000000
    outer loop
      vertex 98.612740 92.434563 3.000000
      vertex 98.520958 92.390343 3.000000
      vertex 98.612740 92.434563 0.000000
    endloop
  endfacet
  facet normal 0.343722 -0.939071 0.000000
    outer loop
      vertex 98.709206 92.469872 0.000000
      vertex 98.612740 92.434563 3.000000
      vertex 98.612740 92.434563 0.000000
    endloop
  endfacet
  facet normal 0.343722 -0.939071 0.000000
    outer loop
      vertex 98.709206 92.469872 3.000000
      vertex 98.612740 92.434563 3.000000
      vertex 98.709206 92.469872 0.000000
    endloop
  endfacet
  facet normal 0.248992 -0.968506 0.000000
    outer loop
      vertex 98.809837 92.495743 0.000000
      vertex 98.709206 92.469872 3.000000
      vertex 98.709206 92.469872 0.000000
    endloop
  endfacet
  facet normal 0.248992 -0.968506 0.000000
    outer loop
      vertex 98.809837 92.495743 3.000000
      vertex 98.709206 92.469872 3.000000
      vertex 98.809837 92.495743 0.000000
    endloop
  endfacet
  facet normal 0.150905 -0.988548 0.000000
    outer loop
      vertex 98.914093 92.511658 0.000000
      vertex 98.809837 92.495743 3.000000
      vertex 98.809837 92.495743 0.000000
    endloop
  endfacet
  facet normal 0.150905 -0.988548 0.000000
    outer loop
      vertex 98.914093 92.511658 3.000000
      vertex 98.809837 92.495743 3.000000
      vertex 98.914093 92.511658 0.000000
    endloop
  endfacet
  facet normal 0.050394 -0.998729 0.000000
    outer loop
      vertex 99.021446 92.517075 0.000000
      vertex 98.914093 92.511658 3.000000
      vertex 98.914093 92.511658 0.000000
    endloop
  endfacet
  facet normal 0.050394 -0.998729 0.000000
    outer loop
      vertex 99.021446 92.517075 3.000000
      vertex 98.914093 92.511658 3.000000
      vertex 99.021446 92.517075 0.000000
    endloop
  endfacet
  facet normal -0.050394 -0.998729 0.000000
    outer loop
      vertex 99.128799 92.511658 0.000000
      vertex 99.021446 92.517075 3.000000
      vertex 99.021446 92.517075 0.000000
    endloop
  endfacet
  facet normal -0.050394 -0.998729 -0.000000
    outer loop
      vertex 99.128799 92.511658 3.000000
      vertex 99.021446 92.517075 3.000000
      vertex 99.128799 92.511658 0.000000
    endloop
  endfacet
  facet normal -0.150905 -0.988548 0.000000
    outer loop
      vertex 99.233055 92.495743 0.000000
      vertex 99.128799 92.511658 3.000000
      vertex 99.128799 92.511658 0.000000
    endloop
  endfacet
  facet normal -0.150905 -0.988548 -0.000000
    outer loop
      vertex 99.233055 92.495743 3.000000
      vertex 99.128799 92.511658 3.000000
      vertex 99.233055 92.495743 0.000000
    endloop
  endfacet
  facet normal -0.248992 -0.968506 0.000000
    outer loop
      vertex 99.333687 92.469872 0.000000
      vertex 99.233055 92.495743 3.000000
      vertex 99.233055 92.495743 0.000000
    endloop
  endfacet
  facet normal -0.248992 -0.968506 -0.000000
    outer loop
      vertex 99.333687 92.469872 3.000000
      vertex 99.233055 92.495743 3.000000
      vertex 99.333687 92.469872 0.000000
    endloop
  endfacet
  facet normal -0.343722 -0.939071 0.000000
    outer loop
      vertex 99.430153 92.434563 0.000000
      vertex 99.333687 92.469872 3.000000
      vertex 99.333687 92.469872 0.000000
    endloop
  endfacet
  facet normal -0.343722 -0.939071 -0.000000
    outer loop
      vertex 99.430153 92.434563 3.000000
      vertex 99.333687 92.469872 3.000000
      vertex 99.430153 92.434563 0.000000
    endloop
  endfacet
  facet normal -0.434016 -0.900905 0.000000
    outer loop
      vertex 99.521942 92.390343 0.000000
      vertex 99.430153 92.434563 3.000000
      vertex 99.430153 92.434563 0.000000
    endloop
  endfacet
  facet normal -0.434016 -0.900905 -0.000000
    outer loop
      vertex 99.521942 92.390343 3.000000
      vertex 99.430153 92.434563 3.000000
      vertex 99.521942 92.390343 0.000000
    endloop
  endfacet
  facet normal -0.519184 -0.854662 0.000000
    outer loop
      vertex 99.608513 92.337753 0.000000
      vertex 99.521942 92.390343 3.000000
      vertex 99.521942 92.390343 0.000000
    endloop
  endfacet
  facet normal -0.519184 -0.854662 -0.000000
    outer loop
      vertex 99.608513 92.337753 3.000000
      vertex 99.521942 92.390343 3.000000
      vertex 99.608513 92.337753 0.000000
    endloop
  endfacet
  facet normal -0.598875 -0.800843 0.000000
    outer loop
      vertex 99.689346 92.277306 0.000000
      vertex 99.608513 92.337753 3.000000
      vertex 99.608513 92.337753 0.000000
    endloop
  endfacet
  facet normal -0.598875 -0.800843 -0.000000
    outer loop
      vertex 99.689346 92.277306 3.000000
      vertex 99.608513 92.337753 3.000000
      vertex 99.689346 92.277306 0.000000
    endloop
  endfacet
  facet normal -0.672609 -0.739998 0.000000
    outer loop
      vertex 99.763908 92.209534 0.000000
      vertex 99.689346 92.277306 3.000000
      vertex 99.689346 92.277306 0.000000
    endloop
  endfacet
  facet normal -0.672609 -0.739998 -0.000000
    outer loop
      vertex 99.763908 92.209534 3.000000
      vertex 99.689346 92.277306 3.000000
      vertex 99.763908 92.209534 0.000000
    endloop
  endfacet
  facet normal -0.739998 -0.672609 0.000000
    outer loop
      vertex 99.831680 92.134972 0.000000
      vertex 99.763908 92.209534 3.000000
      vertex 99.763908 92.209534 0.000000
    endloop
  endfacet
  facet normal -0.739998 -0.672609 -0.000000
    outer loop
      vertex 99.831680 92.134972 3.000000
      vertex 99.763908 92.209534 3.000000
      vertex 99.831680 92.134972 0.000000
    endloop
  endfacet
  facet normal -0.800879 -0.598826 0.000000
    outer loop
      vertex 99.892120 92.054138 0.000000
      vertex 99.831680 92.134972 3.000000
      vertex 99.831680 92.134972 0.000000
    endloop
  endfacet
  facet normal -0.800879 -0.598826 -0.000000
    outer loop
      vertex 99.892120 92.054138 3.000000
      vertex 99.831680 92.134972 3.000000
      vertex 99.892120 92.054138 0.000000
    endloop
  endfacet
  facet normal -0.854629 -0.519240 0.000000
    outer loop
      vertex 99.944717 91.967567 0.000000
      vertex 99.892120 92.054138 3.000000
      vertex 99.892120 92.054138 0.000000
    endloop
  endfacet
  facet normal -0.854629 -0.519240 -0.000000
    outer loop
      vertex 99.944717 91.967567 3.000000
      vertex 99.892120 92.054138 3.000000
      vertex 99.944717 91.967567 0.000000
    endloop
  endfacet
  facet normal -0.900920 -0.433984 0.000000
    outer loop
      vertex 99.988930 91.875786 0.000000
      vertex 99.944717 91.967567 3.000000
      vertex 99.944717 91.967567 0.000000
    endloop
  endfacet
  facet normal -0.900920 -0.433984 -0.000000
    outer loop
      vertex 99.988930 91.875786 3.000000
      vertex 99.944717 91.967567 3.000000
      vertex 99.988930 91.875786 0.000000
    endloop
  endfacet
  facet normal -0.939080 -0.343698 0.000000
    outer loop
      vertex 100.024239 91.779312 0.000000
      vertex 99.988930 91.875786 3.000000
      vertex 99.988930 91.875786 0.000000
    endloop
  endfacet
  facet normal -0.939080 -0.343698 -0.000000
    outer loop
      vertex 100.024239 91.779312 3.000000
      vertex 99.988930 91.875786 3.000000
      vertex 100.024239 91.779312 0.000000
    endloop
  endfacet
  facet normal -0.968483 -0.249078 0.000000
    outer loop
      vertex 100.050117 91.678688 0.000000
      vertex 100.024239 91.779312 3.000000
      vertex 100.024239 91.779312 0.000000
    endloop
  endfacet
  facet normal -0.968483 -0.249078 -0.000000
    outer loop
      vertex 100.050117 91.678688 3.000000
      vertex 100.024239 91.779312 3.000000
      vertex 100.050117 91.678688 0.000000
    endloop
  endfacet
  facet normal -0.988559 -0.150834 0.000000
    outer loop
      vertex 100.066025 91.574432 0.000000
      vertex 100.050117 91.678688 3.000000
      vertex 100.050117 91.678688 0.000000
    endloop
  endfacet
  facet normal -0.988559 -0.150834 -0.000000
    outer loop
      vertex 100.066025 91.574432 3.000000
      vertex 100.050117 91.678688 3.000000
      vertex 100.066025 91.574432 0.000000
    endloop
  endfacet
  facet normal -0.998726 -0.050461 0.000000
    outer loop
      vertex 100.071449 91.467072 0.000000
      vertex 100.066025 91.574432 3.000000
      vertex 100.066025 91.574432 0.000000
    endloop
  endfacet
  facet normal -0.998726 -0.050461 -0.000000
    outer loop
      vertex 100.071449 91.467072 3.000000
      vertex 100.066025 91.574432 3.000000
      vertex 100.071449 91.467072 0.000000
    endloop
  endfacet
  facet normal -0.998729 0.050398 0.000000
    outer loop
      vertex 125.063393 202.113159 3.000000
      vertex 125.063393 202.113159 0.000000
      vertex 125.057976 202.005814 0.000000
    endloop
  endfacet
  facet normal -0.998729 0.050398 0.000000
    outer loop
      vertex 125.057976 202.005814 3.000000
      vertex 125.063393 202.113159 3.000000
      vertex 125.057976 202.005814 0.000000
    endloop
  endfacet
  facet normal -0.988550 0.150894 0.000000
    outer loop
      vertex 125.042061 201.901550 0.000000
      vertex 125.057976 202.005814 3.000000
      vertex 125.057976 202.005814 0.000000
    endloop
  endfacet
  facet normal -0.988550 0.150894 0.000000
    outer loop
      vertex 125.042061 201.901550 3.000000
      vertex 125.057976 202.005814 3.000000
      vertex 125.042061 201.901550 0.000000
    endloop
  endfacet
  facet normal -0.968496 0.249027 0.000000
    outer loop
      vertex 125.016190 201.800934 0.000000
      vertex 125.042061 201.901550 3.000000
      vertex 125.042061 201.901550 0.000000
    endloop
  endfacet
  facet normal -0.968496 0.249027 0.000000
    outer loop
      vertex 125.016190 201.800934 3.000000
      vertex 125.042061 201.901550 3.000000
      vertex 125.016190 201.800934 0.000000
    endloop
  endfacet
  facet normal -0.939089 0.343674 0.000000
    outer loop
      vertex 124.980881 201.704453 0.000000
      vertex 125.016190 201.800934 3.000000
      vertex 125.016190 201.800934 0.000000
    endloop
  endfacet
  facet normal -0.939089 0.343674 0.000000
    outer loop
      vertex 124.980881 201.704453 3.000000
      vertex 125.016190 201.800934 3.000000
      vertex 124.980881 201.704453 0.000000
    endloop
  endfacet
  facet normal -0.900920 0.433984 0.000000
    outer loop
      vertex 124.936668 201.612671 0.000000
      vertex 124.980881 201.704453 3.000000
      vertex 124.980881 201.704453 0.000000
    endloop
  endfacet
  facet normal -0.900920 0.433984 0.000000
    outer loop
      vertex 124.936668 201.612671 3.000000
      vertex 124.980881 201.704453 3.000000
      vertex 124.936668 201.612671 0.000000
    endloop
  endfacet
  facet normal -0.854649 0.519206 0.000000
    outer loop
      vertex 124.884071 201.526093 0.000000
      vertex 124.936668 201.612671 3.000000
      vertex 124.936668 201.612671 0.000000
    endloop
  endfacet
  facet normal -0.854649 0.519206 0.000000
    outer loop
      vertex 124.884071 201.526093 3.000000
      vertex 124.936668 201.612671 3.000000
      vertex 124.884071 201.526093 0.000000
    endloop
  endfacet
  facet normal -0.800816 0.598911 0.000000
    outer loop
      vertex 124.823624 201.445267 0.000000
      vertex 124.884071 201.526093 3.000000
      vertex 124.884071 201.526093 0.000000
    endloop
  endfacet
  facet normal -0.800816 0.598911 0.000000
    outer loop
      vertex 124.823624 201.445267 3.000000
      vertex 124.884071 201.526093 3.000000
      vertex 124.823624 201.445267 0.000000
    endloop
  endfacet
  facet normal -0.740070 0.672530 0.000000
    outer loop
      vertex 124.755859 201.370697 0.000000
      vertex 124.823624 201.445267 3.000000
      vertex 124.823624 201.445267 0.000000
    endloop
  endfacet
  facet normal -0.740070 0.672530 0.000000
    outer loop
      vertex 124.755859 201.370697 3.000000
      vertex 124.823624 201.445267 3.000000
      vertex 124.755859 201.370697 0.000000
    endloop
  endfacet
  facet normal -0.672530 0.740070 0.000000
    outer loop
      vertex 124.681290 201.302933 0.000000
      vertex 124.755859 201.370697 3.000000
      vertex 124.755859 201.370697 0.000000
    endloop
  endfacet
  facet normal -0.672530 0.740070 0.000000
    outer loop
      vertex 124.681290 201.302933 3.000000
      vertex 124.755859 201.370697 3.000000
      vertex 124.681290 201.302933 0.000000
    endloop
  endfacet
  facet normal -0.598862 0.800852 0.000000
    outer loop
      vertex 124.600464 201.242493 0.000000
      vertex 124.681290 201.302933 3.000000
      vertex 124.681290 201.302933 0.000000
    endloop
  endfacet
  facet normal -0.598862 0.800852 0.000000
    outer loop
      vertex 124.600464 201.242493 3.000000
      vertex 124.681290 201.302933 3.000000
      vertex 124.600464 201.242493 0.000000
    endloop
  endfacet
  facet normal -0.519206 0.854649 0.000000
    outer loop
      vertex 124.513885 201.189896 0.000000
      vertex 124.600464 201.242493 3.000000
      vertex 124.600464 201.242493 0.000000
    endloop
  endfacet
  facet normal -0.519206 0.854649 0.000000
    outer loop
      vertex 124.513885 201.189896 3.000000
      vertex 124.600464 201.242493 3.000000
      vertex 124.513885 201.189896 0.000000
    endloop
  endfacet
  facet normal -0.434045 0.900891 0.000000
    outer loop
      vertex 124.422104 201.145676 0.000000
      vertex 124.513885 201.189896 3.000000
      vertex 124.513885 201.189896 0.000000
    endloop
  endfacet
  facet normal -0.434045 0.900891 0.000000
    outer loop
      vertex 124.422104 201.145676 3.000000
      vertex 124.513885 201.189896 3.000000
      vertex 124.422104 201.145676 0.000000
    endloop
  endfacet
  facet normal -0.343698 0.939080 0.000000
    outer loop
      vertex 124.325630 201.110367 0.000000
      vertex 124.422104 201.145676 3.000000
      vertex 124.422104 201.145676 0.000000
    endloop
  endfacet
  facet normal -0.343698 0.939080 0.000000
    outer loop
      vertex 124.325630 201.110367 3.000000
      vertex 124.422104 201.145676 3.000000
      vertex 124.325630 201.110367 0.000000
    endloop
  endfacet
  facet normal -0.248941 0.968519 0.000000
    outer loop
      vertex 124.225006 201.084503 0.000000
      vertex 124.325630 201.110367 3.000000
      vertex 124.325630 201.110367 0.000000
    endloop
  endfacet
  facet normal -0.248941 0.968519 0.000000
    outer loop
      vertex 124.225006 201.084503 3.000000
      vertex 124.325630 201.110367 3.000000
      vertex 124.225006 201.084503 0.000000
    endloop
  endfacet
  facet normal -0.150905 0.988548 0.000000
    outer loop
      vertex 124.120750 201.068588 0.000000
      vertex 124.225006 201.084503 3.000000
      vertex 124.225006 201.084503 0.000000
    endloop
  endfacet
  facet normal -0.150905 0.988548 0.000000
    outer loop
      vertex 124.120750 201.068588 3.000000
      vertex 124.225006 201.084503 3.000000
      vertex 124.120750 201.068588 0.000000
    endloop
  endfacet
  facet normal -0.050394 0.998729 0.000000
    outer loop
      vertex 124.013397 201.063171 0.000000
      vertex 124.120750 201.068588 3.000000
      vertex 124.120750 201.068588 0.000000
    endloop
  endfacet
  facet normal -0.050394 0.998729 0.000000
    outer loop
      vertex 124.013397 201.063171 3.000000
      vertex 124.120750 201.068588 3.000000
      vertex 124.013397 201.063171 0.000000
    endloop
  endfacet
  facet normal 0.050391 0.998730 0.000000
    outer loop
      vertex 123.906036 201.068588 0.000000
      vertex 124.013397 201.063171 3.000000
      vertex 124.013397 201.063171 0.000000
    endloop
  endfacet
  facet normal 0.050391 0.998730 0.000000
    outer loop
      vertex 123.906036 201.068588 3.000000
      vertex 124.013397 201.063171 3.000000
      vertex 123.906036 201.068588 0.000000
    endloop
  endfacet
  facet normal 0.150905 0.988548 0.000000
    outer loop
      vertex 123.801781 201.084503 0.000000
      vertex 123.906036 201.068588 3.000000
      vertex 123.906036 201.068588 0.000000
    endloop
  endfacet
  facet normal 0.150905 0.988548 0.000000
    outer loop
      vertex 123.801781 201.084503 3.000000
      vertex 123.906036 201.068588 3.000000
      vertex 123.801781 201.084503 0.000000
    endloop
  endfacet
  facet normal 0.248941 0.968519 0.000000
    outer loop
      vertex 123.701157 201.110367 0.000000
      vertex 123.801781 201.084503 3.000000
      vertex 123.801781 201.084503 0.000000
    endloop
  endfacet
  facet normal 0.248941 0.968519 0.000000
    outer loop
      vertex 123.701157 201.110367 3.000000
      vertex 123.801781 201.084503 3.000000
      vertex 123.701157 201.110367 0.000000
    endloop
  endfacet
  facet normal 0.343722 0.939071 0.000000
    outer loop
      vertex 123.604691 201.145676 0.000000
      vertex 123.701157 201.110367 3.000000
      vertex 123.701157 201.110367 0.000000
    endloop
  endfacet
  facet normal 0.343722 0.939071 0.000000
    outer loop
      vertex 123.604691 201.145676 3.000000
      vertex 123.701157 201.110367 3.000000
      vertex 123.604691 201.145676 0.000000
    endloop
  endfacet
  facet normal 0.434016 0.900905 0.000000
    outer loop
      vertex 123.512901 201.189896 0.000000
      vertex 123.604691 201.145676 3.000000
      vertex 123.604691 201.145676 0.000000
    endloop
  endfacet
  facet normal 0.434016 0.900905 0.000000
    outer loop
      vertex 123.512901 201.189896 3.000000
      vertex 123.604691 201.145676 3.000000
      vertex 123.512901 201.189896 0.000000
    endloop
  endfacet
  facet normal 0.519240 0.854629 0.000000
    outer loop
      vertex 123.426331 201.242493 0.000000
      vertex 123.512901 201.189896 3.000000
      vertex 123.512901 201.189896 0.000000
    endloop
  endfacet
  facet normal 0.519240 0.854629 0.000000
    outer loop
      vertex 123.426331 201.242493 3.000000
      vertex 123.512901 201.189896 3.000000
      vertex 123.426331 201.242493 0.000000
    endloop
  endfacet
  facet normal 0.598826 0.800879 0.000000
    outer loop
      vertex 123.345497 201.302933 0.000000
      vertex 123.426331 201.242493 3.000000
      vertex 123.426331 201.242493 0.000000
    endloop
  endfacet
  facet normal 0.598826 0.800879 0.000000
    outer loop
      vertex 123.345497 201.302933 3.000000
      vertex 123.426331 201.242493 3.000000
      vertex 123.345497 201.302933 0.000000
    endloop
  endfacet
  facet normal 0.672567 0.740036 0.000000
    outer loop
      vertex 123.270935 201.370697 0.000000
      vertex 123.345497 201.302933 3.000000
      vertex 123.345497 201.302933 0.000000
    endloop
  endfacet
  facet normal 0.672567 0.740036 0.000000
    outer loop
      vertex 123.270935 201.370697 3.000000
      vertex 123.345497 201.302933 3.000000
      vertex 123.270935 201.370697 0.000000
    endloop
  endfacet
  facet normal 0.740033 0.672571 0.000000
    outer loop
      vertex 123.203163 201.445267 0.000000
      vertex 123.270935 201.370697 3.000000
      vertex 123.270935 201.370697 0.000000
    endloop
  endfacet
  facet normal 0.740033 0.672571 0.000000
    outer loop
      vertex 123.203163 201.445267 3.000000
      vertex 123.270935 201.370697 3.000000
      vertex 123.203163 201.445267 0.000000
    endloop
  endfacet
  facet normal 0.800852 0.598862 0.000000
    outer loop
      vertex 123.142723 201.526093 0.000000
      vertex 123.203163 201.445267 3.000000
      vertex 123.203163 201.445267 0.000000
    endloop
  endfacet
  facet normal 0.800852 0.598862 0.000000
    outer loop
      vertex 123.142723 201.526093 3.000000
      vertex 123.203163 201.445267 3.000000
      vertex 123.142723 201.526093 0.000000
    endloop
  endfacet
  facet normal 0.854649 0.519206 0.000000
    outer loop
      vertex 123.090126 201.612671 0.000000
      vertex 123.142723 201.526093 3.000000
      vertex 123.142723 201.526093 0.000000
    endloop
  endfacet
  facet normal 0.854649 0.519206 0.000000
    outer loop
      vertex 123.090126 201.612671 3.000000
      vertex 123.142723 201.526093 3.000000
      vertex 123.090126 201.612671 0.000000
    endloop
  endfacet
  facet normal 0.900920 0.433984 0.000000
    outer loop
      vertex 123.045914 201.704453 0.000000
      vertex 123.090126 201.612671 3.000000
      vertex 123.090126 201.612671 0.000000
    endloop
  endfacet
  facet normal 0.900920 0.433984 0.000000
    outer loop
      vertex 123.045914 201.704453 3.000000
      vertex 123.090126 201.612671 3.000000
      vertex 123.045914 201.704453 0.000000
    endloop
  endfacet
  facet normal 0.939089 0.343674 0.000000
    outer loop
      vertex 123.010605 201.800934 0.000000
      vertex 123.045914 201.704453 3.000000
      vertex 123.045914 201.704453 0.000000
    endloop
  endfacet
  facet normal 0.939089 0.343674 0.000000
    outer loop
      vertex 123.010605 201.800934 3.000000
      vertex 123.045914 201.704453 3.000000
      vertex 123.010605 201.800934 0.000000
    endloop
  endfacet
  facet normal 0.968479 0.249096 0.000000
    outer loop
      vertex 122.984726 201.901550 0.000000
      vertex 123.010605 201.800934 3.000000
      vertex 123.010605 201.800934 0.000000
    endloop
  endfacet
  facet normal 0.968479 0.249096 0.000000
    outer loop
      vertex 122.984726 201.901550 3.000000
      vertex 123.010605 201.800934 3.000000
      vertex 122.984726 201.901550 0.000000
    endloop
  endfacet
  facet normal 0.988561 0.150823 0.000000
    outer loop
      vertex 122.968819 202.005814 0.000000
      vertex 122.984726 201.901550 3.000000
      vertex 122.984726 201.901550 0.000000
    endloop
  endfacet
  facet normal 0.988561 0.150823 0.000000
    outer loop
      vertex 122.968819 202.005814 3.000000
      vertex 122.984726 201.901550 3.000000
      vertex 122.968819 202.005814 0.000000
    endloop
  endfacet
  facet normal 0.998726 0.050469 0.000000
    outer loop
      vertex 122.963394 202.113159 0.000000
      vertex 122.968819 202.005814 3.000000
      vertex 122.968819 202.005814 0.000000
    endloop
  endfacet
  facet normal 0.998726 0.050469 0.000000
    outer loop
      vertex 122.963394 202.113159 3.000000
      vertex 122.968819 202.005814 3.000000
      vertex 122.963394 202.113159 0.000000
    endloop
  endfacet
  facet normal 0.998726 -0.050461 0.000000
    outer loop
      vertex 122.968819 202.220520 0.000000
      vertex 122.963394 202.113159 3.000000
      vertex 122.963394 202.113159 0.000000
    endloop
  endfacet
  facet normal 0.998726 -0.050461 0.000000
    outer loop
      vertex 122.968819 202.220520 3.000000
      vertex 122.963394 202.113159 3.000000
      vertex 122.968819 202.220520 0.000000
    endloop
  endfacet
  facet normal 0.988561 -0.150823 0.000000
    outer loop
      vertex 122.984726 202.324783 0.000000
      vertex 122.968819 202.220520 3.000000
      vertex 122.968819 202.220520 0.000000
    endloop
  endfacet
  facet normal 0.988561 -0.150823 0.000000
    outer loop
      vertex 122.984726 202.324783 3.000000
      vertex 122.968819 202.220520 3.000000
      vertex 122.984726 202.324783 0.000000
    endloop
  endfacet
  facet normal 0.968479 -0.249096 0.000000
    outer loop
      vertex 123.010605 202.425400 0.000000
      vertex 122.984726 202.324783 3.000000
      vertex 122.984726 202.324783 0.000000
    endloop
  endfacet
  facet normal 0.968479 -0.249096 0.000000
    outer loop
      vertex 123.010605 202.425400 3.000000
      vertex 122.984726 202.324783 3.000000
      vertex 123.010605 202.425400 0.000000
    endloop
  endfacet
  facet normal 0.939071 -0.343722 0.000000
    outer loop
      vertex 123.045914 202.521866 0.000000
      vertex 123.010605 202.425400 3.000000
      vertex 123.010605 202.425400 0.000000
    endloop
  endfacet
  facet normal 0.939071 -0.343722 0.000000
    outer loop
      vertex 123.045914 202.521866 3.000000
      vertex 123.010605 202.425400 3.000000
      vertex 123.045914 202.521866 0.000000
    endloop
  endfacet
  facet normal 0.900949 -0.433926 0.000000
    outer loop
      vertex 123.090126 202.613663 0.000000
      vertex 123.045914 202.521866 3.000000
      vertex 123.045914 202.521866 0.000000
    endloop
  endfacet
  facet normal 0.900949 -0.433926 0.000000
    outer loop
      vertex 123.090126 202.613663 3.000000
      vertex 123.045914 202.521866 3.000000
      vertex 123.090126 202.613663 0.000000
    endloop
  endfacet
  facet normal 0.854608 -0.519273 0.000000
    outer loop
      vertex 123.142723 202.700226 0.000000
      vertex 123.090126 202.613663 3.000000
      vertex 123.090126 202.613663 0.000000
    endloop
  endfacet
  facet normal 0.854608 -0.519273 0.000000
    outer loop
      vertex 123.142723 202.700226 3.000000
      vertex 123.090126 202.613663 3.000000
      vertex 123.142723 202.700226 0.000000
    endloop
  endfacet
  facet normal 0.800906 -0.598790 0.000000
    outer loop
      vertex 123.203163 202.781067 0.000000
      vertex 123.142723 202.700226 3.000000
      vertex 123.142723 202.700226 0.000000
    endloop
  endfacet
  facet normal 0.800906 -0.598790 0.000000
    outer loop
      vertex 123.203163 202.781067 3.000000
      vertex 123.142723 202.700226 3.000000
      vertex 123.203163 202.781067 0.000000
    endloop
  endfacet
  facet normal 0.739964 -0.672646 0.000000
    outer loop
      vertex 123.270935 202.855621 0.000000
      vertex 123.203163 202.781067 3.000000
      vertex 123.203163 202.781067 0.000000
    endloop
  endfacet
  facet normal 0.739964 -0.672646 0.000000
    outer loop
      vertex 123.270935 202.855621 3.000000
      vertex 123.203163 202.781067 3.000000
      vertex 123.270935 202.855621 0.000000
    endloop
  endfacet
  facet normal 0.672650 -0.739961 0.000000
    outer loop
      vertex 123.345497 202.923401 0.000000
      vertex 123.270935 202.855621 3.000000
      vertex 123.270935 202.855621 0.000000
    endloop
  endfacet
  facet normal 0.672650 -0.739961 0.000000
    outer loop
      vertex 123.345497 202.923401 3.000000
      vertex 123.270935 202.855621 3.000000
      vertex 123.345497 202.923401 0.000000
    endloop
  endfacet
  facet normal 0.598826 -0.800879 0.000000
    outer loop
      vertex 123.426331 202.983841 0.000000
      vertex 123.345497 202.923401 3.000000
      vertex 123.345497 202.923401 0.000000
    endloop
  endfacet
  facet normal 0.598826 -0.800879 0.000000
    outer loop
      vertex 123.426331 202.983841 3.000000
      vertex 123.345497 202.923401 3.000000
      vertex 123.426331 202.983841 0.000000
    endloop
  endfacet
  facet normal 0.519240 -0.854629 0.000000
    outer loop
      vertex 123.512901 203.036438 0.000000
      vertex 123.426331 202.983841 3.000000
      vertex 123.426331 202.983841 0.000000
    endloop
  endfacet
  facet normal 0.519240 -0.854629 0.000000
    outer loop
      vertex 123.512901 203.036438 3.000000
      vertex 123.426331 202.983841 3.000000
      vertex 123.512901 203.036438 0.000000
    endloop
  endfacet
  facet normal 0.433894 -0.900964 0.000000
    outer loop
      vertex 123.604691 203.080643 0.000000
      vertex 123.512901 203.036438 3.000000
      vertex 123.512901 203.036438 0.000000
    endloop
  endfacet
  facet normal 0.433894 -0.900964 0.000000
    outer loop
      vertex 123.604691 203.080643 3.000000
      vertex 123.512901 203.036438 3.000000
      vertex 123.604691 203.080643 0.000000
    endloop
  endfacet
  facet normal 0.343722 -0.939071 0.000000
    outer loop
      vertex 123.701157 203.115952 0.000000
      vertex 123.604691 203.080643 3.000000
      vertex 123.604691 203.080643 0.000000
    endloop
  endfacet
  facet normal 0.343722 -0.939071 0.000000
    outer loop
      vertex 123.701157 203.115952 3.000000
      vertex 123.604691 203.080643 3.000000
      vertex 123.701157 203.115952 0.000000
    endloop
  endfacet
  facet normal 0.249078 -0.968483 0.000000
    outer loop
      vertex 123.801781 203.141830 0.000000
      vertex 123.701157 203.115952 3.000000
      vertex 123.701157 203.115952 0.000000
    endloop
  endfacet
  facet normal 0.249078 -0.968483 0.000000
    outer loop
      vertex 123.801781 203.141830 3.000000
      vertex 123.701157 203.115952 3.000000
      vertex 123.801781 203.141830 0.000000
    endloop
  endfacet
  facet normal 0.150905 -0.988548 0.000000
    outer loop
      vertex 123.906036 203.157745 0.000000
      vertex 123.801781 203.141830 3.000000
      vertex 123.801781 203.141830 0.000000
    endloop
  endfacet
  facet normal 0.150905 -0.988548 0.000000
    outer loop
      vertex 123.906036 203.157745 3.000000
      vertex 123.801781 203.141830 3.000000
      vertex 123.906036 203.157745 0.000000
    endloop
  endfacet
  facet normal 0.050391 -0.998730 0.000000
    outer loop
      vertex 124.013397 203.163162 0.000000
      vertex 123.906036 203.157745 3.000000
      vertex 123.906036 203.157745 0.000000
    endloop
  endfacet
  facet normal 0.050391 -0.998730 0.000000
    outer loop
      vertex 124.013397 203.163162 3.000000
      vertex 123.906036 203.157745 3.000000
      vertex 124.013397 203.163162 0.000000
    endloop
  endfacet
  facet normal -0.050394 -0.998729 0.000000
    outer loop
      vertex 124.120750 203.157745 0.000000
      vertex 124.013397 203.163162 3.000000
      vertex 124.013397 203.163162 0.000000
    endloop
  endfacet
  facet normal -0.050394 -0.998729 -0.000000
    outer loop
      vertex 124.120750 203.157745 3.000000
      vertex 124.013397 203.163162 3.000000
      vertex 124.120750 203.157745 0.000000
    endloop
  endfacet
  facet normal -0.150905 -0.988548 0.000000
    outer loop
      vertex 124.225006 203.141830 0.000000
      vertex 124.120750 203.157745 3.000000
      vertex 124.120750 203.157745 0.000000
    endloop
  endfacet
  facet normal -0.150905 -0.988548 -0.000000
    outer loop
      vertex 124.225006 203.141830 3.000000
      vertex 124.120750 203.157745 3.000000
      vertex 124.225006 203.141830 0.000000
    endloop
  endfacet
  facet normal -0.249078 -0.968483 0.000000
    outer loop
      vertex 124.325630 203.115952 0.000000
      vertex 124.225006 203.141830 3.000000
      vertex 124.225006 203.141830 0.000000
    endloop
  endfacet
  facet normal -0.249078 -0.968483 -0.000000
    outer loop
      vertex 124.325630 203.115952 3.000000
      vertex 124.225006 203.141830 3.000000
      vertex 124.325630 203.115952 0.000000
    endloop
  endfacet
  facet normal -0.343698 -0.939080 0.000000
    outer loop
      vertex 124.422104 203.080643 0.000000
      vertex 124.325630 203.115952 3.000000
      vertex 124.325630 203.115952 0.000000
    endloop
  endfacet
  facet normal -0.343698 -0.939080 -0.000000
    outer loop
      vertex 124.422104 203.080643 3.000000
      vertex 124.325630 203.115952 3.000000
      vertex 124.422104 203.080643 0.000000
    endloop
  endfacet
  facet normal -0.433924 -0.900950 0.000000
    outer loop
      vertex 124.513885 203.036438 0.000000
      vertex 124.422104 203.080643 3.000000
      vertex 124.422104 203.080643 0.000000
    endloop
  endfacet
  facet normal -0.433924 -0.900950 -0.000000
    outer loop
      vertex 124.513885 203.036438 3.000000
      vertex 124.422104 203.080643 3.000000
      vertex 124.513885 203.036438 0.000000
    endloop
  endfacet
  facet normal -0.519206 -0.854649 0.000000
    outer loop
      vertex 124.600464 202.983841 0.000000
      vertex 124.513885 203.036438 3.000000
      vertex 124.513885 203.036438 0.000000
    endloop
  endfacet
  facet normal -0.519206 -0.854649 -0.000000
    outer loop
      vertex 124.600464 202.983841 3.000000
      vertex 124.513885 203.036438 3.000000
      vertex 124.600464 202.983841 0.000000
    endloop
  endfacet
  facet normal -0.598862 -0.800852 0.000000
    outer loop
      vertex 124.681290 202.923401 0.000000
      vertex 124.600464 202.983841 3.000000
      vertex 124.600464 202.983841 0.000000
    endloop
  endfacet
  facet normal -0.598862 -0.800852 -0.000000
    outer loop
      vertex 124.681290 202.923401 3.000000
      vertex 124.600464 202.983841 3.000000
      vertex 124.681290 202.923401 0.000000
    endloop
  endfacet
  facet normal -0.672612 -0.739995 0.000000
    outer loop
      vertex 124.755859 202.855621 0.000000
      vertex 124.681290 202.923401 3.000000
      vertex 124.681290 202.923401 0.000000
    endloop
  endfacet
  facet normal -0.672612 -0.739995 -0.000000
    outer loop
      vertex 124.755859 202.855621 3.000000
      vertex 124.681290 202.923401 3.000000
      vertex 124.755859 202.855621 0.000000
    endloop
  endfacet
  facet normal -0.740002 -0.672605 0.000000
    outer loop
      vertex 124.823624 202.781067 0.000000
      vertex 124.755859 202.855621 3.000000
      vertex 124.755859 202.855621 0.000000
    endloop
  endfacet
  facet normal -0.740002 -0.672605 -0.000000
    outer loop
      vertex 124.823624 202.781067 3.000000
      vertex 124.755859 202.855621 3.000000
      vertex 124.823624 202.781067 0.000000
    endloop
  endfacet
  facet normal -0.800870 -0.598838 0.000000
    outer loop
      vertex 124.884071 202.700226 0.000000
      vertex 124.823624 202.781067 3.000000
      vertex 124.823624 202.781067 0.000000
    endloop
  endfacet
  facet normal -0.800870 -0.598838 -0.000000
    outer loop
      vertex 124.884071 202.700226 3.000000
      vertex 124.823624 202.781067 3.000000
      vertex 124.884071 202.700226 0.000000
    endloop
  endfacet
  facet normal -0.854608 -0.519273 0.000000
    outer loop
      vertex 124.936668 202.613663 0.000000
      vertex 124.884071 202.700226 3.000000
      vertex 124.884071 202.700226 0.000000
    endloop
  endfacet
  facet normal -0.854608 -0.519273 -0.000000
    outer loop
      vertex 124.936668 202.613663 3.000000
      vertex 124.884071 202.700226 3.000000
      vertex 124.936668 202.613663 0.000000
    endloop
  endfacet
  facet normal -0.900949 -0.433926 0.000000
    outer loop
      vertex 124.980881 202.521866 0.000000
      vertex 124.936668 202.613663 3.000000
      vertex 124.936668 202.613663 0.000000
    endloop
  endfacet
  facet normal -0.900949 -0.433926 -0.000000
    outer loop
      vertex 124.980881 202.521866 3.000000
      vertex 124.936668 202.613663 3.000000
      vertex 124.980881 202.521866 0.000000
    endloop
  endfacet
  facet normal -0.939071 -0.343722 0.000000
    outer loop
      vertex 125.016190 202.425400 0.000000
      vertex 124.980881 202.521866 3.000000
      vertex 124.980881 202.521866 0.000000
    endloop
  endfacet
  facet normal -0.939071 -0.343722 -0.000000
    outer loop
      vertex 125.016190 202.425400 3.000000
      vertex 124.980881 202.521866 3.000000
      vertex 125.016190 202.425400 0.000000
    endloop
  endfacet
  facet normal -0.968496 -0.249027 0.000000
    outer loop
      vertex 125.042061 202.324783 0.000000
      vertex 125.016190 202.425400 3.000000
      vertex 125.016190 202.425400 0.000000
    endloop
  endfacet
  facet normal -0.968496 -0.249027 -0.000000
    outer loop
      vertex 125.042061 202.324783 3.000000
      vertex 125.016190 202.425400 3.000000
      vertex 125.042061 202.324783 0.000000
    endloop
  endfacet
  facet normal -0.988550 -0.150894 0.000000
    outer loop
      vertex 125.057976 202.220520 0.000000
      vertex 125.042061 202.324783 3.000000
      vertex 125.042061 202.324783 0.000000
    endloop
  endfacet
  facet normal -0.988550 -0.150894 -0.000000
    outer loop
      vertex 125.057976 202.220520 3.000000
      vertex 125.042061 202.324783 3.000000
      vertex 125.057976 202.220520 0.000000
    endloop
  endfacet
  facet normal -0.998730 -0.050391 0.000000
    outer loop
      vertex 125.063393 202.113159 0.000000
      vertex 125.057976 202.220520 3.000000
      vertex 125.057976 202.220520 0.000000
    endloop
  endfacet
  facet normal -0.998730 -0.050391 -0.000000
    outer loop
      vertex 125.063393 202.113159 3.000000
      vertex 125.057976 202.220520 3.000000
      vertex 125.063393 202.113159 0.000000
    endloop
  endfacet
  facet normal -0.998729 0.050394 0.000000
    outer loop
      vertex 169.033630 124.989052 3.000000
      vertex 169.033630 124.989052 0.000000
      vertex 169.028214 124.881699 0.000000
    endloop
  endfacet
  facet normal -0.998729 0.050394 0.000000
    outer loop
      vertex 169.028214 124.881699 3.000000
      vertex 169.033630 124.989052 3.000000
      vertex 169.028214 124.881699 0.000000
    endloop
  endfacet
  facet normal -0.988548 0.150905 0.000000
    outer loop
      vertex 169.012299 124.777443 0.000000
      vertex 169.028214 124.881699 3.000000
      vertex 169.028214 124.881699 0.000000
    endloop
  endfacet
  facet normal -0.988548 0.150905 0.000000
    outer loop
      vertex 169.012299 124.777443 3.000000
      vertex 169.028214 124.881699 3.000000
      vertex 169.012299 124.777443 0.000000
    endloop
  endfacet
  facet normal -0.968488 0.249061 0.000000
    outer loop
      vertex 168.986420 124.676811 0.000000
      vertex 169.012299 124.777443 3.000000
      vertex 169.012299 124.777443 0.000000
    endloop
  endfacet
  facet normal -0.968488 0.249061 0.000000
    outer loop
      vertex 168.986420 124.676811 3.000000
      vertex 169.012299 124.777443 3.000000
      vertex 168.986420 124.676811 0.000000
    endloop
  endfacet
  facet normal -0.939071 0.343722 0.000000
    outer loop
      vertex 168.951111 124.580345 0.000000
      vertex 168.986420 124.676811 3.000000
      vertex 168.986420 124.676811 0.000000
    endloop
  endfacet
  facet normal -0.939071 0.343722 0.000000
    outer loop
      vertex 168.951111 124.580345 3.000000
      vertex 168.986420 124.676811 3.000000
      vertex 168.951111 124.580345 0.000000
    endloop
  endfacet
  facet normal -0.900950 0.433924 0.000000
    outer loop
      vertex 168.906906 124.488564 0.000000
      vertex 168.951111 124.580345 3.000000
      vertex 168.951111 124.580345 0.000000
    endloop
  endfacet
  facet normal -0.900950 0.433924 0.000000
    outer loop
      vertex 168.906906 124.488564 3.000000
      vertex 168.951111 124.580345 3.000000
      vertex 168.906906 124.488564 0.000000
    endloop
  endfacet
  facet normal -0.854649 0.519206 0.000000
    outer loop
      vertex 168.854309 124.401985 0.000000
      vertex 168.906906 124.488564 3.000000
      vertex 168.906906 124.488564 0.000000
    endloop
  endfacet
  facet normal -0.854649 0.519206 0.000000
    outer loop
      vertex 168.854309 124.401985 3.000000
      vertex 168.906906 124.488564 3.000000
      vertex 168.854309 124.401985 0.000000
    endloop
  endfacet
  facet normal -0.800807 0.598923 0.000000
    outer loop
      vertex 168.793854 124.321152 0.000000
      vertex 168.854309 124.401985 3.000000
      vertex 168.854309 124.401985 0.000000
    endloop
  endfacet
  facet normal -0.800807 0.598923 0.000000
    outer loop
      vertex 168.793854 124.321152 3.000000
      vertex 168.854309 124.401985 3.000000
      vertex 168.793854 124.321152 0.000000
    endloop
  endfacet
  facet normal -0.740036 0.672567 0.000000
    outer loop
      vertex 168.726089 124.246590 0.000000
      vertex 168.793854 124.321152 3.000000
      vertex 168.793854 124.321152 0.000000
    endloop
  endfacet
  facet normal -0.740036 0.672567 0.000000
    outer loop
      vertex 168.726089 124.246590 3.000000
      vertex 168.793854 124.321152 3.000000
      vertex 168.726089 124.246590 0.000000
    endloop
  endfacet
  facet normal -0.672571 0.740033 0.000000
    outer loop
      vertex 168.651520 124.178818 0.000000
      vertex 168.726089 124.246590 3.000000
      vertex 168.726089 124.246590 0.000000
    endloop
  endfacet
  facet normal -0.672571 0.740033 0.000000
    outer loop
      vertex 168.651520 124.178818 3.000000
      vertex 168.726089 124.246590 3.000000
      vertex 168.651520 124.178818 0.000000
    endloop
  endfacet
  facet normal -0.598862 0.800852 0.000000
    outer loop
      vertex 168.570694 124.118378 0.000000
      vertex 168.651520 124.178818 3.000000
      vertex 168.651520 124.178818 0.000000
    endloop
  endfacet
  facet normal -0.598862 0.800852 0.000000
    outer loop
      vertex 168.570694 124.118378 3.000000
      vertex 168.651520 124.178818 3.000000
      vertex 168.570694 124.118378 0.000000
    endloop
  endfacet
  facet normal -0.519206 0.854649 0.000000
    outer loop
      vertex 168.484116 124.065781 0.000000
      vertex 168.570694 124.118378 3.000000
      vertex 168.570694 124.118378 0.000000
    endloop
  endfacet
  facet normal -0.519206 0.854649 0.000000
    outer loop
      vertex 168.484116 124.065781 3.000000
      vertex 168.570694 124.118378 3.000000
      vertex 168.484116 124.065781 0.000000
    endloop
  endfacet
  facet normal -0.433984 0.900920 0.000000
    outer loop
      vertex 168.392334 124.021568 0.000000
      vertex 168.484116 124.065781 3.000000
      vertex 168.484116 124.065781 0.000000
    endloop
  endfacet
  facet normal -0.433984 0.900920 0.000000
    outer loop
      vertex 168.392334 124.021568 3.000000
      vertex 168.484116 124.065781 3.000000
      vertex 168.392334 124.021568 0.000000
    endloop
  endfacet
  facet normal -0.343722 0.939071 0.000000
    outer loop
      vertex 168.295868 123.986259 0.000000
      vertex 168.392334 124.021568 3.000000
      vertex 168.392334 124.021568 0.000000
    endloop
  endfacet
  facet normal -0.343722 0.939071 0.000000
    outer loop
      vertex 168.295868 123.986259 3.000000
      vertex 168.392334 124.021568 3.000000
      vertex 168.295868 123.986259 0.000000
    endloop
  endfacet
  facet normal -0.248992 0.968506 0.000000
    outer loop
      vertex 168.195236 123.960388 0.000000
      vertex 168.295868 123.986259 3.000000
      vertex 168.295868 123.986259 0.000000
    endloop
  endfacet
  facet normal -0.248992 0.968506 0.000000
    outer loop
      vertex 168.195236 123.960388 3.000000
      vertex 168.295868 123.986259 3.000000
      vertex 168.195236 123.960388 0.000000
    endloop
  endfacet
  facet normal -0.150915 0.988547 0.000000
    outer loop
      vertex 168.090988 123.944473 0.000000
      vertex 168.195236 123.960388 3.000000
      vertex 168.195236 123.960388 0.000000
    endloop
  endfacet
  facet normal -0.150915 0.988547 0.000000
    outer loop
      vertex 168.090988 123.944473 3.000000
      vertex 168.195236 123.960388 3.000000
      vertex 168.090988 123.944473 0.000000
    endloop
  endfacet
  facet normal -0.050461 0.998726 0.000000
    outer loop
      vertex 167.983627 123.939049 0.000000
      vertex 168.090988 123.944473 3.000000
      vertex 168.090988 123.944473 0.000000
    endloop
  endfacet
  facet normal -0.050461 0.998726 0.000000
    outer loop
      vertex 167.983627 123.939049 3.000000
      vertex 168.090988 123.944473 3.000000
      vertex 167.983627 123.939049 0.000000
    endloop
  endfacet
  facet normal 0.050461 0.998726 0.000000
    outer loop
      vertex 167.876266 123.944473 0.000000
      vertex 167.983627 123.939049 3.000000
      vertex 167.983627 123.939049 0.000000
    endloop
  endfacet
  facet normal 0.050461 0.998726 0.000000
    outer loop
      vertex 167.876266 123.944473 3.000000
      vertex 167.983627 123.939049 3.000000
      vertex 167.876266 123.944473 0.000000
    endloop
  endfacet
  facet normal 0.150915 0.988547 0.000000
    outer loop
      vertex 167.772018 123.960388 0.000000
      vertex 167.876266 123.944473 3.000000
      vertex 167.876266 123.944473 0.000000
    endloop
  endfacet
  facet normal 0.150915 0.988547 0.000000
    outer loop
      vertex 167.772018 123.960388 3.000000
      vertex 167.876266 123.944473 3.000000
      vertex 167.772018 123.960388 0.000000
    endloop
  endfacet
  facet normal 0.248992 0.968506 0.000000
    outer loop
      vertex 167.671387 123.986259 0.000000
      vertex 167.772018 123.960388 3.000000
      vertex 167.772018 123.960388 0.000000
    endloop
  endfacet
  facet normal 0.248992 0.968506 0.000000
    outer loop
      vertex 167.671387 123.986259 3.000000
      vertex 167.772018 123.960388 3.000000
      vertex 167.671387 123.986259 0.000000
    endloop
  endfacet
  facet normal 0.343722 0.939071 0.000000
    outer loop
      vertex 167.574921 124.021568 0.000000
      vertex 167.671387 123.986259 3.000000
      vertex 167.671387 123.986259 0.000000
    endloop
  endfacet
  facet normal 0.343722 0.939071 0.000000
    outer loop
      vertex 167.574921 124.021568 3.000000
      vertex 167.671387 123.986259 3.000000
      vertex 167.574921 124.021568 0.000000
    endloop
  endfacet
  facet normal 0.433984 0.900920 0.000000
    outer loop
      vertex 167.483139 124.065781 0.000000
      vertex 167.574921 124.021568 3.000000
      vertex 167.574921 124.021568 0.000000
    endloop
  endfacet
  facet normal 0.433984 0.900920 0.000000
    outer loop
      vertex 167.483139 124.065781 3.000000
      vertex 167.574921 124.021568 3.000000
      vertex 167.483139 124.065781 0.000000
    endloop
  endfacet
  facet normal 0.519206 0.854649 0.000000
    outer loop
      vertex 167.396561 124.118378 0.000000
      vertex 167.483139 124.065781 3.000000
      vertex 167.483139 124.065781 0.000000
    endloop
  endfacet
  facet normal 0.519206 0.854649 0.000000
    outer loop
      vertex 167.396561 124.118378 3.000000
      vertex 167.483139 124.065781 3.000000
      vertex 167.396561 124.118378 0.000000
    endloop
  endfacet
  facet normal 0.598862 0.800852 0.000000
    outer loop
      vertex 167.315735 124.178818 0.000000
      vertex 167.396561 124.118378 3.000000
      vertex 167.396561 124.118378 0.000000
    endloop
  endfacet
  facet normal 0.598862 0.800852 0.000000
    outer loop
      vertex 167.315735 124.178818 3.000000
      vertex 167.396561 124.118378 3.000000
      vertex 167.315735 124.178818 0.000000
    endloop
  endfacet
  facet normal 0.672571 0.740033 0.000000
    outer loop
      vertex 167.241165 124.246590 0.000000
      vertex 167.315735 124.178818 3.000000
      vertex 167.315735 124.178818 0.000000
    endloop
  endfacet
  facet normal 0.672571 0.740033 0.000000
    outer loop
      vertex 167.241165 124.246590 3.000000
      vertex 167.315735 124.178818 3.000000
      vertex 167.241165 124.246590 0.000000
    endloop
  endfacet
  facet normal 0.740036 0.672567 0.000000
    outer loop
      vertex 167.173401 124.321152 0.000000
      vertex 167.241165 124.246590 3.000000
      vertex 167.241165 124.246590 0.000000
    endloop
  endfacet
  facet normal 0.740036 0.672567 0.000000
    outer loop
      vertex 167.173401 124.321152 3.000000
      vertex 167.241165 124.246590 3.000000
      vertex 167.173401 124.321152 0.000000
    endloop
  endfacet
  facet normal 0.800807 0.598923 0.000000
    outer loop
      vertex 167.112946 124.401985 0.000000
      vertex 167.173401 124.321152 3.000000
      vertex 167.173401 124.321152 0.000000
    endloop
  endfacet
  facet normal 0.800807 0.598923 0.000000
    outer loop
      vertex 167.112946 124.401985 3.000000
      vertex 167.173401 124.321152 3.000000
      vertex 167.112946 124.401985 0.000000
    endloop
  endfacet
  facet normal 0.854716 0.519096 0.000000
    outer loop
      vertex 167.060364 124.488564 0.000000
      vertex 167.112946 124.401985 3.000000
      vertex 167.112946 124.401985 0.000000
    endloop
  endfacet
  facet normal 0.854716 0.519096 0.000000
    outer loop
      vertex 167.060364 124.488564 3.000000
      vertex 167.112946 124.401985 3.000000
      vertex 167.060364 124.488564 0.000000
    endloop
  endfacet
  facet normal 0.900891 0.434045 0.000000
    outer loop
      vertex 167.016144 124.580345 0.000000
      vertex 167.060364 124.488564 3.000000
      vertex 167.060364 124.488564 0.000000
    endloop
  endfacet
  facet normal 0.900891 0.434045 0.000000
    outer loop
      vertex 167.016144 124.580345 3.000000
      vertex 167.060364 124.488564 3.000000
      vertex 167.016144 124.580345 0.000000
    endloop
  endfacet
  facet normal 0.939071 0.343722 0.000000
    outer loop
      vertex 166.980835 124.676811 0.000000
      vertex 167.016144 124.580345 3.000000
      vertex 167.016144 124.580345 0.000000
    endloop
  endfacet
  facet normal 0.939071 0.343722 0.000000
    outer loop
      vertex 166.980835 124.676811 3.000000
      vertex 167.016144 124.580345 3.000000
      vertex 166.980835 124.676811 0.000000
    endloop
  endfacet
  facet normal 0.968488 0.249061 0.000000
    outer loop
      vertex 166.954956 124.777443 0.000000
      vertex 166.980835 124.676811 3.000000
      vertex 166.980835 124.676811 0.000000
    endloop
  endfacet
  facet normal 0.968488 0.249061 0.000000
    outer loop
      vertex 166.954956 124.777443 3.000000
      vertex 166.980835 124.676811 3.000000
      vertex 166.954956 124.777443 0.000000
    endloop
  endfacet
  facet normal 0.988570 0.150763 0.000000
    outer loop
      vertex 166.939056 124.881699 0.000000
      vertex 166.954956 124.777443 3.000000
      vertex 166.954956 124.777443 0.000000
    endloop
  endfacet
  facet normal 0.988570 0.150763 0.000000
    outer loop
      vertex 166.939056 124.881699 3.000000
      vertex 166.954956 124.777443 3.000000
      vertex 166.939056 124.881699 0.000000
    endloop
  endfacet
  facet normal 0.998722 0.050536 0.000000
    outer loop
      vertex 166.933624 124.989052 0.000000
      vertex 166.939056 124.881699 3.000000
      vertex 166.939056 124.881699 0.000000
    endloop
  endfacet
  facet normal 0.998722 0.050536 0.000000
    outer loop
      vertex 166.933624 124.989052 3.000000
      vertex 166.939056 124.881699 3.000000
      vertex 166.933624 124.989052 0.000000
    endloop
  endfacet
  facet normal 0.998722 -0.050536 0.000000
    outer loop
      vertex 166.939056 125.096405 0.000000
      vertex 166.933624 124.989052 3.000000
      vertex 166.933624 124.989052 0.000000
    endloop
  endfacet
  facet normal 0.998722 -0.050536 0.000000
    outer loop
      vertex 166.939056 125.096405 3.000000
      vertex 166.933624 124.989052 3.000000
      vertex 166.939056 125.096405 0.000000
    endloop
  endfacet
  facet normal 0.988570 -0.150763 0.000000
    outer loop
      vertex 166.954956 125.200661 0.000000
      vertex 166.939056 125.096405 3.000000
      vertex 166.939056 125.096405 0.000000
    endloop
  endfacet
  facet normal 0.988570 -0.150763 0.000000
    outer loop
      vertex 166.954956 125.200661 3.000000
      vertex 166.939056 125.096405 3.000000
      vertex 166.954956 125.200661 0.000000
    endloop
  endfacet
  facet normal 0.968488 -0.249061 0.000000
    outer loop
      vertex 166.980835 125.301292 0.000000
      vertex 166.954956 125.200661 3.000000
      vertex 166.954956 125.200661 0.000000
    endloop
  endfacet
  facet normal 0.968488 -0.249061 0.000000
    outer loop
      vertex 166.980835 125.301292 3.000000
      vertex 166.954956 125.200661 3.000000
      vertex 166.980835 125.301292 0.000000
    endloop
  endfacet
  facet normal 0.939071 -0.343722 0.000000
    outer loop
      vertex 167.016144 125.397758 0.000000
      vertex 166.980835 125.301292 3.000000
      vertex 166.980835 125.301292 0.000000
    endloop
  endfacet
  facet normal 0.939071 -0.343722 0.000000
    outer loop
      vertex 167.016144 125.397758 3.000000
      vertex 166.980835 125.301292 3.000000
      vertex 167.016144 125.397758 0.000000
    endloop
  endfacet
  facet normal 0.900905 -0.434016 0.000000
    outer loop
      vertex 167.060364 125.489548 0.000000
      vertex 167.016144 125.397758 3.000000
      vertex 167.016144 125.397758 0.000000
    endloop
  endfacet
  facet normal 0.900905 -0.434016 0.000000
    outer loop
      vertex 167.060364 125.489548 3.000000
      vertex 167.016144 125.397758 3.000000
      vertex 167.060364 125.489548 0.000000
    endloop
  endfacet
  facet normal 0.854696 -0.519129 0.000000
    outer loop
      vertex 167.112946 125.576118 0.000000
      vertex 167.060364 125.489548 3.000000
      vertex 167.060364 125.489548 0.000000
    endloop
  endfacet
  facet normal 0.854696 -0.519129 0.000000
    outer loop
      vertex 167.112946 125.576118 3.000000
      vertex 167.060364 125.489548 3.000000
      vertex 167.112946 125.576118 0.000000
    endloop
  endfacet
  facet normal 0.800807 -0.598923 0.000000
    outer loop
      vertex 167.173401 125.656952 0.000000
      vertex 167.112946 125.576118 3.000000
      vertex 167.112946 125.576118 0.000000
    endloop
  endfacet
  facet normal 0.800807 -0.598923 0.000000
    outer loop
      vertex 167.173401 125.656952 3.000000
      vertex 167.112946 125.576118 3.000000
      vertex 167.173401 125.656952 0.000000
    endloop
  endfacet
  facet normal 0.740036 -0.672567 0.000000
    outer loop
      vertex 167.241165 125.731514 0.000000
      vertex 167.173401 125.656952 3.000000
      vertex 167.173401 125.656952 0.000000
    endloop
  endfacet
  facet normal 0.740036 -0.672567 0.000000
    outer loop
      vertex 167.241165 125.731514 3.000000
      vertex 167.173401 125.656952 3.000000
      vertex 167.241165 125.731514 0.000000
    endloop
  endfacet
  facet normal 0.672571 -0.740033 0.000000
    outer loop
      vertex 167.315735 125.799286 0.000000
      vertex 167.241165 125.731514 3.000000
      vertex 167.241165 125.731514 0.000000
    endloop
  endfacet
  facet normal 0.672571 -0.740033 0.000000
    outer loop
      vertex 167.315735 125.799286 3.000000
      vertex 167.241165 125.731514 3.000000
      vertex 167.315735 125.799286 0.000000
    endloop
  endfacet
  facet normal 0.598862 -0.800852 0.000000
    outer loop
      vertex 167.396561 125.859726 0.000000
      vertex 167.315735 125.799286 3.000000
      vertex 167.315735 125.799286 0.000000
    endloop
  endfacet
  facet normal 0.598862 -0.800852 0.000000
    outer loop
      vertex 167.396561 125.859726 3.000000
      vertex 167.315735 125.799286 3.000000
      vertex 167.396561 125.859726 0.000000
    endloop
  endfacet
  facet normal 0.519206 -0.854649 0.000000
    outer loop
      vertex 167.483139 125.912323 0.000000
      vertex 167.396561 125.859726 3.000000
      vertex 167.396561 125.859726 0.000000
    endloop
  endfacet
  facet normal 0.519206 -0.854649 0.000000
    outer loop
      vertex 167.483139 125.912323 3.000000
      vertex 167.396561 125.859726 3.000000
      vertex 167.483139 125.912323 0.000000
    endloop
  endfacet
  facet normal 0.433984 -0.900920 0.000000
    outer loop
      vertex 167.574921 125.956535 0.000000
      vertex 167.483139 125.912323 3.000000
      vertex 167.483139 125.912323 0.000000
    endloop
  endfacet
  facet normal 0.433984 -0.900920 0.000000
    outer loop
      vertex 167.574921 125.956535 3.000000
      vertex 167.483139 125.912323 3.000000
      vertex 167.574921 125.956535 0.000000
    endloop
  endfacet
  facet normal 0.343722 -0.939071 0.000000
    outer loop
      vertex 167.671387 125.991844 0.000000
      vertex 167.574921 125.956535 3.000000
      vertex 167.574921 125.956535 0.000000
    endloop
  endfacet
  facet normal 0.343722 -0.939071 0.000000
    outer loop
      vertex 167.671387 125.991844 3.000000
      vertex 167.574921 125.956535 3.000000
      vertex 167.671387 125.991844 0.000000
    endloop
  endfacet
  facet normal 0.249061 -0.968488 0.000000
    outer loop
      vertex 167.772018 126.017723 0.000000
      vertex 167.671387 125.991844 3.000000
      vertex 167.671387 125.991844 0.000000
    endloop
  endfacet
  facet normal 0.249061 -0.968488 0.000000
    outer loop
      vertex 167.772018 126.017723 3.000000
      vertex 167.671387 125.991844 3.000000
      vertex 167.772018 126.017723 0.000000
    endloop
  endfacet
  facet normal 0.150845 -0.988558 0.000000
    outer loop
      vertex 167.876266 126.033630 0.000000
      vertex 167.772018 126.017723 3.000000
      vertex 167.772018 126.017723 0.000000
    endloop
  endfacet
  facet normal 0.150845 -0.988558 0.000000
    outer loop
      vertex 167.876266 126.033630 3.000000
      vertex 167.772018 126.017723 3.000000
      vertex 167.876266 126.033630 0.000000
    endloop
  endfacet
  facet normal 0.050461 -0.998726 0.000000
    outer loop
      vertex 167.983627 126.039055 0.000000
      vertex 167.876266 126.033630 3.000000
      vertex 167.876266 126.033630 0.000000
    endloop
  endfacet
  facet normal 0.050461 -0.998726 0.000000
    outer loop
      vertex 167.983627 126.039055 3.000000
      vertex 167.876266 126.033630 3.000000
      vertex 167.983627 126.039055 0.000000
    endloop
  endfacet
  facet normal -0.050461 -0.998726 0.000000
    outer loop
      vertex 168.090988 126.033630 0.000000
      vertex 167.983627 126.039055 3.000000
      vertex 167.983627 126.039055 0.000000
    endloop
  endfacet
  facet normal -0.050461 -0.998726 -0.000000
    outer loop
      vertex 168.090988 126.033630 3.000000
      vertex 167.983627 126.039055 3.000000
      vertex 168.090988 126.033630 0.000000
    endloop
  endfacet
  facet normal -0.150845 -0.988558 0.000000
    outer loop
      vertex 168.195236 126.017723 0.000000
      vertex 168.090988 126.033630 3.000000
      vertex 168.090988 126.033630 0.000000
    endloop
  endfacet
  facet normal -0.150845 -0.988558 -0.000000
    outer loop
      vertex 168.195236 126.017723 3.000000
      vertex 168.090988 126.033630 3.000000
      vertex 168.195236 126.017723 0.000000
    endloop
  endfacet
  facet normal -0.249061 -0.968488 0.000000
    outer loop
      vertex 168.295868 125.991844 0.000000
      vertex 168.195236 126.017723 3.000000
      vertex 168.195236 126.017723 0.000000
    endloop
  endfacet
  facet normal -0.249061 -0.968488 -0.000000
    outer loop
      vertex 168.295868 125.991844 3.000000
      vertex 168.195236 126.017723 3.000000
      vertex 168.295868 125.991844 0.000000
    endloop
  endfacet
  facet normal -0.343722 -0.939071 0.000000
    outer loop
      vertex 168.392334 125.956535 0.000000
      vertex 168.295868 125.991844 3.000000
      vertex 168.295868 125.991844 0.000000
    endloop
  endfacet
  facet normal -0.343722 -0.939071 -0.000000
    outer loop
      vertex 168.392334 125.956535 3.000000
      vertex 168.295868 125.991844 3.000000
      vertex 168.392334 125.956535 0.000000
    endloop
  endfacet
  facet normal -0.433984 -0.900920 0.000000
    outer loop
      vertex 168.484116 125.912323 0.000000
      vertex 168.392334 125.956535 3.000000
      vertex 168.392334 125.956535 0.000000
    endloop
  endfacet
  facet normal -0.433984 -0.900920 -0.000000
    outer loop
      vertex 168.484116 125.912323 3.000000
      vertex 168.392334 125.956535 3.000000
      vertex 168.484116 125.912323 0.000000
    endloop
  endfacet
  facet normal -0.519206 -0.854649 0.000000
    outer loop
      vertex 168.570694 125.859726 0.000000
      vertex 168.484116 125.912323 3.000000
      vertex 168.484116 125.912323 0.000000
    endloop
  endfacet
  facet normal -0.519206 -0.854649 -0.000000
    outer loop
      vertex 168.570694 125.859726 3.000000
      vertex 168.484116 125.912323 3.000000
      vertex 168.570694 125.859726 0.000000
    endloop
  endfacet
  facet normal -0.598862 -0.800852 0.000000
    outer loop
      vertex 168.651520 125.799286 0.000000
      vertex 168.570694 125.859726 3.000000
      vertex 168.570694 125.859726 0.000000
    endloop
  endfacet
  facet normal -0.598862 -0.800852 -0.000000
    outer loop
      vertex 168.651520 125.799286 3.000000
      vertex 168.570694 125.859726 3.000000
      vertex 168.651520 125.799286 0.000000
    endloop
  endfacet
  facet normal -0.672571 -0.740033 0.000000
    outer loop
      vertex 168.726089 125.731514 0.000000
      vertex 168.651520 125.799286 3.000000
      vertex 168.651520 125.799286 0.000000
    endloop
  endfacet
  facet normal -0.672571 -0.740033 -0.000000
    outer loop
      vertex 168.726089 125.731514 3.000000
      vertex 168.651520 125.799286 3.000000
      vertex 168.726089 125.731514 0.000000
    endloop
  endfacet
  facet normal -0.740036 -0.672567 0.000000
    outer loop
      vertex 168.793854 125.656952 0.000000
      vertex 168.726089 125.731514 3.000000
      vertex 168.726089 125.731514 0.000000
    endloop
  endfacet
  facet normal -0.740036 -0.672567 -0.000000
    outer loop
      vertex 168.793854 125.656952 3.000000
      vertex 168.726089 125.731514 3.000000
      vertex 168.793854 125.656952 0.000000
    endloop
  endfacet
  facet normal -0.800807 -0.598923 0.000000
    outer loop
      vertex 168.854309 125.576118 0.000000
      vertex 168.793854 125.656952 3.000000
      vertex 168.793854 125.656952 0.000000
    endloop
  endfacet
  facet normal -0.800807 -0.598923 -0.000000
    outer loop
      vertex 168.854309 125.576118 3.000000
      vertex 168.793854 125.656952 3.000000
      vertex 168.854309 125.576118 0.000000
    endloop
  endfacet
  facet normal -0.854629 -0.519240 0.000000
    outer loop
      vertex 168.906906 125.489548 0.000000
      vertex 168.854309 125.576118 3.000000
      vertex 168.854309 125.576118 0.000000
    endloop
  endfacet
  facet normal -0.854629 -0.519240 -0.000000
    outer loop
      vertex 168.906906 125.489548 3.000000
      vertex 168.854309 125.576118 3.000000
      vertex 168.906906 125.489548 0.000000
    endloop
  endfacet
  facet normal -0.900964 -0.433894 0.000000
    outer loop
      vertex 168.951111 125.397758 0.000000
      vertex 168.906906 125.489548 3.000000
      vertex 168.906906 125.489548 0.000000
    endloop
  endfacet
  facet normal -0.900964 -0.433894 -0.000000
    outer loop
      vertex 168.951111 125.397758 3.000000
      vertex 168.906906 125.489548 3.000000
      vertex 168.951111 125.397758 0.000000
    endloop
  endfacet
  facet normal -0.939071 -0.343722 0.000000
    outer loop
      vertex 168.986420 125.301292 0.000000
      vertex 168.951111 125.397758 3.000000
      vertex 168.951111 125.397758 0.000000
    endloop
  endfacet
  facet normal -0.939071 -0.343722 -0.000000
    outer loop
      vertex 168.986420 125.301292 3.000000
      vertex 168.951111 125.397758 3.000000
      vertex 168.986420 125.301292 0.000000
    endloop
  endfacet
  facet normal -0.968488 -0.249061 0.000000
    outer loop
      vertex 169.012299 125.200661 0.000000
      vertex 168.986420 125.301292 3.000000
      vertex 168.986420 125.301292 0.000000
    endloop
  endfacet
  facet normal -0.968488 -0.249061 -0.000000
    outer loop
      vertex 169.012299 125.200661 3.000000
      vertex 168.986420 125.301292 3.000000
      vertex 169.012299 125.200661 0.000000
    endloop
  endfacet
  facet normal -0.988548 -0.150905 0.000000
    outer loop
      vertex 169.028214 125.096405 0.000000
      vertex 169.012299 125.200661 3.000000
      vertex 169.012299 125.200661 0.000000
    endloop
  endfacet
  facet normal -0.988548 -0.150905 -0.000000
    outer loop
      vertex 169.028214 125.096405 3.000000
      vertex 169.012299 125.200661 3.000000
      vertex 169.028214 125.096405 0.000000
    endloop
  endfacet
  facet normal -0.998729 -0.050394 0.000000
    outer loop
      vertex 169.033630 124.989052 0.000000
      vertex 169.028214 125.096405 3.000000
      vertex 169.028214 125.096405 0.000000
    endloop
  endfacet
  facet normal -0.998729 -0.050394 -0.000000
    outer loop
      vertex 169.033630 124.989052 3.000000
      vertex 169.028214 125.096405 3.000000
      vertex 169.033630 124.989052 0.000000
    endloop
  endfacet
  facet normal -0.998728 0.050433 0.000000
    outer loop
      vertex 34.102001 190.612549 3.000000
      vertex 34.102001 190.612549 0.000000
      vertex 34.096581 190.505203 0.000000
    endloop
  endfacet
  facet normal -0.998728 0.050433 0.000000
    outer loop
      vertex 34.096581 190.505203 3.000000
      vertex 34.102001 190.612549 3.000000
      vertex 34.096581 190.505203 0.000000
    endloop
  endfacet
  facet normal -0.988555 0.150858 0.000000
    outer loop
      vertex 34.080669 190.400940 0.000000
      vertex 34.096581 190.505203 3.000000
      vertex 34.096581 190.505203 0.000000
    endloop
  endfacet
  facet normal -0.988555 0.150858 0.000000
    outer loop
      vertex 34.080669 190.400940 3.000000
      vertex 34.096581 190.505203 3.000000
      vertex 34.080669 190.400940 0.000000
    endloop
  endfacet
  facet normal -0.968506 0.248992 0.000000
    outer loop
      vertex 34.054798 190.300308 0.000000
      vertex 34.080669 190.400940 3.000000
      vertex 34.080669 190.400940 0.000000
    endloop
  endfacet
  facet normal -0.968506 0.248992 0.000000
    outer loop
      vertex 34.054798 190.300308 3.000000
      vertex 34.080669 190.400940 3.000000
      vertex 34.054798 190.300308 0.000000
    endloop
  endfacet
  facet normal -0.939071 0.343722 0.000000
    outer loop
      vertex 34.019489 190.203842 0.000000
      vertex 34.054798 190.300308 3.000000
      vertex 34.054798 190.300308 0.000000
    endloop
  endfacet
  facet normal -0.939071 0.343722 0.000000
    outer loop
      vertex 34.019489 190.203842 3.000000
      vertex 34.054798 190.300308 3.000000
      vertex 34.019489 190.203842 0.000000
    endloop
  endfacet
  facet normal -0.900906 0.434015 0.000000
    outer loop
      vertex 33.975273 190.112061 0.000000
      vertex 34.019489 190.203842 3.000000
      vertex 34.019489 190.203842 0.000000
    endloop
  endfacet
  facet normal -0.900906 0.434015 0.000000
    outer loop
      vertex 33.975273 190.112061 3.000000
      vertex 34.019489 190.203842 3.000000
      vertex 33.975273 190.112061 0.000000
    endloop
  endfacet
  facet normal -0.854666 0.519179 0.000000
    outer loop
      vertex 33.922680 190.025482 0.000000
      vertex 33.975273 190.112061 3.000000
      vertex 33.975273 190.112061 0.000000
    endloop
  endfacet
  facet normal -0.854666 0.519179 0.000000
    outer loop
      vertex 33.922680 190.025482 3.000000
      vertex 33.975273 190.112061 3.000000
      vertex 33.922680 190.025482 0.000000
    endloop
  endfacet
  facet normal -0.800816 0.598911 0.000000
    outer loop
      vertex 33.862232 189.944656 0.000000
      vertex 33.922680 190.025482 3.000000
      vertex 33.922680 190.025482 0.000000
    endloop
  endfacet
  facet normal -0.800816 0.598911 0.000000
    outer loop
      vertex 33.862232 189.944656 3.000000
      vertex 33.922680 190.025482 3.000000
      vertex 33.862232 189.944656 0.000000
    endloop
  endfacet
  facet normal -0.740051 0.672550 0.000000
    outer loop
      vertex 33.794464 189.870087 0.000000
      vertex 33.862232 189.944656 3.000000
      vertex 33.862232 189.944656 0.000000
    endloop
  endfacet
  facet normal -0.740051 0.672550 0.000000
    outer loop
      vertex 33.794464 189.870087 3.000000
      vertex 33.862232 189.944656 3.000000
      vertex 33.794464 189.870087 0.000000
    endloop
  endfacet
  facet normal -0.672548 0.740053 0.000000
    outer loop
      vertex 33.719898 189.802322 0.000000
      vertex 33.794464 189.870087 3.000000
      vertex 33.794464 189.870087 0.000000
    endloop
  endfacet
  facet normal -0.672548 0.740053 0.000000
    outer loop
      vertex 33.719898 189.802322 3.000000
      vertex 33.794464 189.870087 3.000000
      vertex 33.719898 189.802322 0.000000
    endloop
  endfacet
  facet normal -0.598844 0.800865 0.000000
    outer loop
      vertex 33.639069 189.741882 0.000000
      vertex 33.719898 189.802322 3.000000
      vertex 33.719898 189.802322 0.000000
    endloop
  endfacet
  facet normal -0.598844 0.800865 0.000000
    outer loop
      vertex 33.639069 189.741882 3.000000
      vertex 33.719898 189.802322 3.000000
      vertex 33.639069 189.741882 0.000000
    endloop
  endfacet
  facet normal -0.519223 0.854639 0.000000
    outer loop
      vertex 33.552494 189.689285 0.000000
      vertex 33.639069 189.741882 3.000000
      vertex 33.639069 189.741882 0.000000
    endloop
  endfacet
  facet normal -0.519223 0.854639 0.000000
    outer loop
      vertex 33.552494 189.689285 3.000000
      vertex 33.639069 189.741882 3.000000
      vertex 33.552494 189.689285 0.000000
    endloop
  endfacet
  facet normal -0.434031 0.900898 0.000000
    outer loop
      vertex 33.460709 189.645065 0.000000
      vertex 33.552494 189.689285 3.000000
      vertex 33.552494 189.689285 0.000000
    endloop
  endfacet
  facet normal -0.434031 0.900898 0.000000
    outer loop
      vertex 33.460709 189.645065 3.000000
      vertex 33.552494 189.689285 3.000000
      vertex 33.460709 189.645065 0.000000
    endloop
  endfacet
  facet normal -0.343710 0.939076 0.000000
    outer loop
      vertex 33.364239 189.609756 0.000000
      vertex 33.460709 189.645065 3.000000
      vertex 33.460709 189.645065 0.000000
    endloop
  endfacet
  facet normal -0.343710 0.939076 0.000000
    outer loop
      vertex 33.364239 189.609756 3.000000
      vertex 33.460709 189.645065 3.000000
      vertex 33.364239 189.609756 0.000000
    endloop
  endfacet
  facet normal -0.249078 0.968483 0.000000
    outer loop
      vertex 33.263615 189.583878 0.000000
      vertex 33.364239 189.609756 3.000000
      vertex 33.364239 189.609756 0.000000
    endloop
  endfacet
  facet normal -0.249078 0.968483 0.000000
    outer loop
      vertex 33.263615 189.583878 3.000000
      vertex 33.364239 189.609756 3.000000
      vertex 33.263615 189.583878 0.000000
    endloop
  endfacet
  facet normal -0.150763 0.988570 0.000000
    outer loop
      vertex 33.159359 189.567978 0.000000
      vertex 33.263615 189.583878 3.000000
      vertex 33.263615 189.583878 0.000000
    endloop
  endfacet
  facet normal -0.150763 0.988570 0.000000
    outer loop
      vertex 33.159359 189.567978 3.000000
      vertex 33.263615 189.583878 3.000000
      vertex 33.159359 189.567978 0.000000
    endloop
  endfacet
  facet normal -0.050534 0.998722 0.000000
    outer loop
      vertex 33.052002 189.562546 0.000000
      vertex 33.159359 189.567978 3.000000
      vertex 33.159359 189.567978 0.000000
    endloop
  endfacet
  facet normal -0.050534 0.998722 0.000000
    outer loop
      vertex 33.052002 189.562546 3.000000
      vertex 33.159359 189.567978 3.000000
      vertex 33.052002 189.562546 0.000000
    endloop
  endfacet
  facet normal 0.050534 0.998722 0.000000
    outer loop
      vertex 32.944645 189.567978 0.000000
      vertex 33.052002 189.562546 3.000000
      vertex 33.052002 189.562546 0.000000
    endloop
  endfacet
  facet normal 0.050534 0.998722 0.000000
    outer loop
      vertex 32.944645 189.567978 3.000000
      vertex 33.052002 189.562546 3.000000
      vertex 32.944645 189.567978 0.000000
    endloop
  endfacet
  facet normal 0.150763 0.988570 0.000000
    outer loop
      vertex 32.840389 189.583878 0.000000
      vertex 32.944645 189.567978 3.000000
      vertex 32.944645 189.567978 0.000000
    endloop
  endfacet
  facet normal 0.150763 0.988570 0.000000
    outer loop
      vertex 32.840389 189.583878 3.000000
      vertex 32.944645 189.567978 3.000000
      vertex 32.840389 189.583878 0.000000
    endloop
  endfacet
  facet normal 0.249078 0.968483 0.000000
    outer loop
      vertex 32.739765 189.609756 0.000000
      vertex 32.840389 189.583878 3.000000
      vertex 32.840389 189.583878 0.000000
    endloop
  endfacet
  facet normal 0.249078 0.968483 0.000000
    outer loop
      vertex 32.739765 189.609756 3.000000
      vertex 32.840389 189.583878 3.000000
      vertex 32.739765 189.609756 0.000000
    endloop
  endfacet
  facet normal 0.343710 0.939076 0.000000
    outer loop
      vertex 32.643295 189.645065 0.000000
      vertex 32.739765 189.609756 3.000000
      vertex 32.739765 189.609756 0.000000
    endloop
  endfacet
  facet normal 0.343710 0.939076 0.000000
    outer loop
      vertex 32.643295 189.645065 3.000000
      vertex 32.739765 189.609756 3.000000
      vertex 32.643295 189.645065 0.000000
    endloop
  endfacet
  facet normal 0.434031 0.900898 0.000000
    outer loop
      vertex 32.551510 189.689285 0.000000
      vertex 32.643295 189.645065 3.000000
      vertex 32.643295 189.645065 0.000000
    endloop
  endfacet
  facet normal 0.434031 0.900898 0.000000
    outer loop
      vertex 32.551510 189.689285 3.000000
      vertex 32.643295 189.645065 3.000000
      vertex 32.551510 189.689285 0.000000
    endloop
  endfacet
  facet normal 0.519240 0.854629 0.000000
    outer loop
      vertex 32.464939 189.741882 0.000000
      vertex 32.551510 189.689285 3.000000
      vertex 32.551510 189.689285 0.000000
    endloop
  endfacet
  facet normal 0.519240 0.854629 0.000000
    outer loop
      vertex 32.464939 189.741882 3.000000
      vertex 32.551510 189.689285 3.000000
      vertex 32.464939 189.741882 0.000000
    endloop
  endfacet
  facet normal 0.598826 0.800879 0.000000
    outer loop
      vertex 32.384106 189.802322 0.000000
      vertex 32.464939 189.741882 3.000000
      vertex 32.464939 189.741882 0.000000
    endloop
  endfacet
  facet normal 0.598826 0.800879 0.000000
    outer loop
      vertex 32.384106 189.802322 3.000000
      vertex 32.464939 189.741882 3.000000
      vertex 32.384106 189.802322 0.000000
    endloop
  endfacet
  facet normal 0.672548 0.740053 0.000000
    outer loop
      vertex 32.309540 189.870087 0.000000
      vertex 32.384106 189.802322 3.000000
      vertex 32.384106 189.802322 0.000000
    endloop
  endfacet
  facet normal 0.672548 0.740053 0.000000
    outer loop
      vertex 32.309540 189.870087 3.000000
      vertex 32.384106 189.802322 3.000000
      vertex 32.309540 189.870087 0.000000
    endloop
  endfacet
  facet normal 0.740051 0.672550 0.000000
    outer loop
      vertex 32.241772 189.944656 0.000000
      vertex 32.309540 189.870087 3.000000
      vertex 32.309540 189.870087 0.000000
    endloop
  endfacet
  facet normal 0.740051 0.672550 0.000000
    outer loop
      vertex 32.241772 189.944656 3.000000
      vertex 32.309540 189.870087 3.000000
      vertex 32.241772 189.944656 0.000000
    endloop
  endfacet
  facet normal 0.800816 0.598911 0.000000
    outer loop
      vertex 32.181324 190.025482 0.000000
      vertex 32.241772 189.944656 3.000000
      vertex 32.241772 189.944656 0.000000
    endloop
  endfacet
  facet normal 0.800816 0.598911 0.000000
    outer loop
      vertex 32.181324 190.025482 3.000000
      vertex 32.241772 189.944656 3.000000
      vertex 32.181324 190.025482 0.000000
    endloop
  endfacet
  facet normal 0.854666 0.519179 0.000000
    outer loop
      vertex 32.128731 190.112061 0.000000
      vertex 32.181324 190.025482 3.000000
      vertex 32.181324 190.025482 0.000000
    endloop
  endfacet
  facet normal 0.854666 0.519179 0.000000
    outer loop
      vertex 32.128731 190.112061 3.000000
      vertex 32.181324 190.025482 3.000000
      vertex 32.128731 190.112061 0.000000
    endloop
  endfacet
  facet normal 0.900920 0.433984 0.000000
    outer loop
      vertex 32.084518 190.203842 0.000000
      vertex 32.128731 190.112061 3.000000
      vertex 32.128731 190.112061 0.000000
    endloop
  endfacet
  facet normal 0.900920 0.433984 0.000000
    outer loop
      vertex 32.084518 190.203842 3.000000
      vertex 32.128731 190.112061 3.000000
      vertex 32.084518 190.203842 0.000000
    endloop
  endfacet
  facet normal 0.939071 0.343722 0.000000
    outer loop
      vertex 32.049210 190.300308 0.000000
      vertex 32.084518 190.203842 3.000000
      vertex 32.084518 190.203842 0.000000
    endloop
  endfacet
  facet normal 0.939071 0.343722 0.000000
    outer loop
      vertex 32.049210 190.300308 3.000000
      vertex 32.084518 190.203842 3.000000
      vertex 32.049210 190.300308 0.000000
    endloop
  endfacet
  facet normal 0.968497 0.249026 0.000000
    outer loop
      vertex 32.023335 190.400940 0.000000
      vertex 32.049210 190.300308 3.000000
      vertex 32.049210 190.300308 0.000000
    endloop
  endfacet
  facet normal 0.968497 0.249026 0.000000
    outer loop
      vertex 32.023335 190.400940 3.000000
      vertex 32.049210 190.300308 3.000000
      vertex 32.023335 190.400940 0.000000
    endloop
  endfacet
  facet normal 0.988555 0.150858 0.000000
    outer loop
      vertex 32.007423 190.505203 0.000000
      vertex 32.023335 190.400940 3.000000
      vertex 32.023335 190.400940 0.000000
    endloop
  endfacet
  facet normal 0.988555 0.150858 0.000000
    outer loop
      vertex 32.007423 190.505203 3.000000
      vertex 32.023335 190.400940 3.000000
      vertex 32.007423 190.505203 0.000000
    endloop
  endfacet
  facet normal 0.998728 0.050433 0.000000
    outer loop
      vertex 32.002003 190.612549 0.000000
      vertex 32.007423 190.505203 3.000000
      vertex 32.007423 190.505203 0.000000
    endloop
  endfacet
  facet normal 0.998728 0.050433 0.000000
    outer loop
      vertex 32.002003 190.612549 3.000000
      vertex 32.007423 190.505203 3.000000
      vertex 32.002003 190.612549 0.000000
    endloop
  endfacet
  facet normal 0.998728 -0.050426 0.000000
    outer loop
      vertex 32.007423 190.719910 0.000000
      vertex 32.002003 190.612549 3.000000
      vertex 32.002003 190.612549 0.000000
    endloop
  endfacet
  facet normal 0.998728 -0.050426 0.000000
    outer loop
      vertex 32.007423 190.719910 3.000000
      vertex 32.002003 190.612549 3.000000
      vertex 32.007423 190.719910 0.000000
    endloop
  endfacet
  facet normal 0.988552 -0.150880 0.000000
    outer loop
      vertex 32.023335 190.824158 0.000000
      vertex 32.007423 190.719910 3.000000
      vertex 32.007423 190.719910 0.000000
    endloop
  endfacet
  facet normal 0.988552 -0.150880 0.000000
    outer loop
      vertex 32.023335 190.824158 3.000000
      vertex 32.007423 190.719910 3.000000
      vertex 32.023335 190.824158 0.000000
    endloop
  endfacet
  facet normal 0.968497 -0.249026 0.000000
    outer loop
      vertex 32.049210 190.924789 0.000000
      vertex 32.023335 190.824158 3.000000
      vertex 32.023335 190.824158 0.000000
    endloop
  endfacet
  facet normal 0.968497 -0.249026 0.000000
    outer loop
      vertex 32.049210 190.924789 3.000000
      vertex 32.023335 190.824158 3.000000
      vertex 32.049210 190.924789 0.000000
    endloop
  endfacet
  facet normal 0.939071 -0.343722 0.000000
    outer loop
      vertex 32.084518 191.021255 0.000000
      vertex 32.049210 190.924789 3.000000
      vertex 32.049210 190.924789 0.000000
    endloop
  endfacet
  facet normal 0.939071 -0.343722 0.000000
    outer loop
      vertex 32.084518 191.021255 3.000000
      vertex 32.049210 190.924789 3.000000
      vertex 32.084518 191.021255 0.000000
    endloop
  endfacet
  facet normal 0.900949 -0.433926 0.000000
    outer loop
      vertex 32.128731 191.113052 0.000000
      vertex 32.084518 191.021255 3.000000
      vertex 32.084518 191.021255 0.000000
    endloop
  endfacet
  facet normal 0.900949 -0.433926 0.000000
    outer loop
      vertex 32.128731 191.113052 3.000000
      vertex 32.084518 191.021255 3.000000
      vertex 32.128731 191.113052 0.000000
    endloop
  endfacet
  facet normal 0.854625 -0.519245 0.000000
    outer loop
      vertex 32.181324 191.199615 0.000000
      vertex 32.128731 191.113052 3.000000
      vertex 32.128731 191.113052 0.000000
    endloop
  endfacet
  facet normal 0.854625 -0.519245 0.000000
    outer loop
      vertex 32.181324 191.199615 3.000000
      vertex 32.128731 191.113052 3.000000
      vertex 32.181324 191.199615 0.000000
    endloop
  endfacet
  facet normal 0.800870 -0.598838 0.000000
    outer loop
      vertex 32.241772 191.280457 0.000000
      vertex 32.181324 191.199615 3.000000
      vertex 32.181324 191.199615 0.000000
    endloop
  endfacet
  facet normal 0.800870 -0.598838 0.000000
    outer loop
      vertex 32.241772 191.280457 3.000000
      vertex 32.181324 191.199615 3.000000
      vertex 32.241772 191.280457 0.000000
    endloop
  endfacet
  facet normal 0.739983 -0.672626 0.000000
    outer loop
      vertex 32.309540 191.355011 0.000000
      vertex 32.241772 191.280457 3.000000
      vertex 32.241772 191.280457 0.000000
    endloop
  endfacet
  facet normal 0.739983 -0.672626 0.000000
    outer loop
      vertex 32.309540 191.355011 3.000000
      vertex 32.241772 191.280457 3.000000
      vertex 32.309540 191.355011 0.000000
    endloop
  endfacet
  facet normal 0.672631 -0.739978 0.000000
    outer loop
      vertex 32.384106 191.422791 0.000000
      vertex 32.309540 191.355011 3.000000
      vertex 32.309540 191.355011 0.000000
    endloop
  endfacet
  facet normal 0.672631 -0.739978 0.000000
    outer loop
      vertex 32.384106 191.422791 3.000000
      vertex 32.309540 191.355011 3.000000
      vertex 32.384106 191.422791 0.000000
    endloop
  endfacet
  facet normal 0.598826 -0.800879 0.000000
    outer loop
      vertex 32.464939 191.483231 0.000000
      vertex 32.384106 191.422791 3.000000
      vertex 32.384106 191.422791 0.000000
    endloop
  endfacet
  facet normal 0.598826 -0.800879 0.000000
    outer loop
      vertex 32.464939 191.483231 3.000000
      vertex 32.384106 191.422791 3.000000
      vertex 32.464939 191.483231 0.000000
    endloop
  endfacet
  facet normal 0.519240 -0.854629 0.000000
    outer loop
      vertex 32.551510 191.535828 0.000000
      vertex 32.464939 191.483231 3.000000
      vertex 32.464939 191.483231 0.000000
    endloop
  endfacet
  facet normal 0.519240 -0.854629 0.000000
    outer loop
      vertex 32.551510 191.535828 3.000000
      vertex 32.464939 191.483231 3.000000
      vertex 32.551510 191.535828 0.000000
    endloop
  endfacet
  facet normal 0.433909 -0.900957 0.000000
    outer loop
      vertex 32.643295 191.580032 0.000000
      vertex 32.551510 191.535828 3.000000
      vertex 32.551510 191.535828 0.000000
    endloop
  endfacet
  facet normal 0.433909 -0.900957 0.000000
    outer loop
      vertex 32.643295 191.580032 3.000000
      vertex 32.551510 191.535828 3.000000
      vertex 32.643295 191.580032 0.000000
    endloop
  endfacet
  facet normal 0.343710 -0.939076 0.000000
    outer loop
      vertex 32.739765 191.615341 0.000000
      vertex 32.643295 191.580032 3.000000
      vertex 32.643295 191.580032 0.000000
    endloop
  endfacet
  facet normal 0.343710 -0.939076 0.000000
    outer loop
      vertex 32.739765 191.615341 3.000000
      vertex 32.643295 191.580032 3.000000
      vertex 32.739765 191.615341 0.000000
    endloop
  endfacet
  facet normal 0.249078 -0.968483 0.000000
    outer loop
      vertex 32.840389 191.641220 0.000000
      vertex 32.739765 191.615341 3.000000
      vertex 32.739765 191.615341 0.000000
    endloop
  endfacet
  facet normal 0.249078 -0.968483 0.000000
    outer loop
      vertex 32.840389 191.641220 3.000000
      vertex 32.739765 191.615341 3.000000
      vertex 32.840389 191.641220 0.000000
    endloop
  endfacet
  facet normal 0.150905 -0.988548 0.000000
    outer loop
      vertex 32.944645 191.657135 0.000000
      vertex 32.840389 191.641220 3.000000
      vertex 32.840389 191.641220 0.000000
    endloop
  endfacet
  facet normal 0.150905 -0.988548 0.000000
    outer loop
      vertex 32.944645 191.657135 3.000000
      vertex 32.840389 191.641220 3.000000
      vertex 32.944645 191.657135 0.000000
    endloop
  endfacet
  facet normal 0.050392 -0.998729 0.000000
    outer loop
      vertex 33.052002 191.662552 0.000000
      vertex 32.944645 191.657135 3.000000
      vertex 32.944645 191.657135 0.000000
    endloop
  endfacet
  facet normal 0.050392 -0.998729 0.000000
    outer loop
      vertex 33.052002 191.662552 3.000000
      vertex 32.944645 191.657135 3.000000
      vertex 33.052002 191.662552 0.000000
    endloop
  endfacet
  facet normal -0.050392 -0.998729 0.000000
    outer loop
      vertex 33.159359 191.657135 0.000000
      vertex 33.052002 191.662552 3.000000
      vertex 33.052002 191.662552 0.000000
    endloop
  endfacet
  facet normal -0.050392 -0.998729 -0.000000
    outer loop
      vertex 33.159359 191.657135 3.000000
      vertex 33.052002 191.662552 3.000000
      vertex 33.159359 191.657135 0.000000
    endloop
  endfacet
  facet normal -0.150905 -0.988548 0.000000
    outer loop
      vertex 33.263615 191.641220 0.000000
      vertex 33.159359 191.657135 3.000000
      vertex 33.159359 191.657135 0.000000
    endloop
  endfacet
  facet normal -0.150905 -0.988548 -0.000000
    outer loop
      vertex 33.263615 191.641220 3.000000
      vertex 33.159359 191.657135 3.000000
      vertex 33.263615 191.641220 0.000000
    endloop
  endfacet
  facet normal -0.249078 -0.968483 0.000000
    outer loop
      vertex 33.364239 191.615341 0.000000
      vertex 33.263615 191.641220 3.000000
      vertex 33.263615 191.641220 0.000000
    endloop
  endfacet
  facet normal -0.249078 -0.968483 -0.000000
    outer loop
      vertex 33.364239 191.615341 3.000000
      vertex 33.263615 191.641220 3.000000
      vertex 33.364239 191.615341 0.000000
    endloop
  endfacet
  facet normal -0.343710 -0.939076 0.000000
    outer loop
      vertex 33.460709 191.580032 0.000000
      vertex 33.364239 191.615341 3.000000
      vertex 33.364239 191.615341 0.000000
    endloop
  endfacet
  facet normal -0.343710 -0.939076 -0.000000
    outer loop
      vertex 33.460709 191.580032 3.000000
      vertex 33.364239 191.615341 3.000000
      vertex 33.460709 191.580032 0.000000
    endloop
  endfacet
  facet normal -0.433909 -0.900957 0.000000
    outer loop
      vertex 33.552494 191.535828 0.000000
      vertex 33.460709 191.580032 3.000000
      vertex 33.460709 191.580032 0.000000
    endloop
  endfacet
  facet normal -0.433909 -0.900957 -0.000000
    outer loop
      vertex 33.552494 191.535828 3.000000
      vertex 33.460709 191.580032 3.000000
      vertex 33.552494 191.535828 0.000000
    endloop
  endfacet
  facet normal -0.519223 -0.854639 0.000000
    outer loop
      vertex 33.639069 191.483231 0.000000
      vertex 33.552494 191.535828 3.000000
      vertex 33.552494 191.535828 0.000000
    endloop
  endfacet
  facet normal -0.519223 -0.854639 -0.000000
    outer loop
      vertex 33.639069 191.483231 3.000000
      vertex 33.552494 191.535828 3.000000
      vertex 33.639069 191.483231 0.000000
    endloop
  endfacet
  facet normal -0.598844 -0.800865 0.000000
    outer loop
      vertex 33.719898 191.422791 0.000000
      vertex 33.639069 191.483231 3.000000
      vertex 33.639069 191.483231 0.000000
    endloop
  endfacet
  facet normal -0.598844 -0.800865 -0.000000
    outer loop
      vertex 33.719898 191.422791 3.000000
      vertex 33.639069 191.483231 3.000000
      vertex 33.719898 191.422791 0.000000
    endloop
  endfacet
  facet normal -0.672631 -0.739978 0.000000
    outer loop
      vertex 33.794464 191.355011 0.000000
      vertex 33.719898 191.422791 3.000000
      vertex 33.719898 191.422791 0.000000
    endloop
  endfacet
  facet normal -0.672631 -0.739978 -0.000000
    outer loop
      vertex 33.794464 191.355011 3.000000
      vertex 33.719898 191.422791 3.000000
      vertex 33.794464 191.355011 0.000000
    endloop
  endfacet
  facet normal -0.739983 -0.672626 0.000000
    outer loop
      vertex 33.862232 191.280457 0.000000
      vertex 33.794464 191.355011 3.000000
      vertex 33.794464 191.355011 0.000000
    endloop
  endfacet
  facet normal -0.739983 -0.672626 -0.000000
    outer loop
      vertex 33.862232 191.280457 3.000000
      vertex 33.794464 191.355011 3.000000
      vertex 33.862232 191.280457 0.000000
    endloop
  endfacet
  facet normal -0.800870 -0.598838 0.000000
    outer loop
      vertex 33.922680 191.199615 0.000000
      vertex 33.862232 191.280457 3.000000
      vertex 33.862232 191.280457 0.000000
    endloop
  endfacet
  facet normal -0.800870 -0.598838 -0.000000
    outer loop
      vertex 33.922680 191.199615 3.000000
      vertex 33.862232 191.280457 3.000000
      vertex 33.922680 191.199615 0.000000
    endloop
  endfacet
  facet normal -0.854625 -0.519245 0.000000
    outer loop
      vertex 33.975273 191.113052 0.000000
      vertex 33.922680 191.199615 3.000000
      vertex 33.922680 191.199615 0.000000
    endloop
  endfacet
  facet normal -0.854625 -0.519245 -0.000000
    outer loop
      vertex 33.975273 191.113052 3.000000
      vertex 33.922680 191.199615 3.000000
      vertex 33.975273 191.113052 0.000000
    endloop
  endfacet
  facet normal -0.900934 -0.433956 0.000000
    outer loop
      vertex 34.019489 191.021255 0.000000
      vertex 33.975273 191.113052 3.000000
      vertex 33.975273 191.113052 0.000000
    endloop
  endfacet
  facet normal -0.900934 -0.433956 -0.000000
    outer loop
      vertex 34.019489 191.021255 3.000000
      vertex 33.975273 191.113052 3.000000
      vertex 34.019489 191.021255 0.000000
    endloop
  endfacet
  facet normal -0.939071 -0.343722 0.000000
    outer loop
      vertex 34.054798 190.924789 0.000000
      vertex 34.019489 191.021255 3.000000
      vertex 34.019489 191.021255 0.000000
    endloop
  endfacet
  facet normal -0.939071 -0.343722 -0.000000
    outer loop
      vertex 34.054798 190.924789 3.000000
      vertex 34.019489 191.021255 3.000000
      vertex 34.054798 190.924789 0.000000
    endloop
  endfacet
  facet normal -0.968506 -0.248992 0.000000
    outer loop
      vertex 34.080669 190.824158 0.000000
      vertex 34.054798 190.924789 3.000000
      vertex 34.054798 190.924789 0.000000
    endloop
  endfacet
  facet normal -0.968506 -0.248992 -0.000000
    outer loop
      vertex 34.080669 190.824158 3.000000
      vertex 34.054798 190.924789 3.000000
      vertex 34.080669 190.824158 0.000000
    endloop
  endfacet
  facet normal -0.988552 -0.150880 0.000000
    outer loop
      vertex 34.096581 190.719910 0.000000
      vertex 34.080669 190.824158 3.000000
      vertex 34.080669 190.824158 0.000000
    endloop
  endfacet
  facet normal -0.988552 -0.150880 -0.000000
    outer loop
      vertex 34.096581 190.719910 3.000000
      vertex 34.080669 190.824158 3.000000
      vertex 34.096581 190.719910 0.000000
    endloop
  endfacet
  facet normal -0.998728 -0.050426 0.000000
    outer loop
      vertex 34.102001 190.612549 0.000000
      vertex 34.096581 190.719910 3.000000
      vertex 34.096581 190.719910 0.000000
    endloop
  endfacet
  facet normal -0.998728 -0.050426 -0.000000
    outer loop
      vertex 34.102001 190.612549 3.000000
      vertex 34.096581 190.719910 3.000000
      vertex 34.102001 190.612549 0.000000
    endloop
  endfacet
  facet normal -0.050376 -0.998730 0.000000
    outer loop
      vertex 114.105431 164.581421 1.500000
      vertex 114.054306 164.584000 3.000000
      vertex 114.054306 164.584000 0.000000
    endloop
  endfacet
  facet normal -0.050376 -0.998730 0.000000
    outer loop
      vertex 114.105431 164.581421 0.000000
      vertex 114.105431 164.581421 1.500000
      vertex 114.054306 164.584000 0.000000
    endloop
  endfacet
  facet normal -0.151007 -0.988533 0.000000
    outer loop
      vertex 114.155075 164.573837 0.000000
      vertex 114.105431 164.581421 1.500000
      vertex 114.105431 164.581421 0.000000
    endloop
  endfacet
  facet normal -0.151007 -0.988533 -0.000000
    outer loop
      vertex 114.155075 164.573837 1.500000
      vertex 114.105431 164.581421 1.500000
      vertex 114.155075 164.573837 0.000000
    endloop
  endfacet
  facet normal -0.248917 -0.968525 0.000000
    outer loop
      vertex 114.202988 164.561523 0.000000
      vertex 114.155075 164.573837 1.500000
      vertex 114.155075 164.573837 0.000000
    endloop
  endfacet
  facet normal -0.248917 -0.968525 -0.000000
    outer loop
      vertex 114.202988 164.561523 1.500000
      vertex 114.155075 164.573837 1.500000
      vertex 114.202988 164.561523 0.000000
    endloop
  endfacet
  facet normal -0.343696 -0.939081 0.000000
    outer loop
      vertex 114.248932 164.544708 0.000000
      vertex 114.202988 164.561523 1.500000
      vertex 114.202988 164.561523 0.000000
    endloop
  endfacet
  facet normal -0.343696 -0.939081 -0.000000
    outer loop
      vertex 114.248932 164.544708 1.500000
      vertex 114.202988 164.561523 1.500000
      vertex 114.248932 164.544708 0.000000
    endloop
  endfacet
  facet normal -0.434080 -0.900874 0.000000
    outer loop
      vertex 114.292633 164.523651 0.000000
      vertex 114.248932 164.544708 1.500000
      vertex 114.248932 164.544708 0.000000
    endloop
  endfacet
  facet normal -0.434080 -0.900874 -0.000000
    outer loop
      vertex 114.292633 164.523651 1.500000
      vertex 114.248932 164.544708 1.500000
      vertex 114.292633 164.523651 0.000000
    endloop
  endfacet
  facet normal -0.519094 -0.854717 0.000000
    outer loop
      vertex 114.333862 164.498611 0.000000
      vertex 114.292633 164.523651 1.500000
      vertex 114.292633 164.523651 0.000000
    endloop
  endfacet
  facet normal -0.519094 -0.854717 -0.000000
    outer loop
      vertex 114.333862 164.498611 1.500000
      vertex 114.292633 164.523651 1.500000
      vertex 114.333862 164.498611 0.000000
    endloop
  endfacet
  facet normal -0.598806 -0.800894 0.000000
    outer loop
      vertex 114.372353 164.469833 0.000000
      vertex 114.333862 164.498611 1.500000
      vertex 114.333862 164.498611 0.000000
    endloop
  endfacet
  facet normal -0.598806 -0.800894 -0.000000
    outer loop
      vertex 114.372353 164.469833 1.500000
      vertex 114.333862 164.498611 1.500000
      vertex 114.372353 164.469833 0.000000
    endloop
  endfacet
  facet normal -0.672594 -0.740012 0.000000
    outer loop
      vertex 114.407860 164.437561 0.000000
      vertex 114.372353 164.469833 1.500000
      vertex 114.372353 164.469833 0.000000
    endloop
  endfacet
  facet normal -0.672594 -0.740012 -0.000000
    outer loop
      vertex 114.407860 164.437561 1.500000
      vertex 114.372353 164.469833 1.500000
      vertex 114.407860 164.437561 0.000000
    endloop
  endfacet
  facet normal -0.740012 -0.672594 0.000000
    outer loop
      vertex 114.440132 164.402054 0.000000
      vertex 114.407860 164.437561 1.500000
      vertex 114.407860 164.437561 0.000000
    endloop
  endfacet
  facet normal -0.740012 -0.672594 -0.000000
    outer loop
      vertex 114.440132 164.402054 1.500000
      vertex 114.407860 164.437561 1.500000
      vertex 114.440132 164.402054 0.000000
    endloop
  endfacet
  facet normal -0.800951 -0.598729 0.000000
    outer loop
      vertex 114.468910 164.363556 0.000000
      vertex 114.440132 164.402054 1.500000
      vertex 114.440132 164.402054 0.000000
    endloop
  endfacet
  facet normal -0.800951 -0.598729 -0.000000
    outer loop
      vertex 114.468910 164.363556 1.500000
      vertex 114.440132 164.402054 1.500000
      vertex 114.468910 164.363556 0.000000
    endloop
  endfacet
  facet normal -0.854647 -0.519209 0.000000
    outer loop
      vertex 114.493958 164.322327 0.000000
      vertex 114.468910 164.363556 1.500000
      vertex 114.468910 164.363556 0.000000
    endloop
  endfacet
  facet normal -0.854647 -0.519209 -0.000000
    outer loop
      vertex 114.493958 164.322327 1.500000
      vertex 114.468910 164.363556 1.500000
      vertex 114.493958 164.322327 0.000000
    endloop
  endfacet
  facet normal -0.900874 -0.434080 0.000000
    outer loop
      vertex 114.515015 164.278625 0.000000
      vertex 114.493958 164.322327 1.500000
      vertex 114.493958 164.322327 0.000000
    endloop
  endfacet
  facet normal -0.900874 -0.434080 -0.000000
    outer loop
      vertex 114.515015 164.278625 1.500000
      vertex 114.493958 164.322327 1.500000
      vertex 114.515015 164.278625 0.000000
    endloop
  endfacet
  facet normal -0.939081 -0.343696 0.000000
    outer loop
      vertex 114.531830 164.232681 0.000000
      vertex 114.515015 164.278625 1.500000
      vertex 114.515015 164.278625 0.000000
    endloop
  endfacet
  facet normal -0.939081 -0.343696 -0.000000
    outer loop
      vertex 114.531830 164.232681 1.500000
      vertex 114.515015 164.278625 1.500000
      vertex 114.531830 164.232681 0.000000
    endloop
  endfacet
  facet normal -0.968488 -0.249062 0.000000
    outer loop
      vertex 114.544151 164.184769 0.000000
      vertex 114.531830 164.232681 1.500000
      vertex 114.531830 164.232681 0.000000
    endloop
  endfacet
  facet normal -0.968488 -0.249062 -0.000000
    outer loop
      vertex 114.544151 164.184769 1.500000
      vertex 114.531830 164.232681 1.500000
      vertex 114.544151 164.184769 0.000000
    endloop
  endfacet
  facet normal -0.988559 -0.150836 0.000000
    outer loop
      vertex 114.551727 164.135117 0.000000
      vertex 114.544151 164.184769 1.500000
      vertex 114.544151 164.184769 0.000000
    endloop
  endfacet
  facet normal -0.988559 -0.150836 -0.000000
    outer loop
      vertex 114.551727 164.135117 1.500000
      vertex 114.544151 164.184769 1.500000
      vertex 114.551727 164.135117 0.000000
    endloop
  endfacet
  facet normal -0.998730 -0.050384 0.000000
    outer loop
      vertex 114.554306 164.084000 0.000000
      vertex 114.551727 164.135117 1.500000
      vertex 114.551727 164.135117 0.000000
    endloop
  endfacet
  facet normal -0.998730 -0.050384 -0.000000
    outer loop
      vertex 114.554306 164.084000 3.000000
      vertex 114.551727 164.135117 1.500000
      vertex 114.554306 164.084000 0.000000
    endloop
  endfacet
  facet normal -0.998730 -0.050384 0.000000
    outer loop
      vertex 114.551727 164.135117 1.500000
      vertex 114.554306 164.084000 3.000000
      vertex 114.551727 164.135117 3.000000
    endloop
  endfacet
  facet normal -0.988559 -0.150836 0.000000
    outer loop
      vertex 114.544151 164.184769 3.000000
      vertex 114.551727 164.135117 1.500000
      vertex 114.551727 164.135117 3.000000
    endloop
  endfacet
  facet normal -0.988559 -0.150836 0.000000
    outer loop
      vertex 114.544151 164.184769 1.500000
      vertex 114.551727 164.135117 1.500000
      vertex 114.544151 164.184769 3.000000
    endloop
  endfacet
  facet normal -0.968488 -0.249062 0.000000
    outer loop
      vertex 114.531830 164.232681 3.000000
      vertex 114.544151 164.184769 1.500000
      vertex 114.544151 164.184769 3.000000
    endloop
  endfacet
  facet normal -0.968488 -0.249062 0.000000
    outer loop
      vertex 114.531830 164.232681 1.500000
      vertex 114.544151 164.184769 1.500000
      vertex 114.531830 164.232681 3.000000
    endloop
  endfacet
  facet normal -0.939081 -0.343696 0.000000
    outer loop
      vertex 114.515015 164.278625 3.000000
      vertex 114.531830 164.232681 1.500000
      vertex 114.531830 164.232681 3.000000
    endloop
  endfacet
  facet normal -0.939081 -0.343696 0.000000
    outer loop
      vertex 114.515015 164.278625 1.500000
      vertex 114.531830 164.232681 1.500000
      vertex 114.515015 164.278625 3.000000
    endloop
  endfacet
  facet normal -0.900874 -0.434080 0.000000
    outer loop
      vertex 114.493958 164.322327 3.000000
      vertex 114.515015 164.278625 1.500000
      vertex 114.515015 164.278625 3.000000
    endloop
  endfacet
  facet normal -0.900874 -0.434080 0.000000
    outer loop
      vertex 114.493958 164.322327 1.500000
      vertex 114.515015 164.278625 1.500000
      vertex 114.493958 164.322327 3.000000
    endloop
  endfacet
  facet normal -0.854647 -0.519209 0.000000
    outer loop
      vertex 114.468910 164.363556 3.000000
      vertex 114.493958 164.322327 1.500000
      vertex 114.493958 164.322327 3.000000
    endloop
  endfacet
  facet normal -0.854647 -0.519209 0.000000
    outer loop
      vertex 114.468910 164.363556 1.500000
      vertex 114.493958 164.322327 1.500000
      vertex 114.468910 164.363556 3.000000
    endloop
  endfacet
  facet normal -0.800951 -0.598729 0.000000
    outer loop
      vertex 114.440132 164.402054 3.000000
      vertex 114.468910 164.363556 1.500000
      vertex 114.468910 164.363556 3.000000
    endloop
  endfacet
  facet normal -0.800951 -0.598729 0.000000
    outer loop
      vertex 114.440132 164.402054 1.500000
      vertex 114.468910 164.363556 1.500000
      vertex 114.440132 164.402054 3.000000
    endloop
  endfacet
  facet normal -0.740012 -0.672594 0.000000
    outer loop
      vertex 114.407860 164.437561 3.000000
      vertex 114.440132 164.402054 1.500000
      vertex 114.440132 164.402054 3.000000
    endloop
  endfacet
  facet normal -0.740012 -0.672594 0.000000
    outer loop
      vertex 114.407860 164.437561 1.500000
      vertex 114.440132 164.402054 1.500000
      vertex 114.407860 164.437561 3.000000
    endloop
  endfacet
  facet normal -0.672594 -0.740012 0.000000
    outer loop
      vertex 114.372353 164.469833 3.000000
      vertex 114.407860 164.437561 1.500000
      vertex 114.407860 164.437561 3.000000
    endloop
  endfacet
  facet normal -0.672594 -0.740012 0.000000
    outer loop
      vertex 114.372353 164.469833 1.500000
      vertex 114.407860 164.437561 1.500000
      vertex 114.372353 164.469833 3.000000
    endloop
  endfacet
  facet normal -0.598806 -0.800894 0.000000
    outer loop
      vertex 114.333862 164.498611 3.000000
      vertex 114.372353 164.469833 1.500000
      vertex 114.372353 164.469833 3.000000
    endloop
  endfacet
  facet normal -0.598806 -0.800894 0.000000
    outer loop
      vertex 114.333862 164.498611 1.500000
      vertex 114.372353 164.469833 1.500000
      vertex 114.333862 164.498611 3.000000
    endloop
  endfacet
  facet normal -0.519094 -0.854717 0.000000
    outer loop
      vertex 114.292633 164.523651 3.000000
      vertex 114.333862 164.498611 1.500000
      vertex 114.333862 164.498611 3.000000
    endloop
  endfacet
  facet normal -0.519094 -0.854717 0.000000
    outer loop
      vertex 114.292633 164.523651 1.500000
      vertex 114.333862 164.498611 1.500000
      vertex 114.292633 164.523651 3.000000
    endloop
  endfacet
  facet normal -0.434080 -0.900874 0.000000
    outer loop
      vertex 114.248932 164.544708 3.000000
      vertex 114.292633 164.523651 1.500000
      vertex 114.292633 164.523651 3.000000
    endloop
  endfacet
  facet normal -0.434080 -0.900874 0.000000
    outer loop
      vertex 114.248932 164.544708 1.500000
      vertex 114.292633 164.523651 1.500000
      vertex 114.248932 164.544708 3.000000
    endloop
  endfacet
  facet normal -0.343696 -0.939081 0.000000
    outer loop
      vertex 114.202988 164.561523 3.000000
      vertex 114.248932 164.544708 1.500000
      vertex 114.248932 164.544708 3.000000
    endloop
  endfacet
  facet normal -0.343696 -0.939081 0.000000
    outer loop
      vertex 114.202988 164.561523 1.500000
      vertex 114.248932 164.544708 1.500000
      vertex 114.202988 164.561523 3.000000
    endloop
  endfacet
  facet normal -0.248917 -0.968525 0.000000
    outer loop
      vertex 114.155075 164.573837 3.000000
      vertex 114.202988 164.561523 1.500000
      vertex 114.202988 164.561523 3.000000
    endloop
  endfacet
  facet normal -0.248917 -0.968525 0.000000
    outer loop
      vertex 114.155075 164.573837 1.500000
      vertex 114.202988 164.561523 1.500000
      vertex 114.155075 164.573837 3.000000
    endloop
  endfacet
  facet normal -0.151007 -0.988533 0.000000
    outer loop
      vertex 114.105431 164.581421 3.000000
      vertex 114.155075 164.573837 1.500000
      vertex 114.155075 164.573837 3.000000
    endloop
  endfacet
  facet normal -0.151007 -0.988533 0.000000
    outer loop
      vertex 114.105431 164.581421 1.500000
      vertex 114.155075 164.573837 1.500000
      vertex 114.105431 164.581421 3.000000
    endloop
  endfacet
  facet normal -0.050376 -0.998730 0.000000
    outer loop
      vertex 114.054306 164.584000 3.000000
      vertex 114.105431 164.581421 1.500000
      vertex 114.105431 164.581421 3.000000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 109.054306 164.584000 3.000000
      vertex 109.054306 164.584000 0.000000
      vertex 114.054306 164.584000 0.000000
    endloop
  endfacet
  facet normal -0.000000 -1.000000 -0.000000
    outer loop
      vertex 114.054306 164.584000 3.000000
      vertex 109.054306 164.584000 3.000000
      vertex 114.054306 164.584000 0.000000
    endloop
  endfacet
  facet normal 0.998730 -0.050384 0.000000
    outer loop
      vertex 108.556885 164.135117 1.500000
      vertex 108.554306 164.084000 3.000000
      vertex 108.554306 164.084000 0.000000
    endloop
  endfacet
  facet normal 0.998730 -0.050384 0.000000
    outer loop
      vertex 108.556885 164.135117 0.000000
      vertex 108.556885 164.135117 1.500000
      vertex 108.554306 164.084000 0.000000
    endloop
  endfacet
  facet normal 0.988559 -0.150836 0.000000
    outer loop
      vertex 108.564461 164.184769 0.000000
      vertex 108.556885 164.135117 1.500000
      vertex 108.556885 164.135117 0.000000
    endloop
  endfacet
  facet normal 0.988559 -0.150836 0.000000
    outer loop
      vertex 108.564461 164.184769 1.500000
      vertex 108.556885 164.135117 1.500000
      vertex 108.564461 164.184769 0.000000
    endloop
  endfacet
  facet normal 0.968488 -0.249062 0.000000
    outer loop
      vertex 108.576782 164.232681 0.000000
      vertex 108.564461 164.184769 1.500000
      vertex 108.564461 164.184769 0.000000
    endloop
  endfacet
  facet normal 0.968488 -0.249062 0.000000
    outer loop
      vertex 108.576782 164.232681 1.500000
      vertex 108.564461 164.184769 1.500000
      vertex 108.576782 164.232681 0.000000
    endloop
  endfacet
  facet normal 0.939081 -0.343696 0.000000
    outer loop
      vertex 108.593597 164.278625 0.000000
      vertex 108.576782 164.232681 1.500000
      vertex 108.576782 164.232681 0.000000
    endloop
  endfacet
  facet normal 0.939081 -0.343696 0.000000
    outer loop
      vertex 108.593597 164.278625 1.500000
      vertex 108.576782 164.232681 1.500000
      vertex 108.593597 164.278625 0.000000
    endloop
  endfacet
  facet normal 0.900874 -0.434080 0.000000
    outer loop
      vertex 108.614655 164.322327 0.000000
      vertex 108.593597 164.278625 1.500000
      vertex 108.593597 164.278625 0.000000
    endloop
  endfacet
  facet normal 0.900874 -0.434080 0.000000
    outer loop
      vertex 108.614655 164.322327 1.500000
      vertex 108.593597 164.278625 1.500000
      vertex 108.614655 164.322327 0.000000
    endloop
  endfacet
  facet normal 0.854717 -0.519094 0.000000
    outer loop
      vertex 108.639694 164.363556 0.000000
      vertex 108.614655 164.322327 1.500000
      vertex 108.614655 164.322327 0.000000
    endloop
  endfacet
  facet normal 0.854717 -0.519094 0.000000
    outer loop
      vertex 108.639694 164.363556 1.500000
      vertex 108.614655 164.322327 1.500000
      vertex 108.639694 164.363556 0.000000
    endloop
  endfacet
  facet normal 0.800875 -0.598831 0.000000
    outer loop
      vertex 108.668480 164.402054 0.000000
      vertex 108.639694 164.363556 1.500000
      vertex 108.639694 164.363556 0.000000
    endloop
  endfacet
  facet normal 0.800875 -0.598831 0.000000
    outer loop
      vertex 108.668480 164.402054 1.500000
      vertex 108.639694 164.363556 1.500000
      vertex 108.668480 164.402054 0.000000
    endloop
  endfacet
  facet normal 0.740012 -0.672594 0.000000
    outer loop
      vertex 108.700752 164.437561 0.000000
      vertex 108.668480 164.402054 1.500000
      vertex 108.668480 164.402054 0.000000
    endloop
  endfacet
  facet normal 0.740012 -0.672594 0.000000
    outer loop
      vertex 108.700752 164.437561 1.500000
      vertex 108.668480 164.402054 1.500000
      vertex 108.700752 164.437561 0.000000
    endloop
  endfacet
  facet normal 0.672594 -0.740012 0.000000
    outer loop
      vertex 108.736259 164.469833 0.000000
      vertex 108.700752 164.437561 1.500000
      vertex 108.700752 164.437561 0.000000
    endloop
  endfacet
  facet normal 0.672594 -0.740012 0.000000
    outer loop
      vertex 108.736259 164.469833 1.500000
      vertex 108.700752 164.437561 1.500000
      vertex 108.736259 164.469833 0.000000
    endloop
  endfacet
  facet normal 0.598806 -0.800894 0.000000
    outer loop
      vertex 108.774750 164.498611 0.000000
      vertex 108.736259 164.469833 1.500000
      vertex 108.736259 164.469833 0.000000
    endloop
  endfacet
  facet normal 0.598806 -0.800894 0.000000
    outer loop
      vertex 108.774750 164.498611 1.500000
      vertex 108.736259 164.469833 1.500000
      vertex 108.774750 164.498611 0.000000
    endloop
  endfacet
  facet normal 0.519094 -0.854717 0.000000
    outer loop
      vertex 108.815979 164.523651 0.000000
      vertex 108.774750 164.498611 1.500000
      vertex 108.774750 164.498611 0.000000
    endloop
  endfacet
  facet normal 0.519094 -0.854717 0.000000
    outer loop
      vertex 108.815979 164.523651 1.500000
      vertex 108.774750 164.498611 1.500000
      vertex 108.815979 164.523651 0.000000
    endloop
  endfacet
  facet normal 0.434080 -0.900874 0.000000
    outer loop
      vertex 108.859680 164.544708 0.000000
      vertex 108.815979 164.523651 1.500000
      vertex 108.815979 164.523651 0.000000
    endloop
  endfacet
  facet normal 0.434080 -0.900874 0.000000
    outer loop
      vertex 108.859680 164.544708 1.500000
      vertex 108.815979 164.523651 1.500000
      vertex 108.859680 164.544708 0.000000
    endloop
  endfacet
  facet normal 0.343696 -0.939081 0.000000
    outer loop
      vertex 108.905624 164.561523 0.000000
      vertex 108.859680 164.544708 1.500000
      vertex 108.859680 164.544708 0.000000
    endloop
  endfacet
  facet normal 0.343696 -0.939081 0.000000
    outer loop
      vertex 108.905624 164.561523 1.500000
      vertex 108.859680 164.544708 1.500000
      vertex 108.905624 164.561523 0.000000
    endloop
  endfacet
  facet normal 0.248917 -0.968525 0.000000
    outer loop
      vertex 108.953537 164.573837 0.000000
      vertex 108.905624 164.561523 1.500000
      vertex 108.905624 164.561523 0.000000
    endloop
  endfacet
  facet normal 0.248917 -0.968525 0.000000
    outer loop
      vertex 108.953537 164.573837 1.500000
      vertex 108.905624 164.561523 1.500000
      vertex 108.953537 164.573837 0.000000
    endloop
  endfacet
  facet normal 0.151007 -0.988533 0.000000
    outer loop
      vertex 109.003181 164.581421 0.000000
      vertex 108.953537 164.573837 1.500000
      vertex 108.953537 164.573837 0.000000
    endloop
  endfacet
  facet normal 0.151007 -0.988533 0.000000
    outer loop
      vertex 109.003181 164.581421 1.500000
      vertex 108.953537 164.573837 1.500000
      vertex 109.003181 164.581421 0.000000
    endloop
  endfacet
  facet normal 0.050376 -0.998730 0.000000
    outer loop
      vertex 109.054306 164.584000 0.000000
      vertex 109.003181 164.581421 1.500000
      vertex 109.003181 164.581421 0.000000
    endloop
  endfacet
  facet normal 0.050376 -0.998730 0.000000
    outer loop
      vertex 109.054306 164.584000 3.000000
      vertex 109.003181 164.581421 1.500000
      vertex 109.054306 164.584000 0.000000
    endloop
  endfacet
  facet normal 0.050376 -0.998730 0.000000
    outer loop
      vertex 109.003181 164.581421 1.500000
      vertex 109.054306 164.584000 3.000000
      vertex 109.003181 164.581421 3.000000
    endloop
  endfacet
  facet normal 0.151007 -0.988533 0.000000
    outer loop
      vertex 108.953537 164.573837 3.000000
      vertex 109.003181 164.581421 1.500000
      vertex 109.003181 164.581421 3.000000
    endloop
  endfacet
  facet normal 0.151007 -0.988533 0.000000
    outer loop
      vertex 108.953537 164.573837 1.500000
      vertex 109.003181 164.581421 1.500000
      vertex 108.953537 164.573837 3.000000
    endloop
  endfacet
  facet normal 0.248917 -0.968525 0.000000
    outer loop
      vertex 108.905624 164.561523 3.000000
      vertex 108.953537 164.573837 1.500000
      vertex 108.953537 164.573837 3.000000
    endloop
  endfacet
  facet normal 0.248917 -0.968525 0.000000
    outer loop
      vertex 108.905624 164.561523 1.500000
      vertex 108.953537 164.573837 1.500000
      vertex 108.905624 164.561523 3.000000
    endloop
  endfacet
  facet normal 0.343696 -0.939081 0.000000
    outer loop
      vertex 108.859680 164.544708 3.000000
      vertex 108.905624 164.561523 1.500000
      vertex 108.905624 164.561523 3.000000
    endloop
  endfacet
  facet normal 0.343696 -0.939081 0.000000
    outer loop
      vertex 108.859680 164.544708 1.500000
      vertex 108.905624 164.561523 1.500000
      vertex 108.859680 164.544708 3.000000
    endloop
  endfacet
  facet normal 0.434080 -0.900874 0.000000
    outer loop
      vertex 108.815979 164.523651 3.000000
      vertex 108.859680 164.544708 1.500000
      vertex 108.859680 164.544708 3.000000
    endloop
  endfacet
  facet normal 0.434080 -0.900874 0.000000
    outer loop
      vertex 108.815979 164.523651 1.500000
      vertex 108.859680 164.544708 1.500000
      vertex 108.815979 164.523651 3.000000
    endloop
  endfacet
  facet normal 0.519094 -0.854717 0.000000
    outer loop
      vertex 108.774750 164.498611 3.000000
      vertex 108.815979 164.523651 1.500000
      vertex 108.815979 164.523651 3.000000
    endloop
  endfacet
  facet normal 0.519094 -0.854717 0.000000
    outer loop
      vertex 108.774750 164.498611 1.500000
      vertex 108.815979 164.523651 1.500000
      vertex 108.774750 164.498611 3.000000
    endloop
  endfacet
  facet normal 0.598806 -0.800894 0.000000
    outer loop
      vertex 108.736259 164.469833 3.000000
      vertex 108.774750 164.498611 1.500000
      vertex 108.774750 164.498611 3.000000
    endloop
  endfacet
  facet normal 0.598806 -0.800894 0.000000
    outer loop
      vertex 108.736259 164.469833 1.500000
      vertex 108.774750 164.498611 1.500000
      vertex 108.736259 164.469833 3.000000
    endloop
  endfacet
  facet normal 0.672594 -0.740012 0.000000
    outer loop
      vertex 108.700752 164.437561 3.000000
      vertex 108.736259 164.469833 1.500000
      vertex 108.736259 164.469833 3.000000
    endloop
  endfacet
  facet normal 0.672594 -0.740012 0.000000
    outer loop
      vertex 108.700752 164.437561 1.500000
      vertex 108.736259 164.469833 1.500000
      vertex 108.700752 164.437561 3.000000
    endloop
  endfacet
  facet normal 0.740012 -0.672594 0.000000
    outer loop
      vertex 108.668480 164.402054 3.000000
      vertex 108.700752 164.437561 1.500000
      vertex 108.700752 164.437561 3.000000
    endloop
  endfacet
  facet normal 0.740012 -0.672594 0.000000
    outer loop
      vertex 108.668480 164.402054 1.500000
      vertex 108.700752 164.437561 1.500000
      vertex 108.668480 164.402054 3.000000
    endloop
  endfacet
  facet normal 0.800875 -0.598831 0.000000
    outer loop
      vertex 108.639694 164.363556 3.000000
      vertex 108.668480 164.402054 1.500000
      vertex 108.668480 164.402054 3.000000
    endloop
  endfacet
  facet normal 0.800875 -0.598831 0.000000
    outer loop
      vertex 108.639694 164.363556 1.500000
      vertex 108.668480 164.402054 1.500000
      vertex 108.639694 164.363556 3.000000
    endloop
  endfacet
  facet normal 0.854717 -0.519094 0.000000
    outer loop
      vertex 108.614655 164.322327 3.000000
      vertex 108.639694 164.363556 1.500000
      vertex 108.639694 164.363556 3.000000
    endloop
  endfacet
  facet normal 0.854717 -0.519094 0.000000
    outer loop
      vertex 108.614655 164.322327 1.500000
      vertex 108.639694 164.363556 1.500000
      vertex 108.614655 164.322327 3.000000
    endloop
  endfacet
  facet normal 0.900874 -0.434080 0.000000
    outer loop
      vertex 108.593597 164.278625 3.000000
      vertex 108.614655 164.322327 1.500000
      vertex 108.614655 164.322327 3.000000
    endloop
  endfacet
  facet normal 0.900874 -0.434080 0.000000
    outer loop
      vertex 108.593597 164.278625 1.500000
      vertex 108.614655 164.322327 1.500000
      vertex 108.593597 164.278625 3.000000
    endloop
  endfacet
  facet normal 0.939081 -0.343696 0.000000
    outer loop
      vertex 108.576782 164.232681 3.000000
      vertex 108.593597 164.278625 1.500000
      vertex 108.593597 164.278625 3.000000
    endloop
  endfacet
  facet normal 0.939081 -0.343696 0.000000
    outer loop
      vertex 108.576782 164.232681 1.500000
      vertex 108.593597 164.278625 1.500000
      vertex 108.576782 164.232681 3.000000
    endloop
  endfacet
  facet normal 0.968488 -0.249062 0.000000
    outer loop
      vertex 108.564461 164.184769 3.000000
      vertex 108.576782 164.232681 1.500000
      vertex 108.576782 164.232681 3.000000
    endloop
  endfacet
  facet normal 0.968488 -0.249062 0.000000
    outer loop
      vertex 108.564461 164.184769 1.500000
      vertex 108.576782 164.232681 1.500000
      vertex 108.564461 164.184769 3.000000
    endloop
  endfacet
  facet normal 0.988559 -0.150836 0.000000
    outer loop
      vertex 108.556885 164.135117 3.000000
      vertex 108.564461 164.184769 1.500000
      vertex 108.564461 164.184769 3.000000
    endloop
  endfacet
  facet normal 0.988559 -0.150836 0.000000
    outer loop
      vertex 108.556885 164.135117 1.500000
      vertex 108.564461 164.184769 1.500000
      vertex 108.556885 164.135117 3.000000
    endloop
  endfacet
  facet normal 0.998730 -0.050384 0.000000
    outer loop
      vertex 108.554306 164.084000 3.000000
      vertex 108.556885 164.135117 1.500000
      vertex 108.556885 164.135117 3.000000
    endloop
  endfacet
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex 108.554306 152.834106 3.000000
      vertex 108.554306 152.834106 0.000000
      vertex 108.554306 164.084000 0.000000
    endloop
  endfacet
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex 108.554306 164.084000 3.000000
      vertex 108.554306 152.834106 3.000000
      vertex 108.554306 164.084000 0.000000
    endloop
  endfacet
  facet normal 0.050376 0.998730 0.000000
    outer loop
      vertex 109.003181 152.336685 1.500000
      vertex 109.054306 152.334106 3.000000
      vertex 109.054306 152.334106 0.000000
    endloop
  endfacet
  facet normal 0.050376 0.998730 -0.000000
    outer loop
      vertex 109.003181 152.336685 0.000000
      vertex 109.003181 152.336685 1.500000
      vertex 109.054306 152.334106 0.000000
    endloop
  endfacet
  facet normal 0.151007 0.988533 0.000000
    outer loop
      vertex 108.953537 152.344269 0.000000
      vertex 109.003181 152.336685 1.500000
      vertex 109.003181 152.336685 0.000000
    endloop
  endfacet
  facet normal 0.151007 0.988533 0.000000
    outer loop
      vertex 108.953537 152.344269 1.500000
      vertex 109.003181 152.336685 1.500000
      vertex 108.953537 152.344269 0.000000
    endloop
  endfacet
  facet normal 0.248917 0.968525 0.000000
    outer loop
      vertex 108.905624 152.356583 0.000000
      vertex 108.953537 152.344269 1.500000
      vertex 108.953537 152.344269 0.000000
    endloop
  endfacet
  facet normal 0.248917 0.968525 0.000000
    outer loop
      vertex 108.905624 152.356583 1.500000
      vertex 108.953537 152.344269 1.500000
      vertex 108.905624 152.356583 0.000000
    endloop
  endfacet
  facet normal 0.343696 0.939081 0.000000
    outer loop
      vertex 108.859680 152.373398 0.000000
      vertex 108.905624 152.356583 1.500000
      vertex 108.905624 152.356583 0.000000
    endloop
  endfacet
  facet normal 0.343696 0.939081 0.000000
    outer loop
      vertex 108.859680 152.373398 1.500000
      vertex 108.905624 152.356583 1.500000
      vertex 108.859680 152.373398 0.000000
    endloop
  endfacet
  facet normal 0.434080 0.900874 0.000000
    outer loop
      vertex 108.815979 152.394455 0.000000
      vertex 108.859680 152.373398 1.500000
      vertex 108.859680 152.373398 0.000000
    endloop
  endfacet
  facet normal 0.434080 0.900874 0.000000
    outer loop
      vertex 108.815979 152.394455 1.500000
      vertex 108.859680 152.373398 1.500000
      vertex 108.815979 152.394455 0.000000
    endloop
  endfacet
  facet normal 0.519094 0.854717 0.000000
    outer loop
      vertex 108.774750 152.419495 0.000000
      vertex 108.815979 152.394455 1.500000
      vertex 108.815979 152.394455 0.000000
    endloop
  endfacet
  facet normal 0.519094 0.854717 0.000000
    outer loop
      vertex 108.774750 152.419495 1.500000
      vertex 108.815979 152.394455 1.500000
      vertex 108.774750 152.419495 0.000000
    endloop
  endfacet
  facet normal 0.599009 0.800742 0.000000
    outer loop
      vertex 108.736259 152.448288 0.000000
      vertex 108.774750 152.419495 1.500000
      vertex 108.774750 152.419495 0.000000
    endloop
  endfacet
  facet normal 0.599009 0.800742 0.000000
    outer loop
      vertex 108.736259 152.448288 1.500000
      vertex 108.774750 152.419495 1.500000
      vertex 108.736259 152.448288 0.000000
    endloop
  endfacet
  facet normal 0.672594 0.740012 0.000000
    outer loop
      vertex 108.700752 152.480560 0.000000
      vertex 108.736259 152.448288 1.500000
      vertex 108.736259 152.448288 0.000000
    endloop
  endfacet
  facet normal 0.672594 0.740012 0.000000
    outer loop
      vertex 108.700752 152.480560 1.500000
      vertex 108.736259 152.448288 1.500000
      vertex 108.700752 152.480560 0.000000
    endloop
  endfacet
  facet normal 0.740012 0.672594 0.000000
    outer loop
      vertex 108.668480 152.516068 0.000000
      vertex 108.700752 152.480560 1.500000
      vertex 108.700752 152.480560 0.000000
    endloop
  endfacet
  facet normal 0.740012 0.672594 0.000000
    outer loop
      vertex 108.668480 152.516068 1.500000
      vertex 108.700752 152.480560 1.500000
      vertex 108.668480 152.516068 0.000000
    endloop
  endfacet
  facet normal 0.800761 0.598983 0.000000
    outer loop
      vertex 108.639694 152.554550 0.000000
      vertex 108.668480 152.516068 1.500000
      vertex 108.668480 152.516068 0.000000
    endloop
  endfacet
  facet normal 0.800761 0.598983 0.000000
    outer loop
      vertex 108.639694 152.554550 1.500000
      vertex 108.668480 152.516068 1.500000
      vertex 108.639694 152.554550 0.000000
    endloop
  endfacet
  facet normal 0.854717 0.519094 0.000000
    outer loop
      vertex 108.614655 152.595779 0.000000
      vertex 108.639694 152.554550 1.500000
      vertex 108.639694 152.554550 0.000000
    endloop
  endfacet
  facet normal 0.854717 0.519094 0.000000
    outer loop
      vertex 108.614655 152.595779 1.500000
      vertex 108.639694 152.554550 1.500000
      vertex 108.614655 152.595779 0.000000
    endloop
  endfacet
  facet normal 0.900874 0.434080 0.000000
    outer loop
      vertex 108.593597 152.639481 0.000000
      vertex 108.614655 152.595779 1.500000
      vertex 108.614655 152.595779 0.000000
    endloop
  endfacet
  facet normal 0.900874 0.434080 0.000000
    outer loop
      vertex 108.593597 152.639481 1.500000
      vertex 108.614655 152.595779 1.500000
      vertex 108.593597 152.639481 0.000000
    endloop
  endfacet
  facet normal 0.939081 0.343696 0.000000
    outer loop
      vertex 108.576782 152.685425 0.000000
      vertex 108.593597 152.639481 1.500000
      vertex 108.593597 152.639481 0.000000
    endloop
  endfacet
  facet normal 0.939081 0.343696 0.000000
    outer loop
      vertex 108.576782 152.685425 1.500000
      vertex 108.593597 152.639481 1.500000
      vertex 108.576782 152.685425 0.000000
    endloop
  endfacet
  facet normal 0.968488 0.249062 0.000000
    outer loop
      vertex 108.564461 152.733337 0.000000
      vertex 108.576782 152.685425 1.500000
      vertex 108.576782 152.685425 0.000000
    endloop
  endfacet
  facet normal 0.968488 0.249062 0.000000
    outer loop
      vertex 108.564461 152.733337 1.500000
      vertex 108.576782 152.685425 1.500000
      vertex 108.564461 152.733337 0.000000
    endloop
  endfacet
  facet normal 0.988559 0.150836 0.000000
    outer loop
      vertex 108.556885 152.782990 0.000000
      vertex 108.564461 152.733337 1.500000
      vertex 108.564461 152.733337 0.000000
    endloop
  endfacet
  facet normal 0.988559 0.150836 0.000000
    outer loop
      vertex 108.556885 152.782990 1.500000
      vertex 108.564461 152.733337 1.500000
      vertex 108.556885 152.782990 0.000000
    endloop
  endfacet
  facet normal 0.998730 0.050384 0.000000
    outer loop
      vertex 108.554306 152.834106 0.000000
      vertex 108.556885 152.782990 1.500000
      vertex 108.556885 152.782990 0.000000
    endloop
  endfacet
  facet normal 0.998730 0.050384 0.000000
    outer loop
      vertex 108.554306 152.834106 3.000000
      vertex 108.556885 152.782990 1.500000
      vertex 108.554306 152.834106 0.000000
    endloop
  endfacet
  facet normal 0.998730 0.050384 -0.000000
    outer loop
      vertex 108.556885 152.782990 1.500000
      vertex 108.554306 152.834106 3.000000
      vertex 108.556885 152.782990 3.000000
    endloop
  endfacet
  facet normal 0.988559 0.150836 0.000000
    outer loop
      vertex 108.564461 152.733337 3.000000
      vertex 108.556885 152.782990 1.500000
      vertex 108.556885 152.782990 3.000000
    endloop
  endfacet
  facet normal 0.988559 0.150836 -0.000000
    outer loop
      vertex 108.564461 152.733337 1.500000
      vertex 108.556885 152.782990 1.500000
      vertex 108.564461 152.733337 3.000000
    endloop
  endfacet
  facet normal 0.968488 0.249062 0.000000
    outer loop
      vertex 108.576782 152.685425 3.000000
      vertex 108.564461 152.733337 1.500000
      vertex 108.564461 152.733337 3.000000
    endloop
  endfacet
  facet normal 0.968488 0.249062 -0.000000
    outer loop
      vertex 108.576782 152.685425 1.500000
      vertex 108.564461 152.733337 1.500000
      vertex 108.576782 152.685425 3.000000
    endloop
  endfacet
  facet normal 0.939081 0.343696 0.000000
    outer loop
      vertex 108.593597 152.639481 3.000000
      vertex 108.576782 152.685425 1.500000
      vertex 108.576782 152.685425 3.000000
    endloop
  endfacet
  facet normal 0.939081 0.343696 -0.000000
    outer loop
      vertex 108.593597 152.639481 1.500000
      vertex 108.576782 152.685425 1.500000
      vertex 108.593597 152.639481 3.000000
    endloop
  endfacet
  facet normal 0.900874 0.434080 0.000000
    outer loop
      vertex 108.614655 152.595779 3.000000
      vertex 108.593597 152.639481 1.500000
      vertex 108.593597 152.639481 3.000000
    endloop
  endfacet
  facet normal 0.900874 0.434080 -0.000000
    outer loop
      vertex 108.614655 152.595779 1.500000
      vertex 108.593597 152.639481 1.500000
      vertex 108.614655 152.595779 3.000000
    endloop
  endfacet
  facet normal 0.854717 0.519094 0.000000
    outer loop
      vertex 108.639694 152.554550 3.000000
      vertex 108.614655 152.595779 1.500000
      vertex 108.614655 152.595779 3.000000
    endloop
  endfacet
  facet normal 0.854717 0.519094 -0.000000
    outer loop
      vertex 108.639694 152.554550 1.500000
      vertex 108.614655 152.595779 1.500000
      vertex 108.639694 152.554550 3.000000
    endloop
  endfacet
  facet normal 0.800761 0.598983 0.000000
    outer loop
      vertex 108.668480 152.516068 3.000000
      vertex 108.639694 152.554550 1.500000
      vertex 108.639694 152.554550 3.000000
    endloop
  endfacet
  facet normal 0.800761 0.598983 -0.000000
    outer loop
      vertex 108.668480 152.516068 1.500000
      vertex 108.639694 152.554550 1.500000
      vertex 108.668480 152.516068 3.000000
    endloop
  endfacet
  facet normal 0.740012 0.672594 0.000000
    outer loop
      vertex 108.700752 152.480560 3.000000
      vertex 108.668480 152.516068 1.500000
      vertex 108.668480 152.516068 3.000000
    endloop
  endfacet
  facet normal 0.740012 0.672594 -0.000000
    outer loop
      vertex 108.700752 152.480560 1.500000
      vertex 108.668480 152.516068 1.500000
      vertex 108.700752 152.480560 3.000000
    endloop
  endfacet
  facet normal 0.672594 0.740012 0.000000
    outer loop
      vertex 108.736259 152.448288 3.000000
      vertex 108.700752 152.480560 1.500000
      vertex 108.700752 152.480560 3.000000
    endloop
  endfacet
  facet normal 0.672594 0.740012 -0.000000
    outer loop
      vertex 108.736259 152.448288 1.500000
      vertex 108.700752 152.480560 1.500000
      vertex 108.736259 152.448288 3.000000
    endloop
  endfacet
  facet normal 0.599009 0.800742 0.000000
    outer loop
      vertex 108.774750 152.419495 3.000000
      vertex 108.736259 152.448288 1.500000
      vertex 108.736259 152.448288 3.000000
    endloop
  endfacet
  facet normal 0.599009 0.800742 -0.000000
    outer loop
      vertex 108.774750 152.419495 1.500000
      vertex 108.736259 152.448288 1.500000
      vertex 108.774750 152.419495 3.000000
    endloop
  endfacet
  facet normal 0.519094 0.854717 0.000000
    outer loop
      vertex 108.815979 152.394455 3.000000
      vertex 108.774750 152.419495 1.500000
      vertex 108.774750 152.419495 3.000000
    endloop
  endfacet
  facet normal 0.519094 0.854717 -0.000000
    outer loop
      vertex 108.815979 152.394455 1.500000
      vertex 108.774750 152.419495 1.500000
      vertex 108.815979 152.394455 3.000000
    endloop
  endfacet
  facet normal 0.434080 0.900874 0.000000
    outer loop
      vertex 108.859680 152.373398 3.000000
      vertex 108.815979 152.394455 1.500000
      vertex 108.815979 152.394455 3.000000
    endloop
  endfacet
  facet normal 0.434080 0.900874 -0.000000
    outer loop
      vertex 108.859680 152.373398 1.500000
      vertex 108.815979 152.394455 1.500000
      vertex 108.859680 152.373398 3.000000
    endloop
  endfacet
  facet normal 0.343696 0.939081 0.000000
    outer loop
      vertex 108.905624 152.356583 3.000000
      vertex 108.859680 152.373398 1.500000
      vertex 108.859680 152.373398 3.000000
    endloop
  endfacet
  facet normal 0.343696 0.939081 -0.000000
    outer loop
      vertex 108.905624 152.356583 1.500000
      vertex 108.859680 152.373398 1.500000
      vertex 108.905624 152.356583 3.000000
    endloop
  endfacet
  facet normal 0.248917 0.968525 0.000000
    outer loop
      vertex 108.953537 152.344269 3.000000
      vertex 108.905624 152.356583 1.500000
      vertex 108.905624 152.356583 3.000000
    endloop
  endfacet
  facet normal 0.248917 0.968525 -0.000000
    outer loop
      vertex 108.953537 152.344269 1.500000
      vertex 108.905624 152.356583 1.500000
      vertex 108.953537 152.344269 3.000000
    endloop
  endfacet
  facet normal 0.151007 0.988533 0.000000
    outer loop
      vertex 109.003181 152.336685 3.000000
      vertex 108.953537 152.344269 1.500000
      vertex 108.953537 152.344269 3.000000
    endloop
  endfacet
  facet normal 0.151007 0.988533 -0.000000
    outer loop
      vertex 109.003181 152.336685 1.500000
      vertex 108.953537 152.344269 1.500000
      vertex 109.003181 152.336685 3.000000
    endloop
  endfacet
  facet normal 0.050376 0.998730 0.000000
    outer loop
      vertex 109.054306 152.334106 3.000000
      vertex 109.003181 152.336685 1.500000
      vertex 109.003181 152.336685 3.000000
    endloop
  endfacet
  facet normal 0.000000 1.000000 0.000000
    outer loop
      vertex 114.054306 152.334106 3.000000
      vertex 114.054306 152.334106 0.000000
      vertex 109.054306 152.334106 0.000000
    endloop
  endfacet
  facet normal -0.000000 1.000000 0.000000
    outer loop
      vertex 109.054306 152.334106 3.000000
      vertex 114.054306 152.334106 3.000000
      vertex 109.054306 152.334106 0.000000
    endloop
  endfacet
  facet normal -0.998730 0.050384 0.000000
    outer loop
      vertex 114.551727 152.782990 1.500000
      vertex 114.554306 152.834106 3.000000
      vertex 114.554306 152.834106 0.000000
    endloop
  endfacet
  facet normal -0.998730 0.050384 0.000000
    outer loop
      vertex 114.551727 152.782990 0.000000
      vertex 114.551727 152.782990 1.500000
      vertex 114.554306 152.834106 0.000000
    endloop
  endfacet
  facet normal -0.988559 0.150836 0.000000
    outer loop
      vertex 114.544151 152.733337 0.000000
      vertex 114.551727 152.782990 1.500000
      vertex 114.551727 152.782990 0.000000
    endloop
  endfacet
  facet normal -0.988559 0.150836 0.000000
    outer loop
      vertex 114.544151 152.733337 1.500000
      vertex 114.551727 152.782990 1.500000
      vertex 114.544151 152.733337 0.000000
    endloop
  endfacet
  facet normal -0.968488 0.249062 0.000000
    outer loop
      vertex 114.531830 152.685425 0.000000
      vertex 114.544151 152.733337 1.500000
      vertex 114.544151 152.733337 0.000000
    endloop
  endfacet
  facet normal -0.968488 0.249062 0.000000
    outer loop
      vertex 114.531830 152.685425 1.500000
      vertex 114.544151 152.733337 1.500000
      vertex 114.531830 152.685425 0.000000
    endloop
  endfacet
  facet normal -0.939081 0.343696 0.000000
    outer loop
      vertex 114.515015 152.639481 0.000000
      vertex 114.531830 152.685425 1.500000
      vertex 114.531830 152.685425 0.000000
    endloop
  endfacet
  facet normal -0.939081 0.343696 0.000000
    outer loop
      vertex 114.515015 152.639481 1.500000
      vertex 114.531830 152.685425 1.500000
      vertex 114.515015 152.639481 0.000000
    endloop
  endfacet
  facet normal -0.900874 0.434080 0.000000
    outer loop
      vertex 114.493958 152.595779 0.000000
      vertex 114.515015 152.639481 1.500000
      vertex 114.515015 152.639481 0.000000
    endloop
  endfacet
  facet normal -0.900874 0.434080 0.000000
    outer loop
      vertex 114.493958 152.595779 1.500000
      vertex 114.515015 152.639481 1.500000
      vertex 114.493958 152.595779 0.000000
    endloop
  endfacet
  facet normal -0.854647 0.519209 0.000000
    outer loop
      vertex 114.468910 152.554550 0.000000
      vertex 114.493958 152.595779 1.500000
      vertex 114.493958 152.595779 0.000000
    endloop
  endfacet
  facet normal -0.854647 0.519209 0.000000
    outer loop
      vertex 114.468910 152.554550 1.500000
      vertex 114.493958 152.595779 1.500000
      vertex 114.468910 152.554550 0.000000
    endloop
  endfacet
  facet normal -0.800838 0.598882 0.000000
    outer loop
      vertex 114.440132 152.516068 0.000000
      vertex 114.468910 152.554550 1.500000
      vertex 114.468910 152.554550 0.000000
    endloop
  endfacet
  facet normal -0.800838 0.598882 0.000000
    outer loop
      vertex 114.440132 152.516068 1.500000
      vertex 114.468910 152.554550 1.500000
      vertex 114.440132 152.516068 0.000000
    endloop
  endfacet
  facet normal -0.740012 0.672594 0.000000
    outer loop
      vertex 114.407860 152.480560 0.000000
      vertex 114.440132 152.516068 1.500000
      vertex 114.440132 152.516068 0.000000
    endloop
  endfacet
  facet normal -0.740012 0.672594 0.000000
    outer loop
      vertex 114.407860 152.480560 1.500000
      vertex 114.440132 152.516068 1.500000
      vertex 114.407860 152.480560 0.000000
    endloop
  endfacet
  facet normal -0.672594 0.740012 0.000000
    outer loop
      vertex 114.372353 152.448288 0.000000
      vertex 114.407860 152.480560 1.500000
      vertex 114.407860 152.480560 0.000000
    endloop
  endfacet
  facet normal -0.672594 0.740012 0.000000
    outer loop
      vertex 114.372353 152.448288 1.500000
      vertex 114.407860 152.480560 1.500000
      vertex 114.372353 152.448288 0.000000
    endloop
  endfacet
  facet normal -0.599009 0.800742 0.000000
    outer loop
      vertex 114.333862 152.419495 0.000000
      vertex 114.372353 152.448288 1.500000
      vertex 114.372353 152.448288 0.000000
    endloop
  endfacet
  facet normal -0.599009 0.800742 0.000000
    outer loop
      vertex 114.333862 152.419495 1.500000
      vertex 114.372353 152.448288 1.500000
      vertex 114.333862 152.419495 0.000000
    endloop
  endfacet
  facet normal -0.519094 0.854717 0.000000
    outer loop
      vertex 114.292633 152.394455 0.000000
      vertex 114.333862 152.419495 1.500000
      vertex 114.333862 152.419495 0.000000
    endloop
  endfacet
  facet normal -0.519094 0.854717 0.000000
    outer loop
      vertex 114.292633 152.394455 1.500000
      vertex 114.333862 152.419495 1.500000
      vertex 114.292633 152.394455 0.000000
    endloop
  endfacet
  facet normal -0.434080 0.900874 0.000000
    outer loop
      vertex 114.248932 152.373398 0.000000
      vertex 114.292633 152.394455 1.500000
      vertex 114.292633 152.394455 0.000000
    endloop
  endfacet
  facet normal -0.434080 0.900874 0.000000
    outer loop
      vertex 114.248932 152.373398 1.500000
      vertex 114.292633 152.394455 1.500000
      vertex 114.248932 152.373398 0.000000
    endloop
  endfacet
  facet normal -0.343696 0.939081 0.000000
    outer loop
      vertex 114.202988 152.356583 0.000000
      vertex 114.248932 152.373398 1.500000
      vertex 114.248932 152.373398 0.000000
    endloop
  endfacet
  facet normal -0.343696 0.939081 0.000000
    outer loop
      vertex 114.202988 152.356583 1.500000
      vertex 114.248932 152.373398 1.500000
      vertex 114.202988 152.356583 0.000000
    endloop
  endfacet
  facet normal -0.248917 0.968525 0.000000
    outer loop
      vertex 114.155075 152.344269 0.000000
      vertex 114.202988 152.356583 1.500000
      vertex 114.202988 152.356583 0.000000
    endloop
  endfacet
  facet normal -0.248917 0.968525 0.000000
    outer loop
      vertex 114.155075 152.344269 1.500000
      vertex 114.202988 152.356583 1.500000
      vertex 114.155075 152.344269 0.000000
    endloop
  endfacet
  facet normal -0.151007 0.988533 0.000000
    outer loop
      vertex 114.105431 152.336685 0.000000
      vertex 114.155075 152.344269 1.500000
      vertex 114.155075 152.344269 0.000000
    endloop
  endfacet
  facet normal -0.151007 0.988533 0.000000
    outer loop
      vertex 114.105431 152.336685 1.500000
      vertex 114.155075 152.344269 1.500000
      vertex 114.105431 152.336685 0.000000
    endloop
  endfacet
  facet normal -0.050376 0.998730 0.000000
    outer loop
      vertex 114.054306 152.334106 0.000000
      vertex 114.105431 152.336685 1.500000
      vertex 114.105431 152.336685 0.000000
    endloop
  endfacet
  facet normal -0.050376 0.998730 0.000000
    outer loop
      vertex 114.054306 152.334106 3.000000
      vertex 114.105431 152.336685 1.500000
      vertex 114.054306 152.334106 0.000000
    endloop
  endfacet
  facet normal -0.050376 0.998730 0.000000
    outer loop
      vertex 114.105431 152.336685 1.500000
      vertex 114.054306 152.334106 3.000000
      vertex 114.105431 152.336685 3.000000
    endloop
  endfacet
  facet normal -0.151007 0.988533 0.000000
    outer loop
      vertex 114.155075 152.344269 3.000000
      vertex 114.105431 152.336685 1.500000
      vertex 114.105431 152.336685 3.000000
    endloop
  endfacet
  facet normal -0.151007 0.988533 0.000000
    outer loop
      vertex 114.155075 152.344269 1.500000
      vertex 114.105431 152.336685 1.500000
      vertex 114.155075 152.344269 3.000000
    endloop
  endfacet
  facet normal -0.248917 0.968525 0.000000
    outer loop
      vertex 114.202988 152.356583 3.000000
      vertex 114.155075 152.344269 1.500000
      vertex 114.155075 152.344269 3.000000
    endloop
  endfacet
  facet normal -0.248917 0.968525 0.000000
    outer loop
      vertex 114.202988 152.356583 1.500000
      vertex 114.155075 152.344269 1.500000
      vertex 114.202988 152.356583 3.000000
    endloop
  endfacet
  facet normal -0.343696 0.939081 0.000000
    outer loop
      vertex 114.248932 152.373398 3.000000
      vertex 114.202988 152.356583 1.500000
      vertex 114.202988 152.356583 3.000000
    endloop
  endfacet
  facet normal -0.343696 0.939081 0.000000
    outer loop
      vertex 114.248932 152.373398 1.500000
      vertex 114.202988 152.356583 1.500000
      vertex 114.248932 152.373398 3.000000
    endloop
  endfacet
  facet normal -0.434080 0.900874 0.000000
    outer loop
      vertex 114.292633 152.394455 3.000000
      vertex 114.248932 152.373398 1.500000
      vertex 114.248932 152.373398 3.000000
    endloop
  endfacet
  facet normal -0.434080 0.900874 0.000000
    outer loop
      vertex 114.292633 152.394455 1.500000
      vertex 114.248932 152.373398 1.500000
      vertex 114.292633 152.394455 3.000000
    endloop
  endfacet
  facet normal -0.519094 0.854717 0.000000
    outer loop
      vertex 114.333862 152.419495 3.000000
      vertex 114.292633 152.394455 1.500000
      vertex 114.292633 152.394455 3.000000
    endloop
  endfacet
  facet normal -0.519094 0.854717 0.000000
    outer loop
      vertex 114.333862 152.419495 1.500000
      vertex 114.292633 152.394455 1.500000
      vertex 114.333862 152.419495 3.000000
    endloop
  endfacet
  facet normal -0.599009 0.800742 0.000000
    outer loop
      vertex 114.372353 152.448288 3.000000
      vertex 114.333862 152.419495 1.500000
      vertex 114.333862 152.419495 3.000000
    endloop
  endfacet
  facet normal -0.599009 0.800742 0.000000
    outer loop
      vertex 114.372353 152.448288 1.500000
      vertex 114.333862 152.419495 1.500000
      vertex 114.372353 152.448288 3.000000
    endloop
  endfacet
  facet normal -0.672594 0.740012 0.000000
    outer loop
      vertex 114.407860 152.480560 3.000000
      vertex 114.372353 152.448288 1.500000
      vertex 114.372353 152.448288 3.000000
    endloop
  endfacet
  facet normal -0.672594 0.740012 0.000000
    outer loop
      vertex 114.407860 152.480560 1.500000
      vertex 114.372353 152.448288 1.500000
      vertex 114.407860 152.480560 3.000000
    endloop
  endfacet
  facet normal -0.740012 0.672594 0.000000
    outer loop
      vertex 114.440132 152.516068 3.000000
      vertex 114.407860 152.480560 1.500000
      vertex 114.407860 152.480560 3.000000
    endloop
  endfacet
  facet normal -0.740012 0.672594 0.000000
    outer loop
      vertex 114.440132 152.516068 1.500000
      vertex 114.407860 152.480560 1.500000
      vertex 114.440132 152.516068 3.000000
    endloop
  endfacet
  facet normal -0.800838 0.598882 0.000000
    outer loop
      vertex 114.468910 152.554550 3.000000
      vertex 114.440132 152.516068 1.500000
      vertex 114.440132 152.516068 3.000000
    endloop
  endfacet
  facet normal -0.800838 0.598882 0.000000
    outer loop
      vertex 114.468910 152.554550 1.500000
      vertex 114.440132 152.516068 1.500000
      vertex 114.468910 152.554550 3.000000
    endloop
  endfacet
  facet normal -0.854647 0.519209 0.000000
    outer loop
      vertex 114.493958 152.595779 3.000000
      vertex 114.468910 152.554550 1.500000
      vertex 114.468910 152.554550 3.000000
    endloop
  endfacet
  facet normal -0.854647 0.519209 0.000000
    outer loop
      vertex 114.493958 152.595779 1.500000
      vertex 114.468910 152.554550 1.500000
      vertex 114.493958 152.595779 3.000000
    endloop
  endfacet
  facet normal -0.900874 0.434080 0.000000
    outer loop
      vertex 114.515015 152.639481 3.000000
      vertex 114.493958 152.595779 1.500000
      vertex 114.493958 152.595779 3.000000
    endloop
  endfacet
  facet normal -0.900874 0.434080 0.000000
    outer loop
      vertex 114.515015 152.639481 1.500000
      vertex 114.493958 152.595779 1.500000
      vertex 114.515015 152.639481 3.000000
    endloop
  endfacet
  facet normal -0.939081 0.343696 0.000000
    outer loop
      vertex 114.531830 152.685425 3.000000
      vertex 114.515015 152.639481 1.500000
      vertex 114.515015 152.639481 3.000000
    endloop
  endfacet
  facet normal -0.939081 0.343696 0.000000
    outer loop
      vertex 114.531830 152.685425 1.500000
      vertex 114.515015 152.639481 1.500000
      vertex 114.531830 152.685425 3.000000
    endloop
  endfacet
  facet normal -0.968488 0.249062 0.000000
    outer loop
      vertex 114.544151 152.733337 3.000000
      vertex 114.531830 152.685425 1.500000
      vertex 114.531830 152.685425 3.000000
    endloop
  endfacet
  facet normal -0.968488 0.249062 0.000000
    outer loop
      vertex 114.544151 152.733337 1.500000
      vertex 114.531830 152.685425 1.500000
      vertex 114.544151 152.733337 3.000000
    endloop
  endfacet
  facet normal -0.988559 0.150836 0.000000
    outer loop
      vertex 114.551727 152.782990 3.000000
      vertex 114.544151 152.733337 1.500000
      vertex 114.544151 152.733337 3.000000
    endloop
  endfacet
  facet normal -0.988559 0.150836 0.000000
    outer loop
      vertex 114.551727 152.782990 1.500000
      vertex 114.544151 152.733337 1.500000
      vertex 114.551727 152.782990 3.000000
    endloop
  endfacet
  facet normal -0.998730 0.050384 0.000000
    outer loop
      vertex 114.554306 152.834106 3.000000
      vertex 114.551727 152.782990 1.500000
      vertex 114.551727 152.782990 3.000000
    endloop
  endfacet
  facet normal -1.000000 0.000000 -0.000000
    outer loop
      vertex 114.554306 164.084000 3.000000
      vertex 114.554306 164.084000 0.000000
      vertex 114.554306 152.834106 0.000000
    endloop
  endfacet
  facet normal -1.000000 0.000000 0.000000
    outer loop
      vertex 114.554306 152.834106 3.000000
      vertex 114.554306 164.084000 3.000000
      vertex 114.554306 152.834106 0.000000
    endloop
  endfacet
  facet normal 0.866243 -0.499622 0.000000
    outer loop
      vertex 157.924652 74.011238 3.000000
      vertex 157.924652 74.011238 0.000000
      vertex 182.395859 116.439316 0.000000
    endloop
  endfacet
  facet normal 0.866243 -0.499622 0.000000
    outer loop
      vertex 182.395859 116.439316 3.000000
      vertex 157.924652 74.011238 3.000000
      vertex 182.395859 116.439316 0.000000
    endloop
  endfacet
  facet normal 0.334194 -0.942504 0.000000
    outer loop
      vertex 156.547043 72.769890 3.000000
      vertex 156.103241 72.612526 3.000000
      vertex 156.103241 72.612526 0.000000
    endloop
  endfacet
  facet normal 0.334194 -0.942504 0.000000
    outer loop
      vertex 156.547043 72.769890 0.000000
      vertex 156.547043 72.769890 3.000000
      vertex 156.103241 72.612526 0.000000
    endloop
  endfacet
  facet normal 0.477526 -0.878618 0.000000
    outer loop
      vertex 156.960815 72.994774 3.000000
      vertex 156.547043 72.769890 3.000000
      vertex 156.547043 72.769890 0.000000
    endloop
  endfacet
  facet normal 0.477526 -0.878618 0.000000
    outer loop
      vertex 156.960815 72.994774 0.000000
      vertex 156.960815 72.994774 3.000000
      vertex 156.547043 72.769890 0.000000
    endloop
  endfacet
  facet normal 0.609060 -0.793124 0.000000
    outer loop
      vertex 157.334305 73.281586 3.000000
      vertex 156.960815 72.994774 3.000000
      vertex 156.960815 72.994774 0.000000
    endloop
  endfacet
  facet normal 0.609060 -0.793124 0.000000
    outer loop
      vertex 157.334305 73.281586 0.000000
      vertex 157.334305 73.281586 3.000000
      vertex 156.960815 72.994774 0.000000
    endloop
  endfacet
  facet normal 0.725638 -0.688076 0.000000
    outer loop
      vertex 157.658264 73.623230 3.000000
      vertex 157.334305 73.281586 3.000000
      vertex 157.334305 73.281586 0.000000
    endloop
  endfacet
  facet normal 0.725638 -0.688076 0.000000
    outer loop
      vertex 157.658264 73.623230 0.000000
      vertex 157.658264 73.623230 3.000000
      vertex 157.334305 73.281586 0.000000
    endloop
  endfacet
  facet normal 0.824406 -0.565998 0.000000
    outer loop
      vertex 157.924652 74.011238 3.000000
      vertex 157.658264 73.623230 3.000000
      vertex 157.658264 73.623230 0.000000
    endloop
  endfacet
  facet normal 0.824406 -0.565998 0.000000
    outer loop
      vertex 157.924652 74.011238 0.000000
      vertex 157.924652 74.011238 3.000000
      vertex 157.658264 73.623230 0.000000
    endloop
  endfacet
  facet normal -0.441837 -0.897095 -0.000000
    outer loop
      vertex 153.826370 72.911903 3.000000
      vertex 153.826370 72.911903 0.000000
      vertex 154.181320 72.737083 0.000000
    endloop
  endfacet
  facet normal -0.441837 -0.897095 -0.000000
    outer loop
      vertex 154.181320 72.737083 3.000000
      vertex 153.826370 72.911903 3.000000
      vertex 154.181320 72.737083 0.000000
    endloop
  endfacet
  facet normal -0.320257 -0.947331 0.000000
    outer loop
      vertex 154.552948 72.611450 0.000000
      vertex 154.181320 72.737083 3.000000
      vertex 154.181320 72.737083 0.000000
    endloop
  endfacet
  facet normal -0.320257 -0.947331 -0.000000
    outer loop
      vertex 154.552948 72.611450 3.000000
      vertex 154.181320 72.737083 3.000000
      vertex 154.552948 72.611450 0.000000
    endloop
  endfacet
  facet normal -0.194099 -0.980982 0.000000
    outer loop
      vertex 154.936188 72.535622 0.000000
      vertex 154.552948 72.611450 3.000000
      vertex 154.552948 72.611450 0.000000
    endloop
  endfacet
  facet normal -0.194099 -0.980982 -0.000000
    outer loop
      vertex 154.936188 72.535622 3.000000
      vertex 154.552948 72.611450 3.000000
      vertex 154.936188 72.535622 0.000000
    endloop
  endfacet
  facet normal -0.065053 -0.997882 0.000000
    outer loop
      vertex 155.326019 72.510208 0.000000
      vertex 154.936188 72.535622 3.000000
      vertex 154.936188 72.535622 0.000000
    endloop
  endfacet
  facet normal -0.065053 -0.997882 -0.000000
    outer loop
      vertex 155.326019 72.510208 3.000000
      vertex 154.936188 72.535622 3.000000
      vertex 155.326019 72.510208 0.000000
    endloop
  endfacet
  facet normal 0.065054 -0.997882 0.000000
    outer loop
      vertex 155.716431 72.535660 0.000000
      vertex 155.326019 72.510208 3.000000
      vertex 155.326019 72.510208 0.000000
    endloop
  endfacet
  facet normal 0.065054 -0.997882 0.000000
    outer loop
      vertex 155.716431 72.535660 3.000000
      vertex 155.326019 72.510208 3.000000
      vertex 155.716431 72.535660 0.000000
    endloop
  endfacet
  facet normal 0.194907 -0.980822 0.000000
    outer loop
      vertex 156.103241 72.612526 0.000000
      vertex 155.716431 72.535660 3.000000
      vertex 155.716431 72.535660 0.000000
    endloop
  endfacet
  facet normal 0.194907 -0.980822 0.000000
    outer loop
      vertex 156.103241 72.612526 3.000000
      vertex 155.716431 72.535660 3.000000
      vertex 156.103241 72.612526 0.000000
    endloop
  endfacet
  facet normal -0.499869 -0.866101 -0.000000
    outer loop
      vertex 151.227386 74.411903 3.000000
      vertex 151.227386 74.411903 0.000000
      vertex 153.826370 72.911903 0.000000
    endloop
  endfacet
  facet normal -0.499869 -0.866101 -0.000000
    outer loop
      vertex 153.826370 72.911903 3.000000
      vertex 151.227386 74.411903 3.000000
      vertex 153.826370 72.911903 0.000000
    endloop
  endfacet
  facet normal -0.140899 -0.990024 -0.000000
    outer loop
      vertex 100.413780 87.483971 3.000000
      vertex 100.413780 87.483971 0.000000
      vertex 102.892342 87.131226 0.000000
    endloop
  endfacet
  facet normal -0.140899 -0.990024 -0.000000
    outer loop
      vertex 102.892342 87.131226 3.000000
      vertex 100.413780 87.483971 3.000000
      vertex 102.892342 87.131226 0.000000
    endloop
  endfacet
  facet normal -0.126308 -0.991991 0.000000
    outer loop
      vertex 105.375107 86.815102 0.000000
      vertex 102.892342 87.131226 3.000000
      vertex 102.892342 87.131226 0.000000
    endloop
  endfacet
  facet normal -0.126308 -0.991991 -0.000000
    outer loop
      vertex 105.375107 86.815102 3.000000
      vertex 102.892342 87.131226 3.000000
      vertex 105.375107 86.815102 0.000000
    endloop
  endfacet
  facet normal -0.116580 -0.993181 0.000000
    outer loop
      vertex 107.848114 86.524818 0.000000
      vertex 105.375107 86.815102 3.000000
      vertex 105.375107 86.815102 0.000000
    endloop
  endfacet
  facet normal -0.116580 -0.993181 -0.000000
    outer loop
      vertex 107.848114 86.524818 3.000000
      vertex 105.375107 86.815102 3.000000
      vertex 107.848114 86.524818 0.000000
    endloop
  endfacet
  facet normal -0.111665 -0.993746 0.000000
    outer loop
      vertex 110.297417 86.249596 0.000000
      vertex 107.848114 86.524818 3.000000
      vertex 107.848114 86.524818 0.000000
    endloop
  endfacet
  facet normal -0.111665 -0.993746 -0.000000
    outer loop
      vertex 110.297417 86.249596 3.000000
      vertex 107.848114 86.524818 3.000000
      vertex 110.297417 86.249596 0.000000
    endloop
  endfacet
  facet normal -0.113799 -0.993504 0.000000
    outer loop
      vertex 114.987381 85.712395 0.000000
      vertex 110.297417 86.249596 3.000000
      vertex 110.297417 86.249596 0.000000
    endloop
  endfacet
  facet normal -0.113799 -0.993504 -0.000000
    outer loop
      vertex 114.987381 85.712395 3.000000
      vertex 110.297417 86.249596 3.000000
      vertex 114.987381 85.712395 0.000000
    endloop
  endfacet
  facet normal -0.124773 -0.992185 0.000000
    outer loop
      vertex 117.355804 85.414551 0.000000
      vertex 114.987381 85.712395 3.000000
      vertex 114.987381 85.712395 0.000000
    endloop
  endfacet
  facet normal -0.124773 -0.992185 -0.000000
    outer loop
      vertex 117.355804 85.414551 3.000000
      vertex 114.987381 85.712395 3.000000
      vertex 117.355804 85.414551 0.000000
    endloop
  endfacet
  facet normal -0.137691 -0.990475 0.000000
    outer loop
      vertex 119.744423 85.082497 0.000000
      vertex 117.355804 85.414551 3.000000
      vertex 117.355804 85.414551 0.000000
    endloop
  endfacet
  facet normal -0.137691 -0.990475 -0.000000
    outer loop
      vertex 119.744423 85.082497 3.000000
      vertex 117.355804 85.414551 3.000000
      vertex 119.744423 85.082497 0.000000
    endloop
  endfacet
  facet normal -0.154537 -0.987987 0.000000
    outer loop
      vertex 122.156654 84.705185 0.000000
      vertex 119.744423 85.082497 3.000000
      vertex 119.744423 85.082497 0.000000
    endloop
  endfacet
  facet normal -0.154537 -0.987987 -0.000000
    outer loop
      vertex 122.156654 84.705185 3.000000
      vertex 119.744423 85.082497 3.000000
      vertex 122.156654 84.705185 0.000000
    endloop
  endfacet
  facet normal -0.175010 -0.984567 0.000000
    outer loop
      vertex 124.595909 84.271599 0.000000
      vertex 122.156654 84.705185 3.000000
      vertex 122.156654 84.705185 0.000000
    endloop
  endfacet
  facet normal -0.175010 -0.984567 -0.000000
    outer loop
      vertex 124.595909 84.271599 3.000000
      vertex 122.156654 84.705185 3.000000
      vertex 124.595909 84.271599 0.000000
    endloop
  endfacet
  facet normal -0.198776 -0.980045 0.000000
    outer loop
      vertex 127.065620 83.770683 0.000000
      vertex 124.595909 84.271599 3.000000
      vertex 124.595909 84.271599 0.000000
    endloop
  endfacet
  facet normal -0.198776 -0.980045 -0.000000
    outer loop
      vertex 127.065620 83.770683 3.000000
      vertex 124.595909 84.271599 3.000000
      vertex 127.065620 83.770683 0.000000
    endloop
  endfacet
  facet normal -0.218402 -0.975859 0.000000
    outer loop
      vertex 128.312958 83.491524 0.000000
      vertex 127.065620 83.770683 3.000000
      vertex 127.065620 83.770683 0.000000
    endloop
  endfacet
  facet normal -0.218402 -0.975859 -0.000000
    outer loop
      vertex 128.312958 83.491524 3.000000
      vertex 127.065620 83.770683 3.000000
      vertex 128.312958 83.491524 0.000000
    endloop
  endfacet
  facet normal -0.232362 -0.972629 0.000000
    outer loop
      vertex 129.569199 83.191406 0.000000
      vertex 128.312958 83.491524 3.000000
      vertex 128.312958 83.491524 0.000000
    endloop
  endfacet
  facet normal -0.232362 -0.972629 -0.000000
    outer loop
      vertex 129.569199 83.191406 3.000000
      vertex 128.312958 83.491524 3.000000
      vertex 129.569199 83.191406 0.000000
    endloop
  endfacet
  facet normal -0.246918 -0.969036 0.000000
    outer loop
      vertex 130.834747 82.868935 0.000000
      vertex 129.569199 83.191406 3.000000
      vertex 129.569199 83.191406 0.000000
    endloop
  endfacet
  facet normal -0.246918 -0.969036 -0.000000
    outer loop
      vertex 130.834747 82.868935 3.000000
      vertex 129.569199 83.191406 3.000000
      vertex 130.834747 82.868935 0.000000
    endloop
  endfacet
  facet normal -0.261980 -0.965073 0.000000
    outer loop
      vertex 132.110062 82.522736 0.000000
      vertex 130.834747 82.868935 3.000000
      vertex 130.834747 82.868935 0.000000
    endloop
  endfacet
  facet normal -0.261980 -0.965073 -0.000000
    outer loop
      vertex 132.110062 82.522736 3.000000
      vertex 130.834747 82.868935 3.000000
      vertex 132.110062 82.522736 0.000000
    endloop
  endfacet
  facet normal -0.277503 -0.960725 0.000000
    outer loop
      vertex 133.395538 82.151428 0.000000
      vertex 132.110062 82.522736 3.000000
      vertex 132.110062 82.522736 0.000000
    endloop
  endfacet
  facet normal -0.277503 -0.960725 -0.000000
    outer loop
      vertex 133.395538 82.151428 3.000000
      vertex 132.110062 82.522736 3.000000
      vertex 133.395538 82.151428 0.000000
    endloop
  endfacet
  facet normal -0.293414 -0.955986 0.000000
    outer loop
      vertex 134.691620 81.753632 0.000000
      vertex 133.395538 82.151428 3.000000
      vertex 133.395538 82.151428 0.000000
    endloop
  endfacet
  facet normal -0.293414 -0.955986 -0.000000
    outer loop
      vertex 134.691620 81.753632 3.000000
      vertex 133.395538 82.151428 3.000000
      vertex 134.691620 81.753632 0.000000
    endloop
  endfacet
  facet normal -0.309640 -0.950854 0.000000
    outer loop
      vertex 135.998749 81.327972 0.000000
      vertex 134.691620 81.753632 3.000000
      vertex 134.691620 81.753632 0.000000
    endloop
  endfacet
  facet normal -0.309640 -0.950854 -0.000000
    outer loop
      vertex 135.998749 81.327972 3.000000
      vertex 134.691620 81.753632 3.000000
      vertex 135.998749 81.327972 0.000000
    endloop
  endfacet
  facet normal -0.326138 -0.945322 0.000000
    outer loop
      vertex 137.317322 80.873062 0.000000
      vertex 135.998749 81.327972 3.000000
      vertex 135.998749 81.327972 0.000000
    endloop
  endfacet
  facet normal -0.326138 -0.945322 -0.000000
    outer loop
      vertex 137.317322 80.873062 3.000000
      vertex 135.998749 81.327972 3.000000
      vertex 137.317322 80.873062 0.000000
    endloop
  endfacet
  facet normal -0.342822 -0.939400 0.000000
    outer loop
      vertex 138.647781 80.387527 0.000000
      vertex 137.317322 80.873062 3.000000
      vertex 137.317322 80.873062 0.000000
    endloop
  endfacet
  facet normal -0.342822 -0.939400 -0.000000
    outer loop
      vertex 138.647781 80.387527 3.000000
      vertex 137.317322 80.873062 3.000000
      vertex 138.647781 80.387527 0.000000
    endloop
  endfacet
  facet normal -0.359634 -0.933093 0.000000
    outer loop
      vertex 139.990570 79.869987 0.000000
      vertex 138.647781 80.387527 3.000000
      vertex 138.647781 80.387527 0.000000
    endloop
  endfacet
  facet normal -0.359634 -0.933093 -0.000000
    outer loop
      vertex 139.990570 79.869987 3.000000
      vertex 138.647781 80.387527 3.000000
      vertex 139.990570 79.869987 0.000000
    endloop
  endfacet
  facet normal -0.376523 -0.926407 0.000000
    outer loop
      vertex 141.346085 79.319061 0.000000
      vertex 139.990570 79.869987 3.000000
      vertex 139.990570 79.869987 0.000000
    endloop
  endfacet
  facet normal -0.376523 -0.926407 -0.000000
    outer loop
      vertex 141.346085 79.319061 3.000000
      vertex 139.990570 79.869987 3.000000
      vertex 141.346085 79.319061 0.000000
    endloop
  endfacet
  facet normal -0.393417 -0.919360 0.000000
    outer loop
      vertex 142.714767 78.733368 0.000000
      vertex 141.346085 79.319061 3.000000
      vertex 141.346085 79.319061 0.000000
    endloop
  endfacet
  facet normal -0.393417 -0.919360 -0.000000
    outer loop
      vertex 142.714767 78.733368 3.000000
      vertex 141.346085 79.319061 3.000000
      vertex 142.714767 78.733368 0.000000
    endloop
  endfacet
  facet normal -0.410256 -0.911970 0.000000
    outer loop
      vertex 144.097061 78.111534 0.000000
      vertex 142.714767 78.733368 3.000000
      vertex 142.714767 78.733368 0.000000
    endloop
  endfacet
  facet normal -0.410256 -0.911970 -0.000000
    outer loop
      vertex 144.097061 78.111534 3.000000
      vertex 142.714767 78.733368 3.000000
      vertex 144.097061 78.111534 0.000000
    endloop
  endfacet
  facet normal -0.427005 -0.904249 0.000000
    outer loop
      vertex 145.493362 77.452171 0.000000
      vertex 144.097061 78.111534 3.000000
      vertex 144.097061 78.111534 0.000000
    endloop
  endfacet
  facet normal -0.427005 -0.904249 -0.000000
    outer loop
      vertex 145.493362 77.452171 3.000000
      vertex 144.097061 78.111534 3.000000
      vertex 145.493362 77.452171 0.000000
    endloop
  endfacet
  facet normal -0.443592 -0.896229 0.000000
    outer loop
      vertex 146.904129 76.753906 0.000000
      vertex 145.493362 77.452171 3.000000
      vertex 145.493362 77.452171 0.000000
    endloop
  endfacet
  facet normal -0.443592 -0.896229 -0.000000
    outer loop
      vertex 146.904129 76.753906 3.000000
      vertex 145.493362 77.452171 3.000000
      vertex 146.904129 76.753906 0.000000
    endloop
  endfacet
  facet normal -0.459986 -0.887926 0.000000
    outer loop
      vertex 148.329773 76.015358 0.000000
      vertex 146.904129 76.753906 3.000000
      vertex 146.904129 76.753906 0.000000
    endloop
  endfacet
  facet normal -0.459986 -0.887926 -0.000000
    outer loop
      vertex 148.329773 76.015358 3.000000
      vertex 146.904129 76.753906 3.000000
      vertex 148.329773 76.015358 0.000000
    endloop
  endfacet
  facet normal -0.476141 -0.879369 0.000000
    outer loop
      vertex 149.770706 75.235153 0.000000
      vertex 148.329773 76.015358 3.000000
      vertex 148.329773 76.015358 0.000000
    endloop
  endfacet
  facet normal -0.476141 -0.879369 -0.000000
    outer loop
      vertex 149.770706 75.235153 3.000000
      vertex 148.329773 76.015358 3.000000
      vertex 149.770706 75.235153 0.000000
    endloop
  endfacet
  facet normal -0.492016 -0.870586 0.000000
    outer loop
      vertex 151.227386 74.411903 0.000000
      vertex 149.770706 75.235153 3.000000
      vertex 149.770706 75.235153 0.000000
    endloop
  endfacet
  facet normal -0.492016 -0.870586 -0.000000
    outer loop
      vertex 151.227386 74.411903 3.000000
      vertex 149.770706 75.235153 3.000000
      vertex 151.227386 74.411903 0.000000
    endloop
  endfacet
  facet normal -0.150109 -0.988670 -0.000000
    outer loop
      vertex 97.862793 87.871284 3.000000
      vertex 97.862793 87.871284 0.000000
      vertex 100.413780 87.483971 0.000000
    endloop
  endfacet
  facet normal -0.150109 -0.988670 -0.000000
    outer loop
      vertex 100.413780 87.483971 3.000000
      vertex 97.862793 87.871284 3.000000
      vertex 100.413780 87.483971 0.000000
    endloop
  endfacet
  facet normal -0.998966 -0.045470 -0.000000
    outer loop
      vertex 95.313316 90.837059 3.000000
      vertex 95.313316 90.837059 0.000000
      vertex 95.325844 90.561836 0.000000
    endloop
  endfacet
  facet normal -0.998966 -0.045470 -0.000000
    outer loop
      vertex 95.325844 90.561836 3.000000
      vertex 95.313316 90.837059 3.000000
      vertex 95.325844 90.561836 0.000000
    endloop
  endfacet
  facet normal -0.990716 -0.135948 0.000000
    outer loop
      vertex 95.362732 90.293015 0.000000
      vertex 95.325844 90.561836 3.000000
      vertex 95.325844 90.561836 0.000000
    endloop
  endfacet
  facet normal -0.990716 -0.135948 -0.000000
    outer loop
      vertex 95.362732 90.293015 3.000000
      vertex 95.325844 90.561836 3.000000
      vertex 95.362732 90.293015 0.000000
    endloop
  endfacet
  facet normal -0.974428 -0.224702 0.000000
    outer loop
      vertex 95.422966 90.031807 0.000000
      vertex 95.362732 90.293015 3.000000
      vertex 95.362732 90.293015 0.000000
    endloop
  endfacet
  facet normal -0.974428 -0.224702 -0.000000
    outer loop
      vertex 95.422966 90.031807 3.000000
      vertex 95.362732 90.293015 3.000000
      vertex 95.422966 90.031807 0.000000
    endloop
  endfacet
  facet normal -0.950472 -0.310810 0.000000
    outer loop
      vertex 95.505508 89.779388 0.000000
      vertex 95.422966 90.031807 3.000000
      vertex 95.422966 90.031807 0.000000
    endloop
  endfacet
  facet normal -0.950472 -0.310810 -0.000000
    outer loop
      vertex 95.505508 89.779388 3.000000
      vertex 95.422966 90.031807 3.000000
      vertex 95.505508 89.779388 0.000000
    endloop
  endfacet
  facet normal -0.919227 -0.393727 0.000000
    outer loop
      vertex 95.609344 89.536964 0.000000
      vertex 95.505508 89.779388 3.000000
      vertex 95.505508 89.779388 0.000000
    endloop
  endfacet
  facet normal -0.919227 -0.393727 -0.000000
    outer loop
      vertex 95.609344 89.536964 3.000000
      vertex 95.505508 89.779388 3.000000
      vertex 95.609344 89.536964 0.000000
    endloop
  endfacet
  facet normal -0.881140 -0.472855 0.000000
    outer loop
      vertex 95.733437 89.305725 0.000000
      vertex 95.609344 89.536964 3.000000
      vertex 95.609344 89.536964 0.000000
    endloop
  endfacet
  facet normal -0.881140 -0.472855 -0.000000
    outer loop
      vertex 95.733437 89.305725 3.000000
      vertex 95.609344 89.536964 3.000000
      vertex 95.733437 89.305725 0.000000
    endloop
  endfacet
  facet normal -0.836572 -0.547857 0.000000
    outer loop
      vertex 95.876762 89.086868 0.000000
      vertex 95.733437 89.305725 3.000000
      vertex 95.733437 89.305725 0.000000
    endloop
  endfacet
  facet normal -0.836572 -0.547857 -0.000000
    outer loop
      vertex 95.876762 89.086868 3.000000
      vertex 95.733437 89.305725 3.000000
      vertex 95.876762 89.086868 0.000000
    endloop
  endfacet
  facet normal -0.785892 -0.618363 0.000000
    outer loop
      vertex 96.038292 88.881577 0.000000
      vertex 95.876762 89.086868 3.000000
      vertex 95.876762 89.086868 0.000000
    endloop
  endfacet
  facet normal -0.785892 -0.618363 -0.000000
    outer loop
      vertex 96.038292 88.881577 3.000000
      vertex 95.876762 89.086868 3.000000
      vertex 96.038292 88.881577 0.000000
    endloop
  endfacet
  facet normal -0.729338 -0.684154 0.000000
    outer loop
      vertex 96.217003 88.691063 0.000000
      vertex 96.038292 88.881577 3.000000
      vertex 96.038292 88.881577 0.000000
    endloop
  endfacet
  facet normal -0.729338 -0.684154 -0.000000
    outer loop
      vertex 96.217003 88.691063 3.000000
      vertex 96.038292 88.881577 3.000000
      vertex 96.217003 88.691063 0.000000
    endloop
  endfacet
  facet normal -0.667224 -0.744857 0.000000
    outer loop
      vertex 96.411865 88.516510 0.000000
      vertex 96.217003 88.691063 3.000000
      vertex 96.217003 88.691063 0.000000
    endloop
  endfacet
  facet normal -0.667224 -0.744857 -0.000000
    outer loop
      vertex 96.411865 88.516510 3.000000
      vertex 96.217003 88.691063 3.000000
      vertex 96.411865 88.516510 0.000000
    endloop
  endfacet
  facet normal -0.599758 -0.800181 0.000000
    outer loop
      vertex 96.621857 88.359116 0.000000
      vertex 96.411865 88.516510 3.000000
      vertex 96.411865 88.516510 0.000000
    endloop
  endfacet
  facet normal -0.599758 -0.800181 -0.000000
    outer loop
      vertex 96.621857 88.359116 3.000000
      vertex 96.411865 88.516510 3.000000
      vertex 96.621857 88.359116 0.000000
    endloop
  endfacet
  facet normal -0.527240 -0.849717 0.000000
    outer loop
      vertex 96.845947 88.220070 0.000000
      vertex 96.621857 88.359116 3.000000
      vertex 96.621857 88.359116 0.000000
    endloop
  endfacet
  facet normal -0.527240 -0.849717 -0.000000
    outer loop
      vertex 96.845947 88.220070 3.000000
      vertex 96.621857 88.359116 3.000000
      vertex 96.845947 88.220070 0.000000
    endloop
  endfacet
  facet normal -0.449969 -0.893044 0.000000
    outer loop
      vertex 97.083115 88.100571 0.000000
      vertex 96.845947 88.220070 3.000000
      vertex 96.845947 88.220070 0.000000
    endloop
  endfacet
  facet normal -0.449969 -0.893044 -0.000000
    outer loop
      vertex 97.083115 88.100571 3.000000
      vertex 96.845947 88.220070 3.000000
      vertex 97.083115 88.100571 0.000000
    endloop
  endfacet
  facet normal -0.368420 -0.929659 0.000000
    outer loop
      vertex 97.332329 88.001808 0.000000
      vertex 97.083115 88.100571 3.000000
      vertex 97.083115 88.100571 0.000000
    endloop
  endfacet
  facet normal -0.368420 -0.929659 -0.000000
    outer loop
      vertex 97.332329 88.001808 3.000000
      vertex 97.083115 88.100571 3.000000
      vertex 97.332329 88.001808 0.000000
    endloop
  endfacet
  facet normal -0.283148 -0.959076 0.000000
    outer loop
      vertex 97.592560 87.924980 0.000000
      vertex 97.332329 88.001808 3.000000
      vertex 97.332329 88.001808 0.000000
    endloop
  endfacet
  facet normal -0.283148 -0.959076 -0.000000
    outer loop
      vertex 97.592560 87.924980 3.000000
      vertex 97.332329 88.001808 3.000000
      vertex 97.592560 87.924980 0.000000
    endloop
  endfacet
  facet normal -0.194891 -0.980825 0.000000
    outer loop
      vertex 97.862793 87.871284 0.000000
      vertex 97.592560 87.924980 3.000000
      vertex 97.592560 87.924980 0.000000
    endloop
  endfacet
  facet normal -0.194891 -0.980825 -0.000000
    outer loop
      vertex 97.862793 87.871284 3.000000
      vertex 97.592560 87.924980 3.000000
      vertex 97.862793 87.871284 0.000000
    endloop
  endfacet
  facet normal -1.000000 0.000000 -0.000000
    outer loop
      vertex 95.313316 103.467812 3.000000
      vertex 95.313316 103.467812 0.000000
      vertex 95.313316 90.837059 0.000000
    endloop
  endfacet
  facet normal -1.000000 0.000000 0.000000
    outer loop
      vertex 95.313316 90.837059 3.000000
      vertex 95.313316 103.467812 3.000000
      vertex 95.313316 90.837059 0.000000
    endloop
  endfacet
  facet normal -0.050426 -0.998728 -0.000000
    outer loop
      vertex 92.314682 106.466446 3.000000
      vertex 92.314682 106.466446 0.000000
      vertex 92.621277 106.450966 0.000000
    endloop
  endfacet
  facet normal -0.050426 -0.998728 -0.000000
    outer loop
      vertex 92.621277 106.450966 3.000000
      vertex 92.314682 106.466446 3.000000
      vertex 92.621277 106.450966 0.000000
    endloop
  endfacet
  facet normal -0.150873 -0.988553 0.000000
    outer loop
      vertex 92.919014 106.405525 0.000000
      vertex 92.621277 106.450966 3.000000
      vertex 92.621277 106.450966 0.000000
    endloop
  endfacet
  facet normal -0.150873 -0.988553 -0.000000
    outer loop
      vertex 92.919014 106.405525 3.000000
      vertex 92.621277 106.450966 3.000000
      vertex 92.919014 106.405525 0.000000
    endloop
  endfacet
  facet normal -0.249022 -0.968498 0.000000
    outer loop
      vertex 93.206390 106.331635 0.000000
      vertex 92.919014 106.405525 3.000000
      vertex 92.919014 106.405525 0.000000
    endloop
  endfacet
  facet normal -0.249022 -0.968498 -0.000000
    outer loop
      vertex 93.206390 106.331635 3.000000
      vertex 92.919014 106.405525 3.000000
      vertex 93.206390 106.331635 0.000000
    endloop
  endfacet
  facet normal -0.343720 -0.939072 0.000000
    outer loop
      vertex 93.481888 106.230797 0.000000
      vertex 93.206390 106.331635 3.000000
      vertex 93.206390 106.331635 0.000000
    endloop
  endfacet
  facet normal -0.343720 -0.939072 -0.000000
    outer loop
      vertex 93.481888 106.230797 3.000000
      vertex 93.206390 106.331635 3.000000
      vertex 93.481888 106.230797 0.000000
    endloop
  endfacet
  facet normal -0.433980 -0.900922 0.000000
    outer loop
      vertex 93.744011 106.104530 0.000000
      vertex 93.481888 106.230797 3.000000
      vertex 93.481888 106.230797 0.000000
    endloop
  endfacet
  facet normal -0.433980 -0.900922 -0.000000
    outer loop
      vertex 93.744011 106.104530 3.000000
      vertex 93.481888 106.230797 3.000000
      vertex 93.744011 106.104530 0.000000
    endloop
  endfacet
  facet normal -0.519208 -0.854648 0.000000
    outer loop
      vertex 93.991249 105.954330 0.000000
      vertex 93.744011 106.104530 3.000000
      vertex 93.744011 106.104530 0.000000
    endloop
  endfacet
  facet normal -0.519208 -0.854648 -0.000000
    outer loop
      vertex 93.991249 105.954330 3.000000
      vertex 93.744011 106.104530 3.000000
      vertex 93.991249 105.954330 0.000000
    endloop
  endfacet
  facet normal -0.598869 -0.800847 0.000000
    outer loop
      vertex 94.222092 105.781708 0.000000
      vertex 93.991249 105.954330 3.000000
      vertex 93.991249 105.954330 0.000000
    endloop
  endfacet
  facet normal -0.598869 -0.800847 -0.000000
    outer loop
      vertex 94.222092 105.781708 3.000000
      vertex 93.991249 105.954330 3.000000
      vertex 94.222092 105.781708 0.000000
    endloop
  endfacet
  facet normal -0.672591 -0.740014 0.000000
    outer loop
      vertex 94.435036 105.588165 0.000000
      vertex 94.222092 105.781708 3.000000
      vertex 94.222092 105.781708 0.000000
    endloop
  endfacet
  facet normal -0.672591 -0.740014 -0.000000
    outer loop
      vertex 94.435036 105.588165 3.000000
      vertex 94.222092 105.781708 3.000000
      vertex 94.435036 105.588165 0.000000
    endloop
  endfacet
  facet normal -0.740014 -0.672591 0.000000
    outer loop
      vertex 94.628578 105.375221 0.000000
      vertex 94.435036 105.588165 3.000000
      vertex 94.435036 105.588165 0.000000
    endloop
  endfacet
  facet normal -0.740014 -0.672591 -0.000000
    outer loop
      vertex 94.628578 105.375221 3.000000
      vertex 94.435036 105.588165 3.000000
      vertex 94.628578 105.375221 0.000000
    endloop
  endfacet
  facet normal -0.800847 -0.598869 0.000000
    outer loop
      vertex 94.801201 105.144379 0.000000
      vertex 94.628578 105.375221 3.000000
      vertex 94.628578 105.375221 0.000000
    endloop
  endfacet
  facet normal -0.800847 -0.598869 -0.000000
    outer loop
      vertex 94.801201 105.144379 3.000000
      vertex 94.628578 105.375221 3.000000
      vertex 94.801201 105.144379 0.000000
    endloop
  endfacet
  facet normal -0.854648 -0.519208 0.000000
    outer loop
      vertex 94.951401 104.897141 0.000000
      vertex 94.801201 105.144379 3.000000
      vertex 94.801201 105.144379 0.000000
    endloop
  endfacet
  facet normal -0.854648 -0.519208 -0.000000
    outer loop
      vertex 94.951401 104.897141 3.000000
      vertex 94.801201 105.144379 3.000000
      vertex 94.951401 104.897141 0.000000
    endloop
  endfacet
  facet normal -0.900922 -0.433980 0.000000
    outer loop
      vertex 95.077667 104.635017 0.000000
      vertex 94.951401 104.897141 3.000000
      vertex 94.951401 104.897141 0.000000
    endloop
  endfacet
  facet normal -0.900922 -0.433980 -0.000000
    outer loop
      vertex 95.077667 104.635017 3.000000
      vertex 94.951401 104.897141 3.000000
      vertex 95.077667 104.635017 0.000000
    endloop
  endfacet
  facet normal -0.939075 -0.343711 0.000000
    outer loop
      vertex 95.178505 104.359512 0.000000
      vertex 95.077667 104.635017 3.000000
      vertex 95.077667 104.635017 0.000000
    endloop
  endfacet
  facet normal -0.939075 -0.343711 -0.000000
    outer loop
      vertex 95.178505 104.359512 3.000000
      vertex 95.077667 104.635017 3.000000
      vertex 95.178505 104.359512 0.000000
    endloop
  endfacet
  facet normal -0.968496 -0.249028 0.000000
    outer loop
      vertex 95.252396 104.072144 0.000000
      vertex 95.178505 104.359512 3.000000
      vertex 95.178505 104.359512 0.000000
    endloop
  endfacet
  facet normal -0.968496 -0.249028 -0.000000
    outer loop
      vertex 95.252396 104.072144 3.000000
      vertex 95.178505 104.359512 3.000000
      vertex 95.252396 104.072144 0.000000
    endloop
  endfacet
  facet normal -0.988553 -0.150873 0.000000
    outer loop
      vertex 95.297836 103.774406 0.000000
      vertex 95.252396 104.072144 3.000000
      vertex 95.252396 104.072144 0.000000
    endloop
  endfacet
  facet normal -0.988553 -0.150873 -0.000000
    outer loop
      vertex 95.297836 103.774406 3.000000
      vertex 95.252396 104.072144 3.000000
      vertex 95.297836 103.774406 0.000000
    endloop
  endfacet
  facet normal -0.998728 -0.050426 0.000000
    outer loop
      vertex 95.313316 103.467812 0.000000
      vertex 95.297836 103.774406 3.000000
      vertex 95.297836 103.774406 0.000000
    endloop
  endfacet
  facet normal -0.998728 -0.050426 -0.000000
    outer loop
      vertex 95.313316 103.467812 3.000000
      vertex 95.297836 103.774406 3.000000
      vertex 95.313316 103.467812 0.000000
    endloop
  endfacet
  facet normal 0.000000 -1.000000 0.000000
    outer loop
      vertex 32.343864 106.466446 3.000000
      vertex 32.343864 106.466446 0.000000
      vertex 92.314682 106.466446 0.000000
    endloop
  endfacet
  facet normal -0.000000 -1.000000 -0.000000
    outer loop
      vertex 92.314682 106.466446 3.000000
      vertex 32.343864 106.466446 3.000000
      vertex 92.314682 106.466446 0.000000
    endloop
  endfacet
  facet normal -0.998728 -0.050428 -0.000000
    outer loop
      vertex 29.343874 109.466438 3.000000
      vertex 29.343874 109.466438 0.000000
      vertex 29.359362 109.159706 0.000000
    endloop
  endfacet
  facet normal -0.998728 -0.050428 -0.000000
    outer loop
      vertex 29.359362 109.159706 3.000000
      vertex 29.343874 109.466438 3.000000
      vertex 29.359362 109.159706 0.000000
    endloop
  endfacet
  facet normal -0.988553 -0.150873 0.000000
    outer loop
      vertex 29.404823 108.861832 0.000000
      vertex 29.359362 109.159706 3.000000
      vertex 29.359362 109.159706 0.000000
    endloop
  endfacet
  facet normal -0.988553 -0.150873 -0.000000
    outer loop
      vertex 29.404823 108.861832 3.000000
      vertex 29.359362 109.159706 3.000000
      vertex 29.404823 108.861832 0.000000
    endloop
  endfacet
  facet normal -0.968495 -0.249031 0.000000
    outer loop
      vertex 29.478748 108.574333 0.000000
      vertex 29.404823 108.861832 3.000000
      vertex 29.404823 108.861832 0.000000
    endloop
  endfacet
  facet normal -0.968495 -0.249031 -0.000000
    outer loop
      vertex 29.478748 108.574333 3.000000
      vertex 29.404823 108.861832 3.000000
      vertex 29.478748 108.574333 0.000000
    endloop
  endfacet
  facet normal -0.939078 -0.343703 0.000000
    outer loop
      vertex 29.579628 108.298706 0.000000
      vertex 29.478748 108.574333 3.000000
      vertex 29.478748 108.574333 0.000000
    endloop
  endfacet
  facet normal -0.939078 -0.343703 -0.000000
    outer loop
      vertex 29.579628 108.298706 3.000000
      vertex 29.478748 108.574333 3.000000
      vertex 29.579628 108.298706 0.000000
    endloop
  endfacet
  facet normal -0.900919 -0.433987 0.000000
    outer loop
      vertex 29.705956 108.036461 0.000000
      vertex 29.579628 108.298706 3.000000
      vertex 29.579628 108.298706 0.000000
    endloop
  endfacet
  facet normal -0.900919 -0.433987 -0.000000
    outer loop
      vertex 29.705956 108.036461 3.000000
      vertex 29.579628 108.298706 3.000000
      vertex 29.705956 108.036461 0.000000
    endloop
  endfacet
  facet normal -0.854642 -0.519217 0.000000
    outer loop
      vertex 29.856224 107.789116 0.000000
      vertex 29.705956 108.036461 3.000000
      vertex 29.705956 108.036461 0.000000
    endloop
  endfacet
  facet normal -0.854642 -0.519217 -0.000000
    outer loop
      vertex 29.856224 107.789116 3.000000
      vertex 29.705956 108.036461 3.000000
      vertex 29.856224 107.789116 0.000000
    endloop
  endfacet
  facet normal -0.800850 -0.598865 0.000000
    outer loop
      vertex 30.028925 107.558167 0.000000
      vertex 29.856224 107.789116 3.000000
      vertex 29.856224 107.789116 0.000000
    endloop
  endfacet
  facet normal -0.800850 -0.598865 -0.000000
    outer loop
      vertex 30.028925 107.558167 3.000000
      vertex 29.856224 107.789116 3.000000
      vertex 30.028925 107.558167 0.000000
    endloop
  endfacet
  facet normal -0.740029 -0.672575 0.000000
    outer loop
      vertex 30.222549 107.345123 0.000000
      vertex 30.028925 107.558167 3.000000
      vertex 30.028925 107.558167 0.000000
    endloop
  endfacet
  facet normal -0.740029 -0.672575 -0.000000
    outer loop
      vertex 30.222549 107.345123 3.000000
      vertex 30.028925 107.558167 3.000000
      vertex 30.222549 107.345123 0.000000
    endloop
  endfacet
  facet normal -0.672582 -0.740022 0.000000
    outer loop
      vertex 30.435591 107.151497 0.000000
      vertex 30.222549 107.345123 3.000000
      vertex 30.222549 107.345123 0.000000
    endloop
  endfacet
  facet normal -0.672582 -0.740022 -0.000000
    outer loop
      vertex 30.435591 107.151497 3.000000
      vertex 30.222549 107.345123 3.000000
      vertex 30.435591 107.151497 0.000000
    endloop
  endfacet
  facet normal -0.598861 -0.800853 0.000000
    outer loop
      vertex 30.666540 106.978798 0.000000
      vertex 30.435591 107.151497 3.000000
      vertex 30.435591 107.151497 0.000000
    endloop
  endfacet
  facet normal -0.598861 -0.800853 -0.000000
    outer loop
      vertex 30.666540 106.978798 3.000000
      vertex 30.435591 107.151497 3.000000
      vertex 30.666540 106.978798 0.000000
    endloop
  endfacet
  facet normal -0.519209 -0.854648 0.000000
    outer loop
      vertex 30.913891 106.828529 0.000000
      vertex 30.666540 106.978798 3.000000
      vertex 30.666540 106.978798 0.000000
    endloop
  endfacet
  facet normal -0.519209 -0.854648 -0.000000
    outer loop
      vertex 30.913891 106.828529 3.000000
      vertex 30.666540 106.978798 3.000000
      vertex 30.913891 106.828529 0.000000
    endloop
  endfacet
  facet normal -0.433992 -0.900917 0.000000
    outer loop
      vertex 31.176132 106.702202 0.000000
      vertex 30.913891 106.828529 3.000000
      vertex 30.913891 106.828529 0.000000
    endloop
  endfacet
  facet normal -0.433992 -0.900917 -0.000000
    outer loop
      vertex 31.176132 106.702202 3.000000
      vertex 30.913891 106.828529 3.000000
      vertex 31.176132 106.702202 0.000000
    endloop
  endfacet
  facet normal -0.343717 -0.939073 0.000000
    outer loop
      vertex 31.451757 106.601318 0.000000
      vertex 31.176132 106.702202 3.000000
      vertex 31.176132 106.702202 0.000000
    endloop
  endfacet
  facet normal -0.343717 -0.939073 -0.000000
    outer loop
      vertex 31.451757 106.601318 3.000000
      vertex 31.176132 106.702202 3.000000
      vertex 31.451757 106.601318 0.000000
    endloop
  endfacet
  facet normal -0.249016 -0.968499 0.000000
    outer loop
      vertex 31.739260 106.527397 0.000000
      vertex 31.451757 106.601318 3.000000
      vertex 31.451757 106.601318 0.000000
    endloop
  endfacet
  facet normal -0.249016 -0.968499 -0.000000
    outer loop
      vertex 31.739260 106.527397 3.000000
      vertex 31.451757 106.601318 3.000000
      vertex 31.739260 106.527397 0.000000
    endloop
  endfacet
  facet normal -0.150880 -0.988552 0.000000
    outer loop
      vertex 32.037132 106.481934 0.000000
      vertex 31.739260 106.527397 3.000000
      vertex 31.739260 106.527397 0.000000
    endloop
  endfacet
  facet normal -0.150880 -0.988552 -0.000000
    outer loop
      vertex 32.037132 106.481934 3.000000
      vertex 31.739260 106.527397 3.000000
      vertex 32.037132 106.481934 0.000000
    endloop
  endfacet
  facet normal -0.050428 -0.998728 0.000000
    outer loop
      vertex 32.343864 106.466446 0.000000
      vertex 32.037132 106.481934 3.000000
      vertex 32.037132 106.481934 0.000000
    endloop
  endfacet
  facet normal -0.050428 -0.998728 -0.000000
    outer loop
      vertex 32.343864 106.466446 3.000000
      vertex 32.037132 106.481934 3.000000
      vertex 32.343864 106.466446 0.000000
    endloop
  endfacet
  facet normal -1.000000 0.000000 -0.000000
    outer loop
      vertex 29.343874 190.965912 3.000000
      vertex 29.343874 190.965912 0.000000
      vertex 29.343874 109.466438 0.000000
    endloop
  endfacet
  facet normal -1.000000 0.000000 0.000000
    outer loop
      vertex 29.343874 109.466438 3.000000
      vertex 29.343874 190.965912 3.000000
      vertex 29.343874 109.466438 0.000000
    endloop
  endfacet
  facet normal -0.299988 0.953943 0.000000
    outer loop
      vertex 31.564236 193.862839 3.000000
      vertex 31.564236 193.862839 0.000000
      vertex 31.323421 193.787109 0.000000
    endloop
  endfacet
  facet normal -0.299988 0.953943 0.000000
    outer loop
      vertex 31.323421 193.787109 3.000000
      vertex 31.564236 193.862839 3.000000
      vertex 31.323421 193.787109 0.000000
    endloop
  endfacet
  facet normal -0.378470 0.925613 0.000000
    outer loop
      vertex 31.092722 193.692780 0.000000
      vertex 31.323421 193.787109 3.000000
      vertex 31.323421 193.787109 0.000000
    endloop
  endfacet
  facet normal -0.378470 0.925613 0.000000
    outer loop
      vertex 31.092722 193.692780 3.000000
      vertex 31.323421 193.787109 3.000000
      vertex 31.092722 193.692780 0.000000
    endloop
  endfacet
  facet normal -0.489902 0.871778 0.000000
    outer loop
      vertex 30.664656 193.452225 0.000000
      vertex 31.092722 193.692780 3.000000
      vertex 31.092722 193.692780 0.000000
    endloop
  endfacet
  facet normal -0.489902 0.871778 0.000000
    outer loop
      vertex 30.664656 193.452225 3.000000
      vertex 31.092722 193.692780 3.000000
      vertex 30.664656 193.452225 0.000000
    endloop
  endfacet
  facet normal -0.625094 0.780550 0.000000
    outer loop
      vertex 30.286024 193.149002 0.000000
      vertex 30.664656 193.452225 3.000000
      vertex 30.664656 193.452225 0.000000
    endloop
  endfacet
  facet normal -0.625094 0.780550 0.000000
    outer loop
      vertex 30.286024 193.149002 3.000000
      vertex 30.664656 193.452225 3.000000
      vertex 30.286024 193.149002 0.000000
    endloop
  endfacet
  facet normal -0.742351 0.670011 0.000000
    outer loop
      vertex 29.962812 192.790894 0.000000
      vertex 30.286024 193.149002 3.000000
      vertex 30.286024 193.149002 0.000000
    endloop
  endfacet
  facet normal -0.742351 0.670011 0.000000
    outer loop
      vertex 29.962812 192.790894 3.000000
      vertex 30.286024 193.149002 3.000000
      vertex 29.962812 192.790894 0.000000
    endloop
  endfacet
  facet normal -0.839911 0.542725 0.000000
    outer loop
      vertex 29.701006 192.385727 0.000000
      vertex 29.962812 192.790894 3.000000
      vertex 29.962812 192.790894 0.000000
    endloop
  endfacet
  facet normal -0.839911 0.542725 0.000000
    outer loop
      vertex 29.701006 192.385727 3.000000
      vertex 29.962812 192.790894 3.000000
      vertex 29.701006 192.385727 0.000000
    endloop
  endfacet
  facet normal -0.916173 0.400783 0.000000
    outer loop
      vertex 29.506590 191.941299 0.000000
      vertex 29.701006 192.385727 3.000000
      vertex 29.701006 192.385727 0.000000
    endloop
  endfacet
  facet normal -0.916173 0.400783 0.000000
    outer loop
      vertex 29.506590 191.941299 3.000000
      vertex 29.701006 192.385727 3.000000
      vertex 29.506590 191.941299 0.000000
    endloop
  endfacet
  facet normal -0.969142 0.246504 0.000000
    outer loop
      vertex 29.385550 191.465424 0.000000
      vertex 29.506590 191.941299 3.000000
      vertex 29.506590 191.941299 0.000000
    endloop
  endfacet
  facet normal -0.969142 0.246504 0.000000
    outer loop
      vertex 29.385550 191.465424 3.000000
      vertex 29.506590 191.941299 3.000000
      vertex 29.385550 191.465424 0.000000
    endloop
  endfacet
  facet normal -0.992168 0.124909 0.000000
    outer loop
      vertex 29.354418 191.218140 0.000000
      vertex 29.385550 191.465424 3.000000
      vertex 29.385550 191.465424 0.000000
    endloop
  endfacet
  facet normal -0.992168 0.124909 0.000000
    outer loop
      vertex 29.354418 191.218140 3.000000
      vertex 29.385550 191.465424 3.000000
      vertex 29.354418 191.218140 0.000000
    endloop
  endfacet
  facet normal -0.999127 0.041766 0.000000
    outer loop
      vertex 29.343874 190.965912 0.000000
      vertex 29.354418 191.218140 3.000000
      vertex 29.354418 191.218140 0.000000
    endloop
  endfacet
  facet normal -0.999127 0.041766 0.000000
    outer loop
      vertex 29.343874 190.965912 3.000000
      vertex 29.354418 191.218140 3.000000
      vertex 29.343874 190.965912 0.000000
    endloop
  endfacet
  facet normal -0.259875 0.965642 0.000000
    outer loop
      vertex 33.784603 194.460388 3.000000
      vertex 33.784603 194.460388 0.000000
      vertex 31.564236 193.862839 0.000000
    endloop
  endfacet
  facet normal -0.259875 0.965642 0.000000
    outer loop
      vertex 31.564236 193.862839 3.000000
      vertex 33.784603 194.460388 3.000000
      vertex 31.564236 193.862839 0.000000
    endloop
  endfacet
  facet normal 0.468037 0.883709 0.000000
    outer loop
      vertex 152.502426 196.322800 3.000000
      vertex 152.502426 196.322800 0.000000
      vertex 151.344193 196.936234 0.000000
    endloop
  endfacet
  facet normal 0.468037 0.883709 0.000000
    outer loop
      vertex 151.344193 196.936234 3.000000
      vertex 152.502426 196.322800 3.000000
      vertex 151.344193 196.936234 0.000000
    endloop
  endfacet
  facet normal 0.451125 0.892461 0.000000
    outer loop
      vertex 150.170212 197.529663 0.000000
      vertex 151.344193 196.936234 3.000000
      vertex 151.344193 196.936234 0.000000
    endloop
  endfacet
  facet normal 0.451125 0.892461 0.000000
    outer loop
      vertex 150.170212 197.529663 3.000000
      vertex 151.344193 196.936234 3.000000
      vertex 150.170212 197.529663 0.000000
    endloop
  endfacet
  facet normal 0.434163 0.900834 0.000000
    outer loop
      vertex 148.980331 198.103134 0.000000
      vertex 150.170212 197.529663 3.000000
      vertex 150.170212 197.529663 0.000000
    endloop
  endfacet
  facet normal 0.434163 0.900834 0.000000
    outer loop
      vertex 148.980331 198.103134 3.000000
      vertex 150.170212 197.529663 3.000000
      vertex 148.980331 198.103134 0.000000
    endloop
  endfacet
  facet normal 0.417173 0.908827 0.000000
    outer loop
      vertex 147.774384 198.656693 0.000000
      vertex 148.980331 198.103134 3.000000
      vertex 148.980331 198.103134 0.000000
    endloop
  endfacet
  facet normal 0.417173 0.908827 0.000000
    outer loop
      vertex 147.774384 198.656693 3.000000
      vertex 148.980331 198.103134 3.000000
      vertex 147.774384 198.656693 0.000000
    endloop
  endfacet
  facet normal 0.400170 0.916441 0.000000
    outer loop
      vertex 146.552231 199.190353 0.000000
      vertex 147.774384 198.656693 3.000000
      vertex 147.774384 198.656693 0.000000
    endloop
  endfacet
  facet normal 0.400170 0.916441 0.000000
    outer loop
      vertex 146.552231 199.190353 3.000000
      vertex 147.774384 198.656693 3.000000
      vertex 146.552231 199.190353 0.000000
    endloop
  endfacet
  facet normal 0.383194 0.923668 0.000000
    outer loop
      vertex 145.313721 199.704163 0.000000
      vertex 146.552231 199.190353 3.000000
      vertex 146.552231 199.190353 0.000000
    endloop
  endfacet
  facet normal 0.383194 0.923668 0.000000
    outer loop
      vertex 145.313721 199.704163 3.000000
      vertex 146.552231 199.190353 3.000000
      vertex 145.313721 199.704163 0.000000
    endloop
  endfacet
  facet normal 0.366251 0.930516 0.000000
    outer loop
      vertex 144.058670 200.198151 0.000000
      vertex 145.313721 199.704163 3.000000
      vertex 145.313721 199.704163 0.000000
    endloop
  endfacet
  facet normal 0.366251 0.930516 0.000000
    outer loop
      vertex 144.058670 200.198151 3.000000
      vertex 145.313721 199.704163 3.000000
      vertex 144.058670 200.198151 0.000000
    endloop
  endfacet
  facet normal 0.349388 0.936978 0.000000
    outer loop
      vertex 142.786942 200.672363 0.000000
      vertex 144.058670 200.198151 3.000000
      vertex 144.058670 200.198151 0.000000
    endloop
  endfacet
  facet normal 0.349388 0.936978 0.000000
    outer loop
      vertex 142.786942 200.672363 3.000000
      vertex 144.058670 200.198151 3.000000
      vertex 142.786942 200.672363 0.000000
    endloop
  endfacet
  facet normal 0.332603 0.943067 0.000000
    outer loop
      vertex 141.498383 201.126816 0.000000
      vertex 142.786942 200.672363 3.000000
      vertex 142.786942 200.672363 0.000000
    endloop
  endfacet
  facet normal 0.332603 0.943067 0.000000
    outer loop
      vertex 141.498383 201.126816 3.000000
      vertex 142.786942 200.672363 3.000000
      vertex 141.498383 201.126816 0.000000
    endloop
  endfacet
  facet normal 0.315925 0.948784 0.000000
    outer loop
      vertex 140.192825 201.561539 0.000000
      vertex 141.498383 201.126816 3.000000
      vertex 141.498383 201.126816 0.000000
    endloop
  endfacet
  facet normal 0.315925 0.948784 0.000000
    outer loop
      vertex 140.192825 201.561539 3.000000
      vertex 141.498383 201.126816 3.000000
      vertex 140.192825 201.561539 0.000000
    endloop
  endfacet
  facet normal 0.299397 0.954129 0.000000
    outer loop
      vertex 138.870117 201.976593 0.000000
      vertex 140.192825 201.561539 3.000000
      vertex 140.192825 201.561539 0.000000
    endloop
  endfacet
  facet normal 0.299397 0.954129 0.000000
    outer loop
      vertex 138.870117 201.976593 3.000000
      vertex 140.192825 201.561539 3.000000
      vertex 138.870117 201.976593 0.000000
    endloop
  endfacet
  facet normal 0.282996 0.959121 0.000000
    outer loop
      vertex 137.530090 202.371979 0.000000
      vertex 138.870117 201.976593 3.000000
      vertex 138.870117 201.976593 0.000000
    endloop
  endfacet
  facet normal 0.282996 0.959121 0.000000
    outer loop
      vertex 137.530090 202.371979 3.000000
      vertex 138.870117 201.976593 3.000000
      vertex 137.530090 202.371979 0.000000
    endloop
  endfacet
  facet normal 0.266789 0.963755 0.000000
    outer loop
      vertex 136.172623 202.747757 0.000000
      vertex 137.530090 202.371979 3.000000
      vertex 137.530090 202.371979 0.000000
    endloop
  endfacet
  facet normal 0.266789 0.963755 0.000000
    outer loop
      vertex 136.172623 202.747757 3.000000
      vertex 137.530090 202.371979 3.000000
      vertex 136.172623 202.747757 0.000000
    endloop
  endfacet
  facet normal 0.250762 0.968049 0.000000
    outer loop
      vertex 134.797531 203.103958 0.000000
      vertex 136.172623 202.747757 3.000000
      vertex 136.172623 202.747757 0.000000
    endloop
  endfacet
  facet normal 0.250762 0.968049 0.000000
    outer loop
      vertex 134.797531 203.103958 3.000000
      vertex 136.172623 202.747757 3.000000
      vertex 134.797531 203.103958 0.000000
    endloop
  endfacet
  facet normal 0.234922 0.972014 0.000000
    outer loop
      vertex 133.404648 203.440598 0.000000
      vertex 134.797531 203.103958 3.000000
      vertex 134.797531 203.103958 0.000000
    endloop
  endfacet
  facet normal 0.234922 0.972014 0.000000
    outer loop
      vertex 133.404648 203.440598 3.000000
      vertex 134.797531 203.103958 3.000000
      vertex 133.404648 203.440598 0.000000
    endloop
  endfacet
  facet normal 0.219321 0.975653 0.000000
    outer loop
      vertex 131.993851 203.757736 0.000000
      vertex 133.404648 203.440598 3.000000
      vertex 133.404648 203.440598 0.000000
    endloop
  endfacet
  facet normal 0.219321 0.975653 0.000000
    outer loop
      vertex 131.993851 203.757736 3.000000
      vertex 133.404648 203.440598 3.000000
      vertex 131.993851 203.757736 0.000000
    endloop
  endfacet
  facet normal 0.203925 0.978987 0.000000
    outer loop
      vertex 130.564972 204.055374 0.000000
      vertex 131.993851 203.757736 3.000000
      vertex 131.993851 203.757736 0.000000
    endloop
  endfacet
  facet normal 0.203925 0.978987 0.000000
    outer loop
      vertex 130.564972 204.055374 3.000000
      vertex 131.993851 203.757736 3.000000
      vertex 130.564972 204.055374 0.000000
    endloop
  endfacet
  facet normal 0.188783 0.982019 0.000000
    outer loop
      vertex 129.117828 204.333572 0.000000
      vertex 130.564972 204.055374 3.000000
      vertex 130.564972 204.055374 0.000000
    endloop
  endfacet
  facet normal 0.188783 0.982019 0.000000
    outer loop
      vertex 129.117828 204.333572 3.000000
      vertex 130.564972 204.055374 3.000000
      vertex 129.117828 204.333572 0.000000
    endloop
  endfacet
  facet normal 0.173894 0.984764 0.000000
    outer loop
      vertex 127.652306 204.592361 0.000000
      vertex 129.117828 204.333572 3.000000
      vertex 129.117828 204.333572 0.000000
    endloop
  endfacet
  facet normal 0.173894 0.984764 0.000000
    outer loop
      vertex 127.652306 204.592361 3.000000
      vertex 129.117828 204.333572 3.000000
      vertex 127.652306 204.592361 0.000000
    endloop
  endfacet
  facet normal 0.159250 0.987238 0.000000
    outer loop
      vertex 126.168221 204.831757 0.000000
      vertex 127.652306 204.592361 3.000000
      vertex 127.652306 204.592361 0.000000
    endloop
  endfacet
  facet normal 0.159250 0.987238 0.000000
    outer loop
      vertex 126.168221 204.831757 3.000000
      vertex 127.652306 204.592361 3.000000
      vertex 126.168221 204.831757 0.000000
    endloop
  endfacet
  facet normal 0.144890 0.989448 0.000000
    outer loop
      vertex 124.665428 205.051819 0.000000
      vertex 126.168221 204.831757 3.000000
      vertex 126.168221 204.831757 0.000000
    endloop
  endfacet
  facet normal 0.144890 0.989448 0.000000
    outer loop
      vertex 124.665428 205.051819 3.000000
      vertex 126.168221 204.831757 3.000000
      vertex 124.665428 205.051819 0.000000
    endloop
  endfacet
  facet normal 0.130791 0.991410 0.000000
    outer loop
      vertex 123.143761 205.252563 0.000000
      vertex 124.665428 205.051819 3.000000
      vertex 124.665428 205.051819 0.000000
    endloop
  endfacet
  facet normal 0.130791 0.991410 0.000000
    outer loop
      vertex 123.143761 205.252563 3.000000
      vertex 124.665428 205.051819 3.000000
      vertex 123.143761 205.252563 0.000000
    endloop
  endfacet
  facet normal 0.116969 0.993136 0.000000
    outer loop
      vertex 121.603073 205.434021 0.000000
      vertex 123.143761 205.252563 3.000000
      vertex 123.143761 205.252563 0.000000
    endloop
  endfacet
  facet normal 0.116969 0.993136 0.000000
    outer loop
      vertex 121.603073 205.434021 3.000000
      vertex 123.143761 205.252563 3.000000
      vertex 121.603073 205.434021 0.000000
    endloop
  endfacet
  facet normal 0.103446 0.994635 0.000000
    outer loop
      vertex 120.043213 205.596252 0.000000
      vertex 121.603073 205.434021 3.000000
      vertex 121.603073 205.434021 0.000000
    endloop
  endfacet
  facet normal 0.103446 0.994635 0.000000
    outer loop
      vertex 120.043213 205.596252 3.000000
      vertex 121.603073 205.434021 3.000000
      vertex 120.043213 205.596252 0.000000
    endloop
  endfacet
  facet normal 0.090186 0.995925 0.000000
    outer loop
      vertex 118.464005 205.739258 0.000000
      vertex 120.043213 205.596252 3.000000
      vertex 120.043213 205.596252 0.000000
    endloop
  endfacet
  facet normal 0.090186 0.995925 0.000000
    outer loop
      vertex 118.464005 205.739258 3.000000
      vertex 120.043213 205.596252 3.000000
      vertex 118.464005 205.739258 0.000000
    endloop
  endfacet
  facet normal 0.077223 0.997014 0.000000
    outer loop
      vertex 116.865311 205.863083 0.000000
      vertex 118.464005 205.739258 3.000000
      vertex 118.464005 205.739258 0.000000
    endloop
  endfacet
  facet normal 0.077223 0.997014 0.000000
    outer loop
      vertex 116.865311 205.863083 3.000000
      vertex 118.464005 205.739258 3.000000
      vertex 116.865311 205.863083 0.000000
    endloop
  endfacet
  facet normal 0.064555 0.997914 0.000000
    outer loop
      vertex 115.246971 205.967773 0.000000
      vertex 116.865311 205.863083 3.000000
      vertex 116.865311 205.863083 0.000000
    endloop
  endfacet
  facet normal 0.064555 0.997914 0.000000
    outer loop
      vertex 115.246971 205.967773 3.000000
      vertex 116.865311 205.863083 3.000000
      vertex 115.246971 205.967773 0.000000
    endloop
  endfacet
  facet normal 0.052166 0.998638 0.000000
    outer loop
      vertex 113.608826 206.053345 0.000000
      vertex 115.246971 205.967773 3.000000
      vertex 115.246971 205.967773 0.000000
    endloop
  endfacet
  facet normal 0.052166 0.998638 0.000000
    outer loop
      vertex 113.608826 206.053345 3.000000
      vertex 115.246971 205.967773 3.000000
      vertex 113.608826 206.053345 0.000000
    endloop
  endfacet
  facet normal 0.040073 0.999197 0.000000
    outer loop
      vertex 111.950722 206.119843 0.000000
      vertex 113.608826 206.053345 3.000000
      vertex 113.608826 206.053345 0.000000
    endloop
  endfacet
  facet normal 0.040073 0.999197 0.000000
    outer loop
      vertex 111.950722 206.119843 3.000000
      vertex 113.608826 206.053345 3.000000
      vertex 111.950722 206.119843 0.000000
    endloop
  endfacet
  facet normal 0.028275 0.999600 0.000000
    outer loop
      vertex 110.272499 206.167313 0.000000
      vertex 111.950722 206.119843 3.000000
      vertex 111.950722 206.119843 0.000000
    endloop
  endfacet
  facet normal 0.028275 0.999600 0.000000
    outer loop
      vertex 110.272499 206.167313 3.000000
      vertex 111.950722 206.119843 3.000000
      vertex 110.272499 206.167313 0.000000
    endloop
  endfacet
  facet normal 0.016743 0.999860 0.000000
    outer loop
      vertex 108.573997 206.195755 0.000000
      vertex 110.272499 206.167313 3.000000
      vertex 110.272499 206.167313 0.000000
    endloop
  endfacet
  facet normal 0.016743 0.999860 0.000000
    outer loop
      vertex 108.573997 206.195755 3.000000
      vertex 110.272499 206.167313 3.000000
      vertex 108.573997 206.195755 0.000000
    endloop
  endfacet
  facet normal 0.005513 0.999985 0.000000
    outer loop
      vertex 106.855080 206.205231 0.000000
      vertex 108.573997 206.195755 3.000000
      vertex 108.573997 206.195755 0.000000
    endloop
  endfacet
  facet normal 0.005513 0.999985 0.000000
    outer loop
      vertex 106.855080 206.205231 3.000000
      vertex 108.573997 206.195755 3.000000
      vertex 106.855080 206.205231 0.000000
    endloop
  endfacet
  facet normal -0.006026 0.999982 0.000000
    outer loop
      vertex 104.986458 206.193970 0.000000
      vertex 106.855080 206.205231 3.000000
      vertex 106.855080 206.205231 0.000000
    endloop
  endfacet
  facet normal -0.006026 0.999982 0.000000
    outer loop
      vertex 104.986458 206.193970 3.000000
      vertex 106.855080 206.205231 3.000000
      vertex 104.986458 206.193970 0.000000
    endloop
  endfacet
  facet normal -0.017861 0.999840 0.000000
    outer loop
      vertex 103.093575 206.160156 0.000000
      vertex 104.986458 206.193970 3.000000
      vertex 104.986458 206.193970 0.000000
    endloop
  endfacet
  facet normal -0.017861 0.999840 0.000000
    outer loop
      vertex 103.093575 206.160156 3.000000
      vertex 104.986458 206.193970 3.000000
      vertex 103.093575 206.160156 0.000000
    endloop
  endfacet
  facet normal -0.029400 0.999568 0.000000
    outer loop
      vertex 101.176178 206.103760 0.000000
      vertex 103.093575 206.160156 3.000000
      vertex 103.093575 206.160156 0.000000
    endloop
  endfacet
  facet normal -0.029400 0.999568 0.000000
    outer loop
      vertex 101.176178 206.103760 3.000000
      vertex 103.093575 206.160156 3.000000
      vertex 101.176178 206.103760 0.000000
    endloop
  endfacet
  facet normal -0.040664 0.999173 0.000000
    outer loop
      vertex 99.234016 206.024719 0.000000
      vertex 101.176178 206.103760 3.000000
      vertex 101.176178 206.103760 0.000000
    endloop
  endfacet
  facet normal -0.040664 0.999173 0.000000
    outer loop
      vertex 99.234016 206.024719 3.000000
      vertex 101.176178 206.103760 3.000000
      vertex 99.234016 206.024719 0.000000
    endloop
  endfacet
  facet normal -0.051630 0.998666 0.000000
    outer loop
      vertex 97.266846 205.923019 0.000000
      vertex 99.234016 206.024719 3.000000
      vertex 99.234016 206.024719 0.000000
    endloop
  endfacet
  facet normal -0.051630 0.998666 0.000000
    outer loop
      vertex 97.266846 205.923019 3.000000
      vertex 99.234016 206.024719 3.000000
      vertex 97.266846 205.923019 0.000000
    endloop
  endfacet
  facet normal -0.062325 0.998056 0.000000
    outer loop
      vertex 95.274414 205.798599 0.000000
      vertex 97.266846 205.923019 3.000000
      vertex 97.266846 205.923019 0.000000
    endloop
  endfacet
  facet normal -0.062325 0.998056 0.000000
    outer loop
      vertex 95.274414 205.798599 3.000000
      vertex 97.266846 205.923019 3.000000
      vertex 95.274414 205.798599 0.000000
    endloop
  endfacet
  facet normal -0.072738 0.997351 0.000000
    outer loop
      vertex 93.256470 205.651428 0.000000
      vertex 95.274414 205.798599 3.000000
      vertex 95.274414 205.798599 0.000000
    endloop
  endfacet
  facet normal -0.072738 0.997351 0.000000
    outer loop
      vertex 93.256470 205.651428 3.000000
      vertex 95.274414 205.798599 3.000000
      vertex 93.256470 205.651428 0.000000
    endloop
  endfacet
  facet normal -0.082880 0.996560 0.000000
    outer loop
      vertex 91.212761 205.481461 0.000000
      vertex 93.256470 205.651428 3.000000
      vertex 93.256470 205.651428 0.000000
    endloop
  endfacet
  facet normal -0.082880 0.996560 0.000000
    outer loop
      vertex 91.212761 205.481461 3.000000
      vertex 93.256470 205.651428 3.000000
      vertex 91.212761 205.481461 0.000000
    endloop
  endfacet
  facet normal -0.092741 0.995690 0.000000
    outer loop
      vertex 89.143036 205.288681 0.000000
      vertex 91.212761 205.481461 3.000000
      vertex 91.212761 205.481461 0.000000
    endloop
  endfacet
  facet normal -0.092741 0.995690 0.000000
    outer loop
      vertex 89.143036 205.288681 3.000000
      vertex 91.212761 205.481461 3.000000
      vertex 89.143036 205.288681 0.000000
    endloop
  endfacet
  facet normal -0.102355 0.994748 0.000000
    outer loop
      vertex 87.047050 205.073013 0.000000
      vertex 89.143036 205.288681 3.000000
      vertex 89.143036 205.288681 0.000000
    endloop
  endfacet
  facet normal -0.102355 0.994748 0.000000
    outer loop
      vertex 87.047050 205.073013 3.000000
      vertex 89.143036 205.288681 3.000000
      vertex 87.047050 205.073013 0.000000
    endloop
  endfacet
  facet normal -0.111705 0.993741 0.000000
    outer loop
      vertex 84.924553 204.834427 0.000000
      vertex 87.047050 205.073013 3.000000
      vertex 87.047050 205.073013 0.000000
    endloop
  endfacet
  facet normal -0.111705 0.993741 0.000000
    outer loop
      vertex 84.924553 204.834427 3.000000
      vertex 87.047050 205.073013 3.000000
      vertex 84.924553 204.834427 0.000000
    endloop
  endfacet
  facet normal -0.120788 0.992678 0.000000
    outer loop
      vertex 82.775291 204.572906 0.000000
      vertex 84.924553 204.834427 3.000000
      vertex 84.924553 204.834427 0.000000
    endloop
  endfacet
  facet normal -0.120788 0.992678 0.000000
    outer loop
      vertex 82.775291 204.572906 3.000000
      vertex 84.924553 204.834427 3.000000
      vertex 82.775291 204.572906 0.000000
    endloop
  endfacet
  facet normal -0.129639 0.991561 0.000000
    outer loop
      vertex 80.599014 204.288376 0.000000
      vertex 82.775291 204.572906 3.000000
      vertex 82.775291 204.572906 0.000000
    endloop
  endfacet
  facet normal -0.129639 0.991561 0.000000
    outer loop
      vertex 80.599014 204.288376 3.000000
      vertex 82.775291 204.572906 3.000000
      vertex 80.599014 204.288376 0.000000
    endloop
  endfacet
  facet normal -0.138233 0.990400 0.000000
    outer loop
      vertex 78.395470 203.980820 0.000000
      vertex 80.599014 204.288376 3.000000
      vertex 80.599014 204.288376 0.000000
    endloop
  endfacet
  facet normal -0.138233 0.990400 0.000000
    outer loop
      vertex 78.395470 203.980820 3.000000
      vertex 80.599014 204.288376 3.000000
      vertex 78.395470 203.980820 0.000000
    endloop
  endfacet
  facet normal -0.146593 0.989197 0.000000
    outer loop
      vertex 76.164421 203.650192 0.000000
      vertex 78.395470 203.980820 3.000000
      vertex 78.395470 203.980820 0.000000
    endloop
  endfacet
  facet normal -0.146593 0.989197 0.000000
    outer loop
      vertex 76.164421 203.650192 3.000000
      vertex 78.395470 203.980820 3.000000
      vertex 76.164421 203.650192 0.000000
    endloop
  endfacet
  facet normal -0.154720 0.987958 0.000000
    outer loop
      vertex 73.905602 203.296448 0.000000
      vertex 76.164421 203.650192 3.000000
      vertex 76.164421 203.650192 0.000000
    endloop
  endfacet
  facet normal -0.154720 0.987958 0.000000
    outer loop
      vertex 73.905602 203.296448 3.000000
      vertex 76.164421 203.650192 3.000000
      vertex 73.905602 203.296448 0.000000
    endloop
  endfacet
  facet normal -0.162616 0.986689 0.000000
    outer loop
      vertex 71.618774 202.919556 0.000000
      vertex 73.905602 203.296448 3.000000
      vertex 73.905602 203.296448 0.000000
    endloop
  endfacet
  facet normal -0.162616 0.986689 0.000000
    outer loop
      vertex 71.618774 202.919556 3.000000
      vertex 73.905602 203.296448 3.000000
      vertex 71.618774 202.919556 0.000000
    endloop
  endfacet
  facet normal -0.170292 0.985394 0.000000
    outer loop
      vertex 69.303680 202.519470 0.000000
      vertex 71.618774 202.919556 3.000000
      vertex 71.618774 202.919556 0.000000
    endloop
  endfacet
  facet normal -0.170292 0.985394 0.000000
    outer loop
      vertex 69.303680 202.519470 3.000000
      vertex 71.618774 202.919556 3.000000
      vertex 69.303680 202.519470 0.000000
    endloop
  endfacet
  facet normal -0.177753 0.984075 0.000000
    outer loop
      vertex 66.960068 202.096146 0.000000
      vertex 69.303680 202.519470 3.000000
      vertex 69.303680 202.519470 0.000000
    endloop
  endfacet
  facet normal -0.177753 0.984075 0.000000
    outer loop
      vertex 66.960068 202.096146 3.000000
      vertex 69.303680 202.519470 3.000000
      vertex 66.960068 202.096146 0.000000
    endloop
  endfacet
  facet normal -0.184999 0.982739 0.000000
    outer loop
      vertex 64.587700 201.649551 0.000000
      vertex 66.960068 202.096146 3.000000
      vertex 66.960068 202.096146 0.000000
    endloop
  endfacet
  facet normal -0.184999 0.982739 0.000000
    outer loop
      vertex 64.587700 201.649551 3.000000
      vertex 66.960068 202.096146 3.000000
      vertex 64.587700 201.649551 0.000000
    endloop
  endfacet
  facet normal -0.192040 0.981387 0.000000
    outer loop
      vertex 62.186310 201.179642 0.000000
      vertex 64.587700 201.649551 3.000000
      vertex 64.587700 201.649551 0.000000
    endloop
  endfacet
  facet normal -0.192040 0.981387 0.000000
    outer loop
      vertex 62.186310 201.179642 3.000000
      vertex 64.587700 201.649551 3.000000
      vertex 62.186310 201.179642 0.000000
    endloop
  endfacet
  facet normal -0.198884 0.980023 0.000000
    outer loop
      vertex 59.755661 200.686371 0.000000
      vertex 62.186310 201.179642 3.000000
      vertex 62.186310 201.179642 0.000000
    endloop
  endfacet
  facet normal -0.198884 0.980023 0.000000
    outer loop
      vertex 59.755661 200.686371 3.000000
      vertex 62.186310 201.179642 3.000000
      vertex 59.755661 200.686371 0.000000
    endloop
  endfacet
  facet normal -0.205528 0.978651 0.000000
    outer loop
      vertex 57.295494 200.169708 0.000000
      vertex 59.755661 200.686371 3.000000
      vertex 59.755661 200.686371 0.000000
    endloop
  endfacet
  facet normal -0.205528 0.978651 0.000000
    outer loop
      vertex 57.295494 200.169708 3.000000
      vertex 59.755661 200.686371 3.000000
      vertex 57.295494 200.169708 0.000000
    endloop
  endfacet
  facet normal -0.211978 0.977274 0.000000
    outer loop
      vertex 54.805565 199.629623 0.000000
      vertex 57.295494 200.169708 3.000000
      vertex 57.295494 200.169708 0.000000
    endloop
  endfacet
  facet normal -0.211978 0.977274 0.000000
    outer loop
      vertex 54.805565 199.629623 3.000000
      vertex 57.295494 200.169708 3.000000
      vertex 54.805565 199.629623 0.000000
    endloop
  endfacet
  facet normal -0.218252 0.975893 0.000000
    outer loop
      vertex 52.285622 199.066055 0.000000
      vertex 54.805565 199.629623 3.000000
      vertex 54.805565 199.629623 0.000000
    endloop
  endfacet
  facet normal -0.218252 0.975893 0.000000
    outer loop
      vertex 52.285622 199.066055 3.000000
      vertex 54.805565 199.629623 3.000000
      vertex 52.285622 199.066055 0.000000
    endloop
  endfacet
  facet normal -0.224347 0.974509 0.000000
    outer loop
      vertex 49.735413 198.478958 0.000000
      vertex 52.285622 199.066055 3.000000
      vertex 52.285622 199.066055 0.000000
    endloop
  endfacet
  facet normal -0.224347 0.974509 0.000000
    outer loop
      vertex 49.735413 198.478958 3.000000
      vertex 52.285622 199.066055 3.000000
      vertex 49.735413 198.478958 0.000000
    endloop
  endfacet
  facet normal -0.230258 0.973130 0.000000
    outer loop
      vertex 47.154690 197.868317 0.000000
      vertex 49.735413 198.478958 3.000000
      vertex 49.735413 198.478958 0.000000
    endloop
  endfacet
  facet normal -0.230258 0.973130 0.000000
    outer loop
      vertex 47.154690 197.868317 3.000000
      vertex 49.735413 198.478958 3.000000
      vertex 47.154690 197.868317 0.000000
    endloop
  endfacet
  facet normal -0.236002 0.971753 0.000000
    outer loop
      vertex 44.543201 197.234085 0.000000
      vertex 47.154690 197.868317 3.000000
      vertex 47.154690 197.868317 0.000000
    endloop
  endfacet
  facet normal -0.236002 0.971753 0.000000
    outer loop
      vertex 44.543201 197.234085 3.000000
      vertex 47.154690 197.868317 3.000000
      vertex 44.543201 197.234085 0.000000
    endloop
  endfacet
  facet normal -0.241582 0.970380 0.000000
    outer loop
      vertex 41.900700 196.576218 0.000000
      vertex 44.543201 197.234085 3.000000
      vertex 44.543201 197.234085 0.000000
    endloop
  endfacet
  facet normal -0.241582 0.970380 0.000000
    outer loop
      vertex 41.900700 196.576218 3.000000
      vertex 44.543201 197.234085 3.000000
      vertex 41.900700 196.576218 0.000000
    endloop
  endfacet
  facet normal -0.247004 0.969014 0.000000
    outer loop
      vertex 39.226933 195.894669 0.000000
      vertex 41.900700 196.576218 3.000000
      vertex 41.900700 196.576218 0.000000
    endloop
  endfacet
  facet normal -0.247004 0.969014 0.000000
    outer loop
      vertex 39.226933 195.894669 3.000000
      vertex 41.900700 196.576218 3.000000
      vertex 39.226933 195.894669 0.000000
    endloop
  endfacet
  facet normal -0.252266 0.967658 0.000000
    outer loop
      vertex 36.521648 195.189407 0.000000
      vertex 39.226933 195.894669 3.000000
      vertex 39.226933 195.894669 0.000000
    endloop
  endfacet
  facet normal -0.252266 0.967658 0.000000
    outer loop
      vertex 36.521648 195.189407 3.000000
      vertex 39.226933 195.894669 3.000000
      vertex 36.521648 195.189407 0.000000
    endloop
  endfacet
  facet normal -0.257379 0.966310 0.000000
    outer loop
      vertex 33.784603 194.460388 0.000000
      vertex 36.521648 195.189407 3.000000
      vertex 36.521648 195.189407 0.000000
    endloop
  endfacet
  facet normal -0.257379 0.966310 0.000000
    outer loop
      vertex 33.784603 194.460388 3.000000
      vertex 36.521648 195.189407 3.000000
      vertex 33.784603 194.460388 0.000000
    endloop
  endfacet
  facet normal 0.476440 0.879207 0.000000
    outer loop
      vertex 154.073029 195.471695 3.000000
      vertex 154.073029 195.471695 0.000000
      vertex 152.502426 196.322800 0.000000
    endloop
  endfacet
  facet normal 0.476440 0.879207 0.000000
    outer loop
      vertex 152.502426 196.322800 3.000000
      vertex 154.073029 195.471695 3.000000
      vertex 152.502426 196.322800 0.000000
    endloop
  endfacet
  facet normal 0.997685 0.068005 0.000000
    outer loop
      vertex 155.643661 192.834167 3.000000
      vertex 155.643661 192.834167 0.000000
      vertex 155.615860 193.242035 0.000000
    endloop
  endfacet
  facet normal 0.997685 0.068005 0.000000
    outer loop
      vertex 155.615860 193.242035 3.000000
      vertex 155.643661 192.834167 3.000000
      vertex 155.615860 193.242035 0.000000
    endloop
  endfacet
  facet normal 0.979353 0.202160 0.000000
    outer loop
      vertex 155.534348 193.636917 0.000000
      vertex 155.615860 193.242035 3.000000
      vertex 155.615860 193.242035 0.000000
    endloop
  endfacet
  facet normal 0.979353 0.202160 0.000000
    outer loop
      vertex 155.534348 193.636917 3.000000
      vertex 155.615860 193.242035 3.000000
      vertex 155.534348 193.636917 0.000000
    endloop
  endfacet
  facet normal 0.943521 0.331312 0.000000
    outer loop
      vertex 155.401886 194.014145 0.000000
      vertex 155.534348 193.636917 3.000000
      vertex 155.534348 193.636917 0.000000
    endloop
  endfacet
  facet normal 0.943521 0.331312 0.000000
    outer loop
      vertex 155.401886 194.014145 3.000000
      vertex 155.534348 193.636917 3.000000
      vertex 155.401886 194.014145 0.000000
    endloop
  endfacet
  facet normal 0.891224 0.453563 0.000000
    outer loop
      vertex 155.221268 194.369049 0.000000
      vertex 155.401886 194.014145 3.000000
      vertex 155.401886 194.014145 0.000000
    endloop
  endfacet
  facet normal 0.891224 0.453563 0.000000
    outer loop
      vertex 155.221268 194.369049 3.000000
      vertex 155.401886 194.014145 3.000000
      vertex 155.221268 194.369049 0.000000
    endloop
  endfacet
  facet normal 0.823392 0.567473 0.000000
    outer loop
      vertex 154.995285 194.696945 0.000000
      vertex 155.221268 194.369049 3.000000
      vertex 155.221268 194.369049 0.000000
    endloop
  endfacet
  facet normal 0.823392 0.567473 0.000000
    outer loop
      vertex 154.995285 194.696945 3.000000
      vertex 155.221268 194.369049 3.000000
      vertex 154.995285 194.696945 0.000000
    endloop
  endfacet
  facet normal 0.740820 0.671703 0.000000
    outer loop
      vertex 154.726730 194.993134 0.000000
      vertex 154.995285 194.696945 3.000000
      vertex 154.995285 194.696945 0.000000
    endloop
  endfacet
  facet normal 0.740820 0.671703 0.000000
    outer loop
      vertex 154.726730 194.993134 3.000000
      vertex 154.995285 194.696945 3.000000
      vertex 154.726730 194.993134 0.000000
    endloop
  endfacet
  facet normal 0.644351 0.764730 0.000000
    outer loop
      vertex 154.418381 195.252945 0.000000
      vertex 154.726730 194.993134 3.000000
      vertex 154.726730 194.993134 0.000000
    endloop
  endfacet
  facet normal 0.644351 0.764730 0.000000
    outer loop
      vertex 154.418381 195.252945 3.000000
      vertex 154.726730 194.993134 3.000000
      vertex 154.418381 195.252945 0.000000
    endloop
  endfacet
  facet normal 0.535099 0.844789 0.000000
    outer loop
      vertex 154.073029 195.471695 0.000000
      vertex 154.418381 195.252945 3.000000
      vertex 154.418381 195.252945 0.000000
    endloop
  endfacet
  facet normal 0.535099 0.844789 0.000000
    outer loop
      vertex 154.073029 195.471695 3.000000
      vertex 154.418381 195.252945 3.000000
      vertex 154.073029 195.471695 0.000000
    endloop
  endfacet
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex 155.643661 143.422668 3.000000
      vertex 155.643661 143.422668 0.000000
      vertex 155.643661 192.834167 0.000000
    endloop
  endfacet
  facet normal 1.000000 0.000000 0.000000
    outer loop
      vertex 155.643661 192.834167 3.000000
      vertex 155.643661 143.422668 3.000000
      vertex 155.643661 192.834167 0.000000
    endloop
  endfacet
  facet normal 0.904281 -0.426938 0.000000
    outer loop
      vertex 155.444077 141.223419 3.000000
      vertex 155.444077 141.223419 0.000000
      vertex 155.578491 141.508118 0.000000
    endloop
  endfacet
  facet normal 0.904281 -0.426938 0.000000
    outer loop
      vertex 155.578491 141.508118 3.000000
      vertex 155.444077 141.223419 3.000000
      vertex 155.578491 141.508118 0.000000
    endloop
  endfacet
  facet normal 0.960415 -0.278572 0.000000
    outer loop
      vertex 155.665619 141.808502 0.000000
      vertex 155.578491 141.508118 3.000000
      vertex 155.578491 141.508118 0.000000
    endloop
  endfacet
  facet normal 0.960415 -0.278572 0.000000
    outer loop
      vertex 155.665619 141.808502 3.000000
      vertex 155.578491 141.508118 3.000000
      vertex 155.665619 141.808502 0.000000
    endloop
  endfacet
  facet normal 0.992075 -0.125649 0.000000
    outer loop
      vertex 155.704941 142.118973 0.000000
      vertex 155.665619 141.808502 3.000000
      vertex 155.665619 141.808502 0.000000
    endloop
  endfacet
  facet normal 0.992075 -0.125649 0.000000
    outer loop
      vertex 155.704941 142.118973 3.000000
      vertex 155.665619 141.808502 3.000000
      vertex 155.704941 142.118973 0.000000
    endloop
  endfacet
  facet normal 0.999593 0.028524 0.000000
    outer loop
      vertex 155.695953 142.433929 0.000000
      vertex 155.704941 142.118973 3.000000
      vertex 155.704941 142.118973 0.000000
    endloop
  endfacet
  facet normal 0.999593 0.028524 0.000000
    outer loop
      vertex 155.695953 142.433929 3.000000
      vertex 155.704941 142.118973 3.000000
      vertex 155.695953 142.433929 0.000000
    endloop
  endfacet
  facet normal 0.996857 0.079228 0.000000
    outer loop
      vertex 155.656876 142.925613 0.000000
      vertex 155.695953 142.433929 3.000000
      vertex 155.695953 142.433929 0.000000
    endloop
  endfacet
  facet normal 0.996857 0.079228 0.000000
    outer loop
      vertex 155.656876 142.925613 3.000000
      vertex 155.695953 142.433929 3.000000
      vertex 155.656876 142.925613 0.000000
    endloop
  endfacet
  facet normal 0.999647 0.026575 0.000000
    outer loop
      vertex 155.643661 143.422668 0.000000
      vertex 155.656876 142.925613 3.000000
      vertex 155.656876 142.925613 0.000000
    endloop
  endfacet
  facet normal 0.999647 0.026575 0.000000
    outer loop
      vertex 155.643661 143.422668 3.000000
      vertex 155.656876 142.925613 3.000000
      vertex 155.643661 143.422668 0.000000
    endloop
  endfacet
  facet normal 0.867231 -0.497906 0.000000
    outer loop
      vertex 150.811142 133.153976 3.000000
      vertex 150.811142 133.153976 0.000000
      vertex 155.444077 141.223419 0.000000
    endloop
  endfacet
  facet normal 0.867231 -0.497906 0.000000
    outer loop
      vertex 155.444077 141.223419 3.000000
      vertex 150.811142 133.153976 3.000000
      vertex 155.444077 141.223419 0.000000
    endloop
  endfacet
  facet normal 0.542966 0.839754 0.000000
    outer loop
      vertex 151.178375 131.790039 3.000000
      vertex 151.178375 131.790039 0.000000
      vertex 151.092545 131.845535 0.000000
    endloop
  endfacet
  facet normal 0.542966 0.839754 0.000000
    outer loop
      vertex 151.092545 131.845535 3.000000
      vertex 151.178375 131.790039 3.000000
      vertex 151.092545 131.845535 0.000000
    endloop
  endfacet
  facet normal 0.624806 0.780780 0.000000
    outer loop
      vertex 151.014252 131.908188 0.000000
      vertex 151.092545 131.845535 3.000000
      vertex 151.092545 131.845535 0.000000
    endloop
  endfacet
  facet normal 0.624806 0.780780 0.000000
    outer loop
      vertex 151.014252 131.908188 3.000000
      vertex 151.092545 131.845535 3.000000
      vertex 151.014252 131.908188 0.000000
    endloop
  endfacet
  facet normal 0.699577 0.714557 0.000000
    outer loop
      vertex 150.943649 131.977310 0.000000
      vertex 151.014252 131.908188 3.000000
      vertex 151.014252 131.908188 0.000000
    endloop
  endfacet
  facet normal 0.699577 0.714557 0.000000
    outer loop
      vertex 150.943649 131.977310 3.000000
      vertex 151.014252 131.908188 3.000000
      vertex 150.943649 131.977310 0.000000
    endloop
  endfacet
  facet normal 0.766824 0.641858 0.000000
    outer loop
      vertex 150.880951 132.052216 0.000000
      vertex 150.943649 131.977310 3.000000
      vertex 150.943649 131.977310 0.000000
    endloop
  endfacet
  facet normal 0.766824 0.641858 0.000000
    outer loop
      vertex 150.880951 132.052216 3.000000
      vertex 150.943649 131.977310 3.000000
      vertex 150.880951 132.052216 0.000000
    endloop
  endfacet
  facet normal 0.825967 0.563718 0.000000
    outer loop
      vertex 150.826340 132.132233 0.000000
      vertex 150.880951 132.052216 3.000000
      vertex 150.880951 132.052216 0.000000
    endloop
  endfacet
  facet normal 0.825967 0.563718 0.000000
    outer loop
      vertex 150.826340 132.132233 3.000000
      vertex 150.880951 132.052216 3.000000
      vertex 150.826340 132.132233 0.000000
    endloop
  endfacet
  facet normal 0.876530 0.481347 0.000000
    outer loop
      vertex 150.779968 132.216675 0.000000
      vertex 150.826340 132.132233 3.000000
      vertex 150.826340 132.132233 0.000000
    endloop
  endfacet
  facet normal 0.876530 0.481347 0.000000
    outer loop
      vertex 150.779968 132.216675 3.000000
      vertex 150.826340 132.132233 3.000000
      vertex 150.779968 132.216675 0.000000
    endloop
  endfacet
  facet normal 0.918667 0.395032 0.000000
    outer loop
      vertex 150.742050 132.304855 0.000000
      vertex 150.779968 132.216675 3.000000
      vertex 150.779968 132.216675 0.000000
    endloop
  endfacet
  facet normal 0.918667 0.395032 0.000000
    outer loop
      vertex 150.742050 132.304855 3.000000
      vertex 150.779968 132.216675 3.000000
      vertex 150.742050 132.304855 0.000000
    endloop
  endfacet
  facet normal 0.952159 0.305602 0.000000
    outer loop
      vertex 150.712769 132.396088 0.000000
      vertex 150.742050 132.304855 3.000000
      vertex 150.742050 132.304855 0.000000
    endloop
  endfacet
  facet normal 0.952159 0.305602 0.000000
    outer loop
      vertex 150.712769 132.396088 3.000000
      vertex 150.742050 132.304855 3.000000
      vertex 150.712769 132.396088 0.000000
    endloop
  endfacet
  facet normal 0.976894 0.213725 0.000000
    outer loop
      vertex 150.692291 132.489685 0.000000
      vertex 150.712769 132.396088 3.000000
      vertex 150.712769 132.396088 0.000000
    endloop
  endfacet
  facet normal 0.976894 0.213725 0.000000
    outer loop
      vertex 150.692291 132.489685 3.000000
      vertex 150.712769 132.396088 3.000000
      vertex 150.692291 132.489685 0.000000
    endloop
  endfacet
  facet normal 0.992811 0.119691 0.000000
    outer loop
      vertex 150.680801 132.584991 0.000000
      vertex 150.692291 132.489685 3.000000
      vertex 150.692291 132.489685 0.000000
    endloop
  endfacet
  facet normal 0.992811 0.119691 0.000000
    outer loop
      vertex 150.680801 132.584991 3.000000
      vertex 150.692291 132.489685 3.000000
      vertex 150.680801 132.584991 0.000000
    endloop
  endfacet
  facet normal 0.999714 0.023920 0.000000
    outer loop
      vertex 150.678497 132.681290 0.000000
      vertex 150.680801 132.584991 3.000000
      vertex 150.680801 132.584991 0.000000
    endloop
  endfacet
  facet normal 0.999714 0.023920 0.000000
    outer loop
      vertex 150.678497 132.681290 3.000000
      vertex 150.680801 132.584991 3.000000
      vertex 150.678497 132.681290 0.000000
    endloop
  endfacet
  facet normal 0.997337 -0.072926 0.000000
    outer loop
      vertex 150.685562 132.777908 0.000000
      vertex 150.678497 132.681290 3.000000
      vertex 150.678497 132.681290 0.000000
    endloop
  endfacet
  facet normal 0.997337 -0.072926 0.000000
    outer loop
      vertex 150.685562 132.777908 3.000000
      vertex 150.678497 132.681290 3.000000
      vertex 150.685562 132.777908 0.000000
    endloop
  endfacet
  facet normal 0.985428 -0.170095 0.000000
    outer loop
      vertex 150.702179 132.874176 0.000000
      vertex 150.685562 132.777908 3.000000
      vertex 150.685562 132.777908 0.000000
    endloop
  endfacet
  facet normal 0.985428 -0.170095 0.000000
    outer loop
      vertex 150.702179 132.874176 3.000000
      vertex 150.685562 132.777908 3.000000
      vertex 150.702179 132.874176 0.000000
    endloop
  endfacet
  facet normal 0.963770 -0.266736 0.000000
    outer loop
      vertex 150.728531 132.969391 0.000000
      vertex 150.702179 132.874176 3.000000
      vertex 150.702179 132.874176 0.000000
    endloop
  endfacet
  facet normal 0.963770 -0.266736 0.000000
    outer loop
      vertex 150.728531 132.969391 3.000000
      vertex 150.702179 132.874176 3.000000
      vertex 150.728531 132.969391 0.000000
    endloop
  endfacet
  facet normal 0.932370 -0.361506 0.000000
    outer loop
      vertex 150.764786 133.062897 0.000000
      vertex 150.728531 132.969391 3.000000
      vertex 150.728531 132.969391 0.000000
    endloop
  endfacet
  facet normal 0.932370 -0.361506 0.000000
    outer loop
      vertex 150.764786 133.062897 3.000000
      vertex 150.728531 132.969391 3.000000
      vertex 150.764786 133.062897 0.000000
    endloop
  endfacet
  facet normal 0.891209 -0.453592 0.000000
    outer loop
      vertex 150.811142 133.153976 0.000000
      vertex 150.764786 133.062897 3.000000
      vertex 150.764786 133.062897 0.000000
    endloop
  endfacet
  facet normal 0.891209 -0.453592 0.000000
    outer loop
      vertex 150.811142 133.153976 3.000000
      vertex 150.764786 133.062897 3.000000
      vertex 150.811142 133.153976 0.000000
    endloop
  endfacet
  facet normal 0.500000 0.866026 0.000000
    outer loop
      vertex 160.669098 126.310570 3.000000
      vertex 160.669098 126.310570 0.000000
      vertex 151.178375 131.790039 0.000000
    endloop
  endfacet
  facet normal 0.500000 0.866026 0.000000
    outer loop
      vertex 151.178375 131.790039 3.000000
      vertex 160.669098 126.310570 3.000000
      vertex 151.178375 131.790039 0.000000
    endloop
  endfacet
  facet normal -0.839742 0.542985 0.000000
    outer loop
      vertex 162.035110 126.676598 3.000000
      vertex 162.035110 126.676598 0.000000
      vertex 161.979523 126.590630 0.000000
    endloop
  endfacet
  facet normal -0.839742 0.542985 0.000000
    outer loop
      vertex 161.979523 126.590630 3.000000
      vertex 162.035110 126.676598 3.000000
      vertex 161.979523 126.590630 0.000000
    endloop
  endfacet
  facet normal -0.780632 0.624991 0.000000
    outer loop
      vertex 161.916748 126.512222 0.000000
      vertex 161.979523 126.590630 3.000000
      vertex 161.979523 126.590630 0.000000
    endloop
  endfacet
  facet normal -0.780632 0.624991 0.000000
    outer loop
      vertex 161.916748 126.512222 3.000000
      vertex 161.979523 126.590630 3.000000
      vertex 161.916748 126.512222 0.000000
    endloop
  endfacet
  facet normal -0.714318 0.699822 0.000000
    outer loop
      vertex 161.847504 126.441544 0.000000
      vertex 161.916748 126.512222 3.000000
      vertex 161.916748 126.512222 0.000000
    endloop
  endfacet
  facet normal -0.714318 0.699822 0.000000
    outer loop
      vertex 161.847504 126.441544 3.000000
      vertex 161.916748 126.512222 3.000000
      vertex 161.847504 126.441544 0.000000
    endloop
  endfacet
  facet normal -0.641334 0.767262 0.000000
    outer loop
      vertex 161.772430 126.378792 0.000000
      vertex 161.847504 126.441544 3.000000
      vertex 161.847504 126.441544 0.000000
    endloop
  endfacet
  facet normal -0.641334 0.767262 0.000000
    outer loop
      vertex 161.772430 126.378792 3.000000
      vertex 161.847504 126.441544 3.000000
      vertex 161.772430 126.378792 0.000000
    endloop
  endfacet
  facet normal -0.563254 0.826284 0.000000
    outer loop
      vertex 161.692261 126.324142 0.000000
      vertex 161.772430 126.378792 3.000000
      vertex 161.772430 126.378792 0.000000
    endloop
  endfacet
  facet normal -0.563254 0.826284 0.000000
    outer loop
      vertex 161.692261 126.324142 3.000000
      vertex 161.772430 126.378792 3.000000
      vertex 161.692261 126.324142 0.000000
    endloop
  endfacet
  facet normal -0.480491 0.876999 0.000000
    outer loop
      vertex 161.607651 126.277786 0.000000
      vertex 161.692261 126.324142 3.000000
      vertex 161.692261 126.324142 0.000000
    endloop
  endfacet
  facet normal -0.480491 0.876999 0.000000
    outer loop
      vertex 161.607651 126.277786 3.000000
      vertex 161.692261 126.324142 3.000000
      vertex 161.607651 126.277786 0.000000
    endloop
  endfacet
  facet normal -0.394188 0.919030 0.000000
    outer loop
      vertex 161.519318 126.239899 0.000000
      vertex 161.607651 126.277786 3.000000
      vertex 161.607651 126.277786 0.000000
    endloop
  endfacet
  facet normal -0.394188 0.919030 0.000000
    outer loop
      vertex 161.519318 126.239899 3.000000
      vertex 161.607651 126.277786 3.000000
      vertex 161.519318 126.239899 0.000000
    endloop
  endfacet
  facet normal -0.304542 0.952499 0.000000
    outer loop
      vertex 161.427902 126.210670 0.000000
      vertex 161.519318 126.239899 3.000000
      vertex 161.519318 126.239899 0.000000
    endloop
  endfacet
  facet normal -0.304542 0.952499 0.000000
    outer loop
      vertex 161.427902 126.210670 3.000000
      vertex 161.519318 126.239899 3.000000
      vertex 161.427902 126.210670 0.000000
    endloop
  endfacet
  facet normal -0.212449 0.977172 0.000000
    outer loop
      vertex 161.334137 126.190285 0.000000
      vertex 161.427902 126.210670 3.000000
      vertex 161.427902 126.210670 0.000000
    endloop
  endfacet
  facet normal -0.212449 0.977172 0.000000
    outer loop
      vertex 161.334137 126.190285 3.000000
      vertex 161.427902 126.210670 3.000000
      vertex 161.334137 126.190285 0.000000
    endloop
  endfacet
  facet normal -0.118269 0.992982 0.000000
    outer loop
      vertex 161.238693 126.178917 0.000000
      vertex 161.334137 126.190285 3.000000
      vertex 161.334137 126.190285 0.000000
    endloop
  endfacet
  facet normal -0.118269 0.992982 0.000000
    outer loop
      vertex 161.238693 126.178917 3.000000
      vertex 161.334137 126.190285 3.000000
      vertex 161.238693 126.178917 0.000000
    endloop
  endfacet
  facet normal -0.022301 0.999751 0.000000
    outer loop
      vertex 161.142242 126.176765 0.000000
      vertex 161.238693 126.178917 3.000000
      vertex 161.238693 126.178917 0.000000
    endloop
  endfacet
  facet normal -0.022301 0.999751 0.000000
    outer loop
      vertex 161.142242 126.176765 3.000000
      vertex 161.238693 126.178917 3.000000
      vertex 161.142242 126.176765 0.000000
    endloop
  endfacet
  facet normal 0.074622 0.997212 0.000000
    outer loop
      vertex 161.045486 126.184006 0.000000
      vertex 161.142242 126.176765 3.000000
      vertex 161.142242 126.176765 0.000000
    endloop
  endfacet
  facet normal 0.074622 0.997212 0.000000
    outer loop
      vertex 161.045486 126.184006 3.000000
      vertex 161.142242 126.176765 3.000000
      vertex 161.045486 126.184006 0.000000
    endloop
  endfacet
  facet normal 0.171854 0.985122 0.000000
    outer loop
      vertex 160.949097 126.200821 0.000000
      vertex 161.045486 126.184006 3.000000
      vertex 161.045486 126.184006 0.000000
    endloop
  endfacet
  facet normal 0.171854 0.985122 0.000000
    outer loop
      vertex 160.949097 126.200821 3.000000
      vertex 161.045486 126.184006 3.000000
      vertex 160.949097 126.200821 0.000000
    endloop
  endfacet
  facet normal 0.268646 0.963239 0.000000
    outer loop
      vertex 160.853790 126.227402 0.000000
      vertex 160.949097 126.200821 3.000000
      vertex 160.949097 126.200821 0.000000
    endloop
  endfacet
  facet normal 0.268646 0.963239 0.000000
    outer loop
      vertex 160.853790 126.227402 3.000000
      vertex 160.949097 126.200821 3.000000
      vertex 160.853790 126.227402 0.000000
    endloop
  endfacet
  facet normal 0.363612 0.931551 0.000000
    outer loop
      vertex 160.760223 126.263924 0.000000
      vertex 160.853790 126.227402 3.000000
      vertex 160.853790 126.227402 0.000000
    endloop
  endfacet
  facet normal 0.363612 0.931551 0.000000
    outer loop
      vertex 160.760223 126.263924 3.000000
      vertex 160.853790 126.227402 3.000000
      vertex 160.760223 126.263924 0.000000
    endloop
  endfacet
  facet normal 0.455660 0.890154 0.000000
    outer loop
      vertex 160.669098 126.310570 0.000000
      vertex 160.760223 126.263924 3.000000
      vertex 160.760223 126.263924 0.000000
    endloop
  endfacet
  facet normal 0.455660 0.890154 0.000000
    outer loop
      vertex 160.669098 126.310570 3.000000
      vertex 160.760223 126.263924 3.000000
      vertex 160.669098 126.310570 0.000000
    endloop
  endfacet
  facet normal -0.866025 0.500000 0.000000
    outer loop
      vertex 163.950409 129.993988 3.000000
      vertex 163.950409 129.993988 0.000000
      vertex 162.035110 126.676598 0.000000
    endloop
  endfacet
  facet normal -0.866025 0.500000 0.000000
    outer loop
      vertex 162.035110 126.676598 3.000000
      vertex 163.950409 129.993988 3.000000
      vertex 162.035110 126.676598 0.000000
    endloop
  endfacet
  facet normal 0.501055 0.865416 0.000000
    outer loop
      vertex 178.700302 122.035522 3.000000
      vertex 178.700302 122.035522 0.000000
      vertex 177.691559 122.619560 0.000000
    endloop
  endfacet
  facet normal 0.501055 0.865416 0.000000
    outer loop
      vertex 177.691559 122.619560 3.000000
      vertex 178.700302 122.035522 3.000000
      vertex 177.691559 122.619560 0.000000
    endloop
  endfacet
  facet normal 0.503356 0.864079 0.000000
    outer loop
      vertex 176.706894 123.193161 0.000000
      vertex 177.691559 122.619560 3.000000
      vertex 177.691559 122.619560 0.000000
    endloop
  endfacet
  facet normal 0.503356 0.864079 0.000000
    outer loop
      vertex 176.706894 123.193161 3.000000
      vertex 177.691559 122.619560 3.000000
      vertex 176.706894 123.193161 0.000000
    endloop
  endfacet
  facet normal 0.505950 0.862563 0.000000
    outer loop
      vertex 175.746231 123.756653 0.000000
      vertex 176.706894 123.193161 3.000000
      vertex 176.706894 123.193161 0.000000
    endloop
  endfacet
  facet normal 0.505950 0.862563 0.000000
    outer loop
      vertex 175.746231 123.756653 3.000000
      vertex 176.706894 123.193161 3.000000
      vertex 175.746231 123.756653 0.000000
    endloop
  endfacet
  facet normal 0.508837 0.860863 0.000000
    outer loop
      vertex 174.809448 124.310364 0.000000
      vertex 175.746231 123.756653 3.000000
      vertex 175.746231 123.756653 0.000000
    endloop
  endfacet
  facet normal 0.508837 0.860863 0.000000
    outer loop
      vertex 174.809448 124.310364 3.000000
      vertex 175.746231 123.756653 3.000000
      vertex 174.809448 124.310364 0.000000
    endloop
  endfacet
  facet normal 0.512039 0.858962 0.000000
    outer loop
      vertex 173.896439 124.854622 0.000000
      vertex 174.809448 124.310364 3.000000
      vertex 174.809448 124.310364 0.000000
    endloop
  endfacet
  facet normal 0.512039 0.858962 0.000000
    outer loop
      vertex 173.896439 124.854622 3.000000
      vertex 174.809448 124.310364 3.000000
      vertex 173.896439 124.854622 0.000000
    endloop
  endfacet
  facet normal 0.515572 0.856846 0.000000
    outer loop
      vertex 173.007095 125.389748 0.000000
      vertex 173.896439 124.854622 3.000000
      vertex 173.896439 124.854622 0.000000
    endloop
  endfacet
  facet normal 0.515572 0.856846 0.000000
    outer loop
      vertex 173.007095 125.389748 3.000000
      vertex 173.896439 124.854622 3.000000
      vertex 173.007095 125.389748 0.000000
    endloop
  endfacet
  facet normal 0.519459 0.854495 0.000000
    outer loop
      vertex 172.141312 125.916069 0.000000
      vertex 173.007095 125.389748 3.000000
      vertex 173.007095 125.389748 0.000000
    endloop
  endfacet
  facet normal 0.519459 0.854495 0.000000
    outer loop
      vertex 172.141312 125.916069 3.000000
      vertex 173.007095 125.389748 3.000000
      vertex 172.141312 125.916069 0.000000
    endloop
  endfacet
  facet normal 0.523722 0.851889 0.000000
    outer loop
      vertex 171.298981 126.433914 0.000000
      vertex 172.141312 125.916069 3.000000
      vertex 172.141312 125.916069 0.000000
    endloop
  endfacet
  facet normal 0.523722 0.851889 0.000000
    outer loop
      vertex 171.298981 126.433914 3.000000
      vertex 172.141312 125.916069 3.000000
      vertex 171.298981 126.433914 0.000000
    endloop
  endfacet
  facet normal 0.528381 0.849007 0.000000
    outer loop
      vertex 170.479996 126.943611 0.000000
      vertex 171.298981 126.433914 3.000000
      vertex 171.298981 126.433914 0.000000
    endloop
  endfacet
  facet normal 0.528381 0.849007 0.000000
    outer loop
      vertex 170.479996 126.943611 3.000000
      vertex 171.298981 126.433914 3.000000
      vertex 170.479996 126.943611 0.000000
    endloop
  endfacet
  facet normal 0.533463 0.845823 0.000000
    outer loop
      vertex 169.684265 127.445480 0.000000
      vertex 170.479996 126.943611 3.000000
      vertex 170.479996 126.943611 0.000000
    endloop
  endfacet
  facet normal 0.533463 0.845823 0.000000
    outer loop
      vertex 169.684265 127.445480 3.000000
      vertex 170.479996 126.943611 3.000000
      vertex 169.684265 127.445480 0.000000
    endloop
  endfacet
  facet normal 0.538974 0.842322 0.000000
    outer loop
      vertex 168.911652 127.939850 0.000000
      vertex 169.684265 127.445480 3.000000
      vertex 169.684265 127.445480 0.000000
    endloop
  endfacet
  facet normal 0.538974 0.842322 0.000000
    outer loop
      vertex 168.911652 127.939850 3.000000
      vertex 169.684265 127.445480 3.000000
      vertex 168.911652 127.939850 0.000000
    endloop
  endfacet
  facet normal 0.544961 0.838461 0.000000
    outer loop
      vertex 168.162064 128.427048 0.000000
      vertex 168.911652 127.939850 3.000000
      vertex 168.911652 127.939850 0.000000
    endloop
  endfacet
  facet normal 0.544961 0.838461 0.000000
    outer loop
      vertex 168.162064 128.427048 3.000000
      vertex 168.911652 127.939850 3.000000
      vertex 168.162064 128.427048 0.000000
    endloop
  endfacet
  facet normal 0.551446 0.834211 0.000000
    outer loop
      vertex 167.435410 128.907394 0.000000
      vertex 168.162064 128.427048 3.000000
      vertex 168.162064 128.427048 0.000000
    endloop
  endfacet
  facet normal 0.551446 0.834211 0.000000
    outer loop
      vertex 167.435410 128.907394 3.000000
      vertex 168.162064 128.427048 3.000000
      vertex 167.435410 128.907394 0.000000
    endloop
  endfacet
  facet normal 0.558454 0.829535 0.000000
    outer loop
      vertex 166.731552 129.381241 0.000000
      vertex 167.435410 128.907394 3.000000
      vertex 167.435410 128.907394 0.000000
    endloop
  endfacet
  facet normal 0.558454 0.829535 0.000000
    outer loop
      vertex 166.731552 129.381241 3.000000
      vertex 167.435410 128.907394 3.000000
      vertex 166.731552 129.381241 0.000000
    endloop
  endfacet
  facet normal 0.565998 0.824407 0.000000
    outer loop
      vertex 166.050415 129.848877 0.000000
      vertex 166.731552 129.381241 3.000000
      vertex 166.731552 129.381241 0.000000
    endloop
  endfacet
  facet normal 0.565998 0.824407 0.000000
    outer loop
      vertex 166.050415 129.848877 3.000000
      vertex 166.731552 129.381241 3.000000
      vertex 166.050415 129.848877 0.000000
    endloop
  endfacet
  facet normal 0.574108 0.818780 0.000000
    outer loop
      vertex 165.391861 130.310638 0.000000
      vertex 166.050415 129.848877 3.000000
      vertex 166.050415 129.848877 0.000000
    endloop
  endfacet
  facet normal 0.574108 0.818780 0.000000
    outer loop
      vertex 165.391861 130.310638 3.000000
      vertex 166.050415 129.848877 3.000000
      vertex 165.391861 130.310638 0.000000
    endloop
  endfacet
  facet normal 0.534009 0.845479 0.000000
    outer loop
      vertex 165.299744 130.368820 0.000000
      vertex 165.391861 130.310638 3.000000
      vertex 165.391861 130.310638 0.000000
    endloop
  endfacet
  facet normal 0.534009 0.845479 0.000000
    outer loop
      vertex 165.299744 130.368820 3.000000
      vertex 165.391861 130.310638 3.000000
      vertex 165.299744 130.368820 0.000000
    endloop
  endfacet
  facet normal 0.440384 0.897810 0.000000
    outer loop
      vertex 165.204086 130.415741 0.000000
      vertex 165.299744 130.368820 3.000000
      vertex 165.299744 130.368820 0.000000
    endloop
  endfacet
  facet normal 0.440384 0.897810 0.000000
    outer loop
      vertex 165.204086 130.415741 3.000000
      vertex 165.299744 130.368820 3.000000
      vertex 165.204086 130.415741 0.000000
    endloop
  endfacet
  facet normal 0.342422 0.939546 0.000000
    outer loop
      vertex 165.105698 130.451599 0.000000
      vertex 165.204086 130.415741 3.000000
      vertex 165.204086 130.415741 0.000000
    endloop
  endfacet
  facet normal 0.342422 0.939546 0.000000
    outer loop
      vertex 165.105698 130.451599 3.000000
      vertex 165.204086 130.415741 3.000000
      vertex 165.105698 130.451599 0.000000
    endloop
  endfacet
  facet normal 0.241494 0.970402 0.000000
    outer loop
      vertex 165.005386 130.476562 0.000000
      vertex 165.105698 130.451599 3.000000
      vertex 165.105698 130.451599 0.000000
    endloop
  endfacet
  facet normal 0.241494 0.970402 0.000000
    outer loop
      vertex 165.005386 130.476562 3.000000
      vertex 165.105698 130.451599 3.000000
      vertex 165.005386 130.476562 0.000000
    endloop
  endfacet
  facet normal 0.139335 0.990245 0.000000
    outer loop
      vertex 164.903992 130.490829 0.000000
      vertex 165.005386 130.476562 3.000000
      vertex 165.005386 130.476562 0.000000
    endloop
  endfacet
  facet normal 0.139335 0.990245 0.000000
    outer loop
      vertex 164.903992 130.490829 3.000000
      vertex 165.005386 130.476562 3.000000
      vertex 164.903992 130.490829 0.000000
    endloop
  endfacet
  facet normal 0.036895 0.999319 0.000000
    outer loop
      vertex 164.802322 130.494583 0.000000
      vertex 164.903992 130.490829 3.000000
      vertex 164.903992 130.490829 0.000000
    endloop
  endfacet
  facet normal 0.036895 0.999319 0.000000
    outer loop
      vertex 164.802322 130.494583 3.000000
      vertex 164.903992 130.490829 3.000000
      vertex 164.802322 130.494583 0.000000
    endloop
  endfacet
  facet normal -0.064890 0.997892 0.000000
    outer loop
      vertex 164.701187 130.488007 0.000000
      vertex 164.802322 130.494583 3.000000
      vertex 164.802322 130.494583 0.000000
    endloop
  endfacet
  facet normal -0.064890 0.997892 0.000000
    outer loop
      vertex 164.701187 130.488007 3.000000
      vertex 164.802322 130.494583 3.000000
      vertex 164.701187 130.488007 0.000000
    endloop
  endfacet
  facet normal -0.165451 0.986218 0.000000
    outer loop
      vertex 164.601410 130.471268 0.000000
      vertex 164.701187 130.488007 3.000000
      vertex 164.701187 130.488007 0.000000
    endloop
  endfacet
  facet normal -0.165451 0.986218 0.000000
    outer loop
      vertex 164.601410 130.471268 3.000000
      vertex 164.701187 130.488007 3.000000
      vertex 164.601410 130.471268 0.000000
    endloop
  endfacet
  facet normal -0.263908 0.964548 0.000000
    outer loop
      vertex 164.503815 130.444565 0.000000
      vertex 164.601410 130.471268 3.000000
      vertex 164.601410 130.471268 0.000000
    endloop
  endfacet
  facet normal -0.263908 0.964548 0.000000
    outer loop
      vertex 164.503815 130.444565 3.000000
      vertex 164.601410 130.471268 3.000000
      vertex 164.503815 130.444565 0.000000
    endloop
  endfacet
  facet normal -0.359866 0.933004 0.000000
    outer loop
      vertex 164.409225 130.408081 0.000000
      vertex 164.503815 130.444565 3.000000
      vertex 164.503815 130.444565 0.000000
    endloop
  endfacet
  facet normal -0.359866 0.933004 0.000000
    outer loop
      vertex 164.409225 130.408081 3.000000
      vertex 164.503815 130.444565 3.000000
      vertex 164.409225 130.408081 0.000000
    endloop
  endfacet
  facet normal -0.452661 0.891683 0.000000
    outer loop
      vertex 164.318451 130.362000 0.000000
      vertex 164.409225 130.408081 3.000000
      vertex 164.409225 130.408081 0.000000
    endloop
  endfacet
  facet normal -0.452661 0.891683 0.000000
    outer loop
      vertex 164.318451 130.362000 3.000000
      vertex 164.409225 130.408081 3.000000
      vertex 164.318451 130.362000 0.000000
    endloop
  endfacet
  facet normal -0.541540 0.840675 0.000000
    outer loop
      vertex 164.232300 130.306503 0.000000
      vertex 164.318451 130.362000 3.000000
      vertex 164.318451 130.362000 0.000000
    endloop
  endfacet
  facet normal -0.541540 0.840675 0.000000
    outer loop
      vertex 164.232300 130.306503 3.000000
      vertex 164.318451 130.362000 3.000000
      vertex 164.232300 130.306503 0.000000
    endloop
  endfacet
  facet normal -0.625828 0.779961 0.000000
    outer loop
      vertex 164.151611 130.241760 0.000000
      vertex 164.232300 130.306503 3.000000
      vertex 164.232300 130.306503 0.000000
    endloop
  endfacet
  facet normal -0.625828 0.779961 0.000000
    outer loop
      vertex 164.151611 130.241760 3.000000
      vertex 164.232300 130.306503 3.000000
      vertex 164.151611 130.241760 0.000000
    endloop
  endfacet
  facet normal -0.704043 0.710157 0.000000
    outer loop
      vertex 164.077179 130.167969 0.000000
      vertex 164.151611 130.241760 3.000000
      vertex 164.151611 130.241760 0.000000
    endloop
  endfacet
  facet normal -0.704043 0.710157 0.000000
    outer loop
      vertex 164.077179 130.167969 3.000000
      vertex 164.151611 130.241760 3.000000
      vertex 164.077179 130.167969 0.000000
    endloop
  endfacet
  facet normal -0.775238 0.631670 0.000000
    outer loop
      vertex 164.009842 130.085327 0.000000
      vertex 164.077179 130.167969 3.000000
      vertex 164.077179 130.167969 0.000000
    endloop
  endfacet
  facet normal -0.775238 0.631670 0.000000
    outer loop
      vertex 164.009842 130.085327 3.000000
      vertex 164.077179 130.167969 3.000000
      vertex 164.009842 130.085327 0.000000
    endloop
  endfacet
  facet normal -0.838181 0.545392 0.000000
    outer loop
      vertex 163.950409 129.993988 0.000000
      vertex 164.009842 130.085327 3.000000
      vertex 164.009842 130.085327 0.000000
    endloop
  endfacet
  facet normal -0.838181 0.545392 0.000000
    outer loop
      vertex 163.950409 129.993988 3.000000
      vertex 164.009842 130.085327 3.000000
      vertex 163.950409 129.993988 0.000000
    endloop
  endfacet
  facet normal 0.499995 0.866028 0.000000
    outer loop
      vertex 181.297104 120.536278 3.000000
      vertex 181.297104 120.536278 0.000000
      vertex 178.700302 122.035522 0.000000
    endloop
  endfacet
  facet normal 0.499995 0.866028 0.000000
    outer loop
      vertex 178.700302 122.035522 3.000000
      vertex 181.297104 120.536278 3.000000
      vertex 178.700302 122.035522 0.000000
    endloop
  endfacet
  facet normal 0.890325 -0.455326 0.000000
    outer loop
      vertex 182.395859 116.439316 3.000000
      vertex 182.395859 116.439316 0.000000
      vertex 182.535660 116.712677 0.000000
    endloop
  endfacet
  facet normal 0.890325 -0.455326 0.000000
    outer loop
      vertex 182.535660 116.712677 3.000000
      vertex 182.395859 116.439316 3.000000
      vertex 182.535660 116.712677 0.000000
    endloop
  endfacet
  facet normal 0.931693 -0.363245 0.000000
    outer loop
      vertex 182.645081 116.993332 0.000000
      vertex 182.535660 116.712677 3.000000
      vertex 182.535660 116.712677 0.000000
    endloop
  endfacet
  facet normal 0.931693 -0.363245 0.000000
    outer loop
      vertex 182.645081 116.993332 3.000000
      vertex 182.535660 116.712677 3.000000
      vertex 182.645081 116.993332 0.000000
    endloop
  endfacet
  facet normal 0.963355 -0.268230 0.000000
    outer loop
      vertex 182.724686 117.279236 0.000000
      vertex 182.645081 116.993332 3.000000
      vertex 182.645081 116.993332 0.000000
    endloop
  endfacet
  facet normal 0.963355 -0.268230 0.000000
    outer loop
      vertex 182.724686 117.279236 3.000000
      vertex 182.645081 116.993332 3.000000
      vertex 182.724686 117.279236 0.000000
    endloop
  endfacet
  facet normal 0.985175 -0.171554 0.000000
    outer loop
      vertex 182.775024 117.568314 0.000000
      vertex 182.724686 117.279236 3.000000
      vertex 182.724686 117.279236 0.000000
    endloop
  endfacet
  facet normal 0.985175 -0.171554 0.000000
    outer loop
      vertex 182.775024 117.568314 3.000000
      vertex 182.724686 117.279236 3.000000
      vertex 182.775024 117.568314 0.000000
    endloop
  endfacet
  facet normal 0.997236 -0.074299 0.000000
    outer loop
      vertex 182.796646 117.858521 0.000000
      vertex 182.775024 117.568314 3.000000
      vertex 182.775024 117.568314 0.000000
    endloop
  endfacet
  facet normal 0.997236 -0.074299 0.000000
    outer loop
      vertex 182.796646 117.858521 3.000000
      vertex 182.775024 117.568314 3.000000
      vertex 182.796646 117.858521 0.000000
    endloop
  endfacet
  facet normal 0.999744 0.022624 0.000000
    outer loop
      vertex 182.790100 118.147789 0.000000
      vertex 182.796646 117.858521 3.000000
      vertex 182.796646 117.858521 0.000000
    endloop
  endfacet
  facet normal 0.999744 0.022624 0.000000
    outer loop
      vertex 182.790100 118.147789 3.000000
      vertex 182.796646 117.858521 3.000000
      vertex 182.790100 118.147789 0.000000
    endloop
  endfacet
  facet normal 0.992960 0.118447 0.000000
    outer loop
      vertex 182.755951 118.434067 0.000000
      vertex 182.790100 118.147789 3.000000
      vertex 182.790100 118.147789 0.000000
    endloop
  endfacet
  facet normal 0.992960 0.118447 0.000000
    outer loop
      vertex 182.755951 118.434067 3.000000
      vertex 182.790100 118.147789 3.000000
      vertex 182.755951 118.434067 0.000000
    endloop
  endfacet
  facet normal 0.977116 0.212707 0.000000
    outer loop
      vertex 182.694733 118.715286 0.000000
      vertex 182.755951 118.434067 3.000000
      vertex 182.755951 118.434067 0.000000
    endloop
  endfacet
  facet normal 0.977116 0.212707 0.000000
    outer loop
      vertex 182.694733 118.715286 3.000000
      vertex 182.755951 118.434067 3.000000
      vertex 182.694733 118.715286 0.000000
    endloop
  endfacet
  facet normal 0.952419 0.304793 0.000000
    outer loop
      vertex 182.607010 118.989403 0.000000
      vertex 182.694733 118.715286 3.000000
      vertex 182.694733 118.715286 0.000000
    endloop
  endfacet
  facet normal 0.952419 0.304793 0.000000
    outer loop
      vertex 182.607010 118.989403 3.000000
      vertex 182.694733 118.715286 3.000000
      vertex 182.607010 118.989403 0.000000
    endloop
  endfacet
  facet normal 0.918986 0.394290 0.000000
    outer loop
      vertex 182.493332 119.254356 0.000000
      vertex 182.607010 118.989403 3.000000
      vertex 182.607010 118.989403 0.000000
    endloop
  endfacet
  facet normal 0.918986 0.394290 0.000000
    outer loop
      vertex 182.493332 119.254356 3.000000
      vertex 182.607010 118.989403 3.000000
      vertex 182.493332 119.254356 0.000000
    endloop
  endfacet
  facet normal 0.876914 0.480647 0.000000
    outer loop
      vertex 182.354263 119.508080 0.000000
      vertex 182.493332 119.254356 3.000000
      vertex 182.493332 119.254356 0.000000
    endloop
  endfacet
  facet normal 0.876914 0.480647 0.000000
    outer loop
      vertex 182.354263 119.508080 3.000000
      vertex 182.493332 119.254356 3.000000
      vertex 182.354263 119.508080 0.000000
    endloop
  endfacet
  facet normal 0.826221 0.563346 0.000000
    outer loop
      vertex 182.190323 119.748520 0.000000
      vertex 182.354263 119.508080 3.000000
      vertex 182.354263 119.508080 0.000000
    endloop
  endfacet
  facet normal 0.826221 0.563346 0.000000
    outer loop
      vertex 182.190323 119.748520 3.000000
      vertex 182.354263 119.508080 3.000000
      vertex 182.190323 119.748520 0.000000
    endloop
  endfacet
  facet normal 0.767129 0.641493 0.000000
    outer loop
      vertex 182.002090 119.973618 0.000000
      vertex 182.190323 119.748520 3.000000
      vertex 182.190323 119.748520 0.000000
    endloop
  endfacet
  facet normal 0.767129 0.641493 0.000000
    outer loop
      vertex 182.002090 119.973618 3.000000
      vertex 182.190323 119.748520 3.000000
      vertex 182.002090 119.973618 0.000000
    endloop
  endfacet
  facet normal 0.699859 0.714281 0.000000
    outer loop
      vertex 181.790115 120.181313 0.000000
      vertex 182.002090 119.973618 3.000000
      vertex 182.002090 119.973618 0.000000
    endloop
  endfacet
  facet normal 0.699859 0.714281 0.000000
    outer loop
      vertex 181.790115 120.181313 3.000000
      vertex 182.002090 119.973618 3.000000
      vertex 181.790115 120.181313 0.000000
    endloop
  endfacet
  facet normal 0.624883 0.780718 0.000000
    outer loop
      vertex 181.554932 120.369553 0.000000
      vertex 181.790115 120.181313 3.000000
      vertex 181.790115 120.181313 0.000000
    endloop
  endfacet
  facet normal 0.624883 0.780718 0.000000
    outer loop
      vertex 181.554932 120.369553 3.000000
      vertex 181.790115 120.181313 3.000000
      vertex 181.554932 120.369553 0.000000
    endloop
  endfacet
  facet normal 0.543011 0.839725 0.000000
    outer loop
      vertex 181.297104 120.536278 0.000000
      vertex 181.554932 120.369553 3.000000
      vertex 181.554932 120.369553 0.000000
    endloop
  endfacet
  facet normal 0.543011 0.839725 0.000000
    outer loop
      vertex 181.297104 120.536278 3.000000
      vertex 181.554932 120.369553 3.000000
      vertex 181.297104 120.536278 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 152.643661 149.405212 3.000000
      vertex 114.551727 164.135117 3.000000
      vertex 114.554306 164.084000 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 114.554306 152.834106 3.000000
      vertex 152.643661 149.405212 3.000000
      vertex 114.554306 164.084000 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 114.551727 152.782990 3.000000
      vertex 152.643661 149.405212 3.000000
      vertex 114.554306 152.834106 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 152.643661 149.405212 3.000000
      vertex 114.551727 152.782990 3.000000
      vertex 114.544151 152.733337 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 114.531830 152.685425 3.000000
      vertex 152.643661 149.405212 3.000000
      vertex 114.544151 152.733337 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 114.515015 152.639481 3.000000
      vertex 152.643661 149.405212 3.000000
      vertex 114.531830 152.685425 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 152.643661 149.405212 3.000000
      vertex 114.515015 152.639481 3.000000
      vertex 114.493958 152.595779 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 114.468910 152.554550 3.000000
      vertex 152.643661 149.405212 3.000000
      vertex 114.493958 152.595779 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 114.440132 152.516068 3.000000
      vertex 152.643661 149.405212 3.000000
      vertex 114.468910 152.554550 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 152.643661 149.405212 3.000000
      vertex 114.440132 152.516068 3.000000
      vertex 114.407860 152.480560 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 114.372353 152.448288 3.000000
      vertex 152.643661 149.405212 3.000000
      vertex 114.407860 152.480560 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 114.333862 152.419495 3.000000
      vertex 152.643661 149.405212 3.000000
      vertex 114.372353 152.448288 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 152.643661 149.405212 3.000000
      vertex 114.333862 152.419495 3.000000
      vertex 114.292633 152.394455 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 114.248932 152.373398 3.000000
      vertex 152.643661 149.405212 3.000000
      vertex 114.292633 152.394455 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 114.202988 152.356583 3.000000
      vertex 152.643661 149.405212 3.000000
      vertex 114.248932 152.373398 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 152.643661 149.405212 3.000000
      vertex 114.202988 152.356583 3.000000
      vertex 114.155075 152.344269 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 114.105431 152.336685 3.000000
      vertex 152.643661 149.405212 3.000000
      vertex 114.155075 152.344269 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 114.054306 152.334106 3.000000
      vertex 152.643661 149.405212 3.000000
      vertex 114.105431 152.336685 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 152.643661 149.405212 3.000000
      vertex 114.054306 152.334106 3.000000
      vertex 109.054306 152.334106 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 152.536316 149.399796 3.000000
      vertex 152.643661 149.405212 3.000000
      vertex 109.054306 152.334106 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 152.432053 149.383881 3.000000
      vertex 152.536316 149.399796 3.000000
      vertex 109.054306 152.334106 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 152.331436 149.358002 3.000000
      vertex 152.432053 149.383881 3.000000
      vertex 109.054306 152.334106 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 152.234955 149.322693 3.000000
      vertex 152.331436 149.358002 3.000000
      vertex 109.054306 152.334106 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 152.143173 149.278488 3.000000
      vertex 152.234955 149.322693 3.000000
      vertex 109.054306 152.334106 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 152.056610 149.225891 3.000000
      vertex 152.143173 149.278488 3.000000
      vertex 109.054306 152.334106 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 151.975769 149.165451 3.000000
      vertex 152.056610 149.225891 3.000000
      vertex 109.054306 152.334106 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 151.901199 149.097672 3.000000
      vertex 151.975769 149.165451 3.000000
      vertex 109.054306 152.334106 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 151.833435 149.023117 3.000000
      vertex 151.901199 149.097672 3.000000
      vertex 109.054306 152.334106 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 151.772995 148.942276 3.000000
      vertex 151.833435 149.023117 3.000000
      vertex 109.054306 152.334106 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 151.720398 148.855713 3.000000
      vertex 151.772995 148.942276 3.000000
      vertex 109.054306 152.334106 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 151.676178 148.763916 3.000000
      vertex 151.720398 148.855713 3.000000
      vertex 109.054306 152.334106 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 151.640869 148.667450 3.000000
      vertex 151.676178 148.763916 3.000000
      vertex 109.054306 152.334106 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 151.615005 148.566818 3.000000
      vertex 151.640869 148.667450 3.000000
      vertex 109.054306 152.334106 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 151.599091 148.462570 3.000000
      vertex 151.615005 148.566818 3.000000
      vertex 109.054306 152.334106 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 151.593674 148.355209 3.000000
      vertex 151.599091 148.462570 3.000000
      vertex 109.054306 152.334106 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.599091 148.247864 3.000000
      vertex 151.593674 148.355209 3.000000
      vertex 109.054306 152.334106 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.615005 148.143600 3.000000
      vertex 151.599091 148.247864 3.000000
      vertex 109.054306 152.334106 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.640869 148.042969 3.000000
      vertex 151.615005 148.143600 3.000000
      vertex 109.054306 152.334106 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.676178 147.946503 3.000000
      vertex 151.640869 148.042969 3.000000
      vertex 109.054306 152.334106 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 150.811142 133.153976 3.000000
      vertex 151.676178 147.946503 3.000000
      vertex 109.054306 152.334106 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.720398 147.854721 3.000000
      vertex 151.676178 147.946503 3.000000
      vertex 150.811142 133.153976 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.772995 147.768143 3.000000
      vertex 151.720398 147.854721 3.000000
      vertex 150.811142 133.153976 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.833435 147.687317 3.000000
      vertex 151.772995 147.768143 3.000000
      vertex 150.811142 133.153976 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.901199 147.612747 3.000000
      vertex 151.833435 147.687317 3.000000
      vertex 150.811142 133.153976 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.975769 147.544983 3.000000
      vertex 151.901199 147.612747 3.000000
      vertex 150.811142 133.153976 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 155.444077 141.223419 3.000000
      vertex 151.975769 147.544983 3.000000
      vertex 150.811142 133.153976 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 152.056610 147.484543 3.000000
      vertex 151.975769 147.544983 3.000000
      vertex 155.444077 141.223419 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 152.143173 147.431946 3.000000
      vertex 152.056610 147.484543 3.000000
      vertex 155.444077 141.223419 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 152.234955 147.387726 3.000000
      vertex 152.143173 147.431946 3.000000
      vertex 155.444077 141.223419 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 155.656876 142.925613 3.000000
      vertex 152.234955 147.387726 3.000000
      vertex 155.444077 141.223419 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 152.331436 147.352417 3.000000
      vertex 152.234955 147.387726 3.000000
      vertex 155.656876 142.925613 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 155.643661 143.422668 3.000000
      vertex 152.331436 147.352417 3.000000
      vertex 155.656876 142.925613 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 152.432053 147.326553 3.000000
      vertex 152.331436 147.352417 3.000000
      vertex 155.643661 143.422668 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 152.536316 147.310638 3.000000
      vertex 152.432053 147.326553 3.000000
      vertex 155.643661 143.422668 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 152.643661 147.305206 3.000000
      vertex 152.536316 147.310638 3.000000
      vertex 155.643661 143.422668 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 152.751022 147.310638 3.000000
      vertex 152.643661 147.305206 3.000000
      vertex 155.643661 143.422668 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 152.855286 147.326553 3.000000
      vertex 152.751022 147.310638 3.000000
      vertex 155.643661 143.422668 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 152.955902 147.352417 3.000000
      vertex 152.855286 147.326553 3.000000
      vertex 155.643661 143.422668 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 153.052383 147.387726 3.000000
      vertex 152.955902 147.352417 3.000000
      vertex 155.643661 143.422668 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 153.144165 147.431946 3.000000
      vertex 153.052383 147.387726 3.000000
      vertex 155.643661 143.422668 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 153.230728 147.484543 3.000000
      vertex 153.144165 147.431946 3.000000
      vertex 155.643661 143.422668 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 153.311569 147.544983 3.000000
      vertex 153.230728 147.484543 3.000000
      vertex 155.643661 143.422668 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 153.386124 147.612747 3.000000
      vertex 153.311569 147.544983 3.000000
      vertex 155.643661 143.422668 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 153.453903 147.687317 3.000000
      vertex 153.386124 147.612747 3.000000
      vertex 155.643661 143.422668 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 153.514343 147.768143 3.000000
      vertex 153.453903 147.687317 3.000000
      vertex 155.643661 143.422668 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 153.566940 147.854721 3.000000
      vertex 153.514343 147.768143 3.000000
      vertex 155.643661 143.422668 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 153.611160 147.946503 3.000000
      vertex 153.566940 147.854721 3.000000
      vertex 155.643661 143.422668 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 153.646469 148.042969 3.000000
      vertex 153.611160 147.946503 3.000000
      vertex 155.643661 143.422668 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 153.672333 148.143600 3.000000
      vertex 153.646469 148.042969 3.000000
      vertex 155.643661 143.422668 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 153.688248 148.247864 3.000000
      vertex 153.672333 148.143600 3.000000
      vertex 155.643661 143.422668 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 153.693665 148.355209 3.000000
      vertex 153.688248 148.247864 3.000000
      vertex 155.643661 143.422668 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 153.688248 148.462570 3.000000
      vertex 153.693665 148.355209 3.000000
      vertex 155.643661 143.422668 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 153.672333 148.566818 3.000000
      vertex 153.688248 148.462570 3.000000
      vertex 155.643661 143.422668 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 153.646469 148.667450 3.000000
      vertex 153.672333 148.566818 3.000000
      vertex 155.643661 143.422668 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 155.643661 192.834167 3.000000
      vertex 153.646469 148.667450 3.000000
      vertex 155.643661 143.422668 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 153.611160 148.763916 3.000000
      vertex 153.646469 148.667450 3.000000
      vertex 155.643661 192.834167 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 153.566940 148.855713 3.000000
      vertex 153.611160 148.763916 3.000000
      vertex 155.643661 192.834167 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 153.514343 148.942276 3.000000
      vertex 153.566940 148.855713 3.000000
      vertex 155.643661 192.834167 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 153.453903 149.023117 3.000000
      vertex 153.514343 148.942276 3.000000
      vertex 155.643661 192.834167 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 153.386124 149.097672 3.000000
      vertex 153.453903 149.023117 3.000000
      vertex 155.643661 192.834167 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 153.311569 149.165451 3.000000
      vertex 153.386124 149.097672 3.000000
      vertex 155.643661 192.834167 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 153.230728 149.225891 3.000000
      vertex 153.311569 149.165451 3.000000
      vertex 155.643661 192.834167 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 153.144165 149.278488 3.000000
      vertex 153.230728 149.225891 3.000000
      vertex 155.643661 192.834167 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 153.052383 149.322693 3.000000
      vertex 153.144165 149.278488 3.000000
      vertex 155.643661 192.834167 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 152.611404 191.618423 3.000000
      vertex 153.052383 149.322693 3.000000
      vertex 155.643661 192.834167 3.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 152.955902 149.358002 3.000000
      vertex 153.052383 149.322693 3.000000
      vertex 152.611404 191.618423 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 152.514938 191.583115 3.000000
      vertex 152.955902 149.358002 3.000000
      vertex 152.611404 191.618423 3.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 152.855286 149.383881 3.000000
      vertex 152.955902 149.358002 3.000000
      vertex 152.514938 191.583115 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 152.414307 191.557236 3.000000
      vertex 152.855286 149.383881 3.000000
      vertex 152.514938 191.583115 3.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 152.751022 149.399796 3.000000
      vertex 152.855286 149.383881 3.000000
      vertex 152.414307 191.557236 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 152.310059 191.541321 3.000000
      vertex 152.751022 149.399796 3.000000
      vertex 152.414307 191.557236 3.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 152.643661 149.405212 3.000000
      vertex 152.751022 149.399796 3.000000
      vertex 152.310059 191.541321 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 152.202698 191.535904 3.000000
      vertex 152.643661 149.405212 3.000000
      vertex 152.310059 191.541321 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 114.531830 164.232681 3.000000
      vertex 152.643661 149.405212 3.000000
      vertex 152.202698 191.535904 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 114.515015 164.278625 3.000000
      vertex 114.531830 164.232681 3.000000
      vertex 152.202698 191.535904 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 114.493958 164.322327 3.000000
      vertex 114.515015 164.278625 3.000000
      vertex 152.202698 191.535904 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 114.468910 164.363556 3.000000
      vertex 114.493958 164.322327 3.000000
      vertex 152.202698 191.535904 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 114.440132 164.402054 3.000000
      vertex 114.468910 164.363556 3.000000
      vertex 152.202698 191.535904 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 114.407860 164.437561 3.000000
      vertex 114.440132 164.402054 3.000000
      vertex 152.202698 191.535904 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 114.372353 164.469833 3.000000
      vertex 114.407860 164.437561 3.000000
      vertex 152.202698 191.535904 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 114.333862 164.498611 3.000000
      vertex 114.372353 164.469833 3.000000
      vertex 152.202698 191.535904 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 114.292633 164.523651 3.000000
      vertex 114.333862 164.498611 3.000000
      vertex 152.202698 191.535904 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 114.248932 164.544708 3.000000
      vertex 114.292633 164.523651 3.000000
      vertex 152.202698 191.535904 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 114.202988 164.561523 3.000000
      vertex 114.248932 164.544708 3.000000
      vertex 152.202698 191.535904 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 114.155075 164.573837 3.000000
      vertex 114.202988 164.561523 3.000000
      vertex 152.202698 191.535904 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 114.105431 164.581421 3.000000
      vertex 114.155075 164.573837 3.000000
      vertex 152.202698 191.535904 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 114.054306 164.584000 3.000000
      vertex 114.105431 164.581421 3.000000
      vertex 152.202698 191.535904 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 33.922680 191.199615 3.000000
      vertex 114.054306 164.584000 3.000000
      vertex 152.202698 191.535904 3.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 33.975273 191.113052 3.000000
      vertex 114.054306 164.584000 3.000000
      vertex 33.922680 191.199615 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 109.054306 152.334106 3.000000
      vertex 109.003181 152.336685 3.000000
      vertex 93.206390 106.331635 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 150.712769 132.396088 3.000000
      vertex 109.054306 152.334106 3.000000
      vertex 93.206390 106.331635 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 150.692291 132.489685 3.000000
      vertex 109.054306 152.334106 3.000000
      vertex 150.712769 132.396088 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 93.206390 106.331635 3.000000
      vertex 109.003181 152.336685 3.000000
      vertex 108.953537 152.344269 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 108.905624 152.356583 3.000000
      vertex 93.206390 106.331635 3.000000
      vertex 108.953537 152.344269 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 92.919014 106.405525 3.000000
      vertex 93.206390 106.331635 3.000000
      vertex 108.905624 152.356583 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 108.859680 152.373398 3.000000
      vertex 92.919014 106.405525 3.000000
      vertex 108.905624 152.356583 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 92.621277 106.450966 3.000000
      vertex 92.919014 106.405525 3.000000
      vertex 108.859680 152.373398 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 108.815979 152.394455 3.000000
      vertex 92.621277 106.450966 3.000000
      vertex 108.859680 152.373398 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 92.314682 106.466446 3.000000
      vertex 92.621277 106.450966 3.000000
      vertex 108.815979 152.394455 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 108.774750 152.419495 3.000000
      vertex 92.314682 106.466446 3.000000
      vertex 108.815979 152.394455 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 108.736259 152.448288 3.000000
      vertex 92.314682 106.466446 3.000000
      vertex 108.774750 152.419495 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 92.314682 106.466446 3.000000
      vertex 108.736259 152.448288 3.000000
      vertex 108.700752 152.480560 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 108.668480 152.516068 3.000000
      vertex 92.314682 106.466446 3.000000
      vertex 108.700752 152.480560 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 108.639694 152.554550 3.000000
      vertex 92.314682 106.466446 3.000000
      vertex 108.668480 152.516068 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 92.314682 106.466446 3.000000
      vertex 108.639694 152.554550 3.000000
      vertex 108.614655 152.595779 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 108.593597 152.639481 3.000000
      vertex 92.314682 106.466446 3.000000
      vertex 108.614655 152.595779 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 33.462051 111.362228 3.000000
      vertex 92.314682 106.466446 3.000000
      vertex 108.593597 152.639481 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 108.576782 152.685425 3.000000
      vertex 33.462051 111.362228 3.000000
      vertex 108.593597 152.639481 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 108.564461 152.733337 3.000000
      vertex 33.462051 111.362228 3.000000
      vertex 108.576782 152.685425 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 33.462051 111.362228 3.000000
      vertex 108.564461 152.733337 3.000000
      vertex 108.556885 152.782990 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 33.052002 189.562546 3.000000
      vertex 33.462051 111.362228 3.000000
      vertex 108.556885 152.782990 3.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 33.357796 111.378136 3.000000
      vertex 33.462051 111.362228 3.000000
      vertex 33.052002 189.562546 3.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 33.250439 111.383560 3.000000
      vertex 33.357796 111.378136 3.000000
      vertex 33.052002 189.562546 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 33.143082 111.378136 3.000000
      vertex 33.250439 111.383560 3.000000
      vertex 33.052002 189.562546 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.944645 189.567978 3.000000
      vertex 33.143082 111.378136 3.000000
      vertex 33.052002 189.562546 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 33.038826 111.362228 3.000000
      vertex 33.143082 111.378136 3.000000
      vertex 32.944645 189.567978 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.840389 189.583878 3.000000
      vertex 33.038826 111.362228 3.000000
      vertex 32.944645 189.567978 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 32.938202 111.336357 3.000000
      vertex 33.038826 111.362228 3.000000
      vertex 32.840389 189.583878 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.739765 189.609756 3.000000
      vertex 32.938202 111.336357 3.000000
      vertex 32.840389 189.583878 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 32.841732 111.301048 3.000000
      vertex 32.938202 111.336357 3.000000
      vertex 32.739765 189.609756 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.643295 189.645065 3.000000
      vertex 32.841732 111.301048 3.000000
      vertex 32.739765 189.609756 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 29.343874 190.965912 3.000000
      vertex 32.841732 111.301048 3.000000
      vertex 32.643295 189.645065 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.551510 189.689285 3.000000
      vertex 29.343874 190.965912 3.000000
      vertex 32.643295 189.645065 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.464939 189.741882 3.000000
      vertex 29.343874 190.965912 3.000000
      vertex 32.551510 189.689285 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 33.052002 189.562546 3.000000
      vertex 108.556885 152.782990 3.000000
      vertex 108.554306 152.834106 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 108.554306 164.084000 3.000000
      vertex 33.052002 189.562546 3.000000
      vertex 108.554306 152.834106 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 108.556885 164.135117 3.000000
      vertex 33.052002 189.562546 3.000000
      vertex 108.554306 164.084000 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 33.052002 189.562546 3.000000
      vertex 108.556885 164.135117 3.000000
      vertex 108.564461 164.184769 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 108.576782 164.232681 3.000000
      vertex 33.052002 189.562546 3.000000
      vertex 108.564461 164.184769 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 108.593597 164.278625 3.000000
      vertex 33.052002 189.562546 3.000000
      vertex 108.576782 164.232681 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 33.052002 189.562546 3.000000
      vertex 108.593597 164.278625 3.000000
      vertex 108.614655 164.322327 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 108.639694 164.363556 3.000000
      vertex 33.052002 189.562546 3.000000
      vertex 108.614655 164.322327 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 108.668480 164.402054 3.000000
      vertex 33.052002 189.562546 3.000000
      vertex 108.639694 164.363556 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 33.052002 189.562546 3.000000
      vertex 108.668480 164.402054 3.000000
      vertex 108.700752 164.437561 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 108.736259 164.469833 3.000000
      vertex 33.052002 189.562546 3.000000
      vertex 108.700752 164.437561 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 108.774750 164.498611 3.000000
      vertex 33.052002 189.562546 3.000000
      vertex 108.736259 164.469833 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 33.052002 189.562546 3.000000
      vertex 108.774750 164.498611 3.000000
      vertex 108.815979 164.523651 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 108.859680 164.544708 3.000000
      vertex 33.052002 189.562546 3.000000
      vertex 108.815979 164.523651 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 108.905624 164.561523 3.000000
      vertex 33.052002 189.562546 3.000000
      vertex 108.859680 164.544708 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 33.052002 189.562546 3.000000
      vertex 108.905624 164.561523 3.000000
      vertex 108.953537 164.573837 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 109.003181 164.581421 3.000000
      vertex 33.052002 189.562546 3.000000
      vertex 108.953537 164.573837 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 109.054306 164.584000 3.000000
      vertex 33.052002 189.562546 3.000000
      vertex 109.003181 164.581421 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 33.052002 189.562546 3.000000
      vertex 109.054306 164.584000 3.000000
      vertex 114.054306 164.584000 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 33.159359 189.567978 3.000000
      vertex 33.052002 189.562546 3.000000
      vertex 114.054306 164.584000 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 33.263615 189.583878 3.000000
      vertex 33.159359 189.567978 3.000000
      vertex 114.054306 164.584000 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 33.364239 189.609756 3.000000
      vertex 33.263615 189.583878 3.000000
      vertex 114.054306 164.584000 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 33.460709 189.645065 3.000000
      vertex 33.364239 189.609756 3.000000
      vertex 114.054306 164.584000 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 33.552494 189.689285 3.000000
      vertex 33.460709 189.645065 3.000000
      vertex 114.054306 164.584000 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 33.639069 189.741882 3.000000
      vertex 33.552494 189.689285 3.000000
      vertex 114.054306 164.584000 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 33.719898 189.802322 3.000000
      vertex 33.639069 189.741882 3.000000
      vertex 114.054306 164.584000 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 33.794464 189.870087 3.000000
      vertex 33.719898 189.802322 3.000000
      vertex 114.054306 164.584000 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 33.862232 189.944656 3.000000
      vertex 33.794464 189.870087 3.000000
      vertex 114.054306 164.584000 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 33.922680 190.025482 3.000000
      vertex 33.862232 189.944656 3.000000
      vertex 114.054306 164.584000 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 33.975273 190.112061 3.000000
      vertex 33.922680 190.025482 3.000000
      vertex 114.054306 164.584000 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 34.019489 190.203842 3.000000
      vertex 33.975273 190.112061 3.000000
      vertex 114.054306 164.584000 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 34.054798 190.300308 3.000000
      vertex 34.019489 190.203842 3.000000
      vertex 114.054306 164.584000 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 34.080669 190.400940 3.000000
      vertex 34.054798 190.300308 3.000000
      vertex 114.054306 164.584000 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 34.096581 190.505203 3.000000
      vertex 34.080669 190.400940 3.000000
      vertex 114.054306 164.584000 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 34.102001 190.612549 3.000000
      vertex 34.096581 190.505203 3.000000
      vertex 114.054306 164.584000 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 34.096581 190.719910 3.000000
      vertex 34.102001 190.612549 3.000000
      vertex 114.054306 164.584000 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 34.080669 190.824158 3.000000
      vertex 34.096581 190.719910 3.000000
      vertex 114.054306 164.584000 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 34.054798 190.924789 3.000000
      vertex 34.080669 190.824158 3.000000
      vertex 114.054306 164.584000 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 34.019489 191.021255 3.000000
      vertex 34.054798 190.924789 3.000000
      vertex 114.054306 164.584000 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 33.975273 191.113052 3.000000
      vertex 34.019489 191.021255 3.000000
      vertex 114.054306 164.584000 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 152.643661 149.405212 3.000000
      vertex 114.531830 164.232681 3.000000
      vertex 114.544151 164.184769 3.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 114.551727 164.135117 3.000000
      vertex 152.643661 149.405212 3.000000
      vertex 114.544151 164.184769 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 29.343874 190.965912 3.000000
      vertex 32.464939 189.741882 3.000000
      vertex 32.384106 189.802322 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.309540 189.870087 3.000000
      vertex 29.343874 190.965912 3.000000
      vertex 32.384106 189.802322 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.241772 189.944656 3.000000
      vertex 29.343874 190.965912 3.000000
      vertex 32.309540 189.870087 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 29.343874 190.965912 3.000000
      vertex 32.241772 189.944656 3.000000
      vertex 32.181324 190.025482 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.128731 190.112061 3.000000
      vertex 29.343874 190.965912 3.000000
      vertex 32.181324 190.025482 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.084518 190.203842 3.000000
      vertex 29.343874 190.965912 3.000000
      vertex 32.128731 190.112061 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 29.343874 190.965912 3.000000
      vertex 32.084518 190.203842 3.000000
      vertex 32.049210 190.300308 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.023335 190.400940 3.000000
      vertex 29.343874 190.965912 3.000000
      vertex 32.049210 190.300308 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.007423 190.505203 3.000000
      vertex 29.343874 190.965912 3.000000
      vertex 32.023335 190.400940 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 29.343874 190.965912 3.000000
      vertex 32.007423 190.505203 3.000000
      vertex 32.002003 190.612549 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.007423 190.719910 3.000000
      vertex 29.343874 190.965912 3.000000
      vertex 32.002003 190.612549 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.023335 190.824158 3.000000
      vertex 29.343874 190.965912 3.000000
      vertex 32.007423 190.719910 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 29.354418 191.218140 3.000000
      vertex 29.343874 190.965912 3.000000
      vertex 32.023335 190.824158 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.049210 190.924789 3.000000
      vertex 29.354418 191.218140 3.000000
      vertex 32.023335 190.824158 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 29.385550 191.465424 3.000000
      vertex 29.354418 191.218140 3.000000
      vertex 32.049210 190.924789 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.084518 191.021255 3.000000
      vertex 29.385550 191.465424 3.000000
      vertex 32.049210 190.924789 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 29.506590 191.941299 3.000000
      vertex 29.385550 191.465424 3.000000
      vertex 32.084518 191.021255 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.128731 191.113052 3.000000
      vertex 29.506590 191.941299 3.000000
      vertex 32.084518 191.021255 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 29.701006 192.385727 3.000000
      vertex 29.506590 191.941299 3.000000
      vertex 32.128731 191.113052 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.181324 191.199615 3.000000
      vertex 29.701006 192.385727 3.000000
      vertex 32.128731 191.113052 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.241772 191.280457 3.000000
      vertex 29.701006 192.385727 3.000000
      vertex 32.181324 191.199615 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 29.962812 192.790894 3.000000
      vertex 29.701006 192.385727 3.000000
      vertex 32.241772 191.280457 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.309540 191.355011 3.000000
      vertex 29.962812 192.790894 3.000000
      vertex 32.241772 191.280457 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 30.286024 193.149002 3.000000
      vertex 29.962812 192.790894 3.000000
      vertex 32.309540 191.355011 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.384106 191.422791 3.000000
      vertex 30.286024 193.149002 3.000000
      vertex 32.309540 191.355011 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 30.664656 193.452225 3.000000
      vertex 30.286024 193.149002 3.000000
      vertex 32.384106 191.422791 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.464939 191.483231 3.000000
      vertex 30.664656 193.452225 3.000000
      vertex 32.384106 191.422791 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 31.092722 193.692780 3.000000
      vertex 30.664656 193.452225 3.000000
      vertex 32.464939 191.483231 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.551510 191.535828 3.000000
      vertex 31.092722 193.692780 3.000000
      vertex 32.464939 191.483231 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 31.323421 193.787109 3.000000
      vertex 31.092722 193.692780 3.000000
      vertex 32.551510 191.535828 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.643295 191.580032 3.000000
      vertex 31.323421 193.787109 3.000000
      vertex 32.551510 191.535828 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 31.564236 193.862839 3.000000
      vertex 31.323421 193.787109 3.000000
      vertex 32.643295 191.580032 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.739765 191.615341 3.000000
      vertex 31.564236 193.862839 3.000000
      vertex 32.643295 191.580032 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.840389 191.641220 3.000000
      vertex 31.564236 193.862839 3.000000
      vertex 32.739765 191.615341 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 31.564236 193.862839 3.000000
      vertex 32.840389 191.641220 3.000000
      vertex 32.944645 191.657135 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 33.052002 191.662552 3.000000
      vertex 31.564236 193.862839 3.000000
      vertex 32.944645 191.657135 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 33.784603 194.460388 3.000000
      vertex 31.564236 193.862839 3.000000
      vertex 33.052002 191.662552 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 36.521648 195.189407 3.000000
      vertex 33.784603 194.460388 3.000000
      vertex 33.052002 191.662552 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 39.226933 195.894669 3.000000
      vertex 36.521648 195.189407 3.000000
      vertex 33.052002 191.662552 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 41.900700 196.576218 3.000000
      vertex 39.226933 195.894669 3.000000
      vertex 33.052002 191.662552 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 44.543201 197.234085 3.000000
      vertex 41.900700 196.576218 3.000000
      vertex 33.052002 191.662552 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 47.154690 197.868317 3.000000
      vertex 44.543201 197.234085 3.000000
      vertex 33.052002 191.662552 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 49.735413 198.478958 3.000000
      vertex 47.154690 197.868317 3.000000
      vertex 33.052002 191.662552 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 52.285622 199.066055 3.000000
      vertex 49.735413 198.478958 3.000000
      vertex 33.052002 191.662552 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 54.805565 199.629623 3.000000
      vertex 52.285622 199.066055 3.000000
      vertex 33.052002 191.662552 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 57.295494 200.169708 3.000000
      vertex 54.805565 199.629623 3.000000
      vertex 33.052002 191.662552 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 59.755661 200.686371 3.000000
      vertex 57.295494 200.169708 3.000000
      vertex 33.052002 191.662552 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.702209 191.662628 3.000000
      vertex 59.755661 200.686371 3.000000
      vertex 33.052002 191.662552 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 124.013397 201.063171 3.000000
      vertex 59.755661 200.686371 3.000000
      vertex 151.702209 191.662628 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.615631 191.715225 3.000000
      vertex 124.013397 201.063171 3.000000
      vertex 151.702209 191.662628 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.534805 191.775665 3.000000
      vertex 124.013397 201.063171 3.000000
      vertex 151.615631 191.715225 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.702209 191.662628 3.000000
      vertex 33.052002 191.662552 3.000000
      vertex 33.159359 191.657135 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 33.263615 191.641220 3.000000
      vertex 151.702209 191.662628 3.000000
      vertex 33.159359 191.657135 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 33.364239 191.615341 3.000000
      vertex 151.702209 191.662628 3.000000
      vertex 33.263615 191.641220 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.702209 191.662628 3.000000
      vertex 33.364239 191.615341 3.000000
      vertex 33.460709 191.580032 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 33.552494 191.535828 3.000000
      vertex 151.702209 191.662628 3.000000
      vertex 33.460709 191.580032 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.793991 191.618423 3.000000
      vertex 151.702209 191.662628 3.000000
      vertex 33.552494 191.535828 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.890457 191.583115 3.000000
      vertex 151.793991 191.618423 3.000000
      vertex 33.552494 191.535828 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.991089 191.557236 3.000000
      vertex 151.890457 191.583115 3.000000
      vertex 33.552494 191.535828 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 152.095337 191.541321 3.000000
      vertex 151.991089 191.557236 3.000000
      vertex 33.552494 191.535828 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 152.202698 191.535904 3.000000
      vertex 152.095337 191.541321 3.000000
      vertex 33.552494 191.535828 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 33.639069 191.483231 3.000000
      vertex 152.202698 191.535904 3.000000
      vertex 33.552494 191.535828 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 33.719898 191.422791 3.000000
      vertex 152.202698 191.535904 3.000000
      vertex 33.639069 191.483231 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 152.202698 191.535904 3.000000
      vertex 33.719898 191.422791 3.000000
      vertex 33.794464 191.355011 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 33.862232 191.280457 3.000000
      vertex 152.202698 191.535904 3.000000
      vertex 33.794464 191.355011 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 33.922680 191.199615 3.000000
      vertex 152.202698 191.535904 3.000000
      vertex 33.862232 191.280457 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 169.033630 124.989052 3.000000
      vertex 169.028214 124.881699 3.000000
      vertex 172.141312 125.916069 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 171.298981 126.433914 3.000000
      vertex 169.033630 124.989052 3.000000
      vertex 172.141312 125.916069 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 169.028214 125.096405 3.000000
      vertex 169.033630 124.989052 3.000000
      vertex 171.298981 126.433914 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 169.012299 125.200661 3.000000
      vertex 169.028214 125.096405 3.000000
      vertex 171.298981 126.433914 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 168.986420 125.301292 3.000000
      vertex 169.012299 125.200661 3.000000
      vertex 171.298981 126.433914 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 168.951111 125.397758 3.000000
      vertex 168.986420 125.301292 3.000000
      vertex 171.298981 126.433914 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 170.479996 126.943611 3.000000
      vertex 168.951111 125.397758 3.000000
      vertex 171.298981 126.433914 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 168.906906 125.489548 3.000000
      vertex 168.951111 125.397758 3.000000
      vertex 170.479996 126.943611 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 168.854309 125.576118 3.000000
      vertex 168.906906 125.489548 3.000000
      vertex 170.479996 126.943611 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 168.793854 125.656952 3.000000
      vertex 168.854309 125.576118 3.000000
      vertex 170.479996 126.943611 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 168.726089 125.731514 3.000000
      vertex 168.793854 125.656952 3.000000
      vertex 170.479996 126.943611 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 168.651520 125.799286 3.000000
      vertex 168.726089 125.731514 3.000000
      vertex 170.479996 126.943611 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 169.684265 127.445480 3.000000
      vertex 168.651520 125.799286 3.000000
      vertex 170.479996 126.943611 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 168.570694 125.859726 3.000000
      vertex 168.651520 125.799286 3.000000
      vertex 169.684265 127.445480 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 168.484116 125.912323 3.000000
      vertex 168.570694 125.859726 3.000000
      vertex 169.684265 127.445480 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 168.392334 125.956535 3.000000
      vertex 168.484116 125.912323 3.000000
      vertex 169.684265 127.445480 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 168.295868 125.991844 3.000000
      vertex 168.392334 125.956535 3.000000
      vertex 169.684265 127.445480 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 168.911652 127.939850 3.000000
      vertex 168.295868 125.991844 3.000000
      vertex 169.684265 127.445480 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 168.195236 126.017723 3.000000
      vertex 168.295868 125.991844 3.000000
      vertex 168.911652 127.939850 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 168.090988 126.033630 3.000000
      vertex 168.195236 126.017723 3.000000
      vertex 168.911652 127.939850 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 167.983627 126.039055 3.000000
      vertex 168.090988 126.033630 3.000000
      vertex 168.911652 127.939850 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 168.162064 128.427048 3.000000
      vertex 167.983627 126.039055 3.000000
      vertex 168.911652 127.939850 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 167.435410 128.907394 3.000000
      vertex 167.983627 126.039055 3.000000
      vertex 168.162064 128.427048 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 172.141312 125.916069 3.000000
      vertex 169.028214 124.881699 3.000000
      vertex 169.012299 124.777443 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 168.986420 124.676811 3.000000
      vertex 172.141312 125.916069 3.000000
      vertex 169.012299 124.777443 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 168.951111 124.580345 3.000000
      vertex 172.141312 125.916069 3.000000
      vertex 168.986420 124.676811 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 173.007095 125.389748 3.000000
      vertex 172.141312 125.916069 3.000000
      vertex 168.951111 124.580345 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 168.906906 124.488564 3.000000
      vertex 173.007095 125.389748 3.000000
      vertex 168.951111 124.580345 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 168.854309 124.401985 3.000000
      vertex 173.007095 125.389748 3.000000
      vertex 168.906906 124.488564 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 173.007095 125.389748 3.000000
      vertex 168.854309 124.401985 3.000000
      vertex 168.793854 124.321152 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 173.896439 124.854622 3.000000
      vertex 173.007095 125.389748 3.000000
      vertex 168.793854 124.321152 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 168.726089 124.246590 3.000000
      vertex 173.896439 124.854622 3.000000
      vertex 168.793854 124.321152 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 168.651520 124.178818 3.000000
      vertex 173.896439 124.854622 3.000000
      vertex 168.726089 124.246590 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 174.809448 124.310364 3.000000
      vertex 173.896439 124.854622 3.000000
      vertex 168.651520 124.178818 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 168.570694 124.118378 3.000000
      vertex 174.809448 124.310364 3.000000
      vertex 168.651520 124.178818 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 168.484116 124.065781 3.000000
      vertex 174.809448 124.310364 3.000000
      vertex 168.570694 124.118378 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 175.746231 123.756653 3.000000
      vertex 174.809448 124.310364 3.000000
      vertex 168.484116 124.065781 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 168.392334 124.021568 3.000000
      vertex 175.746231 123.756653 3.000000
      vertex 168.484116 124.065781 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 168.295868 123.986259 3.000000
      vertex 175.746231 123.756653 3.000000
      vertex 168.392334 124.021568 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 175.746231 123.756653 3.000000
      vertex 168.295868 123.986259 3.000000
      vertex 168.195236 123.960388 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 168.090988 123.944473 3.000000
      vertex 175.746231 123.756653 3.000000
      vertex 168.195236 123.960388 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 167.983627 123.939049 3.000000
      vertex 175.746231 123.756653 3.000000
      vertex 168.090988 123.944473 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 167.983627 123.939049 3.000000
      vertex 167.876266 123.944473 3.000000
      vertex 177.584747 117.290016 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 177.558868 117.390640 3.000000
      vertex 167.983627 123.939049 3.000000
      vertex 177.584747 117.290016 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 177.542953 117.494896 3.000000
      vertex 167.983627 123.939049 3.000000
      vertex 177.558868 117.390640 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 167.876266 123.944473 3.000000
      vertex 167.772018 123.960388 3.000000
      vertex 177.664261 117.101761 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 177.620056 117.193542 3.000000
      vertex 167.876266 123.944473 3.000000
      vertex 177.664261 117.101761 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 177.584747 117.290016 3.000000
      vertex 167.876266 123.944473 3.000000
      vertex 177.620056 117.193542 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 177.716858 117.015190 3.000000
      vertex 177.664261 117.101761 3.000000
      vertex 167.772018 123.960388 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 167.671387 123.986259 3.000000
      vertex 177.716858 117.015190 3.000000
      vertex 167.772018 123.960388 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 177.777298 116.934357 3.000000
      vertex 177.716858 117.015190 3.000000
      vertex 167.671387 123.986259 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 167.574921 124.021568 3.000000
      vertex 177.777298 116.934357 3.000000
      vertex 167.671387 123.986259 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 177.845078 116.859787 3.000000
      vertex 177.777298 116.934357 3.000000
      vertex 167.574921 124.021568 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 160.949097 126.200821 3.000000
      vertex 177.845078 116.859787 3.000000
      vertex 167.574921 124.021568 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 160.853790 126.227402 3.000000
      vertex 177.845078 116.859787 3.000000
      vertex 160.949097 126.200821 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 160.949097 126.200821 3.000000
      vertex 167.574921 124.021568 3.000000
      vertex 167.483139 124.065781 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 161.045486 126.184006 3.000000
      vertex 160.949097 126.200821 3.000000
      vertex 167.483139 124.065781 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 167.396561 124.118378 3.000000
      vertex 161.045486 126.184006 3.000000
      vertex 167.483139 124.065781 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 161.142242 126.176765 3.000000
      vertex 161.045486 126.184006 3.000000
      vertex 167.396561 124.118378 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 167.315735 124.178818 3.000000
      vertex 161.142242 126.176765 3.000000
      vertex 167.396561 124.118378 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 167.241165 124.246590 3.000000
      vertex 161.142242 126.176765 3.000000
      vertex 167.315735 124.178818 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 161.142242 126.176765 3.000000
      vertex 167.241165 124.246590 3.000000
      vertex 167.173401 124.321152 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 167.112946 124.401985 3.000000
      vertex 161.142242 126.176765 3.000000
      vertex 167.173401 124.321152 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 167.060364 124.488564 3.000000
      vertex 161.142242 126.176765 3.000000
      vertex 167.112946 124.401985 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 161.142242 126.176765 3.000000
      vertex 167.060364 124.488564 3.000000
      vertex 167.016144 124.580345 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 166.980835 124.676811 3.000000
      vertex 161.142242 126.176765 3.000000
      vertex 167.016144 124.580345 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 166.954956 124.777443 3.000000
      vertex 161.142242 126.176765 3.000000
      vertex 166.980835 124.676811 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 161.142242 126.176765 3.000000
      vertex 166.954956 124.777443 3.000000
      vertex 166.939056 124.881699 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 166.933624 124.989052 3.000000
      vertex 161.142242 126.176765 3.000000
      vertex 166.939056 124.881699 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 166.939056 125.096405 3.000000
      vertex 161.142242 126.176765 3.000000
      vertex 166.933624 124.989052 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 161.142242 126.176765 3.000000
      vertex 166.939056 125.096405 3.000000
      vertex 166.954956 125.200661 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 166.980835 125.301292 3.000000
      vertex 161.142242 126.176765 3.000000
      vertex 166.954956 125.200661 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 167.016144 125.397758 3.000000
      vertex 161.142242 126.176765 3.000000
      vertex 166.980835 125.301292 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 161.142242 126.176765 3.000000
      vertex 167.016144 125.397758 3.000000
      vertex 167.060364 125.489548 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 167.112946 125.576118 3.000000
      vertex 161.142242 126.176765 3.000000
      vertex 167.060364 125.489548 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 167.173401 125.656952 3.000000
      vertex 161.142242 126.176765 3.000000
      vertex 167.112946 125.576118 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 161.142242 126.176765 3.000000
      vertex 167.173401 125.656952 3.000000
      vertex 167.241165 125.731514 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 167.315735 125.799286 3.000000
      vertex 161.142242 126.176765 3.000000
      vertex 167.241165 125.731514 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 167.396561 125.859726 3.000000
      vertex 161.142242 126.176765 3.000000
      vertex 167.315735 125.799286 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 161.142242 126.176765 3.000000
      vertex 167.396561 125.859726 3.000000
      vertex 167.483139 125.912323 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 167.574921 125.956535 3.000000
      vertex 161.142242 126.176765 3.000000
      vertex 167.483139 125.912323 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 167.671387 125.991844 3.000000
      vertex 161.142242 126.176765 3.000000
      vertex 167.574921 125.956535 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 161.142242 126.176765 3.000000
      vertex 167.671387 125.991844 3.000000
      vertex 167.772018 126.017723 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 167.876266 126.033630 3.000000
      vertex 161.142242 126.176765 3.000000
      vertex 167.772018 126.017723 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 167.983627 126.039055 3.000000
      vertex 161.142242 126.176765 3.000000
      vertex 167.876266 126.033630 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 125.063393 202.113159 3.000000
      vertex 125.057976 202.005814 3.000000
      vertex 129.117828 204.333572 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 127.652306 204.592361 3.000000
      vertex 125.063393 202.113159 3.000000
      vertex 129.117828 204.333572 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 125.057976 202.220520 3.000000
      vertex 125.063393 202.113159 3.000000
      vertex 127.652306 204.592361 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 125.042061 202.324783 3.000000
      vertex 125.057976 202.220520 3.000000
      vertex 127.652306 204.592361 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 125.016190 202.425400 3.000000
      vertex 125.042061 202.324783 3.000000
      vertex 127.652306 204.592361 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 124.980881 202.521866 3.000000
      vertex 125.016190 202.425400 3.000000
      vertex 127.652306 204.592361 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 124.936668 202.613663 3.000000
      vertex 124.980881 202.521866 3.000000
      vertex 127.652306 204.592361 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 126.168221 204.831757 3.000000
      vertex 124.936668 202.613663 3.000000
      vertex 127.652306 204.592361 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 124.884071 202.700226 3.000000
      vertex 124.936668 202.613663 3.000000
      vertex 126.168221 204.831757 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 124.823624 202.781067 3.000000
      vertex 124.884071 202.700226 3.000000
      vertex 126.168221 204.831757 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 124.755859 202.855621 3.000000
      vertex 124.823624 202.781067 3.000000
      vertex 126.168221 204.831757 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 124.681290 202.923401 3.000000
      vertex 124.755859 202.855621 3.000000
      vertex 126.168221 204.831757 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 124.600464 202.983841 3.000000
      vertex 124.681290 202.923401 3.000000
      vertex 126.168221 204.831757 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 124.513885 203.036438 3.000000
      vertex 124.600464 202.983841 3.000000
      vertex 126.168221 204.831757 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 124.665428 205.051819 3.000000
      vertex 124.513885 203.036438 3.000000
      vertex 126.168221 204.831757 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 124.422104 203.080643 3.000000
      vertex 124.513885 203.036438 3.000000
      vertex 124.665428 205.051819 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 124.325630 203.115952 3.000000
      vertex 124.422104 203.080643 3.000000
      vertex 124.665428 205.051819 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 124.225006 203.141830 3.000000
      vertex 124.325630 203.115952 3.000000
      vertex 124.665428 205.051819 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 124.120750 203.157745 3.000000
      vertex 124.225006 203.141830 3.000000
      vertex 124.665428 205.051819 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 124.013397 203.163162 3.000000
      vertex 124.120750 203.157745 3.000000
      vertex 124.665428 205.051819 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 123.143761 205.252563 3.000000
      vertex 124.013397 203.163162 3.000000
      vertex 124.665428 205.051819 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 121.603073 205.434021 3.000000
      vertex 124.013397 203.163162 3.000000
      vertex 123.143761 205.252563 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 129.117828 204.333572 3.000000
      vertex 125.057976 202.005814 3.000000
      vertex 125.042061 201.901550 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 125.016190 201.800934 3.000000
      vertex 129.117828 204.333572 3.000000
      vertex 125.042061 201.901550 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 130.564972 204.055374 3.000000
      vertex 129.117828 204.333572 3.000000
      vertex 125.016190 201.800934 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 124.980881 201.704453 3.000000
      vertex 130.564972 204.055374 3.000000
      vertex 125.016190 201.800934 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 124.936668 201.612671 3.000000
      vertex 130.564972 204.055374 3.000000
      vertex 124.980881 201.704453 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 130.564972 204.055374 3.000000
      vertex 124.936668 201.612671 3.000000
      vertex 124.884071 201.526093 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 131.993851 203.757736 3.000000
      vertex 130.564972 204.055374 3.000000
      vertex 124.884071 201.526093 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 124.823624 201.445267 3.000000
      vertex 131.993851 203.757736 3.000000
      vertex 124.884071 201.526093 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 124.755859 201.370697 3.000000
      vertex 131.993851 203.757736 3.000000
      vertex 124.823624 201.445267 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 133.404648 203.440598 3.000000
      vertex 131.993851 203.757736 3.000000
      vertex 124.755859 201.370697 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 124.681290 201.302933 3.000000
      vertex 133.404648 203.440598 3.000000
      vertex 124.755859 201.370697 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 134.797531 203.103958 3.000000
      vertex 133.404648 203.440598 3.000000
      vertex 124.681290 201.302933 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 124.600464 201.242493 3.000000
      vertex 134.797531 203.103958 3.000000
      vertex 124.681290 201.302933 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 136.172623 202.747757 3.000000
      vertex 134.797531 203.103958 3.000000
      vertex 124.600464 201.242493 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 124.513885 201.189896 3.000000
      vertex 136.172623 202.747757 3.000000
      vertex 124.600464 201.242493 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 137.530090 202.371979 3.000000
      vertex 136.172623 202.747757 3.000000
      vertex 124.513885 201.189896 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 124.422104 201.145676 3.000000
      vertex 137.530090 202.371979 3.000000
      vertex 124.513885 201.189896 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 138.870117 201.976593 3.000000
      vertex 137.530090 202.371979 3.000000
      vertex 124.422104 201.145676 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 140.192825 201.561539 3.000000
      vertex 138.870117 201.976593 3.000000
      vertex 124.422104 201.145676 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.279419 192.085403 3.000000
      vertex 140.192825 201.561539 3.000000
      vertex 124.422104 201.145676 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.235214 192.177200 3.000000
      vertex 140.192825 201.561539 3.000000
      vertex 151.279419 192.085403 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.279419 192.085403 3.000000
      vertex 124.422104 201.145676 3.000000
      vertex 124.325630 201.110367 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.332016 191.998840 3.000000
      vertex 151.279419 192.085403 3.000000
      vertex 124.325630 201.110367 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 124.225006 201.084503 3.000000
      vertex 151.332016 191.998840 3.000000
      vertex 124.325630 201.110367 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.392471 191.917999 3.000000
      vertex 151.332016 191.998840 3.000000
      vertex 124.225006 201.084503 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 124.120750 201.068588 3.000000
      vertex 151.392471 191.917999 3.000000
      vertex 124.225006 201.084503 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.460236 191.843445 3.000000
      vertex 151.392471 191.917999 3.000000
      vertex 124.120750 201.068588 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.534805 191.775665 3.000000
      vertex 151.460236 191.843445 3.000000
      vertex 124.120750 201.068588 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 124.013397 201.063171 3.000000
      vertex 151.534805 191.775665 3.000000
      vertex 124.120750 201.068588 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 59.755661 200.686371 3.000000
      vertex 124.013397 201.063171 3.000000
      vertex 123.906036 201.068588 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 99.044136 201.962616 3.000000
      vertex 59.755661 200.686371 3.000000
      vertex 123.906036 201.068588 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.936775 201.968033 3.000000
      vertex 59.755661 200.686371 3.000000
      vertex 99.044136 201.962616 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 99.044136 201.962616 3.000000
      vertex 123.906036 201.068588 3.000000
      vertex 123.801781 201.084503 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 123.701157 201.110367 3.000000
      vertex 99.044136 201.962616 3.000000
      vertex 123.801781 201.084503 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 123.604691 201.145676 3.000000
      vertex 99.044136 201.962616 3.000000
      vertex 123.701157 201.110367 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 99.044136 201.962616 3.000000
      vertex 123.604691 201.145676 3.000000
      vertex 123.512901 201.189896 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 123.426331 201.242493 3.000000
      vertex 99.044136 201.962616 3.000000
      vertex 123.512901 201.189896 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 123.345497 201.302933 3.000000
      vertex 99.044136 201.962616 3.000000
      vertex 123.426331 201.242493 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 99.044136 201.962616 3.000000
      vertex 123.345497 201.302933 3.000000
      vertex 123.270935 201.370697 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 123.203163 201.445267 3.000000
      vertex 99.044136 201.962616 3.000000
      vertex 123.270935 201.370697 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 123.142723 201.526093 3.000000
      vertex 99.044136 201.962616 3.000000
      vertex 123.203163 201.445267 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 99.044136 201.962616 3.000000
      vertex 123.142723 201.526093 3.000000
      vertex 123.090126 201.612671 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 123.045914 201.704453 3.000000
      vertex 99.044136 201.962616 3.000000
      vertex 123.090126 201.612671 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 123.010605 201.800934 3.000000
      vertex 99.044136 201.962616 3.000000
      vertex 123.045914 201.704453 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 99.044136 201.962616 3.000000
      vertex 123.010605 201.800934 3.000000
      vertex 122.984726 201.901550 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 99.151489 201.968033 3.000000
      vertex 99.044136 201.962616 3.000000
      vertex 122.984726 201.901550 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 99.255745 201.983948 3.000000
      vertex 99.151489 201.968033 3.000000
      vertex 122.984726 201.901550 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 99.356377 202.009811 3.000000
      vertex 99.255745 201.983948 3.000000
      vertex 122.984726 201.901550 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 99.452843 202.045120 3.000000
      vertex 99.356377 202.009811 3.000000
      vertex 122.984726 201.901550 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 99.544624 202.089340 3.000000
      vertex 99.452843 202.045120 3.000000
      vertex 122.984726 201.901550 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 99.631203 202.141937 3.000000
      vertex 99.544624 202.089340 3.000000
      vertex 122.984726 201.901550 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 99.712036 202.202377 3.000000
      vertex 99.631203 202.141937 3.000000
      vertex 122.984726 201.901550 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 99.786598 202.270157 3.000000
      vertex 99.712036 202.202377 3.000000
      vertex 122.984726 201.901550 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 99.854362 202.344711 3.000000
      vertex 99.786598 202.270157 3.000000
      vertex 122.984726 201.901550 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 99.914810 202.425552 3.000000
      vertex 99.854362 202.344711 3.000000
      vertex 122.984726 201.901550 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 99.967407 202.512115 3.000000
      vertex 99.914810 202.425552 3.000000
      vertex 122.984726 201.901550 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 100.011620 202.603897 3.000000
      vertex 99.967407 202.512115 3.000000
      vertex 122.984726 201.901550 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 100.046928 202.700378 3.000000
      vertex 100.011620 202.603897 3.000000
      vertex 122.984726 201.901550 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 100.072800 202.800995 3.000000
      vertex 100.046928 202.700378 3.000000
      vertex 122.984726 201.901550 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 122.968819 202.005814 3.000000
      vertex 100.072800 202.800995 3.000000
      vertex 122.984726 201.901550 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 100.088715 202.905258 3.000000
      vertex 100.072800 202.800995 3.000000
      vertex 122.968819 202.005814 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 122.963394 202.113159 3.000000
      vertex 100.088715 202.905258 3.000000
      vertex 122.968819 202.005814 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 100.094131 203.012619 3.000000
      vertex 100.088715 202.905258 3.000000
      vertex 122.963394 202.113159 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 122.968819 202.220520 3.000000
      vertex 100.094131 203.012619 3.000000
      vertex 122.963394 202.113159 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 100.088715 203.119965 3.000000
      vertex 100.094131 203.012619 3.000000
      vertex 122.968819 202.220520 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 122.984726 202.324783 3.000000
      vertex 100.088715 203.119965 3.000000
      vertex 122.968819 202.220520 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 100.072800 203.224228 3.000000
      vertex 100.088715 203.119965 3.000000
      vertex 122.984726 202.324783 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 123.010605 202.425400 3.000000
      vertex 100.072800 203.224228 3.000000
      vertex 122.984726 202.324783 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 123.045914 202.521866 3.000000
      vertex 100.072800 203.224228 3.000000
      vertex 123.010605 202.425400 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 100.072800 203.224228 3.000000
      vertex 123.045914 202.521866 3.000000
      vertex 123.090126 202.613663 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 123.142723 202.700226 3.000000
      vertex 100.072800 203.224228 3.000000
      vertex 123.090126 202.613663 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 123.203163 202.781067 3.000000
      vertex 100.072800 203.224228 3.000000
      vertex 123.142723 202.700226 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 100.072800 203.224228 3.000000
      vertex 123.203163 202.781067 3.000000
      vertex 123.270935 202.855621 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 123.345497 202.923401 3.000000
      vertex 100.072800 203.224228 3.000000
      vertex 123.270935 202.855621 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 123.426331 202.983841 3.000000
      vertex 100.072800 203.224228 3.000000
      vertex 123.345497 202.923401 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 100.072800 203.224228 3.000000
      vertex 123.426331 202.983841 3.000000
      vertex 123.512901 203.036438 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 123.604691 203.080643 3.000000
      vertex 100.072800 203.224228 3.000000
      vertex 123.512901 203.036438 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 123.701157 203.115952 3.000000
      vertex 100.072800 203.224228 3.000000
      vertex 123.604691 203.080643 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 100.072800 203.224228 3.000000
      vertex 123.701157 203.115952 3.000000
      vertex 123.801781 203.141830 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 123.906036 203.157745 3.000000
      vertex 100.072800 203.224228 3.000000
      vertex 123.801781 203.141830 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 124.013397 203.163162 3.000000
      vertex 100.072800 203.224228 3.000000
      vertex 123.906036 203.157745 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 105.375107 86.815102 3.000000
      vertex 100.066025 91.574432 3.000000
      vertex 100.071449 91.467072 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 100.066025 91.359718 3.000000
      vertex 105.375107 86.815102 3.000000
      vertex 100.071449 91.467072 3.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 102.892342 87.131226 3.000000
      vertex 105.375107 86.815102 3.000000
      vertex 100.066025 91.359718 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 100.050117 91.255463 3.000000
      vertex 102.892342 87.131226 3.000000
      vertex 100.066025 91.359718 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 100.024239 91.154839 3.000000
      vertex 102.892342 87.131226 3.000000
      vertex 100.050117 91.255463 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 102.892342 87.131226 3.000000
      vertex 100.024239 91.154839 3.000000
      vertex 99.988930 91.058365 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 99.944717 90.966583 3.000000
      vertex 102.892342 87.131226 3.000000
      vertex 99.988930 91.058365 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 99.892120 90.880013 3.000000
      vertex 102.892342 87.131226 3.000000
      vertex 99.944717 90.966583 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 102.892342 87.131226 3.000000
      vertex 99.892120 90.880013 3.000000
      vertex 99.831680 90.799179 3.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 100.413780 87.483971 3.000000
      vertex 102.892342 87.131226 3.000000
      vertex 99.831680 90.799179 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 99.763908 90.724609 3.000000
      vertex 100.413780 87.483971 3.000000
      vertex 99.831680 90.799179 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 99.689346 90.656845 3.000000
      vertex 100.413780 87.483971 3.000000
      vertex 99.763908 90.724609 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 100.413780 87.483971 3.000000
      vertex 99.689346 90.656845 3.000000
      vertex 99.608513 90.596397 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 99.521942 90.543808 3.000000
      vertex 100.413780 87.483971 3.000000
      vertex 99.608513 90.596397 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 99.430153 90.499588 3.000000
      vertex 100.413780 87.483971 3.000000
      vertex 99.521942 90.543808 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 100.413780 87.483971 3.000000
      vertex 99.430153 90.499588 3.000000
      vertex 99.333687 90.464279 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 99.233055 90.438408 3.000000
      vertex 100.413780 87.483971 3.000000
      vertex 99.333687 90.464279 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 99.128799 90.422493 3.000000
      vertex 100.413780 87.483971 3.000000
      vertex 99.233055 90.438408 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 97.862793 87.871284 3.000000
      vertex 100.413780 87.483971 3.000000
      vertex 99.128799 90.422493 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 99.021446 90.417076 3.000000
      vertex 97.862793 87.871284 3.000000
      vertex 99.128799 90.422493 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 97.592560 87.924980 3.000000
      vertex 97.862793 87.871284 3.000000
      vertex 99.021446 90.417076 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 97.332329 88.001808 3.000000
      vertex 97.592560 87.924980 3.000000
      vertex 99.021446 90.417076 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 97.083115 88.100571 3.000000
      vertex 97.332329 88.001808 3.000000
      vertex 99.021446 90.417076 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 96.845947 88.220070 3.000000
      vertex 97.083115 88.100571 3.000000
      vertex 99.021446 90.417076 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 96.621857 88.359116 3.000000
      vertex 96.845947 88.220070 3.000000
      vertex 99.021446 90.417076 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 96.411865 88.516510 3.000000
      vertex 96.621857 88.359116 3.000000
      vertex 99.021446 90.417076 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 96.217003 88.691063 3.000000
      vertex 96.411865 88.516510 3.000000
      vertex 99.021446 90.417076 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 96.038292 88.881577 3.000000
      vertex 96.217003 88.691063 3.000000
      vertex 99.021446 90.417076 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 95.876762 89.086868 3.000000
      vertex 96.038292 88.881577 3.000000
      vertex 99.021446 90.417076 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 95.733437 89.305725 3.000000
      vertex 95.876762 89.086868 3.000000
      vertex 99.021446 90.417076 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 95.609344 89.536964 3.000000
      vertex 95.733437 89.305725 3.000000
      vertex 99.021446 90.417076 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 95.505508 89.779388 3.000000
      vertex 95.609344 89.536964 3.000000
      vertex 99.021446 90.417076 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 95.422966 90.031807 3.000000
      vertex 95.505508 89.779388 3.000000
      vertex 99.021446 90.417076 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 95.362732 90.293015 3.000000
      vertex 95.422966 90.031807 3.000000
      vertex 99.021446 90.417076 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.914093 90.422493 3.000000
      vertex 95.362732 90.293015 3.000000
      vertex 99.021446 90.417076 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.809837 90.438408 3.000000
      vertex 95.362732 90.293015 3.000000
      vertex 98.914093 90.422493 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 95.362732 90.293015 3.000000
      vertex 98.809837 90.438408 3.000000
      vertex 98.709206 90.464279 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.612740 90.499588 3.000000
      vertex 95.362732 90.293015 3.000000
      vertex 98.709206 90.464279 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.520958 90.543808 3.000000
      vertex 95.362732 90.293015 3.000000
      vertex 98.612740 90.499588 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 95.362732 90.293015 3.000000
      vertex 98.520958 90.543808 3.000000
      vertex 98.434380 90.596397 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.353546 90.656845 3.000000
      vertex 95.362732 90.293015 3.000000
      vertex 98.434380 90.596397 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.278984 90.724609 3.000000
      vertex 95.362732 90.293015 3.000000
      vertex 98.353546 90.656845 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 95.362732 90.293015 3.000000
      vertex 98.278984 90.724609 3.000000
      vertex 98.211212 90.799179 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.150772 90.880013 3.000000
      vertex 95.362732 90.293015 3.000000
      vertex 98.211212 90.799179 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.098175 90.966583 3.000000
      vertex 95.362732 90.293015 3.000000
      vertex 98.150772 90.880013 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 95.362732 90.293015 3.000000
      vertex 98.098175 90.966583 3.000000
      vertex 98.053963 91.058365 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 95.325844 90.561836 3.000000
      vertex 95.362732 90.293015 3.000000
      vertex 98.053963 91.058365 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.018654 91.154839 3.000000
      vertex 95.325844 90.561836 3.000000
      vertex 98.053963 91.058365 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 95.313316 90.837059 3.000000
      vertex 95.325844 90.561836 3.000000
      vertex 98.018654 91.154839 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 97.992783 91.255463 3.000000
      vertex 95.313316 90.837059 3.000000
      vertex 98.018654 91.154839 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 97.976868 91.359718 3.000000
      vertex 95.313316 90.837059 3.000000
      vertex 97.992783 91.255463 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 95.313316 90.837059 3.000000
      vertex 97.976868 91.359718 3.000000
      vertex 97.971443 91.467072 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 97.976868 91.574432 3.000000
      vertex 95.313316 90.837059 3.000000
      vertex 97.971443 91.467072 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 97.992783 91.678688 3.000000
      vertex 95.313316 90.837059 3.000000
      vertex 97.976868 91.574432 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 95.313316 90.837059 3.000000
      vertex 97.992783 91.678688 3.000000
      vertex 98.018654 91.779312 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.053963 91.875786 3.000000
      vertex 95.313316 90.837059 3.000000
      vertex 98.018654 91.779312 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.098175 91.967567 3.000000
      vertex 95.313316 90.837059 3.000000
      vertex 98.053963 91.875786 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 95.313316 90.837059 3.000000
      vertex 98.098175 91.967567 3.000000
      vertex 98.150772 92.054138 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.211212 92.134972 3.000000
      vertex 95.313316 90.837059 3.000000
      vertex 98.150772 92.054138 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.278984 92.209534 3.000000
      vertex 95.313316 90.837059 3.000000
      vertex 98.211212 92.134972 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 95.313316 90.837059 3.000000
      vertex 98.278984 92.209534 3.000000
      vertex 98.353546 92.277306 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 95.313316 103.467812 3.000000
      vertex 95.313316 90.837059 3.000000
      vertex 98.353546 92.277306 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.434380 92.337753 3.000000
      vertex 95.313316 103.467812 3.000000
      vertex 98.353546 92.277306 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.520958 92.390343 3.000000
      vertex 95.313316 103.467812 3.000000
      vertex 98.434380 92.337753 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 95.313316 103.467812 3.000000
      vertex 98.520958 92.390343 3.000000
      vertex 98.612740 92.434563 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.709206 92.469872 3.000000
      vertex 95.313316 103.467812 3.000000
      vertex 98.612740 92.434563 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.809837 92.495743 3.000000
      vertex 95.313316 103.467812 3.000000
      vertex 98.709206 92.469872 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 95.313316 103.467812 3.000000
      vertex 98.809837 92.495743 3.000000
      vertex 98.914093 92.511658 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 99.021446 92.517075 3.000000
      vertex 95.313316 103.467812 3.000000
      vertex 98.914093 92.511658 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 99.128799 92.511658 3.000000
      vertex 95.313316 103.467812 3.000000
      vertex 99.021446 92.517075 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 95.313316 103.467812 3.000000
      vertex 99.128799 92.511658 3.000000
      vertex 99.233055 92.495743 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 99.333687 92.469872 3.000000
      vertex 95.313316 103.467812 3.000000
      vertex 99.233055 92.495743 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 99.430153 92.434563 3.000000
      vertex 95.313316 103.467812 3.000000
      vertex 99.333687 92.469872 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 95.313316 103.467812 3.000000
      vertex 99.430153 92.434563 3.000000
      vertex 99.521942 92.390343 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 99.608513 92.337753 3.000000
      vertex 95.313316 103.467812 3.000000
      vertex 99.521942 92.390343 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 99.689346 92.277306 3.000000
      vertex 95.313316 103.467812 3.000000
      vertex 99.608513 92.337753 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 95.313316 103.467812 3.000000
      vertex 99.689346 92.277306 3.000000
      vertex 99.763908 92.209534 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 110.297417 86.249596 3.000000
      vertex 95.313316 103.467812 3.000000
      vertex 99.763908 92.209534 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 114.987381 85.712395 3.000000
      vertex 95.313316 103.467812 3.000000
      vertex 110.297417 86.249596 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 110.297417 86.249596 3.000000
      vertex 99.763908 92.209534 3.000000
      vertex 99.831680 92.134972 3.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 99.892120 92.054138 3.000000
      vertex 110.297417 86.249596 3.000000
      vertex 99.831680 92.134972 3.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 99.944717 91.967567 3.000000
      vertex 110.297417 86.249596 3.000000
      vertex 99.892120 92.054138 3.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 107.848114 86.524818 3.000000
      vertex 110.297417 86.249596 3.000000
      vertex 99.944717 91.967567 3.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 99.988930 91.875786 3.000000
      vertex 107.848114 86.524818 3.000000
      vertex 99.944717 91.967567 3.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 100.024239 91.779312 3.000000
      vertex 107.848114 86.524818 3.000000
      vertex 99.988930 91.875786 3.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 105.375107 86.815102 3.000000
      vertex 107.848114 86.524818 3.000000
      vertex 100.024239 91.779312 3.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 100.050117 91.678688 3.000000
      vertex 105.375107 86.815102 3.000000
      vertex 100.024239 91.779312 3.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 100.066025 91.574432 3.000000
      vertex 105.375107 86.815102 3.000000
      vertex 100.050117 91.678688 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 157.924652 74.011238 3.000000
      vertex 156.091553 76.816788 3.000000
      vertex 156.096970 76.709427 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 156.091553 76.602074 3.000000
      vertex 157.924652 74.011238 3.000000
      vertex 156.096970 76.709427 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 156.075638 76.497818 3.000000
      vertex 157.924652 74.011238 3.000000
      vertex 156.091553 76.602074 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 157.924652 74.011238 3.000000
      vertex 156.075638 76.497818 3.000000
      vertex 156.049759 76.397186 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 156.014450 76.300720 3.000000
      vertex 157.924652 74.011238 3.000000
      vertex 156.049759 76.397186 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 155.970245 76.208939 3.000000
      vertex 157.924652 74.011238 3.000000
      vertex 156.014450 76.300720 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 157.924652 74.011238 3.000000
      vertex 155.970245 76.208939 3.000000
      vertex 155.917648 76.122360 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 155.857193 76.041527 3.000000
      vertex 157.924652 74.011238 3.000000
      vertex 155.917648 76.122360 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 155.789429 75.966965 3.000000
      vertex 157.924652 74.011238 3.000000
      vertex 155.857193 76.041527 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 157.924652 74.011238 3.000000
      vertex 155.789429 75.966965 3.000000
      vertex 155.714859 75.899193 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 155.634033 75.838753 3.000000
      vertex 157.924652 74.011238 3.000000
      vertex 155.714859 75.899193 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 155.547455 75.786156 3.000000
      vertex 157.924652 74.011238 3.000000
      vertex 155.634033 75.838753 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 157.658264 73.623230 3.000000
      vertex 157.924652 74.011238 3.000000
      vertex 155.547455 75.786156 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 155.455673 75.741943 3.000000
      vertex 157.658264 73.623230 3.000000
      vertex 155.547455 75.786156 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 157.334305 73.281586 3.000000
      vertex 157.658264 73.623230 3.000000
      vertex 155.455673 75.741943 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 155.359207 75.706635 3.000000
      vertex 157.334305 73.281586 3.000000
      vertex 155.455673 75.741943 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 156.960815 72.994774 3.000000
      vertex 157.334305 73.281586 3.000000
      vertex 155.359207 75.706635 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 155.258575 75.680763 3.000000
      vertex 156.960815 72.994774 3.000000
      vertex 155.359207 75.706635 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 156.547043 72.769890 3.000000
      vertex 156.960815 72.994774 3.000000
      vertex 155.258575 75.680763 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 156.103241 72.612526 3.000000
      vertex 156.547043 72.769890 3.000000
      vertex 155.258575 75.680763 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 155.154327 75.664848 3.000000
      vertex 156.103241 72.612526 3.000000
      vertex 155.258575 75.680763 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 155.716431 72.535660 3.000000
      vertex 156.103241 72.612526 3.000000
      vertex 155.154327 75.664848 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 155.326019 72.510208 3.000000
      vertex 155.716431 72.535660 3.000000
      vertex 155.154327 75.664848 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 154.936188 72.535622 3.000000
      vertex 155.326019 72.510208 3.000000
      vertex 155.154327 75.664848 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 155.046967 75.659424 3.000000
      vertex 154.936188 72.535622 3.000000
      vertex 155.154327 75.664848 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 154.552948 72.611450 3.000000
      vertex 154.936188 72.535622 3.000000
      vertex 155.046967 75.659424 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 154.181320 72.737083 3.000000
      vertex 154.552948 72.611450 3.000000
      vertex 155.046967 75.659424 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 153.826370 72.911903 3.000000
      vertex 154.181320 72.737083 3.000000
      vertex 155.046967 75.659424 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 151.227386 74.411903 3.000000
      vertex 153.826370 72.911903 3.000000
      vertex 155.046967 75.659424 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 149.770706 75.235153 3.000000
      vertex 151.227386 74.411903 3.000000
      vertex 155.046967 75.659424 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 154.939606 75.664848 3.000000
      vertex 149.770706 75.235153 3.000000
      vertex 155.046967 75.659424 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 154.835358 75.680763 3.000000
      vertex 149.770706 75.235153 3.000000
      vertex 154.939606 75.664848 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 149.770706 75.235153 3.000000
      vertex 154.835358 75.680763 3.000000
      vertex 154.734726 75.706635 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 154.638260 75.741943 3.000000
      vertex 149.770706 75.235153 3.000000
      vertex 154.734726 75.706635 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 154.546478 75.786156 3.000000
      vertex 149.770706 75.235153 3.000000
      vertex 154.638260 75.741943 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 149.770706 75.235153 3.000000
      vertex 154.546478 75.786156 3.000000
      vertex 154.459900 75.838753 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 154.379074 75.899193 3.000000
      vertex 149.770706 75.235153 3.000000
      vertex 154.459900 75.838753 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 154.304504 75.966965 3.000000
      vertex 149.770706 75.235153 3.000000
      vertex 154.379074 75.899193 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 149.770706 75.235153 3.000000
      vertex 154.304504 75.966965 3.000000
      vertex 154.236740 76.041527 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 154.176285 76.122360 3.000000
      vertex 149.770706 75.235153 3.000000
      vertex 154.236740 76.041527 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 154.123703 76.208939 3.000000
      vertex 149.770706 75.235153 3.000000
      vertex 154.176285 76.122360 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 149.770706 75.235153 3.000000
      vertex 154.123703 76.208939 3.000000
      vertex 154.079483 76.300720 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 154.044174 76.397186 3.000000
      vertex 149.770706 75.235153 3.000000
      vertex 154.079483 76.300720 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 154.018295 76.497818 3.000000
      vertex 149.770706 75.235153 3.000000
      vertex 154.044174 76.397186 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 149.770706 75.235153 3.000000
      vertex 154.018295 76.497818 3.000000
      vertex 154.002396 76.602074 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 153.996964 76.709427 3.000000
      vertex 149.770706 75.235153 3.000000
      vertex 154.002396 76.602074 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 154.002396 76.816788 3.000000
      vertex 149.770706 75.235153 3.000000
      vertex 153.996964 76.709427 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 149.770706 75.235153 3.000000
      vertex 154.002396 76.816788 3.000000
      vertex 154.018295 76.921036 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 154.044174 77.021667 3.000000
      vertex 149.770706 75.235153 3.000000
      vertex 154.018295 76.921036 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 154.079483 77.118134 3.000000
      vertex 149.770706 75.235153 3.000000
      vertex 154.044174 77.021667 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 148.329773 76.015358 3.000000
      vertex 149.770706 75.235153 3.000000
      vertex 154.079483 77.118134 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 154.123703 77.209923 3.000000
      vertex 148.329773 76.015358 3.000000
      vertex 154.079483 77.118134 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 154.176285 77.296494 3.000000
      vertex 148.329773 76.015358 3.000000
      vertex 154.123703 77.209923 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 148.329773 76.015358 3.000000
      vertex 154.176285 77.296494 3.000000
      vertex 154.236740 77.377327 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 146.904129 76.753906 3.000000
      vertex 148.329773 76.015358 3.000000
      vertex 154.236740 77.377327 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 154.304504 77.451889 3.000000
      vertex 146.904129 76.753906 3.000000
      vertex 154.236740 77.377327 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 154.379074 77.519661 3.000000
      vertex 146.904129 76.753906 3.000000
      vertex 154.304504 77.451889 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 146.904129 76.753906 3.000000
      vertex 154.379074 77.519661 3.000000
      vertex 154.459900 77.580101 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 145.493362 77.452171 3.000000
      vertex 146.904129 76.753906 3.000000
      vertex 154.459900 77.580101 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 154.546478 77.632698 3.000000
      vertex 145.493362 77.452171 3.000000
      vertex 154.459900 77.580101 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 154.638260 77.676910 3.000000
      vertex 145.493362 77.452171 3.000000
      vertex 154.546478 77.632698 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 144.097061 78.111534 3.000000
      vertex 145.493362 77.452171 3.000000
      vertex 154.638260 77.676910 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 154.734726 77.712219 3.000000
      vertex 144.097061 78.111534 3.000000
      vertex 154.638260 77.676910 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 142.714767 78.733368 3.000000
      vertex 144.097061 78.111534 3.000000
      vertex 154.734726 77.712219 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 154.835358 77.738098 3.000000
      vertex 142.714767 78.733368 3.000000
      vertex 154.734726 77.712219 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 141.346085 79.319061 3.000000
      vertex 142.714767 78.733368 3.000000
      vertex 154.835358 77.738098 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 154.939606 77.754005 3.000000
      vertex 141.346085 79.319061 3.000000
      vertex 154.835358 77.738098 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 139.990570 79.869987 3.000000
      vertex 141.346085 79.319061 3.000000
      vertex 154.939606 77.754005 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 178.000473 116.731575 3.000000
      vertex 139.990570 79.869987 3.000000
      vertex 154.939606 77.754005 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 138.647781 80.387527 3.000000
      vertex 139.990570 79.869987 3.000000
      vertex 178.000473 116.731575 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 137.317322 80.873062 3.000000
      vertex 138.647781 80.387527 3.000000
      vertex 178.000473 116.731575 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 135.998749 81.327972 3.000000
      vertex 137.317322 80.873062 3.000000
      vertex 178.000473 116.731575 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 134.691620 81.753632 3.000000
      vertex 135.998749 81.327972 3.000000
      vertex 178.000473 116.731575 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 133.395538 82.151428 3.000000
      vertex 134.691620 81.753632 3.000000
      vertex 178.000473 116.731575 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 132.110062 82.522736 3.000000
      vertex 133.395538 82.151428 3.000000
      vertex 178.000473 116.731575 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 130.834747 82.868935 3.000000
      vertex 132.110062 82.522736 3.000000
      vertex 178.000473 116.731575 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 129.569199 83.191406 3.000000
      vertex 130.834747 82.868935 3.000000
      vertex 178.000473 116.731575 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 128.312958 83.491524 3.000000
      vertex 129.569199 83.191406 3.000000
      vertex 178.000473 116.731575 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 127.065620 83.770683 3.000000
      vertex 128.312958 83.491524 3.000000
      vertex 178.000473 116.731575 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 124.595909 84.271599 3.000000
      vertex 127.065620 83.770683 3.000000
      vertex 178.000473 116.731575 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 94.951401 104.897141 3.000000
      vertex 124.595909 84.271599 3.000000
      vertex 178.000473 116.731575 3.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 95.077667 104.635017 3.000000
      vertex 124.595909 84.271599 3.000000
      vertex 94.951401 104.897141 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 178.000473 116.731575 3.000000
      vertex 154.939606 77.754005 3.000000
      vertex 155.046967 77.759430 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 155.154327 77.754005 3.000000
      vertex 178.000473 116.731575 3.000000
      vertex 155.046967 77.759430 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 155.258575 77.738098 3.000000
      vertex 178.000473 116.731575 3.000000
      vertex 155.154327 77.754005 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 178.000473 116.731575 3.000000
      vertex 155.258575 77.738098 3.000000
      vertex 155.359207 77.712219 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 178.087036 116.678978 3.000000
      vertex 178.000473 116.731575 3.000000
      vertex 155.359207 77.712219 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 155.455673 77.676910 3.000000
      vertex 178.087036 116.678978 3.000000
      vertex 155.359207 77.712219 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 178.178833 116.634766 3.000000
      vertex 178.087036 116.678978 3.000000
      vertex 155.455673 77.676910 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 155.547455 77.632698 3.000000
      vertex 178.178833 116.634766 3.000000
      vertex 155.455673 77.676910 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 178.275299 116.599457 3.000000
      vertex 178.178833 116.634766 3.000000
      vertex 155.547455 77.632698 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 155.634033 77.580101 3.000000
      vertex 178.275299 116.599457 3.000000
      vertex 155.547455 77.632698 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 178.375916 116.573586 3.000000
      vertex 178.275299 116.599457 3.000000
      vertex 155.634033 77.580101 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 155.714859 77.519661 3.000000
      vertex 178.375916 116.573586 3.000000
      vertex 155.634033 77.580101 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 178.480179 116.557671 3.000000
      vertex 178.375916 116.573586 3.000000
      vertex 155.714859 77.519661 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 155.789429 77.451889 3.000000
      vertex 178.480179 116.557671 3.000000
      vertex 155.714859 77.519661 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 178.587540 116.552254 3.000000
      vertex 178.480179 116.557671 3.000000
      vertex 155.789429 77.451889 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 155.857193 77.377327 3.000000
      vertex 178.587540 116.552254 3.000000
      vertex 155.789429 77.451889 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 182.395859 116.439316 3.000000
      vertex 178.587540 116.552254 3.000000
      vertex 155.857193 77.377327 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 155.917648 77.296494 3.000000
      vertex 182.395859 116.439316 3.000000
      vertex 155.857193 77.377327 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 155.970245 77.209923 3.000000
      vertex 182.395859 116.439316 3.000000
      vertex 155.917648 77.296494 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 157.924652 74.011238 3.000000
      vertex 182.395859 116.439316 3.000000
      vertex 155.970245 77.209923 3.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 156.014450 77.118134 3.000000
      vertex 157.924652 74.011238 3.000000
      vertex 155.970245 77.209923 3.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 156.049759 77.021667 3.000000
      vertex 157.924652 74.011238 3.000000
      vertex 156.014450 77.118134 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 157.924652 74.011238 3.000000
      vertex 156.049759 77.021667 3.000000
      vertex 156.075638 76.921036 3.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 156.091553 76.816788 3.000000
      vertex 157.924652 74.011238 3.000000
      vertex 156.075638 76.921036 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 62.186310 201.179642 3.000000
      vertex 59.755661 200.686371 3.000000
      vertex 98.936775 201.968033 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.832527 201.983948 3.000000
      vertex 62.186310 201.179642 3.000000
      vertex 98.936775 201.968033 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 64.587700 201.649551 3.000000
      vertex 62.186310 201.179642 3.000000
      vertex 98.832527 201.983948 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 66.960068 202.096146 3.000000
      vertex 64.587700 201.649551 3.000000
      vertex 98.832527 201.983948 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 69.303680 202.519470 3.000000
      vertex 66.960068 202.096146 3.000000
      vertex 98.832527 201.983948 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 71.618774 202.919556 3.000000
      vertex 69.303680 202.519470 3.000000
      vertex 98.832527 201.983948 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 73.905602 203.296448 3.000000
      vertex 71.618774 202.919556 3.000000
      vertex 98.832527 201.983948 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.731895 202.009811 3.000000
      vertex 73.905602 203.296448 3.000000
      vertex 98.832527 201.983948 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 76.164421 203.650192 3.000000
      vertex 73.905602 203.296448 3.000000
      vertex 98.731895 202.009811 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 78.395470 203.980820 3.000000
      vertex 76.164421 203.650192 3.000000
      vertex 98.731895 202.009811 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.635429 202.045120 3.000000
      vertex 78.395470 203.980820 3.000000
      vertex 98.731895 202.009811 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 80.599014 204.288376 3.000000
      vertex 78.395470 203.980820 3.000000
      vertex 98.635429 202.045120 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.543640 202.089340 3.000000
      vertex 80.599014 204.288376 3.000000
      vertex 98.635429 202.045120 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.457069 202.141937 3.000000
      vertex 80.599014 204.288376 3.000000
      vertex 98.543640 202.089340 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 80.599014 204.288376 3.000000
      vertex 98.457069 202.141937 3.000000
      vertex 98.376236 202.202377 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.301674 202.270157 3.000000
      vertex 80.599014 204.288376 3.000000
      vertex 98.376236 202.202377 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.233902 202.344711 3.000000
      vertex 80.599014 204.288376 3.000000
      vertex 98.301674 202.270157 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 80.599014 204.288376 3.000000
      vertex 98.233902 202.344711 3.000000
      vertex 98.173462 202.425552 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.120865 202.512115 3.000000
      vertex 80.599014 204.288376 3.000000
      vertex 98.173462 202.425552 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.076653 202.603897 3.000000
      vertex 80.599014 204.288376 3.000000
      vertex 98.120865 202.512115 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 80.599014 204.288376 3.000000
      vertex 98.076653 202.603897 3.000000
      vertex 98.041344 202.700378 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.015465 202.800995 3.000000
      vertex 80.599014 204.288376 3.000000
      vertex 98.041344 202.700378 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 97.999557 202.905258 3.000000
      vertex 80.599014 204.288376 3.000000
      vertex 98.015465 202.800995 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 80.599014 204.288376 3.000000
      vertex 97.999557 202.905258 3.000000
      vertex 97.994133 203.012619 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 97.999557 203.119965 3.000000
      vertex 80.599014 204.288376 3.000000
      vertex 97.994133 203.012619 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.015465 203.224228 3.000000
      vertex 80.599014 204.288376 3.000000
      vertex 97.999557 203.119965 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 80.599014 204.288376 3.000000
      vertex 98.015465 203.224228 3.000000
      vertex 98.041344 203.324844 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.076653 203.421326 3.000000
      vertex 80.599014 204.288376 3.000000
      vertex 98.041344 203.324844 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.120865 203.513107 3.000000
      vertex 80.599014 204.288376 3.000000
      vertex 98.076653 203.421326 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 80.599014 204.288376 3.000000
      vertex 98.120865 203.513107 3.000000
      vertex 98.173462 203.599670 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.233902 203.680511 3.000000
      vertex 80.599014 204.288376 3.000000
      vertex 98.173462 203.599670 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.301674 203.755081 3.000000
      vertex 80.599014 204.288376 3.000000
      vertex 98.233902 203.680511 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 80.599014 204.288376 3.000000
      vertex 98.301674 203.755081 3.000000
      vertex 98.376236 203.822845 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.457069 203.883286 3.000000
      vertex 80.599014 204.288376 3.000000
      vertex 98.376236 203.822845 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.543640 203.935883 3.000000
      vertex 80.599014 204.288376 3.000000
      vertex 98.457069 203.883286 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 80.599014 204.288376 3.000000
      vertex 98.543640 203.935883 3.000000
      vertex 98.635429 203.980103 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.731895 204.015411 3.000000
      vertex 80.599014 204.288376 3.000000
      vertex 98.635429 203.980103 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 98.832527 204.041275 3.000000
      vertex 80.599014 204.288376 3.000000
      vertex 98.731895 204.015411 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 80.599014 204.288376 3.000000
      vertex 98.832527 204.041275 3.000000
      vertex 98.936775 204.057190 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 99.044136 204.062607 3.000000
      vertex 80.599014 204.288376 3.000000
      vertex 98.936775 204.057190 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 82.775291 204.572906 3.000000
      vertex 80.599014 204.288376 3.000000
      vertex 99.044136 204.062607 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 84.924553 204.834427 3.000000
      vertex 82.775291 204.572906 3.000000
      vertex 99.044136 204.062607 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 87.047050 205.073013 3.000000
      vertex 84.924553 204.834427 3.000000
      vertex 99.044136 204.062607 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 89.143036 205.288681 3.000000
      vertex 87.047050 205.073013 3.000000
      vertex 99.044136 204.062607 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 91.212761 205.481461 3.000000
      vertex 89.143036 205.288681 3.000000
      vertex 99.044136 204.062607 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 93.256470 205.651428 3.000000
      vertex 91.212761 205.481461 3.000000
      vertex 99.044136 204.062607 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 95.274414 205.798599 3.000000
      vertex 93.256470 205.651428 3.000000
      vertex 99.044136 204.062607 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 97.266846 205.923019 3.000000
      vertex 95.274414 205.798599 3.000000
      vertex 99.044136 204.062607 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 99.234016 206.024719 3.000000
      vertex 97.266846 205.923019 3.000000
      vertex 99.044136 204.062607 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 99.151489 204.057190 3.000000
      vertex 99.234016 206.024719 3.000000
      vertex 99.044136 204.062607 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 99.255745 204.041275 3.000000
      vertex 99.234016 206.024719 3.000000
      vertex 99.151489 204.057190 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 99.234016 206.024719 3.000000
      vertex 99.255745 204.041275 3.000000
      vertex 99.356377 204.015411 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 99.452843 203.980103 3.000000
      vertex 99.234016 206.024719 3.000000
      vertex 99.356377 204.015411 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 99.544624 203.935883 3.000000
      vertex 99.234016 206.024719 3.000000
      vertex 99.452843 203.980103 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 101.176178 206.103760 3.000000
      vertex 99.234016 206.024719 3.000000
      vertex 99.544624 203.935883 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 99.631203 203.883286 3.000000
      vertex 101.176178 206.103760 3.000000
      vertex 99.544624 203.935883 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 99.712036 203.822845 3.000000
      vertex 101.176178 206.103760 3.000000
      vertex 99.631203 203.883286 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 101.176178 206.103760 3.000000
      vertex 99.712036 203.822845 3.000000
      vertex 99.786598 203.755081 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 99.854362 203.680511 3.000000
      vertex 101.176178 206.103760 3.000000
      vertex 99.786598 203.755081 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 99.914810 203.599670 3.000000
      vertex 101.176178 206.103760 3.000000
      vertex 99.854362 203.680511 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 101.176178 206.103760 3.000000
      vertex 99.914810 203.599670 3.000000
      vertex 99.967407 203.513107 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 100.011620 203.421326 3.000000
      vertex 101.176178 206.103760 3.000000
      vertex 99.967407 203.513107 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 103.093575 206.160156 3.000000
      vertex 101.176178 206.103760 3.000000
      vertex 100.011620 203.421326 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 100.046928 203.324844 3.000000
      vertex 103.093575 206.160156 3.000000
      vertex 100.011620 203.421326 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 100.072800 203.224228 3.000000
      vertex 103.093575 206.160156 3.000000
      vertex 100.046928 203.324844 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 155.643661 192.834167 3.000000
      vertex 153.247269 192.693253 3.000000
      vertex 153.252701 192.585907 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 153.247269 192.478546 3.000000
      vertex 155.643661 192.834167 3.000000
      vertex 153.252701 192.585907 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 153.231369 192.374298 3.000000
      vertex 155.643661 192.834167 3.000000
      vertex 153.247269 192.478546 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 155.643661 192.834167 3.000000
      vertex 153.231369 192.374298 3.000000
      vertex 153.205490 192.273666 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 153.170181 192.177200 3.000000
      vertex 155.643661 192.834167 3.000000
      vertex 153.205490 192.273666 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 153.125961 192.085403 3.000000
      vertex 155.643661 192.834167 3.000000
      vertex 153.170181 192.177200 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 155.643661 192.834167 3.000000
      vertex 153.125961 192.085403 3.000000
      vertex 153.073380 191.998840 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 153.012924 191.917999 3.000000
      vertex 155.643661 192.834167 3.000000
      vertex 153.073380 191.998840 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 152.945160 191.843445 3.000000
      vertex 155.643661 192.834167 3.000000
      vertex 153.012924 191.917999 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 155.643661 192.834167 3.000000
      vertex 152.945160 191.843445 3.000000
      vertex 152.870590 191.775665 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 152.789764 191.715225 3.000000
      vertex 155.643661 192.834167 3.000000
      vertex 152.870590 191.775665 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 152.703186 191.662628 3.000000
      vertex 155.643661 192.834167 3.000000
      vertex 152.789764 191.715225 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 155.643661 192.834167 3.000000
      vertex 152.703186 191.662628 3.000000
      vertex 152.611404 191.618423 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 141.498383 201.126816 3.000000
      vertex 140.192825 201.561539 3.000000
      vertex 151.235214 192.177200 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.199905 192.273666 3.000000
      vertex 141.498383 201.126816 3.000000
      vertex 151.235214 192.177200 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 142.786942 200.672363 3.000000
      vertex 141.498383 201.126816 3.000000
      vertex 151.199905 192.273666 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 144.058670 200.198151 3.000000
      vertex 142.786942 200.672363 3.000000
      vertex 151.199905 192.273666 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.174026 192.374298 3.000000
      vertex 144.058670 200.198151 3.000000
      vertex 151.199905 192.273666 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 145.313721 199.704163 3.000000
      vertex 144.058670 200.198151 3.000000
      vertex 151.174026 192.374298 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.158112 192.478546 3.000000
      vertex 145.313721 199.704163 3.000000
      vertex 151.174026 192.374298 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.152695 192.585907 3.000000
      vertex 145.313721 199.704163 3.000000
      vertex 151.158112 192.478546 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 146.552231 199.190353 3.000000
      vertex 145.313721 199.704163 3.000000
      vertex 151.152695 192.585907 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.158112 192.693253 3.000000
      vertex 146.552231 199.190353 3.000000
      vertex 151.152695 192.585907 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 147.774384 198.656693 3.000000
      vertex 146.552231 199.190353 3.000000
      vertex 151.158112 192.693253 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.174026 192.797516 3.000000
      vertex 147.774384 198.656693 3.000000
      vertex 151.158112 192.693253 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.199905 192.898148 3.000000
      vertex 147.774384 198.656693 3.000000
      vertex 151.174026 192.797516 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 148.980331 198.103134 3.000000
      vertex 147.774384 198.656693 3.000000
      vertex 151.199905 192.898148 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.235214 192.994614 3.000000
      vertex 148.980331 198.103134 3.000000
      vertex 151.199905 192.898148 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.279419 193.086395 3.000000
      vertex 148.980331 198.103134 3.000000
      vertex 151.235214 192.994614 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 150.170212 197.529663 3.000000
      vertex 148.980331 198.103134 3.000000
      vertex 151.279419 193.086395 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.332016 193.172974 3.000000
      vertex 150.170212 197.529663 3.000000
      vertex 151.279419 193.086395 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.392471 193.253799 3.000000
      vertex 150.170212 197.529663 3.000000
      vertex 151.332016 193.172974 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 150.170212 197.529663 3.000000
      vertex 151.392471 193.253799 3.000000
      vertex 151.460236 193.328369 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.344193 196.936234 3.000000
      vertex 150.170212 197.529663 3.000000
      vertex 151.460236 193.328369 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.534805 193.396133 3.000000
      vertex 151.344193 196.936234 3.000000
      vertex 151.460236 193.328369 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.615631 193.456573 3.000000
      vertex 151.344193 196.936234 3.000000
      vertex 151.534805 193.396133 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.344193 196.936234 3.000000
      vertex 151.615631 193.456573 3.000000
      vertex 151.702209 193.509171 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.793991 193.553391 3.000000
      vertex 151.344193 196.936234 3.000000
      vertex 151.702209 193.509171 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 152.502426 196.322800 3.000000
      vertex 151.344193 196.936234 3.000000
      vertex 151.793991 193.553391 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 151.890457 193.588699 3.000000
      vertex 152.502426 196.322800 3.000000
      vertex 151.793991 193.553391 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 151.991089 193.614578 3.000000
      vertex 152.502426 196.322800 3.000000
      vertex 151.890457 193.588699 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 152.502426 196.322800 3.000000
      vertex 151.991089 193.614578 3.000000
      vertex 152.095337 193.630478 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 152.202698 193.635910 3.000000
      vertex 152.502426 196.322800 3.000000
      vertex 152.095337 193.630478 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 154.073029 195.471695 3.000000
      vertex 152.502426 196.322800 3.000000
      vertex 152.202698 193.635910 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 154.418381 195.252945 3.000000
      vertex 154.073029 195.471695 3.000000
      vertex 152.202698 193.635910 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 154.726730 194.993134 3.000000
      vertex 154.418381 195.252945 3.000000
      vertex 152.202698 193.635910 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 154.995285 194.696945 3.000000
      vertex 154.726730 194.993134 3.000000
      vertex 152.202698 193.635910 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 155.221268 194.369049 3.000000
      vertex 154.995285 194.696945 3.000000
      vertex 152.202698 193.635910 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 155.401886 194.014145 3.000000
      vertex 155.221268 194.369049 3.000000
      vertex 152.202698 193.635910 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 155.534348 193.636917 3.000000
      vertex 155.401886 194.014145 3.000000
      vertex 152.202698 193.635910 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 152.310059 193.630478 3.000000
      vertex 155.534348 193.636917 3.000000
      vertex 152.202698 193.635910 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 152.414307 193.614578 3.000000
      vertex 155.534348 193.636917 3.000000
      vertex 152.310059 193.630478 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 155.534348 193.636917 3.000000
      vertex 152.414307 193.614578 3.000000
      vertex 152.514938 193.588699 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 152.611404 193.553391 3.000000
      vertex 155.534348 193.636917 3.000000
      vertex 152.514938 193.588699 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 152.703186 193.509171 3.000000
      vertex 155.534348 193.636917 3.000000
      vertex 152.611404 193.553391 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 155.534348 193.636917 3.000000
      vertex 152.703186 193.509171 3.000000
      vertex 152.789764 193.456573 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 152.870590 193.396133 3.000000
      vertex 155.534348 193.636917 3.000000
      vertex 152.789764 193.456573 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 152.945160 193.328369 3.000000
      vertex 155.534348 193.636917 3.000000
      vertex 152.870590 193.396133 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 155.534348 193.636917 3.000000
      vertex 152.945160 193.328369 3.000000
      vertex 153.012924 193.253799 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 153.073380 193.172974 3.000000
      vertex 155.534348 193.636917 3.000000
      vertex 153.012924 193.253799 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 153.125961 193.086395 3.000000
      vertex 155.534348 193.636917 3.000000
      vertex 153.073380 193.172974 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 155.534348 193.636917 3.000000
      vertex 153.125961 193.086395 3.000000
      vertex 153.170181 192.994614 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 153.205490 192.898148 3.000000
      vertex 155.534348 193.636917 3.000000
      vertex 153.170181 192.994614 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 155.615860 193.242035 3.000000
      vertex 155.534348 193.636917 3.000000
      vertex 153.205490 192.898148 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 153.231369 192.797516 3.000000
      vertex 155.615860 193.242035 3.000000
      vertex 153.205490 192.898148 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 155.643661 192.834167 3.000000
      vertex 155.615860 193.242035 3.000000
      vertex 153.231369 192.797516 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 153.247269 192.693253 3.000000
      vertex 155.643661 192.834167 3.000000
      vertex 153.231369 192.797516 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 92.314682 106.466446 3.000000
      vertex 34.295017 110.440910 3.000000
      vertex 34.300442 110.333557 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 34.295017 110.226204 3.000000
      vertex 92.314682 106.466446 3.000000
      vertex 34.300442 110.333557 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 34.279106 110.121948 3.000000
      vertex 92.314682 106.466446 3.000000
      vertex 34.295017 110.226204 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 92.314682 106.466446 3.000000
      vertex 34.279106 110.121948 3.000000
      vertex 34.253235 110.021317 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 34.217926 109.924850 3.000000
      vertex 92.314682 106.466446 3.000000
      vertex 34.253235 110.021317 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 34.173710 109.833069 3.000000
      vertex 92.314682 106.466446 3.000000
      vertex 34.217926 109.924850 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 92.314682 106.466446 3.000000
      vertex 34.173710 109.833069 3.000000
      vertex 34.121117 109.746490 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.343864 106.466446 3.000000
      vertex 92.314682 106.466446 3.000000
      vertex 34.121117 109.746490 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 34.060669 109.665665 3.000000
      vertex 32.343864 106.466446 3.000000
      vertex 34.121117 109.746490 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 33.992901 109.591095 3.000000
      vertex 32.343864 106.466446 3.000000
      vertex 34.060669 109.665665 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.343864 106.466446 3.000000
      vertex 33.992901 109.591095 3.000000
      vertex 33.918339 109.523331 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 33.837505 109.462883 3.000000
      vertex 32.343864 106.466446 3.000000
      vertex 33.918339 109.523331 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 33.750931 109.410286 3.000000
      vertex 32.343864 106.466446 3.000000
      vertex 33.837505 109.462883 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.343864 106.466446 3.000000
      vertex 33.750931 109.410286 3.000000
      vertex 33.659145 109.366074 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 33.562675 109.330765 3.000000
      vertex 32.343864 106.466446 3.000000
      vertex 33.659145 109.366074 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 33.462051 109.304893 3.000000
      vertex 32.343864 106.466446 3.000000
      vertex 33.562675 109.330765 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.343864 106.466446 3.000000
      vertex 33.462051 109.304893 3.000000
      vertex 33.357796 109.288979 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 33.250439 109.283562 3.000000
      vertex 32.343864 106.466446 3.000000
      vertex 33.357796 109.288979 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 32.037132 106.481934 3.000000
      vertex 32.343864 106.466446 3.000000
      vertex 33.250439 109.283562 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 31.739260 106.527397 3.000000
      vertex 32.037132 106.481934 3.000000
      vertex 33.250439 109.283562 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 31.451757 106.601318 3.000000
      vertex 31.739260 106.527397 3.000000
      vertex 33.250439 109.283562 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 31.176132 106.702202 3.000000
      vertex 31.451757 106.601318 3.000000
      vertex 33.250439 109.283562 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 30.913891 106.828529 3.000000
      vertex 31.176132 106.702202 3.000000
      vertex 33.250439 109.283562 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 30.666540 106.978798 3.000000
      vertex 30.913891 106.828529 3.000000
      vertex 33.250439 109.283562 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 30.435591 107.151497 3.000000
      vertex 30.666540 106.978798 3.000000
      vertex 33.250439 109.283562 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 30.222549 107.345123 3.000000
      vertex 30.435591 107.151497 3.000000
      vertex 33.250439 109.283562 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 30.028925 107.558167 3.000000
      vertex 30.222549 107.345123 3.000000
      vertex 33.250439 109.283562 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 29.856224 107.789116 3.000000
      vertex 30.028925 107.558167 3.000000
      vertex 33.250439 109.283562 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 29.705956 108.036461 3.000000
      vertex 29.856224 107.789116 3.000000
      vertex 33.250439 109.283562 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 29.579628 108.298706 3.000000
      vertex 29.705956 108.036461 3.000000
      vertex 33.250439 109.283562 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 29.478748 108.574333 3.000000
      vertex 29.579628 108.298706 3.000000
      vertex 33.250439 109.283562 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 29.404823 108.861832 3.000000
      vertex 29.478748 108.574333 3.000000
      vertex 33.250439 109.283562 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 29.359362 109.159706 3.000000
      vertex 29.404823 108.861832 3.000000
      vertex 33.250439 109.283562 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 33.143082 109.288979 3.000000
      vertex 29.359362 109.159706 3.000000
      vertex 33.250439 109.283562 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 33.038826 109.304893 3.000000
      vertex 29.359362 109.159706 3.000000
      vertex 33.143082 109.288979 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 29.359362 109.159706 3.000000
      vertex 33.038826 109.304893 3.000000
      vertex 32.938202 109.330765 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.841732 109.366074 3.000000
      vertex 29.359362 109.159706 3.000000
      vertex 32.938202 109.330765 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.749947 109.410286 3.000000
      vertex 29.359362 109.159706 3.000000
      vertex 32.841732 109.366074 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 29.359362 109.159706 3.000000
      vertex 32.749947 109.410286 3.000000
      vertex 32.663376 109.462883 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.582542 109.523331 3.000000
      vertex 29.359362 109.159706 3.000000
      vertex 32.663376 109.462883 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.507977 109.591095 3.000000
      vertex 29.359362 109.159706 3.000000
      vertex 32.582542 109.523331 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 29.359362 109.159706 3.000000
      vertex 32.507977 109.591095 3.000000
      vertex 32.440208 109.665665 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.379765 109.746490 3.000000
      vertex 29.359362 109.159706 3.000000
      vertex 32.440208 109.665665 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.327168 109.833069 3.000000
      vertex 29.359362 109.159706 3.000000
      vertex 32.379765 109.746490 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 29.359362 109.159706 3.000000
      vertex 32.327168 109.833069 3.000000
      vertex 32.282955 109.924850 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 29.343874 109.466438 3.000000
      vertex 29.359362 109.159706 3.000000
      vertex 32.282955 109.924850 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.247646 110.021317 3.000000
      vertex 29.343874 109.466438 3.000000
      vertex 32.282955 109.924850 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.221771 110.121948 3.000000
      vertex 29.343874 109.466438 3.000000
      vertex 32.247646 110.021317 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 29.343874 109.466438 3.000000
      vertex 32.221771 110.121948 3.000000
      vertex 32.205860 110.226204 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.200439 110.333557 3.000000
      vertex 29.343874 109.466438 3.000000
      vertex 32.205860 110.226204 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.205860 110.440910 3.000000
      vertex 29.343874 109.466438 3.000000
      vertex 32.200439 110.333557 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 29.343874 109.466438 3.000000
      vertex 32.205860 110.440910 3.000000
      vertex 32.221771 110.545166 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.247646 110.645798 3.000000
      vertex 29.343874 109.466438 3.000000
      vertex 32.221771 110.545166 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.282955 110.742264 3.000000
      vertex 29.343874 109.466438 3.000000
      vertex 32.247646 110.645798 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 29.343874 109.466438 3.000000
      vertex 32.282955 110.742264 3.000000
      vertex 32.327168 110.834053 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.379765 110.920624 3.000000
      vertex 29.343874 109.466438 3.000000
      vertex 32.327168 110.834053 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.440208 111.001457 3.000000
      vertex 29.343874 109.466438 3.000000
      vertex 32.379765 110.920624 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 29.343874 109.466438 3.000000
      vertex 32.440208 111.001457 3.000000
      vertex 32.507977 111.076019 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.582542 111.143791 3.000000
      vertex 29.343874 109.466438 3.000000
      vertex 32.507977 111.076019 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.663376 111.204239 3.000000
      vertex 29.343874 109.466438 3.000000
      vertex 32.582542 111.143791 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 29.343874 109.466438 3.000000
      vertex 32.663376 111.204239 3.000000
      vertex 32.749947 111.256828 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 29.343874 190.965912 3.000000
      vertex 29.343874 109.466438 3.000000
      vertex 32.749947 111.256828 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 32.841732 111.301048 3.000000
      vertex 29.343874 190.965912 3.000000
      vertex 32.749947 111.256828 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 92.314682 106.466446 3.000000
      vertex 33.462051 111.362228 3.000000
      vertex 33.562675 111.336357 3.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 33.659145 111.301048 3.000000
      vertex 92.314682 106.466446 3.000000
      vertex 33.562675 111.336357 3.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 33.750931 111.256828 3.000000
      vertex 92.314682 106.466446 3.000000
      vertex 33.659145 111.301048 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 92.314682 106.466446 3.000000
      vertex 33.750931 111.256828 3.000000
      vertex 33.837505 111.204239 3.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 33.918339 111.143791 3.000000
      vertex 92.314682 106.466446 3.000000
      vertex 33.837505 111.204239 3.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 33.992901 111.076019 3.000000
      vertex 92.314682 106.466446 3.000000
      vertex 33.918339 111.143791 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 92.314682 106.466446 3.000000
      vertex 33.992901 111.076019 3.000000
      vertex 34.060669 111.001457 3.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 34.121117 110.920624 3.000000
      vertex 92.314682 106.466446 3.000000
      vertex 34.060669 111.001457 3.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 34.173710 110.834053 3.000000
      vertex 92.314682 106.466446 3.000000
      vertex 34.121117 110.920624 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 92.314682 106.466446 3.000000
      vertex 34.173710 110.834053 3.000000
      vertex 34.217926 110.742264 3.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 34.253235 110.645798 3.000000
      vertex 92.314682 106.466446 3.000000
      vertex 34.217926 110.742264 3.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 34.279106 110.545166 3.000000
      vertex 92.314682 106.466446 3.000000
      vertex 34.253235 110.645798 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 92.314682 106.466446 3.000000
      vertex 34.279106 110.545166 3.000000
      vertex 34.295017 110.440910 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 179.637527 117.602249 3.000000
      vertex 179.632111 117.494896 3.000000
      vertex 182.724686 117.279236 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 182.775024 117.568314 3.000000
      vertex 179.637527 117.602249 3.000000
      vertex 182.724686 117.279236 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 179.632111 117.709610 3.000000
      vertex 179.637527 117.602249 3.000000
      vertex 182.775024 117.568314 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 182.796646 117.858521 3.000000
      vertex 179.632111 117.709610 3.000000
      vertex 182.775024 117.568314 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 179.616196 117.813866 3.000000
      vertex 179.632111 117.709610 3.000000
      vertex 182.796646 117.858521 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 182.790100 118.147789 3.000000
      vertex 179.616196 117.813866 3.000000
      vertex 182.796646 117.858521 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 182.755951 118.434067 3.000000
      vertex 179.616196 117.813866 3.000000
      vertex 182.790100 118.147789 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 179.632111 117.494896 3.000000
      vertex 179.616196 117.390640 3.000000
      vertex 182.535660 116.712677 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 182.645081 116.993332 3.000000
      vertex 179.632111 117.494896 3.000000
      vertex 182.535660 116.712677 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 182.724686 117.279236 3.000000
      vertex 179.632111 117.494896 3.000000
      vertex 182.645081 116.993332 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 182.395859 116.439316 3.000000
      vertex 182.535660 116.712677 3.000000
      vertex 179.616196 117.390640 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 179.590332 117.290016 3.000000
      vertex 182.395859 116.439316 3.000000
      vertex 179.616196 117.390640 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 179.555023 117.193542 3.000000
      vertex 182.395859 116.439316 3.000000
      vertex 179.590332 117.290016 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 182.395859 116.439316 3.000000
      vertex 179.555023 117.193542 3.000000
      vertex 179.510803 117.101761 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 179.458206 117.015190 3.000000
      vertex 182.395859 116.439316 3.000000
      vertex 179.510803 117.101761 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 179.397766 116.934357 3.000000
      vertex 182.395859 116.439316 3.000000
      vertex 179.458206 117.015190 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 182.395859 116.439316 3.000000
      vertex 179.397766 116.934357 3.000000
      vertex 179.330002 116.859787 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 179.255432 116.792023 3.000000
      vertex 182.395859 116.439316 3.000000
      vertex 179.330002 116.859787 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 179.174606 116.731575 3.000000
      vertex 182.395859 116.439316 3.000000
      vertex 179.255432 116.792023 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 182.395859 116.439316 3.000000
      vertex 179.174606 116.731575 3.000000
      vertex 179.088028 116.678978 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 178.996246 116.634766 3.000000
      vertex 182.395859 116.439316 3.000000
      vertex 179.088028 116.678978 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 178.899765 116.599457 3.000000
      vertex 182.395859 116.439316 3.000000
      vertex 178.996246 116.634766 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 182.395859 116.439316 3.000000
      vertex 178.899765 116.599457 3.000000
      vertex 178.799149 116.573586 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 178.694885 116.557671 3.000000
      vertex 182.395859 116.439316 3.000000
      vertex 178.799149 116.573586 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 178.587540 116.552254 3.000000
      vertex 182.395859 116.439316 3.000000
      vertex 178.694885 116.557671 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 178.000473 116.731575 3.000000
      vertex 177.919632 116.792023 3.000000
      vertex 93.206390 106.331635 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 93.481888 106.230797 3.000000
      vertex 178.000473 116.731575 3.000000
      vertex 93.206390 106.331635 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 93.744011 106.104530 3.000000
      vertex 178.000473 116.731575 3.000000
      vertex 93.481888 106.230797 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 160.853790 126.227402 3.000000
      vertex 93.206390 106.331635 3.000000
      vertex 177.919632 116.792023 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 177.845078 116.859787 3.000000
      vertex 160.853790 126.227402 3.000000
      vertex 177.919632 116.792023 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 167.983627 123.939049 3.000000
      vertex 177.542953 117.494896 3.000000
      vertex 177.537537 117.602249 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 177.542953 117.709610 3.000000
      vertex 167.983627 123.939049 3.000000
      vertex 177.537537 117.602249 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 177.558868 117.813866 3.000000
      vertex 167.983627 123.939049 3.000000
      vertex 177.542953 117.709610 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 167.983627 123.939049 3.000000
      vertex 177.558868 117.813866 3.000000
      vertex 177.584747 117.914490 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 177.620056 118.010956 3.000000
      vertex 167.983627 123.939049 3.000000
      vertex 177.584747 117.914490 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 175.746231 123.756653 3.000000
      vertex 167.983627 123.939049 3.000000
      vertex 177.620056 118.010956 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 177.664261 118.102745 3.000000
      vertex 175.746231 123.756653 3.000000
      vertex 177.620056 118.010956 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 177.716858 118.189316 3.000000
      vertex 175.746231 123.756653 3.000000
      vertex 177.664261 118.102745 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 176.706894 123.193161 3.000000
      vertex 175.746231 123.756653 3.000000
      vertex 177.716858 118.189316 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 177.777298 118.270149 3.000000
      vertex 176.706894 123.193161 3.000000
      vertex 177.716858 118.189316 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 177.845078 118.344711 3.000000
      vertex 176.706894 123.193161 3.000000
      vertex 177.777298 118.270149 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 177.691559 122.619560 3.000000
      vertex 176.706894 123.193161 3.000000
      vertex 177.845078 118.344711 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 177.919632 118.412483 3.000000
      vertex 177.691559 122.619560 3.000000
      vertex 177.845078 118.344711 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 178.000473 118.472931 3.000000
      vertex 177.691559 122.619560 3.000000
      vertex 177.919632 118.412483 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 177.691559 122.619560 3.000000
      vertex 178.000473 118.472931 3.000000
      vertex 178.087036 118.525520 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 178.700302 122.035522 3.000000
      vertex 177.691559 122.619560 3.000000
      vertex 178.087036 118.525520 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 178.178833 118.569740 3.000000
      vertex 178.700302 122.035522 3.000000
      vertex 178.087036 118.525520 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 178.275299 118.605049 3.000000
      vertex 178.700302 122.035522 3.000000
      vertex 178.178833 118.569740 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 178.700302 122.035522 3.000000
      vertex 178.275299 118.605049 3.000000
      vertex 178.375916 118.630920 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 178.480179 118.646828 3.000000
      vertex 178.700302 122.035522 3.000000
      vertex 178.375916 118.630920 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 178.587540 118.652252 3.000000
      vertex 178.700302 122.035522 3.000000
      vertex 178.480179 118.646828 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 178.587540 118.652252 3.000000
      vertex 178.694885 118.646828 3.000000
      vertex 182.694733 118.715286 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 182.607010 118.989403 3.000000
      vertex 178.587540 118.652252 3.000000
      vertex 182.694733 118.715286 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 182.493332 119.254356 3.000000
      vertex 178.587540 118.652252 3.000000
      vertex 182.607010 118.989403 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 182.694733 118.715286 3.000000
      vertex 178.694885 118.646828 3.000000
      vertex 178.799149 118.630920 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 178.899765 118.605049 3.000000
      vertex 182.694733 118.715286 3.000000
      vertex 178.799149 118.630920 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 178.996246 118.569740 3.000000
      vertex 182.694733 118.715286 3.000000
      vertex 178.899765 118.605049 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 182.694733 118.715286 3.000000
      vertex 178.996246 118.569740 3.000000
      vertex 179.088028 118.525520 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 179.174606 118.472931 3.000000
      vertex 182.694733 118.715286 3.000000
      vertex 179.088028 118.525520 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 179.255432 118.412483 3.000000
      vertex 182.694733 118.715286 3.000000
      vertex 179.174606 118.472931 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 182.694733 118.715286 3.000000
      vertex 179.255432 118.412483 3.000000
      vertex 179.330002 118.344711 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 179.397766 118.270149 3.000000
      vertex 182.694733 118.715286 3.000000
      vertex 179.330002 118.344711 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 179.458206 118.189316 3.000000
      vertex 182.694733 118.715286 3.000000
      vertex 179.397766 118.270149 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 182.694733 118.715286 3.000000
      vertex 179.458206 118.189316 3.000000
      vertex 179.510803 118.102745 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 179.555023 118.010956 3.000000
      vertex 182.694733 118.715286 3.000000
      vertex 179.510803 118.102745 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 179.590332 117.914490 3.000000
      vertex 182.694733 118.715286 3.000000
      vertex 179.555023 118.010956 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 182.755951 118.434067 3.000000
      vertex 182.694733 118.715286 3.000000
      vertex 179.590332 117.914490 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 179.616196 117.813866 3.000000
      vertex 182.755951 118.434067 3.000000
      vertex 179.590332 117.914490 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 178.587540 118.652252 3.000000
      vertex 182.493332 119.254356 3.000000
      vertex 182.354263 119.508080 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 182.190323 119.748520 3.000000
      vertex 178.587540 118.652252 3.000000
      vertex 182.354263 119.508080 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 182.002090 119.973618 3.000000
      vertex 178.587540 118.652252 3.000000
      vertex 182.190323 119.748520 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 178.587540 118.652252 3.000000
      vertex 182.002090 119.973618 3.000000
      vertex 181.790115 120.181313 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 181.554932 120.369553 3.000000
      vertex 178.587540 118.652252 3.000000
      vertex 181.790115 120.181313 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 181.297104 120.536278 3.000000
      vertex 178.587540 118.652252 3.000000
      vertex 181.554932 120.369553 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 178.587540 118.652252 3.000000
      vertex 181.297104 120.536278 3.000000
      vertex 178.700302 122.035522 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 167.983627 126.039055 3.000000
      vertex 167.435410 128.907394 3.000000
      vertex 166.731552 129.381241 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 162.035110 126.676598 3.000000
      vertex 167.983627 126.039055 3.000000
      vertex 166.731552 129.381241 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 161.979523 126.590630 3.000000
      vertex 167.983627 126.039055 3.000000
      vertex 162.035110 126.676598 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 163.950409 129.993988 3.000000
      vertex 162.035110 126.676598 3.000000
      vertex 166.731552 129.381241 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 166.050415 129.848877 3.000000
      vertex 163.950409 129.993988 3.000000
      vertex 166.731552 129.381241 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 165.391861 130.310638 3.000000
      vertex 163.950409 129.993988 3.000000
      vertex 166.050415 129.848877 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 165.391861 130.310638 3.000000
      vertex 165.299744 130.368820 3.000000
      vertex 164.503815 130.444565 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 164.409225 130.408081 3.000000
      vertex 165.391861 130.310638 3.000000
      vertex 164.503815 130.444565 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 164.318451 130.362000 3.000000
      vertex 165.391861 130.310638 3.000000
      vertex 164.409225 130.408081 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 165.299744 130.368820 3.000000
      vertex 165.204086 130.415741 3.000000
      vertex 164.903992 130.490829 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 164.802322 130.494583 3.000000
      vertex 165.299744 130.368820 3.000000
      vertex 164.903992 130.490829 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 164.701187 130.488007 3.000000
      vertex 165.299744 130.368820 3.000000
      vertex 164.802322 130.494583 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 164.903992 130.490829 3.000000
      vertex 165.204086 130.415741 3.000000
      vertex 165.105698 130.451599 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 165.005386 130.476562 3.000000
      vertex 164.903992 130.490829 3.000000
      vertex 165.105698 130.451599 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 165.299744 130.368820 3.000000
      vertex 164.701187 130.488007 3.000000
      vertex 164.601410 130.471268 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 164.503815 130.444565 3.000000
      vertex 165.299744 130.368820 3.000000
      vertex 164.601410 130.471268 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 165.391861 130.310638 3.000000
      vertex 164.318451 130.362000 3.000000
      vertex 164.232300 130.306503 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 164.151611 130.241760 3.000000
      vertex 165.391861 130.310638 3.000000
      vertex 164.232300 130.306503 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 164.077179 130.167969 3.000000
      vertex 165.391861 130.310638 3.000000
      vertex 164.151611 130.241760 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 165.391861 130.310638 3.000000
      vertex 164.077179 130.167969 3.000000
      vertex 164.009842 130.085327 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 163.950409 129.993988 3.000000
      vertex 165.391861 130.310638 3.000000
      vertex 164.009842 130.085327 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 167.983627 126.039055 3.000000
      vertex 161.979523 126.590630 3.000000
      vertex 161.916748 126.512222 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 161.847504 126.441544 3.000000
      vertex 167.983627 126.039055 3.000000
      vertex 161.916748 126.512222 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 161.772430 126.378792 3.000000
      vertex 167.983627 126.039055 3.000000
      vertex 161.847504 126.441544 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 167.983627 126.039055 3.000000
      vertex 161.772430 126.378792 3.000000
      vertex 161.692261 126.324142 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 161.607651 126.277786 3.000000
      vertex 167.983627 126.039055 3.000000
      vertex 161.692261 126.324142 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 161.519318 126.239899 3.000000
      vertex 167.983627 126.039055 3.000000
      vertex 161.607651 126.277786 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 167.983627 126.039055 3.000000
      vertex 161.519318 126.239899 3.000000
      vertex 161.427902 126.210670 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 161.334137 126.190285 3.000000
      vertex 167.983627 126.039055 3.000000
      vertex 161.427902 126.210670 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 161.238693 126.178917 3.000000
      vertex 167.983627 126.039055 3.000000
      vertex 161.334137 126.190285 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 167.983627 126.039055 3.000000
      vertex 161.238693 126.178917 3.000000
      vertex 161.142242 126.176765 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 93.206390 106.331635 3.000000
      vertex 160.853790 126.227402 3.000000
      vertex 160.760223 126.263924 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 160.669098 126.310570 3.000000
      vertex 93.206390 106.331635 3.000000
      vertex 160.760223 126.263924 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.178375 131.790039 3.000000
      vertex 93.206390 106.331635 3.000000
      vertex 160.669098 126.310570 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 93.206390 106.331635 3.000000
      vertex 151.178375 131.790039 3.000000
      vertex 151.092545 131.845535 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 151.014252 131.908188 3.000000
      vertex 93.206390 106.331635 3.000000
      vertex 151.092545 131.845535 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 150.943649 131.977310 3.000000
      vertex 93.206390 106.331635 3.000000
      vertex 151.014252 131.908188 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 93.206390 106.331635 3.000000
      vertex 150.943649 131.977310 3.000000
      vertex 150.880951 132.052216 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 150.826340 132.132233 3.000000
      vertex 93.206390 106.331635 3.000000
      vertex 150.880951 132.052216 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 150.779968 132.216675 3.000000
      vertex 93.206390 106.331635 3.000000
      vertex 150.826340 132.132233 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 93.206390 106.331635 3.000000
      vertex 150.779968 132.216675 3.000000
      vertex 150.742050 132.304855 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 150.712769 132.396088 3.000000
      vertex 93.206390 106.331635 3.000000
      vertex 150.742050 132.304855 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 109.054306 152.334106 3.000000
      vertex 150.692291 132.489685 3.000000
      vertex 150.680801 132.584991 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 150.678497 132.681290 3.000000
      vertex 109.054306 152.334106 3.000000
      vertex 150.680801 132.584991 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 150.685562 132.777908 3.000000
      vertex 109.054306 152.334106 3.000000
      vertex 150.678497 132.681290 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 109.054306 152.334106 3.000000
      vertex 150.685562 132.777908 3.000000
      vertex 150.702179 132.874176 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 150.728531 132.969391 3.000000
      vertex 109.054306 152.334106 3.000000
      vertex 150.702179 132.874176 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 150.764786 133.062897 3.000000
      vertex 109.054306 152.334106 3.000000
      vertex 150.728531 132.969391 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 109.054306 152.334106 3.000000
      vertex 150.764786 133.062897 3.000000
      vertex 150.811142 133.153976 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 155.444077 141.223419 3.000000
      vertex 155.578491 141.508118 3.000000
      vertex 155.665619 141.808502 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 155.704941 142.118973 3.000000
      vertex 155.444077 141.223419 3.000000
      vertex 155.665619 141.808502 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 155.695953 142.433929 3.000000
      vertex 155.444077 141.223419 3.000000
      vertex 155.704941 142.118973 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 155.444077 141.223419 3.000000
      vertex 155.695953 142.433929 3.000000
      vertex 155.656876 142.925613 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 124.013397 203.163162 3.000000
      vertex 121.603073 205.434021 3.000000
      vertex 120.043213 205.596252 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 118.464005 205.739258 3.000000
      vertex 124.013397 203.163162 3.000000
      vertex 120.043213 205.596252 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 116.865311 205.863083 3.000000
      vertex 124.013397 203.163162 3.000000
      vertex 118.464005 205.739258 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 124.013397 203.163162 3.000000
      vertex 116.865311 205.863083 3.000000
      vertex 115.246971 205.967773 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 113.608826 206.053345 3.000000
      vertex 124.013397 203.163162 3.000000
      vertex 115.246971 205.967773 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 100.072800 203.224228 3.000000
      vertex 124.013397 203.163162 3.000000
      vertex 113.608826 206.053345 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 111.950722 206.119843 3.000000
      vertex 100.072800 203.224228 3.000000
      vertex 113.608826 206.053345 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 110.272499 206.167313 3.000000
      vertex 100.072800 203.224228 3.000000
      vertex 111.950722 206.119843 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 100.072800 203.224228 3.000000
      vertex 110.272499 206.167313 3.000000
      vertex 108.573997 206.195755 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 106.855080 206.205231 3.000000
      vertex 100.072800 203.224228 3.000000
      vertex 108.573997 206.195755 3.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 1.000000
    outer loop
      vertex 104.986458 206.193970 3.000000
      vertex 100.072800 203.224228 3.000000
      vertex 106.855080 206.205231 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 100.072800 203.224228 3.000000
      vertex 104.986458 206.193970 3.000000
      vertex 103.093575 206.160156 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 178.000473 116.731575 3.000000
      vertex 93.744011 106.104530 3.000000
      vertex 93.991249 105.954330 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 94.222092 105.781708 3.000000
      vertex 178.000473 116.731575 3.000000
      vertex 93.991249 105.954330 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 94.435036 105.588165 3.000000
      vertex 178.000473 116.731575 3.000000
      vertex 94.222092 105.781708 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 178.000473 116.731575 3.000000
      vertex 94.435036 105.588165 3.000000
      vertex 94.628578 105.375221 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 94.801201 105.144379 3.000000
      vertex 178.000473 116.731575 3.000000
      vertex 94.628578 105.375221 3.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 1.000000
    outer loop
      vertex 94.951401 104.897141 3.000000
      vertex 178.000473 116.731575 3.000000
      vertex 94.801201 105.144379 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 95.077667 104.635017 3.000000
      vertex 95.178505 104.359512 3.000000
      vertex 119.744423 85.082497 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 122.156654 84.705185 3.000000
      vertex 95.077667 104.635017 3.000000
      vertex 119.744423 85.082497 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 1.000000
    outer loop
      vertex 124.595909 84.271599 3.000000
      vertex 95.077667 104.635017 3.000000
      vertex 122.156654 84.705185 3.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 117.355804 85.414551 3.000000
      vertex 119.744423 85.082497 3.000000
      vertex 95.178505 104.359512 3.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 95.252396 104.072144 3.000000
      vertex 117.355804 85.414551 3.000000
      vertex 95.178505 104.359512 3.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 114.987381 85.712395 3.000000
      vertex 117.355804 85.414551 3.000000
      vertex 95.252396 104.072144 3.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 95.297836 103.774406 3.000000
      vertex 114.987381 85.712395 3.000000
      vertex 95.252396 104.072144 3.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 1.000000
    outer loop
      vertex 95.313316 103.467812 3.000000
      vertex 114.987381 85.712395 3.000000
      vertex 95.297836 103.774406 3.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 152.643661 149.405212 0.000000
      vertex 114.551727 152.782990 0.000000
      vertex 114.554306 152.834106 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 114.554306 164.084000 0.000000
      vertex 152.643661 149.405212 0.000000
      vertex 114.554306 152.834106 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 114.551727 164.135117 0.000000
      vertex 152.643661 149.405212 0.000000
      vertex 114.554306 164.084000 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 152.643661 149.405212 0.000000
      vertex 114.551727 164.135117 0.000000
      vertex 114.544151 164.184769 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 114.531830 164.232681 0.000000
      vertex 152.643661 149.405212 0.000000
      vertex 114.544151 164.184769 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 152.202698 191.535904 0.000000
      vertex 152.643661 149.405212 0.000000
      vertex 114.531830 164.232681 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 114.515015 164.278625 0.000000
      vertex 152.202698 191.535904 0.000000
      vertex 114.531830 164.232681 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 114.493958 164.322327 0.000000
      vertex 152.202698 191.535904 0.000000
      vertex 114.515015 164.278625 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 152.202698 191.535904 0.000000
      vertex 114.493958 164.322327 0.000000
      vertex 114.468910 164.363556 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 114.440132 164.402054 0.000000
      vertex 152.202698 191.535904 0.000000
      vertex 114.468910 164.363556 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 114.407860 164.437561 0.000000
      vertex 152.202698 191.535904 0.000000
      vertex 114.440132 164.402054 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 152.202698 191.535904 0.000000
      vertex 114.407860 164.437561 0.000000
      vertex 114.372353 164.469833 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 114.333862 164.498611 0.000000
      vertex 152.202698 191.535904 0.000000
      vertex 114.372353 164.469833 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 114.292633 164.523651 0.000000
      vertex 152.202698 191.535904 0.000000
      vertex 114.333862 164.498611 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 152.202698 191.535904 0.000000
      vertex 114.292633 164.523651 0.000000
      vertex 114.248932 164.544708 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 114.202988 164.561523 0.000000
      vertex 152.202698 191.535904 0.000000
      vertex 114.248932 164.544708 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 114.155075 164.573837 0.000000
      vertex 152.202698 191.535904 0.000000
      vertex 114.202988 164.561523 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 152.202698 191.535904 0.000000
      vertex 114.155075 164.573837 0.000000
      vertex 114.105431 164.581421 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 114.054306 164.584000 0.000000
      vertex 152.202698 191.535904 0.000000
      vertex 114.105431 164.581421 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 109.054306 164.584000 0.000000
      vertex 152.202698 191.535904 0.000000
      vertex 114.054306 164.584000 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 109.054306 164.584000 0.000000
      vertex 109.003181 164.581421 0.000000
      vertex 33.052002 189.562546 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 33.159359 189.567978 0.000000
      vertex 109.054306 164.584000 0.000000
      vertex 33.052002 189.562546 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 33.263615 189.583878 0.000000
      vertex 109.054306 164.584000 0.000000
      vertex 33.159359 189.567978 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 33.052002 189.562546 0.000000
      vertex 109.003181 164.581421 0.000000
      vertex 108.953537 164.573837 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 108.905624 164.561523 0.000000
      vertex 33.052002 189.562546 0.000000
      vertex 108.953537 164.573837 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 108.859680 164.544708 0.000000
      vertex 33.052002 189.562546 0.000000
      vertex 108.905624 164.561523 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 33.052002 189.562546 0.000000
      vertex 108.859680 164.544708 0.000000
      vertex 108.815979 164.523651 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 108.774750 164.498611 0.000000
      vertex 33.052002 189.562546 0.000000
      vertex 108.815979 164.523651 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 108.736259 164.469833 0.000000
      vertex 33.052002 189.562546 0.000000
      vertex 108.774750 164.498611 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 33.052002 189.562546 0.000000
      vertex 108.736259 164.469833 0.000000
      vertex 108.700752 164.437561 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 108.668480 164.402054 0.000000
      vertex 33.052002 189.562546 0.000000
      vertex 108.700752 164.437561 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 108.639694 164.363556 0.000000
      vertex 33.052002 189.562546 0.000000
      vertex 108.668480 164.402054 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 33.052002 189.562546 0.000000
      vertex 108.639694 164.363556 0.000000
      vertex 108.614655 164.322327 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 108.593597 164.278625 0.000000
      vertex 33.052002 189.562546 0.000000
      vertex 108.614655 164.322327 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 108.576782 164.232681 0.000000
      vertex 33.052002 189.562546 0.000000
      vertex 108.593597 164.278625 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 33.052002 189.562546 0.000000
      vertex 108.576782 164.232681 0.000000
      vertex 108.564461 164.184769 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 108.556885 164.135117 0.000000
      vertex 33.052002 189.562546 0.000000
      vertex 108.564461 164.184769 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 108.554306 164.084000 0.000000
      vertex 33.052002 189.562546 0.000000
      vertex 108.556885 164.135117 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 33.052002 189.562546 0.000000
      vertex 108.554306 164.084000 0.000000
      vertex 108.554306 152.834106 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 108.556885 152.782990 0.000000
      vertex 33.052002 189.562546 0.000000
      vertex 108.554306 152.834106 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 33.659145 111.301048 0.000000
      vertex 33.052002 189.562546 0.000000
      vertex 108.556885 152.782990 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 33.750931 111.256828 0.000000
      vertex 33.659145 111.301048 0.000000
      vertex 108.556885 152.782990 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 108.564461 152.733337 0.000000
      vertex 33.750931 111.256828 0.000000
      vertex 108.556885 152.782990 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 33.837505 111.204239 0.000000
      vertex 33.750931 111.256828 0.000000
      vertex 108.564461 152.733337 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 108.576782 152.685425 0.000000
      vertex 33.837505 111.204239 0.000000
      vertex 108.564461 152.733337 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 33.918339 111.143791 0.000000
      vertex 33.837505 111.204239 0.000000
      vertex 108.576782 152.685425 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 108.593597 152.639481 0.000000
      vertex 33.918339 111.143791 0.000000
      vertex 108.576782 152.685425 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 92.314682 106.466446 0.000000
      vertex 33.918339 111.143791 0.000000
      vertex 108.593597 152.639481 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 108.614655 152.595779 0.000000
      vertex 92.314682 106.466446 0.000000
      vertex 108.593597 152.639481 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 108.639694 152.554550 0.000000
      vertex 92.314682 106.466446 0.000000
      vertex 108.614655 152.595779 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 92.314682 106.466446 0.000000
      vertex 108.639694 152.554550 0.000000
      vertex 108.668480 152.516068 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 108.700752 152.480560 0.000000
      vertex 92.314682 106.466446 0.000000
      vertex 108.668480 152.516068 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 108.736259 152.448288 0.000000
      vertex 92.314682 106.466446 0.000000
      vertex 108.700752 152.480560 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 92.314682 106.466446 0.000000
      vertex 108.736259 152.448288 0.000000
      vertex 108.774750 152.419495 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 108.815979 152.394455 0.000000
      vertex 92.314682 106.466446 0.000000
      vertex 108.774750 152.419495 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 108.859680 152.373398 0.000000
      vertex 92.314682 106.466446 0.000000
      vertex 108.815979 152.394455 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 92.314682 106.466446 0.000000
      vertex 108.859680 152.373398 0.000000
      vertex 108.905624 152.356583 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 108.953537 152.344269 0.000000
      vertex 92.314682 106.466446 0.000000
      vertex 108.905624 152.356583 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 109.003181 152.336685 0.000000
      vertex 92.314682 106.466446 0.000000
      vertex 108.953537 152.344269 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 92.314682 106.466446 0.000000
      vertex 109.003181 152.336685 0.000000
      vertex 109.054306 152.334106 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 92.621277 106.450966 0.000000
      vertex 92.314682 106.466446 0.000000
      vertex 109.054306 152.334106 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 114.054306 152.334106 0.000000
      vertex 92.621277 106.450966 0.000000
      vertex 109.054306 152.334106 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 150.742050 132.304855 0.000000
      vertex 92.621277 106.450966 0.000000
      vertex 114.054306 152.334106 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 150.712769 132.396088 0.000000
      vertex 150.742050 132.304855 0.000000
      vertex 114.054306 152.334106 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 150.692291 132.489685 0.000000
      vertex 150.712769 132.396088 0.000000
      vertex 114.054306 152.334106 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 150.680801 132.584991 0.000000
      vertex 150.692291 132.489685 0.000000
      vertex 114.054306 152.334106 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 150.678497 132.681290 0.000000
      vertex 150.680801 132.584991 0.000000
      vertex 114.054306 152.334106 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 150.685562 132.777908 0.000000
      vertex 150.678497 132.681290 0.000000
      vertex 114.054306 152.334106 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 150.702179 132.874176 0.000000
      vertex 150.685562 132.777908 0.000000
      vertex 114.054306 152.334106 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 150.728531 132.969391 0.000000
      vertex 150.702179 132.874176 0.000000
      vertex 114.054306 152.334106 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 150.764786 133.062897 0.000000
      vertex 150.728531 132.969391 0.000000
      vertex 114.054306 152.334106 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 150.811142 133.153976 0.000000
      vertex 150.764786 133.062897 0.000000
      vertex 114.054306 152.334106 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 151.676178 147.946503 0.000000
      vertex 150.811142 133.153976 0.000000
      vertex 114.054306 152.334106 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 151.720398 147.854721 0.000000
      vertex 150.811142 133.153976 0.000000
      vertex 151.676178 147.946503 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 114.054306 152.334106 0.000000
      vertex 114.105431 152.336685 0.000000
      vertex 152.643661 149.405212 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 152.536316 149.399796 0.000000
      vertex 114.054306 152.334106 0.000000
      vertex 152.643661 149.405212 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 152.432053 149.383881 0.000000
      vertex 114.054306 152.334106 0.000000
      vertex 152.536316 149.399796 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 152.643661 149.405212 0.000000
      vertex 114.105431 152.336685 0.000000
      vertex 114.155075 152.344269 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 114.202988 152.356583 0.000000
      vertex 152.643661 149.405212 0.000000
      vertex 114.155075 152.344269 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 114.248932 152.373398 0.000000
      vertex 152.643661 149.405212 0.000000
      vertex 114.202988 152.356583 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 152.643661 149.405212 0.000000
      vertex 114.248932 152.373398 0.000000
      vertex 114.292633 152.394455 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 114.333862 152.419495 0.000000
      vertex 152.643661 149.405212 0.000000
      vertex 114.292633 152.394455 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 114.372353 152.448288 0.000000
      vertex 152.643661 149.405212 0.000000
      vertex 114.333862 152.419495 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 152.643661 149.405212 0.000000
      vertex 114.372353 152.448288 0.000000
      vertex 114.407860 152.480560 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 114.440132 152.516068 0.000000
      vertex 152.643661 149.405212 0.000000
      vertex 114.407860 152.480560 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 114.468910 152.554550 0.000000
      vertex 152.643661 149.405212 0.000000
      vertex 114.440132 152.516068 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 152.643661 149.405212 0.000000
      vertex 114.468910 152.554550 0.000000
      vertex 114.493958 152.595779 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 114.515015 152.639481 0.000000
      vertex 152.643661 149.405212 0.000000
      vertex 114.493958 152.595779 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 114.531830 152.685425 0.000000
      vertex 152.643661 149.405212 0.000000
      vertex 114.515015 152.639481 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 152.643661 149.405212 0.000000
      vertex 114.531830 152.685425 0.000000
      vertex 114.544151 152.733337 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 114.551727 152.782990 0.000000
      vertex 152.643661 149.405212 0.000000
      vertex 114.544151 152.733337 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 109.054306 164.584000 0.000000
      vertex 34.096581 190.505203 0.000000
      vertex 34.102001 190.612549 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 34.096581 190.719910 0.000000
      vertex 109.054306 164.584000 0.000000
      vertex 34.102001 190.612549 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 34.080669 190.824158 0.000000
      vertex 109.054306 164.584000 0.000000
      vertex 34.096581 190.719910 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 109.054306 164.584000 0.000000
      vertex 34.080669 190.824158 0.000000
      vertex 34.054798 190.924789 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 34.019489 191.021255 0.000000
      vertex 109.054306 164.584000 0.000000
      vertex 34.054798 190.924789 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 33.975273 191.113052 0.000000
      vertex 109.054306 164.584000 0.000000
      vertex 34.019489 191.021255 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 109.054306 164.584000 0.000000
      vertex 33.975273 191.113052 0.000000
      vertex 33.922680 191.199615 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 152.202698 191.535904 0.000000
      vertex 109.054306 164.584000 0.000000
      vertex 33.922680 191.199615 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 152.202698 191.535904 0.000000
      vertex 33.922680 191.199615 0.000000
      vertex 33.862232 191.280457 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 33.794464 191.355011 0.000000
      vertex 152.202698 191.535904 0.000000
      vertex 33.862232 191.280457 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 33.719898 191.422791 0.000000
      vertex 152.202698 191.535904 0.000000
      vertex 33.794464 191.355011 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 152.202698 191.535904 0.000000
      vertex 33.719898 191.422791 0.000000
      vertex 33.639069 191.483231 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 33.552494 191.535828 0.000000
      vertex 152.202698 191.535904 0.000000
      vertex 33.639069 191.483231 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 152.095337 191.541321 0.000000
      vertex 152.202698 191.535904 0.000000
      vertex 33.552494 191.535828 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 151.991089 191.557236 0.000000
      vertex 152.095337 191.541321 0.000000
      vertex 33.552494 191.535828 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 151.890457 191.583115 0.000000
      vertex 151.991089 191.557236 0.000000
      vertex 33.552494 191.535828 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 151.793991 191.618423 0.000000
      vertex 151.890457 191.583115 0.000000
      vertex 33.552494 191.535828 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 151.702209 191.662628 0.000000
      vertex 151.793991 191.618423 0.000000
      vertex 33.552494 191.535828 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 33.460709 191.580032 0.000000
      vertex 151.702209 191.662628 0.000000
      vertex 33.552494 191.535828 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 33.364239 191.615341 0.000000
      vertex 151.702209 191.662628 0.000000
      vertex 33.460709 191.580032 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 151.702209 191.662628 0.000000
      vertex 33.364239 191.615341 0.000000
      vertex 33.263615 191.641220 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 33.159359 191.657135 0.000000
      vertex 151.702209 191.662628 0.000000
      vertex 33.263615 191.641220 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 33.052002 191.662552 0.000000
      vertex 151.702209 191.662628 0.000000
      vertex 33.159359 191.657135 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 33.052002 191.662552 0.000000
      vertex 32.944645 191.657135 0.000000
      vertex 31.564236 193.862839 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 33.784603 194.460388 0.000000
      vertex 33.052002 191.662552 0.000000
      vertex 31.564236 193.862839 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 36.521648 195.189407 0.000000
      vertex 33.052002 191.662552 0.000000
      vertex 33.784603 194.460388 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 31.564236 193.862839 0.000000
      vertex 32.944645 191.657135 0.000000
      vertex 32.840389 191.641220 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 32.739765 191.615341 0.000000
      vertex 31.564236 193.862839 0.000000
      vertex 32.840389 191.641220 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 32.643295 191.580032 0.000000
      vertex 31.564236 193.862839 0.000000
      vertex 32.739765 191.615341 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 31.323421 193.787109 0.000000
      vertex 31.564236 193.862839 0.000000
      vertex 32.643295 191.580032 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 32.551510 191.535828 0.000000
      vertex 31.323421 193.787109 0.000000
      vertex 32.643295 191.580032 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 31.092722 193.692780 0.000000
      vertex 31.323421 193.787109 0.000000
      vertex 32.551510 191.535828 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 32.464939 191.483231 0.000000
      vertex 31.092722 193.692780 0.000000
      vertex 32.551510 191.535828 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 30.664656 193.452225 0.000000
      vertex 31.092722 193.692780 0.000000
      vertex 32.464939 191.483231 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 32.384106 191.422791 0.000000
      vertex 30.664656 193.452225 0.000000
      vertex 32.464939 191.483231 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 30.286024 193.149002 0.000000
      vertex 30.664656 193.452225 0.000000
      vertex 32.384106 191.422791 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 32.309540 191.355011 0.000000
      vertex 30.286024 193.149002 0.000000
      vertex 32.384106 191.422791 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 29.962812 192.790894 0.000000
      vertex 30.286024 193.149002 0.000000
      vertex 32.309540 191.355011 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 32.241772 191.280457 0.000000
      vertex 29.962812 192.790894 0.000000
      vertex 32.309540 191.355011 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 29.701006 192.385727 0.000000
      vertex 29.962812 192.790894 0.000000
      vertex 32.241772 191.280457 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 32.181324 191.199615 0.000000
      vertex 29.701006 192.385727 0.000000
      vertex 32.241772 191.280457 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 32.128731 191.113052 0.000000
      vertex 29.701006 192.385727 0.000000
      vertex 32.181324 191.199615 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 29.506590 191.941299 0.000000
      vertex 29.701006 192.385727 0.000000
      vertex 32.128731 191.113052 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 32.084518 191.021255 0.000000
      vertex 29.506590 191.941299 0.000000
      vertex 32.128731 191.113052 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 29.385550 191.465424 0.000000
      vertex 29.506590 191.941299 0.000000
      vertex 32.084518 191.021255 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 32.049210 190.924789 0.000000
      vertex 29.385550 191.465424 0.000000
      vertex 32.084518 191.021255 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 29.354418 191.218140 0.000000
      vertex 29.385550 191.465424 0.000000
      vertex 32.049210 190.924789 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 32.023335 190.824158 0.000000
      vertex 29.354418 191.218140 0.000000
      vertex 32.049210 190.924789 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 29.343874 190.965912 0.000000
      vertex 29.354418 191.218140 0.000000
      vertex 32.023335 190.824158 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 32.007423 190.719910 0.000000
      vertex 29.343874 190.965912 0.000000
      vertex 32.023335 190.824158 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 32.002003 190.612549 0.000000
      vertex 29.343874 190.965912 0.000000
      vertex 32.007423 190.719910 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 29.343874 190.965912 0.000000
      vertex 32.002003 190.612549 0.000000
      vertex 32.007423 190.505203 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 32.023335 190.400940 0.000000
      vertex 29.343874 190.965912 0.000000
      vertex 32.007423 190.505203 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 32.049210 190.300308 0.000000
      vertex 29.343874 190.965912 0.000000
      vertex 32.023335 190.400940 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 29.343874 190.965912 0.000000
      vertex 32.049210 190.300308 0.000000
      vertex 32.084518 190.203842 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 32.128731 190.112061 0.000000
      vertex 29.343874 190.965912 0.000000
      vertex 32.084518 190.203842 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 32.181324 190.025482 0.000000
      vertex 29.343874 190.965912 0.000000
      vertex 32.128731 190.112061 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 29.343874 190.965912 0.000000
      vertex 32.181324 190.025482 0.000000
      vertex 32.241772 189.944656 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 32.309540 189.870087 0.000000
      vertex 29.343874 190.965912 0.000000
      vertex 32.241772 189.944656 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 32.384106 189.802322 0.000000
      vertex 29.343874 190.965912 0.000000
      vertex 32.309540 189.870087 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 29.343874 190.965912 0.000000
      vertex 32.384106 189.802322 0.000000
      vertex 32.464939 189.741882 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 32.551510 189.689285 0.000000
      vertex 29.343874 190.965912 0.000000
      vertex 32.464939 189.741882 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 32.643295 189.645065 0.000000
      vertex 29.343874 190.965912 0.000000
      vertex 32.551510 189.689285 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 32.841732 111.301048 0.000000
      vertex 29.343874 190.965912 0.000000
      vertex 32.643295 189.645065 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 32.739765 189.609756 0.000000
      vertex 32.841732 111.301048 0.000000
      vertex 32.643295 189.645065 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 32.938202 111.336357 0.000000
      vertex 32.841732 111.301048 0.000000
      vertex 32.739765 189.609756 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 32.840389 189.583878 0.000000
      vertex 32.938202 111.336357 0.000000
      vertex 32.739765 189.609756 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 33.038826 111.362228 0.000000
      vertex 32.938202 111.336357 0.000000
      vertex 32.840389 189.583878 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 32.944645 189.567978 0.000000
      vertex 33.038826 111.362228 0.000000
      vertex 32.840389 189.583878 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 33.143082 111.378136 0.000000
      vertex 33.038826 111.362228 0.000000
      vertex 32.944645 189.567978 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 33.052002 189.562546 0.000000
      vertex 33.143082 111.378136 0.000000
      vertex 32.944645 189.567978 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 33.250439 111.383560 0.000000
      vertex 33.143082 111.378136 0.000000
      vertex 33.052002 189.562546 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 33.357796 111.378136 0.000000
      vertex 33.250439 111.383560 0.000000
      vertex 33.052002 189.562546 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 33.462051 111.362228 0.000000
      vertex 33.357796 111.378136 0.000000
      vertex 33.052002 189.562546 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 33.562675 111.336357 0.000000
      vertex 33.462051 111.362228 0.000000
      vertex 33.052002 189.562546 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 33.659145 111.301048 0.000000
      vertex 33.562675 111.336357 0.000000
      vertex 33.052002 189.562546 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 109.054306 164.584000 0.000000
      vertex 33.263615 189.583878 0.000000
      vertex 33.364239 189.609756 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 33.460709 189.645065 0.000000
      vertex 109.054306 164.584000 0.000000
      vertex 33.364239 189.609756 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 33.552494 189.689285 0.000000
      vertex 109.054306 164.584000 0.000000
      vertex 33.460709 189.645065 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 109.054306 164.584000 0.000000
      vertex 33.552494 189.689285 0.000000
      vertex 33.639069 189.741882 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 33.719898 189.802322 0.000000
      vertex 109.054306 164.584000 0.000000
      vertex 33.639069 189.741882 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 33.794464 189.870087 0.000000
      vertex 109.054306 164.584000 0.000000
      vertex 33.719898 189.802322 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 109.054306 164.584000 0.000000
      vertex 33.794464 189.870087 0.000000
      vertex 33.862232 189.944656 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 33.922680 190.025482 0.000000
      vertex 109.054306 164.584000 0.000000
      vertex 33.862232 189.944656 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 33.975273 190.112061 0.000000
      vertex 109.054306 164.584000 0.000000
      vertex 33.922680 190.025482 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 109.054306 164.584000 0.000000
      vertex 33.975273 190.112061 0.000000
      vertex 34.019489 190.203842 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 34.054798 190.300308 0.000000
      vertex 109.054306 164.584000 0.000000
      vertex 34.019489 190.203842 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 34.080669 190.400940 0.000000
      vertex 109.054306 164.584000 0.000000
      vertex 34.054798 190.300308 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 109.054306 164.584000 0.000000
      vertex 34.080669 190.400940 0.000000
      vertex 34.096581 190.505203 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 169.033630 124.989052 0.000000
      vertex 169.028214 125.096405 0.000000
      vertex 171.298981 126.433914 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 172.141312 125.916069 0.000000
      vertex 169.033630 124.989052 0.000000
      vertex 171.298981 126.433914 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 169.028214 124.881699 0.000000
      vertex 169.033630 124.989052 0.000000
      vertex 172.141312 125.916069 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 169.012299 124.777443 0.000000
      vertex 169.028214 124.881699 0.000000
      vertex 172.141312 125.916069 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 168.986420 124.676811 0.000000
      vertex 169.012299 124.777443 0.000000
      vertex 172.141312 125.916069 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 168.951111 124.580345 0.000000
      vertex 168.986420 124.676811 0.000000
      vertex 172.141312 125.916069 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 173.007095 125.389748 0.000000
      vertex 168.951111 124.580345 0.000000
      vertex 172.141312 125.916069 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 168.906906 124.488564 0.000000
      vertex 168.951111 124.580345 0.000000
      vertex 173.007095 125.389748 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 168.854309 124.401985 0.000000
      vertex 168.906906 124.488564 0.000000
      vertex 173.007095 125.389748 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 168.793854 124.321152 0.000000
      vertex 168.854309 124.401985 0.000000
      vertex 173.007095 125.389748 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 173.896439 124.854622 0.000000
      vertex 168.793854 124.321152 0.000000
      vertex 173.007095 125.389748 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 168.726089 124.246590 0.000000
      vertex 168.793854 124.321152 0.000000
      vertex 173.896439 124.854622 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 168.651520 124.178818 0.000000
      vertex 168.726089 124.246590 0.000000
      vertex 173.896439 124.854622 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 174.809448 124.310364 0.000000
      vertex 168.651520 124.178818 0.000000
      vertex 173.896439 124.854622 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 168.570694 124.118378 0.000000
      vertex 168.651520 124.178818 0.000000
      vertex 174.809448 124.310364 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 168.484116 124.065781 0.000000
      vertex 168.570694 124.118378 0.000000
      vertex 174.809448 124.310364 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 175.746231 123.756653 0.000000
      vertex 168.484116 124.065781 0.000000
      vertex 174.809448 124.310364 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 168.392334 124.021568 0.000000
      vertex 168.484116 124.065781 0.000000
      vertex 175.746231 123.756653 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 168.295868 123.986259 0.000000
      vertex 168.392334 124.021568 0.000000
      vertex 175.746231 123.756653 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 168.195236 123.960388 0.000000
      vertex 168.295868 123.986259 0.000000
      vertex 175.746231 123.756653 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 168.090988 123.944473 0.000000
      vertex 168.195236 123.960388 0.000000
      vertex 175.746231 123.756653 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 167.983627 123.939049 0.000000
      vertex 168.090988 123.944473 0.000000
      vertex 175.746231 123.756653 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 177.620056 118.010956 0.000000
      vertex 167.983627 123.939049 0.000000
      vertex 175.746231 123.756653 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 177.584747 117.914490 0.000000
      vertex 167.983627 123.939049 0.000000
      vertex 177.620056 118.010956 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 171.298981 126.433914 0.000000
      vertex 169.028214 125.096405 0.000000
      vertex 169.012299 125.200661 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 168.986420 125.301292 0.000000
      vertex 171.298981 126.433914 0.000000
      vertex 169.012299 125.200661 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 168.951111 125.397758 0.000000
      vertex 171.298981 126.433914 0.000000
      vertex 168.986420 125.301292 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 170.479996 126.943611 0.000000
      vertex 171.298981 126.433914 0.000000
      vertex 168.951111 125.397758 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 168.906906 125.489548 0.000000
      vertex 170.479996 126.943611 0.000000
      vertex 168.951111 125.397758 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 168.854309 125.576118 0.000000
      vertex 170.479996 126.943611 0.000000
      vertex 168.906906 125.489548 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 170.479996 126.943611 0.000000
      vertex 168.854309 125.576118 0.000000
      vertex 168.793854 125.656952 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 168.726089 125.731514 0.000000
      vertex 170.479996 126.943611 0.000000
      vertex 168.793854 125.656952 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 168.651520 125.799286 0.000000
      vertex 170.479996 126.943611 0.000000
      vertex 168.726089 125.731514 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 169.684265 127.445480 0.000000
      vertex 170.479996 126.943611 0.000000
      vertex 168.651520 125.799286 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 168.570694 125.859726 0.000000
      vertex 169.684265 127.445480 0.000000
      vertex 168.651520 125.799286 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 168.484116 125.912323 0.000000
      vertex 169.684265 127.445480 0.000000
      vertex 168.570694 125.859726 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 169.684265 127.445480 0.000000
      vertex 168.484116 125.912323 0.000000
      vertex 168.392334 125.956535 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 168.295868 125.991844 0.000000
      vertex 169.684265 127.445480 0.000000
      vertex 168.392334 125.956535 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 168.911652 127.939850 0.000000
      vertex 169.684265 127.445480 0.000000
      vertex 168.295868 125.991844 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 168.195236 126.017723 0.000000
      vertex 168.911652 127.939850 0.000000
      vertex 168.295868 125.991844 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 168.090988 126.033630 0.000000
      vertex 168.911652 127.939850 0.000000
      vertex 168.195236 126.017723 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 168.911652 127.939850 0.000000
      vertex 168.090988 126.033630 0.000000
      vertex 167.983627 126.039055 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 168.162064 128.427048 0.000000
      vertex 168.911652 127.939850 0.000000
      vertex 167.983627 126.039055 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 167.435410 128.907394 0.000000
      vertex 168.162064 128.427048 0.000000
      vertex 167.983627 126.039055 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 166.731552 129.381241 0.000000
      vertex 167.435410 128.907394 0.000000
      vertex 167.983627 126.039055 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 162.035110 126.676598 0.000000
      vertex 166.731552 129.381241 0.000000
      vertex 167.983627 126.039055 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 163.950409 129.993988 0.000000
      vertex 166.731552 129.381241 0.000000
      vertex 162.035110 126.676598 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 167.983627 126.039055 0.000000
      vertex 167.876266 126.033630 0.000000
      vertex 161.142242 126.176765 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 161.238693 126.178917 0.000000
      vertex 167.983627 126.039055 0.000000
      vertex 161.142242 126.176765 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 161.334137 126.190285 0.000000
      vertex 167.983627 126.039055 0.000000
      vertex 161.238693 126.178917 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 161.142242 126.176765 0.000000
      vertex 167.876266 126.033630 0.000000
      vertex 167.772018 126.017723 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 167.671387 125.991844 0.000000
      vertex 161.142242 126.176765 0.000000
      vertex 167.772018 126.017723 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 167.574921 125.956535 0.000000
      vertex 161.142242 126.176765 0.000000
      vertex 167.671387 125.991844 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 161.142242 126.176765 0.000000
      vertex 167.574921 125.956535 0.000000
      vertex 167.483139 125.912323 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 167.396561 125.859726 0.000000
      vertex 161.142242 126.176765 0.000000
      vertex 167.483139 125.912323 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 167.315735 125.799286 0.000000
      vertex 161.142242 126.176765 0.000000
      vertex 167.396561 125.859726 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 161.142242 126.176765 0.000000
      vertex 167.315735 125.799286 0.000000
      vertex 167.241165 125.731514 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 167.173401 125.656952 0.000000
      vertex 161.142242 126.176765 0.000000
      vertex 167.241165 125.731514 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 167.112946 125.576118 0.000000
      vertex 161.142242 126.176765 0.000000
      vertex 167.173401 125.656952 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 161.142242 126.176765 0.000000
      vertex 167.112946 125.576118 0.000000
      vertex 167.060364 125.489548 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 167.016144 125.397758 0.000000
      vertex 161.142242 126.176765 0.000000
      vertex 167.060364 125.489548 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 166.980835 125.301292 0.000000
      vertex 161.142242 126.176765 0.000000
      vertex 167.016144 125.397758 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 161.142242 126.176765 0.000000
      vertex 166.980835 125.301292 0.000000
      vertex 166.954956 125.200661 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 166.939056 125.096405 0.000000
      vertex 161.142242 126.176765 0.000000
      vertex 166.954956 125.200661 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 166.933624 124.989052 0.000000
      vertex 161.142242 126.176765 0.000000
      vertex 166.939056 125.096405 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 161.142242 126.176765 0.000000
      vertex 166.933624 124.989052 0.000000
      vertex 166.939056 124.881699 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 166.954956 124.777443 0.000000
      vertex 161.142242 126.176765 0.000000
      vertex 166.939056 124.881699 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 166.980835 124.676811 0.000000
      vertex 161.142242 126.176765 0.000000
      vertex 166.954956 124.777443 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 161.142242 126.176765 0.000000
      vertex 166.980835 124.676811 0.000000
      vertex 167.016144 124.580345 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 167.060364 124.488564 0.000000
      vertex 161.142242 126.176765 0.000000
      vertex 167.016144 124.580345 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 167.112946 124.401985 0.000000
      vertex 161.142242 126.176765 0.000000
      vertex 167.060364 124.488564 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 161.142242 126.176765 0.000000
      vertex 167.112946 124.401985 0.000000
      vertex 167.173401 124.321152 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 167.241165 124.246590 0.000000
      vertex 161.142242 126.176765 0.000000
      vertex 167.173401 124.321152 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 167.315735 124.178818 0.000000
      vertex 161.142242 126.176765 0.000000
      vertex 167.241165 124.246590 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 161.142242 126.176765 0.000000
      vertex 167.315735 124.178818 0.000000
      vertex 167.396561 124.118378 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 161.045486 126.184006 0.000000
      vertex 161.142242 126.176765 0.000000
      vertex 167.396561 124.118378 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 167.483139 124.065781 0.000000
      vertex 161.045486 126.184006 0.000000
      vertex 167.396561 124.118378 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 160.949097 126.200821 0.000000
      vertex 161.045486 126.184006 0.000000
      vertex 167.483139 124.065781 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 167.574921 124.021568 0.000000
      vertex 160.949097 126.200821 0.000000
      vertex 167.483139 124.065781 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 177.845078 116.859787 0.000000
      vertex 160.949097 126.200821 0.000000
      vertex 167.574921 124.021568 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 177.777298 116.934357 0.000000
      vertex 177.845078 116.859787 0.000000
      vertex 167.574921 124.021568 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 167.671387 123.986259 0.000000
      vertex 177.777298 116.934357 0.000000
      vertex 167.574921 124.021568 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 177.716858 117.015190 0.000000
      vertex 177.777298 116.934357 0.000000
      vertex 167.671387 123.986259 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 167.772018 123.960388 0.000000
      vertex 177.716858 117.015190 0.000000
      vertex 167.671387 123.986259 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 177.664261 117.101761 0.000000
      vertex 177.716858 117.015190 0.000000
      vertex 167.772018 123.960388 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 167.876266 123.944473 0.000000
      vertex 177.664261 117.101761 0.000000
      vertex 167.772018 123.960388 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 177.620056 117.193542 0.000000
      vertex 177.664261 117.101761 0.000000
      vertex 167.876266 123.944473 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 177.584747 117.290016 0.000000
      vertex 177.620056 117.193542 0.000000
      vertex 167.876266 123.944473 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 167.983627 123.939049 0.000000
      vertex 177.584747 117.290016 0.000000
      vertex 167.876266 123.944473 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 177.558868 117.390640 0.000000
      vertex 177.584747 117.290016 0.000000
      vertex 167.983627 123.939049 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 177.542953 117.494896 0.000000
      vertex 177.558868 117.390640 0.000000
      vertex 167.983627 123.939049 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 177.537537 117.602249 0.000000
      vertex 177.542953 117.494896 0.000000
      vertex 167.983627 123.939049 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 177.542953 117.709610 0.000000
      vertex 177.537537 117.602249 0.000000
      vertex 167.983627 123.939049 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 177.558868 117.813866 0.000000
      vertex 177.542953 117.709610 0.000000
      vertex 167.983627 123.939049 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 177.584747 117.914490 0.000000
      vertex 177.558868 117.813866 0.000000
      vertex 167.983627 123.939049 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 125.063393 202.113159 0.000000
      vertex 125.057976 202.220520 0.000000
      vertex 127.652306 204.592361 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 129.117828 204.333572 0.000000
      vertex 125.063393 202.113159 0.000000
      vertex 127.652306 204.592361 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 125.057976 202.005814 0.000000
      vertex 125.063393 202.113159 0.000000
      vertex 129.117828 204.333572 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 125.042061 201.901550 0.000000
      vertex 125.057976 202.005814 0.000000
      vertex 129.117828 204.333572 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 125.016190 201.800934 0.000000
      vertex 125.042061 201.901550 0.000000
      vertex 129.117828 204.333572 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 130.564972 204.055374 0.000000
      vertex 125.016190 201.800934 0.000000
      vertex 129.117828 204.333572 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 124.980881 201.704453 0.000000
      vertex 125.016190 201.800934 0.000000
      vertex 130.564972 204.055374 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 124.936668 201.612671 0.000000
      vertex 124.980881 201.704453 0.000000
      vertex 130.564972 204.055374 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 124.884071 201.526093 0.000000
      vertex 124.936668 201.612671 0.000000
      vertex 130.564972 204.055374 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 131.993851 203.757736 0.000000
      vertex 124.884071 201.526093 0.000000
      vertex 130.564972 204.055374 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 124.823624 201.445267 0.000000
      vertex 124.884071 201.526093 0.000000
      vertex 131.993851 203.757736 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 124.755859 201.370697 0.000000
      vertex 124.823624 201.445267 0.000000
      vertex 131.993851 203.757736 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 133.404648 203.440598 0.000000
      vertex 124.755859 201.370697 0.000000
      vertex 131.993851 203.757736 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 124.681290 201.302933 0.000000
      vertex 124.755859 201.370697 0.000000
      vertex 133.404648 203.440598 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 134.797531 203.103958 0.000000
      vertex 124.681290 201.302933 0.000000
      vertex 133.404648 203.440598 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 124.600464 201.242493 0.000000
      vertex 124.681290 201.302933 0.000000
      vertex 134.797531 203.103958 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 136.172623 202.747757 0.000000
      vertex 124.600464 201.242493 0.000000
      vertex 134.797531 203.103958 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 124.513885 201.189896 0.000000
      vertex 124.600464 201.242493 0.000000
      vertex 136.172623 202.747757 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 137.530090 202.371979 0.000000
      vertex 124.513885 201.189896 0.000000
      vertex 136.172623 202.747757 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 124.422104 201.145676 0.000000
      vertex 124.513885 201.189896 0.000000
      vertex 137.530090 202.371979 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 138.870117 201.976593 0.000000
      vertex 124.422104 201.145676 0.000000
      vertex 137.530090 202.371979 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 140.192825 201.561539 0.000000
      vertex 124.422104 201.145676 0.000000
      vertex 138.870117 201.976593 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 127.652306 204.592361 0.000000
      vertex 125.057976 202.220520 0.000000
      vertex 125.042061 202.324783 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 125.016190 202.425400 0.000000
      vertex 127.652306 204.592361 0.000000
      vertex 125.042061 202.324783 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 124.980881 202.521866 0.000000
      vertex 127.652306 204.592361 0.000000
      vertex 125.016190 202.425400 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 127.652306 204.592361 0.000000
      vertex 124.980881 202.521866 0.000000
      vertex 124.936668 202.613663 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 126.168221 204.831757 0.000000
      vertex 127.652306 204.592361 0.000000
      vertex 124.936668 202.613663 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 124.884071 202.700226 0.000000
      vertex 126.168221 204.831757 0.000000
      vertex 124.936668 202.613663 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 124.823624 202.781067 0.000000
      vertex 126.168221 204.831757 0.000000
      vertex 124.884071 202.700226 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 126.168221 204.831757 0.000000
      vertex 124.823624 202.781067 0.000000
      vertex 124.755859 202.855621 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 124.681290 202.923401 0.000000
      vertex 126.168221 204.831757 0.000000
      vertex 124.755859 202.855621 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 124.600464 202.983841 0.000000
      vertex 126.168221 204.831757 0.000000
      vertex 124.681290 202.923401 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 126.168221 204.831757 0.000000
      vertex 124.600464 202.983841 0.000000
      vertex 124.513885 203.036438 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 124.665428 205.051819 0.000000
      vertex 126.168221 204.831757 0.000000
      vertex 124.513885 203.036438 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 124.422104 203.080643 0.000000
      vertex 124.665428 205.051819 0.000000
      vertex 124.513885 203.036438 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 124.325630 203.115952 0.000000
      vertex 124.665428 205.051819 0.000000
      vertex 124.422104 203.080643 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 124.665428 205.051819 0.000000
      vertex 124.325630 203.115952 0.000000
      vertex 124.225006 203.141830 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 124.120750 203.157745 0.000000
      vertex 124.665428 205.051819 0.000000
      vertex 124.225006 203.141830 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 124.013397 203.163162 0.000000
      vertex 124.665428 205.051819 0.000000
      vertex 124.120750 203.157745 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 124.013397 203.163162 0.000000
      vertex 123.906036 203.157745 0.000000
      vertex 100.072800 203.224228 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 113.608826 206.053345 0.000000
      vertex 124.013397 203.163162 0.000000
      vertex 100.072800 203.224228 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 115.246971 205.967773 0.000000
      vertex 124.013397 203.163162 0.000000
      vertex 113.608826 206.053345 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 100.072800 203.224228 0.000000
      vertex 123.906036 203.157745 0.000000
      vertex 123.801781 203.141830 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 123.701157 203.115952 0.000000
      vertex 100.072800 203.224228 0.000000
      vertex 123.801781 203.141830 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 123.604691 203.080643 0.000000
      vertex 100.072800 203.224228 0.000000
      vertex 123.701157 203.115952 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 100.072800 203.224228 0.000000
      vertex 123.604691 203.080643 0.000000
      vertex 123.512901 203.036438 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 123.426331 202.983841 0.000000
      vertex 100.072800 203.224228 0.000000
      vertex 123.512901 203.036438 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 123.345497 202.923401 0.000000
      vertex 100.072800 203.224228 0.000000
      vertex 123.426331 202.983841 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 100.072800 203.224228 0.000000
      vertex 123.345497 202.923401 0.000000
      vertex 123.270935 202.855621 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 123.203163 202.781067 0.000000
      vertex 100.072800 203.224228 0.000000
      vertex 123.270935 202.855621 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 123.142723 202.700226 0.000000
      vertex 100.072800 203.224228 0.000000
      vertex 123.203163 202.781067 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 100.072800 203.224228 0.000000
      vertex 123.142723 202.700226 0.000000
      vertex 123.090126 202.613663 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 123.045914 202.521866 0.000000
      vertex 100.072800 203.224228 0.000000
      vertex 123.090126 202.613663 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 123.010605 202.425400 0.000000
      vertex 100.072800 203.224228 0.000000
      vertex 123.045914 202.521866 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 100.072800 203.224228 0.000000
      vertex 123.010605 202.425400 0.000000
      vertex 122.984726 202.324783 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 100.088715 203.119965 0.000000
      vertex 100.072800 203.224228 0.000000
      vertex 122.984726 202.324783 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 122.968819 202.220520 0.000000
      vertex 100.088715 203.119965 0.000000
      vertex 122.984726 202.324783 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 100.094131 203.012619 0.000000
      vertex 100.088715 203.119965 0.000000
      vertex 122.968819 202.220520 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 122.963394 202.113159 0.000000
      vertex 100.094131 203.012619 0.000000
      vertex 122.968819 202.220520 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 100.088715 202.905258 0.000000
      vertex 100.094131 203.012619 0.000000
      vertex 122.963394 202.113159 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 122.968819 202.005814 0.000000
      vertex 100.088715 202.905258 0.000000
      vertex 122.963394 202.113159 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 100.072800 202.800995 0.000000
      vertex 100.088715 202.905258 0.000000
      vertex 122.968819 202.005814 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 122.984726 201.901550 0.000000
      vertex 100.072800 202.800995 0.000000
      vertex 122.968819 202.005814 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 100.046928 202.700378 0.000000
      vertex 100.072800 202.800995 0.000000
      vertex 122.984726 201.901550 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 100.011620 202.603897 0.000000
      vertex 100.046928 202.700378 0.000000
      vertex 122.984726 201.901550 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.967407 202.512115 0.000000
      vertex 100.011620 202.603897 0.000000
      vertex 122.984726 201.901550 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.914810 202.425552 0.000000
      vertex 99.967407 202.512115 0.000000
      vertex 122.984726 201.901550 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.854362 202.344711 0.000000
      vertex 99.914810 202.425552 0.000000
      vertex 122.984726 201.901550 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.786598 202.270157 0.000000
      vertex 99.854362 202.344711 0.000000
      vertex 122.984726 201.901550 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.712036 202.202377 0.000000
      vertex 99.786598 202.270157 0.000000
      vertex 122.984726 201.901550 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.631203 202.141937 0.000000
      vertex 99.712036 202.202377 0.000000
      vertex 122.984726 201.901550 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.544624 202.089340 0.000000
      vertex 99.631203 202.141937 0.000000
      vertex 122.984726 201.901550 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.452843 202.045120 0.000000
      vertex 99.544624 202.089340 0.000000
      vertex 122.984726 201.901550 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.356377 202.009811 0.000000
      vertex 99.452843 202.045120 0.000000
      vertex 122.984726 201.901550 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.255745 201.983948 0.000000
      vertex 99.356377 202.009811 0.000000
      vertex 122.984726 201.901550 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.151489 201.968033 0.000000
      vertex 99.255745 201.983948 0.000000
      vertex 122.984726 201.901550 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.044136 201.962616 0.000000
      vertex 99.151489 201.968033 0.000000
      vertex 122.984726 201.901550 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 123.010605 201.800934 0.000000
      vertex 99.044136 201.962616 0.000000
      vertex 122.984726 201.901550 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 123.045914 201.704453 0.000000
      vertex 99.044136 201.962616 0.000000
      vertex 123.010605 201.800934 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.044136 201.962616 0.000000
      vertex 123.045914 201.704453 0.000000
      vertex 123.090126 201.612671 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 123.142723 201.526093 0.000000
      vertex 99.044136 201.962616 0.000000
      vertex 123.090126 201.612671 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 123.203163 201.445267 0.000000
      vertex 99.044136 201.962616 0.000000
      vertex 123.142723 201.526093 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.044136 201.962616 0.000000
      vertex 123.203163 201.445267 0.000000
      vertex 123.270935 201.370697 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 123.345497 201.302933 0.000000
      vertex 99.044136 201.962616 0.000000
      vertex 123.270935 201.370697 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 123.426331 201.242493 0.000000
      vertex 99.044136 201.962616 0.000000
      vertex 123.345497 201.302933 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.044136 201.962616 0.000000
      vertex 123.426331 201.242493 0.000000
      vertex 123.512901 201.189896 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 123.604691 201.145676 0.000000
      vertex 99.044136 201.962616 0.000000
      vertex 123.512901 201.189896 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 123.701157 201.110367 0.000000
      vertex 99.044136 201.962616 0.000000
      vertex 123.604691 201.145676 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.044136 201.962616 0.000000
      vertex 123.701157 201.110367 0.000000
      vertex 123.801781 201.084503 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 123.906036 201.068588 0.000000
      vertex 99.044136 201.962616 0.000000
      vertex 123.801781 201.084503 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 59.755661 200.686371 0.000000
      vertex 99.044136 201.962616 0.000000
      vertex 123.906036 201.068588 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 124.013397 201.063171 0.000000
      vertex 59.755661 200.686371 0.000000
      vertex 123.906036 201.068588 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 151.702209 191.662628 0.000000
      vertex 59.755661 200.686371 0.000000
      vertex 124.013397 201.063171 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 151.615631 191.715225 0.000000
      vertex 151.702209 191.662628 0.000000
      vertex 124.013397 201.063171 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 151.534805 191.775665 0.000000
      vertex 151.615631 191.715225 0.000000
      vertex 124.013397 201.063171 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 124.120750 201.068588 0.000000
      vertex 151.534805 191.775665 0.000000
      vertex 124.013397 201.063171 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 151.460236 191.843445 0.000000
      vertex 151.534805 191.775665 0.000000
      vertex 124.120750 201.068588 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 151.392471 191.917999 0.000000
      vertex 151.460236 191.843445 0.000000
      vertex 124.120750 201.068588 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 124.225006 201.084503 0.000000
      vertex 151.392471 191.917999 0.000000
      vertex 124.120750 201.068588 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 151.332016 191.998840 0.000000
      vertex 151.392471 191.917999 0.000000
      vertex 124.225006 201.084503 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 124.325630 201.110367 0.000000
      vertex 151.332016 191.998840 0.000000
      vertex 124.225006 201.084503 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 151.279419 192.085403 0.000000
      vertex 151.332016 191.998840 0.000000
      vertex 124.325630 201.110367 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 124.422104 201.145676 0.000000
      vertex 151.279419 192.085403 0.000000
      vertex 124.325630 201.110367 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 140.192825 201.561539 0.000000
      vertex 151.279419 192.085403 0.000000
      vertex 124.422104 201.145676 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 105.375107 86.815102 0.000000
      vertex 100.066025 91.359718 0.000000
      vertex 100.071449 91.467072 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 100.066025 91.574432 0.000000
      vertex 105.375107 86.815102 0.000000
      vertex 100.071449 91.467072 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 100.050117 91.678688 0.000000
      vertex 105.375107 86.815102 0.000000
      vertex 100.066025 91.574432 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 105.375107 86.815102 0.000000
      vertex 100.050117 91.678688 0.000000
      vertex 100.024239 91.779312 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 107.848114 86.524818 0.000000
      vertex 105.375107 86.815102 0.000000
      vertex 100.024239 91.779312 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.988930 91.875786 0.000000
      vertex 107.848114 86.524818 0.000000
      vertex 100.024239 91.779312 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.944717 91.967567 0.000000
      vertex 107.848114 86.524818 0.000000
      vertex 99.988930 91.875786 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 110.297417 86.249596 0.000000
      vertex 107.848114 86.524818 0.000000
      vertex 99.944717 91.967567 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.892120 92.054138 0.000000
      vertex 110.297417 86.249596 0.000000
      vertex 99.944717 91.967567 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.831680 92.134972 0.000000
      vertex 110.297417 86.249596 0.000000
      vertex 99.892120 92.054138 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 110.297417 86.249596 0.000000
      vertex 99.831680 92.134972 0.000000
      vertex 99.763908 92.209534 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 95.313316 103.467812 0.000000
      vertex 110.297417 86.249596 0.000000
      vertex 99.763908 92.209534 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 114.987381 85.712395 0.000000
      vertex 110.297417 86.249596 0.000000
      vertex 95.313316 103.467812 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 95.297836 103.774406 0.000000
      vertex 114.987381 85.712395 0.000000
      vertex 95.313316 103.467812 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 95.252396 104.072144 0.000000
      vertex 114.987381 85.712395 0.000000
      vertex 95.297836 103.774406 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 95.313316 103.467812 0.000000
      vertex 99.763908 92.209534 0.000000
      vertex 99.689346 92.277306 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.608513 92.337753 0.000000
      vertex 95.313316 103.467812 0.000000
      vertex 99.689346 92.277306 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.521942 92.390343 0.000000
      vertex 95.313316 103.467812 0.000000
      vertex 99.608513 92.337753 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 95.313316 103.467812 0.000000
      vertex 99.521942 92.390343 0.000000
      vertex 99.430153 92.434563 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.333687 92.469872 0.000000
      vertex 95.313316 103.467812 0.000000
      vertex 99.430153 92.434563 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.233055 92.495743 0.000000
      vertex 95.313316 103.467812 0.000000
      vertex 99.333687 92.469872 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 95.313316 103.467812 0.000000
      vertex 99.233055 92.495743 0.000000
      vertex 99.128799 92.511658 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.021446 92.517075 0.000000
      vertex 95.313316 103.467812 0.000000
      vertex 99.128799 92.511658 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 98.914093 92.511658 0.000000
      vertex 95.313316 103.467812 0.000000
      vertex 99.021446 92.517075 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 95.313316 103.467812 0.000000
      vertex 98.914093 92.511658 0.000000
      vertex 98.809837 92.495743 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 98.709206 92.469872 0.000000
      vertex 95.313316 103.467812 0.000000
      vertex 98.809837 92.495743 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 98.612740 92.434563 0.000000
      vertex 95.313316 103.467812 0.000000
      vertex 98.709206 92.469872 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 95.313316 103.467812 0.000000
      vertex 98.612740 92.434563 0.000000
      vertex 98.520958 92.390343 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 98.434380 92.337753 0.000000
      vertex 95.313316 103.467812 0.000000
      vertex 98.520958 92.390343 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 98.353546 92.277306 0.000000
      vertex 95.313316 103.467812 0.000000
      vertex 98.434380 92.337753 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 95.313316 90.837059 0.000000
      vertex 95.313316 103.467812 0.000000
      vertex 98.353546 92.277306 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 98.278984 92.209534 0.000000
      vertex 95.313316 90.837059 0.000000
      vertex 98.353546 92.277306 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 98.211212 92.134972 0.000000
      vertex 95.313316 90.837059 0.000000
      vertex 98.278984 92.209534 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 95.313316 90.837059 0.000000
      vertex 98.211212 92.134972 0.000000
      vertex 98.150772 92.054138 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 98.098175 91.967567 0.000000
      vertex 95.313316 90.837059 0.000000
      vertex 98.150772 92.054138 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 98.053963 91.875786 0.000000
      vertex 95.313316 90.837059 0.000000
      vertex 98.098175 91.967567 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 95.313316 90.837059 0.000000
      vertex 98.053963 91.875786 0.000000
      vertex 98.018654 91.779312 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 97.992783 91.678688 0.000000
      vertex 95.313316 90.837059 0.000000
      vertex 98.018654 91.779312 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 97.976868 91.574432 0.000000
      vertex 95.313316 90.837059 0.000000
      vertex 97.992783 91.678688 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 95.313316 90.837059 0.000000
      vertex 97.976868 91.574432 0.000000
      vertex 97.971443 91.467072 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 97.976868 91.359718 0.000000
      vertex 95.313316 90.837059 0.000000
      vertex 97.971443 91.467072 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 97.992783 91.255463 0.000000
      vertex 95.313316 90.837059 0.000000
      vertex 97.976868 91.359718 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 95.313316 90.837059 0.000000
      vertex 97.992783 91.255463 0.000000
      vertex 98.018654 91.154839 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 95.325844 90.561836 0.000000
      vertex 95.313316 90.837059 0.000000
      vertex 98.018654 91.154839 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 98.053963 91.058365 0.000000
      vertex 95.325844 90.561836 0.000000
      vertex 98.018654 91.154839 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 95.362732 90.293015 0.000000
      vertex 95.325844 90.561836 0.000000
      vertex 98.053963 91.058365 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 98.098175 90.966583 0.000000
      vertex 95.362732 90.293015 0.000000
      vertex 98.053963 91.058365 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 98.150772 90.880013 0.000000
      vertex 95.362732 90.293015 0.000000
      vertex 98.098175 90.966583 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 95.362732 90.293015 0.000000
      vertex 98.150772 90.880013 0.000000
      vertex 98.211212 90.799179 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 98.278984 90.724609 0.000000
      vertex 95.362732 90.293015 0.000000
      vertex 98.211212 90.799179 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 98.353546 90.656845 0.000000
      vertex 95.362732 90.293015 0.000000
      vertex 98.278984 90.724609 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 95.362732 90.293015 0.000000
      vertex 98.353546 90.656845 0.000000
      vertex 98.434380 90.596397 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 98.520958 90.543808 0.000000
      vertex 95.362732 90.293015 0.000000
      vertex 98.434380 90.596397 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 98.612740 90.499588 0.000000
      vertex 95.362732 90.293015 0.000000
      vertex 98.520958 90.543808 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 95.362732 90.293015 0.000000
      vertex 98.612740 90.499588 0.000000
      vertex 98.709206 90.464279 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 98.809837 90.438408 0.000000
      vertex 95.362732 90.293015 0.000000
      vertex 98.709206 90.464279 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 98.914093 90.422493 0.000000
      vertex 95.362732 90.293015 0.000000
      vertex 98.809837 90.438408 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 95.362732 90.293015 0.000000
      vertex 98.914093 90.422493 0.000000
      vertex 99.021446 90.417076 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 95.422966 90.031807 0.000000
      vertex 95.362732 90.293015 0.000000
      vertex 99.021446 90.417076 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 95.505508 89.779388 0.000000
      vertex 95.422966 90.031807 0.000000
      vertex 99.021446 90.417076 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 95.609344 89.536964 0.000000
      vertex 95.505508 89.779388 0.000000
      vertex 99.021446 90.417076 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 95.733437 89.305725 0.000000
      vertex 95.609344 89.536964 0.000000
      vertex 99.021446 90.417076 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 95.876762 89.086868 0.000000
      vertex 95.733437 89.305725 0.000000
      vertex 99.021446 90.417076 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 96.038292 88.881577 0.000000
      vertex 95.876762 89.086868 0.000000
      vertex 99.021446 90.417076 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 96.217003 88.691063 0.000000
      vertex 96.038292 88.881577 0.000000
      vertex 99.021446 90.417076 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 96.411865 88.516510 0.000000
      vertex 96.217003 88.691063 0.000000
      vertex 99.021446 90.417076 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 96.621857 88.359116 0.000000
      vertex 96.411865 88.516510 0.000000
      vertex 99.021446 90.417076 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 96.845947 88.220070 0.000000
      vertex 96.621857 88.359116 0.000000
      vertex 99.021446 90.417076 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 97.083115 88.100571 0.000000
      vertex 96.845947 88.220070 0.000000
      vertex 99.021446 90.417076 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 97.332329 88.001808 0.000000
      vertex 97.083115 88.100571 0.000000
      vertex 99.021446 90.417076 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 97.592560 87.924980 0.000000
      vertex 97.332329 88.001808 0.000000
      vertex 99.021446 90.417076 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 97.862793 87.871284 0.000000
      vertex 97.592560 87.924980 0.000000
      vertex 99.021446 90.417076 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.128799 90.422493 0.000000
      vertex 97.862793 87.871284 0.000000
      vertex 99.021446 90.417076 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 100.413780 87.483971 0.000000
      vertex 97.862793 87.871284 0.000000
      vertex 99.128799 90.422493 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 99.233055 90.438408 0.000000
      vertex 100.413780 87.483971 0.000000
      vertex 99.128799 90.422493 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 99.333687 90.464279 0.000000
      vertex 100.413780 87.483971 0.000000
      vertex 99.233055 90.438408 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 100.413780 87.483971 0.000000
      vertex 99.333687 90.464279 0.000000
      vertex 99.430153 90.499588 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 99.521942 90.543808 0.000000
      vertex 100.413780 87.483971 0.000000
      vertex 99.430153 90.499588 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 99.608513 90.596397 0.000000
      vertex 100.413780 87.483971 0.000000
      vertex 99.521942 90.543808 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 100.413780 87.483971 0.000000
      vertex 99.608513 90.596397 0.000000
      vertex 99.689346 90.656845 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 99.763908 90.724609 0.000000
      vertex 100.413780 87.483971 0.000000
      vertex 99.689346 90.656845 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 99.831680 90.799179 0.000000
      vertex 100.413780 87.483971 0.000000
      vertex 99.763908 90.724609 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 102.892342 87.131226 0.000000
      vertex 100.413780 87.483971 0.000000
      vertex 99.831680 90.799179 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 99.892120 90.880013 0.000000
      vertex 102.892342 87.131226 0.000000
      vertex 99.831680 90.799179 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 99.944717 90.966583 0.000000
      vertex 102.892342 87.131226 0.000000
      vertex 99.892120 90.880013 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 102.892342 87.131226 0.000000
      vertex 99.944717 90.966583 0.000000
      vertex 99.988930 91.058365 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 100.024239 91.154839 0.000000
      vertex 102.892342 87.131226 0.000000
      vertex 99.988930 91.058365 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 100.050117 91.255463 0.000000
      vertex 102.892342 87.131226 0.000000
      vertex 100.024239 91.154839 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 102.892342 87.131226 0.000000
      vertex 100.050117 91.255463 0.000000
      vertex 100.066025 91.359718 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 105.375107 86.815102 0.000000
      vertex 102.892342 87.131226 0.000000
      vertex 100.066025 91.359718 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 157.924652 74.011238 0.000000
      vertex 156.091553 76.602074 0.000000
      vertex 156.096970 76.709427 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 156.091553 76.816788 0.000000
      vertex 157.924652 74.011238 0.000000
      vertex 156.096970 76.709427 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 156.075638 76.921036 0.000000
      vertex 157.924652 74.011238 0.000000
      vertex 156.091553 76.816788 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 157.924652 74.011238 0.000000
      vertex 156.075638 76.921036 0.000000
      vertex 156.049759 77.021667 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 156.014450 77.118134 0.000000
      vertex 157.924652 74.011238 0.000000
      vertex 156.049759 77.021667 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.970245 77.209923 0.000000
      vertex 157.924652 74.011238 0.000000
      vertex 156.014450 77.118134 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 182.395859 116.439316 0.000000
      vertex 157.924652 74.011238 0.000000
      vertex 155.970245 77.209923 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.917648 77.296494 0.000000
      vertex 182.395859 116.439316 0.000000
      vertex 155.970245 77.209923 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.857193 77.377327 0.000000
      vertex 182.395859 116.439316 0.000000
      vertex 155.917648 77.296494 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 178.587540 116.552254 0.000000
      vertex 182.395859 116.439316 0.000000
      vertex 155.857193 77.377327 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.789429 77.451889 0.000000
      vertex 178.587540 116.552254 0.000000
      vertex 155.857193 77.377327 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 178.480179 116.557671 0.000000
      vertex 178.587540 116.552254 0.000000
      vertex 155.789429 77.451889 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.714859 77.519661 0.000000
      vertex 178.480179 116.557671 0.000000
      vertex 155.789429 77.451889 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 178.375916 116.573586 0.000000
      vertex 178.480179 116.557671 0.000000
      vertex 155.714859 77.519661 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.634033 77.580101 0.000000
      vertex 178.375916 116.573586 0.000000
      vertex 155.714859 77.519661 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.547455 77.632698 0.000000
      vertex 178.375916 116.573586 0.000000
      vertex 155.634033 77.580101 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 178.375916 116.573586 0.000000
      vertex 155.547455 77.632698 0.000000
      vertex 155.455673 77.676910 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.359207 77.712219 0.000000
      vertex 178.375916 116.573586 0.000000
      vertex 155.455673 77.676910 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.258575 77.738098 0.000000
      vertex 178.375916 116.573586 0.000000
      vertex 155.359207 77.712219 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 178.375916 116.573586 0.000000
      vertex 155.258575 77.738098 0.000000
      vertex 155.154327 77.754005 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.046967 77.759430 0.000000
      vertex 178.375916 116.573586 0.000000
      vertex 155.154327 77.754005 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 154.939606 77.754005 0.000000
      vertex 178.375916 116.573586 0.000000
      vertex 155.046967 77.759430 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 154.939606 77.754005 0.000000
      vertex 154.835358 77.738098 0.000000
      vertex 141.346085 79.319061 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 139.990570 79.869987 0.000000
      vertex 154.939606 77.754005 0.000000
      vertex 141.346085 79.319061 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 178.375916 116.573586 0.000000
      vertex 154.939606 77.754005 0.000000
      vertex 139.990570 79.869987 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 138.647781 80.387527 0.000000
      vertex 178.375916 116.573586 0.000000
      vertex 139.990570 79.869987 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 137.317322 80.873062 0.000000
      vertex 178.375916 116.573586 0.000000
      vertex 138.647781 80.387527 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 142.714767 78.733368 0.000000
      vertex 141.346085 79.319061 0.000000
      vertex 154.835358 77.738098 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 154.734726 77.712219 0.000000
      vertex 142.714767 78.733368 0.000000
      vertex 154.835358 77.738098 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 144.097061 78.111534 0.000000
      vertex 142.714767 78.733368 0.000000
      vertex 154.734726 77.712219 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 154.638260 77.676910 0.000000
      vertex 144.097061 78.111534 0.000000
      vertex 154.734726 77.712219 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 145.493362 77.452171 0.000000
      vertex 144.097061 78.111534 0.000000
      vertex 154.638260 77.676910 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 154.546478 77.632698 0.000000
      vertex 145.493362 77.452171 0.000000
      vertex 154.638260 77.676910 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 154.459900 77.580101 0.000000
      vertex 145.493362 77.452171 0.000000
      vertex 154.546478 77.632698 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 146.904129 76.753906 0.000000
      vertex 145.493362 77.452171 0.000000
      vertex 154.459900 77.580101 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 154.379074 77.519661 0.000000
      vertex 146.904129 76.753906 0.000000
      vertex 154.459900 77.580101 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 154.304504 77.451889 0.000000
      vertex 146.904129 76.753906 0.000000
      vertex 154.379074 77.519661 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 146.904129 76.753906 0.000000
      vertex 154.304504 77.451889 0.000000
      vertex 154.236740 77.377327 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 148.329773 76.015358 0.000000
      vertex 146.904129 76.753906 0.000000
      vertex 154.236740 77.377327 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 154.176285 77.296494 0.000000
      vertex 148.329773 76.015358 0.000000
      vertex 154.236740 77.377327 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 154.123703 77.209923 0.000000
      vertex 148.329773 76.015358 0.000000
      vertex 154.176285 77.296494 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 148.329773 76.015358 0.000000
      vertex 154.123703 77.209923 0.000000
      vertex 154.079483 77.118134 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 149.770706 75.235153 0.000000
      vertex 148.329773 76.015358 0.000000
      vertex 154.079483 77.118134 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 154.044174 77.021667 0.000000
      vertex 149.770706 75.235153 0.000000
      vertex 154.079483 77.118134 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 154.018295 76.921036 0.000000
      vertex 149.770706 75.235153 0.000000
      vertex 154.044174 77.021667 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 149.770706 75.235153 0.000000
      vertex 154.018295 76.921036 0.000000
      vertex 154.002396 76.816788 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 153.996964 76.709427 0.000000
      vertex 149.770706 75.235153 0.000000
      vertex 154.002396 76.816788 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 154.002396 76.602074 0.000000
      vertex 149.770706 75.235153 0.000000
      vertex 153.996964 76.709427 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 149.770706 75.235153 0.000000
      vertex 154.002396 76.602074 0.000000
      vertex 154.018295 76.497818 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 154.044174 76.397186 0.000000
      vertex 149.770706 75.235153 0.000000
      vertex 154.018295 76.497818 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 154.079483 76.300720 0.000000
      vertex 149.770706 75.235153 0.000000
      vertex 154.044174 76.397186 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 149.770706 75.235153 0.000000
      vertex 154.079483 76.300720 0.000000
      vertex 154.123703 76.208939 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 154.176285 76.122360 0.000000
      vertex 149.770706 75.235153 0.000000
      vertex 154.123703 76.208939 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 154.236740 76.041527 0.000000
      vertex 149.770706 75.235153 0.000000
      vertex 154.176285 76.122360 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 149.770706 75.235153 0.000000
      vertex 154.236740 76.041527 0.000000
      vertex 154.304504 75.966965 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 154.379074 75.899193 0.000000
      vertex 149.770706 75.235153 0.000000
      vertex 154.304504 75.966965 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 154.459900 75.838753 0.000000
      vertex 149.770706 75.235153 0.000000
      vertex 154.379074 75.899193 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 149.770706 75.235153 0.000000
      vertex 154.459900 75.838753 0.000000
      vertex 154.546478 75.786156 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 154.638260 75.741943 0.000000
      vertex 149.770706 75.235153 0.000000
      vertex 154.546478 75.786156 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 154.734726 75.706635 0.000000
      vertex 149.770706 75.235153 0.000000
      vertex 154.638260 75.741943 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 149.770706 75.235153 0.000000
      vertex 154.734726 75.706635 0.000000
      vertex 154.835358 75.680763 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 154.939606 75.664848 0.000000
      vertex 149.770706 75.235153 0.000000
      vertex 154.835358 75.680763 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 155.046967 75.659424 0.000000
      vertex 149.770706 75.235153 0.000000
      vertex 154.939606 75.664848 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 155.046967 75.659424 0.000000
      vertex 155.154327 75.664848 0.000000
      vertex 154.936188 72.535622 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 154.552948 72.611450 0.000000
      vertex 155.046967 75.659424 0.000000
      vertex 154.936188 72.535622 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 154.181320 72.737083 0.000000
      vertex 155.046967 75.659424 0.000000
      vertex 154.552948 72.611450 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.154327 75.664848 0.000000
      vertex 155.258575 75.680763 0.000000
      vertex 156.103241 72.612526 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.716431 72.535660 0.000000
      vertex 155.154327 75.664848 0.000000
      vertex 156.103241 72.612526 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.326019 72.510208 0.000000
      vertex 155.154327 75.664848 0.000000
      vertex 155.716431 72.535660 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.258575 75.680763 0.000000
      vertex 155.359207 75.706635 0.000000
      vertex 156.960815 72.994774 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 156.547043 72.769890 0.000000
      vertex 155.258575 75.680763 0.000000
      vertex 156.960815 72.994774 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 156.103241 72.612526 0.000000
      vertex 155.258575 75.680763 0.000000
      vertex 156.547043 72.769890 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 157.334305 73.281586 0.000000
      vertex 156.960815 72.994774 0.000000
      vertex 155.359207 75.706635 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 155.455673 75.741943 0.000000
      vertex 157.334305 73.281586 0.000000
      vertex 155.359207 75.706635 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 157.658264 73.623230 0.000000
      vertex 157.334305 73.281586 0.000000
      vertex 155.455673 75.741943 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 155.547455 75.786156 0.000000
      vertex 157.658264 73.623230 0.000000
      vertex 155.455673 75.741943 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 157.924652 74.011238 0.000000
      vertex 157.658264 73.623230 0.000000
      vertex 155.547455 75.786156 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 155.634033 75.838753 0.000000
      vertex 157.924652 74.011238 0.000000
      vertex 155.547455 75.786156 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 155.714859 75.899193 0.000000
      vertex 157.924652 74.011238 0.000000
      vertex 155.634033 75.838753 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 157.924652 74.011238 0.000000
      vertex 155.714859 75.899193 0.000000
      vertex 155.789429 75.966965 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 155.857193 76.041527 0.000000
      vertex 157.924652 74.011238 0.000000
      vertex 155.789429 75.966965 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 155.917648 76.122360 0.000000
      vertex 157.924652 74.011238 0.000000
      vertex 155.857193 76.041527 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 157.924652 74.011238 0.000000
      vertex 155.917648 76.122360 0.000000
      vertex 155.970245 76.208939 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 156.014450 76.300720 0.000000
      vertex 157.924652 74.011238 0.000000
      vertex 155.970245 76.208939 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 156.049759 76.397186 0.000000
      vertex 157.924652 74.011238 0.000000
      vertex 156.014450 76.300720 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 157.924652 74.011238 0.000000
      vertex 156.049759 76.397186 0.000000
      vertex 156.075638 76.497818 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 156.091553 76.602074 0.000000
      vertex 157.924652 74.011238 0.000000
      vertex 156.075638 76.497818 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.643661 143.422668 0.000000
      vertex 153.688248 148.247864 0.000000
      vertex 153.693665 148.355209 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 153.688248 148.462570 0.000000
      vertex 155.643661 143.422668 0.000000
      vertex 153.693665 148.355209 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 153.672333 148.566818 0.000000
      vertex 155.643661 143.422668 0.000000
      vertex 153.688248 148.462570 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.643661 143.422668 0.000000
      vertex 153.672333 148.566818 0.000000
      vertex 153.646469 148.667450 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 155.643661 192.834167 0.000000
      vertex 155.643661 143.422668 0.000000
      vertex 153.646469 148.667450 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 153.611160 148.763916 0.000000
      vertex 155.643661 192.834167 0.000000
      vertex 153.646469 148.667450 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 153.566940 148.855713 0.000000
      vertex 155.643661 192.834167 0.000000
      vertex 153.611160 148.763916 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.643661 192.834167 0.000000
      vertex 153.566940 148.855713 0.000000
      vertex 153.514343 148.942276 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 153.453903 149.023117 0.000000
      vertex 155.643661 192.834167 0.000000
      vertex 153.514343 148.942276 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 153.386124 149.097672 0.000000
      vertex 155.643661 192.834167 0.000000
      vertex 153.453903 149.023117 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.643661 192.834167 0.000000
      vertex 153.386124 149.097672 0.000000
      vertex 153.311569 149.165451 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 153.230728 149.225891 0.000000
      vertex 155.643661 192.834167 0.000000
      vertex 153.311569 149.165451 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 153.144165 149.278488 0.000000
      vertex 155.643661 192.834167 0.000000
      vertex 153.230728 149.225891 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.643661 192.834167 0.000000
      vertex 153.144165 149.278488 0.000000
      vertex 153.052383 149.322693 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 152.611404 191.618423 0.000000
      vertex 155.643661 192.834167 0.000000
      vertex 153.052383 149.322693 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 152.703186 191.662628 0.000000
      vertex 155.643661 192.834167 0.000000
      vertex 152.611404 191.618423 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 152.611404 191.618423 0.000000
      vertex 153.052383 149.322693 0.000000
      vertex 152.955902 149.358002 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 152.514938 191.583115 0.000000
      vertex 152.611404 191.618423 0.000000
      vertex 152.955902 149.358002 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 152.855286 149.383881 0.000000
      vertex 152.514938 191.583115 0.000000
      vertex 152.955902 149.358002 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 152.414307 191.557236 0.000000
      vertex 152.514938 191.583115 0.000000
      vertex 152.855286 149.383881 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 152.751022 149.399796 0.000000
      vertex 152.414307 191.557236 0.000000
      vertex 152.855286 149.383881 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 152.310059 191.541321 0.000000
      vertex 152.414307 191.557236 0.000000
      vertex 152.751022 149.399796 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 152.643661 149.405212 0.000000
      vertex 152.310059 191.541321 0.000000
      vertex 152.751022 149.399796 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 152.202698 191.535904 0.000000
      vertex 152.310059 191.541321 0.000000
      vertex 152.643661 149.405212 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 114.054306 152.334106 0.000000
      vertex 152.432053 149.383881 0.000000
      vertex 152.331436 149.358002 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 152.234955 149.322693 0.000000
      vertex 114.054306 152.334106 0.000000
      vertex 152.331436 149.358002 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 152.143173 149.278488 0.000000
      vertex 114.054306 152.334106 0.000000
      vertex 152.234955 149.322693 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 114.054306 152.334106 0.000000
      vertex 152.143173 149.278488 0.000000
      vertex 152.056610 149.225891 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 151.975769 149.165451 0.000000
      vertex 114.054306 152.334106 0.000000
      vertex 152.056610 149.225891 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 151.901199 149.097672 0.000000
      vertex 114.054306 152.334106 0.000000
      vertex 151.975769 149.165451 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 114.054306 152.334106 0.000000
      vertex 151.901199 149.097672 0.000000
      vertex 151.833435 149.023117 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 151.772995 148.942276 0.000000
      vertex 114.054306 152.334106 0.000000
      vertex 151.833435 149.023117 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 151.720398 148.855713 0.000000
      vertex 114.054306 152.334106 0.000000
      vertex 151.772995 148.942276 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 114.054306 152.334106 0.000000
      vertex 151.720398 148.855713 0.000000
      vertex 151.676178 148.763916 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 151.640869 148.667450 0.000000
      vertex 114.054306 152.334106 0.000000
      vertex 151.676178 148.763916 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 151.615005 148.566818 0.000000
      vertex 114.054306 152.334106 0.000000
      vertex 151.640869 148.667450 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 114.054306 152.334106 0.000000
      vertex 151.615005 148.566818 0.000000
      vertex 151.599091 148.462570 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 151.593674 148.355209 0.000000
      vertex 114.054306 152.334106 0.000000
      vertex 151.599091 148.462570 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 151.599091 148.247864 0.000000
      vertex 114.054306 152.334106 0.000000
      vertex 151.593674 148.355209 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 114.054306 152.334106 0.000000
      vertex 151.599091 148.247864 0.000000
      vertex 151.615005 148.143600 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 151.640869 148.042969 0.000000
      vertex 114.054306 152.334106 0.000000
      vertex 151.615005 148.143600 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 151.676178 147.946503 0.000000
      vertex 114.054306 152.334106 0.000000
      vertex 151.640869 148.042969 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 150.811142 133.153976 0.000000
      vertex 151.720398 147.854721 0.000000
      vertex 151.772995 147.768143 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 151.833435 147.687317 0.000000
      vertex 150.811142 133.153976 0.000000
      vertex 151.772995 147.768143 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 151.901199 147.612747 0.000000
      vertex 150.811142 133.153976 0.000000
      vertex 151.833435 147.687317 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 150.811142 133.153976 0.000000
      vertex 151.901199 147.612747 0.000000
      vertex 151.975769 147.544983 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 155.444077 141.223419 0.000000
      vertex 150.811142 133.153976 0.000000
      vertex 151.975769 147.544983 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 152.056610 147.484543 0.000000
      vertex 155.444077 141.223419 0.000000
      vertex 151.975769 147.544983 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 152.143173 147.431946 0.000000
      vertex 155.444077 141.223419 0.000000
      vertex 152.056610 147.484543 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.444077 141.223419 0.000000
      vertex 152.143173 147.431946 0.000000
      vertex 152.234955 147.387726 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 155.656876 142.925613 0.000000
      vertex 155.444077 141.223419 0.000000
      vertex 152.234955 147.387726 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 155.695953 142.433929 0.000000
      vertex 155.444077 141.223419 0.000000
      vertex 155.656876 142.925613 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.656876 142.925613 0.000000
      vertex 152.234955 147.387726 0.000000
      vertex 152.331436 147.352417 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 155.643661 143.422668 0.000000
      vertex 155.656876 142.925613 0.000000
      vertex 152.331436 147.352417 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 152.432053 147.326553 0.000000
      vertex 155.643661 143.422668 0.000000
      vertex 152.331436 147.352417 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 152.536316 147.310638 0.000000
      vertex 155.643661 143.422668 0.000000
      vertex 152.432053 147.326553 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.643661 143.422668 0.000000
      vertex 152.536316 147.310638 0.000000
      vertex 152.643661 147.305206 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 152.751022 147.310638 0.000000
      vertex 155.643661 143.422668 0.000000
      vertex 152.643661 147.305206 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 152.855286 147.326553 0.000000
      vertex 155.643661 143.422668 0.000000
      vertex 152.751022 147.310638 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.643661 143.422668 0.000000
      vertex 152.855286 147.326553 0.000000
      vertex 152.955902 147.352417 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 153.052383 147.387726 0.000000
      vertex 155.643661 143.422668 0.000000
      vertex 152.955902 147.352417 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 153.144165 147.431946 0.000000
      vertex 155.643661 143.422668 0.000000
      vertex 153.052383 147.387726 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.643661 143.422668 0.000000
      vertex 153.144165 147.431946 0.000000
      vertex 153.230728 147.484543 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 153.311569 147.544983 0.000000
      vertex 155.643661 143.422668 0.000000
      vertex 153.230728 147.484543 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 153.386124 147.612747 0.000000
      vertex 155.643661 143.422668 0.000000
      vertex 153.311569 147.544983 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.643661 143.422668 0.000000
      vertex 153.386124 147.612747 0.000000
      vertex 153.453903 147.687317 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 153.514343 147.768143 0.000000
      vertex 155.643661 143.422668 0.000000
      vertex 153.453903 147.687317 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 153.566940 147.854721 0.000000
      vertex 155.643661 143.422668 0.000000
      vertex 153.514343 147.768143 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.643661 143.422668 0.000000
      vertex 153.566940 147.854721 0.000000
      vertex 153.611160 147.946503 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 153.646469 148.042969 0.000000
      vertex 155.643661 143.422668 0.000000
      vertex 153.611160 147.946503 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 153.672333 148.143600 0.000000
      vertex 155.643661 143.422668 0.000000
      vertex 153.646469 148.042969 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.643661 143.422668 0.000000
      vertex 153.672333 148.143600 0.000000
      vertex 153.688248 148.247864 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 100.072800 203.224228 0.000000
      vertex 100.046928 203.324844 0.000000
      vertex 103.093575 206.160156 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 104.986458 206.193970 0.000000
      vertex 100.072800 203.224228 0.000000
      vertex 103.093575 206.160156 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 106.855080 206.205231 0.000000
      vertex 100.072800 203.224228 0.000000
      vertex 104.986458 206.193970 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 103.093575 206.160156 0.000000
      vertex 100.046928 203.324844 0.000000
      vertex 100.011620 203.421326 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 101.176178 206.103760 0.000000
      vertex 103.093575 206.160156 0.000000
      vertex 100.011620 203.421326 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.967407 203.513107 0.000000
      vertex 101.176178 206.103760 0.000000
      vertex 100.011620 203.421326 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.914810 203.599670 0.000000
      vertex 101.176178 206.103760 0.000000
      vertex 99.967407 203.513107 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 101.176178 206.103760 0.000000
      vertex 99.914810 203.599670 0.000000
      vertex 99.854362 203.680511 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.786598 203.755081 0.000000
      vertex 101.176178 206.103760 0.000000
      vertex 99.854362 203.680511 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.712036 203.822845 0.000000
      vertex 101.176178 206.103760 0.000000
      vertex 99.786598 203.755081 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 101.176178 206.103760 0.000000
      vertex 99.712036 203.822845 0.000000
      vertex 99.631203 203.883286 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.544624 203.935883 0.000000
      vertex 101.176178 206.103760 0.000000
      vertex 99.631203 203.883286 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.234016 206.024719 0.000000
      vertex 101.176178 206.103760 0.000000
      vertex 99.544624 203.935883 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.452843 203.980103 0.000000
      vertex 99.234016 206.024719 0.000000
      vertex 99.544624 203.935883 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.356377 204.015411 0.000000
      vertex 99.234016 206.024719 0.000000
      vertex 99.452843 203.980103 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.234016 206.024719 0.000000
      vertex 99.356377 204.015411 0.000000
      vertex 99.255745 204.041275 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.151489 204.057190 0.000000
      vertex 99.234016 206.024719 0.000000
      vertex 99.255745 204.041275 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.044136 204.062607 0.000000
      vertex 99.234016 206.024719 0.000000
      vertex 99.151489 204.057190 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 99.044136 204.062607 0.000000
      vertex 98.936775 204.057190 0.000000
      vertex 80.599014 204.288376 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 82.775291 204.572906 0.000000
      vertex 99.044136 204.062607 0.000000
      vertex 80.599014 204.288376 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 84.924553 204.834427 0.000000
      vertex 99.044136 204.062607 0.000000
      vertex 82.775291 204.572906 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 80.599014 204.288376 0.000000
      vertex 98.936775 204.057190 0.000000
      vertex 98.832527 204.041275 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 98.731895 204.015411 0.000000
      vertex 80.599014 204.288376 0.000000
      vertex 98.832527 204.041275 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 98.635429 203.980103 0.000000
      vertex 80.599014 204.288376 0.000000
      vertex 98.731895 204.015411 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 80.599014 204.288376 0.000000
      vertex 98.635429 203.980103 0.000000
      vertex 98.543640 203.935883 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 98.457069 203.883286 0.000000
      vertex 80.599014 204.288376 0.000000
      vertex 98.543640 203.935883 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 98.376236 203.822845 0.000000
      vertex 80.599014 204.288376 0.000000
      vertex 98.457069 203.883286 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 80.599014 204.288376 0.000000
      vertex 98.376236 203.822845 0.000000
      vertex 98.301674 203.755081 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 98.233902 203.680511 0.000000
      vertex 80.599014 204.288376 0.000000
      vertex 98.301674 203.755081 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 98.173462 203.599670 0.000000
      vertex 80.599014 204.288376 0.000000
      vertex 98.233902 203.680511 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 80.599014 204.288376 0.000000
      vertex 98.173462 203.599670 0.000000
      vertex 98.120865 203.513107 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 98.076653 203.421326 0.000000
      vertex 80.599014 204.288376 0.000000
      vertex 98.120865 203.513107 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 98.041344 203.324844 0.000000
      vertex 80.599014 204.288376 0.000000
      vertex 98.076653 203.421326 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 80.599014 204.288376 0.000000
      vertex 98.041344 203.324844 0.000000
      vertex 98.015465 203.224228 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 97.999557 203.119965 0.000000
      vertex 80.599014 204.288376 0.000000
      vertex 98.015465 203.224228 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 97.994133 203.012619 0.000000
      vertex 80.599014 204.288376 0.000000
      vertex 97.999557 203.119965 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 80.599014 204.288376 0.000000
      vertex 97.994133 203.012619 0.000000
      vertex 97.999557 202.905258 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 98.015465 202.800995 0.000000
      vertex 80.599014 204.288376 0.000000
      vertex 97.999557 202.905258 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 98.041344 202.700378 0.000000
      vertex 80.599014 204.288376 0.000000
      vertex 98.015465 202.800995 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 80.599014 204.288376 0.000000
      vertex 98.041344 202.700378 0.000000
      vertex 98.076653 202.603897 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 98.120865 202.512115 0.000000
      vertex 80.599014 204.288376 0.000000
      vertex 98.076653 202.603897 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 98.173462 202.425552 0.000000
      vertex 80.599014 204.288376 0.000000
      vertex 98.120865 202.512115 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 80.599014 204.288376 0.000000
      vertex 98.173462 202.425552 0.000000
      vertex 98.233902 202.344711 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 98.301674 202.270157 0.000000
      vertex 80.599014 204.288376 0.000000
      vertex 98.233902 202.344711 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 98.376236 202.202377 0.000000
      vertex 80.599014 204.288376 0.000000
      vertex 98.301674 202.270157 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 80.599014 204.288376 0.000000
      vertex 98.376236 202.202377 0.000000
      vertex 98.457069 202.141937 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 98.543640 202.089340 0.000000
      vertex 80.599014 204.288376 0.000000
      vertex 98.457069 202.141937 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 98.635429 202.045120 0.000000
      vertex 80.599014 204.288376 0.000000
      vertex 98.543640 202.089340 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 78.395470 203.980820 0.000000
      vertex 80.599014 204.288376 0.000000
      vertex 98.635429 202.045120 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 98.731895 202.009811 0.000000
      vertex 78.395470 203.980820 0.000000
      vertex 98.635429 202.045120 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 76.164421 203.650192 0.000000
      vertex 78.395470 203.980820 0.000000
      vertex 98.731895 202.009811 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 73.905602 203.296448 0.000000
      vertex 76.164421 203.650192 0.000000
      vertex 98.731895 202.009811 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 98.832527 201.983948 0.000000
      vertex 73.905602 203.296448 0.000000
      vertex 98.731895 202.009811 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 71.618774 202.919556 0.000000
      vertex 73.905602 203.296448 0.000000
      vertex 98.832527 201.983948 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 69.303680 202.519470 0.000000
      vertex 71.618774 202.919556 0.000000
      vertex 98.832527 201.983948 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 66.960068 202.096146 0.000000
      vertex 69.303680 202.519470 0.000000
      vertex 98.832527 201.983948 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 64.587700 201.649551 0.000000
      vertex 66.960068 202.096146 0.000000
      vertex 98.832527 201.983948 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 62.186310 201.179642 0.000000
      vertex 64.587700 201.649551 0.000000
      vertex 98.832527 201.983948 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 98.936775 201.968033 0.000000
      vertex 62.186310 201.179642 0.000000
      vertex 98.832527 201.983948 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 59.755661 200.686371 0.000000
      vertex 62.186310 201.179642 0.000000
      vertex 98.936775 201.968033 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 99.044136 201.962616 0.000000
      vertex 59.755661 200.686371 0.000000
      vertex 98.936775 201.968033 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.643661 192.834167 0.000000
      vertex 153.247269 192.478546 0.000000
      vertex 153.252701 192.585907 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 153.247269 192.693253 0.000000
      vertex 155.643661 192.834167 0.000000
      vertex 153.252701 192.585907 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 153.231369 192.797516 0.000000
      vertex 155.643661 192.834167 0.000000
      vertex 153.247269 192.693253 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 155.615860 193.242035 0.000000
      vertex 155.643661 192.834167 0.000000
      vertex 153.231369 192.797516 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 153.205490 192.898148 0.000000
      vertex 155.615860 193.242035 0.000000
      vertex 153.231369 192.797516 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 155.534348 193.636917 0.000000
      vertex 155.615860 193.242035 0.000000
      vertex 153.205490 192.898148 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 153.170181 192.994614 0.000000
      vertex 155.534348 193.636917 0.000000
      vertex 153.205490 192.898148 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 153.125961 193.086395 0.000000
      vertex 155.534348 193.636917 0.000000
      vertex 153.170181 192.994614 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.534348 193.636917 0.000000
      vertex 153.125961 193.086395 0.000000
      vertex 153.073380 193.172974 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 153.012924 193.253799 0.000000
      vertex 155.534348 193.636917 0.000000
      vertex 153.073380 193.172974 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 152.945160 193.328369 0.000000
      vertex 155.534348 193.636917 0.000000
      vertex 153.012924 193.253799 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.534348 193.636917 0.000000
      vertex 152.945160 193.328369 0.000000
      vertex 152.870590 193.396133 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 152.789764 193.456573 0.000000
      vertex 155.534348 193.636917 0.000000
      vertex 152.870590 193.396133 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 152.703186 193.509171 0.000000
      vertex 155.534348 193.636917 0.000000
      vertex 152.789764 193.456573 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.534348 193.636917 0.000000
      vertex 152.703186 193.509171 0.000000
      vertex 152.611404 193.553391 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 152.514938 193.588699 0.000000
      vertex 155.534348 193.636917 0.000000
      vertex 152.611404 193.553391 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 152.414307 193.614578 0.000000
      vertex 155.534348 193.636917 0.000000
      vertex 152.514938 193.588699 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.534348 193.636917 0.000000
      vertex 152.414307 193.614578 0.000000
      vertex 152.310059 193.630478 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 152.202698 193.635910 0.000000
      vertex 155.534348 193.636917 0.000000
      vertex 152.310059 193.630478 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 155.401886 194.014145 0.000000
      vertex 155.534348 193.636917 0.000000
      vertex 152.202698 193.635910 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 155.221268 194.369049 0.000000
      vertex 155.401886 194.014145 0.000000
      vertex 152.202698 193.635910 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 154.995285 194.696945 0.000000
      vertex 155.221268 194.369049 0.000000
      vertex 152.202698 193.635910 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 154.726730 194.993134 0.000000
      vertex 154.995285 194.696945 0.000000
      vertex 152.202698 193.635910 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 154.418381 195.252945 0.000000
      vertex 154.726730 194.993134 0.000000
      vertex 152.202698 193.635910 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 154.073029 195.471695 0.000000
      vertex 154.418381 195.252945 0.000000
      vertex 152.202698 193.635910 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 152.502426 196.322800 0.000000
      vertex 154.073029 195.471695 0.000000
      vertex 152.202698 193.635910 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 152.095337 193.630478 0.000000
      vertex 152.502426 196.322800 0.000000
      vertex 152.202698 193.635910 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 151.991089 193.614578 0.000000
      vertex 152.502426 196.322800 0.000000
      vertex 152.095337 193.630478 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 152.502426 196.322800 0.000000
      vertex 151.991089 193.614578 0.000000
      vertex 151.890457 193.588699 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 151.793991 193.553391 0.000000
      vertex 152.502426 196.322800 0.000000
      vertex 151.890457 193.588699 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 151.344193 196.936234 0.000000
      vertex 152.502426 196.322800 0.000000
      vertex 151.793991 193.553391 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 151.702209 193.509171 0.000000
      vertex 151.344193 196.936234 0.000000
      vertex 151.793991 193.553391 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 151.615631 193.456573 0.000000
      vertex 151.344193 196.936234 0.000000
      vertex 151.702209 193.509171 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 151.344193 196.936234 0.000000
      vertex 151.615631 193.456573 0.000000
      vertex 151.534805 193.396133 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 151.460236 193.328369 0.000000
      vertex 151.344193 196.936234 0.000000
      vertex 151.534805 193.396133 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 150.170212 197.529663 0.000000
      vertex 151.344193 196.936234 0.000000
      vertex 151.460236 193.328369 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 151.392471 193.253799 0.000000
      vertex 150.170212 197.529663 0.000000
      vertex 151.460236 193.328369 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 151.332016 193.172974 0.000000
      vertex 150.170212 197.529663 0.000000
      vertex 151.392471 193.253799 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 150.170212 197.529663 0.000000
      vertex 151.332016 193.172974 0.000000
      vertex 151.279419 193.086395 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 148.980331 198.103134 0.000000
      vertex 150.170212 197.529663 0.000000
      vertex 151.279419 193.086395 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 151.235214 192.994614 0.000000
      vertex 148.980331 198.103134 0.000000
      vertex 151.279419 193.086395 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 151.199905 192.898148 0.000000
      vertex 148.980331 198.103134 0.000000
      vertex 151.235214 192.994614 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 147.774384 198.656693 0.000000
      vertex 148.980331 198.103134 0.000000
      vertex 151.199905 192.898148 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 151.174026 192.797516 0.000000
      vertex 147.774384 198.656693 0.000000
      vertex 151.199905 192.898148 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 151.158112 192.693253 0.000000
      vertex 147.774384 198.656693 0.000000
      vertex 151.174026 192.797516 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 146.552231 199.190353 0.000000
      vertex 147.774384 198.656693 0.000000
      vertex 151.158112 192.693253 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 151.152695 192.585907 0.000000
      vertex 146.552231 199.190353 0.000000
      vertex 151.158112 192.693253 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 145.313721 199.704163 0.000000
      vertex 146.552231 199.190353 0.000000
      vertex 151.152695 192.585907 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 151.158112 192.478546 0.000000
      vertex 145.313721 199.704163 0.000000
      vertex 151.152695 192.585907 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 151.174026 192.374298 0.000000
      vertex 145.313721 199.704163 0.000000
      vertex 151.158112 192.478546 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 144.058670 200.198151 0.000000
      vertex 145.313721 199.704163 0.000000
      vertex 151.174026 192.374298 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 151.199905 192.273666 0.000000
      vertex 144.058670 200.198151 0.000000
      vertex 151.174026 192.374298 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 142.786942 200.672363 0.000000
      vertex 144.058670 200.198151 0.000000
      vertex 151.199905 192.273666 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 141.498383 201.126816 0.000000
      vertex 142.786942 200.672363 0.000000
      vertex 151.199905 192.273666 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 151.235214 192.177200 0.000000
      vertex 141.498383 201.126816 0.000000
      vertex 151.199905 192.273666 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 140.192825 201.561539 0.000000
      vertex 141.498383 201.126816 0.000000
      vertex 151.235214 192.177200 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 151.279419 192.085403 0.000000
      vertex 140.192825 201.561539 0.000000
      vertex 151.235214 192.177200 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.643661 192.834167 0.000000
      vertex 152.703186 191.662628 0.000000
      vertex 152.789764 191.715225 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 152.870590 191.775665 0.000000
      vertex 155.643661 192.834167 0.000000
      vertex 152.789764 191.715225 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 152.945160 191.843445 0.000000
      vertex 155.643661 192.834167 0.000000
      vertex 152.870590 191.775665 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.643661 192.834167 0.000000
      vertex 152.945160 191.843445 0.000000
      vertex 153.012924 191.917999 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 153.073380 191.998840 0.000000
      vertex 155.643661 192.834167 0.000000
      vertex 153.012924 191.917999 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 153.125961 192.085403 0.000000
      vertex 155.643661 192.834167 0.000000
      vertex 153.073380 191.998840 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.643661 192.834167 0.000000
      vertex 153.125961 192.085403 0.000000
      vertex 153.170181 192.177200 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 153.205490 192.273666 0.000000
      vertex 155.643661 192.834167 0.000000
      vertex 153.170181 192.177200 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 153.231369 192.374298 0.000000
      vertex 155.643661 192.834167 0.000000
      vertex 153.205490 192.273666 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.643661 192.834167 0.000000
      vertex 153.231369 192.374298 0.000000
      vertex 153.247269 192.478546 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 92.314682 106.466446 0.000000
      vertex 34.295017 110.226204 0.000000
      vertex 34.300442 110.333557 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 34.295017 110.440910 0.000000
      vertex 92.314682 106.466446 0.000000
      vertex 34.300442 110.333557 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 34.279106 110.545166 0.000000
      vertex 92.314682 106.466446 0.000000
      vertex 34.295017 110.440910 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 92.314682 106.466446 0.000000
      vertex 34.279106 110.545166 0.000000
      vertex 34.253235 110.645798 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 34.217926 110.742264 0.000000
      vertex 92.314682 106.466446 0.000000
      vertex 34.253235 110.645798 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 34.173710 110.834053 0.000000
      vertex 92.314682 106.466446 0.000000
      vertex 34.217926 110.742264 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 92.314682 106.466446 0.000000
      vertex 34.173710 110.834053 0.000000
      vertex 34.121117 110.920624 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 34.060669 111.001457 0.000000
      vertex 92.314682 106.466446 0.000000
      vertex 34.121117 110.920624 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 33.992901 111.076019 0.000000
      vertex 92.314682 106.466446 0.000000
      vertex 34.060669 111.001457 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 92.314682 106.466446 0.000000
      vertex 33.992901 111.076019 0.000000
      vertex 33.918339 111.143791 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 29.343874 190.965912 0.000000
      vertex 32.841732 111.301048 0.000000
      vertex 32.749947 111.256828 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 29.343874 109.466438 0.000000
      vertex 29.343874 190.965912 0.000000
      vertex 32.749947 111.256828 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 32.663376 111.204239 0.000000
      vertex 29.343874 109.466438 0.000000
      vertex 32.749947 111.256828 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 32.582542 111.143791 0.000000
      vertex 29.343874 109.466438 0.000000
      vertex 32.663376 111.204239 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 29.343874 109.466438 0.000000
      vertex 32.582542 111.143791 0.000000
      vertex 32.507977 111.076019 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 32.440208 111.001457 0.000000
      vertex 29.343874 109.466438 0.000000
      vertex 32.507977 111.076019 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 32.379765 110.920624 0.000000
      vertex 29.343874 109.466438 0.000000
      vertex 32.440208 111.001457 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 29.343874 109.466438 0.000000
      vertex 32.379765 110.920624 0.000000
      vertex 32.327168 110.834053 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 32.282955 110.742264 0.000000
      vertex 29.343874 109.466438 0.000000
      vertex 32.327168 110.834053 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 32.247646 110.645798 0.000000
      vertex 29.343874 109.466438 0.000000
      vertex 32.282955 110.742264 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 29.343874 109.466438 0.000000
      vertex 32.247646 110.645798 0.000000
      vertex 32.221771 110.545166 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 32.205860 110.440910 0.000000
      vertex 29.343874 109.466438 0.000000
      vertex 32.221771 110.545166 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 32.200439 110.333557 0.000000
      vertex 29.343874 109.466438 0.000000
      vertex 32.205860 110.440910 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 29.343874 109.466438 0.000000
      vertex 32.200439 110.333557 0.000000
      vertex 32.205860 110.226204 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 32.221771 110.121948 0.000000
      vertex 29.343874 109.466438 0.000000
      vertex 32.205860 110.226204 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 32.247646 110.021317 0.000000
      vertex 29.343874 109.466438 0.000000
      vertex 32.221771 110.121948 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 29.343874 109.466438 0.000000
      vertex 32.247646 110.021317 0.000000
      vertex 32.282955 109.924850 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 29.359362 109.159706 0.000000
      vertex 29.343874 109.466438 0.000000
      vertex 32.282955 109.924850 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 32.327168 109.833069 0.000000
      vertex 29.359362 109.159706 0.000000
      vertex 32.282955 109.924850 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 32.379765 109.746490 0.000000
      vertex 29.359362 109.159706 0.000000
      vertex 32.327168 109.833069 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 29.359362 109.159706 0.000000
      vertex 32.379765 109.746490 0.000000
      vertex 32.440208 109.665665 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 32.507977 109.591095 0.000000
      vertex 29.359362 109.159706 0.000000
      vertex 32.440208 109.665665 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 32.582542 109.523331 0.000000
      vertex 29.359362 109.159706 0.000000
      vertex 32.507977 109.591095 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 29.359362 109.159706 0.000000
      vertex 32.582542 109.523331 0.000000
      vertex 32.663376 109.462883 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 32.749947 109.410286 0.000000
      vertex 29.359362 109.159706 0.000000
      vertex 32.663376 109.462883 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 32.841732 109.366074 0.000000
      vertex 29.359362 109.159706 0.000000
      vertex 32.749947 109.410286 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 29.359362 109.159706 0.000000
      vertex 32.841732 109.366074 0.000000
      vertex 32.938202 109.330765 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 33.038826 109.304893 0.000000
      vertex 29.359362 109.159706 0.000000
      vertex 32.938202 109.330765 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 33.143082 109.288979 0.000000
      vertex 29.359362 109.159706 0.000000
      vertex 33.038826 109.304893 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 29.359362 109.159706 0.000000
      vertex 33.143082 109.288979 0.000000
      vertex 33.250439 109.283562 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 29.404823 108.861832 0.000000
      vertex 29.359362 109.159706 0.000000
      vertex 33.250439 109.283562 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 29.478748 108.574333 0.000000
      vertex 29.404823 108.861832 0.000000
      vertex 33.250439 109.283562 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 29.579628 108.298706 0.000000
      vertex 29.478748 108.574333 0.000000
      vertex 33.250439 109.283562 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 29.705956 108.036461 0.000000
      vertex 29.579628 108.298706 0.000000
      vertex 33.250439 109.283562 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 29.856224 107.789116 0.000000
      vertex 29.705956 108.036461 0.000000
      vertex 33.250439 109.283562 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 30.028925 107.558167 0.000000
      vertex 29.856224 107.789116 0.000000
      vertex 33.250439 109.283562 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 30.222549 107.345123 0.000000
      vertex 30.028925 107.558167 0.000000
      vertex 33.250439 109.283562 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 30.435591 107.151497 0.000000
      vertex 30.222549 107.345123 0.000000
      vertex 33.250439 109.283562 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 30.666540 106.978798 0.000000
      vertex 30.435591 107.151497 0.000000
      vertex 33.250439 109.283562 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 30.913891 106.828529 0.000000
      vertex 30.666540 106.978798 0.000000
      vertex 33.250439 109.283562 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 31.176132 106.702202 0.000000
      vertex 30.913891 106.828529 0.000000
      vertex 33.250439 109.283562 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 31.451757 106.601318 0.000000
      vertex 31.176132 106.702202 0.000000
      vertex 33.250439 109.283562 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 31.739260 106.527397 0.000000
      vertex 31.451757 106.601318 0.000000
      vertex 33.250439 109.283562 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 32.037132 106.481934 0.000000
      vertex 31.739260 106.527397 0.000000
      vertex 33.250439 109.283562 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 32.343864 106.466446 0.000000
      vertex 32.037132 106.481934 0.000000
      vertex 33.250439 109.283562 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 33.357796 109.288979 0.000000
      vertex 32.343864 106.466446 0.000000
      vertex 33.250439 109.283562 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 33.462051 109.304893 0.000000
      vertex 32.343864 106.466446 0.000000
      vertex 33.357796 109.288979 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 32.343864 106.466446 0.000000
      vertex 33.462051 109.304893 0.000000
      vertex 33.562675 109.330765 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 33.659145 109.366074 0.000000
      vertex 32.343864 106.466446 0.000000
      vertex 33.562675 109.330765 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 33.750931 109.410286 0.000000
      vertex 32.343864 106.466446 0.000000
      vertex 33.659145 109.366074 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 32.343864 106.466446 0.000000
      vertex 33.750931 109.410286 0.000000
      vertex 33.837505 109.462883 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 33.918339 109.523331 0.000000
      vertex 32.343864 106.466446 0.000000
      vertex 33.837505 109.462883 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 33.992901 109.591095 0.000000
      vertex 32.343864 106.466446 0.000000
      vertex 33.918339 109.523331 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 32.343864 106.466446 0.000000
      vertex 33.992901 109.591095 0.000000
      vertex 34.060669 109.665665 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 34.121117 109.746490 0.000000
      vertex 32.343864 106.466446 0.000000
      vertex 34.060669 109.665665 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 92.314682 106.466446 0.000000
      vertex 32.343864 106.466446 0.000000
      vertex 34.121117 109.746490 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 34.173710 109.833069 0.000000
      vertex 92.314682 106.466446 0.000000
      vertex 34.121117 109.746490 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 34.217926 109.924850 0.000000
      vertex 92.314682 106.466446 0.000000
      vertex 34.173710 109.833069 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 92.314682 106.466446 0.000000
      vertex 34.217926 109.924850 0.000000
      vertex 34.253235 110.021317 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 34.279106 110.121948 0.000000
      vertex 92.314682 106.466446 0.000000
      vertex 34.253235 110.021317 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 34.295017 110.226204 0.000000
      vertex 92.314682 106.466446 0.000000
      vertex 34.279106 110.121948 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 179.637527 117.602249 0.000000
      vertex 179.632111 117.709610 0.000000
      vertex 182.775024 117.568314 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 182.724686 117.279236 0.000000
      vertex 179.637527 117.602249 0.000000
      vertex 182.775024 117.568314 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 179.632111 117.494896 0.000000
      vertex 179.637527 117.602249 0.000000
      vertex 182.724686 117.279236 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 182.645081 116.993332 0.000000
      vertex 179.632111 117.494896 0.000000
      vertex 182.724686 117.279236 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 182.535660 116.712677 0.000000
      vertex 179.632111 117.494896 0.000000
      vertex 182.645081 116.993332 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 182.796646 117.858521 0.000000
      vertex 182.775024 117.568314 0.000000
      vertex 179.632111 117.709610 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 179.616196 117.813866 0.000000
      vertex 182.796646 117.858521 0.000000
      vertex 179.632111 117.709610 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 182.790100 118.147789 0.000000
      vertex 182.796646 117.858521 0.000000
      vertex 179.616196 117.813866 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 182.755951 118.434067 0.000000
      vertex 182.790100 118.147789 0.000000
      vertex 179.616196 117.813866 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 179.590332 117.914490 0.000000
      vertex 182.755951 118.434067 0.000000
      vertex 179.616196 117.813866 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 182.694733 118.715286 0.000000
      vertex 182.755951 118.434067 0.000000
      vertex 179.590332 117.914490 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 179.555023 118.010956 0.000000
      vertex 182.694733 118.715286 0.000000
      vertex 179.590332 117.914490 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 179.510803 118.102745 0.000000
      vertex 182.694733 118.715286 0.000000
      vertex 179.555023 118.010956 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 182.694733 118.715286 0.000000
      vertex 179.510803 118.102745 0.000000
      vertex 179.458206 118.189316 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 179.397766 118.270149 0.000000
      vertex 182.694733 118.715286 0.000000
      vertex 179.458206 118.189316 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 179.330002 118.344711 0.000000
      vertex 182.694733 118.715286 0.000000
      vertex 179.397766 118.270149 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 182.694733 118.715286 0.000000
      vertex 179.330002 118.344711 0.000000
      vertex 179.255432 118.412483 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 179.174606 118.472931 0.000000
      vertex 182.694733 118.715286 0.000000
      vertex 179.255432 118.412483 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 179.088028 118.525520 0.000000
      vertex 182.694733 118.715286 0.000000
      vertex 179.174606 118.472931 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 182.694733 118.715286 0.000000
      vertex 179.088028 118.525520 0.000000
      vertex 178.996246 118.569740 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 178.899765 118.605049 0.000000
      vertex 182.694733 118.715286 0.000000
      vertex 178.996246 118.569740 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 178.799149 118.630920 0.000000
      vertex 182.694733 118.715286 0.000000
      vertex 178.899765 118.605049 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 182.694733 118.715286 0.000000
      vertex 178.799149 118.630920 0.000000
      vertex 178.694885 118.646828 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 178.587540 118.652252 0.000000
      vertex 182.694733 118.715286 0.000000
      vertex 178.694885 118.646828 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 182.607010 118.989403 0.000000
      vertex 182.694733 118.715286 0.000000
      vertex 178.587540 118.652252 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 182.493332 119.254356 0.000000
      vertex 182.607010 118.989403 0.000000
      vertex 178.587540 118.652252 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 182.354263 119.508080 0.000000
      vertex 182.493332 119.254356 0.000000
      vertex 178.587540 118.652252 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 182.190323 119.748520 0.000000
      vertex 182.354263 119.508080 0.000000
      vertex 178.587540 118.652252 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 182.002090 119.973618 0.000000
      vertex 182.190323 119.748520 0.000000
      vertex 178.587540 118.652252 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 181.790115 120.181313 0.000000
      vertex 182.002090 119.973618 0.000000
      vertex 178.587540 118.652252 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 181.554932 120.369553 0.000000
      vertex 181.790115 120.181313 0.000000
      vertex 178.587540 118.652252 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 181.297104 120.536278 0.000000
      vertex 181.554932 120.369553 0.000000
      vertex 178.587540 118.652252 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 178.700302 122.035522 0.000000
      vertex 181.297104 120.536278 0.000000
      vertex 178.587540 118.652252 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 178.480179 118.646828 0.000000
      vertex 178.700302 122.035522 0.000000
      vertex 178.587540 118.652252 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 178.375916 118.630920 0.000000
      vertex 178.700302 122.035522 0.000000
      vertex 178.480179 118.646828 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 178.700302 122.035522 0.000000
      vertex 178.375916 118.630920 0.000000
      vertex 178.275299 118.605049 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 178.178833 118.569740 0.000000
      vertex 178.700302 122.035522 0.000000
      vertex 178.275299 118.605049 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 178.087036 118.525520 0.000000
      vertex 178.700302 122.035522 0.000000
      vertex 178.178833 118.569740 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 177.691559 122.619560 0.000000
      vertex 178.700302 122.035522 0.000000
      vertex 178.087036 118.525520 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 178.000473 118.472931 0.000000
      vertex 177.691559 122.619560 0.000000
      vertex 178.087036 118.525520 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 177.919632 118.412483 0.000000
      vertex 177.691559 122.619560 0.000000
      vertex 178.000473 118.472931 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 177.691559 122.619560 0.000000
      vertex 177.919632 118.412483 0.000000
      vertex 177.845078 118.344711 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 176.706894 123.193161 0.000000
      vertex 177.691559 122.619560 0.000000
      vertex 177.845078 118.344711 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 177.777298 118.270149 0.000000
      vertex 176.706894 123.193161 0.000000
      vertex 177.845078 118.344711 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 177.716858 118.189316 0.000000
      vertex 176.706894 123.193161 0.000000
      vertex 177.777298 118.270149 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 175.746231 123.756653 0.000000
      vertex 176.706894 123.193161 0.000000
      vertex 177.716858 118.189316 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 177.664261 118.102745 0.000000
      vertex 175.746231 123.756653 0.000000
      vertex 177.716858 118.189316 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 177.620056 118.010956 0.000000
      vertex 175.746231 123.756653 0.000000
      vertex 177.664261 118.102745 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 160.853790 126.227402 0.000000
      vertex 160.949097 126.200821 0.000000
      vertex 177.845078 116.859787 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 177.919632 116.792023 0.000000
      vertex 160.853790 126.227402 0.000000
      vertex 177.845078 116.859787 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 92.621277 106.450966 0.000000
      vertex 160.853790 126.227402 0.000000
      vertex 177.919632 116.792023 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 178.000473 116.731575 0.000000
      vertex 92.621277 106.450966 0.000000
      vertex 177.919632 116.792023 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 178.087036 116.678978 0.000000
      vertex 92.621277 106.450966 0.000000
      vertex 178.000473 116.731575 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 92.621277 106.450966 0.000000
      vertex 178.087036 116.678978 0.000000
      vertex 178.178833 116.634766 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 178.275299 116.599457 0.000000
      vertex 92.621277 106.450966 0.000000
      vertex 178.178833 116.634766 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 178.375916 116.573586 0.000000
      vertex 92.621277 106.450966 0.000000
      vertex 178.275299 116.599457 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 182.395859 116.439316 0.000000
      vertex 178.587540 116.552254 0.000000
      vertex 178.694885 116.557671 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 178.799149 116.573586 0.000000
      vertex 182.395859 116.439316 0.000000
      vertex 178.694885 116.557671 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 178.899765 116.599457 0.000000
      vertex 182.395859 116.439316 0.000000
      vertex 178.799149 116.573586 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 182.395859 116.439316 0.000000
      vertex 178.899765 116.599457 0.000000
      vertex 178.996246 116.634766 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 179.088028 116.678978 0.000000
      vertex 182.395859 116.439316 0.000000
      vertex 178.996246 116.634766 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 179.174606 116.731575 0.000000
      vertex 182.395859 116.439316 0.000000
      vertex 179.088028 116.678978 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 182.395859 116.439316 0.000000
      vertex 179.174606 116.731575 0.000000
      vertex 179.255432 116.792023 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 179.330002 116.859787 0.000000
      vertex 182.395859 116.439316 0.000000
      vertex 179.255432 116.792023 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 179.397766 116.934357 0.000000
      vertex 182.395859 116.439316 0.000000
      vertex 179.330002 116.859787 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 182.395859 116.439316 0.000000
      vertex 179.397766 116.934357 0.000000
      vertex 179.458206 117.015190 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 179.510803 117.101761 0.000000
      vertex 182.395859 116.439316 0.000000
      vertex 179.458206 117.015190 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 179.555023 117.193542 0.000000
      vertex 182.395859 116.439316 0.000000
      vertex 179.510803 117.101761 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 182.395859 116.439316 0.000000
      vertex 179.555023 117.193542 0.000000
      vertex 179.590332 117.290016 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 179.616196 117.390640 0.000000
      vertex 182.395859 116.439316 0.000000
      vertex 179.590332 117.290016 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 182.535660 116.712677 0.000000
      vertex 182.395859 116.439316 0.000000
      vertex 179.616196 117.390640 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 179.632111 117.494896 0.000000
      vertex 182.535660 116.712677 0.000000
      vertex 179.616196 117.390640 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 155.154327 75.664848 0.000000
      vertex 155.326019 72.510208 0.000000
      vertex 154.936188 72.535622 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.046967 75.659424 0.000000
      vertex 154.181320 72.737083 0.000000
      vertex 153.826370 72.911903 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 151.227386 74.411903 0.000000
      vertex 155.046967 75.659424 0.000000
      vertex 153.826370 72.911903 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 149.770706 75.235153 0.000000
      vertex 155.046967 75.659424 0.000000
      vertex 151.227386 74.411903 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 178.375916 116.573586 0.000000
      vertex 137.317322 80.873062 0.000000
      vertex 135.998749 81.327972 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 134.691620 81.753632 0.000000
      vertex 178.375916 116.573586 0.000000
      vertex 135.998749 81.327972 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 133.395538 82.151428 0.000000
      vertex 178.375916 116.573586 0.000000
      vertex 134.691620 81.753632 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 178.375916 116.573586 0.000000
      vertex 133.395538 82.151428 0.000000
      vertex 132.110062 82.522736 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 130.834747 82.868935 0.000000
      vertex 178.375916 116.573586 0.000000
      vertex 132.110062 82.522736 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 129.569199 83.191406 0.000000
      vertex 178.375916 116.573586 0.000000
      vertex 130.834747 82.868935 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 178.375916 116.573586 0.000000
      vertex 129.569199 83.191406 0.000000
      vertex 128.312958 83.491524 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 127.065620 83.770683 0.000000
      vertex 178.375916 116.573586 0.000000
      vertex 128.312958 83.491524 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 124.595909 84.271599 0.000000
      vertex 178.375916 116.573586 0.000000
      vertex 127.065620 83.770683 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 124.595909 84.271599 0.000000
      vertex 122.156654 84.705185 0.000000
      vertex 95.077667 104.635017 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 94.951401 104.897141 0.000000
      vertex 124.595909 84.271599 0.000000
      vertex 95.077667 104.635017 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 178.375916 116.573586 0.000000
      vertex 124.595909 84.271599 0.000000
      vertex 94.951401 104.897141 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 94.801201 105.144379 0.000000
      vertex 178.375916 116.573586 0.000000
      vertex 94.951401 104.897141 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 94.628578 105.375221 0.000000
      vertex 178.375916 116.573586 0.000000
      vertex 94.801201 105.144379 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 95.077667 104.635017 0.000000
      vertex 122.156654 84.705185 0.000000
      vertex 119.744423 85.082497 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 95.178505 104.359512 0.000000
      vertex 95.077667 104.635017 0.000000
      vertex 119.744423 85.082497 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 117.355804 85.414551 0.000000
      vertex 95.178505 104.359512 0.000000
      vertex 119.744423 85.082497 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 95.252396 104.072144 0.000000
      vertex 95.178505 104.359512 0.000000
      vertex 117.355804 85.414551 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 114.987381 85.712395 0.000000
      vertex 95.252396 104.072144 0.000000
      vertex 117.355804 85.414551 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 178.375916 116.573586 0.000000
      vertex 94.628578 105.375221 0.000000
      vertex 94.435036 105.588165 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 94.222092 105.781708 0.000000
      vertex 178.375916 116.573586 0.000000
      vertex 94.435036 105.588165 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 93.991249 105.954330 0.000000
      vertex 178.375916 116.573586 0.000000
      vertex 94.222092 105.781708 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 178.375916 116.573586 0.000000
      vertex 93.991249 105.954330 0.000000
      vertex 93.744011 106.104530 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 93.481888 106.230797 0.000000
      vertex 178.375916 116.573586 0.000000
      vertex 93.744011 106.104530 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 93.206390 106.331635 0.000000
      vertex 178.375916 116.573586 0.000000
      vertex 93.481888 106.230797 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 178.375916 116.573586 0.000000
      vertex 93.206390 106.331635 0.000000
      vertex 92.919014 106.405525 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 92.621277 106.450966 0.000000
      vertex 178.375916 116.573586 0.000000
      vertex 92.919014 106.405525 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 33.052002 191.662552 0.000000
      vertex 36.521648 195.189407 0.000000
      vertex 39.226933 195.894669 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 41.900700 196.576218 0.000000
      vertex 33.052002 191.662552 0.000000
      vertex 39.226933 195.894669 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 44.543201 197.234085 0.000000
      vertex 33.052002 191.662552 0.000000
      vertex 41.900700 196.576218 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 33.052002 191.662552 0.000000
      vertex 44.543201 197.234085 0.000000
      vertex 47.154690 197.868317 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 49.735413 198.478958 0.000000
      vertex 33.052002 191.662552 0.000000
      vertex 47.154690 197.868317 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 52.285622 199.066055 0.000000
      vertex 33.052002 191.662552 0.000000
      vertex 49.735413 198.478958 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 33.052002 191.662552 0.000000
      vertex 52.285622 199.066055 0.000000
      vertex 54.805565 199.629623 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 57.295494 200.169708 0.000000
      vertex 33.052002 191.662552 0.000000
      vertex 54.805565 199.629623 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 59.755661 200.686371 0.000000
      vertex 33.052002 191.662552 0.000000
      vertex 57.295494 200.169708 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.044136 204.062607 0.000000
      vertex 84.924553 204.834427 0.000000
      vertex 87.047050 205.073013 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 89.143036 205.288681 0.000000
      vertex 99.044136 204.062607 0.000000
      vertex 87.047050 205.073013 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 91.212761 205.481461 0.000000
      vertex 99.044136 204.062607 0.000000
      vertex 89.143036 205.288681 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.044136 204.062607 0.000000
      vertex 91.212761 205.481461 0.000000
      vertex 93.256470 205.651428 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 95.274414 205.798599 0.000000
      vertex 99.044136 204.062607 0.000000
      vertex 93.256470 205.651428 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 97.266846 205.923019 0.000000
      vertex 99.044136 204.062607 0.000000
      vertex 95.274414 205.798599 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 99.044136 204.062607 0.000000
      vertex 97.266846 205.923019 0.000000
      vertex 99.234016 206.024719 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 100.072800 203.224228 0.000000
      vertex 106.855080 206.205231 0.000000
      vertex 108.573997 206.195755 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 110.272499 206.167313 0.000000
      vertex 100.072800 203.224228 0.000000
      vertex 108.573997 206.195755 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 111.950722 206.119843 0.000000
      vertex 100.072800 203.224228 0.000000
      vertex 110.272499 206.167313 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 100.072800 203.224228 0.000000
      vertex 111.950722 206.119843 0.000000
      vertex 113.608826 206.053345 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 124.013397 203.163162 0.000000
      vertex 115.246971 205.967773 0.000000
      vertex 116.865311 205.863083 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 118.464005 205.739258 0.000000
      vertex 124.013397 203.163162 0.000000
      vertex 116.865311 205.863083 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 120.043213 205.596252 0.000000
      vertex 124.013397 203.163162 0.000000
      vertex 118.464005 205.739258 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 124.013397 203.163162 0.000000
      vertex 120.043213 205.596252 0.000000
      vertex 121.603073 205.434021 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 123.143761 205.252563 0.000000
      vertex 124.013397 203.163162 0.000000
      vertex 121.603073 205.434021 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 124.665428 205.051819 0.000000
      vertex 124.013397 203.163162 0.000000
      vertex 123.143761 205.252563 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 155.444077 141.223419 0.000000
      vertex 155.695953 142.433929 0.000000
      vertex 155.704941 142.118973 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 155.665619 141.808502 0.000000
      vertex 155.444077 141.223419 0.000000
      vertex 155.704941 142.118973 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 155.578491 141.508118 0.000000
      vertex 155.444077 141.223419 0.000000
      vertex 155.665619 141.808502 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 92.621277 106.450966 0.000000
      vertex 150.742050 132.304855 0.000000
      vertex 150.779968 132.216675 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 150.826340 132.132233 0.000000
      vertex 92.621277 106.450966 0.000000
      vertex 150.779968 132.216675 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 150.880951 132.052216 0.000000
      vertex 92.621277 106.450966 0.000000
      vertex 150.826340 132.132233 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 92.621277 106.450966 0.000000
      vertex 150.880951 132.052216 0.000000
      vertex 150.943649 131.977310 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 151.014252 131.908188 0.000000
      vertex 92.621277 106.450966 0.000000
      vertex 150.943649 131.977310 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 151.092545 131.845535 0.000000
      vertex 92.621277 106.450966 0.000000
      vertex 151.014252 131.908188 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 92.621277 106.450966 0.000000
      vertex 151.092545 131.845535 0.000000
      vertex 151.178375 131.790039 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 160.669098 126.310570 0.000000
      vertex 92.621277 106.450966 0.000000
      vertex 151.178375 131.790039 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 160.760223 126.263924 0.000000
      vertex 92.621277 106.450966 0.000000
      vertex 160.669098 126.310570 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 92.621277 106.450966 0.000000
      vertex 160.760223 126.263924 0.000000
      vertex 160.853790 126.227402 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 167.983627 126.039055 0.000000
      vertex 161.334137 126.190285 0.000000
      vertex 161.427902 126.210670 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 161.519318 126.239899 0.000000
      vertex 167.983627 126.039055 0.000000
      vertex 161.427902 126.210670 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 161.607651 126.277786 0.000000
      vertex 167.983627 126.039055 0.000000
      vertex 161.519318 126.239899 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 167.983627 126.039055 0.000000
      vertex 161.607651 126.277786 0.000000
      vertex 161.692261 126.324142 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 161.772430 126.378792 0.000000
      vertex 167.983627 126.039055 0.000000
      vertex 161.692261 126.324142 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 161.847504 126.441544 0.000000
      vertex 167.983627 126.039055 0.000000
      vertex 161.772430 126.378792 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 167.983627 126.039055 0.000000
      vertex 161.847504 126.441544 0.000000
      vertex 161.916748 126.512222 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 161.979523 126.590630 0.000000
      vertex 167.983627 126.039055 0.000000
      vertex 161.916748 126.512222 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 162.035110 126.676598 0.000000
      vertex 167.983627 126.039055 0.000000
      vertex 161.979523 126.590630 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 163.950409 129.993988 0.000000
      vertex 164.009842 130.085327 0.000000
      vertex 165.391861 130.310638 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 166.050415 129.848877 0.000000
      vertex 163.950409 129.993988 0.000000
      vertex 165.391861 130.310638 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 166.731552 129.381241 0.000000
      vertex 163.950409 129.993988 0.000000
      vertex 166.050415 129.848877 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 165.391861 130.310638 0.000000
      vertex 164.009842 130.085327 0.000000
      vertex 164.077179 130.167969 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 164.151611 130.241760 0.000000
      vertex 165.391861 130.310638 0.000000
      vertex 164.077179 130.167969 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 164.232300 130.306503 0.000000
      vertex 165.391861 130.310638 0.000000
      vertex 164.151611 130.241760 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 165.391861 130.310638 0.000000
      vertex 164.232300 130.306503 0.000000
      vertex 164.318451 130.362000 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 164.409225 130.408081 0.000000
      vertex 165.391861 130.310638 0.000000
      vertex 164.318451 130.362000 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 164.503815 130.444565 0.000000
      vertex 165.391861 130.310638 0.000000
      vertex 164.409225 130.408081 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 165.299744 130.368820 0.000000
      vertex 165.391861 130.310638 0.000000
      vertex 164.503815 130.444565 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 164.601410 130.471268 0.000000
      vertex 165.299744 130.368820 0.000000
      vertex 164.503815 130.444565 0.000000
    endloop
  endfacet
  facet normal 0.000000 -0.000000 -1.000000
    outer loop
      vertex 164.701187 130.488007 0.000000
      vertex 165.299744 130.368820 0.000000
      vertex 164.601410 130.471268 0.000000
    endloop
  endfacet
  facet normal 0.000000 0.000000 -1.000000
    outer loop
      vertex 165.299744 130.368820 0.000000
      vertex 164.701187 130.488007 0.000000
      vertex 164.802322 130.494583 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 164.903992 130.490829 0.000000
      vertex 165.299744 130.368820 0.000000
      vertex 164.802322 130.494583 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 165.204086 130.415741 0.000000
      vertex 165.299744 130.368820 0.000000
      vertex 164.903992 130.490829 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 165.105698 130.451599 0.000000
      vertex 165.204086 130.415741 0.000000
      vertex 164.903992 130.490829 0.000000
    endloop
  endfacet
  facet normal -0.000000 -0.000000 -1.000000
    outer loop
      vertex 165.005386 130.476562 0.000000
      vertex 165.105698 130.451599 0.000000
      vertex 164.903992 130.490829 0.000000
    endloop
  endfacet
  facet normal -0.000000 0.000000 -1.000000
    outer loop
      vertex 151.702209 191.662628 0.000000
      vertex 33.052002 191.662552 0.000000
      vertex 59.755661 200.686371 0.000000
    endloop
  endfacet
endsolid Mesh
```

Print the [bottom plate](keebio-iris-pe-bottom-plate-3mm.stl) **twice**. Print the bottom plate once in the original orientation (left side) and then print it a second time by using the mirror function of your slicing software to print it again (right side).

Material: PLA
Layer Height: 0.2mm
Infill: 20%
Supports: None

Notes: 20% infill was used to save material and time but 100% could be adviseable since this is the frame of the keyboard and strength is important.

## Middle Layer

Print the [middle layer](keebio-iris-pe-middle-layer-3mm.stl) **twice**. Print the middle layer once in the original orientation (left side) and then print it a second time by using the mirror function of your slicing software to print it again (right side).

Material: PLA
Layer Height: 0.2mm
Infill: 20%
Supports: 15% in zig zag pattern

Notes: Supports are required due to 90 degree overhangs. at 15% the cleanup wasn't hard at all but lower % of supports would be just fine too. As for the infill, again, 20% was used to save material and time but different patterns and % can achieve different effects if using transparent PLA.

## Tenting Kit

You can add all [4 legs](keebio-iris-pe-ergodox-tenting-leg.stl) and [4 adapters](keebio-iris-pe-ergodox-tenting-legs-adapter.stl) to be printed simultaneously. There is the possibilty

Material: PLA
Layer Height: 0.2mm
Infill: 100%
Supports: None

Notes: 100% infill was used to make sure that the legs and adapters were strong as they will be holding the keyboard up and taking impacts from typing.

## Top plate

If you do decide to print the [top plate](keebio-iris-pe-top-plate-3mm.stil), make sure to **use 100% infill** because otherwise the plate will lack rigidity and lead to an unpleasant typing experience.

Material: PLA
Layer Height: 0.2mm
Infill: 100%
Supports: None

Notes: 100% infill was used to make sure that the top plate will be as strong as possible.

# Assembly Instructions

# Configuration

# Acknowledgements

- [Original 3D files for the keyboard case](https://github.com/keebio/iris-case) - Courtesy of [Keebio](https://keeb.io)
- [Original 3D files for the tenting kit](https://www.thingiverse.com/thing:5259983) - Courtesy of [Dave Lehman](https://www.thingiverse.com/davelehman)
