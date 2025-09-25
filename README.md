# Phishing Website Detection using Random Forest Classifier (RFC) and Support Vector Machine (SVM)

## Project at a Glance

This project applies machine learning to detect phishing websites by analyzing URL and domain-based features. It implements and compares Random Forest Classifier (RFC) and Support Vector Machine (SVM) to evaluate their performance on phishing detection tasks. RFC provides robustness and feature interpretability, while SVM performs well in high-dimensional spaces. The results highlight the importance of ensemble learning methods in cybersecurity applications. This work demonstrates how ML models can strengthen defenses against phishing attacks and lays the groundwork for future real-time detection systems.

## Overview

Phishing is one of the most prevalent cybersecurity threats, tricking users into disclosing sensitive information such as passwords, banking details, or personal identity data. Traditional rule-based detection systems often fail against evolving attack strategies. This project addresses the problem by leveraging machine learning to distinguish phishing websites from legitimate ones with higher accuracy and adaptability.

We implement and compare two powerful machine learning algorithms:

* Random Forest Classifier (RFC) – a robust ensemble learning method that reduces variance and mitigates overfitting.
* Support Vector Machine (SVM) – a margin-based classifier well-suited for high-dimensional feature spaces.

The comparative study allows us to evaluate which model better generalizes for phishing detection tasks.

## Objectives

1. To preprocess and analyze website feature datasets for phishing detection.
2. To implement and evaluate RFC and SVM classifiers.
3. To compare classification accuracy, precision, recall, and F1-score across the models.
4. To demonstrate the role of machine learning in automating cybersecurity defenses.

## Methodology

1. Dataset – Extracted features of legitimate and phishing websites (e.g., URL length, presence of HTTPS, abnormal domain behavior).
2. Data Preprocessing – Handling missing values, normalization, and splitting into train/test sets.
3. Model Training

   * RFC: Uses ensemble decision trees with bootstrapping and feature randomness.
   * SVM: Optimizes separating hyperplanes in high-dimensional feature space.
4. Evaluation Metrics – Accuracy, precision, recall, and F1-score are computed to ensure a holistic comparison.
5. Results Visualization – Comparative analysis through confusion matrices and performance plots.

## Results

* Random Forest Classifier generally performs better in handling noisy features and provides interpretability through feature importance ranking.
* SVM achieves competitive performance in certain feature spaces but is more sensitive to parameter tuning.
* The project demonstrates that ensemble methods like RFC are more resilient in phishing detection tasks, although SVM can be effective in controlled scenarios.

## Key Contributions

* Developed a machine learning pipeline for phishing website detection.
* Conducted a comparative study of RFC and SVM in the cybersecurity domain.
* Highlighted the strengths and limitations of each approach.
* Demonstrated the applicability of ML-based models to real-world phishing prevention.

## How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/sumana0406/Phishing-Detection.git
   cd Phishing-Detection
   ```
2. Open the Jupyter Notebook:

   ```bash
   jupyter notebook assign2.ipynb
   ```
3. Execute cells step by step to reproduce preprocessing, training, and evaluation.

## References

* M. A. Mohammad, F. Thabtah, and L. McCluskey. Intelligent Rule based Phishing Websites Classification. Applied Soft Computing, 2014.
* Vapnik, V. N. The Nature of Statistical Learning Theory. Springer, 1995.
* Breiman, L. Random Forests. Machine Learning, 2001.

## Future Work

* Integration with a real-time browser extension for live phishing detection.
* Exploration of deep learning models (CNN, RNN, Transformers) for sequential URL feature extraction.
* Deployment as a web-based application for wider accessibility.
