tCDP Analysis

Logic synthesis and place-and-route using Cadence Genus & Innovus is used to determine area per die for the Si and M3D eDRAM designs. Given these dimensions, the total number of die per wafer for a 300 mm wafer is calculated for each design. Assuming 90% yield, gCO2eq/die is calculated. 

Performance metrics for each design is determined using RTL simulations in Synopsys VCS on compiled Embench applications. The carbon footprint of use (gCO2eq/application) is determined by multiplying energy per application by the carbon intensity of use. For a case study of 2 hours of use per day on a U.S. grid, gCO2eq/month for each design is calculated. 

Total carbon per die (tC) is the sum of the embodied and operational carbon contributions. Total carbon over a lifetime of 18 months is plotted, with operational and embodied contributions shown in overlay.

tCDP, total carbon delay product, is calculated by multiplying tC by delay. tCDP over a lifetime of 18 months is calculated for each design, along with tCDP/month. 

gCO2eq/month is calculated for a U.S., all-coal, and all-solar grid. The impact of variation in CIuse on gCO2eq/month is calculated for a 3x increase/decrease in the U.S. grid. 

| Embodied                              | Si               | M3D             |
|---------------------------------------|------------------|-----------------|
| Area per die                          | 0.068            | 0.025           |
| Die per 300 mm wafer                  | 299127           | 606238          |
| 90% yield - die per 300 mm wafer      | 269214           | 545614          |
| Total gCO2e per 300 mm wafer          | 853818.1886      | 1048580.573     |
| gCO2e/die (90% yield)                 | 3.171518707      | 1.921835196     |

| Operational                           | Si               | M3D             |
|---------------------------------------|------------------|-----------------|
| Energy per cycle (J)                  | 2.00E-11         | 1.75E-11        |
| Cycles per application                | 2.00E+07         | 2.00E+07        |
| Energy per application (J)            | 4.02E-04         | 3.51E-04        |
| kWh per Joule                         | 3.60E+06         | 3.60E+06        |
| Energy per application (kWh)          | 1.12E-10         | 9.76E-11        |
| CI_use (gCO2e/kWh, US grid)           | 380              | 380             |
| gCO2e/application                     | 4.24E-08         | 3.71E-08        |
| clock period (s)                      | 0.000000002      | 0.000000002     |
| Application run time (s)              | 4.00E-02         | 4.00E-02        |
| Application runs per hour             | 9.00E+04         | 9.00E+04        |
| Hours per day                         | 2                | 2               |
| Application runs per day              | 1.80E+05         | 1.80E+05        |
| gCO2e/day                             | 7.63E-03         | 6.68E-03        |
| gCO2e/year                            | 2.78E+00         | 2.44E+00        |
| gCO2e/month                           | 2.32E-01         | 2.03E-01        |
|                                       |                  |                 |
| Delay (s)                             | 4.01E-02         | 4.01E-02        |

| Month | Carbon total [gCO2e/die] | tCDP [gCO2e*s/die] | tCDP/month [gCO2e*s/die/month] |
|-------|--------------------------|--------------------|--------------------------------|
| 1     | 3.40E+00                 | 1.36E-01           | 1.36E-01                       |
| 2     | 3.64E+00                 | 1.46E-01           | 7.29E-02                       |
| 3     | 3.87E+00                 | 1.55E-01           | 5.17E-02                       |
| 4     | 4.10E+00                 | 1.64E-01           | 4.11E-02                       |
| 5     | 4.33E+00                 | 1.74E-01           | 3.47E-02                       |
| 6     | 4.56E+00                 | 1.83E-01           | 3.05E-02                       |
| 7     | 4.80E+00                 | 1.92E-01           | 2.75E-02                       |
| 8     | 5.03E+00                 | 2.02E-01           | 2.52E-02                       |
| 9     | 5.26E+00                 | 2.11E-01           | 2.34E-02                       |
| 10    | 5.49E+00                 | 2.20E-01           | 2.20E-02                       |
| 11    | 5.72E+00                 | 2.30E-01           | 2.09E-02                       |
| 12    | 5.96E+00                 | 2.39E-01           | 1.99E-02                       |
| 13    | 6.19E+00                 | 2.48E-01           | 1.91E-02                       |
| 14    | 6.42E+00                 | 2.57E-01           | 1.84E-02                       |
| 15    | 6.65E+00                 | 2.67E-01           | 1.78E-02                       |
| 16    | 6.88E+00                 | 2.76E-01           | 1.73E-02                       |
| 17    | 7.12E+00                 | 2.85E-01           | 1.68E-02                       |
| 18    | 7.35E+00                 | 2.95E-01           | 1.64E-02                       |

| Month | Carbon total [gCO2e/die] | tCDP [gCO2e*s/die] | tCDP/month [gCO2e*s/die/month] |
|-------|--------------------------|--------------------|--------------------------------|
| 1     | 2.12E+00                 | 8.52E-02           | 8.52E-02                       |
| 2     | 2.33E+00                 | 9.33E-02           | 4.67E-02                       |
| 3     | 2.53E+00                 | 1.01E-01           | 3.38E-02                       |
| 4     | 2.73E+00                 | 1.10E-01           | 2.74E-02                       |
| 5     | 2.94E+00                 | 1.18E-01           | 2.36E-02                       |
| 6     | 3.14E+00                 | 1.26E-01           | 2.10E-02                       |
| 7     | 3.34E+00                 | 1.34E-01           | 1.91E-02                       |
| 8     | 3.55E+00                 | 1.42E-01           | 1.78E-02                       |
| 9     | 3.75E+00                 | 1.50E-01           | 1.67E-02                       |
| 10    | 3.95E+00                 | 1.58E-01           | 1.58E-02                       |
| 11    | 4.15E+00                 | 1.67E-01           | 1.51E-02                       |
| 12    | 4.36E+00                 | 1.75E-01           | 1.46E-02                       |
| 13    | 4.56E+00                 | 1.83E-01           | 1.41E-02                       |
| 14    | 4.76E+00                 | 1.91E-01           | 1.36E-02                       |
| 15    | 4.97E+00                 | 1.99E-01           | 1.33E-02                       |
| 16    | 5.17E+00                 | 2.07E-01           | 1.30E-02                       |
| 17    | 5.37E+00                 | 2.15E-01           | 1.27E-02                       |
| 18    | 5.58E+00                 | 2.24E-01           | 1.24E-02                       |

| Month | All-Si - Cembodied | All-Si - Coperational/month | All-Si - tC | M3D - Cembodied | M3D - Coperational/month | M3D - tC |
|-------|---------------------|----------------------------|-------------|-----------------|--------------------------|----------|
| 1     | 3.171518707         | 2.32E-01                   | 3.40E+00    | 1.921835196     | 2.03E-01                 | 2.12E+00 |
| 2     | 3.171518707         | 4.64E-01                   | 3.64E+00    | 1.921835196     | 4.06E-01                 | 2.33E+00 |
| 3     | 3.171518707         | 6.96E-01                   | 3.87E+00    | 1.921835196     | 6.09E-01                 | 2.53E+00 |
| 4     | 3.171518707         | 9.28E-01                   | 4.10E+00    | 1.921835196     | 8.12E-01                 | 2.73E+00 |
| 5     | 3.171518707         | 1.16E+00                   | 4.33E+00    | 1.921835196     | 1.02E+00                 | 2.94E+00 |
| 6     | 3.171518707         | 1.39E+00                   | 4.56E+00    | 1.921835196     | 1.22E+00                 | 3.14E+00 |
| 7     | 3.171518707         | 1.62E+00                   | 4.80E+00    | 1.921835196     | 1.42E+00                 | 3.34E+00 |
| 8     | 3.171518707         | 1.86E+00                   | 5.03E+00    | 1.921835196     | 1.62E+00                 | 3.55E+00 |
| 9     | 3.171518707         | 2.09E+00                   | 5.26E+00    | 1.921835196     | 1.83E+00                 | 3.75E+00 |
| 10    | 3.171518707         | 2.32E+00                   | 5.49E+00    | 1.921835196     | 2.03E+00                 | 3.95E+00 |
| 11    | 3.171518707         | 2.55E+00                   | 5.72E+00    | 1.921835196     | 2.23E+00                 | 4.15E+00 |
| 12    | 3.171518707         | 2.78E+00                   | 5.96E+00    | 1.921835196     | 2.44E+00                 | 4.36E+00 |
| 13    | 3.171518707         | 3.02E+00                   | 6.19E+00    | 1.921835196     | 2.64E+00                 | 4.56E+00 |
| 14    | 3.171518707         | 3.25E+00                   | 6.42E+00    | 1.921835196     | 2.84E+00                 | 4.76E+00 |
| 15    | 3.171518707         | 3.48E+00                   | 6.65E+00    | 1.921835196     | 3.05E+00                 | 4.97E+00 |
| 16    | 3.171518707         | 3.71E+00                   | 6.88E+00    | 1.921835196     | 3.25E+00                 | 5.17E+00 |
| 17    | 3.171518707         | 3.94E+00                   | 7.12E+00    | 1.921835196     | 3.45E+00                 | 5.37E+00 |
| 18    | 3.171518707         | 4.18E+00                   | 7.35E+00    | 1.921835196     | 3.65E+00                 | 5.58E+00 |

|       | Si                 |                      | M3D                 |                      |
|-------|--------------------|----------------------|---------------------|----------------------|
|       | 3x U.S. grid       | 1/3x U.S. grid       | 3x U.S. grid        | 1/3x U.S. grid       |
| CI_use | 1140              | 126.6666667          | CI_use              | 1140                 | 126.6666667          |
| gCO2e/app | 1.28E-07       | 1.42E-08             | gCO2e/app           | 1.11E-07             | 1.24E-08             |
| gCO2e/month | 6.89E-01     | 7.66E-02             | gCO2e/month         | 6.01E-01             | 6.68E-02             |
| gCO2e for 12 months | 8.27E+00 | 9.19E-01         | gCO2e for 12 months | 7.21E+00             | 8.01E-01             |

|                     | Si            | M3D           |
|---------------------|---------------|---------------|
| CI_use [gCO2eq/kWh] | gCO2e/application | gCO2e/application |
| US:                 | 4.26E-08      | 3.71E-08      |
| Coal:               | 9.18E-08      | 8.00E-08      |
| Solar:              | 5.38E-09      | 4.68E-09      |
|                     |               |               |
|                     | gCO2e/month   |               |
| US:                 | 0.2298240     | 0.2002752     |
| Coal:               | 0.4959360     | 0.4321728     |
| Solar:              | 0.0290304     | 0.0252979     |
