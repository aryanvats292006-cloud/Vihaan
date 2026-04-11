# Krishi Bharat APP under the open innovation 
#  Krishi Bharat

### AI-Powered Digital Farm Management Platform for Rural India

---

##  Overview

Krishi Bharat is an **AI-driven, multi-agent digital platform** designed to empower **small and marginal farmers** by providing **personalized, real-time agricultural intelligence**.

It integrates:

*  Weather insights
*  Market intelligence
*  Livestock health monitoring
*  AI-based advisory

into a **single unified system**, eliminating fragmented decision-making.

---

##  Problem Statement

Farmers in all over India face:

* Lack of real-time localized weather data
* No access to optimized mandi price insights
* Limited veterinary support
* Language and digital literacy barriers
* Fragmented and unreliable advisory systems

---

##  Solution

Krishi Bharat uses a **Multi-Agent AI Architecture** to convert raw agricultural data into **simple, actionable recommendations**.

###  Core Idea:

> “Turn complex agricultural data into **clear decisions** for farmers”

---

##  System Architecture

```text
Farmer (App / WhatsApp / Voice)
        ↓
API Gateway (FastAPI)
        ↓
AI Agent Layer
   ├── Weather Agent
   ├── Market Agent
   ├── Livestock Agent
   └── Advisory Orchestrator
        ↓
External APIs + Database
        ↓
Decision Engine
        ↓
Multilingual Output (Text + Voice)
```

---

## 🤖 AI Agent System

| Agent              | Function                                 |
| ------------------ | ---------------------------------------- |
|  Weather Agent  | Predicts rainfall, frost, climate risks  |
|  Market Agent    | Analyzes mandi prices & selling strategy |
|  Livestock Agent | Tracks animal health & vaccinations      |
|  Advisory Agent  | Combines all insights into final advice  |

---

##  Tech Stack

###  Backend

* FastAPI (Python)
* Uvicorn
* REST APIs

###  AI / ML

* OpenAI / LLMs
* LangChain / Agent Framework
* Time-series models (future)

###  Multilingual + Voice

* Google Translate / IndicTrans
* Whisper (Speech-to-Text)
* TTS APIs

###  Database

* MongoDB (farmer profiles)
* PostgreSQL (structured data)

###  Integrations

* IMD / Weather APIs
* Agmarknet (mandi prices)

###  Cloud

* AWS / GCP

---

##  Key Features

 Real-time weather alerts
 Smart mandi price recommendations
 Livestock health tracking
 Multilingual voice-based interaction
 WhatsApp integration (planned)
 Personalized advisory

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
└── README.md
```

---

##  Setup Instructions

###  Clone Repository

```bash
git clone https://github.com/your-repo/krishi-bharat.git
cd krishi-bharat/backend
```

###  Install Dependencies

```bash
pip install -r requirements.txt
```

###  Run Server

```bash
uvicorn app.main:app --reload
```

###  Open API Docs



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

##  Future Scope

*  IoT Integration (soil sensors, cattle tracking)
*  Advanced ML predictions (crop yield, disease detection)
*  WhatsApp & Voice Assistant deployment
*  Offline-first support for rural areas
*  Government & NGO integrations

---

##  Business Model

* Freemium model for farmers
* B2B partnerships with agri कंपनियां
* Veterinary consultation services
* Government & NGO collaborations

---

##  Team

* **Team Name:** Purple Hand Gang
* **Team Lead:** Alankar Akinchan
* **Members:** Ayush Kaushik, Rajat Rawal
* **University:** Delhi Technological University

---

##  Impact

*  Reduce crop losses
*  Increase farmer income
*  Improve livestock health
*  Enable sustainable agriculture

---

##  License

MIT License

---

##  Contributions

Pull requests are welcome. For major changes, please open an issue first.

---

##  Acknowledgements

* Government agricultural datasets
* Open-source AI community
* Rural farmers for inspiration

---

