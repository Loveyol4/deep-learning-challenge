# deep-learning-challenge
Module 21 Challenge- reference Xpert Learning Assistant for code issues. 
Overview: The purpose of this analysis is to create a binary classifier to predict whether applicants will be successful if funded by Alphabet Soup using machine learning and neural networks.
Results: 
Data Preprocessing:
o	What variable(s) are the target(s) for your model?
a.	“IS_Successful” is the target that I used for my model.
o	What variable(s) are the features for your model?
a.	I used the following variables for my features:

APPLICATION_TYPE
AFFILIATION
CLASSIFICATION
USE_CASE
STATUS
INCOME_AMT
ASK_AMT
IS_SUCCESSFUL

o	What variable(s) should be removed from the input data because they are neither targets nor features?
The following variables were removed from the input data:
EIN
NAME
ORGANIZANTION 
SPECIAL_CONSIDERATIONS
Compiling, Training, and Evaluating the Model:
o	How many neurons, layers, and activation functions did you select for your neural network model, and why?
a. I selected 350 neurons to increase the accuracy.
o	Were you able to achieve the target model performance?
No, I did not achieve the target model performance in my AlphabetSoupCharity_Optimization.ipynb.

o	What steps did you take in your attempts to increase model performance?
I attempted the following steps to increase model performance:
a.	Removed Organization and Special Considerations from the features
b.	Used Application_Type 10 as a target 
c.	 Increase/decrease the neurons (some increases/decreases caused errors)
d.	Increase/decrease the units 

Summary: Overall the results were achieved with the deep learning model.
