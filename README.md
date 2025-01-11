# Cloud-Computing-Project
Elevator Predictive Maintenance Dashboard, using GCP cloud native with Splunk. 
# Elevator Predictive Maintenance Dashboard
This project develops a machine learning-based predictive maintenance system for elevators, utilizing Google Cloud Platform (GCP) for cloud-native deployment and Splunk for dynamic data visualization. The system predicts when an elevator will require maintenance by analyzing historical data, such as elevator revolutions, humidity, and vibration parameters.

## Key Features
- **Predictive Maintenance:** Uses machine learning models to predict elevator maintenance needs, reducing downtime and operational costs.
- **Google Cloud Platform:** Leverages GCP tools such as Vertex AI for model deployment, Cloud Storage for data storage, and batch prediction capabilities.
- **Splunk Integration:** Visualizes the results and insights in real-time using Splunk dashboards, helping maintenance teams make data-driven decisions.
- **Random Forest Algorithm:** The primary machine learning algorithm used for training the predictive model.

## Project Structure
As shown on the .ipynb file the code goes with:
1. Data Preprocessing and Feature Selection
2. Model Development
3. Model Deployment in Vertex AI and Batch Prediction
4. Data Visualization with Splunk

## Tools and Libraries Used
- Google Colab: Used for coding and interacting with Google Cloud services.
Google Cloud Services:
- google-cloud-storage: For managing data in Cloud Storage.
- google-cloud-aiplatform: For interacting with Vertex AI.
- scikit-learn: For building the machine learning model (Random Forest).
- pandas: For data manipulation and preprocessing.
- joblib: For saving and loading trained models.
- Splunk: For data visualization and creating interactive dashboards.

The project contain a report that shows a several screenshots for the processes in Vertex AI and Splunk
but its not shareable here.
Hope the Splunk Dashboard source code and the final look of the dashboard on the pdf file helps you with the experience

There are some YouTube videos that helps me in this Project:
- https://www.youtube.com/watch?v=Lw55J-koBT4
- https://www.youtube.com/watch?v=MHePOgTzTpw&t=696s
- https://youtu.be/TyNWXOn41rI
- https://youtu.be/NUk22umpuGI
