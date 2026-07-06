# 🚀 SpaceX Falcon 9 First Stage Landing Prediction
### IBM Applied Data Science Capstone Project

## Overview

This repository contains my final capstone project for the **IBM Data Science Professional Certificate**. The project applies the complete data science methodology to analyze SpaceX launch data and build machine learning models capable of predicting whether the **Falcon 9 first stage will land successfully**.

Since the first stage of the Falcon 9 rocket can be recovered and reused, predicting landing success is valuable for estimating launch costs and understanding the factors that contribute to successful missions.

---

## Business Problem

SpaceX has significantly reduced the cost of space launches by successfully recovering and reusing the Falcon 9 first stage. Competitors and customers often want to estimate launch costs before a mission takes place.

The objective of this project is to predict whether the Falcon 9 first stage will land successfully based on launch characteristics such as payload, launch site, orbit, and mission details.

---

## Project Objectives

- Collect launch data from the SpaceX REST API
- Scrape additional launch information from Wikipedia
- Clean and preprocess the collected data
- Store and query data using SQL
- Perform Exploratory Data Analysis (EDA)
- Create interactive visualizations using Plotly and Folium
- Build and evaluate multiple machine learning classification models
- Identify the best-performing predictive model

---

## Dataset

The project combines data from multiple sources:

- **SpaceX REST API**
- **Wikipedia Launch Records**
- Processed datasets generated during the project

The datasets include information such as:

- Flight Number
- Launch Site
- Payload Mass
- Orbit
- Booster Version
- Launch Outcome
- Landing Outcome
- Mission Date

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Plotly
- Folium
- Scikit-learn
- BeautifulSoup
- Requests
- SQLite / SQL

---

## Repository Structure

```
├── Data Collection API.ipynb
├── Web Scraping.ipynb
├── Data Wrangling.ipynb
├── SQL Analysis.ipynb
├── Exploratory Data Analysis.ipynb
├── Interactive Visual Analytics.ipynb
├── Machine Learning Prediction.ipynb
├── Presentation.pdf
├── README.md
└── data/
```

---

## Project Workflow

### 1. Data Collection

Collected launch information using:

- SpaceX REST API
- Web scraping with BeautifulSoup

---

### 2. Data Wrangling

Performed preprocessing tasks including:

- Handling missing values
- Feature engineering
- Data cleaning
- Data transformation

---

### 3. Exploratory Data Analysis

Investigated relationships between landing success and variables including:

- Launch Site
- Payload Mass
- Orbit Type
- Booster Version
- Flight Number

EDA was performed using:

- SQL queries
- Pandas
- Matplotlib
- Plotly

---

### 4. Interactive Visualizations

Created interactive dashboards to analyze launch outcomes.

Visualizations include:

- Launch success by launch site
- Payload mass vs. landing success
- Launch site maps
- Launch location clustering
- Success rate by orbit

Libraries used:

- Plotly Express
- Folium

---

### 5. Machine Learning

Several classification algorithms were trained and evaluated to predict landing success.

Models implemented include:

- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree Classifier
- K-Nearest Neighbors (KNN)

Hyperparameter tuning was performed using GridSearchCV.

Models were evaluated using:

- Accuracy
- Confusion Matrix
- Cross-validation

---

## Results

The machine learning models demonstrated that launch characteristics such as payload mass, orbit type, and launch site have a significant impact on landing success.

After comparing multiple algorithms, the best-performing model achieved strong predictive performance and can be used to estimate the probability of a successful Falcon 9 first-stage landing.

---

## Key Insights

- SpaceX has achieved consistently high landing success rates over time.
- Certain launch sites produce higher landing success rates.
- Payload mass influences landing probability.
- Orbit type plays an important role in predicting mission outcomes.
- Machine learning models can accurately classify landing success using historical launch data.

---

## Future Improvements

Potential enhancements include:

- Incorporating weather conditions
- Including launch vehicle telemetry
- Using ensemble learning methods such as Random Forest or XGBoost
- Deploying the model as a web application using Flask or Streamlit
- Automating data updates from the SpaceX API

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/spacex-falcon9-landing-prediction.git
```

Navigate to the project directory:

```bash
cd spacex-falcon9-landing-prediction
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

---

## Example Requirements

```
pandas
numpy
matplotlib
plotly
folium
scikit-learn
requests
beautifulsoup4
jupyter
```

---

## Skills Demonstrated

- Data Collection
- REST API Integration
- Web Scraping
- Data Wrangling
- SQL
- Exploratory Data Analysis
- Data Visualization
- Interactive Dashboards
- Machine Learning
- Model Evaluation
- Feature Engineering

---

## Author

**Carlos Andres Hernandez**

IBM Data Science Professional Certificate

GitHub: https://github.com/hercandres

LinkedIn: https://www.linkedin.com/in/carlos-hernandez2027/

---

## Acknowledgments

This project was completed as part of the **IBM Data Science Professional Certificate** offered through Coursera.

Special thanks to IBM Skills Network for providing the project framework, datasets, and learning materials.

---

## License

This project is licensed under the MIT License.

Feel free to fork this repository, submit issues, or contribute improvements.
