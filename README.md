# Insurance-chatbot

# Insurance Policy Chatbot

This is an AI-powered chatbot that helps users understand insurance documents. It extracts relevant context from a PDF file and answers natural language questions using DeepSeek's large language model.This model was made on Google colab notebook.

---

##  Features

- Upload any insurance policy PDF
- Asks questions in natural language
- Uses DeepSeek LLM via OpenRouter API
- Streamlit web UI
- Fast and efficient search with FAISS vector store

---
 # Install dependencies
 
 pip install -r requirements.txt

pip install faiss-cpu

#  API Key Setup

This app uses DeepSeek via OpenRouter. 

# Project Structure

insurance-chatbot/

├── app.py                 
├── requirements.txt      
├── README.md 

# Running the App

If running in your terminal:

streamlit run app.py

