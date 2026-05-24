# llm-code-finetuning-lora
🚀 Fine-Tuning Mistral-7B for Python Code Generation using QLoRA

Fine-tuned the Mistral-7B large language model to generate Python code from 
natural language instructions using QLoRA (Quantized Low-Rank Adaptation) — 
entirely on a free Google Colab T4 GPU.

Trained on 18,000+ Python coding examples from the Alpaca dataset. Uses 4-bit 
quantization to reduce model memory from 28GB to 6GB, and LoRA adapters to train 
only 0.58% of parameters (42M out of 7.2B). Fine-tuned model is published on 
HuggingFace Hub.

🛠️ Tech Stack: Python · Mistral-7B · QLoRA · PEFT · bitsandbytes · 
HuggingFace Transformers · TRL · Weights & Biases

🤗 Model: huggingface.co/navnani12/mistral-code-lora
