# 📚 Docu-Chat-Pro using LangChain & ChatGPT API

Welcome to this powerful AI-driven chatbot project that enables you to **ask questions** and extract insights from PDF document using **LangChain, ChatGPT API, and Huggingface Language Models**. 🚀

## 🔥 Key Features
✅ **Chat with PDF** – Upload  PDF document and interact with them like never before!  
✅ **Powered by ChatGPT API** – Uses OpenAI's ChatGPT for intelligent and context-aware responses.  
✅ **Huggingface LLM Support** – Leverage Huggingface's language models for enhanced chatbot performance.  
✅ **LangChain Integration** – Utilize the latest framework for seamless AI-powered interactions.  
✅ **Persistent Conversations** – Keep track of previous conversations for a smooth experience.  
✅ **GUI Implementation** – A user-friendly interface for easy interaction.  

---

## 📌 How It Works
1️⃣ **Upload PDF** – The app extracts text from the uploaded PDF.  
2️⃣ **Chunking & Embeddings** – Splits text into manageable chunks and generates embeddings.  
3️⃣ **Query Processing** – The user asks a question, and the model fetches relevant information.  
4️⃣ **Response Generation** – The chatbot provides answers based on extracted content.  
5️⃣ **Conversation History** – Keeps track of past interactions for a seamless user experience.  

---

## 🛠 Tech Stack
- **Frontend**: HTML, CSS, JavaScript, React (Optional for UI improvements)
- **Backend**: Python, Flask
- **AI Models**: OpenAI's GPT (3.5/4), Huggingface LLMs
- **Frameworks**: LangChain
- **Database**: Vector databases for efficient search & retrieval
- **Hosting**: Can be deployed on cloud platforms like AWS, Google Cloud, or Huggingface Spaces

---

## 🚀 Installation Guide
1️⃣ Clone the repository

2️⃣ **Set up a virtual environment**  
    python -m venv venv
    source venv/bin/activate  # On macOS/Linux
    venv\Scripts\activate  # On Windows


3️⃣ **Install dependencies**  
    pip install -r requirements.txt


4️⃣ **Add API keys**  
Create a `.env` file and add your **OpenAI** and **Huggingface API keys**:  

OPENAI_API_KEY=your_openai_api_key
HUGGINGFACE_API_KEY=your_huggingface_api_key




6️⃣ **Access the Web App**  
Open your browser and go to:  
👉 `http://localhost:5000`  

---

## 🏗 Project Structure
```
📂 chat-with-pdfs
 ├── 📂 templates        # HTML templates for UI
 ├── 📂 static           # CSS & JS files
 ├── 📂 data             # Uploaded PDF file
 ├── app.py             # Main Flask application
 ├── extract.py         # Extract text from PDFs
 ├── langchain_utils.py # Handles LangChain integration
 ├── chat.py            # Chat logic using OpenAI & Huggingface models
 ├── requirements.txt   # List of dependencies
 ├── README.md          # You are here!
```

---

## 📊 Workflow Diagram
```
[PDF Upload] → [Extract Text] → [Chunk & Embed] → [User Query] → [Fetch Relevant Content] → [Generate Response] → [Display Answer]
```

---

## 💡 Future Enhancements
🔹 **Multi-Language Support** – Expand to support multiple languages.  
🔹 **More AI Models** – Integrate additional LLMs for variety.  
🔹 **Cloud Storage** – Store and retrieve PDFs from cloud services.  
🔹 **Mobile App Version** – Extend functionality to mobile platforms.  

---

---

Happy Coding! 🚀💡

