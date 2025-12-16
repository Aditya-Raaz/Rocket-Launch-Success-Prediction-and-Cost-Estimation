# 🚀 Rocket-Launch-Success-Prediction-and-Cost-Estimation

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![Dash](https://img.shields.io/badge/Dash-Plotly-orange?style=for-the-badge&logo=plotly&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Sklearn-Machine_Learning-yellow?style=for-the-badge&logo=scikitlearn&logoColor=white)

This project aims to predict the success of SpaceX's Falcon 9 first-stage landing. By predicting whether the first stage will land successfully, we can estimate the cost of a launch. This analysis involves the entire Data Science pipeline: data collection, wrangling, EDA, interactive visualization, and machine learning classification.

## 📂 Project Structure & Workflow

The analysis is broken down into the following steps corresponding to the notebooks in this repository:

### 1. Data Collection & Wrangling
* **`spacex-data-collection-api.ipynb`**: Fetches real-time launch data from the SpaceX API.
* **`spacex_datawrangling.ipynb`**: Cleans the dataset, handles missing values, and prepares features for analysis.
* **`dataset_part_1.xls` / `dataset_part_3.xls`**: The processed datasets used throughout the project.

### 2. Exploratory Data Analysis (EDA)
* **`jupyter-labs-eda-sql-coursera_sqllite.ipynb`**: Uses **SQL** queries to analyze the landing outcomes stored in the `my_data1 (2).db` database.
* **`edadatavis.ipynb`**: Visualizes success rates and trends using Matplotlib and Seaborn.
* **`launch_site_location.ipynb`**: Uses **Folium** maps to visualize launch sites and the proximity of success/failure landings.

### 3. Interactive Visual Analytics
* **`spacex_dash_app.ipynb`**: A fully interactive web dashboard built with **Dash** and **Plotly**. It allows users to filter by launch site and payload mass to see success correlations.

### 4. Machine Learning Prediction
* **`Part5.ipynb`** (and `ml_model_data.xls`): The final step where we train various classification models (Logistic Regression, SVM, Decision Tree, KNN) to predict landing success.

## 📊 Key Results
* Identified the best launch sites for successful landings.
* Built a dashboard to visualize the correlation between payload mass and success rate.
* Achieved high predictive accuracy using the Classification Models.

## 🛠️ Technologies Used
* **Libraries:** `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `Folium`, `Dash`, `Scikit-Learn`
* **Database:** SQLite (`my_data1 (2).db`)

## 🚀 How to Run the Dash App
To run the interactive dashboard locally:
1.  Open `spacex_dash_app.ipynb`.
2.  Install Dash: `pip install dash dash-html-components dash-core-components plotly`.
3.  Run the code cells. The dashboard will launch on your local server (usually `http://127.0.0.1:8050/`).

## 👤 Author
**Aditya Raaz**
