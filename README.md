# Deploying sentiment analysis Flask app on Google cloud run

In this project we have developed a flask application for sentiment analysis.
Download the code and run flaskapp.py from the main directory.

The model is trained and saved as pkl files. Along with that the stop words and vectors are also loaded in the falsk app.

# Model Creation

Step1. Import the necessary libraries<br />
Step2. Reading the .csv file from Pandas <br />
Step3. Cleaning the text data<br />
Step4. Splitting our data for training and testing<br />
Step5. Transforming words into feature vectors<br />
Step6. Creating the model and checking the score on training and test data<br />


# Create a Web Application

Step1. Serializing fitted scikit-learn estimators<br />
Step2. Importing Flask library, Gunicorn<br />
Step3. Set up the html files for the sentiment analysis app<br />
Step4. Set up style css file for the application<br />
Step6. Test your application on the local server<br />

# Deploying the web application on Google Cloud Run

Step1. Upload all the files in the project into google bucket<br />
Step2. Copy all the bucket files into the specifi working directory<br />
Step3. Create a dockerfile specifiying the port and all the dependencies<br />
Step4. Using gcloud build command, craete a docker image in the container registry<br />
Step5. Deploy the image on the cloud run which is a serverless infrastructure<br />
Step6. Visit the webpage url provided by the GCP and enjoy your developed sentiment analysis application<br />
