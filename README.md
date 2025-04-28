# Honey Adulteration and Anomaly Detection using Autoencoders

This mini-project aims to detect cases of honey adulteration using **neural network autoencoders**, an unsupervised technique that learns a compact representation of data and identifies abnormal samples.

## Objective

* Identify potentially falsified honey samples based on their physicochemical properties.
* Use an **autoencoder** to reconstruct data and detect anomalies based on reconstruction error.

## Methodology

1. **Data Exploration**:
   * Descriptive statistics
2. **Preprocessing**:
   * Data cleaning
   * Normalization
3. **Anomaly Detection with Autoencoder**:
   * Building a simple autoencoder network (encoder + decoder)
   * Training on presumed normal data
   * Calculating reconstruction error
   * Threshold defined from error distribution
   * Detection of samples with error above threshold
4. **Evaluation and Visualization**:
   * Distribution of detected anomalies

## Technologies Used

* Python 3
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* **TensorFlow / Keras** (for autoencoders)
