# Coffee Quality Modelling

*This project was completed as part of the [CareerFoundry Data Analytics Program](https://careerfoundry.com/en/courses/become-a-data-analyst/).*


## Overview

This self-directed project explores global coffee quality using open-source data and machine learning principles. It examines how origin, variety, and processing factors influence sensory scores, and applies statistical and clustering techniques to uncover patterns in quality and potential indicators of demand. The analysis covers beans harvested between 2009 and 2018 and investigates which countries produce the highest-quality coffee, whether certain attributes can predict others, and if higher quality correlates with increased demand.

## Key Questions
1. Which countries produce the best coffee?  
2. Can certain measures be used to predict the scores of others?  
3. Is there a higher demand for coffee with better quality scores?


## Tools Used

- **Python** (Jupyter | Anaconda) – Scripting Environment  
- **pandas, numpy, os** – Data Manipulation  
- **matplotlib, seaborn, pylab** – Plotting | Visualisation  
- **scikit-learn, statsmodels** – Machine Learning | Statistical Modelling  
- **folium** – Geospatial Visualisation  
- **Tableau** – Dashboard Design


## Skills Demonstrated

- Script Writing  
- Exploratory Data Analysis | Data Wrangling | Aggregation | Subsetting  
- Linear Regression | Clustering (K-Means) | Model Evaluation  
- Time Series Analysis | Stationarity Testing | Lag Analysis  
- Geospatial Mapping  
- Visualisation | Dashboard Design


## Data Used

This analysis uses a modified version of data originally sourced from the **Coffee Quality Institute**, made available on **Kaggle**.

- [**Coffee Quality Dataset**](https://www.kaggle.com/datasets/adampq/coffee-quality-with-locations-of-origin/data) – Bean origin, variety, altitude, processing method, physical attributes, flavour metrics, and total quality score, with geospatial coordinates for most entries.
    
The Dataset was accessed on 02 November 2024.


## Deliverables

- **Tableau Dashboard** *(link to be added)*


## Takeaways

**Successes** – The project successfully explored coffee quality measures across countries, examined relationships among sensory attributes, and demonstrated that certain quality metrics can be predicted with reasonable accuracy using others. It also served as a practical application of regression and clustering techniques using open-source data.

**Challenges** – The dataset lacked the granularity required to assess consumer demand relative to quality scores. This limited the ability to explore market dynamics and highlighted the importance of defining analytical objectives and data requirements clearly at the start of a project.

**Way Forward** – Future iterations should focus on sourcing a dataset that includes pricing, volumes sold, or export trends to better assess demand. Additionally, experimenting with alternative modelling techniques may improve predictions for less correlated attributes. A revised Tableau dashboard is planned to enhance visual storytelling and consolidate key insights from the notebooks into an interactive format.


## License
This project is licensed under the MIT License.


## Repository Structure

```text
├── notebooks/            # Python Notebooks
├── LICENSE               # Project License
└── README.md             # Project Overview
