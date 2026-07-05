

# Citi Bike Big Data Analytics

An end-to-end Big Data analytics project built with **Apache Spark** to process, analyze, and model historical NYC Citi Bike trip data. The project combines large-scale data engineering, exploratory analysis, business intelligence, and machine learning to uncover mobility patterns and support data-driven city planning decisions.

Developed for the **Big Data & NoSQL Databases** course at the German International University (GIU).

---

## Project Objectives

- Clean and validate large-scale trip data
- Engineer meaningful features from raw ride information
- Detect noisy and inconsistent records
- Perform analytical queries using Spark SQL and the DataFrame API
- Train machine learning models to predict rider gender
- Generate interactive dashboards from Spark query outputs stored as Parquet files

---

## Dataset

The Citi Bike dataset contains historical ride information including:

- Ride start and end timestamps
- Start and end station information
- Geographic coordinates
- Bike identifiers
- Rider demographics
- User type
- Gender

---

## Tech Stack

- Apache Spark
- PySpark
- Spark SQL
- Spark DataFrame API
- Spark MLlib
- Python
- Parquet
- Jupyter Notebook / Google Colab

---

## Data Engineering

The project includes comprehensive data preprocessing and validation.

### Feature Engineering

- Rider Age
- Trip Duration (seconds)
- Trip Distance (Haversine Formula)
- Estimated Riding Speed (km/h)
- Period of Day
- Start Month
- Age Group
- Season

### Data Validation

Noise detection was performed by flagging:

- Trips shorter than 60 seconds
- Unrealistic riding speeds (>40 km/h)
- Invalid rider ages
- Missing station names
- Missing bike identifiers

---

## Analytical Insights

Business-oriented analyses include:

- Round-trip percentage by user type
- Most popular start stations
- Peak riding hours
- Trip duration across age groups
- Seasonal riding patterns
- Bike utilization and maintenance candidates
- Subscriber vs Customer destination analysis
- Most popular station pairs
- Riding behavior by gender
- Weekday vs Weekend comparisons

Each analysis includes a business interpretation explaining how the results can support operational and planning decisions.

---

## Machine Learning

Three Spark ML classification models were developed to predict rider gender.

### Models

- Logistic Regression
- Decision Tree
- Random Forest

The pipeline includes:

- Feature selection
- Data normalization
- VectorAssembler
- Train/Test split
- Model evaluation
- Accuracy comparison
- Feature importance analysis

---

## Interactive Dashboard

Interactive dashboards were created using **Parquet datasets generated from Spark query outputs**.

The dashboard summarizes:

- Hourly trip demand
- Seasonal trends
- Weekday vs Weekend behavior
- Station popularity
- User demographics
- Bike utilization
- Trip duration and speed analysis

---

## Skills Demonstrated

- Big Data Processing
- Data Cleaning
- Feature Engineering
- Spark SQL
- Spark DataFrames
- User Defined Functions (UDFs)
- Geospatial Analysis
- Machine Learning with Spark ML
- Data Visualization
- Predictive Analytics
- Business Intelligence

---

