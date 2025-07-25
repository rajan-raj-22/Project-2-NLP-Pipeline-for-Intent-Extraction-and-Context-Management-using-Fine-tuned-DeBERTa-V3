# 🧠 NLP Pipeline for Intent Extraction and Context Management

## 📌 Project Overview

This project implements an end-to-end NLP pipeline to extract user intent and entities from free-form text commands using a fine-tuned DeBERTa V3 model. It also includes SpaCy for Named Entity Recognition (NER), a simple context manager, and a document classifier for intelligent query handling in real-world applications.

---

## 🚀 Features

- Fine-tuned DeBERTa V3 model for intent classification.
- Supports 4 intents:
  - `GENERATE_DOCUMENT`
  - `UPDATE_RULES`
  - `QUERY_INFORMATION`
  - `DELETE_DOCUMENT`
- Named Entity Recognition using SpaCy (`en_core_web_sm`).
- Lightweight context management.
- Modular class-based design for easy integration into larger systems.

---

## 📂 Project Structure

