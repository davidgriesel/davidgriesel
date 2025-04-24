# Flu Risk Forecasting

*This project was completed as part of the [CareerFoundry Data Analytics Program](https://careerfoundry.com/en/courses/become-a-data-analyst/).*

## Overview

A medical staffing agency that supplies temporary personnel to clinics and hospitals across the United States is preparing for the upcoming 2018/19 influenza season. This analysis supports planning efforts by identifying high-risk population groups using age, examining seasonal trends, and developing a state-level risk profile to help determine when, where, and how many staff may be needed.

## Key Questions
1. Which age groups are most affected by influenza?
2. Is there a relationship between population size and influenza-related deaths?
3. When does influenza season typically start and end?
4. How does the severity of influenza vary from year to year?
5. Which states are most at risk?
6. Based on risk, when, where, and how many staff should be deployed?

## Tools Used 

- **Excel** - Data Processing | Analysis
- **Tableau** - Visual Exploration & Analysis | Forecasting | Storytelling

## Skills Demonstrated

- Data Exploration | Description | Profiling | Quality & Integrity Assessment | Cleaning | Transformation
- Descriptive Statistics | Trend Analysis | Seasonal Forecasting | Statistical Analysis | Hypothesis Testing
- Deriving Insights | Data Visualisation | Storytelling

## Data Used
This analysis uses publicly available data sourced from the [**Centres for Disease Control and Prevention (CDC)**](https://wonder.cdc.gov/ucd-icd10.html) and the [**US Census Bureau**](https://data.census.gov) that cover the period 2009 to 2017. The data was provided by [**CareerFoundry**](https://careerfoundry.com/en/courses/become-a-data-analyst/) as part of their Data Analytics Course.

- [**Influenza-related deaths**](https://coach-courses-us.s3.amazonaws.com/public/courses/da_program/CDC_Influenza_Deaths_edited.xlsx) - Number of deaths by location, time, and age. (CDC)
- [**Population**](https://coach-courses-us.s3.amazonaws.com/public/courses/data-immersion/A1-A2_Influenza_Project/Census_Population_transformed_202101.csv) - Number of people by location, time, age, and gender. (US Census Bureau)

## Deliverables
- [**Interactive Tableau Storyboard**](https://public.tableau.com/views/MedicalStaffingPlan_17430147849920/Story1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Further Reading
- [**Detailled Case Study**](https://davidgriesel.com/data-analysis-informing-medical-staffing-plan/)

## Takeaways
**Successes** - The project delivered actionable insights into the spatial distribution of vulnerable populations, enabling the creation of a risk profile to guide regional staff allocations. It also enhanced understanding of influenza seasonality, supporting the strategic timing of deployments to meet anticipated healthcare demands.

**Challenges** - The available data lacked sufficient detail to account for all known factors in the analysis. The suppression of all records for children under 5 limited the ability to assess risk in this age group, highlighting how data privacy laws can restrict public health analyses when key demographic groups are excluded.
Challenges – The available data lacked the granularity needed to consider all known risk factors. In particular, the suppression of records for children under 5 limited risk assessment for this group, illustrating how data privacy laws can constrain public health analyses when key demographics are excluded.

**Way Forward** - To evaluate the proposed deployment strategy, its impact should be monitored during the upcoming influenza season. Tracking performance indicators, such as staffing efficiency, response times, and patient outcomes across risk tiers, will help evaluate resource allocation and guide improvements.
Incorporating data on chronic health conditions and vaccination rates among seniors could further strengthen the analysis by offering a more comprehensive view of factors driving influenza outcomes. This would support more targeted and effective planning in future seasons.


## License
This project is licensed under the MIT License.


## Repository Structure

```text
├── data/                 # Cleaned Dataset
├── workbooks/            # Excel Workbooks
├── LICENSE               # Project License (MIT)
└── README.md             # Project Overview