# AGF212_2026
This repository contains the measurement data and code from the AGF212 2026 Weather group. It includes data from 3 automatic weather stations that were set up on Tellbreen and Blekumbreen between March 2nd to March 10th. Furthermore, the repository contains TinyTag and model data. We also uploaded the code we wrote to analyse the data.  
The Automatic Weather Station data are provided as .dat files, the Tinytag data are .csv files.  

The folder names correspond to the names of the logger boxes used at the weather stations.  
**Eileen** = Blekumbreen weather station  
**Layla** = Lower Tellbreen weather station  
**BobbyMcGee** = Upper Tellbreen weather station, lower level  
**Kayleigh** = Upper Tellbreen weather station, upper level  
**Radiation** = Radiation measurements at the Upper Tellbreen weather station  
**Snowpit_tinytags** = Tinytag measurements from the two snowpits :  
    - Tellbreen upper snow pit (depths from the surface : [TT5 White:0.05m], [TT5 Black:0.2m], 
    [TT1 White:0.35m], [TT1 Black:0.5m], [TT4 White:0.65m], [TT4 Black:0.8m])  
    -Blekumbreen snow pit (depths from the surface: [TT3 White:0.05m], [TT3 black:0.3], [TT24 black:0.6], [TT24 white:0.9m])  
    - TinyTags Tellbreen lower snow pit (height from ice surface: [White T16:0m (ground)], [Black T16:0.27m], [Black T16:0.27m], 
    [White TT23:0.54m], [Black TT23:0.81m]  
    - The temperature measurements from the Tellbreen lower and Blekumbreen snowpit were not used in the analysis and are just       provided for possible future studies.  

Each folder contains multiple files with the data from each data collection visit to the station. Data were collected daily with a gap from Thursday March 5th to Monday March 9th.  
The temporal resolution of the measurements is 1 minute. All times are given in UTC. There was no filtering, such as the removal of outliers or time averaging, applied to the raw data. The time slots where the data were recovered from the stations were removed from the analysis. To ensure temporal alignment with AROME data and enable comparison, the Tinytag time columns were rounded to full minutes. This is expected to have a negligible impact on measurement accuracy. 
