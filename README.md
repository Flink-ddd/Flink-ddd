# Hi there, I'm Mu Xiaohui 👋



### How to contact me 🔽
<a href="https://medium.com/@vensenmu" target="_blank"><img src="https://img.shields.io/badge/Medium-%2312100E.svg?&style=for-the-badge&logo=medium&logoColor=white" alt="Medium"/></a>
<a href="mailto:vensenmu@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://www.linkedin.com/in/xiaohui-mu-16493430a/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://wa.me/6581302719" target="_blank"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp"/></a>

---

**Previously**, I'm a **Java Senior Software Engineer** with over **7 years of experience** in designing and building large-scale, high-concurrency distributed systems using Java microservices.

**Currently**, I'm expanding my expertise into **AI Infrastructure and LLM Applications**, applying my deep engineering background to build robust and efficient systems that power intelligent solutions. I'm passionate about creating value at the intersection of solid software architecture and cutting-edge AI.

Based in **Singapore** right now 

---

### 🛠️ Core Expertise & Technology Stack

My skills cover the full spectrum from foundational backend architecture to modern AI/ML infrastructure.

| Core Java & Distributed Systems | AI/ML & Big Data |
| :--- | :--- |
| Java, Spring Boot, Spring Cloud, mybatis, Mybatis-Plus, mybatis | Python, PyTorch, vLLM, DeepSpeed, Triton, aiter, ROCm, ray, Transformers|
| Microservices, SaaS, PaaS, DDD | LLM Fine-tuning (LoRA), RAG |
| Docker, Kubernetes, DevOps, gRPC, OpenFeign, SkyWalking | Vector DB (FAISS, ElasticSearch) |
| rocketMQ, pulsar, Kafka, AWS/sqs, Zookeeper, Alibaba nacos/dubbo/Canal/other, WebSocket, Netty | Delta Lake, Apache Flink, Apache Hudi, Apache Iceberg, kettle, Flink-CDC, Debezium, Prometheus+Grafana+Alertmanager|
| MySQL, MongoDB, Neo4j, PostgreSQL, ElasticSearch, Redis, MinIO, OSS, SolrCloud, Hbase | ELK, Flume, Clickhouse, Drios |
| System Design & Scalable Architecture | MLOps & Inference Optimization |


---

### 🏆 Featured Projects

Here are some projects that highlight my capabilities across both domains.

#### AI Infrastructure & LLM Applications

1.  **RAG System for Domain-Specific Q&A**
    - Engineered a Retrieval-Augmented Generation (RAG) pipeline using `Mistral-7B`,`chatGPT-o4-mini`, `ElasticSearch` for a specialized knowledge domain.
    - Optimized the system for real-time interaction through efficient data processing and a high-throughput inference server deployment.

2.  **LLM Inference Acceleration & Fine-tuning**
    - Customized open-source LLMs (`Mistral`, `Qwen`, `Llama`) using **LoRA** fine-tuning techniques on specific datasets.
    - Accelerated model inference significantly using **vLLM** and **FlashAttention**, deploying them as scalable API endpoints on cloud platforms like **GCP** and **Azure**.

3.  **pytorch & vLLM & DeepSpeed & Transformers & ray Contribution (Ongoing)**



#### Java Microservices & System Architecture

1.  **Group-Level Multi-functional Payment Platform**
    - Architected and developed a highly available,  enterprise-grade payment center using **Domain-Driven Design (DDD)** and a robust microservices architecture.
    - The system reliably handles millions of transactions in a specific period time and smoothly process tens of thousands of transactions or more every day, ensuring data consistency and security across various payment channels.

2.  **High-Concurrency Instant Messaging System**
    - Built a distributed IM system from the ground up to support millions of concurrent users.
    - Leveraged a powerful tech stack including `Spring Boot`, `WebSocket`, `Kafka` for message queuing, and `Zookeeper` for service coordination, achieving high throughput and low latency.

3.  **Enterprise Search & Real-Time Data Platform**
    - Designed a high-performance search engine using `Elasticsearch` and `Flink-CDC` capable of indexing and searching billions of records with sub-second latency.
    - Built the underlying real-time data synchronization pipeline, providing a unified data backbone for multiple business units.
  
4.  **Enterprise Flink computing Platform**
    - Enterprise-level Flink Cluster: Built a unified Flink-based computing center for real-time data lake, stats center, and ETL pipelines.

5.  **Microservice technology system Architecture**
   
     - The project comprises over 28 microservices, including those for users, orders, payments, logistics, merchants, products, instant messaging, basic services, search, gateways, SMS messaging, file services, a computing    platform, and a data synchronization center.
     - A "precise and rapid response" approach was proposed for the new project, and the implementation of the project scaffolding was arranged, encompassing both Spring Boot + Spring Cloud microservice projects and DDD (Device-Driven Development) project models.
     - A binary package format and specification for inter-microservice calls were defined, and the company's private server underlying infrastructure package was encapsulated.
     - The business processing message middleware technologies selected were Kafka, relational database MySQL, non-relational databases Redis and Elasticsearch, and the service registry Nacos.
     - Core components such as Prometheus + Grafana, Node.js Exporter, and Alertmanager were introduced to provide visualized, multi-faceted monitoring and alerting of data center and cloud server resources. Anomaly alerts were pushed to DingTalk and related SMS messages.
     - Flink-CDC was introduced, MySQL binlog was configured, and Flink and related connector packages were added to the data synchronization center. The development team provides relevant code. The CDC (Center for Data Controllers) acquires real-time data changes from monitoring business database tables, performs data processing across different dimensions such as grouping and JOIN, and synchronizes the data to different business data destination sinks or writes it to Kafka.
     - Order and product data are written to Kafka via the upsert-kafka connector. The core processing mechanism in the search service listens to relevant Kafka topics and consumes the data, writing it to Elasticsearch. The search service provides API interfaces for business services to call and query.
     - Chat and payment transaction data are processed using the SQL API and DataStream API syntax in the CDC, synchronized to ClickHouse, and used for analysis and logging of user behavior/actions.
     - Real-time data visualization dashboards are provided and displayed through the computing platform service, based on Flink stream computing, and involve statistics such as order amount, sales volume, and merchant brand ranking.


**etc........**

---

### ✍️ Writing & Sharing

I believe in continuous learning and sharing knowledge. I write about my journey in software architecture, distributed systems, and AI infrastructure on my [Medium blog](https://medium.com/@vensenmu).
