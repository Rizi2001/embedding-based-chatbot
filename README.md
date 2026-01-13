# 💬 Embedding-Based Chatbot (Gecko@001)

An **embedding-driven chatbot** built using **Google’s TextEmbedding Gecko@001 model**, designed for semantic search, confidence-aware responses, and continuous improvement.

## 🚀 Highlights

- Semantic similarity-based QA using embeddings
- Confidence-aware response handling
- Related question suggestions for low-confidence queries
- Evaluation pipeline with accuracy scoring

## 🧠 What This Project Demonstrates

- Practical use of embedding models in chat systems
- Designing confidence thresholds in NLP systems
- Evaluation of chatbot performance using synthetic queries
- Continuous learning via dataset updates

## 🛠️ Tech Stack

- Python  
- Flask  
- Google Text Embeddings (Gecko@001)  
- Cosine Similarity  
- CSV-based embedding store

## 🔍 Core Functionality

- Uses a CSV file containing:
  - Questions  
  - Answers  
  - Precomputed embeddings  

- User queries are embedded and compared using cosine similarity
- Logs user interactions for analysis and improvement
- Suggests related questions when confidence score is low

## 🧪 Evaluation & Improvement

- Automatic generation of test question variations
- Comparison against ground-truth answers
- Accuracy scoring for chatbot responses
- Incremental embedding dataset updates for unanswered queries


## ⚙️ How to Run

Install dependencies:
```bash
pip install -r requirements.txt
```

Run Flask server:
```bash
python app.py
```


---

```md
## 📌 Use Cases

- FAQ automation
- Internal knowledge bases
- Customer support chatbots
- Semantic search systems


