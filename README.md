# 19

## Neural_Network_Charity_Analysis

### Overview of the Project

In this Analysis we looked at Alphabet Soup, a Charitable organisation that helps needy with small loans and helped trhem determine the people that will be able to pay back the loans

### Analysis

The 75% target was not reached. The first model only achieved a 71.5% accuracy rate.
- What steps did you take to try and increase model performance?
1. Optimization 1: Reduced the application_counts to less than 500 and the classification_counts to les than 800; increased neurons to 80 and 30 respectively.


![1st_opt_score](https://user-images.githubusercontent.com/80402142/130339717-50fde162-8a58-4a67-9d3e-f6bc900e7aa0.PNG)

2. Optimization 2: Dropped SPECIAL_CONSIDERATIONS feature because of prevalance of "N" for the value, returned application_counts to less than 700 and classification_counts to less than 1800; returned hidden layers to original values and added a third hidden layer with 25 neurons.


![2nd_opt_score](https://user-images.githubusercontent.com/80402142/130339722-b272f71e-7101-454c-8f3a-be02260605c5.PNG)

3. Optimization 3: Dropped the third hidden layer and changed the activation method for the output layer to "tanh"

![3rd_opt_score](https://user-images.githubusercontent.com/80402142/130339727-ea785cef-be68-44a6-823b-4c690d115c77.PNG)



### Summary

Overall, optimizing the initial model did not significantly improve its predictive accuracy.  All four models failed to meet Alphabet Soup's threshold of 75%. These attemmpts to finda a nueral network model for this dataset that achieved an accuracy rate of 75% or greater failed.
