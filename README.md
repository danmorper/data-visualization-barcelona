# Barcelona Education & Income – Data Visualization in R

Exploratory data analysis and visualization of education level and income across neighborhoods in Barcelona.

This project analyzes how education levels relate to income distribution across the city, using public demographic data and R.

## 📊 Main Techniques
- Tidyverse workflow (`dplyr`, `ggplot2`)
- EDA and data storytelling
- Density plots & faceted scatter plots
- Boxplots comparing income groups
- Spearman correlation test with **bootstrapped confidence interval**

## Possible improvements
- Use **median**/trimmed income aggregation and document missing data.
- **Model the proportion properly:** fit a **binomial regression** on counts  
  `cbind(Univ_count, Total_acad - Univ_count) ~ Income` (logit link). 
- Keep **bootstrapped CIs** and add uncertainty for group comparisons.

## 🗂️ Files
| File | Description |
|---|---|
`StudyCase.Rmd` | R Markdown source code  
`StudyCase.pdf` | Final report  
`StudyCase.html` | Final report (HTML)  
`/data/*.csv` | Raw input datasets  

## 🧠 What I Learned
- Practical data visualization and reporting in R  
- Organizing and communicating an analysis  
- Using non-parametric tests (Spearman correlation)
- **Bootstrapping** the Confidence Interval
- Thinking critically about confounders (population size)

## 🎓 Course
**Data Analysis & Visualization in R**  
Technical University of Munich — Erasmus semester (2022)

## 👥 Team
Project completed with classmates during the TUM Erasmus program.  
This repository contains **my personal version** of the project files for portfolio purposes.
