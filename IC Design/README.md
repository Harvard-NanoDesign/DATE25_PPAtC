### IC Physical Implementation ###

This folder contains the IC design log files from which our data was extracted from. The summarized results for Carbon Analysis are shown below:
| **System** | **M0 + Si eDRAM** | **M0 + IGZO/CNT/Si M3D-eDRAM** |
|------------|-------------------|------------------------------|
| **clock frequency** | 500 MHz | 500 MHz |
| **M0 dynamic energy per cycle** | 2.03 pJ | 2.03 pJ |
| **average memory energy per cycle** | 18.0 pJ | 15.5 pJ |
| **clock cycles to run "matmul-int"** | 20,047,348 | 20,047,348 |
| **64 kB memory area footprint** | 0.068 mm² | 0.025 mm² |
| **total area footprint (memory + M0)** | 0.139 mm²<br>H: 270 μm<br>W: 515 μm | 0.053 mm²<br>H: 159 μm<br>W: 334 μm |

We also provide a circuit layout (GDS) using the M3D process which can be rendered in 3D using GDS3D (https://github.com/trilomix/GDS3D).

![GDS3D Layout Cross Section Rendering](https://github.com/user-attachments/assets/ab8140ab-978f-41e9-a535-0ec23534ef94)

To create the above rendering
- Download GDS3D from https://github.com/trilomix/GDS3D
- Navigate to the 'Layouts' folder
- Run the following command: `vglrun64 GDS3D -p layers.txt -i cross_section.gds`
- `layers.txt` is provided with sample colors, this file can be edited as desired
