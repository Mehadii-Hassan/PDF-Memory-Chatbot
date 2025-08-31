<h1 align="center">📚 Faculty Info RAG Chatbot</h1>

<p align="center">
  <strong>Conversational AI for University Faculty Information </strong><br>
  Powered by <code>LangChain</code>, <code>FAISS</code>, <code>BM25</code>, and <code>OpenAI/Ollama</code>
</p>

<hr>

<h2>📌 Project Overview</h2>

<p>
This project is a Conversational Retrieval-Augmented Generation (RAG) chatbot.  
It allows students to query faculty details (short names, mobile numbers, emails, room numbers) directly from university PDF files.  
The system combines <strong>semantic search (FAISS)</strong> and <strong>keyword search (BM25)</strong> with memory-aware conversation.
</p>

<ul>
  <li>🔎 Hybrid retrieval (FAISS + BM25)</li>
  <li>🧠 Memory-aware conversational AI</li>
  <li>📄 Multiple PDF support</li>
  <li>⚡ Contextual and concise answers</li>
</ul>

<hr>

<h2>🚀 Features</h2>

<ul>
  <li>📑 Load and process PDF files with <code>PyPDF</code></li>
  <li>🔍 Semantic search with <code>Ollama all-minilm</code> embeddings</li>
  <li>📝 Keyword retrieval with <code>BM25</code></li>
  <li>🤖 Question answering with <code>LangChain</code> & OpenAI GPT</li>
  <li>🧩 History-aware retriever to maintain chat context</li>
</ul>

<hr>

<h2>🧠 How It Works</h2>

<ol>
  <li>Load PDFs containing faculty names and details</li>
  <li>Split documents into chunks for better retrieval</li>
  <li>Index with FAISS + BM25</li>
  <li>Run queries using LangChain RAG pipeline</li>
  <li>Get concise, context-aware answers</li>
</ol>

<hr>

<h2>📂 Folder Structure</h2>

<pre>
pdf-faculty-rag-chatbot/
│
├── Faculty-Name-Short-Form.pdf
├── IUBAT-Department-Wise-Faculty-Information.pdf
├── pdf_memory.ipynb        ← Main Colab Notebook
├── requirements.txt        ← Dependencies
└── README.md               ← Project Documentation
</pre>

<hr>

<h2>⚙️ Setup Instructions</h2>

<ol>
  <li>Clone the repository</li>
  
  <pre><code>git clone https://github.com/yourusername/pdf-faculty-rag-chatbot</code></pre>

  <li>Install dependencies</li>

  <pre><code>pip install -r requirements.txt</code></pre>

  <li>Run the notebook</li>

  <pre><code>jupyter notebook pdf_memory.ipynb</code></pre>
</ol>

<hr>

<h2>🧪 Example Queries</h2>

<ul>
  <li><code>Give me the short name of Ms. Imrose Jahan.</code></li>
  <li><code>What was my last question?</code></li>
  <li><code>Give me the short name of Dr Md Shariful Islam.</code></li>
</ul>

<hr>

<h2>🙌 Credits</h2>

<p>
Created by <strong>Mehadi Hassan</strong> using LangChain + FAISS + BM25 + OpenAI/Ollama.
</p>

<hr>

<p align="center">⭐ Star this repo if you find it useful for academic RAG projects!</p>
