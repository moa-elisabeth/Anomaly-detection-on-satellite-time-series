# Anomaly-detection-on-satellite-time-series

This repository contains the algorithms used to detect anomalies in time-series. The algorithms used are a CNN Autoencoder and a LSTM Autoencoder, which were later benchmarked to analyse which algorithm is best suited for detecting anomalies on satellite time-series.

The data used comes from the NAB repository, where data from \RealAWSCloudwatch and \RealKnownCause was used for training and testing the algorithms. --> https://github.com/numenta/NAB/tree/master/data

The CNN autoencoder was built with reference to the following repository --> https://github.com/keras-team/keras-io/blob/master/examples/timeseries/timeseries_anomaly_detection.py

The LSTM autoencoder was built with reference to the following repository --> https://github.com/susanli2016/Machine-Learning-with-Python/blob/master/Timeseries%20anomaly%20detection%20using%20LSTM%20Autoencoder%20JNJ.ipynb
