# tornado-effects-on-water-quality-parameters

### Team Members:

Alex Clippinger,
Charles Hendrickson,
Shale Hunter,
Peter Menzies

### Project Information:

This project aims to investigate effects that tornadoes have on various measures of water quality. The investigation will look at tornadoes and corresponding stream sites within the continental United States, primarily in the Midwest. 

### Data:

Our investigation will utilize water quality readings from USGS and tornado data from NOAA's Storm Prediction Center database. USGS water quality data has been retrieved using the `dataRetrieval` package. Tornado data was downloaded from NOAA's website at https://www.spc.noaa.gov/wcm/#data.

### Data Management:

We will measure water quality by the metric of turbidity`at the Maumelle River monitoring station near Wye, AR. All tornado data from the US between 1950-2019 was collected, but this will be filtered down to tornadoes within 5 kilometers of the monitoring station (as measured by starting lat/long of each tornado).

Tornado data and water quality data are imported in a tidy format to begin with, so data management before final visualization and presentation should be minimal and take no more than a few hours.

After data processing for this project, we will retain our final data and code in a repository on github here: https://github.com/petermenzies/tornado-effects-on-water-quality-parameters

### Data Semantics:

Sediment Flux: http://purl.dataone.org/odo/ECSO_00001596

Turbidity: http://purl.dataone.org/odo/ECSO_00002359