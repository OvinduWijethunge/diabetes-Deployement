# Diabetes Prediction for people - Deployment


• This repository consists of files required to deploy a ___WEB APPLICATION___ created with ___Flask___ on ___Heroku___ platform.

• You can see deployed model in heroku , use below link for reach to deployed model:<br />
Heroku: _https://diabetes-prediction-v-1.herokuapp.com/_

• If you want to check the algorithems,models, accuracy just Click the link mentioned below:<br />
Link: _https://github.com/OvinduWijethunge/diabetes-Model_



## If you are willing to check project in flask API

### Prerequisites
You must have Scikit Learn, Pandas (for Machine Leraning Model) and Flask (for API) installed.

### Project Structure
This project has four major parts :
1. RandomForestClassifier.py - This contains code of our Machine Learning model to predict diabetes status on trainign data in 'diabetes.csv' file.
2. app.py - This contains Flask APIs that receives diabetes details through GUI or API calls, computes the precited value based on our model and returns it.
3. statics - This uses for store css files and some gifs ton use while presenting.
4. templates - This folder contains the HTML template to allow user to enter reuired detail and displays the predicted diabetes status.


### Running the project in flask API
type python app.py for start your server 
then copy the given url and paste it in your browser
then input valid inputs and predict your salary

• Front end was influenced by  _https://predicting-diabetes.herokuapp.com/_


