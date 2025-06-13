# ObscurifyIT – Automated Data Redaction Tool

## 🔐 Overview
ObscurifyIT is a machine learning-powered redaction tool designed to detect and anonymize sensitive information (PII/PHI) in unstructured text documents. It supports synthetic data generation to retain utility and complies with modern privacy regulations like GDPR and HIPAA.

## 🎯 Key Features
- NLP-based PII/PHI detection using NER models
- Customizable redaction styles (mask, remove, replace)
- GAN-powered synthetic replacements for anonymized data
- Support for text and PDF formats
- Compliance-focused design (GDPR, HIPAA, CCPA)
## 🚀 How to Run ObscurifyIT

### 1. Clone the Repository

```bash
git clone https://github.com/GayaStar/ObscurifyIT.git
cd ObscurifyIT

### 2.Start the Frontend
npm install
npm start

### 3.Start the Backend
pip install -r requirements.txt
python app1.py
### 4.Start the Auth Server (Node.js)
bash
Copy
Edit
cd public/server
npm install
node server.js
