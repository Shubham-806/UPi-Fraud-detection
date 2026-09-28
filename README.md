# AI-Powered UPI Fraud Detection & Investigation Platform

> An end-to-end fintech platform for behavioral transaction risk scoring, explainable fraud detection, and investigator-assisted fraud investigation.

![Java](https://img.shields.io/badge/Java-21%2B-orange)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-4.x-brightgreen)
![Python](https://img.shields.io/badge/Python-3.x-blue)
![FastAPI](https://img.shields.io/badge/FastAPI-ML%20Service-teal)
![XGBoost](https://img.shields.io/badge/XGBoost-Fraud%20Detection-red)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-blue)
![pgvector](https://img.shields.io/badge/pgvector-Vector%20Search-purple)
![React](https://img.shields.io/badge/React-TypeScript-61DAFB)
![Docker](https://img.shields.io/badge/Docker-Containerized-2496ED)

---

## Overview

The **AI-Powered UPI Fraud Detection & Investigation Platform** is a full-stack fintech system designed to detect suspicious UPI transactions using behavioral signals and provide investigators with explainable risk assessments.

Instead of treating fraud detection as a simple binary classification problem, the platform combines:

- Behavioral transaction analysis
- Machine-learning-based fraud detection
- Explainable risk scoring
- Customer and transaction history
- Automated fraud-case creation
- Investigator workflows
- AI-assisted investigation
- Retrieval-Augmented Generation (RAG)
- Event-driven transaction processing
- Low-latency behavioral caching

The system is designed around the workflow used by a fraud investigation team:

```text
UPI Transaction
      |
      v
Behavioral Feature Extraction
      |
      v
Fraud Risk Model
      |
      v
Risk Score + Explainable Reasons
      |
      v
Investigation Case
      |
      v
Investigator Dashboard
      |
      v
AI-Assisted Investigation
