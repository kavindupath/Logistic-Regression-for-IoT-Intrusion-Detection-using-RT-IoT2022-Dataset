# Logistic-Regression-for-IoT-Intrusion-Detection-using-RT-IoT2022-Dataset
This project applies logistic regression to classify and detect intrusion attacks in IoT (Internet of Things) networks using the RT-IoT 2022 dataset. It includes exploratory data analysis, preprocessing, and multiple logistic regression models with different regularization techniques.

## Dataset
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/942/rt-iot2022)
- **Citation:** Sharmila & Nagapadma (2024)
- 
## Feature preprocessing:
- Handling categorical features (proto, service)
- Label encoding attack types as normal (0) or malicious (1)
- Train-test split (80/20)
- Feature scaling using StandardScaler

## Models Developed
1. Logistic Regression with:
   - No regularization
   - L2 (Ridge)
   - L1 (Lasso)
   - Elastic Net (L1 + L2)
2. Logistic Regression with **PCA** for dimensionality reduction

## Tools & Libraries
- Python 3.x
- `scikit-learn`
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `ucimlrepo` for fetching the dataset

## Evaluation
- Accuracy and classification metrics
- Visualization of the dataset and PCA results
- Analysis of model coefficients and feature importance


