# Project_Stroke_Prediction_Model

#Author: Ryan Croasdale

#Project Description:

The data scientists at World Health Organization have collected 12 pieces of information from 583 individuals. The aim is to build a predictive model and find out trends among the individuals.

#Context:

According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths.
This dataset is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient.

#Data:

Original source: https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

#Methods: 

After cleaning the data and completing preprocessing, I used a Random Forest Classifier, KNN Model, Log Reg Model, Decision Tree Classifier, and a Soft Voting Classifier Model and with tuning to evaluate the dataset. I further went onto use PCA with a KNN model, and then Feature Engineering with a Random Forest Classifier to try to improve overall metrics. 

#Results

Whether or not an individual is likey to have a Stroke or not.

image

A barplot of outlet type vs outlet sales. The larger the store the more sales it does on average.

Item Type vs Count

image

A barplot that expresses the count of each item type in the dataset

Conclusion

-The Items bought are more of Low Fat

-"Fruits and vegetables" and "Snack food" are the most sold items in all the stores with all sizes.

-The Item Outles sales are high for both Low Fat and Regular Item types, so its not justified why all the outlets have more low fat products than regular.

-The items with visibility near to zero is rarely purchased by the customers.

The "Outlet_Establishment_Year" has no effect on the sales made by any outlet, as the number of sales made or the mean of all years are nearly the same .

For further information For any additional questions, please contact email Ryancroasdale9@gmail.com
