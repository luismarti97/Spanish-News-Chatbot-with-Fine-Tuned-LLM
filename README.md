# Spanish-News-Chatbot-with-Fine-Tuned-LLM

This project implements a chatbot that interacts with Spanish news articles using a fine-tuned Large Language Model (LLM). The goal is to enable users to ask questions about news content via a conversational interface.

## 🎯 Objective

To adapt a Spanish-language LLM for chat interactions using fine-tuning techniques (not RAG or prompt engineering), and deploy it using a Gradio-based web interface.

## 🧠 Model and Methodology

- **Base model**: `mistralai/Mistral-7B-Instruct-v0.2`
- **Fine-tuning method**: LoRA (via PEFT library)
- **Training data**: Spanish news articles from sources like *La Razón* and *Público*, reformatted into chat-style conversation pairs.

## 🛠️ Tools and Libraries

- Hugging Face Transformers
- PEFT (Parameter-Efficient Fine-Tuning)
- TRL (Transformer Reinforcement Learning)
- Datasets
- Gradio (for UI)

## 💻 How it Works

1. Loads and preprocesses Spanish news into chat format
2. Fine-tunes a Mistral-based model using LoRA
3. Hosts a simple Gradio interface where users can ask questions
4. Generates responses in Spanish
