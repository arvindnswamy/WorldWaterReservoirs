# WorldWaterReservoirs

## Description

Collection of codes and data from different water reservoirs around the world. USGS has data for many reservoirs in the US. In India, data are available for reservoirs supplying water to Hyderabad and Chennai as well as for reservoirs in the state of Karnataka. These data are available from the respective city water department websites for Hyderabad and Chennai, and from Karnataka State Natural Disaster Monitoring Center for Karnataka. URLs are included in the relevant files.

**Data from USGS website**: ExtractingVolumeLevelInformationFromUSGSReservoirData.ipynb

**Data from Hyderabad**: AccessingReservoirLevelDataFromHyderabadWaterWorks.ipynb

**Data from Chennai**: ExtractingDataFromChennaiWaterBoardReservoirLevels.ipynb

**Data from Karnataka**: AccessingReservoirLevelsInKarnataka.ipynb

The data for different reservoirs are stored as csv files.

Mostly, we are interested in getting level vs volume stored data. The inverse of the slope of this curve gives the area of the reservoir at that level. 

Credit to @smythp for helping me with the initial code to download data from the Hyderabad website, which seemed extremely daunting because of javascript and forms and so on. 

The following states in India seem to have data that can be retrieved but with some difficulty

Kerala - [https://sldckerala.com/index.php?id=7#]

Madhya Pradesh - [http://eims1.mpwrd.gov.in/fcmreport/control/generatefcmdailyreport?sdate=06/07/2019&dhiStatus=N]

Maharashtra - perhaps

Odisha - perhaps

Andhra Pradesh - perhaps

CWC has data inthe form of a pdf file. Need to mine that.

**Other countries which seem to have data**

Australia, esp. NSW, maybe Melbourne water

South Africa - partial information (capacity but no level). No historical data.





