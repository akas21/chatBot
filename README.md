# 🌐 ChatBot (Langchain,streamlit , OpenAI GPT)

This is a simple demo project that integrates **LangChain**, **OpenAI GPT**, and **Streamlit** into an interactive chatbot web app.  
The app takes a user query, processes it with LangChain pipelines, and displays the response from OpenAI's GPT model.

---

## ⚡ Features
- 🔹 Built with **LangChain Expression Language (LCEL)** (`prompt | llm | parser`)
- 🔹 Uses **OpenAI GPT-3.5 Turbo** for responses
- 🔹 Clean **Streamlit UI**
- 🔹 **Environment variable support** with `.env`
- 🔹 Optional **LangSmith tracing** for debugging & monitoring

---

## 📂 Project Structure
project/
│── app.py # Main Streamlit app
│── .env # Store API keys here
│── requirements.txt # Python dependencies
│── README.md # Project documentation
