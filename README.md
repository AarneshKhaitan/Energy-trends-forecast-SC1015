# Welcome to our Repository: A Data-Driven Dive into Global Energy Trends and Renewable Revolution

## Executive Summary

This Mini-Project, developed for SC1015 (Introduction to Data Science and Artificial Intelligence), tackles the pressing challenge of whether renewable energy production can keep pace with rapidly increasing global energy demands. Using advanced forecasting models and anomaly detection, our findings suggest significant gaps in current growth rates, with an expected rise in renewable energy's share from 3.6% in 2017 to only 5.27% by 2047. The project also identifies major energy-consuming countries and offers strategic recommendations for policymakers to enhance renewable energy adoption.

## About

This repository contains a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence). Our project explores the growth potential of renewable energy production relative to global energy consumption through advanced forecasting models. Please view the source code and accompanying documents in the following order:

1. [Data Cleaning , Preprocessing and Exploratory Data Analysis (EDA)](https://github.com/AarneshKhaitan/Energy-trends-forecast-SC1015/blob/main/Data%20Cleaning%20and%20Exploratory%20Data%20Analysis.ipynb)
2. [Forecasting Future Trends](https://github.com/AarneshKhaitan/Energy-trends-forecast-SC1015/blob/main/Forecasting.ipynb)
3. [Anamoly Detection](https://github.com/AarneshKhaitan/Energy-trends-forecast-SC1015/blob/main/AnamolyDetectionOfCountryConsumption.ipynb)

Here are our [slides](https://www.canva.com/design/DAGDD6tanBs/46au_mn7-X3wHc3-88UCgQ/edit?utm_content=DAGDD6tanBs&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton) and [video](https://www.youtube.com/watch?v=1NE82i3MVQQ).

## Contributors

- @aryanjain285 - Machine Learning (SARIMAX, ARIMA, Isolation Forest)
- @AarneshKhaitan - Exploratory Data Analysis (EDA), Data Extraction

## Problem Definition

Our project seeks to answer two key questions:
- Can renewable energy production shares keep up with the drastically increasing global energy consumption?
- Which countries have abnormally high energy consumption, identified using the Isolation Forest model, and how should these nations prioritize increasing renewable energy production?

## Models Used

1. SARIMAX
2. ARIMA
3. Isolation Forest (for detecting anomalies in energy consumption)

## Conclusion

Our extensive analysis through ARIMA and SARIMAX models reveals a critical and urgent issue: renewable energy production is significantly lagging behind the rapid increase in global energy demands. Although there is a projected increase from 3.6% in 2017 to 5.27% by 2047, this growth is insufficient to meet future energy needs sustainably. Solar and biofuel energies, identified as having substantial growth potential, emerge as critical to bridging this gap. Additionally, our use of the Isolation Forest model has pinpointed major economies like China, the United States, Germany, Russia, Canada, Japan, and India as high energy consumers, emphasizing their strategic importance in global efforts to increase renewable energy production.

In light of these findings, we strongly recommend:
- *Direct Investments:* Significantly enhance public and private investments in promising renewable technologies such as solar and biofuels.
- *Supportive Policies:* Governments should enact robust policies and incentives that robustly promote the adoption and technological advancement of renewable energies.
- *Research and Development:* Intensify research efforts to optimize and scale up slower-growing renewable resources like hydro and geothermal.
- *Diversified Portfolio:* Develop a comprehensive energy strategy that includes a diverse mix of renewable energy sources to ensure energy sustainability and security.

## What did we learn from this project?

Key learnings from the project include:
- *Advanced Forecasting Techniques:* Proficiency in ARIMA, SARIMAX for predicting energy trends.
- *Anomaly Detection:* Use of Isolation Forest to identify high energy-consuming countries.
- *Optimal Parameter Tuning:* Skills in hyperparameter tuning and model diagnostics to prevent overfitting/underfitting.
- *Model Evaluation:* Understanding of AIC, BIC, HQIC for assessing model fit.
- *Data Transformation:* Techniques for transforming time series data to mitigate noise and enhance analysis.

## References
1. https://www.investopedia.com/terms/a/autoregressive-integrated-moving-average-arima.asp#:~:text=An%20autoregressive%20integrated%20moving%20average%2C%20or%20ARIMA%2C%20is%20a%20statistical,values%20based%20on%20past%20values
2. https://towardsdatascience.com/time-series-forecasting-with-arima-sarima-and-sarimax-ee61099e78f6
3. https://scikit-learn.org/stable/auto_examples/ensemble/plot_isolation_forest.html
