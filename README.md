# HR_Employee_attrition_data

Data - 05-05-2023

HR-Analytics-Employee-Attrition-Performance dataset.

I have first performed Exploratory Data Analysis on the data using various libraries like pandas,seaborn,matplotlib etc..

Then I have also used feature selection techniques like RFE (a wrapper method )to select the features. The data is then oversampled using the SMOTE technique in order to deal with the imbalanced classes. Also the data is then scaled for better performance.

Lastly I have trained many ML models from the scikit-learn library for predictive modelling and compared the performance using Precision, Recall and other metrics .

Data Dictionary
1. Age: Age of employee
2. Attrition: Employee attrition status
3. Department: Department of work
4. DistanceFromHome
5. Education: 1-Below College; 2- College; 3-Bachelor; 4-Master; 5-Doctor;
6. EducationField
7. EnvironmentSatisfaction: 1-Low; 2-Medium; 3-High; 4-Very High;
8. JobSatisfaction: 1-Low; 2-Medium; 3-High; 4-Very High;
9. MaritalStatus
10. MonthlyIncome
11. NumCompaniesWorked: Number of companies worked prior to IBM
12. WorkLifeBalance: 1-Bad; 2-Good; 3-Better; 4-Best;
13. YearsAtCompany: Current years of service in IBM

Analysis Task:
1. Import attrition dataset and import libraries such as pandas, matplotlib.pyplot, numpy, and seaborn.
2. Exploratory data analysis
    1. Find the age distribution of employees in IBM
    2. Explore attrition by age
    3. Explore data for Left employees
    4. Find out the distribution of employees by the education field
    5. Give a bar chart for the number of married and unmarried employees
    6. Build up a logistic regression model to predict which employees are likely to attrite.

Technology
1. Python with some required libraries on Jupyter notebook.

