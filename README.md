# Earthquake Magnitude Prediction

**Author:** Kaustav Dutta  
**Roll Number:** 25SCS1003000653  
**College:** IILM University

## Project Overview
This project is a machine learning analysis of global seismic activity aimed at forecasting earthquake intensity. It utilizes a dataset of global seismic events to predict earthquake magnitudes based on geographical location, depth, and impact scores.

## Dataset
The project uses `earthquake_dataset.csv`, which contains 16,944 records of seismic activity. Key features include:
* **Location:** City, Country, Latitude, and Longitude.
* **Time:** Date and Time (UTC).
* **Seismic Details:** Earthquake Magnitude, Depth (km), and Impact Score.

## Project Workflow
The analysis is conducted through a Jupyter Notebook (`earthquake_prediction.ipynb`) and follows these steps:

1. **Data Loading and Inspection:** Loading the CSV and generating summary statistics to understand data distribution.
2. **Cleaning and Preprocessing:** * Combining Date and Time into a single Timestamp.
    * Correcting physically impossible negative depth values.
    * Handling high-cardinality categorical data.
3. **Feature Engineering & Encoding:**
    * Extracting time-based features (Year, Month, Day, Hour, Day of Week).
    * Applying One-Hot Encoding to the 'Country' column.
    * Scaling numerical features (Latitude, Longitude, Depth) using `StandardScaler`.
4. **Exploratory Data Analysis (EDA):** Visualizing earthquake magnitude distribution, depth trends, and correlation heatmaps.

## Technologies Used
* **Python:** Primary programming language.
* **Pandas:** Data manipulation and cleaning.
* **Scikit-learn:** Feature scaling and preprocessing.
* **Matplotlib & Seaborn:** Data visualization and statistical plotting.
* **Pandas:** Data manipulation and cleaning.
