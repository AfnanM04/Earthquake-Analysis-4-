# Temporal and Geospatial Analysis of Earthquake Data with Apache Spark
jupyter notebook for Earthquake Analysis project (unit 4-AIHT)

Link for dataset:
https://www.kaggle.com/datasets/danielpe/earthquakes

ABOUT THE PROJECT-

This project is a comprehensive data analysis and preparation workflow designed to examine global earthquake patterns using big data technologies—specifically, PySpark, the Python API for Apache Spark. Given the potential size and complexity of seismic datasets, Spark is an ideal tool for handling, transforming, and analyzing this data at scale. The dataset used contains a wide range of features such as timestamp, earthquake magnitude, depth, latitude, longitude, and other location-based attributes, allowing for a detailed temporal and spatial study of seismic activity.

Unlike traditional tools like Pandas, which may struggle with memory limitations on large datasets, PySpark offers distributed computing capabilities that can handle millions of records efficiently. The project takes advantage of these features to quickly load and explore the dataset, extract useful insights, and prepare the data for downstream tasks like machine learning or visualization. The code performs a thorough inspection of the schema, identifies numeric and non-numeric columns, generates descriptive statistics, and determines the temporal coverage of the dataset.

Moreover, the code hints at future development by importing components for feature scaling, vector assembly, regression models, and pipeline construction, laying the groundwork for building predictive models in later stages. Overall, this project sets up a solid foundation for both exploratory data analysis and advanced machine learning on seismic data using scalable tools.
