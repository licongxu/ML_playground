# ML Playground 🧠📊

This repository is a **hands-on playground for Machine Learning**, designed to build intuition and practical understanding of modern ML models.

The emphasis is on **learning by doing**: concise explanations paired with runnable notebooks, rather than polished libraries or frameworks.

---

## What This Repository Is For

This project is intended for:
- Learning core Machine Learning concepts through experiments
- Understanding how different model families behave in practice
- Comparing classical models with neural approaches
- Gaining experience with real ML tooling used in research and competitions

The content prioritizes clarity and experimentation over completeness.

---

## Core Model Families Covered

### Tree-Based Models
Tree-based models are among the strongest baselines for **tabular data**.

Topics covered include:
- Decision trees and ensemble methods
- Gradient boosting intuition
- Practical training with XGBoost and LightGBM
- GPU-accelerated training
- Overfitting control and regularization
- Feature importance and model interpretation

These models are widely used in Kaggle competitions and real-world ML systems due to their robustness and performance.

---

### Neural Networks (MLP)
Multi-Layer Perceptrons represent the simplest form of neural networks.

Covered ideas:
- Forward and backward propagation
- Loss functions and optimization
- Regression vs classification
- When neural networks outperform tree-based models (and when they do not)

---

### Transformers
Transformers extend beyond NLP and are increasingly used in:
- Time series
- Tabular modeling
- Scientific data analysis

The notebooks focus on:
- Attention mechanisms
- Model scaling behavior
- Conceptual understanding rather than large-scale training

---

## Hyperparameter Tuning

Good performance often comes from **tuning, not model complexity**.

Topics explored:
- Manual tuning and heuristics
- Grid and random search
- Sensitivity to learning rate, depth, and regularization
- Practical strategies used in competitions

---

## Tools and Libraries

The tutorials make use of standard Python ML tooling:
- NumPy, Pandas, SciPy
- XGBoost, LightGBM, CatBoost
- Statsmodels for classical baselines
- Matplotlib and Plotly for visualization

GPU acceleration is used where available.

---

## Learning Philosophy

This repository follows a few guiding principles:
- Start with strong baselines
- Prefer simple models before complex ones
- Always validate with held-out data
- Inspect model behavior, not just metrics

Understanding *why* a model works is treated as equally important as performance.

---

## Intended Audience

This repository is suitable for:
- Students learning Machine Learning
- Researchers moving from theory to applied ML
- Practitioners comparing model families
- Anyone building intuition for real-world ML systems

---

## Future Directions

Planned extensions include:
- Deeper CatBoost examples
- Model comparison on a shared dataset
- CPU vs GPU performance benchmarks
- Better visualization of model internals

---

Maintained by **Licong Xu**
