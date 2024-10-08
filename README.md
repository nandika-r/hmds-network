# hmds-network
This repository contains the code for my MRes dissertation project in Healthcare Technologies at King's College London. The project involves developing a neural network to classify hyperkinetic movement disorders (HMDs) using video data.

# **Overview**
The HMDS-Network is designed to process joint coordinates extracted from video frames using OpenPose, organizing them into a spatiotemporal matrix for analysis. The repository includes two Google Colab notebooks:

Training & Cross-Validation Notebook:
This notebook features the preprocessing code, network structure (spatial and temporal components connected to a final classification branch), and the complete training loop with cross-validation.

![image](https://github.com/user-attachments/assets/b0bbcd14-7b02-4c03-8efc-ae766af6b75b)

Attention Mapping Notebook:
An alternative notebook that implements visual attention score mapping, providing insights into the network's focus during classification.
Additionally, I plan to upload other development versions of the code, such as the hyperparameter tuning grid search.

# Disclaimer
I'm relatively new to coding and machine learning, having started learning just a year ago. The code may be complex or lack sufficient comments, as I haven't had the time to refine or document it extensively since submitting my dissertation. Additionally, despite attempts to standardize the training results (e.g., using seeding), minor variations exist in the confidence intervals and p-values of the model metrics across re-runs of the training loop for the cross-validation (about 5%).


If you have any questions, suggestions, or need further clarification, feel free to email me at nandika.ramamurthy@kcl.ac.uk.
