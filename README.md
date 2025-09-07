# Medical Device Failure Prediction System

An end-to-end system designed to predict medical device failures using machine learning and a modern web-based interface.

## 🚀 Project Overview

This system helps hospital admins predict the likelihood of medical device failures by providing a user-friendly dashboard. It integrates machine learning models, a backend API, and a web-based frontend to deliver real-time predictions and insights.

---

## ⚙️ Architecture Overview

```plaintext
Hospital Admin
      ↓
Frontend (React + TailwindCSS)
      ↓
Backend (Node.js + Express.js + MongoDB)
      ↓
FastAPI for ML Model Serving
      ↓
Machine Learning Models (Scikit-Learn, XGBoost)
      ↓
Data Integration (Device Data from IoT or Databases)
