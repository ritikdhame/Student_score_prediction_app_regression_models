#Student score prediction app 

#objective : 
This project aims to build prediction model using various regression models to predicti the score of a student based on various factors and then create a flask app hosted and deployed through AWS beanstalk and AWS codepipeline
![Screenshot 1](https://github.com/ritikdhame/Student_score_prediction_app_regression_models/assets/7029092/63586c63-d078-468f-80c6-77c4bbcca9c9)

#Build 
The code for the app can be divided into the folowing parts 
- Components : data ingestion, data transformer, model trainer 
- Pipelining : predict and train pipline, where I have called various components to carry out prediction
- Pickle files : model and preprocessor (helping in caching the model post Model building and training )
![Screenshot 3](https://github.com/ritikdhame/Student_score_prediction_app_regression_models/assets/7029092/619efb72-01be-4021-a480-545f8afb2bfc)
#About data 
-The code requires the following dataset : https://github.com/ritikdhame/Student_score_prediction_app_regression_models/tree/main/notebook/data
-The dataset contains : student scores (	math_score	reading_score	writing_score ) and coressponding variables such as gender	race_ethnicity	parental_level_of_education	lunch	test_preparation_course

#Requirements 
To run the code, you need to install the following libraries:
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
- catboost
- xgboost
- Flask
You can install them using pip or conda commands.

#models used
- Lasso &  Ridge 
- Decision tree
- Random Forest
- XGBoost
- AdaBoost
- CatBoost
- I have used Rsquare as the loss function
  
#Procedure  
To run the code, you need to execute the following steps:
1. Import the required libraries.(pip isntall requirements.txt)
2. Run application.py to deploy it locally on the terminal sutied to the device 
3. In case of running it AWS just fork the repo and then run hosting it on Beanstalk and utilizing codepipline to load the repo.

The code is commented and documented for better understanding and readability.

![network architecture](https://github.com/ritikdhame/Student_score_prediction_app_regression_models/assets/7029092/2138cf79-2719-42bc-8757-8cb2898bdecf)
