# The NetLogo model of wolf population dynamics in Slovenia

The model represents the dispersion of the wolf packs in the territory of Slovenia and neighboring area of Croatia. 
At the biginning of the simulation there is 11 wolf packs, which represent existing packs in the area in 2011 - 2012. 
Wolf packs are agents of NetLogo type turtle. 
One tick in the simuation represents one year. 
Every year every pack can produce the disperger - it represents a wolf that performs the dispersion in search for the mate and establishing its own territory.
The disperger can be successful and establish a new territory. It can also be unsuccessful, in which case it is deleted from the simulation.
Territories can also disintegrate due to reaching a certain age.
We can influence the outcome of the dispersion and the disintegration of territories by adjusting the sliders listed below. <br>
&nbsp; <br>
The sliders are positioned to the left of the screen. Parameters that can be adjusted: <br>
&nbsp;&nbsp;&nbsp;&nbsp;- highway-crossing-probability [0, 1]: how likely is for the disperger to cross the highway <br>
&nbsp;&nbsp;&nbsp;&nbsp;- territory-disintegration-probability [0, 1]: how likely is it that the territory of the wolf pack will disintegrate <br>
&nbsp;&nbsp;&nbsp;&nbsp;- search-new-territory-probability [0, 1]: how likely the pack is to produce the disperger <br>
&nbsp;&nbsp;&nbsp;&nbsp;- exponential-distance-mean [30, 70]: dispersion distance (in km) <br>
&nbsp;&nbsp;&nbsp;&nbsp;- min-disintegration-age [0, 4]: minimal age at which a wolf pack can disintegrate (in years) <br>
&nbsp; <br>
We can also set the number of years for the simulation to run and whether we want for the ages of the territories to be displayed or not. 
&nbsp; <br>
To the right of the screen, we can monitor the data during the simulation.
&nbsp; <br>
&nbsp; <br>

## Structure overview

Wolf_SLO.nlogo - main file for running the model <br>
Folders containing data files for displaying: <br>
&nbsp;&nbsp;&nbsp;&nbsp;- AC: highway infrastructure <br>
&nbsp;&nbsp;&nbsp;&nbsp;- SLO_meja: Slovenian national border <br>
&nbsp;&nbsp;&nbsp;&nbsp;- pack-start: starting coordinats of wolf packs <br>
&nbsp;&nbsp;&nbsp;&nbsp;- simple_habitat: habitat suitability <br>
&nbsp; <br>


## Sources

Model was developed in NetLogo version 6.2.2. <br>
NetLogo download: https://ccl.northwestern.edu/netlogo/download.shtml <br>
Also using NetLogo Gis extension: https://ccl.northwestern.edu/netlogo/docs/gis.html <br>
&nbsp; <br>
Territory data collected from: <br>
&nbsp;&nbsp;&nbsp;&nbsp;- CORINE Land Cover 2018: https://land.copernicus.eu/pan-european/corine-land-cover/clc2018 <br>
&nbsp;&nbsp;&nbsp;&nbsp;- Open Street Map: https://www.openstreetmap.org/map=8/46.150/14 <br>
&nbsp; <br>
The model was inspired by Agent-based models predict patterns and identify constraints of large carnivore recolonizations, 
a case study of wolves in scandinavia (2020) by M. Recio, A. Singer, P. Wabakken, H. Sand, 
https://www.sciencedirect.com/science/article/pii/S0006320720308107 <br>
&nbsp; <br>
Data for the model were taken from Spremljanje stanja populacije volka v Sloveniji (3) 1., 2. in 3. sezona – 2010/11, 2011/12 in 2012/13,
project report for Action C1 (2014) by H. Potočnik, M. Krofel, T. Skrbinšek, N. Ražen, M. Jelenčič, F. Kljun, D. Žele, G. Vengušt, I. Kos,
https://www.volkovi.si/wp-content/uploads/2014/10/porocilo_c1_koncno.pdf
&nbsp; <br>
