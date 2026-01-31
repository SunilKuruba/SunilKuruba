# Sunil Kuruba

## **👨🏻‍💻 Data Engineer**

<img src="https://raw.githubusercontent.com/ABSphreak/ABSphreak/master/gifs/Hi.gif" width="30px"> I'm currently pursuing an MS in Computer Science at the University of Illinois Chicago, graduating in Dec 2025, with a focus on advanced data engineering, cloud computing, distributed systems, and big data technologies. My academic work aligns with my passion for solving real-world data challenges through scalable, cloud-native backend architectures.

I’m an AWS Certified Data Engineer – Associate, skilled in building secure, cost-efficient, and high-performance data pipelines using services such as Amazon S3, Glue, EMR, Kinesis, Redshift, Athena, and DynamoDB. My expertise spans ETL/ELT, data lake architectures, governance, and real-time analytics at scale.

Previously, I worked as a Senior Software Engineer at Fivetran, contributing to core pipeline infrastructure used by enterprise customers. I re-architected the BigQuery data writer to support partitioning, clustering, and JSON — reducing customer costs by ~90%. I also built a high-performance DynamoDB connector (15× faster) and improved MongoDB syncs using Change Streams (5× speedup).

Beyond connectors, I authored the Isolated Endpoint Sync (IES) framework — now adopted in 500+ connectors across 10+ teams — and led the design of the Data Preview feature for smoother onboarding. I also onboarded the 2024 intern batch through a structured training program and conducted technical interviews for various engineering roles.

Passionate about building scalable, reliable, and innovative data solutions that drive real business value. Actively exploring new opportunities in data engineering, backend systems, and cloud infrastructure.

## Core Strengths

- **Data Engineering & Pipelines:** Designing and implementing scalable ETL/ELT pipelines, schema evolution, data modeling, connector development, orchestration, and real-time data processing.
- **Distributed Systems & Processing:** Apache Spark, Hadoop MapReduce, Apache Flink, Kafka, AWS Kinesis, and gRPC for processing large-scale datasets in both batch and real-time systems.
- **Cloud Platforms & Services:** 
  - **AWS:** EC2, Lambda, S3, EMR, Glue, Step Functions, RDS, DynamoDB, Redshift, Athena, EventBridge, IAM, KMS, CloudWatch, CloudTrail.
  - **GCP:** BigQuery, Compute Engine, Pub/Sub, Cloud Storage.
  - **Azure:** Azure VM, Azure Blob Storage.
- **Databases & Warehousing:** Experience with modern data warehouses and databases like Snowflake, BigQuery, Redshift, DynamoDB, MySQL, PostgreSQL, MongoDB, and SQL Server.
- **Programming & Backend Development:** Proficient in Java (Advanced), SQL (Advanced), Scala, Python, C++, Shell Scripting; expertise in backend architecture, REST APIs, and service frameworks.
- **DevOps & Infrastructure:** Skilled in Docker, Kubernetes, Terraform, GitHub Actions, CI/CD, observability tools like New Relic, CloudWatch, and SonarQube for maintaining robust production systems.
- **Data Quality & Governance:** Ensuring data integrity and reliability through validation frameworks, governance practices, and monitoring across the data lifecycle.
- **Collaboration & Leadership:** Onboarded interns with structured training, led design efforts, and contributed to engineering hiring processes.

## Certification
### AWS Certified Data Engineer – Associate  
[Verified on Credly](https://www.credly.com/badges/775a6e7e-2f28-4cb8-ac1c-02949a7a0587/linked_in?t=szfxty)  
Demonstrates ability to design, build, secure, and maintain data analytics solutions on AWS that are efficient, scalable, and cost-optimized. Proficient in:
- Data lake and lakehouse architecture
- Real-time and batch data ingestion
- Data transformation using Glue, EMR
- Querying with Athena, Redshift
- Secure access via IAM, encryption, and governance

## Education

### University of Illinois Chicago
*Master of Science in Computer Science | Aug 2024 – Dec 2025*  

### RV College of Engineering, Bengaluru
*Bachelor of Engineering in Computer Science | Aug 2016 – May 2020*  

## 🧑‍💻 Experience

### **Senior Software Engineer**  
**Fivetran** · Bengaluru, India  
_Mar 2023 – Aug 2024 · 1 yr 6 mos_

- Redesigned and developed a new BigQuery data writer aligned with SQL-based writers, eliminating 90% of maintenance overhead.
- Enhanced Warehouse Data Writer throughput by 30% by implementing multithreaded concurrent processing for split files.
- Added support for JSON data types in BigQuery, ensuring seamless schema evolution and data compatibility.
- Introduced partitioning and clustering in BigQuery writer to reduce customer costs by ~90% — a hackathon-winning optimization.
- Led infrastructure improvements across distributed data pipelines and contributed to system-level performance gains.

### **Software Engineer 2**  
**Fivetran** · Bengaluru, India  
_Sep 2021 – Mar 2023 · 1 yr 7 mos_

- Engineered a high-performance DynamoDB connector with 15× speedup in incremental syncs.
- Improved MongoDB connector using Change Streams to achieve 5× faster data ingestion with reduced latency.
- Designed support for Azure CosmosDB for MongoDB API, expanding Fivetran’s connector catalog.
- Built Data Preview functionality using the IES framework to simplify customer onboarding and demo experiences.

### **Software Engineer**  
**Fivetran** · Bengaluru, India  
_Jun 2020 – Aug 2021 · 1 yr 3 mos_

- Authored **Isolated Endpoint Sync (IES)** — a hackathon-winning framework now adopted by 500+ connectors and 10+ teams.
- Built a public Shopify connector app with OAuth-based merchant onboarding, GraphQL extraction, and failover capabilities.
- Enhanced Stripe connector with multithreading and connected accounts support for scale and fault-tolerance.
- Developed an ETL connector for ADP REST APIs with complete ERD-based schema documentation.

### **Software Engineering Intern**  
**Fivetran** · Bengaluru, India  
_Jan 2020 – May 2020 · 5 mos_

- Built webhook-based incremental sync mechanism for Recharge connector, achieving a 10× increase in extract performance.
- Benchmarked performance of full ETL pipelines using Snowflake, delivering optimization insights for production rollouts.
- Contributed to multiple API-based connectors and gained hands-on experience with Fivetran’s connector lifecycle.


## Projects

###  Mini Database Management System Internals Implementation
**GitHub:** [View Project](https://github.com/SunilKuruba/Mini-Database-Management-System-Internals-Implementation)
Implemented core database engine internals including page-based storage, buffer management, record storage, and B+ tree indexing as part of an academic DBMS project.
**Tech:** C, Storage Manager, Buffer Manager (FIFO/LRU), Record Manager, B+ Tree, Valgrind

---

### **AWS vs GCP Data Pipeline Benchmarking**
**GitHub:** [View Project](https://github.com/SunilKuruba/AWS-VS-GCP-Data-Pipeline-Comparative-Analysis-of-Real-Time-Data-Streaming)  
Benchmarks real-time data pipelines on AWS and GCP using a common IoT workload. Evaluates performance, cost, and sustainability.  
**Tech:** AWS Kinesis, GCP Pub/Sub, Lambda, Dataflow, Python

---

###  Visual Analytics and Interactive Dashboards for LinkedIn Postings

**GitHub:** [View Project](https://github.com/SunilKuruba/Visual-Analytics-and-Interactive-Dashboards-for-LinkedIn-Postings)

Developed an interactive visual analytics platform analyzing 124K+ LinkedIn job postings to uncover trends in skill demand, salaries, geography, experience levels, and remote work. Built reproducible data pipelines in Python and designed linked dashboards using Altair/Vega-Lite, including geospatial salary maps, skill–salary–industry views, and embedding-based job similarity exploration using PCA and UMAP.
Tech: Python, Pandas, Altair, Vega-Lite, PCA, UMAP, Jupyter, GitHub Pages

---

### **AWS Bedrock LLM Conversation API with Ollama**
**GitHub:** [View Project](https://github.com/SunilKuruba/AWS-Bedrock-Based-LLM-Conversation-API-with-Ollama-Integration-with-Dockerized-Deployment)  
Built a cloud-native conversational API using AWS Bedrock and Ollama for multi-turn LLM-based dialogue.  
**Tech:** Scala, Akka HTTP, gRPC, AWS Lambda, Docker

---

### **Distributed Neural Network Training & Sentence Generation**
**GitHub:** [View Project](https://github.com/SunilKuruba/Apache-Spark-and-AWS-EMR-Distributed-Neural-Network-Training-and-Sentence-Generation)  
Built a Spark-based deep learning pipeline to train and generate text using DL4J and AWS EMR.  
**Tech:** Scala, Apache Spark, DL4J, AWS EMR

---

### **Social-Aware Movie Revenue Prediction**
**GitHub:** [View Project](https://github.com/SunilKuruba/Data-Science-Project-Social-Aware-Movie-Revenue-Prediction-Using-Metadata-and-Sentiment-Signals)  
A machine learning pipeline that predicts movie box office revenue by combining traditional metadata (e.g., budget, genre, cast) with sentiment and emotion signals extracted from Reddit and YouTube.  
**Tech:** Python, scikit-learn, NLP, Reddit & YouTube API, Data Visualization, EDA

---

### **Hadoop-based LLM Tokenization & Embeddings**
**GitHub:** [View Project](https://github.com/SunilKuruba/Apache-Hadoop-and-AWS-EMR-Distributed-LLM-Text-Processing-and-Embeddings)  
Created a distributed NLP pipeline using custom tokenizers and Hadoop MapReduce to generate text embeddings.  
**Tech:** Scala, Hadoop, AWS EMR

---

### **Help Session Activity Management System**
**GitHub:** [View Project](https://github.com/SunilKuruba/Data-Modeling-Help-Session-Activity-Management-System)  
Designed the backend data model for scheduling and managing academic help sessions between TAs and students.  
**Tech:** SQL, Database Design, ER Diagram

