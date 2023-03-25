## JDS Cohort 2/2022 Capstone: Target Market Analysis

For the capstone, I was provided with information on customers' historical purchase records. For example, the dataset `data.csv` details information such as the amount of money spent, number of inactive months, whether they made a purchase or not and so on.

## Objectives

1. Design a **predictive model to determine potential customers that will make a purchase** if we send them advertisement. The target variable here is `Potential_Customer`. 
2. The model will then be **benchmarked against the default option where we simply send advertisements to everybody.** Given the cost of sending one advertisement (MYR5.00) and average purchase of MYR14.56, we'll need to see if the overall revenue of our model can exceed the default revenue of MYR1,463.00.

## Findings

While we notice slightly higher revenue (MYR2,078.85) than the default solution, our model still suffers from having **poor precision in the positive class (54%)**, as well as **low accuracy (58%)**. However, our model does have **satisfactory recall** for the positive class (76%).

Future models may benefit from *a larger dataset* and *better data quality*. We note that there were several instances where `Age` was below 18 (0 for some customers!) and `Income` was 0, despite being active (A) and star (S) buyers. Hence, an inital dataset with 4,469 rows was subsequently trimmed down to 3,618.

## Machine Learning Algorithms Used

- XGBoost Classifier
- Support Vector Machine
- Logistic Regression
- Decision Tree Classifier 
- K-Nearest Neighbours *(best model)*

Additionally, threshold-moving was employed (a 44% probability threshold was used for the best model) due to the base model's tendency to predict the negative class (0).

## Data Description

Below are the descriptions of each feature available in the dataset `data.csv`.

<img src="images/MicrosoftTeams-image.png" style="height: 700px">



