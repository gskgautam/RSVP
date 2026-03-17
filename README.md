# RSVP-HHH

RSVP-HHH is a unified benchmark framework for evaluating Large Language Models (LLMs) under the **Helpfulness, Harmlessness, and Honesty (HHH)** paradigm across multiple alignment dimensions.

---

## 🔍 Overview

Traditional alignment benchmarks evaluate models along **single dimensions** (e.g., safety or reasoning). However, real-world alignment requires models to satisfy **multiple objectives simultaneously**.

RSVP-HHH introduces:
- A **unified HHH evaluation framework**
- A curated dataset: **RSVP-X**
- A systematic benchmark for **multi-dimensional alignment**

> Unified HHH optimization improves alignment by **~11%–14%**. :contentReference[oaicite:0]{index=0}

---

## 📦 Dataset: RSVP-X

- **9,228 samples**
- **106 domains** across four dimensions:
  - 🧠 Reasoning (14)
  - 🛡️ Safety (14)
  - ⚖️ Value (56)
  - 🌍 Pluralistic (22)

Each sample includes:
- Prompt
- HHH-aligned response ✅
- Domain label

---

## ⚙️ Pipeline

### Stage I: Dataset Construction

**Module I: Query Construction**
- Domain classification using Mistral-7B
- Expansion of low-resource domains via Llama-3.1
- Deduplication using SimHash

**Module II: Response Generation**
- Responses generated using GPT-4.1
- Two-stage rejection sampling:
  - Candidate filtering (HHH scoring)
  - Feedback-guided resampling

---

### Stage II: Benchmarking

- Zero-shot evaluation of models on RSVP-X
- Model categories:
  - General-purpose aligned (e.g., TrinityX, AlignX)
  - Dimension-specific models (reasoning/safety/value/pluralism)
  - Open-weight LLMs (Qwen, DeepSeek)

---

## 📊 Metrics

- **Helpfulness (WR ↑)** – Win Rate
- **Harmlessness (SS ↓)** – Safety Score
- **Honesty (TI ↑)** – Truthfulness × Informativeness
- **Average Score (↑)**:
  \[
  \text{Avg} = \frac{\text{Helpfulness} + \text{Honesty} - \text{Harmlessness}}{3}
  \]

---

## 📈 Key Findings

- Joint HHH optimization significantly improves performance (+11–14%)
- **TrinityX > AlignX** (46.6% vs 45.0%)
- **DeepSeek > Qwen** among open-weight models
- **GPT-4.1 achieves best performance (~51.37%)**
- Dimension-specific models fail under joint evaluation


If you use this work, please cite the paper.
