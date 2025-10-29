# Gradient-Based Diffeomorphic Segmentation

[![arXiv](https://img.shields.io/badge/arXiv-2506.09357-b31b1b.svg)](https://arxiv.org/abs/2506.09357)

Implementation demo for the paper:  
**"A new approach for image segmentation based on diffeomorphic registration and gradient fields"**  
by **Junchao Zhou**, [arXiv:2506.09357](https://arxiv.org/abs/2506.09357).

---

## Overview
This demo presents a mathematical, non–deep learning segmentation approach that combines  
**diffeomorphic registration (LDDMM)** with a **gradient-based varifold loss**.  
An initial ellipse evolves smoothly toward object boundaries.

---

Input: grayscale medical image (`.png`, `.tif`, etc.)  
Output: evolving contour approaching the target boundary.

---

> Demo version. Some functions may be omitted.
