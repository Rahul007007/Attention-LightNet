# 🧠 Attention-LightNet: A Lightweight Deep Learning Real-Time Defect Detection for Laser Sintering

[![DOI](https://img.shields.io/badge/DOI-10.3390%2Felectronics14132674-blue)](https://doi.org/10.3390/electronics14132674)  
📄 Published in *Electronics*, Volume 14, Issue 13, 2025  
🔗 [Read the full paper](https://www.mdpi.com/2079-9292/14/13/2674)

---

## 📌 Overview

**Attention-LightNet** is a lightweight, real-time deep learning model for detecting powder bed defects during Laser Sintering (LS) in Additive Manufacturing. The model integrates a compact VGG-style architecture with a soft attention mechanism to detect anomalies such as cracks, powder ditches, and voids efficiently and accurately. 

This repository includes:
- ✅ Final Jupyter Notebook with full implementation
- 🧠 VGG19-based model with integrated attention
- 📊 Evaluation results and metrics
- ⚡ Real-time suitability with low computational cost

---

## 📁 Repository Structure
├── .gitignore
├── LICENSE
├── README.md ← This file
├── sls-bed-vgg19-custom-pytorch-3cv_final.ipynb ← Final implementation notebook

To execute the full implementation:

Make sure you have Python installed (preferably version 3.8 or above).

Install Jupyter Notebook (if not already installed):

``` 
pip install notebook


Launch the notebook:

``` 
jupyter notebook sls-bed-vgg19-custom-pytorch-3cv_final.ipynb

## 📄 Citation

If you use this codebase or refer to our work, please cite the following paper:

```bibtex
@Article{electronics14132674,
  author    = {Das, Trishanu and Ali, Asfak and Kuar, Arunanshu Shekhar and Chaudhuri, Sheli Sinha and Nnamoko, Nonso},
  title     = {Attention-LightNet: A Lightweight Deep Learning Real-Time Defect Detection for Laser Sintering},
  journal   = {Electronics},
  volume    = {14},
  number    = {13},
  year      = {2025},
  article-number = {2674},
  url       = {https://www.mdpi.com/2079-9292/14/13/2674},
  issn      = {2079-9292},
  doi       = {10.3390/electronics14132674}
}
