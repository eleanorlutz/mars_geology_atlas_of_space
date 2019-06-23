  DESCRIPTION OF THE DIGITAL DATABASE FOR 
  Geologic Map of Mars, Scale 1:20,000,000
  USGS SCIENTIFIC INVESTIGATIONS MAP 3292

  Reference: K.L. Tanaka, J.A. Skinner, Jr., J.M. Dohm, R.P. Irwin, III, E.J. Kolb, C.M. Fortezzo, 
  Thomas Platz, G.G. Michael, and T.M. Hare, 2014, Geologic Map of Mars, Scale 1:20,000,000, 
  U.S. Geological Survey Scientific Investigations Map SIM 3292. URL: http://pubs.usgs.gov/sim/3292
 
  INTRODUCTION

This new global geologic map of Mars, which records the distribution of geologic units and 
landforms on the planet’s surface through time, is based on unprecedented variety, quality, 
and quantity of remotely sensed data acquired since the Viking Orbiters. These data have 
provided morphologic, topographic, spectral, thermophysical, radar sounding, and other 
observations for integration, analysis, and interpretation in support of geologic mapping. 
In particular, the precise topographic mapping now available has enabled consistent 
morphologic portrayal of the surface for global mapping (whereas previously used visual-range 
image bases were less effective, because they combined morphologic and albedo information 
and, locally, atmospheric haze). Also, thermal infrared image bases used for the new map tended 
to be less affected by atmospheric haze and thus are reliable for analysis of surface morphology 
and texture at even higher resolution than the topographic products.
   
  All GIS data are in Robinson projection using the
  Mars 2000 geographic coordinate system
  (GCS_Mars_2000_Sphere, 3396190.0 radius). Units are in meters.
  Center Longitude = 0.0

  GEOLOGIC CONTENT (contents of "ESRI_FileGeodatabase" Folder,
  SIM3292_geodatabase.gdb)

  This ArcGIS geodatabase contains one feature dataset
  (SIM3292_MGM_Robinson_Mars2000_Sphere) with the following features:

  SIM3292_Global_Contacts - Line feature class, contains a “ConType” field for the 
  geologic unit and map boundaries including symbol types: Certain, Approximate, 
  Border, and Internal.</enttypd>

  SIM3292_Global_Geology - Polygon feature class, geologic unit polygon feature class.  
  Contains a “Unit” field denoting the unit name and “UnitDesc” the short unit 
  decription. “SphArea_km” is the geodesic area of the polygon in km^2.

  SIM3292_Global_Structure - Structural layer. Contains a “Morphology” field denoting 
  the structure type including “Origin”, “Interpretation”, and “Preservation”.

  BASE MAP CONTENT
To produce an up-to-date global geologic map for Mars using modern bases including the Mars 
Global Surveyor (MGS) Mars Orbiter Laser Altimeter (MOLA) digital elevation model 
(DEM) (463 m/pixel resolution at lower latitudes to 115 m/pixel near the poles) 
(Smith and others, 2001) and the Mars Odyssey (ODY) Thermal Emission Imaging System 
(THEMIS) daytime infrared (IR) image mosaic (100 m/pixel) (Christensen and others, 2004).
See Pamphlet for more information and references. 

  DIGITAL DATABASE AND METADATA PACKAGE (SIM3292_database.zip)

  The geologic map files, basemaps, and supportive files are included
  in the database package, as described below:

  "SIM3292_MarsGlobalGeologicGIS_20M" directory
  --------------------------------------------
   Files                     Description
  ---------------------------------------------------------------------
  ---------------------------------------------------------------------

  SIM3292_README.txt         This readme file.

  SIM3292_metadata.txt       Text-format FGDC-style metadata for the
                             database package

  SIM3292_metadata.xml       XML-format FGDC-style metadata for the
                             database package

  SIM3292_MarsGlobalGeologicGIS_20M_ArcMap10.1.mxd ArcGIS (version 10.1) project


  "Basemaps" basemap directory
  --------------------------------------------
  MOLA_Hillshade_Robinson_128ppd.tif - MOLA shaded relief basemap Goddard and USGS.
  
  hillshade_n_128.jpg - North Pole MOLA shaded relief basemap Goddard

  hillshade_s_128.jpg - South Pole MOLA shaded relief basemap Goddard

  Vector directories
  --------------------------------------------
  "SIM3292_geodatabase.gdb" - ArcMap 10.0 versioned geodatabase

  "Shapefiles" -
  This directory contains GIS shapefiles exported from the ArcGIS
  geodatabase described above using decimal degrees. As such, the names
  and descriptions for each shapefile are identical to the content of
  the included geodatabase. See above "GEOLOGIC CONTENT" for details.

  Users of the database package may wish to download the PDF version
  of the map for the Description of Map Units.

  The material described above is available on the World Wide Web at
  http:/pubs.usgs.gov/sim/3292

  "Mars_PublishedGeologicMaps_1Mscale_greater" directory
  --------------------------------------------
  Contains a locator map and GIS shapefiles and ArcMap project for existing
  Mars geologic maps above 1:1,000,000 scale.

  ZIP FILES

  The files described above are packaged within a ZIP file.  Utilities
  to uncompress ZIP files are available for most operating systems and
  may be found readily with a simple web search.

  DIGITAL DATABASE FORMAT

  The digital information compiled in this report used v 10, a
  commercial Geographic Information System produced by Environmental
  Systems Research Institute, Redlands, California.

  OBTAINING HARD-COPY OF SIM 3292

  USGS Information Services
  Box 25286
  Denver Federal Center
  Denver, CO  80225-0046

  (303) 202-4200
  1-888-ASK-USGS
  Email: infoservices@usgs.gov
