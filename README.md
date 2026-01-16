# CIFAR-10 Image Classification

This repository contains **CIFAR-10 image classification models** built across **4 difficulty levels**, starting from a baseline transfer learning model to **expert-level ensemble learning**.
Target: **High accuracy + clean code + proper analysis + reproducible setup**


We train deep learning classifiers on the **CIFAR-10 dataset** (10 classes) using progressively advanced techniques:

- **Level 1:** Transfer Learning Baseline (ResNet50)
- **Level 2:** Augmentation + Regularization + Fine-tuning + Ablation Study
- **Level 3:** Custom Architecture (Attention/SE blocks + Grad-CAM + per-class analysis)
- **Level 4:** Expert Ensemble (multiple models + soft voting + research-quality report)

Each level has:
- a separate notebook/code folder
- trained model checkpoint(s)
- plots + results saved to `results/`

---

## Repository Structure
- level_1_code.ipynb
- level_2_code.ipynb
- level_3_code.ipynb
- models/
- results/
- requirements.txt
- README.md
