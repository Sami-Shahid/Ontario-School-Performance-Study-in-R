# Ontario School Performance Study 📊

This project explores academic performance in Ontario public schools using data on socioeconomic and demographic factors. It investigates how variables such as parental education, income level, and special education services impact Grade 3 and Grade 6 student outcomes.

## 🔍 Objective

To analyze and visualize key factors influencing student performance, and to build statistical models that help understand disparities in educational outcomes.

## 🗂️ Dataset

- **Source:** https://data.ontario.ca/dataset/school-information-and-student-demographics
- **Contents:** Includes information about school enrollment, Grade 3 & Grade 6 average scores, parental education levels, income, special education services, and language background.

## 📌 Key Questions

- How does enrollment size relate to academic outcomes?
- What is the impact of socioeconomic status on Grade 6 performance?
- Do special education services correlate with school achievement?
- Can we predict Grade 6 scores using demographic indicators?

## 🧠 Methods Used

- Data Wrangling (dplyr, tidyr)
- Data Visualization (ggplot2)
- Statistical Summaries and Quartile Analysis
- Linear and Polynomial Regression
- Bootstrapping and Hypothesis Testing
- Cross-Validated Predictive Modeling

## 📈 Visualizations

A few example plots included in the analysis:

- **Scatterplot:** Grade 6 Score vs % of Parents Without Higher Education  
- **Regression:** Grade Avg vs % Special Education (Cubic Fit)  
- **Actual vs Predicted:** 10-Fold Cross-Validation Results

## 📊 Results

- Schools with higher parental education and income levels tended to perform better on average.
- Special education services had a nonlinear relationship with performance.
- A multiple linear regression model explained a significant portion of Grade 6 score variance.

## 🛠️ Tools & Libraries

- **Language:** R
- **Libraries:** `dplyr`, `ggplot2`, `broom`, `caret`, `tidyr`, `knitr`
