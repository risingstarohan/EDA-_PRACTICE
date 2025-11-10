**Zomato Data Analysis: Unlocking Global Restaurant Insights**
A comprehensive data science project focused on Exploratory Data Analysis (EDA) and Feature Engineering on the Zomato restaurant dataset. This analysis aims to extract actionable, data-driven insights into global restaurant trends, pricing strategies, rating dynamics, and geographical service availability.

**Key Analytical Findings**
The EDA process uncovered several critical patterns and geographical distinctions within the dataset:

_Geographical Dominance:_ The dataset is heavily skewed towards India (Country Code 1), which accounts for the vast majority of all restaurant records. This provides critical context for any global inference.

_Rating Dynamics:_

A large segment of the dataset (over 20%) consists of restaurants that are 'Not Rated' (rating of 0.0), indicating a need for careful handling of the Aggregate rating feature.

Most active ratings fall into the Average category (2.5 - 3.4 range), suggesting a typical distribution of quality.

_Online Service Segregation:_ The feature Has Online delivery is exclusively operational in only two countries (primarily India and the UAE), highlighting a major regional gap in Zomato's service infrastructure.

_Top City Concentration:_ The highest density of restaurants is concentrated in a few major metropolitan areas, led by the National Capital Region (NCR) cities (New Delhi, Gurgaon, Noida).

_Currency Mapping:_ Successful integration of the Country-Code reference file to accurately map and interpret the diverse currencies and Average Cost for two across 15+ countries.

**📂 Repository Structure**

File Name,Description
1-eda-feature-engineering.ipynb,"The core Jupyter Notebook containing all code for data cleaning, merging, extensive Exploratory Data Analysis (EDA), visualization, and feature engineering steps."
zomato.csv,"The main raw dataset containing 21 columns of restaurant data (ID, name, location, ratings, votes, etc.)."
Country-Code.xlsx - Sheet1.csv,A crucial reference CSV used to map the numerical Country Code to the descriptive Country name.

**💻 Technology Stack**
The project is built entirely in a Python 3 environment utilizing the following data science libraries:

Python 3.x

pandas: The fundamental tool for data manipulation and analysis.

numpy: Used for efficient numerical operations and array processing.

seaborn & matplotlib: Employed for creating high-quality statistical and informative visualizations (scatter plots, bar charts, heatmaps).

**🚀 Installation and Execution**
To reproduce this analysis locally, please follow these steps:

_Clone the Repository:_
git clone <repository-url>
cd <repository-name>

_Install Dependencies:_ Ensure you have the necessary libraries installed. It is recommended to use a virtual environment.
pip install pandas numpy matplotlib seaborn jupyter

_Run the Analysis:_ Launch the Jupyter environment and open the main analysis notebook.

jupyter notebook

Open 1-eda-feature-engineering.ipynb and run all cells sequentially to view the data processing pipeline, visualizations, and all derived insights.
To reproduce this analysis locally, please follow these steps:

Clone the Repository:
