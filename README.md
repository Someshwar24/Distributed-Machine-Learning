Distributed Banking Analytics and Customer Term Deposit Prediction

Project Overview

This project explores distributed data processing and machine learning using banking customer data. The objective is to predict whether a customer will subscribe to a term deposit using classification techniques, while learning how Hadoop, Hive, and Apache Spark support data analytics.

Problem Statement

Banks need to identify customers who are more likely to subscribe to term-deposit products. This project analyzes historical banking data, applies data preprocessing and machine learning techniques, and explores distributed technologies to understand how banking analytics can scale to larger datasets.

Objectives

Understand distributed storage using Hadoop HDFS.

Explore SQL-based analytics using Hive.

Process banking data using Apache Spark and PySpark.

Build a Logistic Regression classification workflow.

Explore streaming concepts using simulated banking records.

Understand data partitioning and parallel processing.

Dataset

Dataset: bank.csv

Records: 4,521

Columns: 17

Target variable: y

The target variable indicates whether a customer subscribed to a term deposit:

yes — Subscribed

no — Not subscribed

Technologies Used

Python

Pandas

Hadoop and HDFS

Apache Hive

Apache Spark

PySpark ML

Google Colab

Project Components

1. Hadoop and HDFS

Explores distributed file storage using Hadoop Distributed File System (HDFS), which is designed to store large datasets across multiple machines.

2. Hive

Introduces HiveQL, a SQL-like language used to query and analyze structured data within the Hadoop ecosystem.

3. Spark and PySpark

Uses Spark DataFrames for data inspection and preprocessing. The machine learning workflow includes categorical encoding, feature assembly, Logistic Regression, and model interpretation.

4. Spark Streaming Concepts

Simulates incoming banking records in batches, assigns event timestamps, shuffles events to demonstrate out-of-order arrival, and identifies events older than a watermark-like threshold.

Note: The described streaming demonstration uses Pandas and is not a complete Spark Structured Streaming implementation.

5. Data Partitioning and Parallelism

Explores how datasets can be divided into smaller partitions for concurrent processing. Spark supports distributed execution when configured with suitable cluster resources.

Machine Learning Workflow

Load and inspect the banking dataset.

Examine column types and summary statistics.

Handle missing values and selected extreme values.

Encode categorical features.

Assemble the input features into a feature vector.

Convert the target variable into numerical labels.

Split data into training and testing sets.

Train a Logistic Regression classifier using PySpark ML.

Evaluate predictions using classification metrics.

Analyze model coefficients to understand feature associations.

Key Learning Outcomes

Understanding the roles of Hadoop, HDFS, Hive, and Spark.

Preparing categorical and numerical data for machine learning.

Building a classification workflow using PySpark ML.

Understanding event-time processing and out-of-order records.

Learning the concepts of data partitioning, parallelism, and scalability.

Future Improvements

Complete and validate the Hive analytics workflow.

Implement genuine Spark Structured Streaming with a streaming source and watermarking.

Improve preprocessing to avoid data leakage.

Evaluate the model using precision, recall, F1-score, ROC-AUC, and a confusion matrix.

Compare local and distributed execution on larger datasets.

Configure a multi-node Spark cluster to demonstrate distributed execution.

Repository Contents

Distributed_ML_Bank_Analytics.ipynb — Project notebook.

bank.csv — Banking dataset, if included in the repository.

Update the file list to match the actual files uploaded to GitHub.

Disclaimer

This project is intended for educational purposes. Predictions should not be used for real banking decisions without further validation, fairness assessment, privacy safeguards, and business review.          
