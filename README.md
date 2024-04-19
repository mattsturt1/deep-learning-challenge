# deep-learning-challenge
module 21 challenge

In this challenge, I Used Scikit Learn and Pandas to scale data and 
use neural networks to analyze the trends and accuracy of those trends. 
Thank you to Andrew K and Sakib B for the help on this challenge.

The report should contain the following:

Overview of the analysis: Explain the purpose of this analysis. The purpose of this analysis is to see if we can predict based on past criteria whether or not companies will be successful with their ventures. As an analyst for Alphabet Soup, we must look at different variables, both numeric and classification, to make a neural network model to make this prediction.

Results: Using bulleted lists and images to support your answers, address the following questions:

Unfortunately, it was not possible to reacha percentage higher than 75% on accuracy, so the model is shaky at best. however, the results still show Data Preprocessing
What variable(s) are the target(s) for your model?

the target variable is the "IS Succesful" benchmark What variable(s) are the features for your model? the features for our model are: -----APPLICATION_TYPE—Alphabet Soup application type -----AFFILIATION—Affiliated sector of industry -----CLASSIFICATION—Government organization classification -----USE_CASE—Use case for funding -----ORGANIZATION—Organization type -----STATUS—Active status -----INCOME_AMT—Income classification -----SPECIAL_CONSIDERATIONS—Special considerations for application -----ASK_AMT—Funding amount requested What variable(s) should be removed from the input data because they are neither targets nor features? the variables that should be removed are: -----EIN -----NAME Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why? -I Used 16 and 16 because a) the evaluation seemed to best at this number and b), previoud similar exercises hovered around here, so this was a solid basline. Were you able to achieve the target model performance? -Unfortunately not What steps did you take in your attempts to increase model performance? -changing nodes and layer numbers. This combo is the best reaching about 74% (threshold is 75%). Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation. -Overall, the results show that the listed predictors were not quite able to hit the 75% accuracy threshold. WHile it is close, different models such as RandomForest could be used to get higher results.

Matthew Sturt
April 2024
