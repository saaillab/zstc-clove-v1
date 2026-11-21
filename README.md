[![Project Page](https://img.shields.io/badge/Project%20Page-Live-2563eb)](https://saaillab.github.io/zstc-clove-v1/) [![SAAIL Lab](https://img.shields.io/badge/SAAIL%20Lab-AI4EAC%202026-0f172a)](https://saaillab.github.io/papers/zstc-clove-v1/)

# Deep Learning for Automated Clove Quality Grading: A Feasibility Study

[![AI4EAC 2026](https://img.shields.io/badge/AI4EAC-2026-orange)](https://sti.easteco.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

**Authors:** Patrick Vincent Ndowo, Innocent Nyalala  
**Affiliation:** SAAIL Lab, IIT Madras Zanzibar Campus, Tanzania  
**Venue:** AI for East Africa Conference (AI4EAC 2026), Kigali, Rwanda

---

## Abstract

We investigate the technical feasibility of automated clove quality grading using deep learning on ZSTC-Clove-V1, a novel dataset of 5,298 single-clove images across four official commercial grades collected at the Zanzibar State Trading Corporation. ResNet18 achieves 94.46% accuracy, while VGG16 fails to converge at 31.32%, demonstrating the architectural sensitivity of specialized agricultural datasets. The paper argues that accuracy alone is insufficient; interpretable and trustworthy AI is essential for responsible deployment in East African agriculture.

---

## Key Results

| Model | Accuracy | Precision | Recall | F1-Score |
|---|---|---|---|---|
| ResNet18 | 94.46% | 94.39% | 94.34% | 94.33% |
| VGG16 | 31.32% | 9.81% | 31.32% | 14.94% |

---

## Dataset

ZSTC-Clove-V1 contains 5,298 high-resolution single-clove images across four official ZSTC grades, collected at the Saateni warehouse, Unguja, Zanzibar.

> Dataset download link coming soon via Zenodo.

---

## Repository Structure

```
zstc-clove-v1/
├── data/                  # Dataset placeholder
├── src/
│   ├── train.py           # Training script
│   ├── evaluate.py        # Evaluation and metrics
│   └── models/            # Model definitions
├── notebooks/
├── requirements.txt
└── README.md
```

## Setup

```bash
git clone https://github.com/saaillab/zstc-clove-v1
cd zstc-clove-v1
pip install -r requirements.txt
```

---

## Citation

```bibtex
@inproceedings{vincent2026deeplearning,
  title={Deep Learning for Automated Clove Quality Grading: A Feasibility Study Using CNN Architectures on a Novel Zanzibar Dataset},
  author={Vincent Ndowo, Patrick and Nyalala, Innocent},
  booktitle={AI for East Africa Conference (AI4EAC)},
  address={Kigali, Rwanda},
  year={2026}
}
```

---

## About SAAIL Lab

SAAIL Lab (Sustainable AI for Agriculture and Intelligent Livelihoods) is based at IIT Madras Zanzibar Campus, Tanzania. We build responsible, locally grounded AI solutions for East Africa and the Global South.

🌍 [saaillab.github.io](https://saaillab.github.io)
