# BWT_TeamRockets

## Project Title

UPI Scam Shield – Real-Time Cyber Threat Detection for UPI Transactions

---

## Theme

Cyber Threat Detection Systems

---

## Team Details

Team Name: Team Rockets
Hackathon: Build With Technology (BWT)

---

## Development Environment

This project is built using **TRAE IDE (AI-assisted development environment)**.

---

## Problem Statement

UPI digital payment systems are increasingly vulnerable to cyber fraud such as refund scams, fake merchant identities, impersonation attacks, and social engineering techniques.

Most existing fraud detection mechanisms identify threats only after transactions are completed, making financial recovery difficult. A proactive system is required to detect and prevent fraudulent transactions before authorization.

---

## Solution Overview

UPI Scam Shield is a real-time fraud detection and interception system designed to analyze UPI transaction metadata before payment authorization.

The system evaluates transaction behavior and identifies suspicious indicators to generate:

* Fraud Risk Score
* Risk Classification (Safe, Suspicious, High Risk)
* Transaction Decision (Allow, Flag, Block)

This approach shifts fraud detection from reactive monitoring to proactive prevention.

---

## System Architecture

![Architecture Diagram](architecture/architecture_diagram.png)

### Architecture Flow

User Initiates Payment
→ Transaction Metadata Captured
→ Real-Time Fraud Detection Engine
→ Risk Score Computation
→ Decision Layer
→ Transaction Allowed or Blocked

---

## Tech Stack

Frontend:

* Web Interface / Dashboard

Backend:

* Python / Node.js

Fraud Detection Engine:

* Rule-Based Risk Scoring System
* Real-Time Processing Logic

Database:

* Transaction Metadata Storage

Development Tool:

* TRAE IDE

---

## Working Flow

1. User initiates a UPI transaction.
2. Transaction metadata is captured.
3. Input validation checks are performed.
4. Fraud indicators are evaluated in real time.
5. Risk score is calculated.
6. Transaction is classified as Safe, Suspicious, or High Risk.
7. System allows, flags, or blocks the transaction.

---

## Key Features

* Real-time fraud interception before transaction completion
* Sub-300 millisecond decision response
* Detection of impersonation and scam patterns
* Suspicious keyword and behavior analysis
* Low false-positive risk evaluation
* Pre-authorization transaction validation

---

## Example Scenario

UPI ID: support-refund@okaxis
Message: "Your refund is pending. Send ₹1 to verify."

Detected Indicators:

* Refund scam pattern
* Urgency manipulation
* Impersonation-style merchant identity

Fraud Score: 85
Classification: High Risk
Decision: Transaction Blocked

---

## Future Enhancements

* Machine learning-based fraud prediction
* Behavioral anomaly detection
* Integration with banking gateways
* Distributed fraud monitoring system

---

## Setup Instructions

```bash
git clone https://github.com/your-username/BWT_TeamRockets.git
cd BWT_TeamRockets
npm install
npm start
```

---

## License

This project is developed for the Build With Technology (BWT) Hackathon.

