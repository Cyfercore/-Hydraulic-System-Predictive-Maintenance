# -Hydraulic-System-Predictive-Maintenance
Predictive maintenance analysis for hydraulic systems using SQL, telemetry insights, and failure pattern detection.

---

## 📘 Project Summary

This project focuses on building a predictive maintenance system for hydraulic systems by analysing multi‑sensor telemetry to detect early signs of failure.  
It applies machine learning to classify failure modes and estimate Remaining Useful Life (RUL), enabling a shift from reactive to condition‑based maintenance.  
An end‑to‑end pipeline was developed to support data validation, feature engineering, model training, and automated deployment.  
The solution enhances reliability, reduces unplanned downtime, and supports Bosch Rexroth’s transition toward intelligent, data‑driven industrial operations.  

---
## Team

- **Project Owner** — Responsible for project vision, stakeholder alignment, prioritisation, and sign-off on deliverables.  
- **Data Scientist** — Led model selection, algorithm development, validation, and RUL estimation.  
- **Business Analyst** — Defined business requirements, KPIs, and ensured model outputs map to maintenance workflows.  
- **Data Analyst** — Owned SQL restoration, data assessment, cleaning, transformation, T‑SQL feature engineering, and dashboarding.  
- **Data Analyst Scrum Master** — Facilitated agile ceremonies, managed the sprint backlog, coordinated cross‑functional tasks, and ensured timely delivery.



## Business Challenge

**Problem Statement**  
Bosch Rexroth AG is experiencing frequent unplanned downtime from hydraulic system failures, causing production interruptions, costly emergency repairs, and delayed deliveries. The current maintenance approach cannot reliably predict failures or estimate Remaining Useful Life (RUL) for critical components.

**Operational Context**  
Hydraulic systems run in high‑demand, near‑24/7 environments under extreme and variable conditions (pressure spikes, temperature swings, contamination). Degradation often progresses unnoticed due to limited maintenance windows and inconsistent monitoring.

**Key Obstacles & Pain Points**  
- **Reactive maintenance culture** — technicians respond to breakdowns rather than preventing them.  
- **Data fragmentation and underutilisation** — multi‑sensor telemetry is not integrated for centralized analysis.  
- **Lack of predictive capability** — no system exists to forecast failures or estimate RUL reliably.  
- **No standardized failure classification** — maintenance relies on manual logs and experience rather than a structured taxonomy.

**Business Impact**  
Each failure causes significant downtime, higher repair costs, and potential delivery delays, accumulating into substantial annual financial losses and reduced operational efficiency.

**Strategic Implication**  
Without a predictive maintenance framework, Bosch Rexroth cannot fully transition to a proactive, data‑driven maintenance strategy, limiting optimisation of resources, cost reduction, and the value of sensor investments in an Industry 4.0 context.



## Project Objectives

Deliver a production‑ready predictive‑maintenance platform that ingests time‑series telemetry, ensures data quality, engineers time‑series features, detects early warnings, trains failure and RUL models (F1/MAE), and deploys containerized models with a real‑time dashboard and MLOps automation to drive actionable alerts and reduce unplanned downtime.
  

## Business  Requirements

The Business Analyst defined outcome‑driven requirements to prevent unplanned downtime and make predictions actionable for maintenance teams: predict failures and RUL; detect anomalies in real time; generate alerts and maintenance reports; provide an intuitive dashboard; ensure ≤3s dashboard load, ≤30s alert latency, ≥99% uptime, encrypted data, and role‑based access.


