# deep-learning-challenge
**Overview**

The objective of this analysis is to develop a machine learning model that can effectively identify a fictitious charitable organization with the highest likelihood of success in their endeavors. The dataset used for this analysis is sourced from Alphabet Soup, a nonprofit foundation, and consists of information on over 34,000 organizations that have previously received funding from Alphabet Soup. The dataset includes details such as application type, affiliation, classification, funding use case, organization type, active status, income, special considerations, requested funding amount, and the success or failure of each applicant.

The primary objective is to leverage the dataset for constructing a binary classification model that accurately predicts the success of charitable organizations, enabling Alphabet Soup to make well-informed funding decisions. The analysis involves several stages, such as data cleaning, preprocessing, feature engineering, model selection, training, and performance evaluation, with the ultimate aim of developing a model that effectively predicts funding success and aids in future approval decisions.


**Results**
* Data Preprocessing
 * What variable(s) are the target(s) for your model?
   - Targer variable is the "IS_SUCCESSFUL" data 
 * What variable(s) are the features for your model?
   - My variables in my model is 'APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION', 'USE_CASE',
       'ORGANIZATION', 'STATUS', 'INCOME_AMT', 'SPECIAL_CONSIDERATIONS',
       'ASK_AMT' data.
 * What variable(s) should be removed from the input data because they are neither targets nor features?
   - Variable that should be removed from the data are "EIN", "NAME" as they were neither targets nor features.

* Compiling, Training, and Evaluating the Model
 * How many neurons, layers, and activation functions did you select for your neural network model, and why?
   - For this classification problem, a neural network model with four layers was selected. The first layer had 80 neurons, the second layer had 30 neurons, and both the third and output layers consisted of 10 neurons each.
   
 * Were you able to achieve the target model performance?
   - The target goal of achieving an accuracy above 75% was not met.

**Summary**

The deep learning model created for this classification task achieved an accuracy of around 72%, which surpasses random guessing but still indicates room for improvement. To enhance its performance, one could consider exploring alternative algorithms, like a Random Forest model, which has shown promising results in various classification problems and might be better tailored to the dataset's specific features.