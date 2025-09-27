# 📌 Conversation Management & Classification using Groq API

This project demonstrates **conversation history management with summarization** and **structured information extraction** using the **Groq API** (OpenAI-compatible client).  

It is an assignment project with the following objectives:  
- Efficiently manage and compress long chat histories.  
- Perform **periodic summarization** to keep conversations concise.  
- Extract structured user details (name, email, phone, location, age) using **JSON schema classification**.  
- Provide a clean and well-documented implementation without external frameworks.

---

## 🚀 Features

### ✅ Task 1: Conversation Management & Summarization
- Maintains a **running conversation history** between user and assistant.  
- **Summarizes conversation** after every *k* turns.  
- Supports **truncation** of conversation history:  
  - By number of turns.  
  - By character limit.  
  - By word limit.  
- Stores **summary history** for later reference.  
- Demonstrated with a **restaurant recommendation chat**.

### ✅ Task 2: JSON Schema Classification & Information Extraction
- Defines a **JSON schema** with 5 fields:
  - `name`
  - `email`
  - `phone`
  - `location`
  - `age`
- Uses **Groq API function calling** for structured extraction.  
- Includes **regex-based fallback extraction** if API fails.  
- Implements **data validation & cleaning** for extracted fields.  
- Demonstrated with **3 sample chat conversations**.

---
