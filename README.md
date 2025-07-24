# 📄 RAG with HuggingFace Embeddings + FAISS + Gemini 2.0 Flash
- This is a lightweight RAG (Retrieval-Augmented Generation) demo using:
- HuggingFace sentence-transformer embeddings
- FAISS vector store for similarity search
- Google's Gemini 2.0 Flash model for generation
- Built with Streamlit for a simple web interface

🚀 Features
- Upload a PDF and automatically extract its text.
- Split the text into manageable chunks using CharacterTextSplitter.
- Embed the chunks using sentence-transformers/all-MiniLM-L6-v2.
- Store embeddings in a FAISS vector database.
- Retrieve relevant chunks for a given query using semantic search.
- Use Google's Gemini 2.0 Flash model to generate accurate answers based on retrieved context.

🛠️ Tech Stack
Component	Description
Streamlit	Frontend UI
PyPDF	PDF text extraction
LangChain	Text splitting + schema
HuggingFace Embeddings	all-MiniLM-L6-v2 sentence transformer
FAISS	Vector similarity search
Google Generative AI	Gemini 2.0 Flash model

📁 Project Structure

├── app.py               # Main Streamlit app
├── .env                 # Your Google API key
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation

📌 Notes
- This is a simple local demo and does not persist documents or vectors.
- Best suited for small to medium-sized documents.
- Ensure that Gemini's API access is enabled in your Google account.

💡 Example Use Cases
- Quick insights from research papers
- Summarizing and querying contracts or reports
- Contextual Q&A over internal documentation

