# Predicting India's COVID-19 Fourth Wave Using LSTM

### _It presents coronavirus disease (COVID-19) spread forecasting to track the growth of the pandemic._

Deep learning models such as recurrent neural networks (RNN) are well suited for modelling time series data. I used the long short-term memory (LSTM) method to learn the correlation of COVID-19 growth over time for next 90 days based (starting from 21 April 2022) on the number of confirmed cases. This model predicts the likelihood of another wave of infections in May, June and July 2022. The prediction will help the government, policymakers, and business partners to take social and administrative decisions.

## Dataset

The dataset is downloaded from ‘[COVID-19 India Datasets by DataMeet](https://projects.datameet.org/covid19/)’. The information was gathered, cleaned, and compiled by the community from several government websites that are open to all Indians.

Github Repository: https://github.com/datameet/covid19

The dataset has a Creative Commons Attribution 4.0 International Public License. The dataset is downloaded on 10 January 2022 and contains data up to the same date.

We are using the file all_totals.JSON in the data directory.

## Application

We created an LSTM-based prediction model to predict the spread of the COVID-19 pandemic in India. This model excludes transmissibility and other variables when making predictions. The total number of confirmed COVID-19 cases rises steadily over time until a convergent peak curve in COVID-19 data is reached. The findings imply that LSTM is a promising strategy for learning from large amounts of data in order to forecast future outbreaks of COVID-19. Future work should either add fresh data or use a data augmentation approach to increase the training data.
