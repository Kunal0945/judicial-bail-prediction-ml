Judicial Bail Prediction using Machine Learning
🔍 Project Overview

This project builds an NLP-based Machine Learning model to predict whether bail is likely to be granted or rejected based on Indian court judgment texts.

🧠 Problem Statement

Judicial bail decisions involve risk. A false positive (granting bail when it should be rejected) can be dangerous.
This project focuses on risk-aware predictions using threshold tuning.

⚙️ Tech Stack

Python

Pandas, NumPy

Scikit-learn

TF-IDF Vectorizer (NLP)

Logistic Regression

Google Colab

🚀 Approach

Text preprocessing & TF-IDF feature extraction

Train Logistic Regression classifier

Evaluate using Precision, Recall, Confusion Matrix

Apply custom probability threshold to reduce false positives

Live prediction on unseen case text

📊 Results

Accuracy: ~94%

Reduced False Positives using strict threshold (0.7)

Model favors judicial safety over leniency

📁 Files

Judicial_Intelligence_Bail_Prediction.ipynb – Complete implementation

Dataset: Indian Bail Judgments (public legal texts)

⚠️ Disclaimer

This project is for educational purposes only and does not replace legal judgment.
