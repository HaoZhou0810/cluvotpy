This is a simple case of the clean extraction of GRB 130427A spectrum.

"sw00554620000ugu_1ord_1_f.pha" is the spectrum extracted with uvotpy.

Run
> python.exe cluvotpy.py
in your terminal

if your terminal prints
```
PHA file: 130427A/sw00554620000ugu_1ord_1_f.pha
MET start: 388741990.92986
MET stop: 388742040.7104
Wheel position: 200
1st anchor [dt pix]: (1205.48, 1136.19)
Distance of 1st anchor from the ref position: 224.18
Track width: 2.5
1st order effective area file: swugu0200_20041120v105.arf+SPECRESPUGRISM0200_AX1005AY1080_O1      
2nd order effective area file: swugu0200_ax1080ay1000_dx100dy100_o2_20041120v001_cl.arf+SPECRESP0200GRISM2NDORDER
```
and a plot pops out, the code runs successfully. The cleaned spectrum "sw00554620000ugu_1ord_1_f_cl.pha" can be found in the same folder of the input file "sw00554620000ugu_1ord_1_f.pha".