ClauseAI – Legal Risk Classifier

ClauseAI is an end-to-end AI-powered legal risk analysis system that automatically parses contracts, extracts clauses, and classifies legal risk using Large Language Models (LLMs).
The project is optimized for NVIDIA H100 GPU training using modern deep learning efficiency techniques.

🚀 Features

📄 Contract Parsing – Ingests legal documents and preprocesses them for analysis

🧠 Clause Extraction – Identifies and segments contractual clauses

⚖️ Risk Classification – Classifies clauses into risk categories using LLMs

⚡ High-Performance Training – Optimized for NVIDIA H100 GPUs

🔄 Robust Training Pipeline – Automated checkpointing and recovery

🧠 Models Used

Phi-3.5-Mini

Qwen2.5-3B

Both models are fine-tuned for legal text understanding and risk classification.

🛠 Tech Stack

Programming Language: Python

Frameworks: PyTorch, HuggingFace Transformers

Training Optimizations

Flash Attention 2

BF16 mixed precision

Gradient checkpointing

Large-batch data parallelism

Hardware: NVIDIA H100 GPUs

⚡ Performance Optimizations

~40% reduction in training time

Reduced memory footprint via gradient checkpointing

Improved throughput using Flash Attention 2

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

The main training workflow is implemented in:

training/contract_risk_analyzer_training_h100_optimized.ipynb

Includes:

Dataset preprocessing

Model loading and fine-tuning

Performance optimizations

Automated checkpointing

Evaluation metrics

📊 Use Cases

Legal contract review automation

Compliance and risk assessment

Enterprise document intelligence

AI-assisted legal workflows

🔮 Future Improvements

Multi-risk classification per clause

Retrieval-Augmented Generation (RAG) for legal references

Web-based contract upload and analysis dashboard

Explainability layer for risk predictions
