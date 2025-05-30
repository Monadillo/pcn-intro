# pcn-intro
**Introduction to Predictive Coding Networks for Machine Learning**


Welcome! This repository contains supplementary materials for the manuscript *Introduction to Predictive Coding Networks for Machine Learning* (arXiv link TBA).

---

## What’s Included

- A copy of the manuscript: [`pcn_intro.pdf`](./pcn_intro.pdf)
- A Google Colab-ready Python notebook: [`pcn_cifar10_notebook.ipynb`](./pcn_cifar10_notebook.ipynb)  
- Trained model weights from the CIFAR-10 experiment: [`pcn_model_statedict.pth`](./pcn_model_statedict.pth)  
- A clean and readable implementation of predictive coding networks (PCNs)
- Instructions inside the notebook for loading weights and running inference/training

---

## Highlights

From the manuscript abstract:

> *Predictive coding networks (PCNs) constitute a biologically inspired framework for understanding hierarchical computation in the brain, and offer an alternative to traditional feedforward neural networks in ML. This note serves as a quick, onboarding introduction to PCNs for machine learning practitioners. We cover the foundational network architecture, inference and learning update rules, and algorithmic implementation. A concrete image-classification task (CIFAR-10) is provided as a benchmark-smashing application...*

🚀 **New benchmark achieved**:
With just 4 minutes of training, the PCN model sets a new state-of-the-art accuracy on CIFAR-10 — **99.92%**, meaning only 8 misclassifications out of 10,000 test images.

---

## 🌱 What’s Next? Community Exploration

This repo is just a starting point. We invite the broader machine learning and neuroscience-inspired AI community — hobbyists and professionals alike — to further **explore the capabilities of PCNs** across new datasets, tasks and architectural variations. 

We’re planning a follow-up repository:
👉 [`pcn-project`](https://github.com/monadillo/pcn-project) — a space for community-driven research and benchmarking of PCNs.

If you're interested in contributing and experimenting — stay tuned and reach out via [Discussions](https://github.com/monadillo/pcn-project/discussions) or *repo owner* at pm dot me.

---

## 📎 How to Use This Repo

1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Follow the in-notebook instructions to load the model and reproduce results
3. (Optional) Run training or inference on your own system or dataset

---

## 📜 License

[MIT License](./LICENSE) — open to use, reproduce, and modify with attribution.

---

## 🤝 Contributions

This repo is kept simple and focused, but please check out [`pcn-project`](https://github.com/monadillo/pcn-project) for more experimental and collaborative work on PCNs.
