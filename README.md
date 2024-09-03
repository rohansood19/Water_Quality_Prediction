# Water_Quality_Prediction
Water Quality Prediction System using AI - Dissertation

## Table of Contents

- [Project Overview](#project-overview)
- [Data](#data)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Libraries Used](#libraries-used)
- [Versioning](#versioning)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Project Overview

This project is part of a dissertation focused on predicting water quality using various machine learning models. The system leverages data from 2018 and 2019 to build and evaluate predictive models for chemical oxygen demand (COD), which is a critical measure of water quality.

## Data

The datasets used in this project are as follows:

- `eng_967_2018.csv`: Water quality data for the year 2018.
- `eng_967_2019.csv`: Water quality data for the year 2019.

These files are included in the repository.

## Installation

To run the code in this repository, you need to have Python installed along with the necessary libraries. You can install all the required libraries using the following command:

```bash
pip install -r requirements.txt
```

(Note: You can generate a `requirements.txt` file using `pip freeze > requirements.txt` to capture all the installed libraries with their versions.)

## Usage

To use the code provided in this repository:

1. Clone the repository:
    ```bash
    git clone https://github.com/rohansood19/Water_Quality_Prediction.git
    ```

2. Navigate to the directory:
    ```bash
    cd Water_Quality_Prediction
    ```

3. Open the Jupyter Notebook `Dissertation_final.ipynb` to explore the analysis, model building, and evaluation steps.

## Results

The key results of this project are the predictive performance metrics for the various models used, including Mean Absolute Error (MAE), R-squared (R²), and Mean Squared Error (MSE). These metrics help in understanding the effectiveness of the models in predicting water quality.

## Libraries Used

The project uses the following libraries:

- **Python**: `3.8`
- **numpy**
- **pandas**
- **seaborn**
- **matplotlib**
- **scikit-learn**
    - `Pipeline`, `GridSearchCV`, `cross_val_score`
    - `ColumnTransformer`, `TransformedTargetRegressor`
    - `StandardScaler`, `RobustScaler`, `OneHotEncoder`
    - `SVR`, `RandomForestRegressor`, `GradientBoostingRegressor`, `AdaBoostRegressor`, `StackingRegressor`, `VotingRegressor`, `DecisionTreeRegressor`, `MLPRegressor`
    - `mean_absolute_error`, `r2_score`, `mean_squared_error`
    - `RFE`, `SelectFromModel`
- **xgboost**
- **catboost**
- **shap**
- **lime**

## Versioning

For the versions of the libraries used in this project, refer to the `requirements.txt` file. Below are the versions of a few key libraries:

- **numpy**: 1.21.2
- **pandas**: 1.3.3
- **seaborn**: 0.11.2
- **matplotlib**: 3.4.3
- **scikit-learn**: 0.24.2
- **xgboost**: 1.4.2
- **catboost**: 0.26.1
- **shap**: 0.39.0
- **lime**: 0.2.0.1

## Contributing

If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. Please ensure that your changes are well-documented and tested.

## Acknowledgements

- Thank you to the University of Nottingham for the guidance and resources provided during this project.
- Special thanks to my supervisor for their support and mentorship.
