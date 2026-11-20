<div align="center">

# 🚀 Engineering Projects

**Enterprise data pipelines built for analytics, retrieval, and reliability.**

[← Back to Portfolio](../README.md) · [Experience](experience.md) · [Tech Stack](tech-stack.md)

</div>

---

## 🧠 Enterprise RAG Data Pipeline & Evaluation Harness

**Repository:** [github.com/sumitingaleSplendid/enterprise-rag-pipeline](https://github.com/sumitingaleSplendid/enterprise-rag-pipeline)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![LlamaIndex](https://img.shields.io/badge/LlamaIndex-6554C0?style=flat-square) ![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=flat-square&logo=amazons3&logoColor=white) ![AWS Glue](https://img.shields.io/badge/AWS_Glue-232F3E?style=flat-square) ![Pinecone](https://img.shields.io/badge/Pinecone-111827?style=flat-square) ![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)

### What It Demonstrates

- Ingestion and preprocessing of document data for downstream retrieval.
- Semantic chunking and vector indexing using LlamaIndex and Pinecone.
- AWS S3 and Glue components for cloud data workflows.
- Airflow orchestration of data processing steps.
- Evaluation-oriented workflows for RAG response and retrieval quality.

### Conceptual Workflow

```mermaid
flowchart LR
    A[Documents] --> B[AWS S3 / Glue]
    B --> C[Semantic Chunking]
    C --> D[Vector Index / Pinecone]
    D --> E[Retrieval]
    E --> F[Evaluation Harness]
```

[**Explore repository →**](https://github.com/sumitingaleSplendid/enterprise-rag-pipeline)

---

## 🏦 Claims & Fraud Benchmark Data Platform

**Repository:** [github.com/sumitingaleSplendid/claims-fraud-platform](https://github.com/sumitingaleSplendid/claims-fraud-platform)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square) ![AWS Step Functions](https://img.shields.io/badge/AWS_Step_Functions-232F3E?style=flat-square) ![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white) ![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)

### What It Demonstrates

- Claims and fraud-focused data processing pipelines.
- Workflow coordination using AWS Step Functions.
- Snowflake-based storage and analytics models.
- dbt transformations and SQL validation.
- Repeatable benchmark-oriented data preparation.

### Conceptual Workflow

```mermaid
flowchart LR
    A[Claims Data] --> B[Python / SQL Processing]
    B --> C[AWS Step Functions]
    C --> D[(Snowflake)]
    D --> E[dbt Models & Tests]
    E --> F[Fraud Analytics]
```

[**Explore repository →**](https://github.com/sumitingaleSplendid/claims-fraud-platform)

---

<div align="center">

[← Back to Main Portfolio](../README.md)

</div>
