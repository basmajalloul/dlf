# Acute Gait Adaptation Index (AGAI)

Official implementation of the AGAI framework for short-term motor adaptation analysis using a hybrid AI pipeline. This repository includes all experimental notebooks, processed results, and supplementary materials from the ICONIP 2025 submission:  
**"Quantifying Motor Adaptation: A Hybrid AI Approach for Interpreting Short-Term Gait Variability."**

## 📖 Overview
- Composite metric (AGAI) integrating Autoencoder anomaly scores, Transformer forecasting deviations, and DTW-based trajectory drift.
- LLM-based interpretability layer for generating subject-level motor adaptation summaries.
- Ablation and comparative studies against classical metrics (e.g., standard deviation, entropy).

## 📂 Repository Structure
- `data/`: Processed gait feature data and AGAI results.
- `Notebooks/`: Jupyter notebooks for model training, AGAI computation, clustering, and visualization.
- `Supplementary/`: Mathematical formulations, LLM prompt templates, and figure exports.
- `LICENSE`: Licensing information.

## 🚀 Quick Start

Install dependencies:
```bash
pip install -r requirements.txt

```

Explore the notebooks in the `Notebooks/` directory for step-by-step experiments.

## 📄 License
This project is licensed under the MIT License.
