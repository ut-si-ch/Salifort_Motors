# Salifort_Motors
Machine Learning Project for analyzing key factors responsible for high employee turnover and building a predictive model.

# Overview
The goal of this project is to analyze the data collected by HR department and to build a model that predicts whether or not an employee will leave the company.This project  uses a dataset called #HR_capstone_dataset.csv . It represents information about employee survey.The random forest model performed well with 96% accuracy and 87% precision. Based on the model, last_performance_rating, number_of_projects, years_at_company, overworked were top performing features as a result of feature engineering.

# Business Understanding
Salifort Motors is experiencing a high rate of turnover among its employees. The company makes bug investment in recruiting, training, and upskilling its employees. Further, high turnover rate is costly in financial sense. At this stage, it is important to understand the reasons behind there departure, so that company can better understand the problemand develop a solution.

# Data Understanding
The Salifort Motors dataset is created by creating a survey of sample of employees to learn about what might be driving turnover. It represnts 10 different columns of self reported information from employee of a multi national vehicel manufacturing corporation. The dataset contains 15k rows representing different employees self reported information. The features include information of satisfaction_level, last_evaluation, number_project, etc.
In connection to this new features were engineered and not useful were dropped.

# Modelling and Evaluation
As the outcome variable is categorical in nature, Logistic Regression model was used that achieved a precision of 80%, recall of 83% and accuracy of 83% on test set. After conducting feature enginnering, the decision tree model achieved a precision of 87%, recall of 90.4%, and accuracy of 96.2% on the test set.The random forest model modestly outperformed the decision tree model.According to the model, the dominating features were 'last_evaluation', 'years_at_company', 'number_project',and 'overworked', have the highest importance. These variables are most helpful in predicting the outcome variable, 'left'. 

The below chart shows the features,

![image](https://github.com/user-attachments/assets/1bbadd44-288c-414f-a881-91371ca542c7)


The models and the features importances extracted from the models confirm that employees at company are overworked. so to retain employees, company can take appropriate measures.

# Conclusion
The model help predict whether an employee will leave and identify which factors are most influential. These insights can help HR make decisions to improve employee retention which will be benefical for the company. 
