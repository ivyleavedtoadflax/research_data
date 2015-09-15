# Silsoe organic carbon data.

[![http://dx.doi.org/10.6084/m9.figshare.1492497](https://img.shields.io/badge/DOI-dx.doi.org%2F10.6084%2Fm9.figshare.1492497-blue.svg)](http://dx.doi.org/10.6084/m9.figshare.1492497)
[![http://figshare.com/licensing](https://img.shields.io/badge/license-BY--CC-brightgreen.svg)](http://figshare.com/licensing)

Cite as:

Upson, Matthew (2015): Soil organic carbon data from: Soil organic carbon and root distribution in a temperate arable agroforestry system. figshare.
http://dx.doi.org/10.6084/m9.figshare.1492497
Retrieved 09:35, Sep 15, 2015 (GMT)

## Data descriptive

|Name|Units|Description|
|:---|:---|:---|
|year| years| Year data was collected.|
|ID|| Code indentifying individual trees in the experiment closest to the soil carbon measurements. e.g.: 1CB4: Block one, Cropped treatment, Beaupre hybrid, tree 4. See Upson & Burgess (2013).|
|block|| Following the original experimental design, there are three replicate blocks (B1:B3).|
|ctrltmt|| This column describes whether the sample was taken from the silvoarable agroforestry experiment (tmt), or from surrounding arable controls (ctrl).|
|treat|| Cropping treatment. Either C for continuously cropped, or F for continously Fallow.|
|dist_m| m | Distance of sample from sample tree in metres.|
|depth_cm| cm | Depth from which the sample was taken in cm: 5, 16, 30, 50, 83, 128.|
|di_cm|| Depth of assumed sampling increment centred on the sampling depth.|
|OCC_g_100g| g 100g<sup>-1</sup> |Uncorrected organic carbon content as determined by a modified Walkley Black dichromate digest.|
|BD_g_cm3| g cm<sup>-3</sup>| Soil bulk density, in grams per centimetre cubed. measured using the ring method described by Klute (1986).|
|mEquiv|  | Assumed mass of each soil layer sampled. In this case 1 gm cm<sup>-3</sup> &times; di_cm &times; 10<sup>4</sup>.
mMeas|| Actual measured mass from measured bulk density, i.e.: BD_g_cm3 	&times; di_cm.|
|tC|| Depth adjusted required to reach mEquiv. Calculated from ((mEquiv - mMeas) 	&times; 10<sup>-</sup>4) / BD_g_cm3.|
|SOC_ESM_Mg_ha1| Mg ha<sup>-1</sup> | Soil organic carbon stock (Mg ha<sup>-1</sup>) calculated from the equivalent soil mass technique by: (OCC_g_100g &times; 0.1) &times; BD_g_cm3 &times; tC &times; 10<sup>4</sup> &times; 10<sup>-</sup>.
|SOC_Mg_ha2| Mg ha<sup>-1</sup> | Soil organic carbon stock (Mg ha<sup>-1</sup>) caclulated using the fixed depth method: OCC_g_100g &times; BD_g_cm3 &times; di_cm.|

## References
* Klute, A. (1986) *Methods of Soil Analysis: Part 1 - Physical and Mineralogical Methods*. 2nd edn. Wisconsin: American Society of Agronomy. 
* Upson, M.A. & Burgess, P.J. (2013) Soil organic carbon and root distribution in a temperate arable agroforestry system. *Plant and Soil*, 373(1-2), pp.43–58. Avilable at: http://link.springer.com/article/10.1007%2Fs11104-013-1733-x.