# NeuroIgnite — Medical Equipment Failure Prediction

**One-line summary:**  
Predictive maintenance system for hospital equipment using an XGBoost machine learning model to reduce downtime and maintenance costs.

---

## 🎥 Demo
- **YouTube Demo (3–6 min):** [https://youtu.be/-Cn62CdDh14](https://youtu.be/-Cn62CdDh14)  
- *(If live demo unavailable, see video above — due to Railway free-tier expiry)*

---

## 🧰 Tech Stack

| Layer | Technology |
|--------|-------------|
| **Frontend** | React.js, Tailwind CSS |
| **Backend** | Node.js, Express.js |
| **ML Service** | Python, FastAPI, Scikit-learn, XGBoost |
| **Database** | MongoDB |
| **Hosting** | Railway (Backend & ML), Vercel (Frontend) |

---

## 🏗️ Architecture

See `ARCHITECTURE.png` (attached in folder).

### Key Components
1. **Frontend (React + Tailwind)** – Hospital admin dashboard for predictions and history.  
2. **Backend (Node.js + Express)** – API layer for data flow and authentication.  
3. **ML Microservice (FastAPI + XGBoost)** – Predicts probability of equipment failure.  
4. **Database (MongoDB)** – Stores device info, logs, and prediction history.  
5. **Deployment (Railway + Vercel)** – Deployed via CI/CD pipelines from GitHub.

---

## 🚀 Core Features
1. Predicts equipment failure probability based on operational data.  
2. Displays prediction history for trend monitoring.  
3. User-friendly dashboard for hospital admins.  
4. API integration between Node.js backend and FastAPI model.  
5. Quick deployment via Railway and Vercel for cost-effective hosting.

**Trade-offs:**  
- Accuracy depends on dataset quality and size.  
- Real-time IoT integration is a planned improvement.

---

## ⚙️ Setup & Run (Local)

### 1. Clone the repository
```bash
git clone <your-repo-url>
cd NeuroIgnite
2. Backend Setup
bash
Copy code
cd backend
npm install
cp .env.example .env
npm start
3. ML Service Setup

cd ../ml_service
python -m venv venv
venv\Scripts\activate    
pip install -r requirements.txt
uvicorn app:app --reload --port 8000
4. Frontend Setup
bash
Copy code
cd ../frontend
npm install
npm run dev


