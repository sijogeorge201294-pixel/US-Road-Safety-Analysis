# US Road Safety and Accident Severity Analysis

### Project Overview

This project presents a comprehensive Exploratory Data Analysis (EDA) of traffic accident data in the United States. The goal is to identify key factors that influence accident severity and frequency. By cleaning raw data and using statistical visualisations, this study provides insights into how weather, road conditions, and driver behaviour impact road safety.

### Dataset Source - https://www.kaggle.com/datasets/farshidbahrami021/road-accident-dataset/data

### Objectives
The primary goals of this analysis include:
Identifying the major factors that lead to road accidents.

Understanding the effect of weather and road conditions on accident severity.

Determining which age groups are involved in the most accidents.

Analysing the relationship between speed limits and actual vehicle speeds.

Finding the peak times for accident occurrences.

### Dataset Information
The data for this project was sourced from the Road Accident Dataset on Kaggle. It contains 1,610 entries across 23 columns, covering details such as location, weather, light conditions, and driver demographics.

### Tools and Technologies
Python: The core programming language used for analysis.

Pandas: For data manipulation and structural analysis.

Matplotlib: For creating static and interactive charts.

Seaborn: For advanced statistical visualisations.

### Data Pre-processing
To ensure accuracy, the following steps were taken:

Data Cleaning: Inconsistent values in columns like Light Conditions and Road Type were standardised for better readability.

Missing Value Treatment: Null values in numerical columns were filled using median values, while categorical missing data was handled using the mode.

Feature Engineering: New columns were created for the exact hour of the accident and the difference between vehicle speed and the speed limit.

Outlier Detection: The Interquartile Range (IQR) method was used to verify data distribution, confirming no extreme outliers hindered the analysis.


### Key Insights
Weather Impact: Rainy conditions are a significant factor, accounting for the highest number of accidents (462 incidents).

Vehicle Types: Trucks and motorcycles are involved in more accidents than other vehicle types.

Driver Demographics: Adult and senior drivers are involved in over 50% of the recorded accidents.

Speeding Behaviour: Teenagers were the only age group found to consistently exceed the permitted speed limits.

Dangerous Hotspots: Intersections were identified as the most frequent locations for collisions.

Environmental Risks: The combination of rain and night time resulted in the highest average number of casualties per accident.

### Visualizations
The analysis includes several key charts:

Vehicle Speed vs. Speed Limit: A scatter plot highlighting overspeeding trends.

Accidents by Day of the Week: A count plot showing frequency across different days.

Weather and Light Analysis: Comparative charts showing the risk levels of various environmental factors.

### Strategic Recommendations
Based on the data findings, the following actions are recommended to improve road safety:

Safety Awareness Programs: Conduct awareness campaigns for drivers, especially teenagers, regarding the dangers of overspeeding and weather related risks.

Better Road Lighting: Improve lighting and add reflective road signs in rural areas and highways to reduce night time accidents.

Emergency Services Improvement: Place more ambulance services in areas far from hospitals to reduce response times and save lives.

Safer Intersections: Upgrade dangerous intersections with better signals or convert them into roundabouts to reduce collision frequency.

Warning Signs: Increase the number of warning boards near accident hotspots to inform drivers of the total accidents and deaths in those specific areas.

Conclusion
This analysis demonstrates that weather and specific road locations like intersections play a vital role in road safety. Targeted improvements in lighting and stricter speed monitoring for younger drivers could potentially reduce the severity and frequency of accidents.
