# Naive-Bayes-Spam-Email-Classifier

📌 Project Overview
This project implements a Spam Email Classifier using a probabilistic approach based on Naive Bayes theorem. The classifier is designed to distinguish between spam and non-spam (ham) emails by computing the probability of an email belonging to each category. The model leverages Bayesian inference and log-probability calculations to handle large feature spaces efficiently.


🏗 Project Structure

The repository includes:

Preprocessing and Feature Extraction: Converting raw email text into numerical representations using Bag-of-Words (BoW) and TF-IDF methods.

Probability-Based Classification: Applying Bayes' theorem to determine the likelihood of an email being spam or non-spam.

Log Probability Visualization: Plotting log probabilities of spam vs. ham emails to analyze classification boundaries.

Model Evaluation: Assessing performance using accuracy, precision, recall, and confusion matrices.



🚀 Key Features

✔ Naive Bayes Model: A probabilistic classifier that calculates the likelihood of an email being spam based on word frequency.

✔ Sparse Matrix Construction: Converts raw email data into a structured numeric format.

✔ Performance Metrics: Evaluates the model using precision, recall, and F1-score.

✔ Visualization: Scatter plots of log probabilities of spam vs. non-spam emails.



📊 Classification Pipeline

1️⃣ Data Preprocessing:

Load raw email data

Tokenize and process text

Convert emails into a sparse matrix representation


2️⃣ Probability Computation (Naive Bayes):

Compute word probabilities using maximum likelihood estimation

Apply log transformations for numerical stability

Calculate posterior probabilities using Bayes' theorem


3️⃣ Model Evaluation:

Compute accuracy, precision, recall, and F1-score

Generate confusion matrix to analyze false positives & false negatives

Visualize log-probabilities with scatter plots

🛠 Technologies Used

Python (NumPy, Pandas, Matplotlib, Seaborn)

Naive Bayes Theorem for classification

Sparse Matrix Representation for efficient text processing

Data Visualization using log-scale probability plots
