# 📚 AI Exam Question Bank Assistant 
 
A Retrieval-Augmented Generation (RAG) based AI assistant that helps students 
search and understand previous exam papers and study notes. 
 
## 🚀 Features 
 
- Upload multiple PDF exam papers or study notes 
- Extract and process PDF documents 
- Split documents into smaller chunks 
- Generate semantic embeddings 
- Store and retrieve documents using ChromaDB 
- Retrieve relevant information using similarity search 
- Generate answers using Groq LLM 
- Identify repeated questions 
- Find important exam questions 
- Topic-wise question retrieval 
- Generate answers from uploaded study material 
- Evaluate RAG performance using LLM-as-a-Judge 
 
## 🏗️ Architecture 
 
PDF Documents 
↓ 
PyPDFLoader 
↓ 
Recursive Character Text Splitter 
↓ 
HuggingFace Embeddings 
↓ 
ChromaDB 
↓ 
Similarity Search 
↓ 
Retrieved Context 
↓ 
Groq LLM 
↓ 
Generated Answer 
 
## 🛠️ Technologies Used 
 
- Python 
- LangChain 
- HuggingFace / SentenceTransformers 
- ChromaDB 
- Groq LLM 
- Gradio 
- PyPDF 
 
## 📊 Evaluation 
 
The system is evaluated using LLM-as-a-Judge based on: 
 
- Faithfulness 
- Answer Relevance 
- Context Relevance 
 
## 💻 Running the Project 
 
The project can be run using Google Colab. 
 
1. Open the Jupyter Notebook. 
2. Install the required dependencies. 
3. Configure the Groq API key. 
4. Upload exam papers or study notes. 
5. Process the PDFs. 
6. Enter a question in the Gradio interface. 
7. View the generated response. 
 
## 🔮 Future Improvements 
- Deploy the application as a public web application
- Add user-specific document collections
- Add automatic exam preparation recommendations
- Deploy the application as a public web application 
- Add user-specific document collections 
- Add automatic exam preparation recommendations        i think this will be good
