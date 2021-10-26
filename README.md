# tornado-effects-on-water-quality-parameters

### Team Members:

Alex Clippinger,
Charles Hendrickson,
Shale Hunter,
Peter Menzies

### Project Information:

This project aims to investigate effects that tornadoes have on various measures of water quality. The investigation will look at tornadoes and corresponding stream sites within the continental United States, primarily in the Midwest. 

### Data:

Our investigation will utilize water quality readings from USGS and tornado data from NOAA's Storm Prediction Center database. USGS water quality data has been retrieved using a USGS API via the `dataRetrieval` package. Tornado data was retrieved using a NOAA API via the `rnoaa` package.

### Data Management:

We will assess water quality based on four parameters measured daily at the Maumelle River monitoring station near Wye, AR. All tornado data from the US between 1950-2019 was collected, but this will be filtered down to tornadoes within 5 kilometers of the monitoring station (as measured by starting lat/long of each tornado).

Tornado data and water quality data are imported in a tidy format to begin with, so data management before final visualization and presentation should be minimal and take no more than a few hours—this will be undertaken as a group.

After data processing for this project, we will store our final datasets on KNB (https://dev.nceas.ucsb.edu/), and our code will be available in a repository on github here: https://github.com/petermenzies/tornado-effects-on-water-quality-parameters

Our data log is stored in the file 'data-log_tornado-effects-on-water-quality.xlsx' in the github repository. Because data was only retrieved once, it it a short log with only one entry for tornado data and one entry for stream data.

### Data Semantics:

Stream discharge: http://sweetontology.net/phenHydro/StreamDischarge

Turbidity: http://purl.dataone.org/odo/ECSO_00002359

Dissolved Oxygen: http://purl.dataone.org/odo/ECSO_00001669

River water temperature: http://purl.dataone.org/odo/ECSO_00001528

Tornado: http://purl.obolibrary.org/obo/ENVO_01001482
