# 🚚 FreightQuote AI
### Intelligent AI-Powered Freight Quotation & Logistics Management System

<p align="center">

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-Web%20Application-red?style=for-the-badge&logo=streamlit)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-Retrieval%20Augmented%20Generation-green?style=for-the-badge)
![FAISS](https://img.shields.io/badge/FAISS-Vector%20Database-purple?style=for-the-badge)
![SQLite](https://img.shields.io/badge/Database-SQLite-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-Educational-success?style=for-the-badge)

</p>

---

# 📖 Project Overview

FreightQuote AI is an intelligent logistics management platform that combines **Artificial Intelligence**, **Machine Learning**, and **Retrieval-Augmented Generation (RAG)** to simplify and automate freight quotation, customs compliance, logistics decision-making, and operational workflows.

The system enables logistics professionals to generate accurate freight quotations, retrieve customs and compliance information from an AI-powered knowledge base, predict freight pricing using machine learning, and manage users securely through an administrative dashboard.

Unlike traditional freight management systems, FreightQuote AI integrates AI-based decision support with a Retrieval-Augmented Generation (RAG) pipeline built from official customs resources, enabling users to obtain reliable, context-aware answers to logistics and compliance questions.

---

# 🎯 Problem Statement

Freight and logistics operations involve complex pricing calculations, customs regulations, documentation requirements, and constantly changing compliance rules.

Organizations often rely on multiple disconnected systems and manual documentation, resulting in:

- Time-consuming quotation processes
- Human calculation errors
- Difficult customs compliance verification
- Limited decision support
- Scattered logistics information
- Inefficient workflow management

FreightQuote AI addresses these challenges by providing a unified AI-powered platform for freight quotation, compliance assistance, and logistics intelligence.

---

# 🎯 Project Objectives

The primary objectives of FreightQuote AI are:

- Develop an intelligent freight quotation system.
- Predict freight pricing using Machine Learning.
- Build an AI Copilot for logistics assistance.
- Create a Retrieval-Augmented Generation (RAG) knowledge base using official customs resources.
- Automate logistics knowledge retrieval.
- Improve customs compliance awareness.
- Provide secure authentication and authorization.
- Deliver an intuitive Streamlit-based user interface.
- Enable administrators to manage users efficiently.

---

# ✨ Key Features

## 🤖 AI Copilot

- Intelligent logistics assistant
- Natural language interaction
- Freight-related question answering
- Compliance guidance
- AI-powered recommendations

---

## 📊 Machine Learning Freight Prediction

- Predicts freight quotation cost
- Data-driven pricing
- Fast estimation
- Scikit-Learn based prediction model
- Real-time inference

---

## 🔍 Retrieval-Augmented Generation (RAG)

The project incorporates a complete RAG pipeline that enhances AI responses using an external logistics knowledge base.

### Knowledge Sources

- US Customs (CBP)
- UK Government Customs
- European Union Customs
- Indian Customs (CBIC)
- DGFT
- Compliance Documents
- Freight Rules
- Logistics Guidelines
- PDF Documentation

---

## 🌐 Intelligent Web Scraping

Automatically collects logistics information from trusted government websites.

Features include:

- Website crawling
- HTML parsing
- PDF detection
- Dynamic knowledge collection
- Data preprocessing

---

## 📄 PDF Knowledge Extraction

The system automatically:

- Detects PDF files
- Downloads PDF documents
- Extracts text using PyMuPDF
- Adds extracted information to the knowledge base

---

## 🧠 AI Knowledge Base

The RAG knowledge base includes information related to:

- Customs regulations
- Incoterms
- Dangerous goods
- Port congestion
- Freight pricing
- Weather rerouting
- Bill of Lading
- CBAM regulations
- IMO 2020
- ISF 10+2
- Electronics customs compliance

---

## 👥 User Authentication

The platform provides secure authentication including:

- User Registration
- Login
- Password Reset
- OTP Verification
- Security Questions
- Password Encryption
- Role-Based Access

---

## 👨‍💼 Admin Dashboard

Administrators can:

- View registered users
- Unlock user accounts
- Delete users
- Monitor AI usage
- View ML model metrics
- Access system analytics

---

## 📈 Analytics Dashboard

Interactive dashboard presenting:

- Model performance
- System metrics
- User activity
- AI usage statistics
- Prediction analytics

---

# 🛠 Technology Stack

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Frontend | Streamlit |
| Machine Learning | Scikit-Learn |
| AI | Generative AI |
| RAG Framework | LangChain |
| Vector Database | FAISS |
| Embeddings | HuggingFace Sentence Transformers |
| Database | SQLite |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib |
| Web Scraping | BeautifulSoup, Requests |
| PDF Processing | PyMuPDF (fitz) |
| Authentication | JWT, bcrypt |
| Version Control | Git & GitHub |

---

# 🏗 System Architecture

```
                    +-----------------------+
                    |      User Interface   |
                    |      (Streamlit)      |
                    +-----------+-----------+
                                |
                                v
                 +-------------------------------+
                 |      FreightQuote AI Engine   |
                 +---------------+---------------+
                                 |
         +-----------------------+-----------------------+
         |                       |                       |
         v                       v                       v
 AI Copilot Module      ML Prediction Module      Admin Module
         |                       |                       |
         +-----------------------+-----------------------+
                                 |
                                 v
                      Retrieval-Augmented Generation
                                 |
          +----------------------+----------------------+
          |                                             |
          v                                             v
   FAISS Vector Store                         Logistics Knowledge Base
          |                                             |
          +----------------------+----------------------+
                                 |
                                 v
                    Government Websites & PDF Documents

```

---

# 📂 Major Modules

The project is divided into the following major components:

### 🏠 Home Module

Provides the project introduction and navigation.

---

### 🤖 AI Copilot

Allows users to ask logistics-related questions using natural language.

---

### 📊 Freight Price Prediction

Uses Machine Learning to estimate freight costs.

---

### 📚 RAG Knowledge Base

Retrieves relevant logistics information before AI generates responses.

---

### 👥 Authentication Module

Handles user registration, login, password reset, and account security.

---

### 👨‍💼 Admin Panel

Provides administrative controls and monitoring features.

---

### 📈 Analytics

Displays machine learning metrics and operational statistics.

---

> 📌 **Next:** **Part 2** will cover:
>
> - 📁 Project Folder Structure
> - ⚙ Installation Guide
> - 💻 Software Requirements
> - 📦 Library Requirements
> - 🚀 How to Run the Project
> - 🔑 API Key Configuration
> - 🗄 Database Setup
> - 📂 RAG Builder Setup
