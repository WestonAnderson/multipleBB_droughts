# multipleBB_droughts

Running notes document [here](https://docs.google.com/document/d/1Fb4GTULZtOX-Dy1DbsV4pxdQ7d4-_F4mcNmVYy0adK4/edit)


## Proposed analyses and datasets
This project is designed to explore simultaneous breadbasket droughts across crop producing regions of the Southern Hemisphere for wheat, maize, and soybeans. We will explore both droughts across countries within a crop and across crops.

<br> <br> 


## Model screening
- How much does NCAR LENS look like observations during the growing seasons identified?

<br> <br> 


## Analyses
 - To what extent does ENSO control the likelihood of multiple breadbasket failures?
	- How strongly does it do so in joint and conditional probability distributions, and what does that say about whether regions are connected by single mechanisms or by collections of influences? Here we would compare the conditional probability of e.g. (A fails | B fails) in ENSO and non-ENSO years.
		- For example, if ENSO sometimes affects X, which affects A and B country, those would likely co-occur in the conditional probability of A fails given B fails much more frequently than if ENSO sometimes affects X which affects A and sometimes affects Y which affects B. Basically, does ENSO impose correlated risks by uniformly increasing risks with single mechanisms?
- Can we quantify the likely extent of drought/heat during these events within and across each BB?
- Is the influence of ENSO on multiple breadbasket failures intensity dependent?
	- The effect on number of BB droughts
 	- The effect of extent of drought
  	- The effect on intensity of drought  

<br> <br> 


### Data
- CRU precip and GPCC precip
- CRU Tmax
- CRU PDSI

<br> <br> 


## Methods
### Climate modes
We will use climate mode indices calculated from HadISST during the months when the variance is greatest
- Niño 3.4: NDJ ENSO index calculated from HadISST https://psl.noaa.gov/gcos_wgsp/Timeseries/Nino34/
 	- 0.5 degree C
   	- to investigate if a shifting trend needs to be removed
- IOD: SON IOD index from HadISST https://psl.noaa.gov/gcos_wgsp/Timeseries/DMI/
 	- to investigate if a shifting trend needs to be removed
- SAM: ?
  
<br> <br> 

### Crop yield growing seasons
Below I outline the crop yield growing seasons for each country and crop with the corresponding GEOGLAM crop calendar listed alongside it. Above each set of countries is a suggested three season climate season to use across all countries with an optional fourth season in brackets
 
Maize -(NDJ[F]) <br> 
- Argentina, NDJ  Maize 1 <br> 
- (south) Brazil  NDJ  Maize 2 <br> 
- South Africa  DJF  Maize 1 <br> 
- Indonesia?  JF  Maize 1  <br> 

Wheat - ([J]JAS[0]) <br> 
- Argentina  JAS  Winter Wheat <br> 
- Uruguay  MJJAS  Winter Wheat <br> 
- Brazil  JJAS  Winter Wheat <br> 
- Australia  JASO  Winter Wheat <br> 

Soybeans - ([D]JFM) <br> 
- Argentina  JFM  Soybean 1 <br> 
- Brazil  DJF  Soybean 1 <br> 


