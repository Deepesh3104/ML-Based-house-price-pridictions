
# ML-Based House Price Predictions

## Overview

The ML-Based House Price Predictions project is designed to predict house prices using machine learning algorithms. This project utilizes various features of houses, such as size, location, and number of rooms, to make accurate price predictions. The goal is to provide a tool that can help homeowners, real estate agents, and potential buyers make informed decisions based on data-driven insights.

## Features

- **Data Preprocessing**: Handling missing values, encoding categorical data, and scaling features.
- **Model Training**: Training machine learning models using algorithms like Linear Regression, Decision Trees, and Random Forest.
- **Model Evaluation**: Evaluating model performance using metrics like RMSE, MAE, and R-squared.
- **Prediction**: Making predictions on new data inputs.
- **User Interface**: Simple and intuitive interface for inputting house features and getting price predictions.

## Installation

### Prerequisites

- Python 3.6 or higher
- Pandas
- NumPy
- Scikit-learn
- Flask

### Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Deepesh3104/ML-Based-house-price-pridictions.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd ML-Based-house-price-pridictions
   ```
3. **Create a virtual environment**:
   ```bash
   python -m venv venv
   ```
4. **Activate the virtual environment**:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```
5. **Install the required dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
6. **Run the application**:
   ```bash
   python app.py
   ```

## Usage

1. **Input House Features**: Enter the features of the house you want to predict the price for, such as size, location, and number of rooms.
2. **Make Prediction**: Click on the 'Predict' button to get the estimated house price.
3. **View Results**: The application will display the predicted price based on the input features.

## Technology Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Flask
- **Machine Learning**: Scikit-learn
- **Data Processing**: Pandas, NumPy

## Contributors

- [Deepesh3104](https://github.com/Deepesh3104)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
