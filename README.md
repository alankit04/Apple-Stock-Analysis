# <h1>Apple-Stock-Analysis</h1>

**<h2>Project Overview**<h2>
This project aims to predict the future stock prices of <strong>Apple Inc. (AAPL)</strong> using historical stock data. This project analyses past stock prices by leveraging <strong>Time Series Analysis</strong> and the<strong> Long Short-Term Memory (LSTM) model</strong>. It predicts future trends, providing a valuable tool for investors and analysts.

**<h2>Project Structure<h2>**
<li>Data: Contains the raw historical stock data of Apple (AAPL) from Yahoo Finance or another source.</li>
<li>IDE: Jupyter notebooks with the code for data analysis, feature engineering, and model building.</li>
<li>Model: Contains saved prediction models.</li>
<li>Requirements.txt: List of dependencies for the project (e.g., TensorFlow, pandas, matplotlib, numpy, etc.).</li>
<li>app.py: The script to run predictions and visualize results.</li>
<li>Output: Folder containing the predicted results and visualizations.</li>
  
**<h2>Technology Using</h2>**
<li>Python: A programming language for the project.</li>
<li>TensorFlow/Keras: Deep learning framework for building the LSTM model.</li>
<li>pandas: Data manipulation and analysis.</li>
<li>NumPy: Numerical computing.</li>
<li>matplotlib and seaborn: Data visualization tools for plotting stock prices and predictions.</li>
<li>scikit-learn: For splitting the dataset and scaling the data.</li>
  
**<h2>Dataset</h2>**
The dataset consists of daily stock prices for Apple Inc. (AAPL) that include the following columns:
<li>Date: The date of the stock data.</li>
<li>Open: The price at which the stock opened.</li>
<li>High: The highest price of the day.</li>
<li>Low: The lowest price of the day.</li>
<li>Close: The closing price of the stock.</li>
<li>Volume: The number of shares traded.</li>
**<h2>Model Working</h2>**
<li>Time Series Analysis: The stock prices are treated as a time series, where past prices influence future values. We preprocess the data by scaling and transforming it to fit the model.</li>
<li>LSTM Model: A type of Recurrent Neural Network (RNN) designed to capture long-term dependencies in sequential data. The LSTM model is trained on the historical stock data to predict future stock prices.</li>
