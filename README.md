# Smart-Kissan 🌾

**Smart-Kissan** is an AI-powered agricultural intelligence and farm risk-decision platform tailored for Indian agriculture and modern farming. It brings together real-time hyper-local weather forecasting, AI-driven plant disease diagnostics, agricultural mandi market price intelligence, government schemes discovery, and a smart multilingual conversational assistant.

---

## 🌟 Key Features

- 🌿 **AI Crop Disease Diagnosis**: Upload crop/leaf images for real-time disease detection, severity assessment, and treatment plans powered by Gemini AI.
- ⛅ **Hyper-Local Weather Intelligence**: Accurate weather forecasts, temperature, precipitation chance, and alerts powered by Open-Meteo.
- 📈 **Mandi Market Discovery**: Live commodity pricing across states and mandis with price trends to help farmers sell at the best rates.
- 🤖 **Kisan Sahayak Assistant**: Multilingual AI conversational assistant that speaks and answers queries in local languages.
- 🏛️ **Government Agricultural Schemes**: Instant directory of government subsidies and welfare schemes (PM-KISAN, KCC, Soil Health Card, etc.).
- 🚜 **Plot & Farm Management**: Manage agricultural plots, crop cycles, and farm records seamlessly.

---

## 🏗️ Architecture & Tech Stack

### Frontend (`client/`)
- **Framework**: React 19 + Vite
- **Styling**: Tailwind CSS + Shadcn UI primitives + Lucide Icons
- **Authentication & Database**: Supabase
- **Internationalization**: Multilingual support (English, Hindi, Gujarati, Marathi, Tamil)

### Backend (`server/`)
- **Runtime**: Node.js & Express
- **AI Engine**: Google Generative AI (Gemini)
- **External Integrations**: Open-Meteo Weather APIs & Mandi Market Feed

---

## 🚀 Quick Start

### 1. Backend Setup
```bash
cd server
npm install
npm run dev
```

### 2. Frontend Setup
```bash
cd client
npm install
npm run dev
```

The application will be live at `http://localhost:5173`.
