# Sentiment Analysis on Twitter Data Using Apache Hive and MapReduce

## Overview
This project involves sentiment analysis on Twitter data using Apache Hive for data warehousing and MapReduce for processing. The goal is to extract tweets, analyze sentiments (positive, negative, neutral), and store the data in Hive for further analysis.

## Tools Used
- **Apache Hive**: Data warehousing framework on Hadoop.
- **MapReduce**: Distributed processing technique.

## Steps

### 1. Setting Up Hadoop Cluster
- **Install Hadoop**: Follow the installation guide for your OS.
- **Configure Cluster**: Set up a distributed Hadoop cluster.

### 2. Apache Hive Installation
- **Download and Install Hive**: Get the Apache Hive package and follow installation instructions.
- **Configuration**: Set up environmental variables and paths for Hive.

### 3. Data Collection (Twitter API)
- **Access Twitter API**: Obtain API keys from Twitter Developer Platform.
- **Extract Tweets**: Use Python or a suitable language to fetch tweets based on criteria.

### 4. Data Preparation
- **Clean Data**: Remove irrelevant characters, links, and format issues.
- **Transform Data**: Prepare data for analysis and storage in Hive.

### 5. Hive Table Creation
- **Define Schema**: Create a Hive table structure for the prepared data.
- **Load Data**: Populate the Hive table with the prepared data.

### 6. Sentiment Analysis with MapReduce
- **MapReduce Job**: Develop a program to analyze sentiments in Hive using MapReduce.
- **Sentiment Classification**: Classify sentiments (positive, negative, neutral).
- **Output**: Store analysis results in Hive tables.

### 7. Querying and Visualization
- **Hive Queries**: Use HiveQL to query sentiment analyzed data.
- **Visualization**: Utilize tools like Tableau or Matplotlib for visual representations.

## Objective
This project demonstrates sentiment analysis on Twitter data using Apache Hive and MapReduce. It outlines setting up tools
