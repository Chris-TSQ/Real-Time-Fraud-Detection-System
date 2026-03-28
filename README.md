# Real-Time-Fraud-Detection-System
Real-Time Fraud Detection System
# Real-Time Fraud Detection System
Streaming Data Pipeline + Machine Learning for Financial Transactions

---

## 🚀 Overview
A production-style fraud detection system designed to process financial transactions in real time and detect anomalous behavior using machine learning.

---

## 💼 Business Problem

Financial institutions in Southeast Asia process millions of transactions daily.

Key risks:
- fraud and unauthorized transactions
- delayed detection leads to financial loss
- lack of real-time analytics

---

## ✅ Solution

Designed a system that:
- ingests streaming transaction data
- applies real-time anomaly detection
- flags suspicious transactions instantly
- logs alerts for investigation

---

## 🧠 Engineering Design

Transaction Stream → Processing Layer → ML Model → Alert System

- event-driven architecture
- real-time scoring
- scalable processing pipeline

---

## 📊 Results

- Detected anomalous patterns with ~91% accuracy
- Reduced fraud detection latency from minutes to seconds
- Improved monitoring efficiency

---

## 💰 Business Impact

- Potential reduction in fraud losses
- Faster incident response
- Increased trust in financial systems

---

## 📁 Project Structure

/streaming
    producer.py
    consumer.py

/src
    preprocess.py
    anomaly_model.py
    real_time_scoring.py

/models
    fraud_model.pkl

/reports
    metrics.json

/docs
    architecture.png
