# "🕵️‍♂️ SmishShield: Structural SMS & URL Fraud Monitor"

PhishPulse is an enterprise-grade threat intelligence and forensic detection engine designed to intercept regional automated smishing (SMS Phishing) vectors and malicious hyperlink structures before execution. Built on a machine learning pipeline using a Support Vector Machine (SVM) classifier, the system extracts lexical syntax weights and deconstructs URL payloads to deliver zero-latency threat triage metrics and actionable SOC (Security Operations Center) mitigation logs.

---

## 🚀 Key Capabilities

* **Multi-Class Telemetry Analysis:** Simultaneously inspects textual intent arrays and structural URL configurations to eliminate classification variance.
* **Regional & Hybrid Tokenization:** Optimized to detect localized threat configurations, including English text, Tamil syntax indicators, and transliterated vernacular text (Tanglish).
* **Impersonated Brand Profiling:** Features an autonomous entity extraction layer that scans string objects to flag targeted spoofing profiles (e.g., TNEB, SBI, IndiaPost, Telecom networks).
* **Automated Incident Serialization:** Dynamically translates machine learning output into structured, SIEM-compatible syslog formats (`[SOC THREAT ENGINE LOG]`).

---

## 📂 Repository Structure

* `app.py`: Streamlit Forensic Telemetry Dashboard
* `train.py`: Model pipeline training script & dataset compilation
* `smishing_model.pkl`: Serialized Support Vector Machine brain
* `smishing_vectorizer.pkl`: Compiled TF-IDF linguistic feature array
* `requirements.txt`: Environment dependencies mapping
