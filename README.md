# CPSC-Assignment-2-Part-2
Titanic Survival Analysis
Project Overview
This project performs an Exploratory Data Analysis (EDA) on the Titanic dataset from Kaggle. The goal is to investigate factors that influenced passenger survival and evaluate 3 hypotheses using statistical analysis and data visualization.


Objectives
The primary objective of this project is to analyze passenger characteristics and identify factors associated with survival aboard the Titanic.

The following hypotheses were investigated:

Survival rate is associated with passenger class.
Survival rate is associated with gender.
Survival rate is associated with age.

Dataset
Source: Kaggle Titanic Dataset

Project Structure
Titanic-Survival-Analysis/ │

├── data/ 

│ └── titanic.csv │ 

├── src/ 

│ └── titanic_analysis.ipynb │ 

├── docs/ 

├── results/ 

│ └── Titanic_Summary_Report.pdf │ 

│ └──survival_by_class.png │ 

│ └──survival_by_gender.png │ 

│ └──survival_by_age.png 

├── README.md



Methodology
1. Data Cleaning
-Imported the dataset into Python using Pandas.
- Inspected data types and missing values.
- Handled missing values where necessary.
- Generated summary statistics.
    
2. Exploratory Data Analysis (EDA)
- Examined variable distributions.
- Calculated survival rates across different groups.
- Created visualizations to identify trends and patterns

3. Hypothesis Testing
  
   Hypothesis 1 **Passenger class is associated with survival.** 
    -Compared survival rates across First, Second, and Third Class passengers. -
   - Visualized results using bar charts.

   Hypothesis 2 **Gender is associated with survival.** 
   - Compared survival rates between male and female passengers. -
   - Used bar charts to illustrate differences.

   Hypothesis 3 **Age is associated with survival.** 
   - Examined the age distribution of survivors and non-survivors. 
   - Used histograms and boxplots to identify trends.

   ## Tools and Technologies
   Python
   Jupyter Notebook
   andas
   NumPy
   Matplotlib


    ## Results Summary
   The analysis revealed several important relationships between passenger characteristics and survival outcomes: -
   Passenger class influenced survival rates, with higher-class passengers generally experiencing greater survival rates. -
   Gender showed a strong relationship with survival, with female passengers surviving at higher rates. -
   Age demonstrated varying survival patterns between different age groups. Detailed findings, visualizations.

   Conclusions are provided in the final report located in the `results` folder.
