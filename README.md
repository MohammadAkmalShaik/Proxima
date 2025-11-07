# 📊 Team Tasks Dashboard - Hackathon Nellore 2025

> AI-Powered Team Productivity Dashboard with Advanced Analytics, Forecasting, and Real-time Monitoring

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?logo=mongodb&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?logo=fastapi)
![AI](https://img.shields.io/badge/AI-Gemini_2.5_Pro-orange)

---

## 🎯 Overview

A comprehensive **multi-user productivity dashboard** designed for **Hackathon Nellore 2025**, featuring AI-powered insights, real-time monitoring, and advanced analytics.

### ✨ Key Features

- 🔐 Multi-User Authentication with JWT
- 📤 CSV Upload with Drag & Drop
- 📊 6 Chart Types (Pie, Bar, Donut, Radar, Area)
- 🤖 AI Chatbot (Google Gemini 2.5 Pro)
- 💡 5 AI Insights (Auto-Generated)
- ⚡ Real-time Monitoring
- 🔔 Smart Alerts & Notifications

---

## 🚀 Quick Start

### Prerequisites
- Python 3.11+
- Node.js 18+
- MongoDB
- Yarn

### Installation

```bash
# Backend
cd backend
pip install -r requirements.txt
uvicorn server:app --host 0.0.0.0 --port 8001

# Frontend
cd frontend
yarn install
yarn start
```

**Access**: http://localhost:3000

---

## 📦 Tech Stack

**Frontend**: React 19, Recharts, Shadcn UI, Tailwind CSS
**Backend**: FastAPI, Motor (MongoDB), Pydantic, JWT
**AI**: Google Gemini 2.5 Pro
**Database**: MongoDB

---

## 🎨 Features

### 1. Overview
- 4 Hero Cards, 6 Metrics, 6 Charts
- CSV Upload Button (Auto-generates insights)

### 2. Tasks
- Filterable task table
- Status, Member, Priority filters

### 3. Queries (AI Chatbot)
- Context-aware Q&A
- Gemini 2.5 Pro powered

### 4. AI Insights (Auto-Generated!)
1. Velocity & Efficiency Analysis
2. Workload Forecasting
3. Anomaly Detection
4. Team Sentiment Analysis
5. Performance Benchmarking

### 5. Settings
- Notifications & Alerts
- Dashboard Preferences
- AI Configuration

---

## 🤖 AI Auto-Generation

**Insights generate automatically:**
- ✅ When opening AI Insights page
- ✅ After uploading CSV file
- ✅ Manual refresh available

---

## 🔐 Authentication

- JWT tokens (7-day validity)
- Bcrypt password hashing
- Multi-user data isolation

---

## 📊 Database

**MongoDB**: `mongodb://localhost:27017/test_database`

**Collections:**
- users
- tasks
- insights
- chat_history

---

## 🧪 Test Credentials

```
Email: demo@test.com
Password: demo123
```

---

## 📚 Documentation

**Complete Guide**: `PROJECT_DOCUMENTATION.md` (500+ lines)

---

## 🎓 Hackathon Requirements

✅ AI Integration
✅ Forecasting
✅ Sentiment Analysis
✅ Anomaly Detection
✅ Team Benchmarking
✅ Real-time Monitoring
✅ Velocity Tracking
✅ Auto-Generation

---

## 🔗 Live Demo

https://teamtasks-dashboard.preview.emergentagent.com

---

**Made with ❤️ for Hackathon Nellore 2025**
