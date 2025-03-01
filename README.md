# NYC Taxi Data Machine Learning Project

## Overview
This project explores the NYC Taxi dataset, leveraging machine learning techniques for data visualization and anomaly detection. The dataset consists of millions of taxi trip records, including timestamps, geolocation, fares, and passenger counts. The project demonstrates how to efficiently process big data, reduce dimensionality, and detect anomalies, ultimately uncovering hidden patterns in taxi trips.

## Project Objectives
- **Big Data Handling**: Efficiently process large-scale trip data using Python and PySpark.
- **Dimensionality Reduction**: Implement Principal Component Analysis (PCA) and t-SNE to visualize high-dimensional features.
- **Anomaly Detection**: Identify unusual trips using statistical and clustering-based methods.

## Key Features
The dataset contains the following features:
- `VendorID`
- `tpep_pickup_datetime`
- `tpep_dropoff_datetime`
- `passenger_count`
- `trip_distance`
- `pickup_longitude`
- `pickup_latitude`
- `RateCodeID`
- `store_and_fwd_flag`
- `dropoff_longitude`
- `dropoff_latitude`
- `payment_type`
- `fare_amount`
- `extra`
- `mta_tax`
- `tip_amount`
- `tolls_amount`
- `improvement_surcharge`
- `total_amount`

## What Was Done
1. **Data Loading**: Loaded 48 million taxi ride records using PySpark.
2. **Data Sampling & Filtering**: Applied stratified sampling and filtering to gather a sample of 10,000 rides and downsampled it further to 8,500 rides after removing outliers from key features.
3. **Data Analysis**: Analyzed the key features using PySpark for efficient data processing.
4. **Data Visualization**: Created visualizations such as histograms, hexbin plots, and pie charts to better understand the data.
5. **Dimensionality Reduction**: Used PCA and t-SNE to reduce the data to 2D and prepare it for machine learning purposes.

## Tools & Technologies
- **PySpark**: For handling and processing big data efficiently.
- **Python**: For data analysis, visualization, and machine learning tasks.
- **Pandas**: For data manipulation.
- **Matplotlib/Seaborn**: For data visualization.
- **Scikit-learn**: For machine learning tasks such as dimensionality reduction.

## Installation

To run this project locally, ensure that you have the following dependencies installed:

```bash
pip install pyspark
pip install pandas
pip install matplotlib
pip install seaborn
pip install scikit-learn
