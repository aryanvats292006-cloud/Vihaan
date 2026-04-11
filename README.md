#  Krishi Bharat

### AI-Powered Multilingual Digital Farm Intelligence Platform

---

##  Overview

Krishi Bharat is a **full-stack AI-powered agricultural intelligence platform** designed to support **small and marginal farmers in rural India**.

It integrates **weather data, mandi prices, livestock health, and AI advisory** into a **single, unified, multilingual system** that delivers **simple, actionable insights** via **mobile app, voice interface, and WhatsApp (planned)**.

---

##  Problem Statement

Farmers all over India face:

*  Fragmented agricultural tools
*  Lack of real-time localized weather insights
*  No optimized market selling strategy
*  Limited veterinary support
*  Language & digital literacy barriers
*  Low trust in digital advisory systems

---

##  Solution

Krishi Bharat solves this using a **Multi-Agent AI System** that converts raw agricultural data into:

>  Clear, personalized, and real-time farming decisions

---

##  Core Features

*  **Real-Time Weather & Risk Alerts**
*  **Smart Mandi Price Optimization**
*  **Livestock Health Monitoring & Alerts**
*  **AI-Based Personalized Advisory**
*  **Voice-Based Interaction (Multilingual)**
*  **Mobile-First Design for Rural Users**
*  **Notifications & Alerts System**
*  **Unified Farm Dashboard**

---

##  System Architecture

```text
User (Mobile App / Voice / WhatsApp)
        ↓
Frontend (Flutter App)
        ↓
API Gateway (FastAPI Backend)
        ↓
AI Agent Layer (Core Intelligence)
   ├── Weather Agent
   ├── Market Agent
   ├── Livestock Agent
   └── Advisory Orchestrator
        ↓
External APIs + Internal Database
        ↓
Decision Engine
        ↓
Multilingual Response (Text + Voice)
```

---

##  AI Agent Architecture

| Agent              | Role                                    |
| ------------------ | --------------------------------------- |
|  Weather Agent  | Fetches & analyzes weather data         |
|  Market Agent    | Predicts mandi price trends             |
|  Livestock Agent | Tracks animal health & alerts           |
|  Orchestrator    | Combines all insights into final advice |

---

##  Complete Tech Stack

###  Frontend

* Flutter (Dart)
* Riverpod (State Management)
* Dio (API Calls)
* speech_to_text (Voice Input)
* flutter_tts (Voice Output)
* Hive (Local Storage)
* Firebase Auth (OTP Login)
* Firebase Cloud Messaging (Notifications)

---

###  Backend

* FastAPI (Python)
* Uvicorn
* REST APIs

---

###  AI / ML Layer

* OpenAI / LLM APIs
* LangChain / CrewAI (Agent orchestration)
* Time-series models (future: price/weather prediction)
* CNN models (future: crop disease detection)

---

###  Multilingual Support

* IndicTrans / Google Translate API
* Whisper (Speech-to-Text)
* Text-to-Speech APIs

---

###  Database

* MongoDB (Farmer profiles & dynamic data)
* PostgreSQL (Structured data)
* Firebase (Realtime sync & auth)

---

###  Cloud & Infrastructure

* AWS / GCP / Azure
* S3 / Cloud Storage
* API Gateway
* Serverless Functions

---

###  External Integrations

* IMD / Weather APIs
* Agmarknet (mandi prices)
* Government agricultural datasets

---

 
##  Project Structure

```bash
krishi-bharat/
│
├── backend/
│   ├── app/
│   │   ├── routes/
│   │   ├── agents/
│   │   ├── services/
│   │   ├── models/
│   │   └── main.py
│   ├── requirements.txt
│   └── .env
│
├── frontend/
│   ├── lib/
│   │   ├── features/
│   │   ├── services/
│   │   ├── providers/
│   │   └── main.dart
│
└── README.md
```

---

##  Setup Instructions

###  Backend Setup

```bash
cd backend
pip install -r requirements.txt
uvicorn app.main:app --reload
```



---

###  Frontend Setup

```bash
cd frontend
flutter pub get
flutter run
```

---

##  Sample API Request

```json
POST /advisory/

{
  "query": "Kal barish hogi kya?",
  "location": "Hisar"
}
```

---

##  User Flow

1. Farmer speaks or types query
2. App detects language
3. Query sent to backend
4. AI agents process data
5. Response generated
6. Output delivered in:

   * Text (local language)
   * Voice (audio response)

---

##  Design Principles

*  Voice-first interaction
*  Multilingual support
*  Works in low-connectivity environments
*  Simple UI for low literacy users
*  Transparent & explainable recommendations

---

##  Future Scope

*  IoT-based smart farming integration
*  Advanced ML predictions (yield, disease)
*  WhatsApp bot deployment
*  Offline-first architecture
*  Government & NGO partnerships
*  Farmer analytics dashboard

---

##  Business Model

* Freemium for farmers
* B2B partnerships (agri कंपनियां, dairy companies)
* Paid veterinary consultations
* Government & NGO collaborations

---

##  Impact

*  Reduce crop losses
*  Increase farmer income
*  Improve livestock health
*  Promote sustainable agriculture
*  Bridge rural digital divide



##  License

MIT License

---

##  Contributing

Contributions are welcome!
Please open an issue before submitting major changes.

---

##  Acknowledgements

* Government agricultural datasets
* Open-source AI community
* Rural farmers for inspiration

---

##  Contact

For collaborations or queries:
📧 [[kaushikayush581@gmail.com](mailto:kaushikayush581@gmail.com)]

---
