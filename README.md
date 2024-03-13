## Project Overview
* This project was for a data mining and statistical learning course intended to highlight the importance of data exploration 
Kaggle hosted a [competition](https://www.kaggle.com/competitions/shelter-animal-outcomes) in 2016 with the goal of improving the outcome (adopted, died, euthanized, returned to owner, transferred) for cats and dogs at the Austin Animal Center. Outcome is defined as the status of the animal at the time of leaving the shelter. 

The goal of this project was to answer the following questions: 
1. Do physical characteristics of a dog or cat in the Austin Animal Shelter shelter influence the fate of an animal? 
2. If so, which characteristics are most important and why? 
3. Can we create a machine learning model that predicts with accurate results the likelihood of an animal given its physical characteristics?

## Data 
A cleaned training (26,730 observations) and testing (11,457 observations) data set are provided, with a random 70/30 split. The data was collected from October 2013 until March 2016. They can be downloaded [here](https://www.kaggle.com/competitions/shelter-animal-outcomes/data)

## Results 
For more detailed results of our analysis and performance of our machine learning models, refer to the [report] and [presentation]
Here are some interesting findings: 
- ![Box Plots](https://github.com/sofialaval/Kaggle_Competition-Prediction_of_Obesity_Risk/assets/159965979/e2e3aa4b-7eed-47d3-8180-9d9ae522f574)

We found that color, breed and age of an animal affect their adoption chances. We recommend to identify these animals and dedicate more resources and time to expanding their social media presence and showcase them more often. XGBoost was the top performing model (compared to random forest and linear svc) with an accuracy score of .584. Improvements could be made to the model such as collecting more independent variables that affect animal outcomes. Examples include intake date, behavior, economic factors, etc. Including this could improve the accuracy and help better explain outcomes. 

