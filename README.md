# 📊 Developer Survey & Job Market Analysis

### 📁 Project Structure:

project

- **[Data_collection](https://github.com/Damian4nT/Stack_Overflow_survey_analysis/tree/main/Data_collection)**
- **[Data_Wrangling](https://github.com/Damian4nT/Stack_Overflow_survey_analysis/tree/main/Data_wrangling)**
- **[Exploratory_Data_Analysis](https://github.com/Damian4nT/Stack_Overflow_survey_analysis/tree/main/Exploratory_Data_Analysis)**
- **[Data_Visualization](https://github.com/Damian4nT/Stack_Overflow_survey_analysis/tree/main/Data_Visualization)**
- **[Final_Report](https://github.com/Damian4nT/Stack_Overflow_survey_analysis/blob/main/Final_Report_Technologies_and_Demographics.pdf)**
- **README.md**

### 📌 Project Overview

This project analyzes developer survey data alongside job market data to uncover trends in:

- compensation
- job satisfaction
- technology preferences
- experience and demographics

The goal is to simulate a real-world data analysis workflow, combining multiple data sources and applying data cleaning, transformation, and visualization techniques.
 
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
- Collecting job data via API
- Web scraping external datasets
  
### 🧹 Data Cleaning & Preprocessing:
- Removed missing and non-informative values (e.g. "Prefer not to say")
- Converted categorical variables into numerical formats (e.g. age ranges → numeric values)
- Handled missing values using appropriate techniques (dropping or imputing)
- Normalized selected variables for comparison
- Split multi-response fields into individual rows (e.g. languages, databases)
  
### 🔍 Exploratory Data Analysis (EDA):
- Distribution analysis (compensation, age, experience)
- Outlier detection using IQR method
- Group-based aggregation (e.g. median salary by age group)
- Trend analysis across different demographics

### 📊 Data Visualization:
- Bar charts → categorical comparisons 
- Line charts → trends
- Histograms & box plots → distribution and outliers
- Scatter & heatmaps → relationships between variables
  
## 📈 Key Insights:
### Compensation is strongly right-skewed (few high earners significantly impact averages)
<img width="1634" height="701" alt="image" src="https://github.com/user-attachments/assets/effce4ec-963b-4115-9d71-c21136ae5065" />

### Experience positively correlates with salary
<img width="824" height="700" alt="image" src="https://github.com/user-attachments/assets/bd61ad6c-59be-4a38-a037-114c71514e23" />

### There is no correlation between Job satisfaction and compensation
<img width="758" height="714" alt="image" src="https://github.com/user-attachments/assets/58db23df-32e7-46e8-af9c-3915a4c96afb" />

### median compensation is higher in English speaking countries
  <img width="2039" height="855" alt="image" src="https://github.com/user-attachments/assets/2363a95f-2c5d-4896-b6f9-c5f6462599c0" />

### over 90% of respondents have attended university or college
<img width="681" height="373" alt="image" src="https://github.com/user-attachments/assets/58ca62c2-1a80-49c1-b683-77f0f501ae8e" />

### PostgreSQL is the most popular database
<img width="689" height="361" alt="image" src="https://github.com/user-attachments/assets/a23f37f7-aae9-4507-8791-8ee527a82f3e" />


### Data source
https://survey.stackoverflow.co/ (year 2024)

### 💡 Future Improvements:
- Build Power BI dashboard
- Build predictive model (e.g. salary prediction)
