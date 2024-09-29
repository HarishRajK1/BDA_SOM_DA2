# BDA_SOM_DA2
Self-Organizing Map (SOM) on Depression Data

Overview
This implementation applies a Self-Organizing Map (SOM) to cluster individuals in the dataset based on various features like lifestyle, health, and personal details. SOMs are used for identifying patterns and visualizing high-dimensional data.

How to Run the Project

Software Requirements:
Python 3.x

Required libraries:
pandas (for data handling)
numpy (for numerical operations)
sklearn (for preprocessing the data)
MiniSom (for implementing the Self-Organizing Map)
matplotlib (for visualizations)

To install the necessary libraries, use:
pip install pandas numpy scikit-learn MiniSom matplotlib

Hardware Requirements:
Any modern machine with a minimum of 4GB RAM. For large datasets, 8GB+ RAM is recommended.
At least 1GB of free disk space.

Steps to Execute:
Download the Dataset: Ensure the dataset (depression_data.csv) is in the working directory.
Run the Python Script: Execute the Python script to preprocess the data, train the SOM, and visualize the results.

Sample execution:
python som_depression.py

Output:
A heatmap visualization representing the clusters formed by SOM.
Additional information like distance maps for interpretation.

Data Preprocessing:
Categorical features (e.g., Marital Status, Education Level) are converted into numerical form using One-Hot Encoding.
Numerical features (e.g., Age, Income) are scaled using standard scaling.

SOM Training:
The SOM is initialized with a 10x10 grid and trained using the preprocessed dataset.
The final output is a distance map, which visualizes the clusters and patterns.
