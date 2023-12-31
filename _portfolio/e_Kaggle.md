---
title: "Kaggle competitions"
excerpt: "Personal project  2020.01.03 - current"
header:
  image: /assets/images/pexels-anna-nekrashevich-6801648.jpg
  teaser: assets/images/pexels-anna-nekrashevich-6801648.jpg
---

I simply started Kaggle competitions to improve my data analysis skills, but now being Kaggle Master in competition is my goal. I would like to introduce to you about Kaggle competitions I have completed so far.

Libraries used: Tensorflow, Pytorch, Pandas, Numpy, Ray (for multiprocessing)

My Kaggle profile: [here](https://www.kaggle.com/hhkang94/account)

# **Jane Street Market Prediction**

*Duration: 2020.11.24 ~ 2021.08.24*

*Topic: Test your model against future real market data*

*Tags: finance, time series,  custom metric, generalization, binary classification*

{% include figure image_path="/assets/images/chart-1905225_1920.jpg" alt="this is a placeholder image" %}

**Difficulties**

- Noises in real market data
- Correlations between variables
- Skewed data distribution
- Selection of better prediction model

**Task**

Build quantitative trading model to maximize returns using market data from a major global stock exchange. Next, test the predictiveness of built models  against future market returns.

**Approach**

- Cleaned data to remove noises
- Performed feature engineering
- Trained DL models for large dataset
- Applied Ensemble to improve predictiveness

**Result**

Ranked 31st/4245 (top 1%) - silver medal

# Google Universal Image Embedding

*Duration: 2022.07.12 ~ 2022.10.11*

*Topic: Create image representations that work across many visual domains.*

*Tags: image, Multiclass Classification*

{% include figure image_path="/assets/images/Embedding.png" alt="this is a placeholder image" %}

**Difficulties**

- Dataset is not provided by host
- Large-scale model training and inference
- Class imbalances in distribution of evaluation dataset
- Insufficient GPU resources

**Task**

In this competition, the developed models are expected to retrieve relevant database images to a given query image (ie, the model should retrieve database images containing the same object as the query). The images in our dataset comprise a variety of object types, such as apparel, artwork, landmarks, furniture, packaged goods, among others.

**Approach**

- Proper dataset collection and processing 
- CLIP model finetuning
- Model architecture and loss function customization

**Result**

Ranked 107th/1022 (Top 11%)

# Kaggle - LLM Science Exam

*Duration: 2023.07.12 ~ 2023.10.11*

*Topic: Use LLMs to answer difficult science questions. *

*Tags: physics, NLP*

{% include figure image_path="/assets/images/LLM.png" alt="this is a placeholder image" %}

**Difficulties**

- Dataset is not provided by host
- Hard science questions 
- Limited resources to implement large scale AI model

**Task**

This competition challenges participants to answer difficult science-based questions written by a Large Language Model.

**Approach**

- Science-topic text dataset collection via Wikipedia
- Data pre-processing for better quality 
- Implementation of open-source large language model
- Improved context generation through Retrieval Augmented Generation (RAG)

**Result**

Ranked 354th/2664 (Top 14%)

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

**Task**

Train a prediction model to compute location down to decimeter or even centimeter resolution based on ground truth, raw GPS, and IMU datasets. Next, test your results.

**Approach**

- Smoothing for noise and outlier removal
- Kalman-filter based sensor fusion

**Result**

Ranked 293rd /810 (Top 37%)
