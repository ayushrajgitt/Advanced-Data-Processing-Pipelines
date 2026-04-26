# Advanced Data Processing Pipelines

## 📌 Overview
This repository contains hands-on architectures, scripts, and distributed processing labs that I built during a 90-hour advanced Data Engineering training program conducted by ExcelR in collaboration with KIIT University.

Building upon prior experience with cloud data warehousing and API integrations, this repository focuses on the next step in the modern data stack: **large-scale distributed computing, real-time streaming, pipeline orchestration, and ACID-compliant data lakes.**

## 🧠 Core Architectures Mastered
Beyond hands-on implementation, this repository reflects deep theoretical knowledge of distributed system internals:
* **Hadoop Ecosystem:** HDFS storage architectures and MapReduce processing paradigms.
* **Apache Spark:** Directed Acyclic Graph (DAG) execution, RDDs vs. DataFrames, and memory management across distributed clusters.
* **Apache Kafka:** Distributed pub/sub messaging, topic partitioning, Zookeeper coordination, and fault-tolerant streaming.
* **Apache Airflow:** Dependency management and dynamic workflow scheduling.

## 📂 Repository Structure

### 1. `1_Apache_Spark_and_Delta_Lake`
Focuses on distributed processing and modern data lakehouse architectures.
* PySpark DataFrames, aggregations, and Spark SQL.
* Delta Lake setup, DML operations (Update, Delete, Merge).
* Implementing Schema Enforcement and Delta Time Travel (`versionAsOf`).
* Performance testing using standard Python multiprocessing vs. distributed Spark clusters.

### 2. `2_Python_ETL_and_Data_Quality`
Foundational data pipeline logic focusing on reliability and performance optimization.
* Identifying and handling dirty data (nulls, invalid formats, duplicate rows).
* Building robust ETL pipelines with Python's `logging` module.
* Memory management, cost optimization, and comparing iterative loops vs. vectorized operations.

### 3. `3_Data_Modeling`
Designing architectures for optimized analytics.
* Creating Fact and Dimension tables.
* Joining disparate datasets into optimized Star Schemas for business intelligence.

### 4. `4_SQL_and_Analytical_Databases`
* Utilizing DuckDB for high-performance, local analytical query execution.

### 5. `5_Cloud_Foundations`
* Foundational cloud computing labs and instance configurations.

### 6. `6_Apache_Kafka`
Implementing real-time data streaming architectures.
* Setting up Kafka clusters and Zookeeper.
* Developing real-time message Producer and Consumer scripts.
* Building real-world streaming use cases (E-commerce, Ride Booking, Stock Ticketing, Temperature Sensors).
* Bridging streaming and distributed processing via Kafka-to-Spark integrations.

### 7. `7_Data_Orchestration_and_CICD`
Designing resilient, automated data pipelines and deployment workflows.
* Simulating Directed Acyclic Graphs (DAGs) for task dependency management.
* Developing Continuous Integration and Deployment (CI/CD) checks for data validity before production merges.

### 8. `8_Governance_and_Security`
Implementing enterprise-grade data protection and metadata management.
* Role-Based Access Control (RBAC) implementations masking sensitive columns (e.g., salaries, account numbers) based on user roles.
* Creating metadata dictionaries to track data lineage, source, and ownership.

---
*Note: This repository is a demonstration of advanced data engineering concepts and continuous upskilling in distributed systems.*
