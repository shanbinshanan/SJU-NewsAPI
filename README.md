# SJU-NewsAPI
## 📌 Project Overview
In this mini-project, each team will focus on retrieving news articles using a designated free API from the provided list. Teams will extract, clean, and store the data into a designated **S3 bucket on AWS**. 

This project involves:
- Designing **efficient workflows** for API interaction, data processing, and storage.
- Implementing **data cleaning & preprocessing** to ensure high-quality datasets.
- Documenting the process for **reproducibility** and future enhancements.

---

## 🛠️ Tech Stack

### **Languages & Tools**
- **Python**
- **AWS CLI / SDK**
- **Jupyter Notebooks**

### **Libraries Used**
- `requests` → API interaction  
- `boto3` → AWS S3 integration  
- `pandas` → Data processing  
- `json` → Data storage  

### **Storage**
- **AWS S3 Bucket** (provided by the instructor)

### **Development Environment**
- **Local Setup** (Jupyter Notebook, VS Code)  
- **Cloud-Based Setup** (Google Colab, AWS Cloud9)

---

## 🚀 Project Workflow

### **1️⃣ Data Retrieval**
- Use **NewsAPI** to fetch **news articles** in different categories (e.g., health, business, finance).
- Retrieve up to **300 articles** in total.

### **2️⃣ Data Cleaning & Preprocessing**
- Remove **duplicates** and **irrelevant fields**.
- Handle **missing values** and ensure data consistency.

### **3️⃣ Data Storage**
- Convert articles into **structured JSON format**.
- Store each article as an **individual JSON file** inside an **S3 bucket**.

---
