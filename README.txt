This project is used to add diabatic heating to CESM2/CAM6

To use, simply put all the F90 files into your $CASEDIR/SourceMods/src.cam/

Descriptions of the F90 scripts:
1) the modified lines in the F90 files are denoted within the following notation for the convenience to read:
!******************** ADD HEAT EDITS **********************
modified code to add diabatic heating
!*********************** END EDITS ************************

2) cam_diagnostics.F90 is used to output the added temperature tendency variable "XXH"

3) change amount, location and time of the added heating in physpkg.F90 
