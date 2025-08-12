# Customer Segmentation for a National Gym Chain

This project performs **customer segmentation** using clustering techniques to help a national gym chain tailor marketing strategies and personalise services. It was completed as part of **BUSA8001 – Applied Predictive Analytics** at Macquarie University.

## Overview
Using membership data from **2,000 individuals**, the project applies **K-Means++** and **Agglomerative Clustering** to uncover distinct customer segments based on:
- Demographics (age, gender, marital status, education)
- Socio-economic attributes (annual income, occupation)
- Settlement size

## Workflow
1. **Exploratory Data Analysis (EDA)** – Summary statistics, distribution analysis, correlation heatmaps, and pair plots.
2. **Data Preparation** – Standardisation of numerical variables (Age, Income).
3. **Cluster Selection** – Elbow Method and Silhouette Analysis to determine optimal k.
4. **Clustering** – Comparison between K-Means++ and Agglomerative Clustering.
5. **Segment Profiling** – Interpretation and naming of segments.
6. **Marketing Recommendations** – Targeted strategies for each segment.

## Key Segments (K-Means++)
- **Young Budget-Conscious** – Younger, lower-income, mostly male, small-city residents.
- **Senior Premium** – Older, higher-income, well-educated professionals in big cities.
- **Working Middle Tier** – Mid-aged, steady-income individuals valuing practicality and loyalty perks.

## Marketing Strategies
- **Young Budget-Conscious** – Student discounts, referral bonuses, social media engagement.
- **Senior Premium** – Premium services, wellness packages, private sessions.
- **Working Middle Tier** – Bundled offers, family plans, loyalty rewards.

## Tools
- **Python** – `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`
- **Jupyter Notebook** for analysis and visualisation

## Repository Contents
- `Assignment2_Coding.ipynb` – Full Python implementation
- `data.csv` – Membership dataset
- `data legend.csv` – Data dictionary

---
**Author**: Muhammad Pasha Arrighi Effendi  
