# Time-Series-Analysis-On-Road-Dataset
This project consist of a time series analysis (TSA) model on a Road Dataset built/created using Facebook's Prophet Library.

Prophet is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. It works best with time series that have strong seasonal effects and several seasons of historical data. Prophet is robust to missing data and shifts in the trend, and typically handles outliers well.
After extensive research in this domain of time series, prophet was selected to exploit or make most use out of its forecasting abilities. 
At its core it is the sum of three functions of time plus an error term: growthg(t), seasonality s(t), holidays h(t) , and error e_t :

![alt text](https://miro.medium.com/max/448/1*xb5z_Nh5RXDagT_cg9r6iA.webp)

After training a basic model using prophet some of its hyperparameters were fine tuned like Possible overfitting due to seasonality constraint, missing the diminishing trend and so on. 
Facebook Prophet is easy to use, fast, and doesn’t face many of the challenges that some other kinds of time-series modeling algorithms face.
