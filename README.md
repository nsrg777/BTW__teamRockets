# 🚀 BWT_TeamRockets

## 🔐 Project Title

**UPI Scam Shield – Real-Time Cyber Threat Detection for UPI Transactions**

---

## 🎯 Theme

**Cyber Threat Detection Systems**

---

## 👥 Team Details

* **Team Name:** Team Rockets
* **Hackathon:** Build With Trae (BWT)

---

## 💡 Problem Statement

UPI digital payments are increasingly targeted by cyber frauds such as refund scams, fake merchant identities, impersonation attacks, and social engineering techniques.

Most existing systems detect fraud only after the transaction is completed, making recovery difficult.

---

## ✅ Solution Overview

**UPI Scam Shield** is a real-time fraud detection system that analyzes UPI transaction data before authorization to identify suspicious or malicious activities.

The system generates:

* Fraud Risk Score
* Risk Classification (Safe / Suspicious / High Risk)
* Instant transaction decision (Allow / Flag / Block)

This enables proactive protection by stopping fraudulent payments before money is transferred.

---

## 🏗️ System Architecture

![Architecture Diagram](architecture/architecture_diagram.png)

### Architecture Flow

User Payment Request
→ Transaction Metadata Capture
→ Real-Time Fraud Detection Engine
→ Risk Score Calculation
→ Decision Layer
→ Transaction Allowed or Blocked

---

## ⚙️ Tech Stack

**Frontend**

* Web Dashboard / UI

**Backend**

* Python / Node.js

**Fraud Detection Engine**

* Rule-Based Risk Scoring
* Real-Time Processing Logic

**Database**

* Transaction Metadata Storage

**Development Environment**

* TRAE IDE (AI-assisted coding)

---

## 🔄 Working Flow

1. User initiates UPI transaction.
2. Transaction metadata is captured.
3. Fraud engine evaluates risk indicators.
4. Risk score is calculated instantly.
5. System classifies transaction risk.
6. Transaction is allowed, flagged, or blocked.

---

## ✨ Key Features

* Real-time fraud interception
* Sub-300ms decision response
* Suspicious keyword detection
* Impersonation pattern analysis
* Low false-positive detection
* Pre-transaction security validation

---

## 📊 Example Use Case

**UPI ID:** support-refund@okaxis
**Message:** "Send ₹1 to verify refund"

Detected:

* Refund scam pattern
* Urgency manipulation
* Fake merchant identity

✅ Fraud Score: 85
🚨 Classification: High Risk
⛔ Decision: Transaction Blocked

---

## 🚀 Future Enhancements

* Machine learning-based fraud prediction
* Behavioral anomaly detection
* Bank gateway integration
* Distributed fraud monitoring system

---

## 🛠️ Setup Instructions

```bash
git clone https://github.com/your-username/BWT_TeamRockets.git
cd BWT_TeamRockets
npm install
npm start
```

---

## 📄 License

Developed for the **Build With Technology Hackathon**.
