# 📊 Developer Survey & Job Market Analysis

### 📌 Project Overview

This project analyzes developer survey data alongside job market data to identify key factors influencing compensation, technology trends, and workforce characteristics.

The analysis combines multiple data sources (~65k records, 100+ variables) and follows a full data analysis workflow: data collection, cleaning, transformation, analysis, and visualization.

The goal of the project is to demonstrate how data can be used to support decision-making in areas such as hiring, salary benchmarking, and technology selection.

### 💼 Business Value
- Identified key drivers of developer compensation (experience, location)
- Highlighted lack of correlation between salary and job satisfaction
- Provided insights into technology trends and market demand
- Demonstrated how data can support data-driven decision making

### ⚡ Technical Highlights
- Processing and analyzing large dataset (~65k records, 100+ variables)
- Transforming multi-value fields into analyzable format
- Handling missing data and detecting outliers (IQR method)
- Performing aggregations and trend analysis
- Building visualizations to effectively communicate insights
 
### 🎯 Objectives:
- Identify key factors influencing developer compensation
- Analyze popularity of programming languages, databases, and tools
- Compare trends across countries and employment types

### 🛠️ Tools & Technologies:
- Python (Pandas, NumPy, Matplotlib & Seaborn)
- SQL (SQLite) in labs: [16](https://github.com/Damian4nT/Stack_Overflow_survey_analysis/blob/main/Data_Visualization/16_Data_Visualization.ipynb), [17](https://github.com/Damian4nT/Stack_Overflow_survey_analysis/blob/main/Data_Visualization/17_Histograms.ipynb), [18](https://github.com/Damian4nT/Stack_Overflow_survey_analysis/blob/main/Data_Visualization/18_Box_Plot.ipynb)
- Jupyter Notebook

### 📂 Data Sources:
- Stack Overflow Developer Survey 2024 (CSV)
- Naukri.com job postings (API, JSON)
- Programming Languages dataset (Web Scraping)
  
### ⚙️ Data Collection Methods:
- Loading structured data from CSV files
- Web scraping external datasets in lab: [2](https://github.com/Damian4nT/Stack_Overflow_survey_analysis/blob/main/Data_collection/Web%20Scraping/Web-Scraping-Lab.ipynb)
- Collecting job data via API in lab: [1](https://github.com/Damian4nT/Stack_Overflow_survey_analysis/blob/main/Data_collection/Collecting_data_using_API/Collecting_job_data_using_APIs-Lab.ipynb)

### 🧹 Data Cleaning & Transformation:
- Handling missing data using filtering and imputation techniques
- Detecting and removing outliers using IQR method
- Standardizing inconsistent data formats  
- Converting categorical variables into numerical values
- Splitting multi-response fields into structured format
- Normalizing selected variables for comparison
  
### 🔍 Exploratory Data Analysis (EDA):
- Analyzed salary distribution (strong right-skewed distribution)
- Evaluated relationship between experience and compensation
- Assessed correlation between job satisfaction and salary
- Performed group-based aggregation (e.g. median salary by country and experience)
- Compared trends across demographics and employment types
  
## 📈 Key Insights:
### Compensation is strongly right-skewed 
High salaries are driven by a small group of top earners
<img width="1634" height="701" alt="image" src="https://github.com/user-attachments/assets/effce4ec-963b-4115-9d71-c21136ae5065" />

### Experience positively correlates with salary
More experienced developers tend to earn significantly higher salaries
<img width="824" height="700" alt="image" src="https://github.com/user-attachments/assets/bd61ad6c-59be-4a38-a037-114c71514e23" />

### There is no correlation between Job satisfaction and compensation
Higher salary does not necessarily lead to higher job satisfaction
<img width="758" height="714" alt="image" src="https://github.com/user-attachments/assets/58db23df-32e7-46e8-af9c-3915a4c96afb" />

### median compensation is higher in English speaking countries
Countries with English as primary language show higher median salaries
  <img width="2039" height="855" alt="image" src="https://github.com/user-attachments/assets/2363a95f-2c5d-4896-b6f9-c5f6462599c0" />

### over 90% of respondents have attended university or college
Most developers have attended university or college
<img width="681" height="373" alt="image" src="https://github.com/user-attachments/assets/58ca62c2-1a80-49c1-b683-77f0f501ae8e" />

### PostgreSQL is the most popular database
Indicates strong industry adoption of relational database systems
<img width="854" height="457" alt="image" src="https://github.com/user-attachments/assets/2f84768b-edb1-4553-adf6-c50d1d27e3fb" />

### 📁 Project Structure:

project

- **[Data_collection](https://github.com/Damian4nT/Stack_Overflow_survey_analysis/tree/main/Data_collection)**
- **[Data_Wrangling](https://github.com/Damian4nT/Stack_Overflow_survey_analysis/tree/main/Data_wrangling)**
- **[Exploratory_Data_Analysis](https://github.com/Damian4nT/Stack_Overflow_survey_analysis/tree/main/Exploratory_Data_Analysis)**
- **[Data_Visualization](https://github.com/Damian4nT/Stack_Overflow_survey_analysis/tree/main/Data_Visualization)**
- **[Final_Report](https://github.com/Damian4nT/Stack_Overflow_survey_analysis/blob/main/Final_Report_Technologies_and_Demographics.pdf)**
- **README.md**

### Data source
https://survey.stackoverflow.co/ (year 2024)

### 💡 Future Improvements:
- Build Power BI dashboard
- Build predictive model (e.g. salary prediction)
