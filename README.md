# **Gradient Boosting RegressorModel for Financial Predictions**

This repository contains an implementation of an Gradient Boosting Regressormodel, specifically designed for predicting the prices of financial instruments such as currencies, stocks, and cryptocurrencies. The Gradient Boosting Regressoralgorithm leverages gradient boosting techniques, enabling it to capture intricate patterns in price movements and handle various dataset characteristics effectively. This approach enhances the accuracy and robustness of price forecasts across various datasets.

This is the original code sample for the Gradient Boosting Regressormodel. Explore my GitHub repository for additional models and implementations that cater to different financial prediction needs.

## **Performance Metrics**

### 

### **BTC-USD (Bitcoin)**

| Metric | Open | High | Low | Close |
| :---- | :---- | :---- | :---- | :---- |
| Mean Squared Error | 0.000797 | 0.000723 | 0.000725 | 0.000812 |
| Mean Absolute Error | 0.02081 | 0.01837 | 0.02003 | 0.02089 |
| R-squared | 0.96620 | 0.96989 | 0.96883 | 0.96646 |
| Median Absolute Error | 0.01419 | 0.01293 | 0.01677 | 0.01487 |
| Explained Variance Score | 0.96623 | 0.97027 | 0.96928 | 0.96649 |

### **![][image1]**

### **GC=F (Gold Futures)**

| Metric | Open | High | Low | Close |
| :---- | :---- | :---- | :---- | :---- |
| Mean Squared Error | 0.001308 | 0.000704 | 0.000780 | 0.000876 |
| Mean Absolute Error | 0.02866 | 0.02011 | 0.02144 | 0.02286 |
| R-squared | 0.93471 | 0.96448 | 0.96116 | 0.95602 |
| Median Absolute Error | 0.02487 | 0.01455 | 0.01742 | 0.01764 |
| Explained Variance Score | 0.95845 | 0.96589 | 0.96486 | 0.95955 |

### **![][image2]**

### **EURUSD (Euro/US Dollar)**

| Metric | Open | High | Low | Close |
| ----- | ----- | ----- | ----- | ----- |
| Mean Squared Error | 0.000416 | 0.000265 | 0.000228 | 0.000396 |
| Mean Absolute Error | 0.01574 | 0.01247 | 0.01126 | 0.01552 |
| R-squared | 0.90842 | 0.94280 | 0.95060 | 0.91206 |
| Median Absolute Error | 0.01178 | 0.00913 | 0.00968 | 0.01274 |
| Explained Variance Score | 0.90849 | 0.94311 | 0.95062 | 0.91206 |

 

### **![][image3]**

### **GSPC (S\&P 500 Index)**

| Metric | Open | High | Low | Close |
| :---- | :---- | :---- | :---- | :---- |
| Mean Squared Error | 0.000497 | 0.000394 | 0.000479 | 0.000606 |
| Mean Absolute Error | 0.01670 | 0.01403 | 0.01650 | 0.01863 |
| R-squared | 0.96356 | 0.97249 | 0.96462 | 0.95739 |
| Median Absolute Error | 0.01234 | 0.01036 | 0.01296 | 0.01415 |
| Explained Variance Score | 0.96636 | 0.97444 | 0.96632 | 0.96067 |

### **![][image4]**

## **Related Websites**

### [**Predict Price**](https://predict-price.com/)

Free AI-powered short-term (5/10/30 days) and long-term (6 months/1/2 years) forecasts for cryptocurrencies, stocks, ETFs, currencies, indices, and mutual funds.

### [**Magical Prediction**](https://magicalprediction.com/)

Get free trading signals generated by advanced AI models. Enhance your trading strategy with accurate, real-time market predictions powered by AI.

### [**Magical Analysis**](https://magicalanalysis.com/)

Discover free trading signals powered by expert technical analysis. Boost your forex, stock, and crypto trading strategy with real-time market insights.

## **About This Project**

This Gradient Boosting Regressormodel is an initial implementation, released for public use. The project demonstrates the potential of deep learning models for financial predictions. While this repository focuses on SVR, I have also utilized other models, the code for which is available on my GitHub[https://github.com/taleblou/].

## **How to Use**

1. Clone this repository.  
2. Install the required libraries: `pip install -r requirements.txt`  
3. Prepare your dataset and follow the instructions in the notebook or script.  
4. Run the model and evaluate its performance using the provided metrics.

## **License**

This project is open-source and available for public use under the MIT License. Contributions and feedback are welcome\!

[image1]: <https://raw.githubusercontent.com/taleblou/GradientBoostingRegressor-Price-Prediction/refs/heads/main/Plot/GradientBoostingRegressor_BTC-USD.png>
[image2]: <https://raw.githubusercontent.com/taleblou/GradientBoostingRegressor-Price-Prediction/refs/heads/main/Plot/GradientBoostingRegressor_GC%3DF.png>
[image3]: <https://raw.githubusercontent.com/taleblou/GradientBoostingRegressor-Price-Prediction/refs/heads/main/Plot/GradientBoostingRegressor_EURUSD%3DX.png>
[image4]: <https://raw.githubusercontent.com/taleblou/GradientBoostingRegressor-Price-Prediction/refs/heads/main/Plot/GradientBoostingRegressor_%5EGSPC.png>
