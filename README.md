# Predicting European Roaming Internet Consumption: Time Series Forecasting

## Overview
This project focuses on forecasting European roaming internet consumption using state-of-the-art time series forecasting models. The objective is to predict internet usage trends across Europe, employing machine learning techniques for improved forecasting accuracy. The project explores **XGBoost** and incorporates hyperparameter tuning using **Optuna** to optimize model performance.

## Features
- **Hyperparameter Tuning**: Optimization of models with Optuna for improved performance.
- **Exogenous Variables**: Integration of external factors (e.g., major events) to enhance forecasting accuracy.
- **Comparative Analysis**: Assessment of the models' strengths and weaknesses in handling complex time series data.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ChaimaBalti/Predicting-European-Roaming-Internet-Consumption-Time-Series-Forecasting.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Predicting-European-Roaming-Internet-Consumption-Time-Series-Forecasting
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Data Preprocessing**: Load and preprocess the time series data.
2. **Model Training**: Train the selected forecasting models using the preprocessed data.
3. **Hyperparameter Tuning**: Use Optuna for hyperparameter tuning to improve model performance.
4. **Forecasting**: Generate forecasts and evaluate model accuracy on test data.
5. **Visualization**: Visualize the results, comparing model predictions with actual data.

## Results
The project demonstrates significant improvements in forecasting accuracy with the inclusion of exogenous variables, providing valuable insights for decision-making processes in the telecommunications sector.

## Project Structure
```plaintext
Predicting-European-Roaming-Internet-Consumption-Time-Series-Forecasting/
│
├── data/                    # Data files (not included due to confidentiality)
├── notebook/                # Jupyter notebooks for data exploration and model training
├── Snippets_of_Report_Summer_internship.pdf
├── README.md                 # Project overview and documentation
├── requirements.txt          # Required dependencies for the project
└── .gitignore                # Gitignore file for sensitive and unnecessary files
```

## Keywords
- Time Series Forecasting
- XGBoost
- Exogenous Variables
- Optuna
- Hyperparameter Tuning

## License
This project is licensed under the MIT License. See the `LICENSE` file for more information.

## Acknowledgments
Special thanks to the team members and mentors who provided guidance throughout the project.

```
