---
title: "Kaggle competitions"
excerpt: "Personal project"
header:
  image: /assets/images/pexels-anna-nekrashevich-6801648.jpg
  teaser: assets/images/pexels-anna-nekrashevich-6801648.jpg
---

I simply started Kaggle competitions to imporve my data analysis skills, but now being Kaggle Master in competition is my goal. I would like to introduce to you about Kaggle competitions I have completed so far.

Libraries used: Tensorflow, Pytorch, Pandas, Numpy, Ray (for multiprocessing)

My Kaggle profile: [here](https://www.kaggle.com/hhkang94/account)

# **Jane Street market prediction**

*Duration: 2020.11.24 ~ 2021.08.24*

*Topic: Test your model against future real market data*

*Tags: finance, time series,  custom metric, generalization, binary classification*

{% include figure image_path="/assets/images/chart-1905225_1920.jpg" alt="this is a placeholder image" %}

**Difficulties**

- Noises in real market data
- Correlations between variables
- Skewed data distribution
- Selection of better prediction model

{% include figure image_path="/assets/images/paper-3309829_1920.jpg" alt="this is a placeholder image" %}

**Task**

Build quantitative trading model to maximize returns using market data from a major global stock exchange. Next, Test the predictiveness of built models  against future market returns.

{% include figure image_path="/assets/images/man-677770_1920.jpg" alt="this is a placeholder image" %}

**Approach**

- Cleaned data to remove noises
- Performed feature engineering
- Trained DL models for large dataset
- Applied Ensemble to improve predictiveness

**Result**

Ranked 31st/4245 (top 1%) - silver medal

# Google Smartphone Decimeter Challenge

*Duration: 2021.05.13 ~ 2021.08.05*

*Topic: Improve high precision GNSS positioning and navigation accuracy on smartphones.*

*Tags: time series data, geospatial analysis, mobile and wireless, signal processing, custom metric*

{% include figure image_path="/assets/images/navigation-1048294_1920.jpg" alt="this is a placeholder image" %}

**Difficulties**

- Noises and outliers in signal data
- Bias in measurements due to many factors
- Effects of signal interference and surroundings
- Sensor fusion

{% include figure image_path="/assets/images/paper-3309829_1920.jpg" alt="this is a placeholder image" %}

**Task**

Train a prediction model to compute location down to decimeter or even centimeter resolution based on ground truth, raw GPS, and IMU datasets. Next, test your results.

{% include figure image_path="/assets/images/man-677770_1920.jpg" alt="this is a placeholder image" %}

**Approach**

- Smoothing for noise and outlier removal
- Kalman-filter based sensor fusion

**Result**

Ranked 293rd /810 (Top 37%)