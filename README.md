# Uber Data Pipeline on Google Cloud Platform

This project is about building a data pipeline to extract, transform and load Uber data from external data source over Google Cloud Storage to Google Cloud BigQuery, deployed by Mage and Google Cloud Compute Engine.

## Architecture

![architecture](architecture.png)

## Data Model

![data-model](data-model.png)

## Data Source

Website: https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
Data Dictionary: https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf

## Tech Stack

1. Python
2. Mage (https://www.mage.ai/)
3. Google Cloud Platform
   - Cloud Storage
   - Compute Engine
   - BigQuery

## Commands

### Install Python and pip

sudo apt-get update

sudo apt-get install python3-distutils

sudo apt-get install python3-apt

sudo apt-get install wget

wget https://bootstrap.pypa.io/get-pip.py

sudo python3 get-pip.py

### Install Mage

pip install mage-ai

### Install Google Cloud Library

pip install google-cloud

pip install google-cloud-bigquery
