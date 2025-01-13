Total Processes + Fab Energies

Here, we calculate the total electrical energy of fabrication for the Si eDRAM and M3D eDRAM designs, broken down into contributions from the FEOL, MOL, and BEOL. For the FEOL and MOL, the electrical energy of fabrication is approximated as the FEOL and MOL energy of fabrication of the iN7 EUV-patterned node ([6], Figure 9). 

The BEOL of the Si eDRAM is modeled after that of the ASAP7 PDK, with V0 followed by 9 metal/via (M/V) layers. M/V 1-3 are at 36 nm pitch, 4-5 at 48 nm pitch, 6-7 at 64 nm pitch, and 8-9 at 80 nm pitch. [6] reports the energy of fabrication of metal/via layers according to their pitch and lithography methods used for 11 nodes (Figure 10). The energy of fabrication of a metal/via layer is taken by matching this data to ASAP7 specifications, using the data reported for the iN7 EUV-pattered imec node. The energy of fabrication of V0 is estimated by subtracting the total energy of metal/via pair fabrication at 36 nm pitch from energy of metal line fabrication reported in [6] Figure 8. The data provided for ‘Metal 42 nm pitch’ is used to model the 48 nm pitch M/V lines.

The BEOL of the M3D eDRAM is modeled as V0 and 4 metal layers out of the MOL, 2 CNFET and 1 IGZO FET layer with 2 metal layers at 36 nm pitch in between each transistor layer, and 9 metal/via layers. The electrical energy of fabrication of the transistor layers was calculated on the previous sheet. 

| Step                   | Energy/wafer (kWh/wafer) |
|------------------------|--------------------------|
| FEOL                   | 310                      |
| MOL                    | 126                      |
| BEOL: V0               | 23.74                    |
| BEOL: M/V 1 - 36 nm pitch | 37.74                  |
| BEOL: M/V 2 - 36 nm pitch | 37.74                  |
| BEOL: M/V 3 - 36 nm pitch | 37.74                  |
| BEOL: M/V 4 - 48 nm pitch | 32.85                  |
| BEOL: M/V 5 - 48 nm pitch | 32.85                  |
| BEOL: M/V 6 - 64 nm pitch | 23.07                  |
| BEOL: M/V 7 - 64 nm pitch | 23.07                  |
| BEOL: M/V 8 - 80 nm pitch | 19.57                  |
| BEOL: M/V 9 - 80 nm pitch | 19.57                  |
|                          |                          |
| TOTAL BEOL:            | 287.94                   |
| TOTAL DESIGN:          | 723.94                   |

| Step                      | Energy/wafer (kWh/wafer) |
|---------------------------|--------------------------|
| FEOL                      | 310                      |
| MOL                       | 126                      |
| BEOL: V0                  | 23.74                    |
| BEOL: M/V 1 - 36 nm pitch | 37.74                    |
| BEOL: M/V 2 - 36 nm pitch | 37.74                    |
| BEOL: M/V 3 - 36 nm pitch | 37.74                    |
| BEOL: M/V 4 - 48 nm pitch | 32.85                    |
| BEOL: CNFET 1             | 18                       |
| BEOL: M/V 5 - 36 nm pitch | 37.74                    |
| BEOL: M/V 6 - 36 nm pitch | 37.74                    |
| BEOL: CNFET 2             | 18                       |
| BEOL: M/V 7 - 36 nm pitch | 37.74                    |
| BEOL: M/V 8 - 36 nm pitch | 37.74                    |
| BEOL: IGZO FET            | 19.33333333              |
| BEOL: M/V 9 - 36 nm pitch | 37.74                    |
| BEOL: M/V 10 - 36 nm pitch| 37.74                    |
| BEOL: M/V 11 - 48 nm pitch| 32.85                    |
| BEOL: M/V 12 - 64 nm pitch| 23.07                    |
| BEOL: M/V 13 - 64 nm pitch| 23.07                    |
| BEOL: M/V 14 - 80 nm pitch| 19.57                    |
| BEOL: M/V 15 - 80 nm pitch| 19.57                    |
|                           |                          |
| TOTAL BEOL:               | 569.7133333              |
| TOTAL DESIGN:             | 1005.713333              |
