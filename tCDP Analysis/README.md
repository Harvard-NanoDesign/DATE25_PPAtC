tCDP Analysis

Logic synthesis and place-and-route using Cadence Genus & Innovus is used to determine area per die for the Si and M3D eDRAM designs. Given these dimensions, the total number of die per wafer for a 300 mm wafer is calculated for each design. Assuming 90% yield, gCO2eq/die is calculated. 

Performance metrics for each design is determined using RTL simulations in Synopsys VCS on compiled Embench applications. The carbon footprint of use (gCO2eq/application) is determined by multiplying energy per application by the carbon intensity of use. For a case study of 2 hours of use per day on a U.S. grid, gCO2eq/month for each design is calculated. 

Total carbon per die (tC) is the sum of the embodied and operational carbon contributions. Total carbon over a lifetime of 18 months is plotted, with operational and embodied contributions shown in overlay.

tCDP, total carbon delay product, is calculated by multiplying tC by delay. tCDP over a lifetime of 18 months is calculated for each design, along with tCDP/month. 

gCO2eq/month is calculated for a U.S., all-coal, and all-solar grid. The impact of variation in CIuse on gCO2eq/month is calculated for a 3x increase/decrease in the U.S. grid. 
