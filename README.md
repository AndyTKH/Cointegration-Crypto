# Cointegrated Cryptocurrency trading strategy
In this project, we will explore cointegrated cryptocurrency pair by first running linear regression to determine the optimal hedge ratio, and subsequently Augmented Dickey Fuller (ADF) test to ensure the pair is stationary. We then use Bollinger Band trading strategy to execute trades when the pair deviates, and take profit when the pair prices return to mean value. In our example, we're trading on Bitcoin and Ethereum. The output of the Tearsheet is as shown as below: 

<img src='image/cluster.png' width=100% />
<img src='image/matrix.png' width=100% />

## Project Instructions

### Instructions

1. Open your terminal and clone the repository, then navigate to the the project folder.
```
git clone https://github.com/AndyTKH/Cointegration-Crypto.git                                                          
cd Cointegration-Crypto
```
2. Open the notebook to view the project. 
```
jupyter notebook cointegrated_crypto.ipynb
```
3. Simply close the terminal window to exit Jupyter Notebook. 
