# Predicting House Prices with Artificial Neural Networks (ANN)

## Project Overview

This project uses an Artificial Neural Network (ANN) to predict house prices based on various features from the Melbourne House Prices dataset. The dataset includes information about housing features and their corresponding prices, and the goal is to build a predictive model to estimate house prices accurately.

## Dataset

- **File**: `MELBOURNE_HOUSE_PRICES_LESS.csv`
- **Source**: [Kaggle - Melbourne Housing Market](https://www.kaggle.com/anthonypino/melbourne-housing-market/data)

### Description

The dataset contains information on various attributes of houses in Melbourne and their selling prices. Features include property attributes, location details, and other relevant data points.

## Objectives

- **Data Preprocessing**: Clean and prepare the data for modeling, including handling missing values and feature encoding.
- **Model Building**: Develop an Artificial Neural Network to predict house prices based on the features.
- **Evaluation**: Assess the model's performance using appropriate metrics and refine it to improve accuracy.

## Installation

1. Clone the repository:
   ```bash
   git clone [repository_link]
   ```
2. Navigate to the project directory:
   ```bash
   cd ann-house-price-prediction
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Data Preparation**:
   ```python
   python data_preprocessing.py
   ```
2. **Train the ANN Model**:
   ```python
   python train_ann_model.py
   ```
3. **Evaluate the Model**:
   ```python
   python evaluate_model.py
   ```

## Modeling

The project utilizes an Artificial Neural Network (ANN) for regression tasks, implemented using libraries such as TensorFlow or PyTorch. The model is designed to learn patterns from the features in the dataset to predict house prices.

## Evaluation

Model performance is evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared. The goal is to minimize prediction error and improve the model's accuracy.

## Conclusion

The ANN model provides a powerful tool for predicting house prices based on various features. By analyzing and refining the model, accurate predictions can be made, assisting in real estate evaluations and decision-making.

## References

- [Melbourne Housing Market Dataset](https://www.kaggle.com/anthonypino/melbourne-housing-market/data)
