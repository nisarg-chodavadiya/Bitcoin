# Bitcoin Time Series Analysis and Forecasting
## Problem Statment
More insights on fluctuating price of bitcoin. Prediction on future prices.
## Steps
1. Collecting Data for the last 5 years from yahoo finance. All the prices are in USD.
2. EDA, For forecasting the last one year data is used because of higher uncertainty.
3. Forecasting using facebook prophet for next 180 days.

# Dataset
I got this data on https://finance.yahoo.com/quote/BTC-USD?p=BTC-USD </br>
It was the original data I got. (5 Years)
![DataFrame BTC-USD](https://user-images.githubusercontent.com/75474944/119854177-7bb82a80-bf2e-11eb-9b58-09aa550e0dad.png)

# EDA
EDA on DataFame is done for superficially making sense of trends, fluctuation trends.
These are some of it...

![bitcoin 1](https://user-images.githubusercontent.com/75474944/120080705-ce811600-c0d7-11eb-9772-18870c6a1e1a.png)
---
![bitcoin 02](https://user-images.githubusercontent.com/75474944/120080708-d2ad3380-c0d7-11eb-9ec9-22f88b6d575b.png)
---
![bitcoin 2](https://user-images.githubusercontent.com/75474944/120080710-d3de6080-c0d7-11eb-9b2d-5168d98b4759.png)
---
![bitcoin 3](https://user-images.githubusercontent.com/75474944/120080713-d5a82400-c0d7-11eb-9840-133fad853ef9.png)
---
![bitcoin 4](https://user-images.githubusercontent.com/75474944/120080718-d771e780-c0d7-11eb-965b-ce9fe9c96855.png)
---

# Time Series Forecasting in Facebook Prophet
![bitcoin fbp 1](https://user-images.githubusercontent.com/75474944/120080678-b8735580-c0d7-11eb-9a41-34002968bce6.png)
![bitcoin fbp 2](https://user-images.githubusercontent.com/75474944/120080694-bf9a6380-c0d7-11eb-9ff0-0e3f90c87e75.png)

# Time Series Forecasting (RNN-LSTM)
![image](https://user-images.githubusercontent.com/75474944/125106220-062ea500-e0fd-11eb-9662-ecaf1c6d379b.png)
