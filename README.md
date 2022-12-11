## JDS Cohort 2/2022 Capstone: Target Market Analysis

This repo details my revised attempt at answering the capstone project I had to submit for the Centre of Applied Data Science (CADS) bootcamp. The initial submission was
on the 5th of October 2022. 

For the capstone, I was provided with information on customers' historical purchase records. For example, the dataset `data.csv` details information such
as the amount of money spent, number of inactive months, whether they made a purchase or not and so on. 
The overall goal is to design a predictive model to determine potential customers who will make a purchase if you send them an advertisement.

## Data description

Below are the descriptions of each feature available in the dataset `data.csv`.

<img src="images/MicrosoftTeams-image.png" style="height: 700px">

## Objectives

1. Design a predictive model to determine potential customers that will make a purchase if we send them advertisement.
The target variable here is `Potential_Customer`. 

2. Calculate the value and the revenue of our models.

3. Compare the best model's revenue with the revenue of the default solution which is sending advertisement to all the customers in X_test.

4. Will you send the advertisement to everyone, or you use one of the models you have already created, given the following assumptions?

    - Assume that we now want to target a group of 30,000 customers simillar to this group. 
    - Additionally, assume that the purchase rate is $10%$ which means 10 out of 100 people who receive the advertisement will purchase the product.
    - Also assume your model will have the same Precision and Recall for Class1.



