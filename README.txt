# 🍽️ AI-Powered Restaurant Feedback Automation (n8n Workflow)

## 📌 Description
This project is an automated workflow built باستخدام n8n that collects restaurant customer feedback, performs AI-based sentiment analysis, stores results in Google Sheets, and sends real-time email notifications.

---

## ❗ Problem Statement
Restaurants receive large amounts of customer feedback, but:
- It is often unstructured
- Hard to analyze manually
- Delays response to negative experiences

---

## 💡 Solution Overview
This workflow automates the entire pipeline:
1. Collect feedback via form
2. Analyze sentiment using AI (Groq LLM)
3. Store structured data in Google Sheets
4. Send email alerts for monitoring

---

## ⚙️ Features
- 📋 Automated form-based data collection
- 🤖 AI sentiment analysis (Positive / Negative)
- 📊 Data storage in Google Sheets
- 📧 Email notifications for new feedback
- ⚡ Fully automated workflow using n8n

---

## 🧰 Tech Stack
- n8n (Workflow Automation)
- Groq API (LLM - allam-2-7b)
- LangChain Agent (AI Processing)
- Google Sheets API
- Gmail API

---

## 🏗️ Workflow Architecture

Form Trigger → AI Agent → Google Sheets → Email Notification

---