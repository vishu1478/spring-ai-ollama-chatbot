# Spring AI + Ollama Local Chatbot

A simple AI chatbot built using **Spring Boot** and **Spring AI** that connects to a locally running **Ollama LLM (Llama3)**.

This project demonstrates how to build a **local AI-powered backend application without using paid APIs**.

---

## 🚀 Features

- Local AI model using Ollama
- Llama3 integration
- Spring AI chat client
- REST API endpoint for AI queries
- Simple HTML UI for chatting

---

## 🛠 Tech Stack

- Java 17
- Spring Boot
- Spring AI
- Ollama
- Llama3 LLM
- Maven

---

## 📂 Project Architecture

```
Browser UI
     │
     ▼
Spring Boot REST API
     │
     ▼
Spring AI
     │
     ▼
Ollama API (localhost:11434)
     │
     ▼
Llama3 Model
```

---

## ⚙️ Setup Instructions

### 1 Install Ollama

Install Ollama from:

https://ollama.com

Run the model:

```
ollama run llama3
```

---

### 2 Run the Spring Boot Application

```
mvn spring-boot:run
```

---

### 3 Call the API

```
http://localhost:8080/ai/ask?question=Explain Spring Boot
```

---

## 📸 Example Response

```
Spring Boot is a Java framework used to build standalone production-ready Spring applications.
```

---

## 📌 Future Improvements

- Streaming responses
- Chat history
- Vector database integration
- AI document search
- Web UI improvements

---

## 👨‍💻 Author

Vishwajeet Agrwal
