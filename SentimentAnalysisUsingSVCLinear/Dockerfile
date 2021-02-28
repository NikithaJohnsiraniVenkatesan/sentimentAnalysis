# lightweight python
FROM python:3.8-slim-buster

# Copy local code to the container image.
ENV APP_HOME /app
WORKDIR $APP_HOME
COPY . ./

# Install dependencies
RUN pip install joblib WTForms numpy==1.19.2 pandas==1.2.1 seaborn==0.11.0 nltk==3.5 scikit-learn==0.22.2 sklearn Flask gunicorn healthcheck google-cloud-logging
EXPOSE 8080


# Run the flask service on container startup
CMD exec gunicorn --bind :$PORT --workers 1 --threads 8 flaskapp:app
