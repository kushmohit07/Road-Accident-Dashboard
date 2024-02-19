# Road-Accident-Dashboard
## 1. Introduction
The aim of this analysis is to investigate and understand the factors contributing to road accidents on single carriageway roads, with the objective of identifying opportunities to improve road safety and reduce the incidence of accidents in these environments.

## 2. Business Problem
Client wants to create a Road Accident Dashboard for year 2021 and 2022 so that they can have insight on the below requirement-
  <br />❖ Primary KPI: Total Casualties and Total Accident values for current Year and YoY growth
  <br />❖ Primary KPI’s: Total Casualties by Accident Severity for current Year and YoY growth
  <br />❖ Secondary KPI’s: Total Casualties with respect to vehicle type for Current Year
  <br />❖ Casualties by Road Type for Current year
  <br />❖ Current Year Casualties by Area/Location & by Day/Night
  <br />❖ Total Casualties and Total Accidents by Location

  ## 3. Methodology
->3.1 Dataset Preparation: The Road Accident data is obtained and imported into Power Query for data cleaning and transformation.<br />
<br />3.2 Data Cleaning and Transformation: Using Power Query, the data is cleaned by removing irrelevant columns, filtering out unnecessary data, and handling missing values. Transformation steps are applied to ensure the data is in a suitable format for analysis.<br />
<br />3.3 Dashboard Design: The cleaned dataset is connected to Power BI, where an interactive and visually appealing dashboard is designed. Various visualizations, such as charts, and graphs, are added to present key insights from the accident data.<br />
<br />3.4 Interactive Filters: Filters are implemented in the dashboard to allow users to slice and dice the data based on dimensions like Road Surface and Wheather Condition. This enhances the exploratory capabilities of the dashboard.<br />
<br />3.5 Calculated Measures: Using the DAX formula language, calculated measures are created to derive additional insights from the data.

## 4. Dashboard
![Road_Accident_page-0001](https://github.com/kushmohit07/Road-Accident-Dashboard/assets/144076408/4fe9230f-0446-4299-8704-bbea11df997f)

## 5. Observation
#### 5.1 CY Casualties v/s PY Casualties
In the analysis of road accidents for the current year 2022 compared to the previous year 2021, it has been observed that the number of accidents has decreased. This decline in accidents signifies a positive trend towards enhanced road safety measures and awareness campaigns.

![Road_Accident_page-0001](https://github.com/kushmohit07/Road-Accident-Dashboard/assets/144076408/7f46ce4e-b261-4565-8e27-941a867b283b)

#### 5.2 Casualties by Vehicle Type
Cars and motorcycles consistently emerge as the most commonly involved vehicle types in road accidents. This observation suggests that these vehicles play a significant role in traffic incidents, possibly due to their prevalence on the roads and varying degrees of vulnerability to accidents.

#### 5.3 Casualties by Road Type
Single carriageway roads consistently exhibit a higher incidence of accidents compared to dual carriageways or motorways. This observation suggests that the characteristics and inherent features of single carriageway roads contribute to increased accident risk.

![Road_Accident_page-0002](https://github.com/kushmohit07/Road-Accident-Dashboard/assets/144076408/79e6cc06-37fe-49c2-a97e-35f420b94a43)

## Limitations and challenges.
<b>Limited Interactivity</b>: Depending on the design and functionality of the dashboard, the level of interactivity and drill-down capabilities may be limited, restricting users' ability to explore data and gain deeper insights.

<b>User Expertise</b>: The dashboard assumes that users have a basic understanding of data analysis and interpretation. Users with limited data literacy or domain knowledge may face challenges in effectively utilizing the dashboard.

<b>Challenges</b>: Limited knowledge of DAX language requires learning it for the project, including understanding syntax, complex calculations, optimization and staying updated with DAX's evolving features.
