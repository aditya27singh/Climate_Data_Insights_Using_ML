# Climate and Sustainability Trends: Clustering & Anomaly Detection

## Abstract
This project investigates global sustainability patterns by analyzing CO₂ emissions, renewable energy share, GDP per capita, and population across countries and years. Building on my first project (data cleaning & visualization), this second phase applies unsupervised learning (K-Means clustering & anomaly detection) to uncover hidden structures in the data.

## Overview
This project is the second installment in a structured research series designed as part of my journey towards AI/ML research internships.

1. Project 1: Climate and Sustainability Trends — Data Cleaning, Exploration, and Visualization
2. Project 2 (this project): Clustering and Anomaly Detection — Unsupervised Learning for Pattern Discovery

In this project, I extend my earlier exploratory analysis with clustering and anomaly detection to uncover latent patterns in sustainability data.

## Key Contributions
 1. Optimal Clustering: Evaluated multiple values of k using Silhouette Score, selecting k = 3 (score = 0.31) as the most meaningful segmentation.
 2. Cluster Insights: Identified distinct groups of countries (e.g., high-emission economies vs. mid-industrializing regions vs. developed transitional economies).
 3. Anomaly Detection: Flagged outlier countries/years with unusual sustainability indicators, offering insights into unique policy or development trajectories.
 4. Scalable Pipeline: Data cleaning, clustering, and anomaly detection are structured for extension into predictive ML modeling.

## Key Findings
  1. Countries are naturally grouped into three clusters:
      * Mid-Industrializing Economies – moderate GDP, growing CO₂ emissions, and relatively low renewable energy adoption.
      * Developed Transitional Economies – strong GDP per capita, mixed energy strategies, and visible progress in reducing emissions.
      * High-Emission Economies – advanced economies with very high CO₂ emissions despite robust economic growth.
  3. Renewable energy share played a central role in distinguishing clusters.
  4. Anomaly detection highlighted countries experiencing rapid shifts in sustainability metrics or facing unique developmental pathways.

## Why This Matters
Understanding sustainability clusters offers a data-driven lens for comparing countries, evaluating progress, and identifying leaders/laggards. This framework can be extended into forecasting models to inform global policy and research on climate change.

## Next Steps
 1. Extend clustering to time-series forecasting of sustainability indicators.
 2. Integrate deep learning models for CO₂ emission prediction.
 3. Compare results against real-world policy interventions.

## Tech Stack
 1. Python: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
 2. Data Source: Our World in Data (CO₂, GDP, Renewable Energy, Population)

## License
Released under MIT License

