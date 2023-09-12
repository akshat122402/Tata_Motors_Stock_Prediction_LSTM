# Stock Price Prediction with LSTM

## Overview

This repository contains code for a stock price prediction model using **Long Short-Term Memory (LSTM)** neural networks. The model is trained on historical stock price data for **Tata Motors Ltd**. The goal is to predict future stock prices based on past price trends.

## Dataset

The historical stock price data for Tata Motors Ltd. used in this project was obtained from **Kaggle**. You can access the dataset [here](https://www.kaggle.com/datasets/anoopjohny/tata-motors-stock-history). Make sure to download the dataset and place it in the `/data` directory of this repository before running the code.

### Dataset Details

- **Dataset Name**: Tata Motors Stock History
- **Source**: https://www.kaggle.com/datasets/anoopjohny/tata-motors-stock-history
- **License**: Check the Kaggle dataset page for licensing information.

## Dependencies

Before running the code in this repository, make sure you have the following dependencies installed:

- **Python 3.x**
- **NumPy**
- **pandas**
- **matplotlib**
- **scikit-learn**
- **TensorFlow** (for LSTM model)
- **Google Colab** (optional, for running the code interactively)

You can install these dependencies using pip:

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow
```
## Usage

### Data Preparation
Place the downloaded dataset (CSV file) in the `/data` directory of this repository.

### Training the Model
The Jupyter Notebook guides you through the process of loading the dataset, preprocessing the data, creating sequences, and training the LSTM model. Adjust the hyperparameters and model architecture as needed.

### Evaluation and Testing
Evaluate the model's performance on the test set and visualize the predictions.

### Future Predictions
The notebook also includes code to make future stock price predictions for a specified number of days beyond the test dataset.

## Model Details

The LSTM model used in this project consists of two LSTM layers with dropout for sequence prediction and a dense output layer. The model is compiled with the **Adam optimizer** and **Mean Squared Error (MSE)** loss.

## Results

### Training Set Metrics
- **Mean Absolute Error (MAE)**: 11.12
- **Mean Squared Error (MSE)**: 275.20
- **Root Mean Squared Error (RMSE)**: 16.59

### Testing Set Metrics
- **Mean Absolute Error (MAE)**: 18.50
- **Mean Squared Error (MSE)**: 606.81
- **Root Mean Squared Error (RMSE)**: 24.63

## Future Predictions

The model can be used to make future stock price predictions for a specified number of days beyond the test dataset. You can find the future predictions in the notebook.

## License

This project is open-source and is available under the **MIT License**.

Feel free to contribute to this project by opening issues, suggesting improvements, or submitting pull requests. If you have any questions or feedback, please don't hesitate to reach out.

**Happy coding!**

