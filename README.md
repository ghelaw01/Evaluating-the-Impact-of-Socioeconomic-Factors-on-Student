# Evaluating the Impact of Socioeconomic Factors on Student Academic Performance

> **Author:** [Zemen Matebe Ghelaw](https://github.com/ghelaw01) — Data Scientist & AI/ML Specialist
> **Repository:** [`ghelaw01/Evaluating-the-Impact-of-Socioeconomic-Factors-on-Student`](https://github.com/ghelaw01/Evaluating-the-Impact-of-Socioeconomic-Factors-on-Student)

Research project analyzing how socioeconomic factors—parental education, economic status, and access to educational resources—influence student achievement in math, reading, and writing.

Socioeconomic Factors and Student Academic Performance
Overview
This repository contains the research project "Evaluating the Impact of Socioeconomic Factors on Student Academic Performance." The study analyzes how socioeconomic factors such as parental education, economic status, and access to educational resources influence student achievement in math, reading, and writing.
Dataset
The analysis uses the "Students Performance in Exams" dataset, which includes information on 1,000 students with the following variables:
Demographic variables: Gender, Race/Ethnicity
Socioeconomic variables: Parental Education, Lunch Type (economic status proxy)
Educational intervention: Test Preparation Course completion
Performance metrics: Math, Reading, and Writing Scores
Research Questions
How do socioeconomic factors influence student academic performance?
Which factors have the strongest predictive power for academic outcomes?
How can these insights inform educational interventions and policies?
Key Findings
Economic status (measured by lunch type) emerged as a powerful predictor of academic achievement
Access to educational resources (test preparation) showed substantial impact on performance
Parental education level demonstrated significant but more complex relationships with student performance
Cluster analysis identified three distinct student performance profiles with clear socioeconomic associations
Repository Structure
data/: Contains the dataset used for analysis
code/: R scripts for data analysis
analysis.R: Main analysis script
figures/: Visualizations generated from the analysis
paper/: Research paper and related documents
research_paper.pdf: Final research paper
Analysis Methods
The research employs various statistical and machine learning techniques:
Exploratory Data Analysis (EDA)
Statistical tests (t-tests, ANOVA)
Multiple linear regression
K-means clustering
Requirements
To run the analysis code, you'll need:
R (version 4.0 or higher)
Required R packages:
ggplot2
dplyr
tidyr
caret
cluster
factoextra
car
Usage
Clone this repository
Install required R packages:
r
install.packages(c("ggplot2", "dplyr", "tidyr", "caret", "cluster", "factoextra", "car"))
Run the analysis script:
r
source("code/analysis.R")
Implications
The findings highlight the need for educational policies that address socioeconomic barriers to academic success, including:
Comprehensive test preparation programs
Additional support for students from lower socioeconomic backgrounds
Strategies to engage parents across all education levels
Citation
If you use this research or code in your work, please cite:
Author. Zemen, Jack, Wayne, and Anderson ITEC 610 (2025). Evaluating the Impact of Socioeconomic Factors on Student Academic Performance.
License
This project is licensed under the MIT License - see the LICENSE file for details.
Acknowledgments
Data source: Kaggle "Students Performance in Exams" dataset
R Core Team and package developers

---

<sub><b>Author:</b> Zemen Matebe Ghelaw (also: Zemen Ghelaw, Zemen M. Ghelaw) — Data Scientist & AI/ML Specialist based in Washington, D.C. · <a href="https://github.com/ghelaw01">github.com/ghelaw01</a><br><b>Keywords:</b> socioeconomic factors · education research · student performance · statistics · regression analysis · Zemen Matebe Ghelaw</sub>
