Embodied Carbon Sum and Graphs

This sheet calculates the embodied carbon per wafer (gCO2eq/wafer) of the Si eDRAM and M3D eDRAM. Embodied carbon is the sum of electrical, gaseous, and material contributions.

Electrical contributions: The total electrical energy for the Si eDRAM is listed in Cell B2; the total electrical energy for the M3D eDRAM is listed in Cell H2. In the next column, this number is scaled up by 40% to incorporate the energy of the fabrication facility (EPA → EPAf). EPAf is then multiplied by the carbon intensity of fabrication (CIfab) for a typical U.S. grid, an all-coal grid, and an all solar grid (CIfab values listed in cells N2-4). This product converts electrical energy into an equivalent mass of CO2 per wafer. 

Material contributions: The contribution to embodied carbon from material sourcing is approximated as the equivalent mass of CO2 per wafer of a 300 mm Si wafer.

Gas contributions: [6] reports the GHG emissions for full fabrication processes for 14 nodes using different fabrication techniques. We model the gas contribution of fabrication by calculating the ratio between the gaseous contribution of the iN7-EUV patterned node and its energy of fabrication. We multiply this ratio by the energy of fabrication of the Si and M3D eDRAM designs to approximate the gaseous contribution to embodied carbon.

Total embodied carbon of the Si eDRAM and M3D eDRAM are graphed for a U.S., coal, and solar grid.

| CI_fab [gCO2eq/kWh] | Value |
|---------------------|-------|
| US                  | 380   |
| Coal                | 820   |
| Solar               | 48    |

|                | [kgCO2e/wafer]      | GPA (99% abatement) | MPA         | EPA_f∙CI_fab   |
|----------------|---------------------|---------------------|-------------|----------------|
| U.S. grid      | Si eDRAM            | 115.2529351         | 353.4291735 | 385.13608      |
|                | M3D eDRAM           | 160.1119064         | 353.4291735 | 535.0394933    |
| Coal           | Si eDRAM            | 115.2529351         | 353.4291735 | 831.08312      |
|                | M3D eDRAM           | 160.1119064         | 353.4291735 | 1154.558907    |
| Solar          | Si eDRAM            | 115.2529351         | 353.4291735 | 48.648768      |
|                | M3D eDRAM           | 160.1119064         | 353.4291735 | 67.583936      |

| Description                                       | Value                     |
|---------------------------------------------------|---------------------------|
| Si eDRAM: EPA [kWh/wafer]                         | 723.94                    |
| Si eDRAM: EPA_f (EPA with 40% facility overhead) [kWh/wafer] | 1013.516       |
| EPA_f * CI_fab (US) [gCO2eq/wafer]                | 385136.08                 |
| EPA_f * CI_fab (coal) [gCO2eq/wafer]              | 831083.12                 |
| EPA_f * CI_fab (solar) [gCO2eq/wafer]             | 48648.768                 |
| Source:                                           |                           |

| Description                                       | Value                     |
|---------------------------------------------------|---------------------------|
| M3D eDRAM: EPA [kWh/wafer]                        | 1005.713333               |
| M3D eDRAM: EPA with 40% facility overhead (EPA_f) [kWh/wafer] | 1407.998667   |
| EPA_f * CI_fab (US) [gCO2eq/wafer]                | 535039.4933               |
| EPA_f * CI_fab (coal) [gCO2eq/wafer]              | 1154558.907               |
| EPA_f * CI_fab (solar) [gCO2eq/wafer]             | 67583.936                 |
| Source:                                           |                           |
