Embodied Carbon Sum and Graphs

This sheet calculates the embodied carbon per wafer (gCO2eq/wafer) of the Si eDRAM and M3D eDRAM. Embodied carbon is the sum of electrical, gaseous, and material contributions.

Electrical contributions: The total electrical energy for the Si eDRAM is listed in Cell B2; the total electrical energy for the M3D eDRAM is listed in Cell H2. In the next column, this number is scaled up by 40% to incorporate the energy of the fabrication facility (EPA → EPAf). EPAf is then multiplied by the carbon intensity of fabrication (CIfab) for a typical U.S. grid, an all-coal grid, and an all solar grid (CIfab values listed in cells N2-4). This product converts electrical energy into an equivalent mass of CO2 per wafer. 

Material contributions: The contribution to embodied carbon from material sourcing is approximated as the equivalent mass of CO2 per wafer of a 300 mm Si wafer.

Gas contributions: [6] reports the GHG emissions for full fabrication processes for 14 nodes using different fabrication techniques. We model the gas contribution of fabrication by calculating the ratio between the gaseous contribution of the iN7-EUV patterned node and its energy of fabrication. We multiply this ratio by the energy of fabrication of the Si and M3D eDRAM designs to approximate the gaseous contribution to embodied carbon.

Total embodied carbon of the Si eDRAM and M3D eDRAM are graphed for a U.S., coal, and solar grid.
