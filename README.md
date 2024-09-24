# Supervised-Learning-Cross-National-Cancer-Trends-An-Analytical-Approach-Using-ML-Classification
This project leverages supervised machine learning to predict cancer rates across nations using global socioeconomic, environmental, and health indicators. By applying models like Logistic Regression, Decision Trees, and Random Forests, along with data preprocessing and imbalance handling techniques, it uncovers key predictors of cancer trends.
# Supervised Learning: Cross-National Cancer Trends

### An Analytical Approach Using ML Classification

This project uses supervised machine learning to predict cancer rates across countries based on global socioeconomic, environmental, and health indicators. By employing various classification models, this study identifies key predictors of cancer incidence across nations.

## Project Overview

Global cancer rates vary significantly, influenced by factors such as economic conditions, healthcare access, environmental quality, and social development. This project explores these relationships by applying machine learning classification models to predict cancer rates from a wide range of global indicators.

The models used include:
- Logistic Regression
- Decision Trees
- Random Forest
- Support Vector Machines (SVM)

Advanced preprocessing techniques and methods to handle class imbalance are incorporated, including:
- Data cleaning, scaling, and encoding
- Class weighting strategies
- SMOTE upsampling for handling imbalanced datasets
- Hyperparameter tuning for model optimization

## Table of Contents

- [Project Overview](#project-overview)
- [Installation](#installation)
- [Dataset](#dataset)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Installation

To run this project locally, follow these steps:

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/cancer-trends-prediction.git
    ```

2. Create and activate a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # For Windows: venv\Scripts\activate
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Dataset

The dataset includes global socioeconomic, environmental, and health indicators used to predict cancer rates. The target variable is the dichotomized cancer rate per 100,000 population, with predictors including indicators such as:

- GDP per capita
- Urban population percentage
- Life expectancy
- CO2 emissions
- Research and development expenditure

## Usage

1. Run the Jupyter notebook to preprocess the data, explore relationships, and train machine learning models:
    ```bash
    jupyter notebook ClassificationForMachineLearning_FinalAssignment.ipynb
    ```

2. Follow the notebook's instructions to execute data cleaning, preprocessing, and model training.

3. The final models will provide predictions on cancer rates across countries and key insights into the contributing factors.

## Results

The project successfully identifies significant predictors of cancer rates, with models like Random Forest and SVM showing high accuracy. The use of SMOTE upsampling and class weighting improved the models' ability to handle imbalanced data. Results show how socioeconomic and environmental indicators can predict cancer incidence.

## Contributing

If you'd like to contribute to this project, please fork the repository and use a feature branch. Pull requests are warmly welcome.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
