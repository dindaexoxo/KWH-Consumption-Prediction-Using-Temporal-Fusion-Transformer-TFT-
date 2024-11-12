# KWH Consumption Prediction Using Temporal Fusion Transformer (TFT)

Hello! My name is **Adinda Ayu Lestari**, you can call me **Dinda**. I make this project **for learning and demonstration purposes only** with guidance from ChatGPT, Gemini, and any stuff on the internet. This project aims to predict energy consumption (measured in kWh) over time using a Temporal Fusion Transformer (TFT) model. The model leverages time-series data to provide accurate and interpretable predictions of future energy usage, which can aid in optimizing energy resources.

# Project Overview
- **Dataset**: The dataset for this project is from Kaggle and contains time-series data on kWh consumption.
- **Goal**: Predict future kWh consumption based on historical data, capturing seasonal trends and patterns.
- **Model Used**: Temporal Fusion Transformer (TFT), a deep learning architecture suitable for time-series forecasting.

# Dataset
The dataset used for this project is publicly available on Kaggle. You can access it here: https://www.kaggle.com/datasets/vitthalmadane/energy-consumption-time-series-dataset.

# Requirements
To run this project, you'll need the following Python packages:

- Pandas
- NumPy
- TensorFlow
- scikit-learn
- Matplotlib

>To install all requirements, use:
`pip install -r requirements.txt`

#  Result
- **MSE**: The final model achieved an MSE of approximately `0.0071`, indicating a low average error for predictions.
- **Interpretation**: With the kWh values ranging from 0 to approximately 27.3, this MSE value suggests that the model’s predictions are highly accurate, making it a reliable tool for forecasting future consumption.

#  License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

#  Acknowledgments
This project was developed with the guidance of various online resources, including ChatGPT, and follows best practices in time-series forecasting for energy data. Special thanks to the contributors of the TFT model architecture for time-series data.




