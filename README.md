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

![bitcoin 1](https://user-images.githubusercontent.com/75474944/119855024-32b4a600-bf2f-11eb-9228-5a08c44daca2.png)
---
![bitcoin 02](https://user-images.githubusercontent.com/75474944/119855035-35170000-bf2f-11eb-8687-b5700bbf43eb.png)
---
![bitcoin 2](https://user-images.githubusercontent.com/75474944/119855044-36482d00-bf2f-11eb-9d1c-33b4640a2a55.png)
---
![bitcoin 3](https://user-images.githubusercontent.com/75474944/119855047-37795a00-bf2f-11eb-922e-62bc5a723a8a.png)
---
![bitcoin 4](https://user-images.githubusercontent.com/75474944/119855049-3811f080-bf2f-11eb-9afe-15715bc98b2f.png)
---
![bitcoin 5](https://user-images.githubusercontent.com/75474944/119855054-39431d80-bf2f-11eb-954d-8db6847af4af.png)
---

# Time Series Forecasting in Facebook Prophet
![bitcoin fbp 1](https://user-images.githubusercontent.com/75474944/119855207-58da4600-bf2f-11eb-8e8b-3128645258af.png)
![bitcoin fbp 2](https://user-images.githubusercontent.com/75474944/119855217-5972dc80-bf2f-11eb-8fd0-139570bf2b6e.png)
