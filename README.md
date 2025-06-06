# 🛠️ Incident Log Generator for Root Cause AI Tool

## 📌 Project Overview
This project transforms backend logs and system error outputs into human-readable incident reports using Large Language Models (LLMs). It helps Site Reliability Engineering (SRE) and DevOps teams quickly understand the nature of system failures and their likely causes.

---

## 🧠 Key Features

- 📋 **LLM-based Explanation**: Converts technical logs into plain-English summaries.
- 🔥 **Spark Log Processing**: Efficient batch processing of large-scale system logs.
- 🌐 **FastAPI Interface**: REST endpoints for log-to-report transformation.
- 🧪 **Extensible Log Types**: Works with HTTP errors, DB failures, microservice crashes, etc.

---

## 🛠️ Tech Stack

| Component   | Technology              |
|-------------|--------------------------|
| Log Engine  | Apache Spark             |
| Backend     | Python + FastAPI         |
| LLM         | OpenAI GPT via LangChain |
| Storage     | File System / S3         |

---

## 🚀 Getting Started

### 1. Clone and Install

