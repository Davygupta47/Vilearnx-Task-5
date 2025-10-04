# AAPL Stock Market Predictor. VilearnX offers a dynamic internship experience, providing students with hands-on exposure to AI-driven projects, mentorship from industry experts, and a collaborative environment to develop skills and build a strong professional network.

Dear VilearnX Team,

A comprehensive stock market analysis and prediction system for Apple Inc. (AAPL) using Python and machine learning techniques. This project demonstrates data fetching, exploratory data analysis, ARIMA modeling, and LSTM neural network implementation for stock price prediction.        I wanted to take a moment to express my sincere gratitude for the opportunity to intern at VilearnX. I am so grateful to have had the chance to work alongside, and I have learned so much from each one of the given tasks for DATA ANALYTICS and MACHINE LEARNING.



## FeaturesThanking you,

Dwaipayan Dasgupta

- **Data Fetching**: Automated retrieval of historical stock data from Yahoo Finance# Vilearnx-Task-5

- **Exploratory Data Analysis**: Comprehensive analysis including price trends, returns distribution, correlation analysis, moving averages, and volatilityTHIS particular Task is a comprehensive stock market analysis and prediction system using Python and various libraries such as Pandas, NumPy, Matplotlib, Seaborn, Statsmodels, Scikit-learn, and TensorFlow. The project focuses on analyzing and predicting the stock price of Apple Inc. (AAPL) using historical data from Yahoo Finance.

- **ARIMA Modeling**: Time series forecasting using ARIMA (AutoRegressive Integrated Moving Average)This repository contains a comprehensive stock market analysis and prediction system using Python and various libraries such as Pandas, NumPy, Matplotlib, Seaborn, Statsmodels, Scikit-learn, and TensorFlow. The project focuses on analyzing and predicting the stock price of Apple Inc. (AAPL) using historical data from Yahoo Finance. The project includes data fetching, data preprocessing, exploratory data analysis, ARIMA model implementation, LSTM model implementation, model evaluation, and forecasting. The project provides a comprehensive analysis of the stock price of Apple Inc. (AAPL) and demonstrates the use of LSTM neural networks for stock price prediction.

- **LSTM Neural Network**: Deep learning approach for stock price prediction using Long Short-Term Memory networks

- **Visualization**: Multiple plots for data insights and model performance

- **Model Evaluation**: RMSE metrics for both training and testing datasetsOUTPUT:

<class 'pandas.core.frame.DataFrame'>

## Technologies UsedDatetimeIndex: 1006 entries, 2020-01-02 to 2023-12-29

Data columns (total 6 columns):

- Python #   Column     Non-Null Count  Dtype  

- Pandas & NumPy (Data manipulation)---  ------     --------------  -----  

- Matplotlib & Seaborn (Visualization) 0   Open       1006 non-null   float64

- Statsmodels (ARIMA modeling) 1   High       1006 non-null   float64

- Scikit-learn (Metrics and preprocessing) 2   Low        1006 non-null   float64

- TensorFlow/Keras (LSTM implementation) 3   Close      1006 non-null   float64

- YFinance (Data fetching) 4   Adj Close  1006 non-null   float64

 5   Volume     1006 non-null   int64  

## Installationdtypes: float64(5), int64(1)

memory usage: 55.0 KB

1. Clone the repository:Number of duplicate rows: 0

```bashRMSE: 30.83889864818401

git clone https://github.com/Davygupta47/Vilearnx-Task-5.git                               SARIMAX Results                                

cd Vilearnx-Task-5==============================================================================

```Dep. Variable:                  Close   No. Observations:                  804

Model:                 ARIMA(1, 1, 1)   Log Likelihood               -1955.393

2. Install required packages:Date:                Mon, 16 Sep 2024   AIC                           3916.786

```bashTime:                        17:12:01   BIC                           3930.851

pip install -r requirements.txtSample:                             0   HQIC                          3922.188

```                                - 804                                         

Covariance Type:                  opg                                         

## Usage==============================================================================

                 coef    std err          z      P>|z|      [0.025      0.975]

1. Open the Jupyter notebook:------------------------------------------------------------------------------

```bashar.L1          0.3818      0.383      0.998      0.318      -0.368       1.132

jupyter notebook src/AAPL_Stock_Predictor.ipynbma.L1         -0.4442      0.374     -1.187      0.235      -1.178       0.289

```sigma2         7.6314      0.298     25.568      0.000       7.046       8.216

===================================================================================

2. Run all cells in sequence to:Ljung-Box (L1) (Q):                   0.00   Jarque-Bera (JB):                64.14

   - Fetch AAPL stock data from 2020-01-01 to 2023-12-31Prob(Q):                              1.00   Prob(JB):                         0.00

   - Perform exploratory data analysisHeteroskedasticity (H):               1.56   Skew:                            -0.05

   - Train and evaluate ARIMA modelProb(H) (two-sided):                  0.00   Kurtosis:                         4.38

   - Train and evaluate LSTM model===================================================================================

   - Generate predictions for the next trading day

Warnings:

## Project Structure[1] Covariance matrix calculated using the outer product of gradients (complex-step).

/usr/local/lib/python3.10/dist-packages/keras/src/layers/rnn/rnn.py:204: UserWarning: Do not pass an `input_shape`/`input_dim` argument to a layer. When using Sequential models, prefer using an `Input(shape)` object as the first layer in the model instead.

```  super().__init__(**kwargs)

AAPL-Stock-Market-Predictor/Epoch 1/100

├── src/21/21 ━━━━━━━━━━━━━━━━━━━━ 13s 112ms/step - loss: 0.0891 - val_loss: 0.0089

│   └── AAPL_Stock_Predictor.ipynb  # Main analysis notebookEpoch 2/100

├── requirements.txt                 # Python dependencies21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 84ms/step - loss: 0.0154 - val_loss: 0.0046

├── LICENSE                          # MIT LicenseEpoch 3/100

├── .gitignore                      # Git ignore rules21/21 ━━━━━━━━━━━━━━━━━━━━ 3s 124ms/step - loss: 0.0082 - val_loss: 0.0053

└── README.md                       # Project documentationEpoch 4/100

```21/21 ━━━━━━━━━━━━━━━━━━━━ 6s 169ms/step - loss: 0.0079 - val_loss: 0.0041

Epoch 5/100

## Results21/21 ━━━━━━━━━━━━━━━━━━━━ 6s 202ms/step - loss: 0.0071 - val_loss: 0.0047

Epoch 6/100

### Data Overview21/21 ━━━━━━━━━━━━━━━━━━━━ 4s 200ms/step - loss: 0.0077 - val_loss: 0.0040

- Dataset: AAPL stock data (2020-01-01 to 2023-12-29)Epoch 7/100

- Total records: 1006 entries21/21 ━━━━━━━━━━━━━━━━━━━━ 5s 190ms/step - loss: 0.0069 - val_loss: 0.0049

- No missing values or duplicatesEpoch 8/100

21/21 ━━━━━━━━━━━━━━━━━━━━ 3s 126ms/step - loss: 0.0081 - val_loss: 0.0044

### ARIMA Model PerformanceEpoch 9/100

- RMSE: 30.8421/21 ━━━━━━━━━━━━━━━━━━━━ 2s 83ms/step - loss: 0.0067 - val_loss: 0.0035

- Model: ARIMA(1,1,1)Epoch 10/100

21/21 ━━━━━━━━━━━━━━━━━━━━ 3s 130ms/step - loss: 0.0070 - val_loss: 0.0042

### LSTM Model PerformanceEpoch 11/100

- Train RMSE: 4.6821/21 ━━━━━━━━━━━━━━━━━━━━ 4s 82ms/step - loss: 0.0065 - val_loss: 0.0048

- Test RMSE: 10.35Epoch 12/100

- Next day prediction: ~$192.68 (as of last run)21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 85ms/step - loss: 0.0068 - val_loss: 0.0032

Epoch 13/100

### Sample Visualizations21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 83ms/step - loss: 0.0067 - val_loss: 0.0078

- Stock price time seriesEpoch 14/100

- Daily returns distribution21/21 ━━━━━━━━━━━━━━━━━━━━ 3s 97ms/step - loss: 0.0078 - val_loss: 0.0048

- Correlation heatmapEpoch 15/100

- Moving averages (50-day, 200-day)21/21 ━━━━━━━━━━━━━━━━━━━━ 3s 130ms/step - loss: 0.0073 - val_loss: 0.0030

- Volatility analysisEpoch 16/100

- Model prediction plots21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 84ms/step - loss: 0.0063 - val_loss: 0.0033

Epoch 17/100

## Contributing21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 82ms/step - loss: 0.0061 - val_loss: 0.0028

Epoch 18/100

This project was completed as part of the VilearnX internship program. For suggestions or improvements, please open an issue or submit a pull request.21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 84ms/step - loss: 0.0057 - val_loss: 0.0029

Epoch 19/100

## License21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 85ms/step - loss: 0.0052 - val_loss: 0.0027

Epoch 20/100

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 82ms/step - loss: 0.0052 - val_loss: 0.0030

Epoch 21/100

## Acknowledgments21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 115ms/step - loss: 0.0053 - val_loss: 0.0038

Epoch 22/100

- VilearnX for the internship opportunity21/21 ━━━━━━━━━━━━━━━━━━━━ 4s 167ms/step - loss: 0.0060 - val_loss: 0.0029

- Yahoo Finance for stock dataEpoch 23/100

- Open-source Python libraries used in this project21/21 ━━━━━━━━━━━━━━━━━━━━ 3s 81ms/step - loss: 0.0058 - val_loss: 0.0040

Epoch 24/100

---21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 83ms/step - loss: 0.0051 - val_loss: 0.0023

Epoch 25/100

**Author**: Dwaipayan Dasgupta21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 81ms/step - loss: 0.0051 - val_loss: 0.0023

**Internship**: VilearnX Data Analytics and Machine LearningEpoch 26/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 3s 100ms/step - loss: 0.0050 - val_loss: 0.0022
Epoch 27/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 3s 133ms/step - loss: 0.0055 - val_loss: 0.0022
Epoch 28/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 86ms/step - loss: 0.0053 - val_loss: 0.0030
Epoch 29/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 83ms/step - loss: 0.0050 - val_loss: 0.0030
Epoch 30/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 3s 83ms/step - loss: 0.0047 - val_loss: 0.0021
Epoch 31/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 83ms/step - loss: 0.0050 - val_loss: 0.0032
Epoch 32/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 3s 92ms/step - loss: 0.0045 - val_loss: 0.0027
Epoch 33/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 3s 130ms/step - loss: 0.0052 - val_loss: 0.0020
Epoch 34/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 90ms/step - loss: 0.0049 - val_loss: 0.0018
Epoch 35/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 84ms/step - loss: 0.0047 - val_loss: 0.0023
Epoch 36/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 3s 84ms/step - loss: 0.0044 - val_loss: 0.0032
Epoch 37/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 84ms/step - loss: 0.0045 - val_loss: 0.0017
Epoch 38/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 3s 118ms/step - loss: 0.0046 - val_loss: 0.0017
Epoch 39/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 4s 180ms/step - loss: 0.0039 - val_loss: 0.0032
Epoch 40/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 86ms/step - loss: 0.0050 - val_loss: 0.0016
Epoch 41/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 87ms/step - loss: 0.0042 - val_loss: 0.0016
Epoch 42/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 84ms/step - loss: 0.0042 - val_loss: 0.0018
Epoch 43/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 3s 84ms/step - loss: 0.0040 - val_loss: 0.0015
Epoch 44/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 4s 130ms/step - loss: 0.0042 - val_loss: 0.0016
Epoch 45/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 4s 84ms/step - loss: 0.0044 - val_loss: 0.0021
Epoch 46/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 3s 83ms/step - loss: 0.0041 - val_loss: 0.0015
Epoch 47/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 3s 85ms/step - loss: 0.0036 - val_loss: 0.0014
Epoch 48/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 4s 132ms/step - loss: 0.0035 - val_loss: 0.0014
Epoch 49/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 92ms/step - loss: 0.0044 - val_loss: 0.0016
Epoch 50/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 83ms/step - loss: 0.0037 - val_loss: 0.0013
Epoch 51/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 3s 91ms/step - loss: 0.0034 - val_loss: 0.0013
Epoch 52/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 84ms/step - loss: 0.0036 - val_loss: 0.0014
Epoch 53/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 84ms/step - loss: 0.0041 - val_loss: 0.0016
Epoch 54/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 4s 131ms/step - loss: 0.0035 - val_loss: 0.0013
Epoch 55/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 83ms/step - loss: 0.0039 - val_loss: 0.0019
Epoch 56/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 82ms/step - loss: 0.0034 - val_loss: 0.0012
Epoch 57/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 3s 82ms/step - loss: 0.0034 - val_loss: 0.0013
Epoch 58/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 3s 84ms/step - loss: 0.0034 - val_loss: 0.0017
Epoch 59/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 3s 118ms/step - loss: 0.0040 - val_loss: 0.0018
Epoch 60/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 108ms/step - loss: 0.0038 - val_loss: 0.0012
Epoch 61/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 88ms/step - loss: 0.0043 - val_loss: 0.0012
Epoch 62/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 84ms/step - loss: 0.0039 - val_loss: 0.0016
Epoch 63/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 83ms/step - loss: 0.0037 - val_loss: 0.0014
Epoch 64/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 84ms/step - loss: 0.0032 - val_loss: 0.0012
Epoch 65/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 3s 124ms/step - loss: 0.0034 - val_loss: 0.0011
Epoch 66/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 4s 85ms/step - loss: 0.0033 - val_loss: 0.0012
Epoch 67/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 84ms/step - loss: 0.0033 - val_loss: 0.0018
Epoch 68/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 86ms/step - loss: 0.0032 - val_loss: 0.0012
Epoch 69/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 86ms/step - loss: 0.0032 - val_loss: 0.0012
Epoch 70/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 3s 124ms/step - loss: 0.0031 - val_loss: 0.0017
Epoch 71/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 3s 118ms/step - loss: 0.0029 - val_loss: 0.0013
Epoch 72/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 86ms/step - loss: 0.0033 - val_loss: 0.0011
Epoch 73/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 3s 91ms/step - loss: 0.0032 - val_loss: 0.0011
Epoch 74/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 87ms/step - loss: 0.0037 - val_loss: 0.0011
Epoch 75/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 3s 89ms/step - loss: 0.0034 - val_loss: 0.0011
Epoch 76/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 4s 141ms/step - loss: 0.0031 - val_loss: 0.0016
Epoch 77/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 93ms/step - loss: 0.0031 - val_loss: 0.0011
Epoch 78/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 84ms/step - loss: 0.0034 - val_loss: 0.0011
Epoch 79/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 86ms/step - loss: 0.0028 - val_loss: 0.0010
Epoch 80/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 85ms/step - loss: 0.0028 - val_loss: 0.0010
Epoch 81/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 3s 92ms/step - loss: 0.0028 - val_loss: 9.9528e-04
Epoch 82/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 3s 136ms/step - loss: 0.0030 - val_loss: 0.0011
Epoch 83/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 89ms/step - loss: 0.0028 - val_loss: 0.0012
Epoch 84/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 85ms/step - loss: 0.0030 - val_loss: 0.0011
Epoch 85/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 3s 87ms/step - loss: 0.0027 - val_loss: 0.0010
Epoch 86/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 3s 86ms/step - loss: 0.0025 - val_loss: 0.0011
Epoch 87/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 3s 116ms/step - loss: 0.0027 - val_loss: 0.0015
Epoch 88/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 3s 119ms/step - loss: 0.0027 - val_loss: 9.6854e-04
Epoch 89/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 87ms/step - loss: 0.0026 - val_loss: 9.6158e-04
Epoch 90/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 84ms/step - loss: 0.0028 - val_loss: 0.0012
Epoch 91/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 83ms/step - loss: 0.0030 - val_loss: 8.8658e-04
Epoch 92/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 84ms/step - loss: 0.0026 - val_loss: 9.6213e-04
Epoch 93/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 94ms/step - loss: 0.0031 - val_loss: 9.2678e-04
Epoch 94/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 3s 134ms/step - loss: 0.0026 - val_loss: 9.6380e-04
Epoch 95/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 85ms/step - loss: 0.0026 - val_loss: 9.8107e-04
Epoch 96/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 84ms/step - loss: 0.0023 - val_loss: 9.0993e-04
Epoch 97/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 82ms/step - loss: 0.0026 - val_loss: 9.1397e-04
Epoch 98/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 83ms/step - loss: 0.0028 - val_loss: 9.4039e-04
Epoch 99/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 2s 85ms/step - loss: 0.0026 - val_loss: 0.0011
Epoch 100/100
21/21 ━━━━━━━━━━━━━━━━━━━━ 3s 119ms/step - loss: 0.0029 - val_loss: 0.0015

24/24 ━━━━━━━━━━━━━━━━━━━━ 2s 47ms/step
5/5 ━━━━━━━━━━━━━━━━━━━━ 0s 23ms/step
Train RMSE: 4.6790689666332534
Test RMSE: 10.346889508996654

1/1 ━━━━━━━━━━━━━━━━━━━━ 0s 28ms/step
Predicted price for next day: 192.6816864013672

![image](https://github.com/user-attachments/assets/ef4c7d5c-d2f7-41c9-a5ee-265efcd41bbb)

![download](https://github.com/user-attachments/assets/c62c9955-b4e5-46ee-9639-ccfb8eac8ba8)
![download (1)](https://github.com/user-attachments/assets/c024ee30-7024-4fb5-be80-3ff406853fe2)
![image](https://github.com/user-attachments/assets/5cb34b6a-c246-4d12-b53c-0cfa5ec21a24)
![image](https://github.com/user-attachments/assets/235b6c0a-a3ee-49f9-9aa6-8aaa42da56a1)


![download (2)](https://github.com/user-attachments/assets/d9318e86-7167-414d-bbd4-74b47a41be61)
![download (3)](https://github.com/user-attachments/assets/8adfce43-ddf0-4197-8639-9a20d8bb1fbe)
