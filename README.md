📊 Strava Fitness Analytics Dashboard



A complete end-to-end \*\*fitness analytics project\*\* built using \*\*Python, SQL, and Power BI\*\* to analyze user activity, sleep patterns, calories burned, heart rate trends, BMI indicators, and overall fitness behavior.



This project combines \*\*data cleaning, exploratory data analysis, SQL-based preprocessing, and dashboard development\*\* to transform raw fitness data into meaningful insights and interactive visual storytelling.



\---



📌 Project Overview



The goal of this project is to analyze fitness and health-related data from a Strava-style activity dataset and uncover patterns related to:



\- daily physical activity

\- calorie expenditure

\- sleep duration

\- heart rate behavior

\- BMI and body composition

\- step count and distance relationships

\- overall lifestyle and activity trends



This project follows a complete analytics workflow:



1\. Data collection and consolidation  

2\. Data cleaning and preprocessing  

3\. Exploratory Data Analysis (EDA) using Python  

4\. Data transformation and querying using SQL  

5\. Interactive dashboard creation in Power BI  

6\. Insight generation and visual reporting  



\---



🎯 Objectives



The main objectives of this project are:



\- To analyze user fitness data in a structured and meaningful way  

\- To identify relationships between steps, calories, sleep, heart rate, and BMI  

\- To compare activity intensity levels such as very active, fairly active, lightly active, and sedentary minutes  

\- To build a professional dashboard for easy monitoring of key fitness metrics  

\- To present the analysis in a portfolio-ready format using real tools used in data analytics roles  



\---



🛠️ Tools and Technologies Used



Programming and Analysis

\- Python

\- Pandas

\- NumPy

\- Matplotlib

\- Jupyter Notebook



Database and Querying

\- SQL (MySQL)



Visualization and Reporting

\- Power BI



Version Control and Documentation

\- Git

\- GitHub

\- Markdown



\---



🗂️ Dataset Information



The project uses merged fitness-related data containing information such as:



\- total steps

\- total distance

\- calories burned

\- activity minutes by intensity

\- sleep duration

\- hourly and minute-level activity metrics

\- heart rate

\- BMI, weight, and fat percentage



The cleaned and merged dataset is stored in:



```text

data/StravaFullMergedData.csv



📁 Project Structure



Strava-Fitness-Analytics/

│

├── README.md

├── requirements.txt

├── .gitignore

│

├── data/

│   └── StravaFullMergedData.csv

│

├── notebook/

│   └── Strava\_fitness\_EDA\_final.ipynb

│

├── sql/

│   └── Strava\_Project.sql

│

├── powerbi/

│   └── Strava\_Fitness\_Dashboard.pbix

│

└── images/

&#x20;   ├── dashboard\_main.png

&#x20;   ├── 01\_total\_steps\_distribution.png

&#x20;   ├── 02\_activity\_level\_comparison.png

&#x20;   ├── 04\_steps\_vs\_distance.png

&#x20;   ├── 05\_sleep\_vs\_steps.png

&#x20;   └── 06\_correlation\_heatmap.png



📄 Project Files Description

data/StravaFullMergedData.csv



This file contains the cleaned and merged dataset used for final analysis and visualization.



notebook/Strava\_fitness\_EDA\_final.ipynb



This Jupyter Notebook contains:



data loading



preprocessing



data exploration



statistical summaries



chart generation



trend and relationship analysis



sql/Strava\_Project.sql



This SQL script includes:



table creation



CSV import logic



joins and merges



preprocessing steps



cleaned output preparation



powerbi/Strava\_Fitness\_Dashboard.pbix



This Power BI file contains the final interactive dashboard with filters, KPI cards, and visual reports.



images/



This folder contains exported charts and dashboard screenshots used for presentation and documentation.



📈 Exploratory Data Analysis Highlights



The Python analysis focuses on understanding the distribution and relationship of major fitness indicators.



1️⃣ Distribution of Total Steps



A histogram was used to study the spread of daily steps and understand how user activity varies across days.



Insight:

The step count distribution shows moderate variation, with most records concentrated in a mid-range activity band and a few high-step outliers.



2️⃣ Average Activity Minutes by Level



A bar chart compares average minutes spent in:



Very Active Minutes



Fairly Active Minutes



Lightly Active Minutes



Sedentary Minutes



Insight:

Sedentary minutes are significantly higher than active minutes, indicating that inactive time dominates daily behavior.



3️⃣ Total Steps vs Total Distance



A scatter plot was used to examine the relationship between steps and total distance.



Insight:

There is a strong positive relationship between total steps and total distance, which confirms data consistency and expected real-world activity patterns.



4️⃣ Sleep vs Total Steps



A scatter plot was created to compare sleep duration and total steps.



Insight:

The relationship appears weak or inconsistent, suggesting that higher sleep duration does not always directly translate into increased physical activity.



5️⃣ Correlation Heatmap



A correlation heatmap was generated to identify relationships across numerical features in the merged dataset.



Insight:

Strong positive correlations are observed among activity-related variables such as steps, distance, calories, and intensity-based features.



🧮 SQL Work Performed



The SQL part of the project was used to organize, structure, and prepare the data before analysis and dashboarding.



Key SQL tasks included:



creating tables for multiple raw fitness datasets



importing CSV files into MySQL



cleaning inconsistent values



joining multiple tables into a final merged structure



preparing analysis-ready columns



supporting the final dashboard and EDA workflow



This step demonstrates practical knowledge of handling structured data using relational databases.



📊 Power BI Dashboard Features



The Power BI dashboard provides an interactive view of the user’s fitness profile and trends.



Dashboard includes:



KPI cards for:



BMI



Weight



Fat Percentage



Average Heart Rate



Calories



Total Distance



Total Steps



Sleep Duration



Visuals such as:



Hourly Calories by Steps



Minute Calories, Steps, and Sleep across Days



Average Heart Rate across Time



BMI Category Distribution



Monthly Distribution of Calories



Sleep Duration across Time



Interactive slicers for:



User ID



Date



Dashboard value



Although this is a fitness dataset, the dashboard is designed like a professional analytics solution where users can:



monitor KPIs



compare behavioral metrics



identify trends over time



observe health-related patterns interactively


🖼️ Dashboard Preview



📸 Sample Visual Outputs

Distribution of Total Steps



Average Activity Minutes by Level



Total Steps vs Total Distance



Sleep vs Total Steps



Correlation Heatmap



💡 Key Insights



Some of the important findings from the project are:



Higher step counts are strongly associated with greater total distance



Sedentary time is much higher than active time across the dataset



Activity-based metrics such as calories, steps, and intensity tend to move together



Sleep duration does not show a strong direct relationship with total steps



KPI-based health tracking can be effectively monitored through interactive dashboarding



🚀 Skills Demonstrated



This project demonstrates practical skills in:



data cleaning



data preprocessing



exploratory data analysis



data visualization



SQL querying



dashboard development



insight generation



GitHub project documentation



▶️ How to Run This Project

1\. Clone the repository

git clone https://github.com/Sahid-22/strava-fitness-analytics.git

cd strava-fitness-analytics

2\. Install required Python libraries

pip install -r requirements.txt

3\. Open the notebook



Open the Jupyter Notebook file from the notebook/ folder and run the cells.



4\. Open the Power BI dashboard



Open the .pbix file from the powerbi/ folder using Microsoft Power BI Desktop.



5\. Run SQL script



Execute the SQL script in MySQL to recreate the data structure and preprocessing workflow if required.



🔮 Future Improvements



Possible future enhancements for this project include:



adding more advanced KPI calculations



improving dashboard theme consistency



including predictive analysis for calories or activity behavior



building a web-based dashboard version



adding user-level comparison or segmentation analysis



👨‍💻 Author



Md Sahid Raza

B.Tech in Information Technology

Data Analytics Enthusiast



Gmail: \[ sahidraza2000@gmail.com ]

LinkedIn: \[ https://www.linkedin.com/in/md-sahid-raza-2215ssr ]

&#x20;



✅ Conclusion



This project showcases a complete data analytics workflow using industry-relevant tools. It demonstrates the ability to collect, clean, analyze, and visualize data in a way that is both technically sound and presentation-ready.



It is a strong portfolio project for roles related to:



Data Analyst



Business Analyst



Reporting Analyst



Power BI Developer



Junior Data Scientist

