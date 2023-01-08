# NYUS.1_CHmodel


Data and code for analysis and figure preparation for the manuscript "Development of a new cold hardiness prediction model for grapevine using phased integration of acclimation and deacclimation responses".

## File descriptions

### DataCH_allCVs_allPIs.csv

Data for cold hardiness from Vitis vinifera 'Cabernet Sauvignon' and 'Riesling', and V. labruscana 'Concord'. Columns are "Cultivar", "LTE", "Date", "PI", "DataType", "Location". Data are for three cultivars. "LTE" refers to low temperature exotherm, which indicates killing temperature for a given bud. "PI" indicates lab which collected the dataset. "DataType" can be ignored. "Location" is the same for all data, and only includes Geneva, refering to Geneva, NY.


### DataWeather.csv

Hourly weather data from 30 April 2012 to 31 July 2021 extracted from NEWA (newa.cornell.edu) for the "Geneva (Bejo)" station.


### NYUS.1_******.Rmd

R Markdown files for data analyses conducted for the three cultivars separately (****** = CabSauv, Concord, or Riesling). The model optimization step can take many days to run. R workspace files are available and can be shared upon request to avoid running all the code.


### Figures.Rmd

R Markdown file that generates figures within the manuscript, as well as some of the stats presented within figures.

