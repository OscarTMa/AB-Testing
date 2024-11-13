# AB-Testing

This project performs A/B testing on a dataset from Kaggle using Python. It includes the essential steps for conducting an A/B test, from loading and exploring data to statistical analysis and results interpretation. The notebook is designed to be run on Google Colab, making it accessible and easy to collaborate on.

## 1. Introduction

What is A/B Testing?
A/B Testing, or split testing, is an experimental technique that compares two versions of an item (like a web page or product design) to determine which one performs better based on a specific metric (e.g., conversion rate). By randomly dividing users into two groups (control and treatment) and showing each group a different version, A/B Testing helps identify statistically significant improvements in performance.

Project Objective
The goal of this project is to conduct an A/B test on a Kaggle dataset, applying statistical methods to determine if there’s a significant difference between the control and treatment groups regarding a key metric—conversion rate, in this case. This notebook includes:

Data loading from Kaggle.
Data exploration.
A/B Testing analysis.
Result visualization.
Interpretation of analysis results.

## 2. Project Structure

The project’s folder and file structure is organized as follows:

ab-testing-project/                                                                           
├── data/                   # Folder to store data files downloaded from Kaggle                                                                           
│   └── ab-testing.csv      # Downloaded dataset file                                                                           
├── notebooks/              # Folder for Jupyter or Colab notebooks                                                                           
│   └── ab_testing.ipynb    # Main A/B testing notebook                                                                           
├── results/                # Folder for storing results, graphs, and visualizations                                                                           
├── README.md               # Project overview                                                                           
├── LICENSE                 # License file (MIT)                                                                           
└── requirements.txt        # Project dependencies                                                                           

## 3. Notebook Section Explanations

Install Dependencies and Download Data
This section installs necessary libraries and downloads the dataset from Kaggle, saving it in the data/ folder.

Load Libraries and Dataset
Here, essential libraries are imported, and the dataset CSV file is loaded into a DataFrame for analysis.

Exploratory Data Analysis (EDA)
EDA helps understand the dataset structure and quality. It includes checking data types, detecting missing values, and analyzing control and treatment group distributions. This step ensures data is ready for A/B testing analysis.

A/B Testing Analysis
A hypothesis test is applied to compare conversion rates between the control and treatment groups using a two-sample t-test. This test assesses whether the observed difference is statistically significant.

Visualization of Results
This section includes charts to visualize group differences, such as a bar chart for means and a histogram for distribution comparison. Visualizations provide a clearer understanding of results.

## Dataset
The dataset used is from Kaggle and contains banking-related information. This project is only for educational purposes; please refer to Kaggle for the original dataset and its licensing details.

## 4. Conclusions
The final section summarizes findings and interprets the results. Based on the statistical test, it determines whether the treatment was effective.

## 5. License
Using a permissive license such as the MIT License is recommended, as it allows others to freely use, modify, and distribute the project with attribution to the original creator.

Copyright (c) 2024 Oscar Tibaduiza

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

## 6. Contact
If you have any questions or suggestions, please feel free to open an issue or contact me at oscartibaduiza@hotmail.com.
