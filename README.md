# Stock Market Data Streaming & Analytics Pipeline

This project demonstrates a complete end-to-end data pipeline for real-time stock market data using Python, Apache Kafka, Amazon S3, AWS Glue, and Amazon Athena.

## 📖 Overview

- **Data Ingestion:** Live stock market data is fetched using Python and sent to an Apache Kafka cluster as streaming events.
- **Streaming Architecture:** Kafka serves as a reliable message broker, decoupling data producers and consumers for scalable processing.
- **Storage:** A Kafka consumer writes the ingested data to Amazon S3 in a structured format, enabling durable and cost-effective storage.
- **Data Cataloging:** AWS Glue Crawlers automatically catalog the stock data stored in S3, creating an AWS Glue Data Catalog for schema discovery and metadata management.
- **Analysis:** Amazon Athena leverages the Glue Catalog to run SQL queries directly on the S3-stored data, enabling fast, serverless analytics on streaming stock data.

## 🚀 Technologies Used

- Python
- Apache Kafka
- Amazon S3
- AWS Glue
- Amazon Athena

## 📝 Features

✅ Real-time stock data streaming  
✅ Scalable Kafka-based architecture  
✅ Automated data cataloging with AWS Glue  
✅ Serverless analytics using Amazon Athena  
✅ End-to-end demonstration of streaming, storage, cataloging, and querying

---

Feel free to fork, clone, and adapt this pipeline for your own real-time data streaming and analytics use cases!
