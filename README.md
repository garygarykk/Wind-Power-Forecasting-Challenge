# Wind Power Forecasting Challenge
This project is about a dataset for Spatial Dynamic Wind Power Forecasting (SDWPF) Challenge at KDD Cup 2022 from Baidu.  

SDWPF provides the wind power data of 134 wind turbines from a wind farm over half a year with their relative positions and internal statuses. The attributes include Wind turbine ID, day of the record, created time of the record, wind speed recorded by the anemometer, reactive power,
active power, etc.  

There is a total of 4727520 records of data, containing 245 days of turbine data for each of those 134 turbines, with 10 minutes intervals for each record on a specific day and turbine. The project is about using the data to predict the active power ( $Patv$ ) in the next 2 days, which contains 288 values. The input sequence can be different, but the maximum length of input should be at most 14 days.
