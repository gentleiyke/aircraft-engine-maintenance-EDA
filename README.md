# Aircraft Engine Maintenance EDA
This repository contains an Exploratory Data Analysis project focused on aircraft engine maintenance data. It includes key operational parameters like engine temperature, pressure, rotational speed, and health indicators, along with failure data. The goal of the analysis is to identify patterns, relationships, and insights that can guide predictive maintenance and improve the reliability of aircraft engines.

#### Objective
* Understand the relationships between engine parameters (temperature, pressure, speed) and engine health.
* Identify potential indicators of engine failure.
* Lay the groundwork for predictive maintenance models that can prevent engine failures.

#### Dataset
The dataset consists of 720 observations of engine performance recorded at various times, with the following features:
* Engine_ID: Unique identifier for each engine.
* Timestamp: Time-based data collection for each engine's parameters.
* Temperature: Engine temperature in degrees Celsius (°C).
* Pressure: Engine pressure readings (kPa).
* Rotational_Speed: Speed of engine rotation (RPM).
* Engine_Health: Health index of the engine (0 to 1 scale).
* Engine_Failure: Binary indicator (0: No Failure, 1: Failure).

Temperature and Pressure variables contain missing values, which are addressed during the analysis.

#### Contents of the Repository
* Aircraft_engine_maintenance_EDA_Analysis.ipynb: A Jupyter Notebook performing in-depth Exploratory Data Analysis on the dataset.
  ##### Key Analyses:
  * Data cleaning and handling missing values.
  * Descriptive statistics and distribution analysis.
  * Univariate Analysis of engine parameters distribution.
  * Bivariate analysis of engine parameters versus engine failures.
  * Correlation heatmap to explore interactions between multiple variables.
  * Feature Engineering to capture patterns, trend and interaction terms between engine parameters.
  * Visualising relationships between engine health, temperature, and failure rates.

* aircraft_engine_maintenance.csv: Dataset used for analysis.

#### Key Insights
* There is a strong correlation between engine temperature and engine health.
* Engines with high rotational speed tend to have better engine health.
* Visualisations show clear patterns that can guide predictive maintenance strategies.

#### Future Work
* Extend the analysis to include machine learning models for predictive maintenance.
* Explore other failure predictors such as vibrations and fuel consumption.

#### How to Run
1. Clone the repository:

  ```bash 
  git clone https://github.com/your-repo/aircraft-engine-maintenance-EDA.git
  ```
2. Install the required dependencies:

  ```bash
  pip install -r requirements.txt
  ```
3. Open the Jupyter notebook:
  ```bash
  jupyter notebook Aircraft_engine_maintenance_EDA_Analysis.ipynb
  ```
#### Collaborations:

You can reach out to me using my contact below for job roles, gigs and collaborations.

#### Contact:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gentleiyke/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ikemefulaoriaku@gmail.com)
