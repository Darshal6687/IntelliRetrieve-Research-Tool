# 🧠 IntelliRetrieve Research Tool

**IntelliRetrieve** is a Streamlit-based web application that performs **Retrieval-Augmented Generation (RAG)** on URLs. It scrapes content from user-provided URLs, indexes the content into a vector database, and then uses **LLM-powered QA** to answer user queries with sourced responses.

---

## 📦 Features

- ✅ Scrape and process up to 3 custom URLs
- ✅ Split documents into semantic chunks
- ✅ Store embeddings using `Chroma` vector DB
- ✅ Use Hugging Face embeddings with `all-MiniLM-L6-v2`
- ✅ Ask questions and get answers with sources using `Groq + LLaMA 3`
- ✅ Streamlit UI for interactive research

---

## 🚀 Setup 

1. Run the following command to install all dependencies. 

    ```bash
    pip install -r requirements.txt
    ```

2. Create a .env file with your GROQ credentials as follows:
    ```text
    GROQ_MODEL=MODEL_NAME_HERE
    GROQ_API_KEY=GROQ_API_KEY_HERE
    ```

3. Run the streamlit app by running the following command.

    ```bash
    streamlit run main.py
    ```
