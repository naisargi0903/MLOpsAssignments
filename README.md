# MLOps Assignments


This repository contains assignments focused on MLOps concepts and tools, including KServe, Kubeflow, Streamlit, and Observability. Each assignment folder contains source code, deployment files, and scripts tailored to specific use-cases in the MLOps lifecycle.

---

## Directory 

### 🔹'DevOps'


AWS, Docker, and Kubernetes form the backbone of modern MLOps workflows by streamlining development, deployment, and scaling of ML models. They enable containerization (via Docker), orchestration (via Kubernetes), and cloud-native automation (via AWS), ensuring reliable and reproducible ML pipelines.


---

### 🔹`Kserve/`


A machine learning model deployed using **KServe** on Kubernetes for predicting crop diseases.
- Includes: `disease_prediction.py`, `inference.py`, `deployment.yaml`, `Dockerfile`, trained model & encoders.
- Features: Dockerization, custom inference logic, KServe REST deployment.

---

### 🔹`Kuberflow/`



A Kubeflow pipeline to predict **crop disease risk** based on environmental features.
- Shows end-to-end workflow: data processing, model inference, and visualization using pipeline components.

---

### 🔹 `Observability/`


Basic observability assignment demonstrating **Elasticsearch + Kibana** setup.
- Includes configuration and data indexing steps to monitor logs/metrics.

---

### 🔹 `Python/`

#### • 'Assignment_1/'
Python script showcasing basic automation or scripting tasks.
Useful for learning scripting basics before full ML pipelines.

#### • 'Assignment_2/'
Flask-based web app featuring:

images/, templates/, static/ — assets for the web frontend

Web interface for prediction or visualization (likely related to ML model)

#### • 'Assignment_3/'
Data analysis on wine quality dataset (winequality-red.csv).
Python script (Assignment3.py) demonstrates data visualization and basic ML techniques.

#### • 'Assignment_4/'
Customer segmentation using Mall Customer dataset (Mall_Customers.csv).
Python script (Assignment4.py) applies clustering techniques like K-Means.

####• 'Assignment_5/'
Sales data analysis with supermarket sales dataset (supermarket_sales.csv).
Python script (Assignment5.py) includes data preprocessing, analysis, and sales visualization (sales_over_time.png).

####• 'Assignment_6/'
Iris flower classification using the Iris dataset (Iris.csv).
Python script (Assignment6.py) performs basic machine learning model training and evaluation.

---

### 🔹 `Streamlit/`

#### • `Assignment1_Visualizing CSV Data/`
Streamlit-based dashboard to visualize uploaded CSV files using interactive charts.
- Allows users to upload any dataset and explore it visually.

#### • `Assignment2_Weather_App/`
A weather dashboard built with Streamlit fetching real-time data from an external API.
- Users can input a city and get weather details like temperature, humidity, etc.

#### • `Assignment3_Sentiment_Analysis/`
Sentiment analysis web app using NLP libraries and Streamlit UI.
- Input a sentence and get sentiment prediction (Positive/Negative).

## 🛠 Requirements

- Docker, Kubernetes
- KServe, Kubeflow Pipelines
- Python 3.8+
- Streamlit, Flask
- Elasticsearch (for Observability)

---

