# 🧠 LLM Prompt Engineering Library

A curated repository of high-quality prompts, templates, and workflows for training, testing, and evaluating Large Language Models (LLMs).

Built by Eva Paunova, this repo serves as a living collection of:
- 💡 Prompt design strategies
- 🔍 Evaluation rubrics and examples
- 📊 Structured prompt datasets
- 🔧 Scripts for formatting and fine-tuning
- 📘 Templates for real-world applications (product management, education, classification, reasoning, etc.)

---

## 📁 Repository Structure

```
llm-prompt-engineering/
│
├── prompts/                # Prompt libraries by category and use case
│   ├── product_management_prompts.csv
│   ├── prompt_engineering_basic.csv
│   ├── prompt_engineering_advanced.csv
│
├── templates/              # Meta-prompt scaffolds, system instructions
│   └── evaluation_rubric.md
│
├── notebooks/              # Testbed notebooks for prompt output analysis
│   └── prompt_testing.ipynb
│
├── datasets/               # Training/evaluation datasets (optional)
│
├── scripts/                # Automation scripts for prompt formatting, export
│   └── convert_to_finetune_json.py
│
└── README.md               # This file
```

---

## 🔍 Prompt Libraries

### ✅ Product Management
Prompts to simulate daily workflows of a PM:
- User research synthesis
- Roadmap prioritization (RICE, Kano, OKRs)
- PRD writing, backlog grooming, sprint planning
- Stakeholder communication and go-to-market strategy

### 🛠 Prompt Engineering (Basic + Advanced)
- Few-shot, chain-of-thought, zero-shot, multi-turn design
- Meta-prompts and evaluation scaffolds
- Token efficiency optimization
- Bias reduction, multilingual prompting, rubric design

---

## 🤖 Ideal For

- LLM trainers, researchers, and applied ML teams
- Prompt engineers working on RAG, agents, or fine-tuning
- Technical PMs and AI product builders
- OpenAI/Anthropic/Claude/LLaMA model testers

---

## 🚀 Getting Started

1. Clone this repo
2. Open any prompt CSV in `/prompts`
3. Load it into your LLM playground or use the scripts to convert to OpenAI fine-tune format
4. Use `/notebooks` to run evaluations, score responses, or visualize token costs

---

## 📜 License

MIT License

---

## ✨ Contributions Welcome

Want to add your own prompt library or prompt evaluation tool? See [`CONTRIBUTING.md`](./CONTRIBUTING.md)

---
