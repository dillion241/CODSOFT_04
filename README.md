# CODSOFT_04
This repository contains code and resources for building a machine learning model to classify SMS messages as spam or legitimate.
# SMS Spam Classification

This repository contains code and resources for building a machine learning model to classify SMS messages as spam or legitimate.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Usage](#usage)
- [Installation](#installation)
- [Dependencies](#dependencies)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

In this project, we aim to develop a model that can automatically classify SMS messages as either spam or legitimate. We explore different machine learning algorithms and techniques for text classification, including TF-IDF vectorization, SMOTE resampling, and multiple classifiers.

## Dataset

The dataset used for this project contains SMS messages labeled as spam or legitimate. It's stored in a CSV file named `data.csv` and contains two columns: 'text' (the SMS content) and 'cat' (the label, where 0 represents legitimate messages and 1 represents spam messages).

## Usage

To run this project:

1. Clone this repository: `git clone https://github.com/yourusername/sms-spam-classification.git`
2. Navigate to the project directory: `cd sms-spam-classification`
3. Install the required dependencies (see [Installation](#installation))
4. Run the main script: `python main.py`

## Installation

You can install the required dependencies using the following command:


## Dependencies

The project uses the following main libraries:

- pandas
- scikit-learn
- imbalanced-learn
- matplotlib

You can find the complete list of dependencies in the `requirements.txt` file.

## Model Training

The main script `main.py` performs the following steps:

1. Loads and preprocesses the dataset.
2. Applies TF-IDF vectorization to convert text data into numerical features.
3. Performs SMOTE resampling to address class imbalance.
4. Trains multiple classifiers (Naive Bayes, Logistic Regression, SVM).
5. Evaluates the classifiers using cross-validation.

## Evaluation

The evaluation results for each classifier are displayed in the console, including accuracy, precision, recall, and F1-score.

## Results

The SVM classifier demonstrated the highest average accuracy of approximately 96.3% across cross-validation folds.

## Contributing

Contributions are welcome! If you find any issues or want to enhance the project, feel free to submit a pull request.



