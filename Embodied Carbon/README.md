Embodied Carbon Sum and Graphs

Here, we show calculations of the embodied carbon per wafer (gCO2eq/wafer) of the Si eDRAM and M3D eDRAM. Embodied carbon is the sum of electrical, gaseous, and material contributions.

Electrical contributions include the total electrical energy for the Si eDRAM; the total electrical energy for the M3D eDRAM. In the next column, this number is scaled up by 40% to incorporate the energy of the fabrication facility (EPA → EPAf). EPAf is then multiplied by the carbon intensity of fabrication (CIfab) for a typical U.S. grid, an all-coal grid, and an all solar grid (CIfab values listed in cells N2-4). This product converts electrical energy into an equivalent mass of CO2 per wafer. 

Material contributions: The contribution to embodied carbon from material sourcing is approximated as the equivalent mass of CO2 per wafer of a 300 mm Si wafer.

Gas contributions: https://ieeexplore.ieee.org/abstract/document/9372004/ reports the GHG emissions for full fabrication processes for 14 nodes using different fabrication techniques. We model the gas contribution of fabrication by calculating the ratio between the gaseous contribution of the iN7-EUV patterned node and its energy of fabrication. We multiply this ratio by the energy of fabrication of the Si and M3D eDRAM designs to approximate the gaseous contribution to embodied carbon.

Total embodied carbon of the Si eDRAM and M3D eDRAM are graphed for a U.S., coal, and solar grid.

| CI_fab [gCO2eq/kWh] | Value |
|---------------------|-------|
| US                  | 380   |
| Coal                | 820   |
| Solar               | 48    |

| Grid         | Type       | GPA (99% abatement) [kgCO2e/wafer] | MPA [kgCO2e/wafer] | EPA_f∙CI_fab [kgCO2e/wafer] |
|--------------|------------|------------------------------------|-------------------|-----------------------------|
| U.S. grid    | Si eDRAM   | 111.4734718                        | 353.4291735       | 372.5064                    |
|              | M3D eDRAM  | 171.969296                         | 353.4291735       | 574.6628533                 |
| Coal         | Si eDRAM   | 111.4734718                        | 353.4291735       | 803.8296                    |
|              | M3D eDRAM  | 171.969296                         | 353.4291735       | 1240.061947                 |
| Solar        | Si eDRAM   | 111.4734718                        | 353.4291735       | 47.05344                    |
|              | M3D eDRAM  | 171.969296                         | 353.4291735       | 72.588992                   |
| Taiwan grid  | Si eDRAM   | 111.4734718                        | 353.4291735       | 551.89764                   |
|              | M3D eDRAM  | 171.969296                         | 353.4291735       | 851.4083853                 |

| Si eDRAM                       | Value                   |
|-------------------------------|-------------------------|
| EPA [kWh/wafer]               | 700.2                   |
| EPA_f (EPA with 40% facility overhead) [kWh/wafer] | 980.28                  |
| EPA_f * CI_fab (US) [gCO2eq/wafer]     | 372506.4                |
| EPA_f * CI_fab (coal) [gCO2eq/wafer]   | 803829.6                |
| EPA_f * CI_fab (solar) [gCO2eq/wafer]  | 47053.44               |
| EPA_f * CI_fab (Taiwan) [gCO2eq/wafer] | 551897.64              |

| M3D eDRAM                              | Value                   |
|----------------------------------------|-------------------------|
| EPA [kWh/wafer]                        | 1080.193333             |
| EPA with 40% facility overhead (EPA_f) [kWh/wafer] | 1512.270667             |
| EPA_f * CI_fab (US) [gCO2eq/wafer]     | 574662.8533             |
| EPA_f * CI_fab (coal) [gCO2eq/wafer]   | 1240061.947             |
| EPA_f * CI_fab (solar) [gCO2eq/wafer]  | 72588.992               |
| EPA_f * CI_fab (Taiwan) [gCO2eq/wafer] | 851408.3853             |
