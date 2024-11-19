Cardiographic Dataset Exploratory Data Analysis (EDA)
Welcome to the Cardiographic Dataset EDA project! This repository contains a comprehensive exploratory analysis of the cardiographic.csv dataset. The primary objective of this project is to uncover insights, identify patterns, and understand the underlying structure of the dataset using statistical summaries, data manipulation, and advanced visualizations.

Objective
To conduct a thorough exploratory data analysis of the cardiographic dataset to gain meaningful insights into fetal health indicators and provide actionable recommendations based on the findings.

Dataset Description
The dataset comprises key indicators related to fetal health. Below are the features analyzed:

LB - Baseline Fetal Heart Rate (FHR)
AC - Accelerations in the FHR (indicating fetal well-being)
FM - Fetal Movements detected by the monitor
UC - Uterine Contractions
DL - Late Decelerations (may indicate fetal distress)
DS - Short Decelerations
DP - Prolonged Decelerations
ASTV - Percentage of Time with Abnormal Short-Term Variability
MSTV - Mean Value of Short-Term Variability
ALTV - Percentage of Time with Abnormal Long-Term Variability
MLTV - Mean Value of Long-Term Variability
Tools and Libraries
The analysis is conducted using Python and the following libraries:

Data Manipulation: pandas, numpy
Data Visualization: matplotlib, seaborn
Documentation and Analysis: Jupyter Notebook
Project Workflow
1. Data Cleaning and Preparation
The dataset was loaded into a pandas DataFrame.
Missing values were handled using imputation or removal techniques.
Data types were corrected to ensure consistency (e.g., converting strings to numeric).
Outliers were detected using statistical techniques and treated appropriately.
2. Statistical Summary
Central tendency measures like mean and median were calculated for all features.
Dispersion metrics such as standard deviation and interquartile range (IQR) were evaluated.
Key insights from the statistical summary were highlighted to provide an initial understanding of the data.
3. Data Visualization
Histograms and boxplots were used to visualize the distributions of numerical variables.
Scatterplots and a correlation heatmap explored relationships between variables.
Advanced techniques like pair plots and violin plots provided deeper insights into variability and distributions.
4. Pattern Recognition and Insights
Correlations between variables were identified and discussed, such as the relationship between:
Fetal Movements (FM) and Accelerations (AC) to assess fetal well-being.
Uterine Contractions (UC) and decelerations (DL, DS, DP) to monitor potential distress.
Trends and patterns were identified to provide actionable insights.
5. Conclusion
Summarized the key findings and their implications for decision-making.
Proposed recommendations for further analysis and potential clinical applications.
Key Findings
Weak Correlation Between Baseline FHR (LB) and Uterine Contractions (UC): Minimal direct influence, suggesting other factors may play a larger role.
Strong Correlation Between Accelerations (AC) and Fetal Movements (FM): Confirms fetal well-being.
Abnormal Variability Indicators (ASTV/ALTV): Elevated values suggest potential fetal distress, warranting closer monitoring.
Late and Prolonged Decelerations (DL/DP): Highlighted the need for immediate medical attention in specific scenarios.
Contact



If you have any questions or feedback, feel free to reach out:

Name: Raj Shekokar
Email: rajshekokar3.com
GitHub: Rajshekokar3
