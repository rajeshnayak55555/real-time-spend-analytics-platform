# 🚀 Real-Time Spend Analytics Platform

🔥 Built with production-grade architecture inspired by real-world financial systems (Morgan Stanley / Citi-like pipelines)

## 📌 Overview
Real-time data pipeline using Kafka, PySpark, MLflow, and FastAPI for fraud detection.

## 🧱 Architecture
Kafka → Spark → ML → API

## ⚙️ How to Run
1. docker-compose up -d
2. python ingestion/kafka_producer.py
3. spark-submit streaming/spark_streaming_job.py
4. python ml_models/train_model_mlflow.py
5. uvicorn api.app:app --reload