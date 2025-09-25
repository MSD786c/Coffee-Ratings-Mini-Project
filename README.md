#☕ Coffee Ratings EDA Project
<p align="center"> <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-blue?logo=pandas" alt="Pandas Badge"/> <img src="https://img.shields.io/badge/Seaborn-Visualization-green?logo=python" alt="Seaborn Badge"/> <img src="https://img.shields.io/badge/Matplotlib-Charts-orange?logo=python" alt="Matplotlib Badge"/> <img src="https://img.shields.io/badge/Google%20Colab-Notebook-yellow?logo=googlecolab" alt="Colab Badge"/> </p>
📖 Project Overview

This project explores the Coffee Quality Database provided by the Coffee Quality Institute (CQI).
The dataset contains expert reviews of Arabica coffee beans from around the world, scored across multiple categories such as Aroma, Flavor, Acidity, Body, and Overall Quality.

The goal of this project is to perform Exploratory Data Analysis (EDA) to uncover:

Which countries consistently produce the highest-rated coffee

The relationships between sensory features (e.g., Aroma, Flavor)

Distribution of coffee quality scores

Outliers and interesting insights

📂 Dataset

Source: Coffee Quality Database (Kaggle)

File Used: arabica_data_cleaned.csv

Key Features:

Country.of.Origin – Country producing the coffee

Aroma, Flavor, Acidity, Body – Sensory scores (0–10)

Overall – Overall rating given by experts

🔎 Analysis Steps

Data Loading & Inspection – Checking dataset structure & types

Data Cleaning – Handling missing values & duplicates

Exploratory Analysis

Top producing countries

Average ratings per country

Correlations between attributes

Visualizations

📊 Bar chart: Top 10 countries by average rating

🔥 Heatmap: Correlation between features

📈 Histogram: Distribution of scores

☁️ Scatter plot: Aroma vs Overall

📊 Key Insights

🌍 Countries like Ethiopia, Kenya, and Colombia rank among the highest for coffee ratings

☕ Aroma and Flavor are the strongest predictors of the Overall score

📉 Distribution shows that most coffees score between 80–90 points, with few outliers

📸 Sample Visualizations
<p align="center"> <img src="plots/top_countries.png" width="45%" alt="Top Countries"> <img src="plots/heatmap.png" width="45%" alt="Feature Correlation"> </p>
⚙️ Tech Stack

Python – Pandas, NumPy

Visualization – Matplotlib, Seaborn

Notebook – Google Colab

Version Control – Git & GitHub

🚀 How to Run

Clone this repo:

git clone https://github.com/your-username/coffee-ratings-eda.git
cd coffee-ratings-eda


Install requirements:

pip install pandas matplotlib seaborn


Open the Jupyter/Colab notebook:

jupyter notebook coffee_ratings_eda.ipynb

🙌 Acknowledgments

Dataset by Coffee Quality Institute (CQI)

Inspiration from specialty coffee research & sensory analysis

🔥 If you love coffee & data, drop a ⭐ on this repo!
