# T3DPS

# Text-based Three-dimensional Geometric Person Retrieval

[![Paper](https://img.shields.io/badge/Paper-EAAI-blue)](#citation)
[![License](https://img.shields.io/badge/License-MIT-green)](#license)
[![Python](https://img.shields.io/badge/Python-3.9%2B-blue)](#installation)

Official implementation of **Text-based Three-dimensional Geometric Person Retrieval** (Engineering Applications of Artificial Intelligence, EAAI).

> 🚧 This repository is under active maintenance. Code/models will be released progressively.

---

## Highlights
- **Text-to-3D retrieval** for person search using geometric 3D cues.
- [Feature 1] e.g., robust cross-modal alignment with contrastive learning.
- [Feature 2] e.g., efficient 3D representation / point cloud / mesh encoder.
- Reproducible training and evaluation scripts.

---

## News
- **2026-02-18**: Repository initialized.
- [Add your milestones here.]

---

## Method Overview
<p align="center">
  <img src="t_3dps.png" width="85%">
</p>

**Pipeline**: Given a textual description, the model retrieves the corresponding 3D person geometry (and optionally multi-view images) from a gallery.

> Put your method figure in `assets/teaser.png`.

---

## Environment
- OS: Linux/macOS/Windows
- Python: 3.9+
- PyTorch: 2.x
- CUDA: 11.x (optional, recommended)

---

## Installation
```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>

# (Recommended) create env
conda create -n t3dpr python=3.10 -y
conda activate t3dpr

# install deps
pip install -r requirements.txt
