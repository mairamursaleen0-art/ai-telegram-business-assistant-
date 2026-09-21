<img width="1278" height="838" alt="30 07 2026_23 57 56_REC" src="https://github.com/user-attachments/assets/cf80a03a-e972-462d-afc4-7d88e81e4e9e" />


# AI Telegram Business Assistant

An intelligent Telegram Business Assistant built with **n8n** that uses AI, RAG, and workflow automation to handle customer conversations, capture qualified leads, and automate business processes.

## Overview

This workflow connects Telegram with an AI Agent powered by **Groq** to understand customer queries and provide relevant business information.

The system uses **Pinecone as a vector database** to retrieve information from a knowledge base, while Simple Memory maintains conversation context. It can also extract important customer details and automatically store qualified leads in Google Sheets.

## Workflow

**Telegram → AI Agent → Pinecone Knowledge Base → Response → Information Extraction → Google Sheets → Gmail Notification**

### How It Works

1. Receives customer messages through Telegram.
2. Uses a **Groq-powered AI Agent** to understand and process customer queries.
3. Retrieves relevant information from a **Pinecone vector database** using RAG.
4. Maintains conversation context using **Simple Memory**.
5. Generates and sends an intelligent response back through Telegram.
6. Extracts important lead information such as name, email, company, budget, and requirements.
7. Stores qualified lead information in Google Sheets.
8. Sends an automated Gmail notification with the captured lead details.

## Key Features

* 🤖 AI-powered Telegram conversations
* 🧠 RAG-based knowledge retrieval
* 📚 Pinecone vector database integration
* 💬 Automated customer support
* 🧾 Customer information extraction
* 📊 Automated lead capture
* ✉️ Gmail lead notifications
* 🧠 Conversation memory
* ⚡ End-to-end business workflow automation

## Tech Stack

* **n8n**
* **Groq LLM**
* **Pinecone**
* **Telegram Bot API**
* **Google Sheets**
* **Gmail**
* **Information Extractor**
* **Simple Memory**
* **RAG**

## Use Cases

This business assistant can be adapted for:

* Customer support
* Lead generation
* Lead qualification
* Product or service inquiries
* Business FAQs
* Customer information collection
* Automated sales assistance

## Project Goal

The goal of this project is to demonstrate how **AI Agents, RAG, and workflow automation** can work together to create an intelligent business assistant that handles customer conversations, captures leads, and automates repetitive business processes.

---

**Built with n8n + Groq + Pinecone + Telegram**
