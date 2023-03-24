# Predicting Cause of Wildfires in California
###  DSI Group #4
##### Contributions by: Carl, Mary, Alex, Krishna, and Ryan Virgin

### Problem Statement

The aim of this project is to develop a predictive model that accurately identifies the cause of wildfires using various features. The dataset includes a target variable that provides information on the statistical cause of fires. The project will involve analyzing and modeling the data using different data science techniques to accurately predict the cause of a wildfire.

The significance of this problem lies in the potential catastrophic consequences of wildfires and the need to prevent them. Accurate prediction of the cause of wildfires can help in identifying effective prevention strategies, allocating resources efficiently, and improving the response time of fire organizations. By identifying the cause of wildfires, we can better understand the factors that contribute to their occurrence and take steps to mitigate their impact on the environment and human lives.

--- 

### Dataset Introduction

In this project, we have ensembled multiple datasets to enhance our analysis. Our primary dataset includes wildfire data collected in the United States from 1992 to 2013. We have filtered this dataset to only include wildfires in California during the same period. By utilizing the geocoordinates provided in the California wildfire data, we have extracted additional information on the natural environment, such as soil conditions and elevation. To obtain this information, we have utilized the SoilGrid API to access soil composition and characteristics of the soil's chemistry. Additionally, we called the Open-Meteo API to retrieve elevation data.

--- 

### Conclusion


---

### Recommendations
1. Educate the community about the most common causes of wildfires in the area, such as lightning strikes, human activity, and equipment failure.
2. Encourage citizens to report any suspicious activity or behavior that may lead to a fire.
3. Train local firefighters and first responders to identify the cause of a fire and collect evidence for investigation.
4. Use technology such as drones and cameras to monitor high-risk areas for potential fires and gather data on environmental factors that could contribute to their occurrence.
5. Conduct regular evaluations of equipment and infrastructure that may pose a fire risk, such as power lines and transformers.

--- 

### Data Dictionary

| Column Name              | Description                                               | Data Type |
|--------------------------|-----------------------------------------------------------|-----------|
| OBJECTID                 | Unique identifier of the fire incident                    | integer   |
| Shape                    | Geometry of the fire incident                             | geometry  |
| FOD_ID                   | Unique identifier of the fire in the national database    | integer   |
| FPA_ID                   | Unique identifier of the fire in the Fire Program Analysis | string    |
| NWCG_REPORTING_UNIT_NAME | Name of the reporting unit that submitted the data         | string    |
| NWCG_REPORTING_UNIT_ID   | Identifier of the reporting unit                           | string    |
| OWNER_DESCR              | Description of the ownership category of the land          | string    |
| SOURCE_SYSTEM            | System that originated the report                          | string    |
| SOURCE_REPORTING_UNIT     | Identifier of the reporting unit that submitted the data   | string    |
| NWCG_REPORTING_AGENCY    | Agency responsible for reporting the data                  | string    |
| DISCOVERY_DOY            | Day of the year the fire was discovered (1-366)            | integer   |
| STAT_CAUSE_DESCR         | Description of the cause of the fire                        | string    |
| STATE                    | State where the fire occurred                              | string    |
| SOURCE_SYSTEM_TYPE       | Type of system that originated the report                  | string    |
| duration                 | Duration of the fire (in days)                              | float     |
| FIRE_SIZE_CLASS          | Class of the fire size                                      | string    |
| LATITUDE                 | Latitude of the fire                                        | float     |
| LONGITUDE                | Longitude of the fire                                       | float     |
| FIRE_YEAR                | Year in which the fire occurred                             | integer   |
| FIRE_SIZE                | Size of the fire (in acres)                                 | float     |
| SOURCE_REPORTING_UNIT_NAME| Name of the reporting unit that submitted the data         | string    |
| DISCOVERY_MONTH          | Month the fire was discovered (1-12)                        | integer   |
| DISCOVERY_DATE           | Date the fire was discovered (1-31)                         | integer   |
| DISCOVERY_DAY            | Day of the week the fire was discovered                     | string    |

--- 

### References

1. SlidesGo (Presentation Template)
2. Medium - How Do Neural Nets Really Work? By Chris Landschoot (https://medium.com/@crlandschoot/how-do-neural-networks-really-work-ac137e0b052)
3. Kaggle (1.88 million wildfires dataset) (https://www.kaggle.com/rtatman/188-million-us-wildfires)
4. Open-Meteo API (https://open-meteo.com/)
5. SoilGridAPI (https://soilgrids.org/)