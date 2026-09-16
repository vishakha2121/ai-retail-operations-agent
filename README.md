# 🚀 AI Retail Operations Agent

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-0.109-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![SQLite](https://img.shields.io/badge/SQLite-3-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-AI-4285F4?style=for-the-badge&logo=google&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

**An AI-powered retail operations platform that optimizes pricing, promotions, inventory, store operations, and customer engagement across multiple retail locations.**

[Features](#-features) • [Tech Stack](#-tech-stack) • [Installation](#-installation) • [API Docs](#-api-endpoints) • [Screenshots](#-screenshots)

</div>

---

## 📖 Overview

**AI Retail Operations Agent** is a full-stack web application designed to help retail businesses make data-driven decisions across all operational areas. It combines classical Machine Learning models (forecasting, optimization, clustering) with Google's Gemini LLM to deliver actionable insights for store managers and retail executives.

The platform simulates a real-world retail chain with multiple stores, thousands of products, and historical sales data — then uses AI to answer questions like:

- 📈 *"What will be the demand for Product X next month?"*
- 💰 *"What's the optimal price to maximize profit for Product Y?"*
- 👥 *"Which customers are at risk of churning?"*
- 🎁 *"Which promotion will drive the highest ROI?"*
- 📦 *"When should I reorder inventory for Store Z?"*

---

## ✨ Features

### 📊 Dashboard & Analytics
- Real-time KPIs (Revenue, Sales, Inventory Turnover)
- Interactive charts (Sales trends, Revenue by store)
- AI-generated business insights panel
- Multi-store performance comparison

### 💰 Dynamic Pricing
- ML-based price optimization using demand elasticity
- Competitor price comparison
- Price history tracking
- Automated discount recommendations

### 📦 Inventory Management
- Real-time stock tracking per store
- Automated reorder point calculation
- Safety stock optimization
- Low-stock and overstock alerts
- Dead stock identification

### 🎁 Promotions Engine
- Create & manage promotional campaigns
- Promotion effectiveness tracking (ROI analysis)
- AI-suggested discount percentages
- A/B testing support

### 📈 Demand Forecasting
- 30/60/90-day sales predictions
- Product-level and store-level forecasts
- Seasonality detection
- Confidence intervals

### 👥 Customer Analytics
- K-Means customer segmentation
- Churn prediction (Random Forest)
- Customer lifetime value (CLV) estimation
- Personalized recommendations

### 🏪 Multi-Store Operations
- Manage operations across multiple locations
- Store-wise performance metrics
- Regional trend analysis

### 🤖 AI Assistant (Gemini)
- Natural language chat interface
- Business insight generation
- Anomaly detection & explanations
- Custom report generation

### 🔗 ERP Integration
- Mock ERP data synchronization
- Product catalog sync
- Order management integration
- Inventory sync logs

### 🔐 Authentication
- JWT-based secure login/register
- Role-based access control
- Password hashing (bcrypt)

---

## 🛠️ Tech Stack

### Backend
| Technology | Purpose |
|-----------|---------|
| **Python 3.10+** | Core language |
| **FastAPI** | REST API framework |
| **SQLAlchemy** | ORM for database |
| **SQLite** | Lightweight database |
| **Pandas / NumPy** | Data manipulation |
| **Scikit-learn** | ML models |
| **Prophet / Linear Regression** | Forecasting |
| **SciPy / PuLP** | Optimization |
| **Google Gemini API** | LLM insights |
| **Pydantic** | Data validation |
| **JWT (python-jose)** | Authentication |
| **Uvicorn** | ASGI server |

### Frontend
| Technology | Purpose |
|-----------|---------|
| **React 18** | UI library |
| **Vite** | Build tool |
| **Tailwind CSS** | Styling |
| **Recharts** | Charts & graphs |
| **Axios** | HTTP client |
| **React Router v6** | Routing |
| **Zustand** | State management |
| **Lucide React** | Icons |
| **React Hot Toast** | Notifications |

### Database
- **SQLite** (lightweight, CPU-friendly, no setup needed)

### AI / ML
- **Google Gemini 1.5 Flash** (free tier)
- **Scikit-learn** models (KMeans, RandomForest, LinearRegression)
- **Prophet** for time-series forecasting

---

## 📁 Project Structure



---

## 🚀 Installation

### Prerequisites
- Python 3.10 or higher
- Node.js 18+ and npm
- Git
- Google Gemini API key ([get it free here](https://aistudio.google.com/app/apikey))

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/vishakha2121/ai-retail-operations-agent.git
cd ai-retail-operations-agent


# Navigate to backend
cd backend

# Create virtual environment
python -m venv venv

# Activate (Windows)
venv\Scripts\activate

# Activate (Mac/Linux)
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Create .env file
copy .env.example .env    # Windows
cp .env.example .env      # Mac/Linux


cd frontend

# Install dependencies
npm install

# Create .env file
copy .env.example .env    # Windows
cp .env.example .env      # Mac/Linux