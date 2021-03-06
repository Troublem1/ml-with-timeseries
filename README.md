﻿## Tutorial: Machine Learning with Time Series

Round of applause to Andrii Gakhov and his video tutorials!

Instructor: [Vaibhav Srivastav](https://www.linkedin.com/in/vaibhavs10/)

### Abstract

Time series is an important instrument to model, analyze and predict data collected over time. In this talk, we learn the basic theoretical concepts without going deep into mathematical aspects, study different models, and try them in practice using StatsModels, Prophet, scikit-learn, and keras.

### Required Software

Attendees will need to bring a laptop with [scikit-learn](http://scikit-learn.org/stable/install.html) and [pandas](http://pandas.pydata.org/pandas-docs/stable/install.html) (and their dependencies) already installed. Installing the [Anaconda distribution of Python](https://www.continuum.io/downloads) is an easy way to accomplish this. Both Python 2 and 3 are welcome.

I will be leading the tutorial using the IPython/Jupyter notebook, and have added a pre-written notebook to this repository. I have also created a Python script that is identical to the notebook, which you can use in the Python environment of your choice.

### Description

Nowadays, it is hard to find a company that doesn’t collect various time-dependent data in different forms, for instance, it can be a daily number of visitors and monthly sales for online stores, available resources and stock for factories, number of food poisoning cases for hospitals, and so on. And the reason why all that data is carefully collected, because it can provide meaningful insides not only about the past but can be used to predict and prepare for the future.

In this presentation, we discuss how to analyze and forecast those data, that is called time series. Many people already did that many times while trying to predict the weather on the weekend, guessing the currency exchange rate for tomorrow, or just by expecting great discounts on Christmas sales. Of course, some patterns are truly obvious, like weekly or monthly changes, and overall tendency, others are not. However, all these aspects can be formalized and learned automatically using the power of mathematics and computer science.

The first part is dedicated to the theoretical introduction of time series, where listeners can learn or refresh in memory the essential aspects of time series’ representations, modeling, and forecasting. In the second part, we dive into the most popular time series forecast models - stochastic models (e.g., Autoregressive integrated moving average (ARIMA)), artificial neural networks (e.g., seasonal recurrent neural network) and Support Vector Machines (SVR). Along the way, we show at practice how these models can be applied to a real-world dataset of UK visits by providing examples using such popular Python libraries as StatsModels, Prophet, scikit-learn, and keras.

With these guidelines in mind, you should be better equipped to deal with time series in your everyday work and opt-in for the right tools to analyze them.

GitHub repository: https://github.com/vaibhavs10/ml-for-timeseries/

### Prerequisite Knowledge

Attendees to this tutorial should be comfortable working in Python, should understand the basic principles of machine learning, and should have at least basic experience with both pandas and scikit-learn. However, no knowledge of advanced mathematics is required.

### Dataset

To demonstrate the mentioned in the presentation models, I will use the following dataset:

#### OS visits to UK (All visits)
The dataset represents the monthly total number of visits to the UK by overseas residents (in thousands)<br>from January 1980 to October 2017.
Source: [Office for National Statistics](https://www.ons.gov.uk/peoplepopulationandcommunity/leisureandtourism/timeseries/gmaa/ott)

* Jupyter Notebook: https://github.com/vaibhavs10/ml-for-timeseries/blob/master/look-into-the-data.ipynb

### Stochastic Models

As a stochastic model for seasonal time series, in the presentation, I describe the Seasonal Autoregressive Integrated Moving Average (SARIMA) model.

* Jupyter Notebook: https://github.com/vaibhavs10/ml-for-timeseries/blob/master/stochastic-models.ipynb
* Python package: [Statsmodels](https://www.statsmodels.org/)


Another example is Facebook Prophet model that implements an additive regression model which is essentially a sophisticated curve-fitting model.

* Jupyter Notebook: https://github.com/vaibhavs10/ml-for-timeseries/blob/master/prophet.ipynb
* Python package: [Facebook Prophet](https://github.com/facebook/prophet)


Author
-------

* Vaibhav Srivastav <vaibhavs10@gmail.com>


Read More
---------

[Seasonal ARIMA with Python](http://www.seanabu.com/2016/03/22/time-series-seasonal-ARIMA-model-in-python/)

[TimeSeries Decomposition in Python with statsmodels and Pandas](http://www.cbcity.de/timeseries-decomposition-in-python-with-statsmodels-and-pandas)

[How to Make Out-of-Sample Forecasts with ARIMA in Python](https://machinelearningmastery.com/make-sample-forecasts-arima-python/)

[Introduction to ARIMA: nonseasonal models](https://people.duke.edu/~rnau/411arim.htm)

[book] [Time Series by A.W. van der Vaart](https://ia600202.us.archive.org/2/items/TimeSeries/TimeSeries.pdf)

[github] [Time series predictions with Keras](https://github.com/gcarq/keras-timeseries-prediction)

[Time Series Prediction with LSTM Recurrent Neural Networks in Python with Keras](https://machinelearningmastery.com/time-series-prediction-lstm-recurrent-neural-networks-python-keras/)

[book] [Time series analysis by Jan Grandell](https://www.math.kth.se/matstat/gru/sf2943/tsform.pdf)

[Seasonal Decomposition of Time Series by Loess](https://align-alytics.com/seasonal-decomposition-of-time-series-by-loessan-experiment/)

[How To Identify Patterns in Time Series Data: Time Series Analysis](http://www.statsoft.com/Textbook/Time-Series-Analysis)

[paper] [Another look at measures of forecast accuracy](https://robjhyndman.com/papers/mase.pdf)

[book] [An Introductory Study on Time Series Modeling and Forecasting](https://arxiv.org/pdf/1302.6613.pdf)

[paper] [PSO based Neural Networks vs. Traditional Statistical Models for Seasonal Time Series Forecasting](https://arxiv.org/pdf/1302.6615.pdf)

[paper] [Seasonal Time Series Forecasting Models based on Artificial Neural Network](https://pdfs.semanticscholar.org/619e/9bcd2a36a193141600c4e797a8fde15abadf.pdf)

[paper] [Improving artificial neural networks’ performance in seasonal time series forecasting](https://sci-hub.tw/https://www.sciencedirect.com/science/article/pii/S0020025508002958#)

[Forecasting strong seasonal time series with artificial neural networks](http://www.academia.edu/2576481/Forecasting_strong_seasonal_time_series_with_artificial_neural_networks)

[Recurrent Neural Networks. Part 1: Theory](https://www.slideshare.net/gakhov/recurrent-neural-networks-part-1-theory)

[slides] [Time Series Analysis - Moving average and ARMA processes](http://www.etsii.upm.es/ingor/estadistica/Carol/TSAtema4petten.pdf)

[How to Make Out-of-Sample Forecasts with ARIMA in Python](https://machinelearningmastery.com/make-sample-forecasts-arima-python/)

[Cryptocurrency Predictions with ARIMA](https://www.kaggle.com/taniaj/cryptocurrency-predictions-with-arima)

[Using Facebook Prophet Forecasting Library to Predict the Weather](https://arnesund.com/2017/02/26/using-facebook-prophet-forecasting-library-to-predict-the-weather/)

[Forecasting Time-Series data with Prophet](http://pythondata.com/forecasting-time-series-data-prophet-part-1/)

[Prophet: forecasting at scale](https://research.fb.com/prophet-forecasting-at-scale/)

[Playing with Prophet on Bike Sharing Demand in Washington, D.C.](https://towardsdatascience.com/playing-with-prophet-on-bike-sharing-demand-time-series-1f14255f7ff0)

[paper] [Using support vector machines for time series prediction](https://www.sciencedirect.com/science/article/abs/pii/S0169743903001114)

