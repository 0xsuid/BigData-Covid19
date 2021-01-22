# Big Data Covid-19

Predicting possible infection rate of COVID-19 in Australia using Apache Spark(pyspark) & Python.

## Overview

- Importing the data to Spark.
- Data Preprocessing:
    - Handle null values
    - Select only the relevant rows (i.e., those that include data about Australia)
    - We want to consider the entire country(Australia), so all states should be merged.
- Take the number of confirmed infections as well as the corresponding point in time (the first day could be encoded as 0, the second as 1, and so forth) and apply a regression method (e.g., linear regression) to predict further values.


## References:

- [JHU CSSE COVID-19 Data](https://github.com/CSSEGISandData/COVID-19/blob/master/archived_data/archived_time_series/time_series_19-covid-Confirmed_archived_0325.csv)
- [PySpark Documentation](https://spark.apache.org/docs/latest/api/python/pyspark.sql.html)
- [PySpark Examples](https://sparkbyexamples.com/pyspark)
- [PySpark Cheat Sheet by DataCamp](https://s3.amazonaws.com/assets.datacamp.com/blog_assets/PySpark_SQL_Cheat_Sheet_Python.pdf)