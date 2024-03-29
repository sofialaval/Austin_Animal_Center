## Project Overview
Kaggle hosted a [competition](https://www.kaggle.com/competitions/shelter-animal-outcomes) with the goal of analyzing the outcome (adopted, died, euthanized, returned to owner, transferred) for cats and dogs at the Austin Animal Center. Outcome is defined as the status of the animal at the time of leaving the shelter. 

This project was for a data mining and statistical learning course intended to highlight the importance of data exploration, and my team chose this competition as our project. 

The goal of this project was to answer the following questions: 
1. Do physical characteristics of a dog or cat in the Austin Animal Shelter shelter influence the fate of an animal? 
2. If so, which characteristics are most important and why? 
3. Can we create a machine learning model that predicts with accurate results the likelihood of an animal given its physical characteristics?

## Data 
A cleaned training (26,730 observations) and testing (11,457 observations) data set are provided, with a random 70/30 split. The data was collected from October 2013 until March 2016. They can be downloaded [here](https://www.kaggle.com/competitions/shelter-animal-outcomes/data)

## Results 
For more detailed results of our analysis and performance of our machine learning models, refer to the [report](https://github.com/sofialaval/Austin_Animal_Center/blob/main/ISYE7406_Final_Report.pdf) and [presentation](https://github.com/sofialaval/Austin_Animal_Center/blob/main/ISYE%207406%20Final%20Project%20Presentation.pdf)

Here are some interesting findings: 
![Animal Shelter Overall Stats](https://github.com/sofialaval/Kaggle_Competition-Prediction_of_Obesity_Risk/assets/159965979/e2e3aa4b-7eed-47d3-8180-9d9ae522f574)
![Screen Shot 2024-03-12 at 6 46 02 PM](https://github.com/sofialaval/Austin_Animal_Center/assets/159965979/01bc223d-3ed9-4613-916a-69f7d312148f)
<p align="center">
  <img src=https://github.com/sofialaval/Austin_Animal_Center/assets/159965979/63c406d6-af9e-4919-b4b7-995deba22f73>
</p>



Overall, we found that adoption was the most likely outcome for cats and dogs, with transfer being the second most likely outcome. Dogs are more likely to be returned to their owners compared to cats. 

We recommend more resources and time alloted to the animals that are older and of a breed that is not popular amongs adopters. For example, personalized headshots and expanding their social media presence can help these animals get seen more. 

XGBoost was the top performing model (compared to random forest and linear svc) with an accuracy score of .584, with age of an animal being the most important feature. This indicates that while color, breed, gender and age could be important features, improvements could still be made to the model such as collecting more independent variables that affect animal outcomes. Examples include intake date, behavior, economic factors, etc. 

