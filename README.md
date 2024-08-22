## Regression Models to predict Dissolved Inorganic Carbon in California Coastal Ecosystems

### [Link to Blog (with Python code)](https://linusghanadan.github.io/blog/2024-4-3-post/dic-ml-models.html)

### Repository Contents
    dic-ml-models
    └───data
        │   water_samples.csv
    └───images
        │   Correlation heatmap of features: correlation-heatmap.png
        │   Feature importances in best-performing model: feature-importance.png
        │   RMSE comparison of different models: model-comparison.png
    │   README.md
    │   .ipynb

### Context

This project was completed for my Machine Learning class, taken as part of my Master's program at UC Santa Barbara. Provided with data and questions, I carried out this analysis using appropriate machine learning techniques.

### Question

How can machine learning models, specifically random forest and stochastic gradient boosted tree models, be used to predict Dissovled Inorganic Carbon (DIC) in California coastal ecosystems based on ocean chemistry features?

### Analysis Summary

Used data from a marine ecosystem research program to build three models (single decision tree, random forest, and stochastic gradient boosted trees) that predict dissolved inorganic carbon (DIC) based on other ocean chemistry features (e.g., sulfur trioxide concentration) that were also measured during water sampling. Developed visualizations comparing root mean squared error (RMSE) among the three models and analyzing feature importances in the best performing model.

### Datasets
- CSV of DIC and other ocean chemistry features in water samples from California coastal ecosystems

### Data References
- California Cooperative Oceanic Fisheries Investigations (CalCOFI). "Bottle Database". https://calcofi.org/data/oceanographic-data/bottle-database/
