# covid_arima

An ARIMA model to forecast total confirmed covid-19 cases in Australia. Utilising covid-19 data from Our World in Data (https://raw.githubusercontent.com/owid/covid-19-data/master/public/data/owid-covid-data.csv). 

Explored multiple orders for ARIMA(p,d,q) using Akaike information criterion (AIC) and differencing orders using ACF and PACF. Concluding that ARIMA(5,2,5) produces an MAE of 53,0002.22, MAPE of 0.0047 and RMSE of 230.22.
![covid_arima_image_10](https://user-images.githubusercontent.com/62190453/220231106-edb621c5-35f4-40ff-98f9-1d58f31db167.png)
