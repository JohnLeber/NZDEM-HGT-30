# NZDEM-HGT-30

New Zealand Digital elevation Model in 1 arc-second (~30 meter) HGT format. I created this dataset back around 2010. It was intended as a resource for the PC gaming community (train, plane, ship simulators...), graphics artists, or anyone who can apply the data safely.

At that time NASA had not released 1 arc-second (30 meter) SRTM data for New Zealand or for any country other than the United States. By using existing elevation data from Land Information New Zealand (LINZ) I was able to artificially create the HGT files at this higher resolution. The data was derived from the same base grid which was computed at a resolution of 10 meters by interpolating the contour lines from the LINZ topographical database. I wrote [custom software](https://github.com/nodecomplete/NZDEM-HGT-30/blob/master/Screenshots/ConversionApp.jpg?raw=true) to perform the calculations which took two 6 core machines about 1 week to complete. Information on the HGT (STRM1) format can be found [here](https://dds.cr.usgs.gov/srtm/version2_1/Documentation/SRTM_Topo.pdf).

You can use the data for commerical and non-commerical purposes according to the [Creative Commons Attribution 4.0 International license](https://creativecommons.org/licenses/by/4.0/legalcode). You must attribute the creator in your own works which in this case would be [Land Information New Zealand](https://www.linz.govt.nz/).

 

 
