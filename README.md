



# 🤖 RAG App with ChromaDB & LLM API

This project is a demo of a **Retrieval-Augmented Generation (RAG)** application built using [Streamlit](https://streamlit.io/), [ChromaDB](https://www.trychroma.com/), and an LLM API (SkillCaptain in this case). The app allows users to build a knowledge base, perform semantic search, and generate contextual responses using RAG.

## 🧠 What is RAG?

RAG combines the power of vector databases (retrieval) with Large Language Models (generation) to provide:
- More accurate and contextual answers
- Reduced hallucinations
- Domain-specific knowledge enhancement without retraining

---

## 📂 Features

- ✅ Add documents (sample or custom) to ChromaDB
- 🔍 Perform semantic search using vector similarity
- 💬 Ask questions and get RAG-powered responses
- 🎓 Compare direct LLM answers with RAG-enhanced answers

---

## 🛠️ Tech Stack

- **Frontend/UI**: Streamlit
- **Vector Store**: ChromaDB (in-memory)
- **LLM API**: SkillCaptain API (used for prompt completion)
- **Language**: Python

---

## 🧑‍💻 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/rag-app-chromadb.git
   cd rag-app-chromadb


2. **Create and activate a virtual environment** (optional but recommended)

   ```bash
   python -m venv venv
   source venv/bin/activate   # For Windows: venv\Scripts\activate
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Streamlit app**

   ```bash
   streamlit run app.py
   



## 🌐 Deployment Instructions (Streamlit Cloud)

You can deploy this app for free using [Streamlit Community Cloud](https://streamlit.io/cloud).

### Steps:

1. Push your code to a public GitHub repository.

2. Go to [https://streamlit.io/cloud](https://streamlit.io/cloud) and sign in.

3. Click **"New app"** → Select your repository and `app.py` as the entry point.

4. Add your `requirements.txt` file (example below) to install dependencies.

5. Click **Deploy**. Your app will be live on a public URL!

---

## 📄 Example `requirements.txt`

```txt
streamlit
chromadb
requests
```

*(You can generate this by running `pip freeze > requirements.txt` after installing your packages.)*

---

## 🚀 API Configuration

The app uses a SkillCaptain LLM API. If you're using a different API, replace the `call_skillcaptain_api` function in `app.py` with your own endpoint and logic.

---

## 📸 Screenshots
![image](https://github.com/user-attachments/assets/29f4d0fb-4cc2-4482-a088-31681a643f91)

![image](https://github.com/user-attachments/assets/5ccc1a53-7010-45c9-97fb-5888458f4e46)



> 

---

## ✨ What You’ll Learn

* How to use **vector embeddings** to store and retrieve knowledge
* How to create **RAG prompts** for better question answering
* How to build modern apps using **Streamlit** and deploy them
* How to **compare LLM-only vs RAG-augmented** answers side by side

---

## 🙏 Acknowledgements

* [ChromaDB](https://www.trychroma.com/)
* [Streamlit](https://streamlit.io/)
* [SkillCaptain](https://skillcaptain.app/) API (used for LLM responses)

---

## 📜 License

MIT License. Feel free to use, remix, and share.

---

## 💡 Future Ideas

* Add support for file uploads (PDF, TXT)
* Integrate OpenAI/Gemini LLMs
* Use persistent ChromaDB storage
* Add user authentication for multiple user IDs

---

## 📬 Contact

Made with ❤️ by [Tarosh Rao](https://github.com/taroshrao)


