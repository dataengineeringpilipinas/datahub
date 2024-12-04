---
title: "Project Stormchaser Data Source"
contributor: "TreacherousDev"
date_added: 2024-11-30
last_updated: 2024-12-03
version: v0.2.2
source_organization: "National Centers for Environmental Information (NCEI)"
time_period: "1842-2024"
update_frequency: "Real-time"
data_formats:
  - "API"
license: " NOAA Open Data Dissemination (NODD)"
tags:
  - typhoon
  - cyclone
  - hurricane
  - basin
  - archive
---

# The International Best Track Archive for Climate Stewardship

*Note: To view the full metadata for this data source, please see the raw file in our [GitHub repository](https://github.com/dataengineeringpilipinas/datahub/tree/main/data-sources).*

## Description
The International Best Track Archive for Climate Stewardship (IBTrACS) is a collection of data about tropical cyclones from all over the world. 
It gathers and organizes information like storm paths, wind speeds, and pressure from different weather agencies into one place. 
This makes it easier for scientists, researchers, and the public to study and understand storms and their patterns. 
It’s managed by NOAA’s National Centers for Environmental Information (NCEI) and is freely available for anyone to use.

## Data Collection Methodology
Data was collected by creating a web scraper API that visits and reads table data based on year, basin and typhoon name.

## How to Access
Follow this [link](https://ncics.org/ibtracs/index.php?name=browse-year-basin),  
or use this [library](https://github.com/TreacherousDev/Stormchaser/blob/main/scripts/typhoon_scraper.py)

## Data Dictionary
| **Column Name**     | **Description**                                                                                      | **Data Type**   | **Example**            |
|----------------------|-----------------------------------------------------------------------------------------------------|-----------------|------------------------|
| `SID`               | Unique identifier for the storm.                                                                    | String          | "2021309N19141"       |
| `NAME`              | Name of the storm (if assigned).                                                                    | String          | "Haiyan"              |
| `SEASON`            | Year when the storm occurred.                                                                       | Integer         | 2023                  |
| `BASIN`             | Ocean basin where the storm occurred (e.g., Western Pacific, North Atlantic).                       | String          | "WP"                  |
| `LAT`               | Latitude of the storm's center during a specific observation.                                       | Float           | 13.4                  |
| `LON`               | Longitude of the storm's center during a specific observation.                                      | Float           | 120.8                 |
| `WIND`              | Maximum sustained wind speed in knots during the observation.                                       | Float           | 130                   |
| `PRES`              | Minimum central pressure in millibars (hPa) during the observation.                                 | Float           | 920                   |
| `ISO_TIME`          | Date and time of the observation in ISO format (UTC).                                               | DateTime        | "2023-11-05T18:00:00" |
| `STORM_TYPE`        | Type of the storm (e.g., Tropical Depression, Tropical Storm, Typhoon).                             | String          | "Typhoon"             |
| `NATURE`            | Nature of the system (e.g., Tropical, Subtropical, Extratropical).                                  | String          | "Tropical"            |
| `TRACK_TYPE`        | Track data source type (e.g., Best Track, Operational Track).                                       | String          | "Best Track"          |
| `LANDFALL`          | Indicator if the storm made landfall (Yes/No).                                                      | String          | "Yes"                 |
| `ADDITIONAL_INFO`   | Any remarks or comments about the storm's behavior or track.                                        | String          | "Rapid intensification noted." |


## Relevance to Philippine Data Projects
The IBTrACS data plays a crucial role for projects in the Philippines as a beacon of information.
The Philippies lies in the center of the world’s most active typhoon basin, and every year over 20 tropical storms pass through or near the country, often causing major damage. 
This data helps us understand where these storms come from, how they move, and how strong they are.

## Known Issues or Limitations
- There are gaps in the data because not all storms are recorded perfectly. Sometimes, important details like wind speed or pressure might be missing.
- Many storms, especially weaker ones, are not given names. This can make it harder to track or identify them when looking at historical data.

## Related Projects
- N / A

## Additional Resources
[digital-typhoon](http://agora.ex.nii.ac.jp/digital-typhoon/) website, containing information about typhoon data in the North and South Western Pacific.
