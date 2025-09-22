📘 Question Answering with Transformers

📌 Task Description

This project implements Question Answering (QA) using Transformer-based models fine-tuned on the SQuAD v1.1 dataset.
The system takes a context passage and a question as input, and extracts the correct answer span using pre-trained models (e.g., DistilBERT, RoBERTa).

⸻

🚀 Features
 • ✅ Load SQuAD v1.1 dataset (Stanford Question Answering Dataset).
 • ✅ Use Hugging Face Transformers for QA.
 • ✅ Pre-trained model: distilbert-base-uncased-distilled-squad.
 • ✅ Evaluation with Exact Match (EM) and F1 Score.
 • ✅ Bonus: Test alternative models like RoBERTa.
 • ✅ Simple Streamlit web interface to ask questions interactively.

⸻

🛠️ Tools & Libraries
 • Transformers (https://huggingface.co/transformers/)
 • Datasets (https://huggingface.co/docs/datasets/)
 • Evaluate (https://huggingface.co/docs/evaluate/)
 • Streamlit (https://streamlit.io/)
 • Pandas (https://pandas.pydata.org/)
 ⸻

📊 Evaluation Results

On a subset of 200 validation samples from SQuAD v1.1 using DistilBERT:
 • Exact Match (EM): ~85%
 • F1 Score: ~89.4
