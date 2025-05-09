# 🧠 LLM-Custom-Training

This repository provides a full toolkit for fine-tuning and evaluating Large Language Models (LLMs) using structured prompt datasets. It includes training-ready data formats, configuration files, Jupyter notebooks, and utility scripts — ideal for custom instruction tuning, low-rank adaptation (LoRA), or benchmarking LLMs.

---

## 🚀 Use Cases
- Fine-tune open models like LLaMA, Mistral, GPT-J, or Falcon
- Build instruction-following models with custom prompts
- Analyze prompt performance (zero-shot vs. few-shot)
- Perform evaluation and token usage diagnostics

---

## 🗂 Folder Structure

```
LLM-Custom-Training/
├── datasets/           # JSONL training + evaluation data
├── configs/            # HuggingFace-style fine-tuning configs
├── notebooks/          # Jupyter notebooks for data prep & training
├── scripts/            # Utilities (e.g., token counters)
├── metadata/           # Data source & usage disclaimers
├── README.md
├── LICENSE
```

---

## 📁 Key Components

### ✅ `datasets/`
- `train.jsonl` – Sample prompt-completion pairs
- `eval.jsonl` – Test examples for evaluation
- `data_schema.md` – JSONL structure and best practices

### ⚙️ `configs/`
- `finetune_config.json` – Example training config for HuggingFace's `Trainer`

### 📓 `notebooks/`
- `explore_dataset.ipynb` – Visualize and clean your dataset
- `prepare_prompts.ipynb` – Format raw text into prompt/completion
- `run_training.ipynb` – Launch fine-tuning jobs
- `evaluate_outputs.ipynb` – Check model responses and metrics

### 🧮 `scripts/`
- `tokenizer_count.py` – Counts token usage in your dataset

### 🧾 `metadata/`
- `data_source.md` – Document where your data came from
- `disclaimer.md` – Legal/ethical disclaimer for synthetic content

---

## ✅ Requirements

- Python 3.8+
- HuggingFace `transformers`
- `datasets`, `evaluate`, `openai`, or `trl` (optional)
- Jupyter or VS Code (recommended)

---

## 📜 License
This project is licensed under the MIT License. See `LICENSE` for details.
