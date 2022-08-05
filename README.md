# Project_Stroke_Prediction_Model

# Author: Ryan Croasdale

# Project Description:

The data scientists at World Health Organization have collected 12 pieces of information from 583 individuals. The aim is to build a predictive model and find out trends among the individuals.

# Context:

According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths.
This dataset is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient.

# Data:

Original source: https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

# Methods: 

After cleaning the data and completing preprocessing, I used a Random Forest Classifier, KNN Model, Log Reg Model, Decision Tree Classifier, and a Soft Voting Classifier Model and with tuning to evaluate the dataset. I further went onto use PCA with a KNN model, and then Feature Engineering with a Random Forest Classifier to try to improve overall metrics. 

# Results

Whether or not an individual will have a Stroke

# Data Visual

![Screenshot 2022-07-28 211716](https://user-images.githubusercontent.com/105382201/183113752-72f507a1-0405-4836-a561-99dc4e27ec61.png)

A pie graph of Age Group Distrubtion of the individuals in the study

![Screenshot 2022-07-28 211942](https://user-images.githubusercontent.com/105382201/183114011-c545dedf-4e71-4f3a-b7da-0fb14608c6e9.png)

A barplot that expresses the cohorts of smokers vs non smokers, and whether they've had a stroke.

# Conclusion

- The data shows that if you're a 65+ y/o Male, Smoker, with Hypertension and Heart Disease with elevated Avg Glucose Level, has been married and had kids, and worked in the Private Sector then you would be an indivdual with the absolute highest risk to have a stroke.

- All models tested performed very similiarly, with accuracy scores at or around 93.7%, before oversampling was applied.

- After oversampling was applied all models preformed very differently, giving a better outcome of results.

- The Random Forest Classifier had an accuracy of 98.3% with a recall of 97% and a precision of 100%.

![Screenshot 2022-08-05 113849](https://user-images.githubusercontent.com/105382201/183113612-4b0419ab-b25e-4492-a4f6-d7217ad8f666.png)


# Contact
For further information For any additional questions, please contact email Ryancroasdale9@gmail.com
