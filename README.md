# 📚 AI Book Recommendation System

An interactive AI-powered book recommendation engine that leverages semantic search, emotion analysis, and category filtering to deliver personalized reading suggestions based on natural language queries.

![Gradio Dashboard](https://img.shields.io/badge/Built%20With-Gradio-blue?style=flat&logo=python)
![LangChain](https://img.shields.io/badge/LangChain-Enabled-green?style=flat)
![OpenAI API](https://img.shields.io/badge/OpenAI-Powered-ff69b4?style=flat)

---

## 🚀 Features

- 🔍 **Semantic Search**: Retrieves books using vector similarity based on user input and book descriptions.
- 🧠 **Emotion-Aware Filtering**: Recommends books matching a specific emotional tone (e.g., happy, suspenseful).
- 🧾 **Category Support**: Search by genre, mood, or both.
- 📊 **Data Exploration**: Includes Jupyter notebooks for exploring genre trends, ratings, and metadata.
- 🎛️ **Interactive UI**: Built with [Gradio](https://gradio.app/) for a seamless user experience.

---

## 📂 Project Structure

```bash
.
├── data-exploration.ipynb        # EDA on book metadata
├── sentiment-analysis.ipynb      # Emotion tagging for book descriptions
├── vector_search.ipynb           # Building and testing vector similarity search
├── gradio-dashboard.py           # Gradio UI to interact with the system
├── books_with_emotions.csv       # Dataset with processed metadata and emotions
├── .env                          # (Ignored) Contains API keys
└── README.md
