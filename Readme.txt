Diabetes Dataset Analysis
This project analyzes a dataset related to diabetic patients. The objective is to derive meaningful insights into various factors like gender, age, insulin consumption, hospital readmission rates, and other relevant health indicators. The analysis is performed using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

Dataset
The dataset used is diabetic_data.csv, which contains records of diabetic patients, including medical history and various health-related indicators.

Analysis Performed
Data Cleaning:

Identified and removed columns with irrelevant data such as max_glu_serum, A1Cresult, and weight.
Handled missing values and invalid entries, particularly removing records with Unknown/Invalid gender values.
Exploratory Data Analysis (EDA):

Analyzed the distribution of gender, age groups, and insulin consumption using count plots and bar charts.
Visualized missing data with heatmaps and investigated its patterns.
Gender-based Analysis:

Investigated the distribution of male and female patients, their insulin consumption, and corresponding readmission rates.
A pie chart was created to depict the proportion of males and females in the dataset.
Age-based Analysis:

Age groups were visualized using bar charts to show their distribution and relationship with readmission rates.
Insulin Consumption:

Replaced the insulin values with binary values (0 for no/steady insulin, 1 for increased insulin).
Analyzed the insulin consumption rate across different genders and races.
Created visualizations to show the percentage of insulin consumption for each race and gender.
Readmission Rates:

Analyzed the relationship between gender and readmission rates, showing a higher readmission rate for females.
Investigated which age group had the highest rate of readmission.
Explored the link between the length of hospital stays and the probability of being readmitted.
Lab Procedures & Medications:

Analyzed the number of lab procedures performed on patients and their relationship with readmission rates.
Examined the distribution of prescribed medications and found that the median number of prescribed medications is 15.
Diabetes Medication Changes:

Investigated how many individuals underwent changes in their diabetes medications and visualized these findings.
Key Insights
Female patients were readmitted more often than male patients.
Older patients (particularly in the age group of 70-80) had a higher chance of readmission.
Insulin consumption showed a slight difference across genders, with males slightly more likely to consume higher doses.
The race labeled as "Other" had the highest percentage of insulin consumption.
Most patients did not experience changes in their diabetes medications during their hospital visits.
Readmission rates did not show a significant correlation with the length of hospital stays.
Tools and Libraries Used:
Pandas for data manipulation and cleaning.
NumPy for numerical computations.
Matplotlib and Seaborn for data visualization.