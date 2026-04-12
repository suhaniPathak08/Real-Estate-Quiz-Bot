# Real Estate Educational Bot

An AI-powered educational quiz bot that helps users learn real estate concepts through interactive multiple-choice questions, explanations, and real-world examples.

---

## 🚀 Overview

This quiz bot is built using **Generative AI + RAG (Retrieval-Augmented Generation)** to provide accurate and engaging learning experiences.
It generates quiz questions dynamically and evaluates user answers with detailed explanations.

---

## 🎯 Problem Statement

Understanding real estate concepts like property valuation, legal disclosures, and closing costs is often difficult for beginners.

Traditional methods lack:

* Interactivity
* Personalization
* Immediate feedback

👉 This project solves that by providing an **AI-driven quiz-based learning system**.

---

## ✨ Key Features

* ✅ AI-generated MCQ questions
* ✅ Real-time answer evaluation
* ✅ Detailed explanations in simple language
* ✅ Real-world examples & memory tips
* ✅ Session tracking (score & accuracy)
* ✅ Beginner-friendly UI using Streamlit
* ✅ RAG-based responses (no hallucination)

---

## 🏗️ System Architecture

The system consists of 4 main layers:

### 1. Presentation Layer

* Built with **Streamlit**
* Handles UI and user interaction
* File: `app.py`

### 2. AI Layer

* Uses **Google Gemini API**
* Generates questions and evaluates answers
* Modules:

  * `quiz_generator.py`
  * `tutor_chat.py`

### 3. RAG Layer

* Retrieves relevant knowledge using embeddings
* Modules:

  * `embeddings.py`
  * `vector_db.py` (FAISS)

### 4. Knowledge Base

* File: `real_estate_docs.txt`
* Contains curated real estate topics

---

## 🔄 Workflow

1. User selects a topic
2. System retrieves relevant data using FAISS
3. Gemini generates MCQ question
4. User answers the question
5. System evaluates answer
6. Explanation + result is displayed
7. Session stats are updated

---

## 🛠️ Tech Stack

| Category     | Technology                     |
| ------------ | ------------------------------ |
| Language     | Python                         |
| UI           | Streamlit                      |
| LLM          | Google Gemini 2.5 Flash        |
| Vector DB    | FAISS                          |
| Embeddings   | Sentence Transformers (MiniLM) |
| Architecture | RAG Pipeline                   |


---

## 📊 Output

The system generates structured outputs including:

* MCQ questions (with options & hints)
* Correct/Incorrect evaluation
* Explanation
* Real-world example
* Memory tips

---

## ⚙️ Installation & Setup

```bash
# Clone the repository
git clone https://github.com/your-username/your-repo-name.git

# Navigate to project folder
cd your-repo-name

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
```

---

## 📈 Results

* Interactive learning experience
* Accurate AI responses using RAG
* Fast retrieval with FAISS
* User-friendly interface

---

## 🔮 Future Scope

* Multi-user authentication
* Cloud deployment
* Database for user progress
* More topics & content
* Adaptive difficulty levels
* Voice-based interaction
* Mobile application

---


