# 📧 Customer Support Email Automation

An AI-powered system that automates customer email management using LangGraph workflows, AI agents, and Retrieval-Augmented Generation (RAG) for high-quality, accurate, and personalized email responses.

---

## 📝 Introduction

In today's fast-paced digital landscape, customers expect **quick**, **accurate**, and **personalized** responses. Traditional support teams often struggle with high email volumes, leading to delays, errors, and reduced customer satisfaction.

**Customer Support Email Automation** is an AI-driven solution designed to streamline customer communication. By leveraging a LangGraph-powered workflow, multiple AI agents collaborate to manage inboxes, categorize emails, draft responses, and ensure high-quality communication. Using **Retrieval-Augmented Generation (RAG)**, the system provides precise answers based on your business or product documents.

---

## ✨ Features

### 📥 AI Email Inbox Management
- Monitors the agency’s Gmail inbox continuously  
- Categorizes emails into:
  - Customer complaint  
  - Product inquiry  
  - Customer feedback  
  - Unrelated  
- Automatically filters irrelevant emails to maintain workflow efficiency

### 🤖 AI Response Generation
- Drafts personalized emails for complaints and feedback  
- Uses RAG to deliver accurate product/service-related answers  
- Tailors every email to customer context and tone  

### ✔️ Automated Quality Assurance
- AI checks each email for:
  - Clarity  
  - Formatting  
  - Relevance  
  - Professional tone  
- Ensures only polished responses are sent to clients  

---

## 🛠️ How It Works

1. **Email Monitoring**  
   Constantly checks the Gmail inbox using the Gmail API.

2. **Email Categorization**  
   AI agents classify emails into predefined categories.

3. **Response Generation**  
   - **Complaints/Feedback** → Tailored AI-generated email reply  
   - **Inquiries** → RAG retrieves info from agency documents, then drafts a precise response

4. **Quality Assurance**  
   Each draft is reviewed and refined by an AI quality checker.

5. **Sending**  
   After approval, the system sends the email automatically to the customer.

---

## 🧰 Tech Stack

- **LangChain & LangGraph** – AI workflow and agent orchestration  
- **LangServe** – API deployment (FastAPI)  
- **Groq API** – Access to Llama-3.1-70B  
- **Google Gemini API** – Embeddings for RAG  
- **Gmail API** – Inbox monitoring and email sending  

---

## 🚀 How to Run

### **Prerequisites**
- Python **3.7+**  
- Groq API key  
- Google Gemini API key  
- Gmail API credentials  
- Python libraries from `requirements.txt`

---

### **1. Clone the Repository**
```bash
git clone https://github.com/Avinash3570/Email-Automation
cd Email-Automation
```
### **2. Create & Activate Virtual Environment
```bash
python -m venv venv
source venv/bin/activate     # macOS/Linux
# On Windows:
# venv\Scripts\activate
```
### **3. Install Dependencies
```bash
pip install -r requirements.txt
```
### **4. Add Environment Variables
```bash
MY_EMAIL=your_email@gmail.com
GROQ_API_KEY=your_groq_api_key
GOOGLE_API_KEY=your_gemini_api_key
```
### **5. Enable Gmail API
Follow Google’s guide to enable the Gmail API and download OAuth credentials.
