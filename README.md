# OPDA
Ocean Physical Data analyzer (OPDA)
https://pace.oceansciences.org

The scripts are used for Ocean Geophysical remote sensing research. 
どぞ.

Required Packages: 
(1) netCDF4,numpy,scipy,sklearn.metrics.pairwise,math,matplotlib.pyplot,urllib.request,os,pandas,bs4
(2) cartopy.crs, cartopy.feature ---> Geophysics Packages

Data Usage & Download Sites:

(1)NASA PACE Satelliate measurements (.nc): 
Link--->  https://search.earthdata.nasa.gov/search?portal=obdaac

(2)NASA AERONET station measurements (.html): 
Link---> https://aeronet.gsfc.nasa.gov/new_web/webtool_aod_v3.html

(3)NASA PACE Data Matchups for Apparent Optical Properties (.csv):  
Link---> https://pace.oceansciences.org/pace_data_matchups.htm


## Folders:

(A)SatelliateSingleDayExample ---> .ipynb script is to read Single day NASA PACE Satelliate SWAP data (.nc file) and AERONET site measurement (exported as .html file).

  Examples:
  (1) Example Folder: [SatelliateSingleDayExample]
  Geo-coordinate is set as:  lat=41; lon=1.36
  Casablanca AERONET Station Coordinate (Revise the coordinate to fit your  purpose) Measurement Date:  2024 9/15

  Step No.1:
  Go to the NASA PACE Satelliate measurements (.nc): Link--->  https://search.earthdata.nasa.gov/search?portal=obdaac to      download satelliate measurement data file: "PACE_OCI.20240915T122947.L2.OC_AOP.V2_0.NRT.nc" in order to recover the     result   plots presented in the folder.

  Step No.2:
  In the current foler, the .ipynb notebook file will convert geophysical data parameters to arrays, follow the   instructions in the file, following functions could be achieved:
  (a) Plotting satelliate measurement (3 resoulation options) rg. Rrs values, Ocean Color geophysical parameter etc.
  (b) AERONET station data measurements at available bands
  (c) Correction of Rrs Values at all available wavelengthes 


