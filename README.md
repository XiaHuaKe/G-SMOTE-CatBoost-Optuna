## Introduce
An advanced **oversampling framework (G-SMOTE)** integrating Gaussian Mixture Models (GMM) for noise filtering and directional sample generation, coupled with a **CatBoost-based ensemble model** optimized through Optuna for seismic landslide susceptibility assessment.

The framework combining:
-  **G-SMOTE**: Gaussian Mixture Model-based oversampling with noise filtering
-  **CatBoost**: Gradient boosting model
-  **Optuna**: Automated hyperparameter tuning
-  **Benchmarking**: Comparative analysis with 8 ML models

## Dataset example

The data contains **11 features** and **1 label column**. Here are the first 3 sample records:
| dem | slope | aspect | curvature | dis_river | dis_road | dis_fault | ndvi | ndwi | rainfall | lithology |  S/N  |
|-----|-------|------- |-----------|-----------|----------|-----------|------|------|----------|-----------|-------|
| 1909      | 3.321429968  |  7      | 0.333332986      |    1       |    1     |       7    |   0.188406006   |   -0.205881998   |   16.99189949       | 1        | 1     |
| 1533     | 26.28409958  |    2    | 1     |     10      |     6     |     1      | 0.555555999     |  -0.465115994    |    17.3010006      | 12         | 1     | 
| 2504    | 11.54629993  |    7    | 0     |      1     |      5    |     1      |   0.507246017   |   -0.485713989   |     15.8987999     | 3         | 0     |
