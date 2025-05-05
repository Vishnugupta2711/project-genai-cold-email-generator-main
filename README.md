# 📧 Cold Mail Generator

**Cold email generator for service companies** built using **Groq**, **Langchain**, and **Streamlit**.  
This tool helps you create highly personalized cold emails by extracting job listings from a company's careers page and suggesting portfolio links based on the job description.

---

## 🚀 Features
- Input the URL of a company's **careers page**.
- Automatically **extract job listings** from the page.
- Generate **personalized cold emails** aligned with each job description.
- Include **relevant portfolio links** sourced dynamically from a **vector database**.

---

## ✨ Example Scenario
Imagine this:

- **Nike** is hiring for a **Principal Software Engineer**.
- They are investing time and money in hiring, onboarding, and training.
- **Atliq**, a software development company, can quickly deploy an expert engineer for Nike.
- **Mohan**, the Business Development Executive at Atliq, uses the Cold Mail Generator to send Nike a **personalized, relevant email** — offering immediate solutions.

> 📩 **Result:** Higher chance of response and business collaboration.

![Demo Screenshot](imgs/img.png)

---

## 🏗️ Architecture Diagram

Here’s how it all fits together:

![Architecture Diagram](imgs/architecture.png)

---

## ⚙️ Getting Started

### 1. Set Up Your API Key
- Go to [Groq Console](https://console.groq.com/keys) and generate your API Key.
- Update the `app/.env` file:
  ```bash
  GROQ_API_KEY=your_api_key_here


Attribution is required in all copies or substantial portions of the software.



