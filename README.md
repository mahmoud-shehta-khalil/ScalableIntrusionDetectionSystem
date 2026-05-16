# 🛡️ Sentinel-Spark-IDS: Scalable Intrusion Detection System
---

## 📌 Project Overview
This project focuses on building a **high-performance, scalable Intrusion Detection System (IDS)** leveraging the [CIC-IDS-2017 Dataset](https://cicresearch.ca/CICDataset/CIC-IDS-2017/). By integrating a complete **Data Science Pipeline** with distributed computing, we address the critical challenge of monitoring massive network traffic for real-time cyber-attack detection.

The project is built on three core pillars:
1.  **Big Data:** Utilizing **Apache Spark (PySpark)** for distributed processing of millions of network flow records.
2.  **Advanced Data Science:** A rigorous pipeline for data cleaning, advanced feature engineering, and handling severe class imbalances.
3. **Applied Machine Learning:** Training high-performance classifiers (e.g., Random Forest, LightGBM) to distinguish between benign traffic and malicious activities.

---

## 🛠️ Data Science & ML Pipeline
Our methodology strictly adheres to the professional ML pipeline requirements:

| Stage | Focus | Key Operations |
| :--- | :--- | :--- |
| **1. Data Collection** | Retrieval | Efficient loading of 2.8M+ records via PySpark. |
| **2. Pre-processing** | Cleaning | Handling NaNs/Infs, duplicate removal, and schema standardization. |
| **3. Feature Engineering** | Extraction | Generating domain-specific metrics (e.g., flow ratios) to reveal attack patterns. |
| **4. Feature Selection** | Optimization | Using Correlation analysis and Feature Importance to reduce dimensionality. |
| **5. Imbalance Handling** | Sampling | Applying techniques to protect the model from "Benign" class bias. |
| **6. ML Core** | Training | Hyperparameter tuning and evaluation of Random Forest & LightGBM. |
| **7. Analytics** | Visualization | Storytelling through interactive dashboards and threat mapping. |

---

## 👥 Team Contributions
| Name | Role | Core Responsibility |
| :--- | :--- | :--- |
| **Mahmoud Shehta Mahmoud** | **Project Lead** | Architecture, Spark Engine Config & Integration. |
| **Mohamed Anwar Nassar** | **Data Engineer** | Cleaning Pipeline & Data Integrity. |
| **Ahmed Nassar Nassar** | **Feature Architect** | Extraction Logic & Selection Methods. |
| **Ahd Sayed Atia** | **Data Scientist** | Sampling Strategies & Class Imbalance. |
| **Reem Ahmed Maher** | **ML Engineer** | Model Training, Tuning & Evaluation. |

---
