# ChroniCare AI 🩺  
### AI-Based Chronic Disease Monitoring Assistant

ChroniCare AI is an **assistive, non-diagnostic AI system** designed to support **proactive chronic disease management** by continuously analyzing patient-generated health data, detecting early risk trends, and providing personalized lifestyle recommendations.

The system is built using **LangFlow with IBM Granite models** and **Retrieval-Augmented Generation (RAG)** to ensure safe, explainable, and guideline-aligned AI outputs.

---

## 📌 Problem Statement

Patients with chronic conditions such as **diabetes, hypertension, and asthma** generate large volumes of daily health data through self-monitoring devices and logs.  
Healthcare professionals cannot continuously analyze this data due to time and resource constraints, resulting in:

- Missed early warning signs  
- Delayed interventions  
- Increased risk of complications  

There is a need for an intelligent assistive system that can **continuously analyze health logs** and support **early risk awareness and proactive care**.

---

## 💡 Proposed Solution

ChroniCare AI bridges this gap using a **multi-agent AI architecture** that:

- Continuously analyzes daily health data
- Detects short-term and long-term risk trends
- Generates early alerts and lifestyle recommendations
- Summarizes historical health patterns for better decision-making

⚠️ The system is **assistive only** and does **not provide medical diagnosis or treatment advice**.

---

## 🧠 System Architecture

ChroniCare AI consists of the following agents:

### 1️⃣ Health Data Analysis Agent
- Ingests daily vitals and medication logs
- Organizes data into meaningful short-term and long-term trends

### 2️⃣ Risk Trend Detection Agent
- Identifies abnormal or worsening patterns
- Uses clinical thresholds and historical baselines
- Detects early risk indicators (non-diagnostic)

### 3️⃣ Alert & Lifestyle Recommendation Agent
- Generates early warning alerts
- Provides lifestyle guidance (diet, activity, sleep, stress, medication adherence)
- Aligns recommendations with trusted clinical guidelines

---

## 🧰 Technology Stack

| Component | Description |
|---------|-------------|
| LangFlow | Visual orchestration of multi-agent AI workflows |
| IBM Granite Model | Responsible, enterprise-grade foundation model |
| IBM watsonx.ai | Secure platform for running and governing AI models |
| RAG | Grounds AI responses in trusted healthcare guidelines |
| Astra DB (Vector DB) | Semantic retrieval of guideline documents |
| IBM Cloud | Scalable and secure deployment infrastructure |

---

## 📥 Input Data

ChroniCare AI analyzes the following patient-generated data:

- Blood glucose levels  
- Blood pressure readings  
- Peak flow values  
- Symptoms  
- Medication adherence logs  

Data can be entered manually and is designed to support future wearable/IoT integration.

---

## 📤 Output Capabilities

- Short-term and long-term health trend analysis  
- Early risk trend detection (assistive)  
- Personalized lifestyle recommendations  
- Historical health summaries  
- Structured health reports  

---
MENU

1️⃣ Health Data Analysis
2️⃣ Risk Trend Detection
3️⃣ Alerts & Lifestyle Recommendations
4️⃣ History
5️⃣ Summarize Report

Each option triggers a specific agent-based analysis aligned with the problem statement.

---

## 🔐 Safety, Ethics & Compliance

- ❌ No diagnosis or medical treatment is provided  
- ✅ Assistive and informational outputs only  
- 📚 Recommendations grounded in trusted healthcare guidelines  
- 🔒 Secure data handling via IBM Cloud  
- ⚖️ Aligned with IBM Responsible AI principles  

---

## 👥 End Users

- Patients with chronic diseases  
- Caregivers and family members  
- Healthcare professionals  
- Hospitals and chronic care clinics  
- Digital health and remote care platforms  

---

## 🚀 Future Scope

- Integration with wearable and IoT devices  
- Predictive risk scoring  
- Clinician dashboards  
- Multilingual and voice-based assistance  
- Expansion to additional chronic conditions  
- Population-level chronic care analytics

## 🧭 User Interaction Flow

When a user starts the conversation, the system displays the following menu:
