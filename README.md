Road Accidents Analysis
=======================

Overview
--------
The Road Accidents Analysis project aims to provide insights into road accidents reported over multiple years. By analyzing a dataset containing detailed information on various attributes related to accident status, vehicle and casualty references, demographics, and severity of casualties, the project seeks to identify trends, patterns, and factors contributing to road accidents. This analysis can help in implementing effective safety measures to reduce casualties and enhance road safety.

Dataset Description
-------------------
The dataset encompasses the following columns:
- Status: The status of the accident (e.g., reported, under investigation).
- Accident_Index: A unique identifier for each reported accident.
- Accident_Year: The year in which the accident occurred.
- Vehicle_Reference: A reference number for the involved vehicle in the accident.
- Casualty_Reference: A reference number for the casualty involved in the accident.
- Casualty_Class: Indicates the class of the casualty (e.g., driver, passenger, pedestrian).
- Sex_of_Casualty: The gender of the casualty (male or female).
- Age_of_Casualty: The age of the casualty.
- Casualty_Severity: The severity of the casualty's injuries (e.g., fatal, serious, slight).
- Pedestrian_Location: The location of the pedestrian at the time of the accident.
- Pedestrian_Movement: The movement of the pedestrian during the accident.
- Car_Passenger: Indicates whether the casualty was a car passenger at the time of the accident (yes or no).
- Bus_or_Coach_Passenger: Indicates whether the casualty was a bus or coach passenger (yes or no).
- Pedestrian_Road_Maintenance_Worker: Indicates whether the casualty was a road maintenance worker (yes or no).
- Casualty_Type: The type of casualty (e.g., driver/rider, passenger, pedestrian).
- Casualty_Home_Area_Type: The type of area in which the casualty resides (e.g., urban, rural).
- Casualty_IMD_Decile: The IMD decile of the area where the casualty resides (a measure of deprivation).
- LSOA_of_Casualty: The Lower Layer Super Output Area (LSOA) associated with the casualty's location.

Project Structure
-----------------

### Data Collection
The dataset utilized in this project was obtained from the UK government's official statistics on road traffic accidents. It offers a comprehensive view of road accidents reported over several years, containing details on accident status, vehicle and casualty references, demographics, and casualty severity.

### Data Preprocessing
Preprocessing steps were implemented to enhance data quality and prepare it for analysis and modeling. Tasks included handling missing values, eliminating irrelevant and highly correlated columns, and standardizing numerical variables using standard scaling.

### Exploratory Data Analysis (EDA)
EDA involved descriptive statistics, visualizations, and correlation analysis to extract insights from the dataset. Key explorations included casualty severity counts, distributions of casualty class, gender, and age, as well as factors such as pedestrian location, movement, and their relationships with casualty severity.

### Model Development
A logistic regression, decision tree and random forest models were employed to predict casualty severity based on various factors. Model evaluation encompassed metrics like accuracy, Precision, recall and f1.

### Feature Importance Analysis
Feature importance analysis was conducted on the logistic regression model to identify significant predictors of casualty severity. This analysis shed light on the factors exerting the most influence on predicting casualty severity levels.

### Results and Discussion
The results highlighted significant findings from the analysis, indicating correlations between different factors and casualty severity. For instance, casualty class, age, and area type were identified as correlated with casualty severity. Recommendations for accident reduction and road safety enhancement were proposed based on the insights derived from the analysis.


Getting Started
---------------

Clone the repository:
git clone https://github.com/sama/road-accidents-analysis.git
pip install -r requirements.txt

Follow the Notebook:
The main.ipynb notebook contains sections for data exploration, preprocessing, exploratory data analysis (EDA), and machine learning modeling. Follow the instructions within the notebook to analyze the dataset, preprocess the data, explore relationships, and build predictive models.