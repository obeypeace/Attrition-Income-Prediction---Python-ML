# Attrition-Income-Prediction---Python-ML
Welcome to the Employee Attribution and Salary Prediction Project repository! This project aims to analyze employee data from company WEMA to uncover factors influencing employee attribution and salary. We employ both classification and regression techniques to build predictive models for these objectives.

## Table of Contents
- [Project Objective](#Project-objective)
- [Data Scource](#data-source)
- [Data Processing](#data-processing)
- [Evaluation Metrices](#evaluation-metrices)
- [Key Insights](#key-insights)
- [conclusion and recommendations](#conclusion and recommendations)

## Project Objective
- Employee Attribution Classification: The primary objective is to determine the driving factors for employee attribution and build a predictive model capable of classifying whether an employee will attribute or not.
- Employee Salary Prediction: The secondary objective is to predict employee salaries based on various features present in the data.

## Data Source
The dataset used for this analysis was obtained from Kaggle. It contains various features related to employee demographics, job characteristics, and other relevant factors. The dataset is provided in a structured format, making it suitable for machine learning analysis.

## Data Processing
Before training the machine learning model, the dataset undergoes preprocessing steps such as handling missing values, encoding categorical variables, and scaling numerical features. Exploratory data analysis (EDA) techniques are applied to gain insights into the distribution and relationships between different features. Additionally, the dataset is split into training and testing sets to evaluate the model's performance. Regression models were used for the monthly income machine learning building while classification models were used for the attrition machine learning building. Lastly, the model was stimulated on a new dataset and used to make relevant predictions

## Evaluation Metrices
- For the employee attribution classification model, we use evaluation metrics such as accuracy, precision, recall, and F1-score to assess model performance. These metrics provide insight into the model's ability to correctly classify employees who attribute or do not attribute.
- For the employee salary prediction model, we use metrics such as mean absolute error (MAE), mean squared error (MSE), and R-squared to evaluate the model's predictive accuracy and goodness of fit.

## key Insights
- Overall, the company have an attrition rate of 16.9%. Employees with attrition rate of 1 tend to have a lower median value of: hourly rate, monthly income, monthly rate, total working years, years worked at company, years in current role, years since last promotion.

- Monthly income have a strong positive correlation with total working years, years at company, years in current role, years since last promotion, years with cureent manager, and age.
  
- Attrition have a very weak positive correlation with performance rating, distance from home, monthly rate, number of comapnies worked, percent salary hike.
  
- Most of the employees in the company are male (58.6%). The youth age group across both genders have an higher attrition count. For females, the elder age group have the lowest attrition count. For males, the old adult age group have the lowest attrition count. The elder age group aross both genders have an higher monthly income while the youth age group have the lowest monthly income

- Employees with a job satisfaction level of 3 have the highest attrition rate while those with a job satisfaction level of 2 have the lowest attrition rate. Employees with job satisfaction of 4 have the highest employee count while those with employee satisfaction rating of 2 have the lowest count.
  
- Most of the employees fall into the Adult age bracket while the elder age group have the least count of employees. The adult age group have the highest attrition count while the elder age group have the lowest attririon count. The adult age group have the highest monthly income while the youth age group have the lowest monthly income.
  
- Most of the employee (44%) live very close to the comapny while only 7% of the employee live far. 22% of the emploees live very far. Employees that live very close to the company have the highest attrition count while those taht live far from the company have the lowest attrition count. Employees that live very close to the company have the highest attrition count while those taht live far from the company have the lowest monthly income.
  
- The median year of last promotion of employees at the company is around 1 years, with most values falling between 0 and 3. There are some outliers, with some employees last promotion being as high as 14 years.
  
- The median total working years of employees is around 10 years, with most values falling between 5 and 15. There are some outliers, with some employees total working years being as high as 40 years. The median years spent at the company is around 5 years, with most values falling between 4 and 9. There are some outliers, with some employees spending close to 40 years at the company.
  
- The median hourly rate is around 65, with most values falling between 48 and 82. There are no outliers.
  
- The median monthly income is around 5,000, with most values falling between 2,500 and 9,500. There are some outliers, with some income as high as 20,000.
- The median monthly rate is around 14,000, with most values falling between 8000 and 20000. There are no outliers.

- Married employee have the highest employee count while divorced employee have the lowest employee count. Single employees have the higehst attrition count while the divorced employees have the lowest attrition count. Married employees have the higehst monthly income while the divorced employees have the lowest monthly income.
  
- Employees with relationship satisfaction rating of 3 and 4 have the highest employee count while those with relationship satisfaction rating of 1 have the lowest count. Employees with a relationship satisfation rating of 4 have the highest attrition rate while those with a relationship satisfation rating of 2 have the lowest attrition rate. Employees with a relationship satisfation rating of 3 & 4 have the highest monthly income hile those with a relationship satisfation rating of 1 have the lowest monthly income
  
- Employees with performance rating of 3 have the highest employee count while those with performance rating of 4 have the lowest count. Employees with a performance rating of 3 have the highest attrition rate while those with a performance rating of 4 have the lowest attrition rate. Employees with a performance rating of 3 have the highest monthly income while those with a performance rating of 4have the lowest monthly income.
  
- Employees that do not travel have the lowest attrition count while employees that rarely travel have the highest attrition count. Employees that do not travel have the lowest monthly income while employees that rarely travel have the highest monthly income. 
  
- Research & development department have the highest employee count while the human resource department have the lowest employee count. The employees in the life science department have the highest attrition count while those in the human resource department have the lowest attrition count. Employees in the research & development department have the highest monthly income while employees in the human resource department have the lowest monthly income.
  
- Employees with environment satisfaction of 3 have the highest employee count while those with employee satisfaction rating of 2 have the lowest count. Employees that have an environment satisfaction of 1 have the highest attrition coount while those that have an environment satisfaction level of 2 have the lowest attrition count. Employees that have an environment satisfaction of 4 have the highest monthly income while those that have an environment satisfaction level of 2 have the lowest monthly income. 
  
- Employees in the laboratory technician and sales executive roles have the highest attrition count while employees in the research director job role have the lowest attrition count.
  
- Life resource education field have the highest employee count while the human resource education field have the lowest employee count. The employees in the life science education field have the highest monthly income while those in the human resource education field have the lowest monthly income.
  
- Employees with job involvement level of 3 have the highest employee count while those with job involvement level of 1 have the lowest count. Employees with a job involvement level of 3 have the highest attrition rate while those with a job involvement level of 4 have the lowest attrition rate.
  
- Employees with job level of 1 have the highest employee count while those with job level of 5 have the lowest count. Employees with a job level of 1 have the highest attrition rate while those with a job level of 4 have the lowest attrition rate. Employees with a job level of 2 have the highest monthly income while those with a job level of 1 have the lowest monthly income.
  
- Employees in sales executive department the highest employee count while those in human resource department have the lowest count. Employees in the sales executive roles and manager roles have the highest monthly income while employees in the human resources and sales rep have the lowest monthly income.
  
- Employees that have no overtime have the highest employee count. Employees that have overtime have the highest attrition count while those with no overtime have the lowest attrition count. Employees that have no overtime have the highest monthly income while those with overtime have the lowest monthly income
  
- Employees with work life balance rating of 3 have the highest attrition count while those with a rating of 1 have the lowest attrition count. Employees with work life balance rating of 3 have the highest monthly income while those with a rating of 1 have the lowest monthly income
  
- 70.5% of the employees rarely travel while only 19.4% of employee travel frequesntly. 10.1% of employees have not travelled.
  
- Employees with no stock option level have the higest emploee count while those with stock option level of 3 have the lowest employee count. Employees with 0 stock option level have the highest attrition count while those with stock option level of 2 and 3 hav ethe lowest attrition count. Employees with 1 stock option level have the highest monthly income while those with stock option level of 3 hav ethe lowest monthly income.
  
- Employees that had 2 trainings in the previous year have the highest employee count while the lowest employee count were employees with no trainings in the previous year.
  
- Employees with a job involvement level of 3 have the highest monthly income while those with a job involvement level of 1 have the lowest monthly income.

## Conclusion and Recommendations
Considering these metrics, Logisitc regression seems to perform consistently well across all metrics for attrition prediction while optimized GradientBoostingClassifier model perform consistently well across all metrics for monthly income prediction
