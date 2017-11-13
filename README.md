# Ames Housing Data and Kaggle Challenges

In this project, I demonstrate two important skills:

1. Creating and iteratively refining regression and classification models
2. Using [Kaggle](https://www.kaggle.com/) to practice the modeling process

I have outlined the process for creating two models with the increasing accuracy based on the Ames Housing Dataset. These models predicted the following:

- The price of a house at sale (regression)
- Whether a house sale was abnormal or not (classification)

The Ames Housing Dataset is an exceptionally detailed and robust dataset with over 70 columns of different features relating to houses. While the two models predicted different targets (and required different features, model choices, and hyperparameters), I was able to use the rich knowledge I developed from generating one model to help inform the other.

Secondly, these two competitions were hosted on Kaggle by General Assembly (one for the regression and one for the classification) to practice the following skills:

- Refining models over time
- Use of train-test split, cross-validation, and data with unknown values for the target to simulate the modeling process
- The use of Kaggle as a place to practice data science

#### You can find my work for the regression models here: https://github.com/HallieCrosby/Ames-Housing-Data-and-Kaggle-Challenges/blob/portfolio/DSI-EAST-1%20Project%203%20Regression%20Challenge.ipynb

#### You can find my work for the classification models here: https://github.com/HallieCrosby/Ames-Housing-Data-and-Kaggle-Challenges/blob/portfolio/DSI-EAST-1%20Project%203%20Classification%20Challenge.ipynb

## The Modeling Process

1. The train and test datasets for both challenges are the **same**, with the exception of the target that I was trying to predict.
2. The train dataset has all of the columns needed to generate and refine the models. The test dataset has all of those columns except for the two targets that I was trying to predict in the Regression and Classification models.
3. When generating the regression and classification models using the training data, I made use of:
   - strong exploratory data analysis to question correlation and relationship across predictive variables
   - train-test split
   - cross-validation / grid searching for hyperparameters
   - code that reproducibly and consistently applies feature transformation (such as the preprocessing library) 
4. Predicted the values for the target columns in the test dataset and submited the predictions to Kaggle to see how my model did against unknown data. 
