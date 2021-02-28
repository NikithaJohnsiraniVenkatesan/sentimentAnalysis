# Deploying sentiment analysis Flask app on Google cloud run

In this project we have developed a flask application for sentiment analysis.
Download the code and run flaskapp.py from the main directory.

The model is trained and saved as pkl files. Along with that the stop words and vectors are also loaded in the falsk app.

# Model Creation

Step1. Import the necessary libraries
Step2. Reading the .csv file from Pandas 
Step3. Cleaning the text data
Step4. Splitting our data for training and testing
Step5. Transforming words into feature vectors
Step6. Creating the model and checking the score on training and test data


# Create a Web Application

Step1. Serializing fitted scikit-learn estimators
Step2. Importing Flask library, Gunicorn
Step3. Set up the html files for the sentiment analysis app
Step4. Set up style css file for the application
Step6. Test your application on the local server

# Deploying the web application on Google Cloud Run

Step1. Upload all the files in the project into google bucket
Step2. Copy all the bucket files into the specifi working directory
Step3. Create a dockerfile specifiying the port and all the dependencies
Step4. Using gcloud build command, craete a docker image in the container registry
Step5. Deploy the image on the cloud run which is a serverless infrastructure
Step6. Visit the webpage url provided by the GCP and enjoy your developed sentiment analysis application
