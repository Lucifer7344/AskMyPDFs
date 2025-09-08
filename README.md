# AskMyPDFs 📄💬  

AskMyPDFs is a Python application that allows you to **chat with multiple PDF documents**.  
You can ask natural language questions about the PDFs, and the app will provide relevant responses based on their content.  

This tool is powered by **language models** and embeddings to deliver accurate and contextual answers from your documents.  

---

## 🚀 Features
- 📂 **Load multiple PDFs** at once.  
- ✂️ **Text Chunking** for better processing.  
- 🧠 **Semantic Search** using embeddings.  
- 💡 **Contextual Q&A** with relevant PDF content only.  
- 🐍 Built with **Python** for flexibility and ease of use.  

---

## ⚙️ How It Works
1. **PDF Loading** – Reads multiple PDF documents and extracts their text.  
2. **Text Chunking** – Splits extracted text into smaller, manageable chunks.  
3. **Embeddings Generation** – Converts chunks into vector representations using a language model.  
4. **Similarity Matching** – Finds the most relevant chunks based on your query.  
5. **Response Generation** – The language model generates an answer from the selected chunks.  

---

## 🛠️ Installation

1. Clone this repository:  
   ```bash
   git clone https://github.com/Lucifer7344/AskMyPDFs.git
   cd AskMyPDFs

2. Create a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate   # On macOS/Linux
   venv\Scripts\activate      # On Windows

4. Install dependencies:
   ```bash
   pip install -r requirements.txt


1. ▶️ Usage Run the app:
    ```bash
   python app.py

2. Upload your PDF files when prompted.

3. Start asking questions like:

   "What is the summary of chapter 3?"

   "List all references mentioned in the document


🤝 Contributing

   Contributions are welcome! Feel free to fork this repo, create a new branch, and submit a pull request.

📜 License

   This project is licensed under the MIT License.
