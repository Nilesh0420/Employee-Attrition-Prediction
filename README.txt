This project aims to predict whether an employee will leave the organization or not, based on Kaggle's 'HR-Employee-Attrition' dataset. This dataset comprises of 1470 rows and 35 columns like Age, MonthalySalary, etc.

I loaded the dataset, checked its missing values restructured the data. I used the label encoding technique to encode the categorical values & then standardized and normalized the data, hence making it ready for the modelling part.

I've applied K-Nearest Neighbor as my base model. Further I have applied multiple classification models like Logistic Regression, Support Vector Classifier, Decision Tree Classifier, Random Forest Classifier, Gradient Boosting Classifier. Finally, I achieved the highest accuracy of 87% with KNN Model having 27 neighbours.