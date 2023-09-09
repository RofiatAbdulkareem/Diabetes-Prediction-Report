# Diabetes-Prediction-Report
	About the dataset
The Diabetes prediction dataset is a collection of medical and demographic data from patients, along with their diabetes status (positive or negative). The data includes features such as age, gender, body mass index (BMI), hypertension, heart disease, smoking history, HbA1c level, and blood glucose level.
	About Diabetes
Diabetes is a chronic disease that occurs when the pancreas does not produce enough insulin, or when the body cannot effectively use the insulin produced. Insulin is a hormone that regulates blood glucose
	Goal of project
The goal of the project is to create a one-page summary report, showing the correlation of each features such as BMI, hypertension, heart disease, etc. to diabetes.
	Data Sourcing 
The dataset was gotten from Kaggle https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset
	Understanding the Dataset
The first step I took was to have a good understanding of the dataset, Since I was already familiar with diabetes as a biochemist, I did not find it hard for my first step which is data exploration.
	Data exploration

•	The next step was to critically examine my datasets, check the quality of the data, look for missing values, outliers, duplicate values, and inconsistencies.
•	After cleaning the dataset, I wanted more insights into the data by calculating the descriptive statistics, i.e, Mean, Median, Standard Deviation, Min and Max for my numerical variables such as age, BMI, HbA1c level, and glucose level. 
	Why am I doing this? 
•	I wanted an overview of the central tendencies and spread of the data.
•	A comparison of the mean and median can help identify the potential outliers. If the mean is significantly higher or lower than the median, extreme values may be present in the data.
•	If the mean and median are close to each other, this suggests a symmetric distribution, whereas a large difference indicates potential skewness (lack of symmetry in the data distribution).
•	The minimum and maximum ages give you an idea of the span of ages covered in your data
•	This indicates how many individual data points differ from the mean (average) value. A higher standard deviation indicates that the data points are spread out more from the mean, whereas a lower standard deviation suggests that the data points are closer to the mean.

	Data transformation using excel
Looking at the data exploration, variables and data that are relevant to our analysis, I choose to answer the following questions.
	Scientific Questions
1.	Does age, sex, BMI have an effect in diabetes
2.	How do hypertension, smoking history, and heart disease affect blood glucose levels? Do they have causal effects? Is there a correlation?
3.	Does an increase in blood glucose level indicate diabetes?
4.	The HbA1C (Hemoglobin A1C) test is commonly used to monitor long-term blood glucose control in individuals because it measures the percentage of red blood cells that have glucose-coated hemoglobin. The HbA1C test provides the average blood glucose level over a few months. Therefore, does high HbA1C indicate diabetes?

	The process
•	Mostly using Pivot table, I grouped the diabetes column into “Diabetic” and “not Diabetic,” which provided insights into the % of the diabetic group.
•	Using the pivot table, HbA1c, Hypertension and Blood glucose levels were added and the averages were compared between the two diabetes groups.
•	The blood glucose level and the diabetes group were compared using Pearson’s correlation to determine the relationship.
•	I did things like BMI Analysis, calculated the descriptive statistics so that I can understand the average BMI and its spread among diabetic and non-diabetic groups
•	The Average HbA1c levels were visualized to show the difference in the two diabetes groups
•	I also created a contingency table, comparing hypertension and diabetes; I compared them into four groups: diabetic + hypertensive, diabetic + non-hypertensive, non-diabetic + non-hypertensive, and non-diabetic + hypertensive.
•	A contingency table for diabetes and heart disease to see if there was a causal effect or any type of effect.
•	I wanted to see the patterns and trends of any kind.

	Visualization
•	All visualizations were created using MS Excel to create a one page report. The following insights were drawn from the analysis.
•	Prevalence of Diabetes: From dataset of 100,000 individuals, 91% (91,500) were diabetic and 9% (8500) were diabetic.
•	Average HbA1c: The Hemoglobin A1C test provides the average blood glucose level over a few months, whereas for people without diabetes, the normal range for the hemoglobin A1c level is between 4% and 5.6%. HbA1c levels between 5.7% and 6.4% mean you have prediabetes and a higher chance of getting diabetes. levels of 6.5% or higher means you have diabetes. (source:webmd.com)
•	Hypertension vs. diabetes: A correlation coefficient of 0.197 indicates a relatively weak relationship. This is not a very strong correlation, but it still suggests a tendency for the two variables to move together in the same direction. From the diagram above, some people who were non-diabetic still had hypertension, while some people who were diabetic had no hypertension. A positive correlation might indicate that individuals with diabetes are somewhat more likely to have hypertension; however, this does not necessarily mean that one directly causes the other.
•	BMI: If BMI is 18.5 to 24.9, it falls within the healthy weight range; if BMI is 25.0 to 29.9, it falls within the overweight range; if it is 30.0 or higher, it falls within the obese range. An average BMI of 32 falls within the obese range, but it does not guarantee that an individual will have diabetes. Many people with higher BMIs do not have diabetes, and many with lower BMIs can still develop diabetes.
•	Smoking History: From the chart above, smoking do not have a causal effect on diabetes, people who never smoked also had diabetes, it may not have a direct effect
•	Heart Disease Vs Diabetes:  The correlation between heart disease and diabetes is 0.17 which falls closer to 0, indicating a weak positive relationship, It means that there is a slight tendency for the two variables to increase together, but the relationship is not very strong or significant, therefore, it suggests that there is a slight tendency for individuals with diabetes to also have a slightly higher likelihood of having heart disease. However, the correlation is not strong, and other factors might be influencing the relationship between the two variables.
•	Age Groups Vs Diabetes: people with older age groups (40-80) were found to be Diabetic compared to younger age groups

	CONCLUSION
•	From my analysis, Diabetes as a disease is not caused by individual factors like age, BMI, etc., but there is a tendency that these factors together might contribute to diabetes.
•	More research like building machine learning models should be done to predict diabetes in patients based on their medical history and demographic information


