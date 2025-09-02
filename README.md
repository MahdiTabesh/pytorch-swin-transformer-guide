# Swin Transformer

This repo demonstrates the core ideas from **“Swin Transformer: Hierarchical Vision Transformer using Shifted Windows.”**  
It shows how the architecture works and how to run a quick image-classification demo.

## What’s inside
- `Swin_Tutorial.ipynb` — tutorial notebook with:
  - A brief walkthrough of shifted windows & hierarchical features
  - **Part 1:** simple from-scratch blocks to illustrate the mechanics
  - **Part 2:** inference with a pretrained Swin model (Hugging Face)

## Quick start
```bash
pip install torch torchvision einops transformers pillow matplotlib
jupyter notebook Swin_Tutorial.ipynb
