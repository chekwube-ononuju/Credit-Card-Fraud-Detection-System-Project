# Credit-Card-Fraud-Detection-System-Project

This project aims to build a machine learning model to detect fraudulent credit card transactions. The system analyzes transaction data and identifies patterns that indicate potential fraud, helping to prevent unauthorized transactions and secure financial information.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Credit card fraud is a significant issue that affects both consumers and financial institutions. This project leverages machine learning techniques to detect fraudulent transactions. By analyzing past transaction data, the system can predict whether a new transaction is fraudulent.

## Features

- Data preprocessing and cleaning
- Exploratory data analysis
- Feature engineering
- Model training using various algorithms
- Model evaluation and validation
- Fraud detection on new data

## Dataset

The dataset used in this project is the [Credit Card Fraud Detection dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud) from Kaggle. It contains credit card transactions made by European cardholders in September 2013. The dataset presents transactions that occurred in two days, where 492 out of 284,807 transactions are fraudulent.

## Requirements

- Python 3.x
- Jupyter Notebook
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/chekz1321/Credit-Card-Fraud-Detection-System-Project.git
    cd Credit-Card-Fraud-Detection-System-Project
    ```

2. Create a virtual environment:
    ```sh
    python -m venv venv
    ```

3. Activate the virtual environment:
    - On Windows:
        ```sh
        venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```sh
        source venv/bin/activate
        ```

4. Install the required libraries:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Start Jupyter Notebook:
    ```sh
    jupyter notebook
    ```

2. Open the notebook `Credit_Card_Fraud_Detection.ipynb` and follow the instructions to preprocess data, train models, and evaluate results.

## Model Training

The project includes training various machine learning models, such as:

- Decision Trees
- Random Forest
- Light GBM
- XG Boost
- Neural Networks

Each model is trained and evaluated to determine the best performing algorithm for fraud detection.

## Evaluation

Model performance is evaluated using metrics such as:

- Accuracy
- Precision
- Recall
- F1-Score

Confusion matrices are also used to visualize model performance.

## Results

The results of the project include the performance metrics of various models, highlighting the most effective algorithm for detecting fraudulent transactions.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to reach out if you have any questions or suggestions. Thank you for your interest in the Credit Card Fraud Detection System Project!
