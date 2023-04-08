# basic-etl-pipeline

## Docs

- https://medium.com/@topefolorunso/build-an-etl-data-pipeline-using-python-139c6875b046

## Run


## Extract
First, we extract the data. In this stage, we must consider a few things.

* The data source

It is important to consider the source of the data. This is because the source determines how the data will be extracted. Data stored in an API will be extracted differently from data in HTML webpages. Common data sources:
- APIs
- IoT devices
- Databases
- Webpages
- Flat files
- Local server

* The data format

The data format also determines how the data is pulled. HTML data will be extracted differently from CSV data. The list of data formats is not exhaustive. Below are a few examples that you will most likely encounter.
- csv
- parquet
- json
- html
In this article, we will extract a csv file from our local machine using pandas. Pandas is a python module used to process data as Dataframe.

The extract function below extracts a csv file data and converts it to a pandas Dataframe.


