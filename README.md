ClauseAI – Legal Risk Classifier

ClauseAI is an end-to-end AI-powered legal risk analysis system that automatically parses contracts, extracts clauses, and classifies legal risk using Large Language Models (LLMs).
The project is optimized for NVIDIA H100 GPU training using modern deep learning efficiency techniques.

Training Optimizations
BF16 mixed precision
Gradient checkpointing
Large-batch data parallelism

Performance Optimizations
~40% reduction in training time
Reduced GPU memory usage via gradient checkpointing
Higher throughput using Flash Attention 2
Stable large-batch training with BF16 precision

Project Structure
training/
└── contract_risk_analyzer_training_h100_optimized.ipynb
data/
├── raw_contracts/
└── processed_clauses/
models/
├── phi-3.5-mini/
└── qwen2.5-3b/
checkpoints/
utils/
README.md

Training Notebook
Path:
training/contract_risk_analyzer_training_h100_optimized.ipynb

Includes:
Dataset preprocessing
Model loading and fine-tuning
Training performance optimizations
Evaluation metrics
