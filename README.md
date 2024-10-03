# fuel-efficiency
# Fuel Efficiency Prediction

This project aims to predict the fuel efficiency of vehicles using a machine learning model built with TensorFlow/Keras. The dataset includes features like horsepower, weight, displacement, and more, which are used to predict the fuel efficiency (in miles per gallon, MPG).

## Project Structure

1. **Data Loading and Preprocessing**:
    - The dataset is loaded, and initial exploration is conducted to understand the attributes.
    - Data is cleaned, normalized, and prepared for modeling.

2. **Model Creation**:
    - A neural network is designed and built using Keras.
    - The architecture uses several dense layers and the mean absolute error (MAE) as the loss function.

3. **Model Training**:
    - The model is trained on a training dataset and evaluated using a testing dataset.
    - Visualizations are used to compare predicted MPG values to true values.

4. **Evaluation**:
    - The final model is evaluated using MAE, and visualizations provide insights into the performance.

## Dependencies

- TensorFlow/Keras
- Pandas
- NumPy
- Matplotlib

## How to Run

1. Clone the repository.
2. Install the required dependencies by running:
   ```bash
   pip install -r requirements.txt
