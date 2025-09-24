**Banking-assistant-chatbot**

A conversational **Banking FAQ Chatbot** built with **Flask**, **Sentence Transformers**, **FAISS**, and **Google Gemini API**.  
It helps users get instant answers to common banking-related queries using semantic search and AI-powered responses.  
The project also includes a modern **chat UI** for a user-friendly experience.

**Features**
- Semantic search using **FAISS** to find the most relevant FAQ.  
- Embeddings generated with **Sentence Transformers** (`all-MiniLM-L6-v2`).  
- AI-powered responses using **Google Gemini API**.  
- Modern and responsive **chat interface** with:  
  - Dark/Light mode toggle  
  - Typing indicator  
  - Chat bubbles (Messenger/WhatsApp style)  
- REST API (`/ask`) + Chat UI (`/chat`).  

**Tech Stack**
- **Backend**: Flask (Python)  
- **Semantic Search**: FAISS  
- **Embeddings**: Sentence Transformers  
- **LLM API**: Google Gemini  
- **Frontend**: HTML, CSS, JavaScript (in Flask template)

- 1 Create virtual environment (recommended)
python -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate      # On Windows

- 2 Install dependencies
pip install -r requirements.txt

- 3 Set up environment variable

You need a Google Gemini API key.
Create a .env file or set it in your terminal:

export GEMINI_API_KEY=your_api_key_here   # Mac/Linux
set GEMINI_API_KEY=your_api_key_here      # Windows

- 4 Run the application
python app.py


The app will run locally at:

http://127.0.0.1:5000


