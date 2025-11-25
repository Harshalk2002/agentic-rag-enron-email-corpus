# Agentic RAG – Enron Email Mini Project

This project demonstrates a simple Agentic Retrieval-Augmented Generation (RAG) workflow built on a small synthetic Enron-style email dataset.

The system shows how an agent can combine:
- Semantic retrieval using FAISS
- Summarization tool
- Tone/Sentiment analysis tool
- OpenAI function-calling for agentic reasoning

to generate accurate and grounded answers.

---

## ✅ Features
- Synthetic Enron-style dataset (10 emails)
- Embeddings using `text-embedding-3-small`
- FAISS vector index for retrieval
- Tools:
  - **RAG Search Tool**
  - **Summarizer Tool**
  - **Sentiment Analyzer**
- Agentic controller using OpenAI function-calling
- Evaluation on 3 tasks:
  1. Who is leading a project?
  2. Legal & regulatory issues
  3. Tone around accounting & risk

---

## 📁 Project Files
```
Assignment3.ipynb
agentic_rag_enron_report.pdf
agentic_rag_enron_report_with_image.pdf
agentic_rag_architecture.png
data/email_subset.csv
data/email_subset.jsonl
results/enron_rag_evaluation_synthetic.json
```

---

## ▶️ How to Run
1. Install dependencies:
```
pip install openai faiss-cpu pandas python-dotenv langchain tqdm
```

2. Open the notebook:
```
jupyter notebook Assignment3.ipynb
```

3. Run all cells to build the dataset, create the index, and execute the evaluation.

---

## ⚠️ API Key Reminder
Do NOT upload your API key to GitHub.
Use a `.env` file if needed.

---

## 📜 License
MIT License
