# Data Processing and Machine Learning Projects

This repository contains two projects focused on the end-to-end data science pipeline, ranging from rigorous data cleaning to advanced feature engineering and binary classification. These projects were completed as part of the ** (Data Preprocessing and Analysis)** course.

---

## 1. Data Validation & Cleaning (The Metropolitan Museum of Art)

### Goal

The primary objective of this project is to clean and validate the **Metropolitan Museum of Art Open Access dataset**. It focuses on transforming a "messy" real-world dataset into a structured format suitable for analysis.

### Main Steps

* **Data Acquisition:** Integrating the `MetObjects.csv` dataset from the official Met Museum repository.
* **Initial Validation:** Identifying inconsistencies, data type errors, and structural issues across thousands of records.
* **Data Cleaning:** * Standardizing categorical fields and handling string inconsistencies.
* Treating missing values (NaNs) across multiple features.
* Cleaning dimensions and measurements (parsing heights, widths, and depths from raw text).


* **Exploratory Data Analysis (EDA):** Using visualizations to document the data distribution before and after cleaning.
* **Documentation:** Detailed Markdown commentary explaining the logic behind every cleaning decision.


## 2. Advanced Preprocessing & Binary Classification

### Goal

This project explores how different preprocessing strategies—such as balancing, transformations, and dimensionality reduction—impact the performance of a **Binary Classification** model.

### Main Steps

* **Feature Transformation:** Applying binning and scaling to numerical features to improve model stability.
* **Addressing Imbalance:** Implementing techniques to balance the target classes (e.g., oversampling or undersampling) to prevent model bias.
* **Dimensionality Reduction:** Reducing the feature space to remove noise while retaining the most significant variance in the data.
* **Model Training:** Evaluating the impact of different preprocessing combinations on a classifier.
* **Performance Evaluation:** * Analyzing **F1 Scores** (Positive, Macro, and Weighted).
* Plotting **ROC Curves** and calculating **AUC** (Area Under the Curve).
* Visualizing results via **Confusion Matrices**.



### Key Metrics

* **F1 Score:** Used as the primary metric to balance Precision and Recall.
* **AUC-ROC:** Used to measure the model's ability to distinguish between classes.
