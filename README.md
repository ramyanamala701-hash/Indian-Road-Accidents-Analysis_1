# Indian Road Accidents Analysis

## 1. Project Overview

The **Indian Road Accidents Analysis** project analyzes road accident records to identify patterns related to accident severity, road conditions, weather, vehicle types, driver characteristics, speed, safety measures, fatalities, injuries, and primary causes.

The project demonstrates the use of Python-based data analysis techniques including data inspection, cleaning, filtering, transformation, feature engineering, grouping, aggregation, statistical analysis, and visualization.

## 2. Objectives

* Analyze road accident records and identify important patterns.
* Study accident severity and casualty levels.
* Analyze accident patterns across States/UTs.
* Examine the relationship between accidents and weather, road surface, and lighting conditions.
* Analyze vehicle types involved in accidents.
* Study recorded primary causes of accidents.
* Examine speeding, alcohol involvement, and helmet/seatbelt usage.
* Calculate fatalities, injuries, and total casualties.
* Present important findings using data visualizations.

## 3. Dataset Description

The dataset contains **240 accident records and 25 attributes** covering the period **2021–2024**.

The attributes include:

* Accident ID
* Date and time
* Year and month
* State/UT
* District
* Road type
* Weather
* Road surface
* Lighting
* Vehicle type
* Driver age group
* Driver gender
* Speed limit
* Estimated speed
* Alcohol involvement
* Helmet/seatbelt usage
* Accident severity
* Fatalities
* Severe injuries
* Minor injuries
* Primary cause
* Pedestrian involvement
* Latitude
* Longitude

## 4. Tools and Technologies

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn

## 5. Data Analysis Process

### Data Loading and Inspection

The dataset was loaded using Pandas and inspected using operations such as:

* `head()`
* `shape`
* `columns`
* `info()`
* `isnull().sum()`
* `duplicated()`
* `describe()`
* `nunique()`

### Data Cleaning

The dataset was checked for missing values and duplicate records.

* No missing values were found.
* Duplicate records were checked and removed where applicable.
* Data types were inspected and prepared for analysis.

### Data Filtering

The dataset was filtered to examine:

* Fatal accidents
* Accidents where estimated speed exceeded the speed limit
* Alcohol-involved accidents

### Data Transformation and Feature Engineering

New features were created from the existing data:

* `speed_difference_kmph`
* `speeding`
* `total_injuries`
* `total_casualties`

### Data Grouping and Aggregation

Pandas grouping and aggregation operations were used to analyze:

* Accidents by State/UT
* Accidents by severity
* Accidents by weather
* Accidents by vehicle type
* Fatalities by State/UT
* Average speed by road type
* Average casualties by severity

### Statistical Analysis

The project calculated:

* Total accidents
* Total fatalities
* Total injuries
* Total casualties
* Severity percentages
* Speeding percentage
* Alcohol involvement percentage
* Helmet/seatbelt usage percentage
* Correlations between numerical variables
* Accident counts by primary cause and month

## 6. Data Visualizations

The project includes visualizations for:

* Accidents by year
* Accidents by State/UT
* Accident severity
* Primary causes
* Vehicle types
* Weather conditions
* Road surface conditions
* Lighting conditions
* Estimated speed vs. speed limit
* Fatalities by State/UT

All charts include appropriate titles and axis labels.

## 7. Key Findings

* The dataset contains **240 recorded accidents**.
* Maharashtra has the highest recorded accident count in the dataset with **24 accidents**.
* Assam and Telangana each have **19 accidents**.
* **Overspeeding** is the most frequently recorded primary cause, appearing in **74 accident records**.
* **Drunk Driving** is the second most frequently recorded primary cause, with **46 records**.
* **Two-wheele**
