<div align="center">
  <h2>Hi, I'm Mammad Aliyev 👋</h2>
  <p>
    <b>Data Engineer</b> based in Baku, Azerbaijan 🇦🇿<br>
    <i>Specializing in High-Scale Streaming, FinOps, and Secure Data Infrastructure.</i>
  </p>
  <a href="[https://linkedin.com/in/mammad--aliyev](https://www.linkedin.com/in/mammad--aliyev/)">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin" />
  </a>
  <a href="mailto:mammed.aliyev.e@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact_Me-red?style=for-the-badge&logo=gmail" />
  </a>
</div>

---

### 🔭 Engineering Philosophy
I build **battle-hardened data platforms** that survive contact with reality. My engineering focus is threefold:
1.  **Extreme Scale:** designing for **1B+ daily events** and handling backpressure gracefully.
2.  **Unit Economics (FinOps):** optimizing compute/storage ratios to stop cloud bills from bleeding.
3.  **Governance as Code:** embedding PII security (hashing/vault) directly into ingestion pipelines.

---

### 🛠️ Tech Stack

**Core & Compute**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Flink](https://img.shields.io/badge/Apache%20Flink-E6526F?style=flat-square&logo=apacheflink&logoColor=white)

**Streaming & Orchestration**
![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Debezium](https://img.shields.io/badge/Debezium-000000?style=flat-square&logo=debezium&logoColor=white)

**Infrastructure & Ops**
![K8s](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Vault](https://img.shields.io/badge/HashiCorp%20Vault-FFD814?style=flat-square&logo=vault&logoColor=black)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)

**Data Lake & Storage**
![Iceberg](https://img.shields.io/badge/Apache%20Iceberg-222222?style=flat-square&logo=apache&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white)
![Postgres](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)

---

### 🚀 Key Systems Engineered

#### 📉 **Cloud Repatriation Strategy (FinOps)**
* **Problem:** Cloud-native analytics costs were spiraling due to high-frequency queries on BigQuery.
* **Solution:** Architected a repatriation pipeline moving 50M+ daily records to on-premise Spark clusters with Iceberg tables.
* **Outcome:** Reduced total compute spend by **~75%**, proving that "cloud-first" isn't always "cost-efficient."

#### 🌊 **CDC Ingestion Backbone**
* **Scale:** **1 Billion+ events/day** across 70+ Oracle databases.
* **Architecture:** Oracle GoldenGate → Kafka → Flink/Spark → Data Lake.
* **Reliability:** Implemented metadata-driven alerting and auto-schema evolution to manage **1,000+ tables** without manual intervention.

#### 🔐 **Secure PII Vault**
* **Concept:** Zero-trust ingestion for banking data.
* **Implementation:** Integrated **HashiCorp Vault** for dynamic secret management and implemented **SHA-256 PAN Hashing** at the ingestion layer.
* **Result:** Analytics teams can join datasets on hashed keys without ever exposing raw credit card numbers.
