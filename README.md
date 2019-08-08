# CDAL-SummerSchool

Materials for the sessions organised by the Computational and Digital Archaeology Laboratory (CDAL) of the Department of Archaeology, Cambridge University, in the Peterhouse Archaeology Summer School (5-9/8/2019) and the [Sutton Trust Summer School](https://summerschools.suttontrust.com/) (22/8/2019). Materials were created by [Enrico R. Crema](https://www.arch.cam.ac.uk/directory/erc62), [Arnau García](https://www.arch.cam.ac.uk/directory/ag2023), [Andreas Angourakis](https://www.arch.cam.ac.uk/directory/aa2112), and [D.I. Redhouse](https://www.arch.cam.ac.uk/directory/dir21). 

CDAL is a group based on the McDonald Institute for Archaeological Research at the University of Cambridge (https://www.mcdonald.cam.ac.uk/).

This exercise introduces some Geographic Information Systems (GIS) techniques used in archaeology. More specifically, it focus on visibility network and cumulative viewshed procedures available in the plugin named "Visibility Analysis" in the Quantum GIS or QGIS software.

The exercise is inspired by:
> Kay S and Sly T J T 2001 An application of cumulative viewshed analysis to a medieval archaeological study: The beacon system of the Isle of Wight, United Kingdom Archeol. e Calc. 12 167–79 Online: http://www.archcalc.cnr.it/indice/PDF12/09Kay.pdf  
(This article is included as "09Kay.pdf" under the [CC BY-NC-ND 3.0](https://creativecommons.org/licenses/by-nc-nd/3.0/) Licence.)

Download the content of this repository to your local computer and install QGIS, if not already installed (https://qgis.org/en/site/). Follow the instruction in the pdf document that better corresponds to the QGIS version installed in your computer (2.18 or 3.8). All necessary data for this exercise is inside the "data" folder.

The beacon positions and metadata were obtained as open data at [Historic England’s PastScape engine](http://www.pastscape.org.uk). No license is specified. The sample in raw format was created by D.I. Redhouse <dir21@cam.ac.uk> and is available as a csv file in the folder named “raw data”. The shapefile representing the United Kingdom and the Digital Elevation Model (DEM) were obtained at the [Ordnance Survey Open Data](http://www.ordnancesurvey.co.uk) under the  [Open Government Licence (OGL)](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/) (Contains Ordnance Survey data © Crown copyright and database right 2019). See "LICENSE-data.txt" inside the "data" folder for more details on OGL.

The final outcome of this exercise should be similar to the following image:

![preview](preview.png?raw=true "preview")
