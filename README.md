# Athlete Performance Modeling with Feature Store and Carbon Tracking
This project explores how to build a reproducible ML pipeline with feature versioning and environmental impact tracking.

## Project Summary
1. Loaded and cleaned athlete performance data from CSV.

2. Created two versions of feature sets using Feast, a feature store framework.

3. Trained and evaluated RandomForestRegressor models with two different hyperparameter settings for each feature version (total of 4 experiments).

4. Logged metrics including RMSE and R² for comparison.

5. Used CodeCarbon to measure and log the carbon emissions of each training run.

6. Visualized experiment results and carbon footprint using matplotlib and seaborn.

## Tools Used
1. Google Colab

2. Python (pandas, scikit-learn, numpy)

3. Feast (Feature Store)

4. CodeCarbon (Carbon Emissions Tracker)

5. Matplotlib & Seaborn (Visualization)

## Output Files
1. experiment_results_with_emissions.csv: Summary of all 4 experiments.

2. emissions_log/: Raw CodeCarbon logs for each experiment.

Notebook (.ipynb) includes all preprocessing, training, and visualization steps.
