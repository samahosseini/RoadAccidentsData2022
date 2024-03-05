Road Accidents Analysis
Overview
The Road Accidents Analysis project aims to provide insights into road accidents reported over multiple years. The dataset used in this project contains detailed information on various attributes related to accident status, vehicle and casualty references, demographics, and severity of casualties. By analyzing this dataset, we can identify trends, patterns, and factors contributing to road accidents, which can help in implementing effective safety measures to reduce casualties and enhance road safety.

Dataset Description
The dataset encompasses the following columns:

Status: The status of the accident (e.g., reported, under investigation).
Accident_Index: A unique identifier for each reported accident.
Accident_Year: The year in which the accident occurred.
Vehicle_Reference: A reference number for the involved vehicle in the accident.
Casualty_Reference: A reference number for the casualty involved in the accident.
Casualty_Class: Indicates the class of the casualty (e.g., driver, passenger, pedestrian).
Sex_of_Casualty: The gender of the casualty (male or female).
Age_of_Casualty: The age of the casualty.
Casualty_Severity: The severity of the casualty's injuries (e.g., fatal, serious, slight).
Pedestrian_Location: The location of the pedestrian at the time of the accident.
Pedestrian_Movement: The movement of the pedestrian during the accident.
Car_Passenger: Indicates whether the casualty was a car passenger at the time of the accident (yes or no).
Bus_or_Coach_Passenger: Indicates whether the casualty was a bus or coach passenger (yes or no).
Pedestrian_Road_Maintenance_Worker: Indicates whether the casualty was a road maintenance worker (yes or no).
Casualty_Type: The type of casualty (e.g., driver/rider, passenger, pedestrian).
Casualty_Home_Area_Type: The type of area in which the casualty resides (e.g., urban, rural).
Casualty_IMD_Decile: The IMD decile of the area where the casualty resides (a measure of deprivation).
LSOA_of_Casualty: The Lower Layer Super Output Area (LSOA) associated with the casualty's location.
Project Structure
data/: (https://www.kaggle.com/datasets/juhibhojani/road-accidents-data-2022?resource=download)
notebooks/: Jupyter notebooks for data analysis and modeling.
src/: Source code files for data preprocessing, modeling, and evaluation.
README.md: Overview and instructions for the project.
Getting Started
Clone the repository:
git clone https://github.com/samahosseini/road-accidents-analysis.git
pip install -r requirements.txt

Follow the Notebook:
The main.ipynb notebook contains sections for data exploration, preprocessing, exploratory data analysis (EDA), and machine learning modeling. Follow the instructions within the notebook to analyze the dataset, preprocess the data, explore relationships, and build predictive models.
