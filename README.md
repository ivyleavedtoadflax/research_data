# General Description
This repository is home to data presented in the following PhD thesis, and the papers that arise from it:

Upson, M.A. (2014) The carbon storage benefits of agroforestry and farm woodlands. PhD Thesis. Cranfield University. Available at [http://dspace.lib.cranfield.ac.uk/handle/1826/9298](http://dspace.lib.cranfield.ac.uk/handle/1826/9298)

<!--Files are arranged into directories of field site first, then measurement type. Each data file is presented with a description (as a .md file). Geopgraphical location of sampling points are provided in a number of formats (geoJSON, kml, .shp). The script for producing these plots is included as [geospatial.R](geospatial.R).-->

# Field sites

Site prefixes and file extensions have been excluded for brevity. See indiviudal README files for DOI, and additional details.

## Silsoe silvoarable experiment [![license](https://img.shields.io/badge/license-BY--CC-brightgreen.svg)](http://figshare.com/licensing)

The Silsoe silvoarable experiment at the Cranfield University experimental farm is described by Burgess et al. (2003, 2005).

### File descriptions

|Filename|Collected by|Type|Description|
|:---|:---|:---|:---|
|[coarse_root_agg](silsoe/silsoe_coarse_root_agg)| Matthew Upson, Francois Clavagnier | Coarse root counts | Data describe 2130 observations of coarse root counts recorded from the wall of a trench dug at 90 degrees to each of siz sample trees. Measurements were taken in 0.2 x 0.2 m squares to a depth of 1.5 m, and up to 5 m distance from the sample tree. Roots were grouped into four size classes from 2-5 mm until >20 mm. In line with the final analysis in Upson & Burgess (2013), these data have been aggregated into five distances of one metre each.|
|[coarse_root_raw](silsoe/silsoe_coarse_root_raw)| Matthew Upson, Francois Clavagnier | Coarse root counts | The raw version of the above but without grouping by distance. 4800 observations.|
|[fine_root_length](silsoe/silsoe_fine_root_length)| Matthew Upson, Francois Clavagnier, Pascal Pasturel | Fine root length and mass | This file is a concatenation of two datasets: the first was collected in 2004 by Pascal Pasturel (originally described in Pasturel (2004); the second was collected by Matthew Upson and Francois Clavagnier in 2011, and are described in Upson & Burgess (2013).|
|[soil_organic_carbon](silsoe/silsoe_soil_organic_carbon)| Matthew Upson, Francois Clavagnier | Soil organic carbon | These data describe 216 observations of organic carbon content and soil bulk density, and soil organic carbon stock calculations using the fixed depth and equivalent soil mass calculations (Ellert, 1995).|
|[zimmermann_fractions](silsoe/silsoe_zimmermann_fractions)| Matthew Upson | Soil organic carbon fractionation | These data describe the fractionation (Zimmermann, 2007) of eighteen samples drawn from those analysed for soil organic carbon (above). Fractionation was completed at Rothamsted Research under contract from Cranfield University.|


## Clapham Park

### File descriptions

|Filename|Author|Type|Description|
|:---|:---|:---|:---|
|psd| Matthew Upson, Claire Smith | Particle Size Distribution | These data describe 72 measurements of particle size distribution (PSD) taken at locations at the Clapham Park field site, north of Bedford, UK. The full standard operating procedure for the laboratory procedures is included in the [thesis](http://dspace.lib.cranfield.ac.uk/handle/1826/9298) on p.301. The location of each sample is also given. In most cases, the values of interest are included in the columns SAND, SILT, and CLAY, but percentages of three different sand fractions are also given.|
|bd| Matthew Upson | Soil bulk density | These data describe 1985 measurements of soil bulk density taken at Clapham Park during in 2013. Samples were taken using a slot auger and compared to measurements taken by the more usual core method. See [Upson (2013)](http://dspace.lib.cranfield.ac.uk/handle/1826/9298) p.91 for details.|


# References
* Burgess, P.J., Incoll, L.D., Hart, B.J., Beaton, A., Piper, R.W., Seymour, I., Reynolds, F.H., Wright, C., Pillbeam, D.J., Graves, A.R. and Pilbeam, D.J. (2003) *The Impact of Silvoarable Agroforestry with Poplar on Farm Profitability and Biological Diversity: Final Report to DEFRA*. Silsoe: Institute of Water and Environment, Cranfield University.
* Burgess P.J., Incoll L.D., Corry D.T., Beaton A., Hart B.J. (2005) Poplar (Populus spp) growth and crop yields in a silvoarable experiment at three lowland sites in England. *Agroforestry Systems* 63, pp.157–169
* Ellert, B.H. and Bettany, J.R. (1995) 'Calculation of organic matter and nutrients stored in soils under contrasting management regimes', *Canadian Journal of Soil Science*, 75(4), pp. 529–538.
* Pasturel, P. (2004) *Light and water use in a poplar silvoarable system*. MSc Thesis. Cranfield: Cranfield University
* Upson, M.A. & Burgess, P.J. (2013) Soil organic carbon and root distribution in a temperate arable agroforestry system. *Plant and Soil*, 373(1-2), pp.43–58. Avilable at: http://link.springer.com/article/10.1007%2Fs11104-013-1733-x.
* Upson, M.A. (2014) *The carbon storage benefits of agroforestry and farm woodlands*. PhD Thesis. Cranfield University. Available at: http://dspace.lib.cranfield.ac.uk/handle/1826/9298.
* Zimmermann, M., Leifeld, J., Schmidt, M.W.I., Smith, P. and Fuhrer, J. (2007) ‘Measured soil organic matter fractions can be related to pools in the RothC model’, *European Journal of Soil Science*, 58(3), pp. 658–667.
