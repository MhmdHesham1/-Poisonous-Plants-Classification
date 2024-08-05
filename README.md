# Poisonous Plants Classification

This project is part of a Kaggle competition to classify mushrooms as either poisonous or edible based on various features.

## Table of Contents
1. [Description](#description)
2. [Requirements](#requirements)
3. [Installation](#installation)
4. [Usage](#usage)
5. [File Structure](#file-structure)
6. [Models](#models)
7. [Evaluation](#evaluation)
8. [Submission](#submission)

## Description

This project uses machine learning to classify mushrooms as either poisonous or edible. It uses various features of mushrooms such as cap shape, cap color, gill attachment, etc., to make predictions. The project implements and compares three different classification models: Logistic Regression, Decision Tree, and Random Forest.

## Requirements

- Python 3.7+
- pandas
- numpy
- scikit-learn

## Installation

1. Clone this repository:
   git clone https://github.com/your-username/poisonous-plants-classification.git
2. Navigate to the project directory:
   cd poisonous-plants-classification
3. Install the required packages:
   pip install -r requirements.txt
## Usage

1. Ensure your training data is located at '/content/drive/MyDrive/train.csv'
2. Ensure your test data is located at '/content/drive/MyDrive/test.csv'
3. Run the script:
   python mushroom_classification.py
## File Structure

- `mushroom_classification.py`: Main script containing data preprocessing, model training, and prediction code.
- `train.csv`: Training dataset (not included in repo)
- `test.csv`: Test dataset (not included in repo)
- `submission.csv`: Output file with predictions (generated after running the script)

## Models

The script trains and compares three models:
1. Logistic Regression
2. Decision Tree
3. Random Forest

## Evaluation

The models are evaluated using the following metrics:
- Accuracy
- Precision
- Recall
- F1-Score

## Submission

After running the script, a `submission.csv` file will be generated containing the predictions for the test set. This file can be submitted to the Kaggle competition.
