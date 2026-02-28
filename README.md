# 🚑 AEMS – Adaptive Emergency Mobility System

AEMS (Adaptive Emergency Mobility System) is an authenticated, predictive, AI-driven emergency mobility intelligence platform designed specifically for Indian traffic conditions.

## 🚦 Key Features

- Secure emergency vehicle authentication
- Multimodal validation (vehicle registry + siren + GPS simulation)
- Congestion-weighted predictive routing
- Severity-based ripple corridor activation
- Dynamic ETA calculation
- Hospital and command center integration
- Real-time network visualization dashboard

## 🧠 How It Works

1. Emergency vehicle sends a request.
2. System verifies vehicle identity.
3. Traffic congestion is analyzed.
4. Optimal route is calculated.
5. Ripple-based corridor is activated.
6. ETA is optimized and hospital is notified.

## ▶️ How to Run

Install dependencies:

pip install -r requirements.txt

Run the dashboard:

python -m streamlit run aemsprodashboard.py
