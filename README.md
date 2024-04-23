# SC1015 MiniProject - Job Salary Predictor
Lab Group: FDAD, Group 10

Instructor: Dr Smitha K G and Ong Chin Ann

## About
We aim to predict the most relevant variables that affect how much salary is received by an employee, based on aspects of experience level, job category, work setting and company size. We used dataset from [Kaggle](https://www.kaggle.com/) on the [2024 Jobs and Salaries in the Data Field](https://www.kaggle.com/datasets/murilozangari/jobs-and-salaries-in-data-field-2024).

Within this repository, we have used various exploratory data analysis techniques to identify the key variables which affect the amount of salary received. In order to assess whether the salaries are relatively low or high, we have classified the numbers into Low, Medium Low, Medium High and High, corresponding to the quartiles of the dataset. To gain a comprehensive understanding of the salary predictor, it is recommended to view the source code in the following order:

  1. Data Extraction, Cleaning & Preparation
  2. Exploratory Data Analysis
  3. Machine Learning
  4. Conclusion

## The Dataset
The data is sourced from internal data (submissions of surveys and jobs with open salaries) in the AI, ML and Data Science field. Salary is recorded in USD.

Reference: [https://www.kaggle.com/datasets/murilozangari/jobs-and-salaries-in-data-field-2024](https://www.kaggle.com/datasets/murilozangari/jobs-and-salaries-in-data-field-2024)

## Problem Definition
* Are we able to predict how relatively high or low of a salary an employee would receive based on selected variables?
* Which model would be the best to predict it?

The objective of this project is to see how the features of both an employee and a company affects the salary received by an employee and determine which variable has the highest correlation to the amount of salary received. By finding the most important variables, we will be able to provide information to people finding jobs on the job category/type of company/work setting they should target for a higher salary, or how much salary they can expect based on their experience level. We are going to do this by using 4 different machine learning models.

## Machine Learning Models
  1. Decision Tree
  2. Extreme Gradient Boosting (XGB)
  3. Random Forest

## Performance Metrics
F1-Score (Micro)

## Recommendations
According to our AI analysis, our main data driven insight is that job category and experience level are the two most important variables that affect the amount of salary received. As such, we recommend people looking for jobs in the data field to do their research on which job categories are higher paying, and to manage their expectations on the amount of salary received as per their experience level. Furthermore, the usage of more machine learning tools is recommended as we may not have considered all the possible factors due to lack of knowledge. It is also recommended to use more than one performance metrics when comparing the machine learning models.

## Conclusion
* Job category and experience level are the most important variables in predicting amount of salary received.
* This will provide people looking for jobs with relevant information to filter out jobs that may be lower paying.
* The best model performance is
* This may not be guaranteed in terms of accuracy as we may not have considered all possible factors affecting amount of salary received due to lack of knowledge.
* From Exploratory Data Analysis, we found that ???

## Contributions
* @tamans13 - Exploratory Data Analysis, Decision Tree, Data Formatting, Slides
* jiaqi - Data Extraction & Cleaning, Exploratory Data Analysis, Random Forest, Slides
* raashi - Extreme Gradient Boosting, Video Recording

## References
* [https://www.kaggle.com/datasets/murilozangari/jobs-and-salaries-in-data-field-2024](https://www.kaggle.com/datasets/murilozangari/jobs-and-salaries-in-data-field-2024)
* [https://www.geeksforgeeks.org/how-to-calculate-cramers-v-in-python/](https://www.geeksforgeeks.org/how-to-calculate-cramers-v-in-python/)
* [https://www.geeksforgeeks.org/how-to-convert-categorical-variable-to-numeric-in-pandas/](https://www.geeksforgeeks.org/how-to-convert-categorical-variable-to-numeric-in-pandas/)
* 
