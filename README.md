# 📉 Predict Bitcoin Price Using scikit-learn

This project implements a simple linear regression model to predict Bitcoin's closing price based on historical data. Utilizing Python and scikit-learn, it demonstrates fundamental machine learning concepts applied to financial time series data.

## 🚀 Features

* **Data Loading**: Reads historical Bitcoin price data from a CSV file.
* **Data Preprocessing**: Extracts relevant features for model training.
* **Model Training**: Implements linear regression using scikit-learn.
* **Evaluation**: Calculates Mean Squared Error (MSE) to assess model performance.
* **Visualization**: Plots actual vs. predicted prices for visual comparison.

## 🛠️ Technologies Used

* Python
* pandas
* scikit-learn
* matplotlib

## 📂 Project Structure

```
Predict_Bitcoin_Price_Using_scikit-learn/
├── main.py                               # Main script for data processing and model training
├── Problema2 - Predict Bitcoin Price Using scikit-learn.jpg  # Output visualization
└── README.md                             # Project documentation
```

## 📈 How to Use

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/OrasanuAna/Predict_Bitcoin_Price_Using_scikit-learn.git
   cd Predict_Bitcoin_Price_Using_scikit-learn
   ```

2. **Install Dependencies**:
   Ensure you have the required libraries installed:

   ```bash
   pip install pandas scikit-learn matplotlib
   ```

3. **Prepare the Data**:
   Place your historical Bitcoin price data CSV file in the project directory. Ensure the CSV includes columns like 'Date' and 'Close'.

4. **Run the Script**:
   Execute the main script:

   ```bash
   python main.py
   ```

   The script will:

   * Load and preprocess the data.
   * Train a linear regression model.
   * Predict future prices.
   * Calculate and display the MSE.
   * Generate a plot comparing actual and predicted prices.

## 📊 Sample Output

![Prediction Output](https://github.com/OrasanuAna/Predict_Bitcoin_Price_Using_scikit-learn/blob/master/Problema2%20-%20Predict%20Bitcoin%20Price%20Using%20scikit-learn.jpg)

*Figure: Actual vs. Predicted Bitcoin Closing Prices*

