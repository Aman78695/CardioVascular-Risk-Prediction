# CardioVascular-Risk-Prediction
Predicting coronary heart disease in advance helps raise awareness for the disease. Preventive measurements like changing diet plans and exercise can slow down the progression of CHD. Early prediction can result in early diagnosis. The goal is to predict whether the patient has a 10-year risk of future coronary heart disease (CHD).
Cardiovascular diseases (CVD) are among the most common serious illnesses affecting human health. CVDs may be prevented or mitigated by early diagnosis, and this may reduce mortality rates. Identifying risk factors using machine learning models is a promising approach. We would like to propose a model that incorporates different methods to achieve effective prediction of heart disease. For our proposed model to be successful, we have used efficient Data Collection, Data Pre-processing and Data Transformation methods to create accurate information for the training model.

New hybrid classifiers like Decision Tree Bagging Method (DTBM), Random Forest Bagging Method (RFBM), K-Nearest Neighbours, Bagging Method (KNNBM), AdaBoost Boosting Method (ABBM), and Gradient Boosting Boosting Method (GBBM) are developed by integrating the traditional classifiers with bagging and boosting methods, which are used in the training process. We have also instrumented some machine learning algorithms to calculate the Accuracy (ACC), Sensitivity (SEN), Error Rate, Precision (PRE) and F1 Score (F1) of our model, along with the Negative Predictive Value (NPR), False Positive Rate (FPR), and False Negative Rate (FNR). The results are shown separately to provide comparisons. Based on the result analysis, we can conclude that our proposed model produced the highest accuracy while using RFBM and Relief feature selection methods (99.05%).

Approach:

The approach followed here is to first check the sanctity of the data and then understand the features involved. The events followed were in our approach:

•	Understanding the business problem and the datasets.

•	Data cleaning and pre-processing: -finding null values and imputing them with appropriate values. Converting categorical values into appropriate data types and merging the datasets provided to get a final dataset to work upon.

•	Exploratory data analysis of categorical and continuous variables against our target variable.

•	Data manipulation- feature selection and engineering, feature scaling, outlier detection and treatment and encoding categorical features.

•	Modelling- The baseline model Decision tree was chosen considering our features were mostly categorical with few having continuous importance.

•	Model Performance and Evaluation

•	Conclusion and Recommendations


Data Description:
The dataset provides the patients’ information. It includes over 3390 records and 17 attributes. Variables Each attribute is a potential risk factor. There are both demographic, behavioural, and medical risk factors.

Demographic:
• Sex: male or female("M" or "F")

• Age: Age of the patient

Behavioural:
• is_smoking: whether the patient is a current smoker ("YES" or "NO")

• Cigs Per Day: the number of cigarettes that the person smoked on average in one day

Medical(History):
• BP Meds: whether the patient was on blood pressure medication

• Prevalent Stroke: whether the patient had previously had a stroke

• Prevalent Hyp: whether the patient was hypertensive

• Diabetes: whether the patient had diabetes (Nominal) Medical(current)

• Tot Chol: total cholesterol level

• Sys BP: systolic blood pressure

• Dia BP: diastolic blood pressure

• BMI: Body Mass Index

• Heart Rate: heart rate

• Glucose: glucose level

• CHD: 10-year risk of coronary heart disease CHD(binary: “1”, means “Yes”, “0” means “No”)




Findings and Applications
1.The elderly are more likely to suffer from various types of cardiovascular diseases.

2.Cholesterol level is a very important determinant in leading to cardiovascular diseases. The risks of getting cardiovascular diseases climb significantly when the cholesterol content in human body rises above the normal.

3.People with high alcohol consumption have a lower likelihood to have cardiovascular diseases.

4.Physical activities help people become less susceptible to cardiovascular diseases.

5.A female non-smoker is less likely to have cardiovascular diseases, while a male smoker is less likely to get cardiovascular diseases.

6.As long as people have systolic blood pressure ≥ 126, they are classified as those susceptible to cardiovascular diseases. Therefore, high systolic blood pressure plays an important role in predicting that one experiences greater risks of suffering from cardiovascular diseases.

7.Among the three splitting factors, two of them are age. This suggests that apart from systolic blood pressure, age is the second most significant factor in deciding whether a person will have a chance of getting cardiovascular disease.

CONCLUSION
1.As age increases the risk of getting diagnosed with heart disease also increases.

2.Cigarette consumption is also a major factor that causes CHDs.

3.Patients having Diabetes and cholesterol problems show a higher risk of CHDs.

4.Patients having high glucose levels are more prone to CHDs.

5.Patients with a history of “strokes” have a higher chance of developing CHDs.

6.Patients with high BMI(Body Mass Index) are at more risk of getting diagnosed with CHDs.

7.Finally we can say that, XGBoost Classifier has performed best among all the models with the accuracy of 76% & f1-score of 0.71. It is by far the second highest score we have achieved. So, It’s safe to say that XGBoost Classifier provides an optimal solution to our problem.




