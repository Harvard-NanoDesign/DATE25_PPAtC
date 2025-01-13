Process Energy Calculations

This sheet calculates the energy/step values (in kWh/step/wafer) used to approximate the energy of a single dry etch, EUV lithography exposure, metallization, wet etch, or deposition step. [6] reports the process complexity of 9 BEOL metal line fabrication/patterning processes by lithographic method used (Figure 3), reporting the number of dry etch, lithography, metallization, metrology, wet etch, and deposition steps needed. [6] also reports the electrical energy per wafer for the same 9 metal line fabrication/patterning processes, broken down by amount of energy from each process (Figure 8). Dividing the total energy used by a process step by the number of times that process step is used obtains energy/step in kWh/step/wafer.

Because the IGZO and CNT transistors in the M3D design in our paper are modeled at a 7nm node, with our overall design following the specifications of the ASAP7 PDK, we base our analysis around the process energies reported to fabricate a metal line with single-patterning EUV (“Metal line LE (EUV)” in Figures 3 and 8). [8] Because there is no data on deposition for this process, we use the EUV LE2 data (“Metal SA-LE2 grating (EUVL)”) process energies for energy/step of deposition.

| Metal line EUV      | Total energy (kWh/wafer)/line | Total number of steps | Energy/step (kWh/step) |
|---------------------|-------------------------------|-----------------------|------------------------|
| Dry etch            | 2                             | 1                     | 2                      |
| Lithography (EUV)   | 10                            | 3                     | 3.333333333            |
| Metallization       | 2                             | 1                     | 2                      |
| Wet etch            | 1                             | 3                     | 0.333333333            |
| Deposition          | 0                             | 3                     | 0                      |

| Metal SA-LE2 grating (EUVL) | Total energy (kWh/wafer)/line | Total number of steps | Energy/step (kWh/step) |
|-----------------------------|-------------------------------|-----------------------|------------------------|
| Dry etch                    | 5                             | 5                     | 1                      |
| Lithography (EUV)           | 19                            | 6                     | 3.166666667            |
| Metallization               | 2                             | 1                     | 2                      |
| Wet etch                    | 1                             | 7                     | 0.142857143            |
| Deposition                  | 4                             | 3                     | 1.333333333            |
