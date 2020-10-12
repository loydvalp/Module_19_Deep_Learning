# Alphabet Soup Challenge

Build your own machine learning model that will be able to predict the success of a venture paid by Alphabet soup. Train model will be used to determine the future decisions of the company—only those projects likely to be a success will receive any future funding from Alphabet Soup.

## Project Overview

### Objectives

The goals of this challenge:

1. Import, analyze, clean, and preprocess a “real-world” classification dataset.
2. Select, design, and train a binary classification model of your choosing.
3. Optimize model training and input data to achieve desired model performance.

## Resources

Data Source: charity_data.csv
Software: Python 3.7.6, Anaconda 4.8.4, Jupyter Notebook 6.0.3

## Challenge Overview

1. Create a new Jupyter Notebook within a new folder on your computer. Name this new notebook file “AlphabetSoupChallenge.ipynb” entifiable).
2. Download charity_data.csv
3. Import and characterize the input data.
      - What variable(s) are considered the target for your model? 
      SPECIAL_CONSIDERATIONS and IS_SUCCESSFUL
      
      - What variable(s) are considered to be the features for your model?
      APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT, IS_SUCCESSFUL
      
      - What variable(s) are neither and should be removed from the input data?
      EIN and NAME
      
4. Using the methods described in this module, preprocess all numerical and categorical variables, as needed:
      - Combine rare categorical values via bucketing.
      - Encode categorical variables using one-hot encoding.
      - Standardize numerical variables using Scikit-Learn’s StandardScaler class
5. Using a TensorFlow neural network design of your choice, create a binary classification model that can predict if an Alphabet Soup funded organization will be successful based on the features in the dataset.
      - You may choose to use a neural network or deep learning model.
 6. Compile, train, and evaluate your binary classification model. Be sure that your notebook produces the following outputs:
      - Final model loss metric
      - Final model predictive accuracy
 7. Do your best to optimize your model training and input data to achieve a target predictive accuracy higher than 75%.
 8. Create a new README.txt file within the same folder as your AlphabetSoupChallenge.ipynb notebook. Include a 5–10 sentence writeup in your README that addresses the following questions:
      - How many neurons and layers did you select for your neural network model? Why?
      - Were you able to achieve the target model performance? What steps did you take to try and increase model performance?
      - If you were to implement a different model to solve this classification problem, which would you choose? Why?
     
## Summary      
