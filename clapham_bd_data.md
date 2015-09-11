# General Description

## Data descriptive

|Name|Units|Description|
|:---|:---|:---|
|dateCollected| _ | Date sample collected in the field. |
|Type| _ | One of four values corresponding to the experimental treatments: FW (farm woodland), MW (mature woodland), PA (pasture control), and SP (silvopasture).|
|ID| _ | Sample location ID. {1,2,...,40} for PA, {1,...,20} for FW and SP, {1, 2, 3} for MW.|
|rep| _ | Replicate. Three replicates were taken at each depth.|
|block| _ | The experiment was split into two blocks to attempt to explain some of the variance: the PA and SP (block 1) and FW (block 2). This was because the SP and PA treatments were intimately mixed, whilst the FW treatment was separate.|
|depth| cm | Depth at which the sample was taken {5,15,30,50}.|
|BD| g cm<sup>-1</sup> | Soil bulk density, calculated using mass/core volume. |
|MC| g 100 g<sup>-1</sup> | Soil moisture content measured using the bulk density samples calculated from $wet mass - dry_mass$|
|coreLength| cm | As noted, BD samples were taken using a slot auger and needed to be cut to a know length to allow a volume to be calculated. This was not a uniform value, and depended on the quality of the core. This value has been recorded here.|
|coreArea| cm<sup>2</sup> | Cross sectional area of the slot auger for use in calculating core volume. |
|VMC| cm<sup>3</sup> cm<sup>-3</sup> | Volumetric soil moisture content derived from moisture content (MC). |
|grid| _ | Location of sampling point in British National Grid coordinates.|
|lat| decimal degrees | Location of sampling point.|
|lon| decimal degrees | Location of sampling point.|


