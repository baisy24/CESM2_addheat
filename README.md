## This project is used to add diabatic heating to CESM2/CAM6

To use, simply put all F90 files into your $CASEDIR/SourceMods/src.cam/ directory

## Descriptions of the F90 scripts

1) the modified lines in the F90 files are denoted within the following notation for the convenience to read:

********************* ADD HEAT EDITS *********************

modified code to add diabatic heating

*********************** END EDITS ************************

2) **cam_diagnostics.F90** is used to output the added temperature tendency variable "XXH"

3) change amount, location and time of the added heating in **physpkg.F90** 

## How to cite

If you would like to use this script, please cite the following publications:

Bai, H. and Schumacher, C., **2021**. The Interaction between the Nocturnal Amazonian Low-Level Jet and Convection in CESM. Journal of Climate, 34(21), 8519-8532.

Lappen, C.L. and Schumacher, C., **2012**. Heating in the tropical atmosphere: what level of detail is critical for accurate MJO simulations in GCMs?. Climate Dynamics, 39(9), 2547-2568.
