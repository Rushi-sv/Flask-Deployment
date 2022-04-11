# Flask-Deployment
This project contains 4 parts :

1. model.py - Contains machine learning model for employee salary prediction
2. app.py - Contains Flask APIs
3. Templates - The folder contains the HTML webpage
4. static - The folder contains css styling of the webpage

## Running the project
1. Ensure that you are in the project home directory. Create the machine learning model by running below command -
python model.py
This would create a serialized version of our model into a file model.pkl

2. Run app.py using below command to start Flask API -
python app.py
3. By default, flask will run on port 5000.
Navigate to URL http://localhost:5000
