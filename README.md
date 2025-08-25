# 🔍 Research Assistant (LangChain + OpenAI + FAISS)

An intelligent **Research Agent** built with **Streamlit, LangChain, OpenAI, and FAISS**.  
It allows you to **input URLs**, automatically **load & process articles**, build a **local vector store**,  
and then ask **research questions** with **AI-powered answers + sources**.

---

## ✨ Features
- 🌐 Load documents directly from URLs (news, blogs, articles, etc.)
- 📖 Split text into chunks for better embedding & retrieval
- 🧠 Generate embeddings using **OpenAI**
- 📂 Store & retrieve context using **FAISS Vector Store**
- 🤖 Ask natural language questions and get **answers with cited sources**
- ⚡ Built with **Streamlit** for a clean & interactive UI

---

## 🛠️ Tech Stack
- [Streamlit](https://streamlit.io/) – UI framework  
- [LangChain](https://www.langchain.com/) – LLM orchestration  
- [OpenAI GPT models](https://platform.openai.com/) – for Q&A  
- [FAISS](https://github.com/facebookresearch/faiss) – Vector search  
- [Unstructured](https://github.com/Unstructured-IO/unstructured) – Document loading  

---

## 📂 Project Structure
Research-Agent/
│── main.py # Streamlit app
│── requirements.txt # Dependencies
│── .env # Stores API key (not committed)
│── faiss_index/ # Vectorstore (auto-generated)

yaml
Copy
Edit

---

## ⚙️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/Research-Agent.git
   cd Research-Agent
Create a virtual environment (optional but recommended)

bash
Copy
Edit
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Set your OpenAI API key

Create a .env file in the project root:

ini
Copy
Edit
OPENAI_API_KEY=sk-proj-xxxxxxxxxxxxxxxx
▶️ Usage
Run the Streamlit app:

bash
Copy
Edit
streamlit run main.py
Open the app in your browser → http://localhost:8501

Demo Example
URL:

arduino
Copy
Edit
https://www.bbc.com/news/science-environment-68543241
Question:

perl
Copy
Edit
What does the article say about the link between climate change and extreme weather?


🚀 Future Improvements
Support for PDF/DOCX uploads

Multi-URL cross-analysis

Conversation history (chat mode)

Export results to CSV/Markdown

🤝 Contributing
Pull requests are welcome!
For major changes, please open an issue first to discuss what you’d like to change.

📜 License
MIT License © 2025 Srijan Roy
