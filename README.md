# PhotoBioReactor(PBR)

Ensemble and Sequence Modeling for Monitoring Autotrophic Single-Cell Cultivation

# Overview
Welcome to the PBR repisority. The goal of this work is to explore methods for predicting key quality indicator variables such as dissolved oxygen and optical density cosidering algorithmic invistigation for the sake of accuracy and computatial time. In-house experimental data  and codes for different machin learning algorithms are available in this reposority.

# Files 
1- **Datasets**
- Run1.Xlsx includes the data of the first experiment
- Run2.Xlsx includes the data of the second experiment
- Run3.Xlsx includes the data of the third experiment

2. **Python Scripts**
PBR.ipynb
This Jupyter Notebook contains all codes for predicting dissolved oxygen as a quality indicator variable. The notebook includes the following sections:

- Dataset Overview: Provides a summary and visualization of the dataset.
- Pair Plot: Displays relationships between variables in the dataset.
- Correlation Matrix: Analyzes the relationships between all features.
- Autocorrelation: Examines temporal dependencies in the data.
- Deep Learning: Implements a Long Short-Term Memory network for sequence modeling.
- Ensemble Learning:
- Base Models: Includes Multiple Linear Regression (MLR), Decision Tree Regression (DTR), Support Vector Regression (SVR), and General Regression Neural Network (GRNN).
- Meta Models:
- Mean-based ensemble.
- Sum-based ensemble.
- RidgeCV-based ensemble.
PBROD.ipynb
This Jupyter Notebook contains all codes for predicting optical density as a quality indicator variable. The notebook includes the following sections:

Dataset Overview: Provides a summary and visualization of the dataset.
- Pair Plot: Displays relationships between variables in the dataset.
- Correlation Matrix: Analyzes the relationships between all features.
- Autocorrelation: Examines temporal dependencies in the data.
- Deep Learning: Implements a Long Short-Term Memory network for sequence modeling.
- Noise Addition: Adds noise to the dataset for robustness evaluation.
- Model Evaluation: Evaluates the model on the modified dataset.
- Running Time Analysis
The running times for both Ensemble Learning and Deep Learning (LSTM) models have been investigated and included in the analysis to provide insights into their computational efficiency.

# Additional Information
- For more details on the simulation setup and parameters, refer to the article.
- For any questions or issues, please contact seso@kt.dtu.dk or morebo@kt.dtu.dk.

Thank you for using the PBR respository
