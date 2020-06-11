# FDRS
ArcGIS Toolbox for Fire Danger Rating System based on the Canadian Forest Fire Weather Index System

The Fire Danger Rating System (FDRS) is a forest/vegetation fire monitoring system that provides information to support fire management. FDRS products are used as a guide to predict fire behaviour, with the objective to help stakeholders make informed decisions on fire mitigation and smoke haze pollution.

FDRS uses measured meteorological variables such as temperature, relative humidity, rainfall and wind speed collected from meteorological stations or remote sensing data.

## Requirement
ArcGIS and python

## How to use
Add FDRS_tbx to local directory, and add FDRS.pyt from ArcGIS toolbox. 
If you have timeseries data, you can run this tool [testFDRS.py](https://github.com/wfpidn/FDRS/blob/master/FDRS_tbx/testFDRS.py)

## Data
This toolbox required daily input data, there are few data example inside Data/Input folder. 
- **Precipitation**: CHIRPS, CHC - University California Santa Barbara. Download: https://data.chc.ucsb.edu/products/CHIRPS-2.0/global_daily/tifs/
- **Temperature**: DarkSky - https://maps.darksky.net/@temperature,-6.208,106.776. The GeoTIFF images can be downloaded like so: http://maps.forecast.io/temperature/YEAR/MONTH/DAY/HOUR.tif
For example, the image for May 16, 2020 at 6AM UTC ~ 12PM WIB (UTC+7) is: http://maps.forecast.io/temperature/2020/05/16/06.tif
- **Relative Humidity**: NOAA Global Forecast System. GRIB filter https://nomads.ncep.noaa.gov/cgi-bin/filter_gfs_0p25.pl (bit complicated). 
- **Wind Speed**: NOAA Global Forecast System. GRIB filter https://nomads.ncep.noaa.gov/cgi-bin/filter_gfs_0p25.pl (bit complicated). 

## Contact
FDRS toolbox originally developed by [spatialexplore](https://github.com/spatialexplore) for WFP's activities with LAPAN.
If you have any question related to FDRS tool and application in Indonesia, contact [bennyistanto](https://github.com/bennyistanto)
