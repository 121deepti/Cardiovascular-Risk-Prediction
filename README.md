# Cardiovascular_Risk_Prediction

## What exactly are cardiovascular diseases?
A group of conditions affecting the heart and blood vessels is known as cardiovascular diseases. They consist of heart disease, which affects the blood vessels that supply the heart muscle. The majority of the time, a blockage that prevents blood from flowing to the heart or brain is to blame for heart attacks and strokes, which are typically sudden events. A buildup of fatty deposits on the inner walls of the blood vessels that supply the heart or brain is the most common cause of this.

The goal of the classification is to predict the 10-year risk of future coronary heart disease (CHD) for patients. The issue of coronary heart disease is a significant public health concern and early prediction of CHD risk is crucial for preventative measures. The dataset is from an ongoing cardiovascular study on residents of Flamingham, Massachusetts. The data set includes over 4000 records and 16 attributes, each of which is a potential risk factor, including demographic, behavioral, and medical risk factors.

## WHY DO WE NEED CARDIOVASCULAR RISK PREDICTION?
The greatest obstacle facing the medical industry is accurately predicting and diagnosing heart disease. Heart diseases are influenced by numerous factors. Heart disease is even referred to as a "silent killer" because it kills people without showing any obvious symptoms. When high-risk patients are diagnosed with heart disease early, it is easier to make lifestyle changes, which in turn lowers the risk of complications. Based on the way people currently live, machine learning can help predict the likelihood of heart disease in the coming years.

## Conclusion
Careful data preprocessing and transformation improved the performance of machine learning models and enabled more accurate predictions. **Feature selection** was important for identifying the most relevant predictors of CHD risk.<br>
The **Support Vector Machine model (tuned)** was chosen as the final prediction model due to its **high recall score**.<br>
Techniques such as **SMOTE** combined with **Tomek links** undersampling and **standard scalar** scaling were used to handle **imbalanced data** and improve model performance.<br>

Since we have added synthetic datapoints to handle the huge class imbalance in training set, the data distribution in train and test are different so the high performance of models in the train set is due to the train-test data distribution mismatch and not due to overfitting.

This project provides a valuable example of how machine learning techniques can be applied to real-world problems to achieve positive business impact. Overall, this project highlights the importance of careful data preparation and analysis in machine learning projects. By taking the time to clean and transform the data, select relevant features, and choose an appropriate model, it is possible to achieve accurate predictions and support decision-making in a wide range of domains.
