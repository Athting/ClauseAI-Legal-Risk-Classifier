<div align="center">
ClauseAI – Legal Risk Classifier

AI-powered contract risk analysis using Large Language Models (LLMs)
Optimized for NVIDIA H100 GPU training

</div>
📌 Overview

ClauseAI is an end-to-end legal risk analysis system that automatically parses contracts, extracts clauses, and classifies legal risk using state-of-the-art LLMs.
The project focuses on high-performance training, scalability, and robustness for real-world legal workflows.

🚀 Features

📄 Contract Parsing
Ingests legal documents and preprocesses them for downstream analysis

🧠 Clause Extraction
Identifies and segments individual contractual clauses

⚖️ Risk Classification
Assigns risk categories to clauses using LLM-based classifiers

⚡ High-Performance Training
Optimized for NVIDIA H100 GPUs

🔄 Robust Training Pipeline
Automated checkpointing and fault recovery

🧠 Models Used
Model Name	Purpose
Phi-3.5-Mini	Lightweight LLM for efficient legal understanding
Qwen2.5-3B	Higher-capacity model for robust risk classification

Both models are fine-tuned specifically for legal text understanding and risk prediction.

🛠 Tech Stack
Category	Details
Language	Python
Frameworks	PyTorch, HuggingFace Transformers
Hardware	NVIDIA H100 GPUs
Training Optimizations

Flash Attention 2

BF16 mixed precision

Gradient checkpointing

Large-batch data parallelism

⚡ Performance Optimizations

~40% reduction in training time

Reduced GPU memory usage via gradient checkpointing

Higher throughput using Flash Attention 2

Stable large-batch training with BF16 precision

📂 Project Structure
├── training/
│   └── contract_risk_analyzer_training_h100_optimized.ipynb
├── data/
│   ├── raw_contracts/
│   └── processed_clauses/
├── models/
│   ├── phi-3.5-mini/
│   └── qwen2.5-3b/
├── checkpoints/
├── utils/
└── README.md

🧪 Training Notebook

Path:
training/contract_risk_analyzer_training_h100_optimized.ipynb

Includes:

Dataset preprocessing

Model loading and fine-tuning

Training performance optimizations

Automated checkpointing

Evaluation metrics

📊 Use Cases

Legal contract review automation

Compliance and regulatory risk assessment

Enterprise document intelligence systems

AI-assisted legal decision support

🔮 Future Improvements

Multi-risk classification per clause

Retrieval-Augmented Generation (RAG) for legal references

Web-based contract upload and analysis dashboard

Explainability layer for risk predictions

<div align="center">

Built for scalable, high-performance legal AI systems

</div>
