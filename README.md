# Data Preprocessing for Energy System Models 
## Load Data Preprocessing

### Thomas Möbius, Mira Watermeyer, Oliver Grothe, Felix Müsgens

Load directly impacts electricity prices, making it one of the most important variables to include in fundamental energy system models. However, day-ahead load forecasts, published by Transmission System Operators (TSO), are known to be biased and have a high potential to be improved. Unfortunately, technically advanced models for preprocessing load time series, as they are proposed in the literature, might intimidate energy system modelers and hinder them from actually improving their input data. We therefore propose an as-simple-as-it-gets model that improves the average load forecast error. We achieve a 26~\% improvement in our empirical example, which easily keeps up with the more complex models. We feed our improved load data into a fundamental, day-ahead energy system model that we present in detail as a further contribution. Applied to real data for the German market, we see the benefits from the improved load data particularly in times where prices are high and the market situation is tight. In these situations, predicted prices vary strongly with the assumed loads, so it pays to have the loads as precise as possible.

### Keywords:
Data preprocessing, Day-ahead electricity prices, Energy system modelling, Load forecasting
 
### Links: 
tba

### The code reproduces the benchmarks from the paper 
This repository includes all relevant files for the load data preprocessing part of the paper. To reproduce the load data preprocessing, the code "load_datapreprocessing" has to be run. It was tested on Matlab R2020b. The Excel-Files "Load_DayAheadForecastAndActual_DL-LU_2016to2019.xlsx" and "holidaygermany.xlsx" are needed to run the code. "Output_Impr_loadforecast_2017to2019.xlsx" contains the result: TSO day-ahead load prediction, actual load and the improved load forecast (load data preprocessing). 
The repository including all relevant files for the energy system model part of the paper can be found here: https://github.com/BTU-EnerEcon/Data-PreProcessing-for-Energy-System-Models.

### Citing IntEG

The model published in this repository is free: you can access, modify and share it under the terms of the <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>. This model is shared in the hope that it will be useful for further research on topics of risk-aversion, investments, flexibility and uncertainty in ectricity markets but without any warranty of merchantability or fitness for a particular purpose. 

If you use the model or its components for your research, we would appreciate it if you
would cite us as follows:
```
This paper is in review. The reference to the working paper version is as follows:

tba
```
