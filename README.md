# 🚀 SpaceX Falcon 9 Landing Prediction

## 📜 Project Overview
This capstone project is the final project of the **IBM Data Science** course. The goal of the project is to create a machine learning pipeline that predicts whether the first stage of the Falcon 9 rocket will land successfully, thereby estimating the cost savings for a rocket launch.

SpaceX advertises Falcon 9 rocket launches at a cost of $62 million, compared to other providers charging upwards of $165 million. The key to SpaceX's savings is the reuse of the first stage of the rocket. By predicting whether the first stage will land, we can provide insights to alternate companies bidding against SpaceX in future rocket launches.

## 🔍 Problem Statement
- What factors determine if the rocket's first stage will land successfully?
- How do various features interact to influence the success rate of the landing?
- What operational conditions are needed to ensure a successful landing program?

## 🗂️ Project Structure
- **01_Data Collection API.ipynb**: Data collection using APIs to retrieve launch data.
- **02_Data Collection with Web Scraping-checkpoint.ipynb**: Supplementary data collection using web scraping techniques.
- **03_Data Wrangling.ipynb**: Data preprocessing and cleaning to prepare for analysis and modeling.
- **04_EDA with SQL.ipynb**: Exploratory data analysis using SQL queries.
- **05_EDA with Data Visualization.ipynb**: Visual exploration of data to uncover trends and patterns.
- **06_Visual Analytics with Folium.ipynb**: Geospatial visualization of launch data using `Folium`.
- **07_Machine Learning Prediction.ipynb**: Building and evaluating machine learning models to predict successful rocket landings.
- **app.py**: The main application file that contains the Dash app, layout, and callback functions.

## 🛠️ Tools and Technologies
- **Python**: For scripting and machine learning model development.
- **APIs & Web Scraping**: To collect launch data from multiple sources.
- **Pandas, Numpy**: For data manipulation and wrangling.
- **SQL**: For querying the data and performing EDA.
- **Matplotlib, Seaborn, Plotly**: For data visualization.
- **Folium**: For geospatial analysis and mapping.
- **Scikit-learn**: For machine learning and model building.
- **Dash**: For building the web-based dashboard.
- **Plotly**: For creating interactive visualizations.

## 🚀 Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/Hamadzki/IBM_Data_Science_Capstone_Project.git
