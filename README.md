# 🧠 Emotion-Aware NPC Dialogue System

## Overview

This repository contains the **code and experimental results** for a **multilingual emotion-aware non-player character (NPC) dialogue system**, developed and submitted as a **regular paper** to **IEEE SoutheastCon 2026** under the **AI and Predictive Modeling** track.

The system integrates **emotion classification**, **multilingual translation**, and **empathetic response generation** to enable NPCs to react emotionally and contextually to user input across multiple languages and expression types (literal vs. idiomatic).

---

## Key Contributions

* 🌍 **Multilingual pipeline** supporting English, Persian, French, and Arabic
* 🧠 **Emotion detection** over core affective categories (e.g., sadness, joy, anger)
* 🗣️ **Emotion-aware response engine** for NPC dialogue generation
* 📊 **Quantitative evaluation** across language and expression types
* ⏱️ **Latency analysis** of translation and model inference stages

---

## Methodology Summary

1. **Input Processing**

   * Accepts user text in multiple languages
   * Detects whether the expression is literal or idiomatic

2. **Translation Layer**

   * Non-English inputs are translated into English for unified processing

3. **Emotion Classification**

   * Transformer-based emotion detection model
   * Outputs predicted emotion and confidence score

4. **NPC Response Generation**

   * Emotion-aligned, empathetic dialogue responses
   * Rule-based response mapping for interpretability

5. **Evaluation**

   * Accuracy by language and expression type
   * Error and failure analysis
   * Latency breakdown of pipeline components

---

## Experiments & Results

All experiments, plots, and tables reported in the paper are generated in:

📓 **`Southeast.ipynb`**

This notebook includes:

* Accuracy comparisons by language
* Accuracy comparisons by expression type
* Confidence score distributions
* Latency analysis (translation vs. inference)
* Misclassification case studies

Figures in the notebook directly correspond to those referenced in the paper.

---

## How to Run

### 1. Install dependencies

```bash
pip install -r requirements.txt
```

### 2. Run the main system

```bash
python southeast.py
```

### 3. Reproduce experiments

Open and run:

```bash
Southeast.ipynb
```

---

## Reproducibility

* All experiments are deterministic given fixed random seeds
* No proprietary datasets are required
* Translation and emotion inference rely on publicly available models

This repository is provided to support **transparent review**, **replication**, and **future research**.

---

## Paper Information

* **Conference:** IEEE SoutheastCon 2026
* **Track:** AI and Predictive Modeling
* **Paper Type:** Regular Paper (up to 6 pages)
* **Status:** Submitted

---

## Author

**Zeinab Tehrani**
Undergraduate Researcher
Multilingual AI & Human-Centered Computing
