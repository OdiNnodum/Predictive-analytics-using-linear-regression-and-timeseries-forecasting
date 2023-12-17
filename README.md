# Predictive-analytics-using-linear-regression-and-timeseries-forecasting

 </h2>

<h2>Description</h2>
This project involved using different predictive models to predict the number of crypto-currency websites. Linear regression and timeseries forecasting were the predictive techniques employed for this project. In terms of the linear regression, the hypothesis was Bitcoin price, on its own, can be used to predict the number of crypto-currency websites created. Hence, this was examined and tested.

<h2>Languages Used</h2>

- <b>Python 

<h2>Project walk-through </h2>
<p align="center">
Data collection 1 (Web-scraping): <br/>
<img src="https://imgur.com/YoYBqSk.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/ST58LH2.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/5qTZryC.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />
Data collection 2 (Using SQL to query data lake):  <br/>
<img src="https://imgur.com/E7J93fP.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />
Renaming columns so they match for join: <br/>
<img src="https://imgur.com/9XhYsgh.png" height="50%" width="30%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/vHi3dzC.png" height="50%" width="30%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/0VKq8tF.png" height="50%" width="30%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/9ESNBIj.png" height="50%" width="30%" alt="Disk Sanitization Steps"/>
<br />
<br />
Concatenating datasets into one and dropping duplicates:  <br/>
<img src="https://imgur.com/YsDjNpN.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/wGxKa2d.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />
Data exploration showing minimal correlation between Bitcoin and Website count:  <br/>
<img src="https://imgur.com/O1AABhC.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />
Combining Cryptocurrency and website datasets into one:  <br/>
<img src="https://imgur.com/1466Wgt.png" height="30%" width="30%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/plNesL5.png" height="30%" width="30%" alt="Disk Sanitization Steps"/>
<br />
<br />
Bulding first linear regression model:  <br/>
<img src="https://imgur.com/b74FQi1.png" height="30%" width="30%" alt="Disk Sanitization Steps"/>
<br />
<br />
Using correlation to find useful features:  <br/>
<img src="https://imgur.com/qjgXwHK.png" height="30%" width="30%" alt="Disk Sanitization Steps"/>
<br />
<br />
Adding features with correlation to improve linear regression model (2nd model):  <br/>
<img src="https://imgur.com/ALQcfSm.png" height="30%" width="30%" alt="Disk Sanitization Steps"/>
<br />
<br />
Removing outliers/Feature engineering to improve linear regression model:  <br/>
<img src="https://imgur.com/EqmSjuE.png" height="30%" width="30%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/FAi7bqZ.png" height="30%" width="30%" alt="Disk Sanitization Steps"/>
<br />
<br />
Optimised model:  <br/>
<img src="https://imgur.com/F7bVJGo.png" height="30%" width="30%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/FAi7bqZ.png" height="30%" width="30%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h2>Timeseries Forecasting</h2> <br/>
<p align="center">
Data exploration:  <br/>
<img src="https://imgur.com/fVGoC3U.png" height="30%" width="30%" alt="Disk Sanitization Steps"/>
<br />
<br />
Downsampling data to weeks for smoothening:  <br/>
<img src="https://imgur.com/0cR5XZJ.png" height="30%" width="30%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/41VlZhO.png" height="30%" width="30%" alt="Disk Sanitization Steps"/>
<br />
<br />
Further data exploration to check for seasonality/trends: <br />
<img src="https://imgur.com/RO3LwIa.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />
Timeseries model (Blue line - actual data, yellow - prediction against actual data, red - forecast: <br />
<img src="https://imgur.com/4sQgsal.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />
Timeseries model evaluation: <br />
<img src="https://imgur.com/WdCODtI.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
