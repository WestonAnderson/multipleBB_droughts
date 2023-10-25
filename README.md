# multipleBB_droughts

## Proposed analyses and datasets
This project is designed to explore simultaneous breadbasket droughts across crop producing regions of the Southern Hemisphere for wheat, maize, and soybeans. We will explore both droughts across countries within a crop and across crops.

## Model screening
- How much does NCAR LENS look like observations during the growing seasons identified?

## Analyses
 - To what extent does ENSO control the likelihood of multiple breadbasket failures?
	- How strongly does it do so in joint and conditional probability distributions, and what does that say about whether regions are connected by single mechanisms or by collections of influences? Here we would compare the conditional probability of e.g. (A fails | B fails) in ENSO and non-ENSO years.
		- For example, if ENSO sometimes affects X, which affects A and B country, those would likely co-occur in the conditional probability of A fails given B fails much more frequently than if ENSO sometimes affects X which affects A and sometimes affects Y which affects B. Basically, does ENSO impose correlated risks by uniformly increasing risks with single mechanisms?

### Data
- CRU precip or GPCC precip? (we had proposed both at different points)
- CRU Tmax
- CRU PDSI



## Methods
### Climate modes
We will use climate mode indices calculated from HadISST during the months when the variance is greatest
	- Niño 3.4 - NDJ ENSO index calculated from HadISST https://psl.noaa.gov/gcos_wgsp/Timeseries/Nino34/
 		- 0.5 degree C
   		- to investigate if a shifting trend needs to be removed
	- IOD - SON IOD index from HadISST https://psl.noaa.gov/gcos_wgsp/Timeseries/DMI/
 		- to investigate if a shifting trend needs to be removed
	- SAM - ?

### Crop yield growing seasons
Below I outline the crop yield growing seasons for each country and crop with the corresponding GEOGLAM crop calendar listed alongside it. Above each set of countries is a suggested three season climate season to use across all countries with an optional fourth season in brackets
 
Maize -(NDJ[F]) <br> 
- Argentina, - NDJ - Maize 1 <br> 
- (south) Brazil - NDJ - Maize 2 <br> 
- South Africa - DJF - Maize 1 <br> 
- Indonesia? - JF <br> 

Wheat - ([J]JAS) <br> 
- Argentina - JAS - Winter Wheat <br> 
- Uruguay - MJJAS - Winter Wheat <br> 
- Brazil - JJAS - Winter Wheat <br> 
- Australia - JJAS <br> 

Soybeans - ([D]JFM) <br> 
- Argentina - JFM - Soybean 1 <br> 
- Brazil - DJF <br> 


