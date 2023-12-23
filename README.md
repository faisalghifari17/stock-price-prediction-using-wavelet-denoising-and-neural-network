# Stock Price Prediction using Wavelet Denoising and Neural Network

In this project, we try to build a model that combining wavelet denoising and Artificial Neural Network. Using this model, we will predict stock price of Apple Inc. Then, we will evaluate model's performance using evaluation metrics.

At first, stock price data will be processed using wavelet denoising. Then we get denoised stock price data. Using this denoised data, we train neural network model. Neural network used in this project is Long-Short Term Memory (LSTM). After training phase, we test the model and evaluate its performance using several evaluation metrics (Mean Absolute Error, Mean Absolute Percentage Error, Mean Squared Error, Root Mean Squared Error and R2 score).

The model capture the pattern of Apple Inc., reaches 78% R2 score and 1,62% Mean Absolute Percentage Error.

Actual Price vs Prediction Price
![image](https://github.com/faisalghifariz/stock-price-prediction-using-wavelet-denoising-and-neural-network/assets/90921520/45d011a0-6632-487f-b5ef-560fc4c55f63)

Evaluation Metrics of the model
![image](https://github.com/faisalghifariz/stock-price-prediction-using-wavelet-denoising-and-neural-network/assets/90921520/6d492bcc-f5a1-4fa3-a114-6bdcf1527cf3)
