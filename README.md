# Large Wood as a Confounding Factor in Interpreting the Width of Spring-Fed Streams: Datasets and Supplementary Material
Stream width vs. wood length and wood orientation data for spring-fed streams in western US

Dana Lapides [1] and Michael Manga [1]

[1] Department of Earth and Planetary Science, University of California, Berkeley

[![DOI](https://zenodo.org/badge/164133590.svg)](https://zenodo.org/badge/latestdoi/164133590)

This repo hosts a Jupyter notebook which contains aggregated data in the form of a python dictionary about the characteristics of 
spring-fed streams in the Western United States. Streams included in the data are:
  
  	Spring-fed streams:
	
	Big Springs, ID
  
	Buffalo River, ID
  
	Chick Creek, ID
  
	*Deschutes River, OR
  
	Elk Springs Creek, ID
  
	Lucky Dog Creek, ID
	
	Reservation Spring, OR
  
	Snow Creek, OR
  
	Toms Creek, ID
  
	*Cultus River, OR
  
	Browns Creek, OR
  
	Mill Creek, ID
  
	Tyler Creek,ID
  
	Billingsley Creek, ID
  
	Blue Springs, OR
  
	Spring Creek A, OR
  
	Spring Creek B, OR
  
	Fall River, OR
  
	Black Sands Creek, MT
  
	*Hat Creek, CA
  
	Lost Creek, CA
  
	Big Springs Creek, CA
  
	Unnamed Spring 1, AZ
  
	Whisting Spring, AZ
  
	Unnamed Spring 2, AZ
  
	Unnamed Spring 3, AZ
  
	West Pinchot Spring, AZ
  
	*Big Springs, MO
  
	Maramec Springs, MO
  
	*Silver Creek, ID
	
	Quinn River, OR
	
	Blue Heart Springs, ID
	
	Tucker Bay Spring, MO
	
	*Lost Creek, OR
	
	Rio Salado, Chile
	
	Stream 0, Chile
	
	
	
	Runoff-fed streams:
  
	Crystal Castle Cr, OR
  
	Deer Creek, OR
  
	*Cultus Creek, OR
  
	Moose Creek, ID
	
	*Boulder Creek, OR
	
	Quaking Aspen Canyon, AZ
	
	Merritt Draw, AZ
	
	Buck Springs Canyon, AZ
	
	*Hills Creek, OR
	
	*Little Deschutes River, OR
	
	*South Fork McKenzie River, OR
	
	*Bourbeuse River, MO
	
	*Current River, MO
	
	*Huzzah Creek, MO
	
	*Little Piney Creek, MO
	
	*Meramec River, MO
	
	*Fall River, ID
	
	*Henry's Fork, ID
	
	*Robinson Creek, ID
	
	*McCloud River,CA
	
Data are included as follows:


	GPS: GPS location as identified using Google Earth Pro
  
	elevation: elevation at the GPS point identified using Google Earth Pro
  
	stream_width: stream width measured at about 10 cross-sections near the GPS location using Google Earth Pro
  
	wood_length: length of about 10 pieces of large woody debris found in or near the channel
  
	discharge: discharge level measured by the author specified in info_source. All discharge values are bankfull except those for streams marked by a star. Those streams have estimated bankfull discharges. For spring-fed streams, the estimate is mean discharge since mean discharge is very close to bankfull discharge. For runoff-fed streams, the estimate is 1.25 year flow.
  
	info_source: keyword to identify source of discharge information, full citations below
  
	temp: average annual temperature at that location as measured by NOAA, except El Tatio sites for which data come from a weather station, full citation below
  
	MAP: mean annual precipitation at that location as measured by NOAA, except El Tatio sites for which data come from a weather station, full citation below
  
	snow: mean annual snowfall at that location as measured by NOAA, full citation below
  
	avg_str_wid: stream width as measured by Griffiths et al. (2008) for streams in AZ that do not contain wood
  
	wood_hist: difference in orientation from downstream direction measured up to 90 degrees since it is
              not possible to distinguish reliably between ends of LWD in Google Earth Pro
	      
	woodperlen: number of single pieces of wood per stream segment length, measured via Google Earth Pro
	
	logjamperlen: number of logjams per stream segment length, measured via Google Earth Pro
	
	basin_area: watershed area feeding the stream gauge, info sources match discharge info source except Maramec Springs (from Vandike, 1996), Deer Creek (from USGS), and Fall River (from Manga, 1996)
	
              
Additional Data Sources:

Anthony Arguez, Imke Durre, Scott Applequist, Mike Squires, Russell Vose, Xungang Yin, and Rocky Bilotta (2010). 
	NOAA's U.S. Climate Normals (1981-2010). NOAA National Centers for Environmental Information. DOI:10.7289/V5PN93JP.
	
Deas, M. (2006). Big Springs Creek and Spring Complex--Estimated Quantification [Technical Memorandum]. 
  Retreived from https://www.waterboards.ca.gov/northcoast/ \\water\_issues/programs/tmdls/shasta\_river/060707/23appendixgtechnicalmemorandum-\\bigspringscreekandspringcomplexflow.pdf.

Griffiths, R. E., Anderson, D. E., and Springer, A. E. (2008). The morphology and hydrology of small 
  spring-dominated channels. Geomorphology, 102(3-4), 511-521.

Hygelund, B. N. (2002). Geomorphic and Hydraulic Effects of Large Woody Debris: Insights from Spring-Dominated Streams 
  in the Oregon Cascades (Master's Thesis). U. of Oregon.
  
Jefferson, A., Grant, G. E., Lewis, S. L., and Lancaster, S. T. (2010). Coevolution of hydrology and topography on a basalt 
  landscape in the Oregon Cascade Range, USA. Earth Surface Processes and Landforms. 35, 803-816.
  
Kull, C., Grosjean, M. (2000). "Late Pleistocene climate conditions in the north Chilean Andes drawn from a climate–glacier 
  model". Journal of Glaciology. 46 (155): 622–632.

Manga, M. (1996). Hydrology of spring-dominated streams in the Oregon Cascades. Water Resources Research, 32(8), 2435-2439.

Maramec Spring Park [Web log post]. Retreived September 13, 2018, from \\http://www.maramecspringpark.com/.

Munoz-Saez, C., Manga, M., and Hurwitz, S (2018). Hydrothermal discharge from the El Tatio basin, Atacama, Chile. 
  Journal of Volcanology and Geothermal Research, 361, 25-35.

U.S. Geological Survey (2018). National Water Information System data available on the World Wide Web 
  (Surface-Water Data for the Nation). Accessed Sept. 13, 2018, at http://waterdata.esgs.gov/nwis.
  
Vandike, J. E. (1996). The Hydrology of Maramec Spring. Missouri Department of Natural Resources, Division of 
  Geology and Land Survey, Water Resources Report Number 55.

Whiting, P. J., and Moog, D. B. (2001). The geometric, sedimentologic and hydrologic attributes of spring-dominated 
  channels in volcanic areas. Geomorphology, 39(3-4), 131-149.
  
Wilkerson Jr., T. F. (2003). Current River Watershed Inventory and Assessment. Missouri Department of Conservation.
