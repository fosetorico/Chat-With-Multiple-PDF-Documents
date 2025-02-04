# Research Bot for PDF-Based Data Summarization and Insight Extraction
#### Link: https://huggingface.co/spaces/valleeneutral/multi-PDF_chatBot

This project is an AI-powered chatbot designed to summarize, analyze, and extract insights from multiple PDF documents. It leverages Google Gemini AI, FAISS vector storage, and Google Generative AI embeddings to provide accurate, context-aware responses based on document content.

## Features
1. Multi-PDF Chat Support – Query multiple documents in one session.
2. Google Gemini AI – Generates intelligent, human-like responses.
3. FAISS Vector Storage – Efficient document chunk retrieval.
4. Google Generative AI Embeddings – Enhances contextual understanding.

## Steps to run this Project

#### Clone the repository
```
git clone https://github.com/fosetorico/Chat-With-Multiple-PDF-Documents.git
```

#### Create a conda environment after opening the repository
```
conda create -n your-chosen-name python=3.10 -y
```

```
conda activate your-chosen-name
```

#### install the requirements
```
pip install -r requirements.txt
```

#### Finally run the following command
```
streamlit run app.py
```