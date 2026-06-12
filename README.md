# Job Salary Prediction Using Machine Learning

## Project Overview

This project explores the factors that influence employee compensation using a dataset of 250,000 job records. The dataset contains information on job titles, experience levels, education, skills, industries, company characteristics, certifications, work arrangements, and salaries.

The objective was to analyze salary trends, identify key compensation drivers, and develop a machine learning model capable of predicting salaries for unseen job profiles.

## Business Problem

Compensation decisions are influenced by multiple factors, making salary estimation a complex task for both employers and job seekers. Understanding these factors can support:

* Salary benchmarking
* Workforce planning
* Compensation analysis
* Career decision making
* Talent acquisition strategies

This project applies data analysis and machine learning techniques to uncover salary patterns and generate predictive insights.

## Dataset Features

The dataset includes:

* Job Title
* Experience Level
* Education Level
* Skills Count
* Industry
* Location
* Company Size
* Remote Work Type
* Certifications
* Salary

## Project Workflow

### 1. Data Preparation

* Data cleaning and validation
* Handling missing values
* Feature engineering
* Data transformation and encoding

### 2. Exploratory Data Analysis (EDA)

Explored relationships between salary and various professional attributes to identify trends, correlations, and salary drivers.

### 3. Machine Learning

A Random Forest Regressor was trained to predict salaries based on the available features.

Model objectives:

* Learn salary patterns from historical data
* Predict salaries for new employee profiles
* Evaluate predictive performance using regression metrics

## Exploratory Data Analysis (EDA) Findings

The exploratory analysis focused on identifying the key factors that influence salary and understanding the relationships between compensation and professional attributes.

### Does Experience Increase Salary?

### Which Job Titles Pay the Most?

### Do More Skills Lead to Higher Pay?

### Does Industry Affect Salary?

### Which Industries Pay the Most and Least?

### Are Certifications Important?

### Does Location Influence Salary?

### Key Takeaway

The analysis revealed that **Job Title, Location, and Experience** were the strongest predictors of salary, while skills, certifications, and industry also contributed to compensation differences but to a lesser extent.


## Key Insights

### Experience Matters

Salary generally increases with experience, showing a moderate positive relationship between years of experience and compensation.

### Job Role Is a Major Salary Driver

Highly specialized technical roles consistently showed higher salary ranges compared to general business and entry-level technical positions.

### Skills and Certifications Add Value

Professionals with broader skill sets and additional certifications tended to earn higher salaries across multiple job categories.

### Location Creates Significant Salary Differences

Geographic location emerged as one of the strongest determinants of salary variation, highlighting differences in regional labor markets.

### Industry Has a Smaller Impact

Compared to factors such as role, experience, and location, industry showed relatively limited influence on salary levels within this dataset.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Machine Learning Model

**Model:** Random Forest Regressor

The model was trained to estimate salary based on professional and organizational characteristics. By learning patterns from historical salary data, it can generate salary predictions for new profiles while capturing complex relationships between variables.

## Results

The model demonstrated strong predictive performance and successfully identified the most influential factors affecting salary outcomes.

Key predictors included:

* Job Title
* Location
* Experience Level
* Skills
* Certifications

## Conclusion

This project demonstrates how machine learning can be applied to workforce and compensation data to uncover salary patterns and generate reliable salary estimates. Beyond prediction, the analysis provides insights into the factors that shape compensation across industries, locations, and career stages.

