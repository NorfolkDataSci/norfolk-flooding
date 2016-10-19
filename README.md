# A Street-Level Flood Prediction Project
An analysis to predict which areas of Norfolk are flooded based on Weather, Tides, and other factors. The goal is to be able to create a real-time traffic map that highlights which areas of the city are flooded and have started re-routing traffic, so you can plan your route accordingly. This should forecast in the next hour or certain timeframe whether the water level will keep rising or start falling.

The following data sources:

* NOAA (Rainfall, Wind, Tides, River & Coastal Water Levels)
  * http://www.ncdc.noaa.gov/IPS/hpd/hpd.html - Hourly (Historical, 6-month lag)
  * https://openweathermap.org/api - Current Weather
  * http://tidesandcurrents.noaa.gov/api/ - NOAA CO-OPS API For Data Retrieval
* USGS (Water Discharge) 
  * http://waterdata.usgs.gov/va/nwis/uv?site_no=0204288771
* Google Maps (Elevation)
  * https://developers.google.com/maps/documentation/elevation/intro
  * Elevation along a path: https://developers.google.com/maps/documentation/javascript/examples/elevation-paths
* Microsoft/Bing Traffic API
  * https://msdn.microsoft.com/en-us/library/hh441730.aspx
* Social Media
  * Scanning tweets of flooded intersections (@511hamptonroads, others?)
  
Weather Underground has generous weather API: 
https://www.wunderground.com/weather/api/d/pricing.html
  
