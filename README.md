<h1 align="center">
Multi-Agent AI Chatbot for E-Commerce with Automated Order Processing & Stock Management
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Automation-n8n-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/AI%20Agent-LLM-blueviolet?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Chatbot-Telegram-2CA5E0?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Database-Google%20Sheets-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/E--Commerce-KickSpace-black?style=for-the-badge"/>
</p>

---

### 👤 Author
**Muhammad Abyan Nurfajarizqi**  
📧 Email: muhammadabyan077@gmail.com  

---

## 📌 Project Overview

> *"An AI-powered conversational commerce system that automates customer interaction, order handling, inventory stock management and payment validation using Multi-Agent AI architecture."*

This project implements a **smart multi-agent AI chatbot** built using **n8n + LLM** to automate e-commerce operations.  
The chatbot acts as a **virtual store assistant** capable of handling customer inquiries, assisting checkout processes, recording transactions, and **automatically reducing product stock after successful payment confirmation**.

The goal of this system is to **reduce manual workload**, improve customer shopping experience, ensure inventory accuracy, and provide seamless automation in e-commerce operations.

<img width="1002" height="496" alt="Workflow" src="https://github.com/user-attachments/assets/c73d8cc4-62ad-4776-998f-37c22e7747eb" />

---

## 🎯 Key Capabilities

| Feature | Description |
|--------|------------|
| Product Inquiry Handling | AI answers product availability, size, and price |
| Smart Conversation Flow | Guides customer step-by-step during checkout |
| Payment Handling Process | Accepts proof of payment for verification workflow |
| Automatic Stock Reduction | System automatically decreases stock once payment is validated |
| Google Sheets Integration | Stores transaction & inventory updates automatically |
| Real-Time Telegram Interaction | Customers interact directly via chatbot |

---

## 🖼️ Workflow Pipeline

1️⃣ Customer chats via Telegram  
2️⃣ AI understands intent (ask / order / pay)  
3️⃣ AI guides user through checkout  
4️⃣ System extracts structured order details  
5️⃣ User confirms payment  
6️⃣ **Stock automatically reduced**  
7️⃣ Final confirmation sent to customer

---

## 🔧 Technical Implementation

### 1️⃣ Telegram Interaction Layer
- Acts as the main communication channel
- Supports text & image message handling
- Designed to provide natural conversational experience

### 2️⃣ AI Reasoning & Multi-Agent Logic
- Uses LLM intelligence to:
  - Understand customer intent
  - Extract order data
  - Manage conversation context
  - Decide next system actions

### 3️⃣ Google Sheets Integration
Stores structured data for:
- Customer identity
- Order information
- Payment status
- **Stock value adjustment**

---

## ⚠️ Important Note
> Payment confirmation and proof of transfer used in this project are **DEMO ONLY**  
> No real financial transactions are processed.

This ensures the project remains:
✔️ Safe  
✔️ Ethical  

---

## 🚀 Deployment Guide

### 1️⃣ Import Workflow to n8n
- Open **n8n dashboard**
- Click **Import Workflow**
- Upload JSON workflow file

### 2️⃣ Configure Required Credentials

| Service | Purpose |
|--------|------------|
| Telegram Bot API | Chat interaction |
| OpenAI / LLM Provider | AI reasoning |
| Google Sheets OAuth2 | Transaction logging & stock update |

---

## 🔐 Security Notice
No sensitive credentials are stored in this repository.

- All Chat ID, Webhook ID, Google Sheet ID & credentials are sanitized
- All sensitive configurations must be set securely inside n8n
- Repository is safe for public sharing

---

## 🏆 Result

### 1️⃣ **Customer ask about Product Recommendation via Telegram**

  <img width="1113" height="888" alt="Screenshot 2025-12-27 185814" src="https://github.com/user-attachments/assets/78779bca-59a8-485f-a5fb-4b211d747ff3" />

---
  
### 2️⃣ **Customer ask about price and want to buy a Product**

  <img width="1117" height="889" alt="Screenshot 2025-12-27 190347" src="https://github.com/user-attachments/assets/917d9ed6-c98b-4d64-8f55-c502d134ef89" />



### 3️⃣ **Customer Confirm Purchase and Chatbot gives Invoice**

  <img width="1055" height="564" alt="Screenshot 2025-12-27 190556" src="https://github.com/user-attachments/assets/bc5d1a2b-f3aa-4be2-b941-4d1a6589d623" />

---

### 4️⃣ **Customer Send Payment Proof and Chatbot Validating**

  <img width="1113" height="883" alt="Screenshot 2025-12-27 190850" src="https://github.com/user-attachments/assets/6ac5d3a0-97d2-4af3-a0f4-76c6b89fbce9" />

---

### 5️⃣ **Stock Product (Before & After Payment)**

  <img width="640" height="480" alt="Before (2)" src="https://github.com/user-attachments/assets/b7fab976-8c4d-40f1-acd4-20bc88ed4b81" />
  
---
