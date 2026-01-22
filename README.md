# Big Data Stock Analytics Pipeline

End-to-end big data pipeline using Hadoop, Spark (PySpark), and MongoDB for real-time NLP analytics and sentiment-driven stock price forecasting with SARIMAX and LSTM models.

---

## 🚀 Project Overview

This project demonstrates the design and implementation of a scalable big data architecture capable of:

- Ingesting structured and unstructured data (CSV, APIs)
- Distributed storage using HDFS
- Distributed processing using Apache Spark (PySpark)
- NoSQL persistence using MongoDB
- Real-time streaming analytics using Reddit API
- NLP processing (tokenization, sentiment analysis, summarization)
- Time-series forecasting using SARIMAX and LSTM models
- Dashboard-based visualization and evaluation

The pipeline supports both batch processing and real-time streaming workloads.

---

## 🏗️ Architecture

**Data Sources**
- Stock price CSV files
- Twitter / Reddit API feeds

**Ingestion**
- Batch ingestion via PySpark
- Real-time ingestion via Spark streaming

**Storage**
- Hadoop HDFS (raw and processed data)
- MongoDB (enriched datasets)

**Processing**
- Data cleaning, transformation, joins
- Spark SQL analytics
- NLP pipelines

**Analytics**
- Sentiment analysis (VADER / TextBlob)
- Forecasting models (SARIMAX, LSTM)
- Dashboard visualization

---

## 🛠️ Tech Stack

- Python
- Apache Spark (PySpark)
- Hadoop HDFS
- MongoDB / PyMongo
- NLP: VADER, TextBlob, HuggingFace
- Machine Learning: SARIMAX, LSTM (TensorFlow / Keras)
- Visualization: Matplotlib / dashboards

---

## 📂 Repository Structure

---

## 🎓 Academic Use Disclaimer

This repository and its contents were created for **academic and educational purposes only**.  
The project demonstrates concepts in big data architecture, distributed processing, database benchmarking, and predictive analytics.

It is **not intended for production use, financial decision-making, or commercial deployment**.  
Any forecasts, analyses, or results should be interpreted strictly as learning outcomes and technical demonstrations.
