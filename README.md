# PYSPARK-X-DBT
This project demonstrates an **end-to-end data engineering pipeline** built with **PySpark**, **dbt**, and a **Data Lake** architecture.  
It covers data ingestion, transformation, and modeling following a **medallion architecture (Bronze → Silver → Gold)** using industry-standard tools.

![image alt](https://github.com/Charvi-M-J/PYSPARK-X-DBT/blob/daf4bb61ec12dbc17f29c661855cb9532b50421b/screenshot.png)


🔁 Pipeline Flow
1. Streaming Data Source:  
   - Input data in CSV format is continuously streamed into the system.
2. Ingestion (Bronze Layer):
   - Raw data is ingested into the Data Lake using Apache Spark.
3. Transformation (Silver Layer):  
   - Cleaned and refined data is processed using PySpark and stored in the Silver layer.
4. Modeling (Gold Layer):  
   - The final Star Schema models are created using dbt (Data Build Tool) for analytics and reporting.
5. Visualization / Analysis: 
   - The transformed data is ready for BI tools or ML model consumption.

![image alt](https://github.com/Charvi-M-J/PYSPARK-X-DBT/blob/90e63ac3753d549f950b02e3608822067eca1a0e/Screenshot%202025-10-07%20190043.png)

![image alt](https://github.com/Charvi-M-J/PYSPARK-X-DBT/blob/b68ea73d1368d144f3779eda9a150991be47f5ec/Screenshot%202025-10-07%20185935.png)

![image alt](https://github.com/Charvi-M-J/PYSPARK-X-DBT/blob/0737b42c33a78d05dc4159d8b5d5b451fa383e77/Screenshot%202025-10-07%20200528.png)

🌟 Key Learnings

* Data ingestion with PySpark and streaming CSVs

* Building modular ETL pipelines

* Implementing Medallion architecture (Bronze–Silver–Gold)

* Data modeling using dbt and Star Schema
