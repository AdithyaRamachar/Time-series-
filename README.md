# Airline Passenger Traffic Time Series Forecasting
Author - Adithya Ramachar

This project focuses on time series forecasting of airline passenger traffic using various methods and comparing their performance.

## Dataset

The dataset used in this project is the "Airline Passenger Traffic" dataset from Kaggle. It contains monthly totals of international airline passengers from 1949 to 1960. You can download it from this link [Airline Passenger Traffic](https://www.kaggle.com/datasets/umaer369/airline) 

To download the dataset:

1. Visit [Kaggle](https://www.kaggle.com/)
2. Download the CSV file named "airline-passenger-traffic(1).csv"

Place the downloaded CSV file in the project's root directory.

## Project Structure

```
airline-passenger-traffic/
│
├── data/
│   └── airline-passenger-traffic(1).csv
│
├── notebooks/
│   └── airline-passenger-traffic.ipynb
│
├── README.md
└── requirements.txt
```

## Setup

1. Clone this repository:
   ```
   git clone https://github.com/your-username/airline-passenger-traffic.git
   cd airline-passenger-traffic
   ```

2. Create a virtual environment and activate it:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Open the Jupyter notebook:
   ```
   jupyter notebook notebooks/airline-passenger-traffic.ipynb
   ```

2. Run the cells in the notebook to perform the analysis and generate forecasts.

## Methods Implemented

The project implements and compares the following forecasting methods:

1. Naive method
2. Simple average method
3. Simple moving average forecast
4. Simple exponential smoothing forecast
5. Holt's exponential smoothing method
6. Holt Winters' additive method
7. Autoregressive (AR) method
8. Moving Average (MA) method
9. Autoregressive Moving Average (ARMA) method
10. Seasonal Autoregressive Integrated Moving Average (SARIMA) method

## Results

The performance of each method is evaluated using Root Mean Square Error (RMSE) and Mean Absolute Percentage Error (MAPE). The results are presented in a table within the notebook, allowing for easy comparison of the different forecasting techniques.

## Contributing

Contributions to improve the project are welcome. Please feel free to submit a Pull Request.

