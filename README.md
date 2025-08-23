# Teen Phone Addiction - Exploratory Data Analysis

## Overview
This project explores **teen phone addiction** patterns using an exploratory data analysis (EDA) approach.  
The analysis focuses on identifying trends, correlations, and behavioral patterns in smartphone usage among teenagers, and how these habits may affect sleep, academic performance, and overall phone dependency.

## Dataset
**Source:** [Teen_Phone_Addiction_Dataset](https://www.kaggle.com/datasets/khushikyad001/teen-phone-addiction-and-lifestyle-survey)


**File:** `teen_phone_addiction_dataset.csv`

**Key Features:**
- **Demographics:** Age, Gender, School Grade
- **Usage Metrics:** Daily Usage Hours, Phone Checks Per Day, Apps Used Daily, Screen Time Before Bed
- **Behavioral Metrics:** Phone Usage Purpose, Time on Gaming, Time on Education
- **Outcome Variables:** Addiction Level, Academic Performance, Sleep Hours

## Objectives
- Understand demographic patterns in phone usage
- Identify correlations between smartphone habits and addiction level
- Explore relationships between phone usage and academic performance/sleep
- Visualize patterns for clearer insights

## Methodology
1. **Data Loading & Inspection**
   - Checked column types, missing values, and general structure
2. **Descriptive Statistics**
   - Summary statistics for numeric and categorical variables
3. **Data Visualization**
   - Scatterplots, line plots, bar charts, boxplots, histograms, and heatmaps
4. **Correlation Analysis**
   - Identified strong and moderate relationships between variables

## Visualizations
### 1. Scatterplot – Daily Usage Hours vs Academic Performance
- Differentiated by gender to observe trends.
- Helps identify whether higher daily usage correlates with performance drops.

### 2. Lineplot – Average Sleep Hours by Age
- Shows how average sleep changes across ages.
- Detects possible sleep deprivation trends with age.

### 3. Barplot – Average Addiction Level by Phone Usage Purpose
- Compares addiction levels across usage purposes (social media, gaming, etc.).

### 4. Boxplot – Screen Time Before Bed by Gender
- Highlights distribution differences between genders.

### 5. Histogram – Distribution of Apps Used Daily
- Visualizes how many apps teens use on average.

### 6. Correlation Heatmap
- Displays relationships between numeric variables.
- **Key Findings:**
  - Addiction Level strongly correlated with Daily Usage Hours (0.60).
  - Moderate positive correlations with Phone Checks Per Day, Apps Used Daily, and Screen Time Before Bed (~0.31–0.32).
  - Time on Gaming negatively correlated with Academic Performance (-0.22).
  - Time on Education positively correlated with Academic Performance (0.22).

### 7. Regression Plots
- **Daily Usage Hours vs Addiction Level**
- **Phone Checks Per Day vs Addiction Level**
- **Apps Used Daily vs Addiction Level**
- All three show positive trends between usage and addiction.

## Key Insights
- **Higher daily phone usage is strongly linked to increased addiction levels.**
- Frequent app usage and phone checks contribute moderately to phone dependence.
- Gaming time may reduce academic performance, while educational phone use has a positive effect.
- Teens spending more time on phones before bed may also show higher addiction levels.

## Conclusion
This EDA highlights clear behavioral patterns connecting **smartphone usage intensity** with **addiction levels** among teenagers.  
Findings can be valuable for parents, educators, and policymakers in developing balanced technology use strategies to improve sleep quality and academic outcomes.

## Tech Stack
- **Language:** Python 3
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

## Author  
Shaik Mohammed Kaif

📫 [Mail](mailto:kaifshaik1817@gmail.com) |
🔗 [LinkedIn](https://www.linkedin.com/in/mohammed-kaif-shaik)
