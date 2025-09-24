# Modeling the Language of Life 🧬

This repository centralizes my PhD research on using **Large Language Models (LLMs)** to study proteins and decode missense mutations.  
It is organized as a **monorepo** with multiple projects under a shared ecosystem.  

---

## 📂 Repository Structure
```
phd-repo/
├── projects/
│ ├── protein-lm/ # Pretraining and embeddings
│ ├── protein-design/ # Generative design tasks
│ ├── mutation-effects/ # Missense mutation analysis
│ └── annotation/ # Function annotation & benchmarks
├── common/ # Shared utilities (data loaders, metrics, plots)
├── data/ # Raw & processed datasets (symlink or gitignored)
├── docs/ # Notes, figures, drafts, publications
├── scripts/ # Spark jobs, preprocessing, automation
├── tests/ # Unit & integration tests
├── requirements.txt
└── README.md
```


---

## 🚀 Goals

- Train and evaluate LLMs on protein sequences  
- Model the impact of **missense mutations**  
- Explore **protein design** applications  
- Benchmark across annotation datasets  

---

## 🔧 Setup

```bash
git clone https://github.com/abidikhairi/lang2life.git
cd lang2life
conda create -n protein-llm python=3.10
pip install -r requirements.txt
```
---

## 🧩 Projects

- protein-lm → pretraining + embeddings
- protein-design → generation experiments
- mutation-effects → mutation prediction & analysis
- annotation → benchmarking functional annotation

---
## 📖 Documentation

See `docs/` for research notes, figures, and paper drafts.
