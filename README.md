# Machine Learning with Spark

[![License](https://img.shields.io/badge/License-Apache_2.0-0D76A8?style=flat)](https://opensource.org/licenses/Apache-2.0)
[![Python 3.11](https://img.shields.io/badge/Python-3.11-green.svg)](https://shields.io/)

## Disclaimer 

This repository contains my submission for all ***Hands-on Labs, Pratice Project and Final Project*** provided by the IBM Skills Network as part of the **[Machine Learning with Spark](https://www.coursera.org/learn/machine-learning-with-apache-spark)** course on Coursera.

This repository stores all Hands-on Labs, Pratice Project and Final Product of The **Machine Learning with Spark** course of the **IBM Data Engineering** track.

## Final Project Scenario

The [Final Project](Final%20Project/final_project.ipynb) will be woring with the modified version of the NASA Airfoil Self Noise dataset. You will clean this dataset, by dropping the duplicate rows, and removing the rows with null values. You will create an ML pipe line to create a model that will predict the SoundLevel based on all the other columns. You will evaluate the model and towards the end you will persist the model.

Given your role as a data engineer, you've been requested to leverage PySpark components to accomplish the tasks.

## Project Overview 

This needs to be achieved by performing the following tasks:

- Perform ETL activity
  - Load a csv dataset
  - Remove duplicates if any
  - Drop rows with null values if any
  - Make transformations
  - Store the cleaned data in parquet format
- Create a  Machine Learning Pipeline
  - Create a machine learning pipeline for prediction
- Evaluate the Model
  - Evaluate the model using relevant metrics
- Persist the Model 
  - Save the model for future production use
  - Load and verify the stored model

## Setup 

Install the required libraries using the provided `requirements.txt` file. The command syntax is:

```bash
python3 -m pip install -r requirements.txt
```

Download the required employees csv file using the terminal command:

```bash
wget https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-BD0231EN-Coursera/datasets/NASA_airfoil_noise_raw.csv
```

## Learner

[Hai Hoang Nguyen](https://www.linkedin.com/in/hoang-ngn/)

## Acknowledgments

* IBM Skills Network © IBM Corporation 2025. All rights reserved.
