# Battery Degradation and SOH Prediction

This project investigates machine learning methods for predicting battery State of Health (SOH) and modeling degradation trajectories using publicly available datasets, including Wenzhou and HNEI. The main objective is to evaluate whether shared degradation patterns across multiple batteries can improve predictions when only a limited number of initial cycles are available.

The methodology explores Support Vector Regression (SVR), population-level mean degradation curves, residual learning, and hyperparameter optimization. Experiments evaluate prediction accuracy across different training-window sizes, comparing individual models with approaches that incorporate information from multiple batteries. Data preprocessing, visualization, and statistical evaluation are also performed to investigate model performance and generalization.
