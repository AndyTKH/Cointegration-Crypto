# Cointegrated Cryptocurrency trading strategy
In this project, we will explore how cointegrated cryptocurrency pair could lead to profitable mean-reverting trading opportunities. The hypothesis presented here is that the cryptocurrency price of Bitcoin (BTC) and Ethereum (ETH) could be cointegrated and thus lead to a potential mean-reverting trading strategy. We will first perform a linear regression between the two to obtain the slope coefficient/hedge ratio, and subsequently carry out a Cointegrated Augmented Dickey Fuller (CADF) test that confirms the cryptocurrency pair is stationary, by rejecting the null hypothesis. To backtest the strategy, we will utilize the QSTrader backtesting simulation framework. The QSTrader framework has been simplified and updated to accommodate our strategy. In our example, we will utilize the Bollinger Bands to identify a mean-reverting series that deviate from its mean, for example a hedge position is opened and closed out when the mean-reverting series deviate and revert to its rolling mean respectively. Finally, a Tearsheet that shows the performance curve and other metrics for this strategy is shown as below: 

<img src='out/tearsheet.png' width=100% />

## Project Instructions

### Instructions

## Configure and Manage Your Environment with Anaconda
1. Install [miniconda](https://docs.conda.io/en/latest/miniconda.html) on your computer.
2. Install ```git``` for working with Github from your terminal window with command:  
   ``` 
   conda install git 
   ``` 
3. Clone this repository to your local computer, and navigate to your downloaded folder with command:
   ```
   git clone https://github.com/AndyTKH/Cointegration-Crypto.git                                                          
   cd Cointegration-Crypto
   ```
   **Note:** We will need to copy all the files from above `Cointegration-Crypto` directory to a specific project directory in the later steps.
   
4. Create and activate a new environment, note that we specify a path for the environment ( please change this to your own path ):
   
   - __Linux__ or __Mac__: 
	```
	conda create --prefix /Users/AndyTan/Documents/cointegration_crypto
	source activate /Users/AndyTan/Documents/cointegration_crypto
	```
	- __Windows__: 
	```
	conda create --prefix /Users/AndyTan/Documents/cointegration_crypto
	activate /Users/AndyTan/Documents/cointegration_crypto
	```
5. Install the required pip packages, as specified in the requirement text file: 
   ```
   pip install -r requirements.txt
   ```
6. Copy all files from step 3 and paste it to your current directory, assume my current directory is `/Users/AndyTan/Documents/cointegration_crypto` .

7. Now, you can open the notebook to view the project:	
   ```
   jupyter notebook cointegrated_crypto.ipynb
   ```
8. Simply close the terminal window to exit Jupyter Notebook. 
