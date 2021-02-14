# Covid19_Prediction
With this case study we try to forecast COVID-19 cases for the state of Maharashtra which has the highest number of COVID-19 cases in India. For which we use ARIMA model, prior to which we need to pre-process the data and rectify all the typo's. After which we need to format data and change index to Date and then check data for stationarity. And then feed data to ARIMA model. But after forecasting we found that model forecasted higher number of cases then actual cases, which leads us conclusion that as ARIMA model does not include non-quantitative factors like public awareness, Quality of testing, anti-body generation and many others which would lead to increase or decrease in number of cases. Hence we can say that we would not be able to forecast the exact number of cases using ARIMA model. 
