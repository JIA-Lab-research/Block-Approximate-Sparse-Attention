# 🚀 BA-Att: Block Approximate Sparse Attention

> Efficient Long-Context Modeling in Diffusion Language Models  
> 📄 CVPR 2026 (Findings)

<!-- [![Paper](https://img.shields.io/badge/Paper-PDF-red)](./assets/paper.pdf)
[![Project Page](https://img.shields.io/badge/Project-Coming_Soon-blue)]() -->

---

## 🔥 Highlights

- 🚀 Up to **6.95× speedup** over FlashAttention  
- ⚡ Training-free sparse attention (no finetuning required)  
- 🧠 Maintains near full-attention performance at **50% sparsity**  
- 🎥 Strong generalization across language, multimodal, and video generation  

---

## 📌 Overview

We propose **Block Approximate Sparse Attention (BA-Att)**, a training-free block-sparse attention framework for **Diffusion Language Models (DLMs)**.

Unlike prior works relying on fixed patterns, BA-Att:

- Performs **selection in downsampled space**
- Uses **norm-based ranking** to reduce approximation error
- Applies **covariance compensation** for accuracy recovery

---

## 🧠 Method

### 🔹 Framework Overview


<div align="center">
  <img src="assets/framework.pdf" width="100%">
</div>


## 📦 Code

🚧 **Code is coming soon!**

We are currently cleaning and organizing the codebase.


<!-- ---

## 🧾 Citation

```bibtex
@inproceedings{baatt2026,
  title={Efficient Long-Context Modeling in Diffusion Language Models via Block Approximate Sparse Attention},
  author={Zhang, Wenhu and Wu, Yiming and Wang, Huanyu and others},
  booktitle={CVPR},
  year={2026}
} -->