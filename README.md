## Project Overview

### Objective:

This capstone project is designed to reinforce your understanding of Data Pipeline Orchestration with Apache Airflow. The focus is on implementing a data pipeline that addresses data ingestion, processing, storage, and analysis. The project challenges you to apply your knowledge of Apache Airflow to solve a practical scenario based problem.

### Duration:

1 week (To be submitted on Saturday 19th of October, 2024)

### Deliverables:

- A data pipeline orchestrated with Apache Airflow
- Documentation of the design or architecture of the data pipeline, including the rationale behind key decisions and useful information.


## Project Scenario. 

### Background:
You have been hired by a data consulting organization, who is looking at building a stock market prediction tool that applies sentiment analysis, called CoreSentiment. To perform this sentiment analysis, they plan to leverage the data about the number of Wikipedia page views a company has.

Wikipedia is one the largest public information resources on the internet. Besides the wiki pages, other items such as website pageview counts are also publicly available. To make things simple, they assume that an increase in a company’s website page views shows a positive sentiment, and the company’s stock is likely to increase. On the other hand, a decrease in pageviews tells us a loss in interest, and the stock price is likely to decrease.
Data Source:
Luckily the needed data to perform this sentiment analysis is readily available. The Wikimedia Foundation (the organization behind Wikipedia) provides all pageviews since 2015 in machine-readable format. The pageviews can be downloaded in gzip format and are aggregated per hour per page. Each hourly dump is approximately 50 MB in gzipped text files and is somewhere between 200 and 250 MB in size unzipped.
The pageviews data for October, 2024 can be found here [click here](https://dumps.wikimedia.org/other/pageviews)

## Sample Data Explanation:

![Sample Image](/storage/emulated/0/DCIM/Screenshots/IMG_20241019_232545.jpg)
