# **DeltaStream: Netflix Data Warehouse with Delta Lake**

## **Overview**
**DeltaStream** is a modern **data lakehouse** project designed to build a scalable and reliable data warehouse using **Delta Lake** for Netflix movie data. This project integrates **raw, unstructured data** from Netflix with the power of Delta Lake's ACID transactions, enabling reliable data processing, cleaning, and analysis.

DeltaStream processes and stores large volumes of movie metadata, ratings, genres, and other key attributes, transforming them into structured, query-friendly formats. With **Delta Lake**, we can combine the flexibility of a **data lake** with the performance and reliability of a **data warehouse**, enabling efficient querying and real-time analytics.

## **Project Highlights**
- **Data Collection**: Gather and clean raw Netflix movie data (e.g., titles, genres, ratings, release years) from diverse sources.
- **Data Transformation**: Clean, transform, and normalize the data to ensure consistency and structure for analysis.
- **Lakehouse Architecture**: Utilize **Delta Lake** for ACID transactions, data versioning, and optimized performance in a scalable lakehouse setup.
- **ETL Pipeline**: Build an automated **ETL pipeline** to continuously refresh and update the data warehouse with the latest movie information.
- **Advanced Analytics**: Provide fast, powerful querying capabilities for trend analysis, genre popularity, and more.

## **Key Features**
- **Delta Lake**: Leverage Delta Lake for reliable, consistent data storage with features like time travel and schema enforcement.
- **Scalable Architecture**: Efficiently handle large-scale Netflix movie data.
- **Optimized for Performance**: Fast querying and real-time analytics for insightful decision-making.
- **Automated ETL Pipeline**: Seamless data extraction, transformation, and loading with minimal manual intervention.
- **Insights and Analytics**: Run powerful queries for trend analysis, movie ratings, and content recommendations.

## **Technologies Used**
- **Delta Lake** on top of **Apache Spark** for scalable data processing.
- **Python** and **PySpark** for data cleaning, transformation, and automation.
- **SQL** for querying the data warehouse.
- **Azure Data Lake Storage** (for storing raw data in the lake).
