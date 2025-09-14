# GANimated

**GANimated** is a project where I build a Generative Adversarial Network (GAN) from scratch, focusing on learning, research paper implementation, and hands-on exploration of deep generative models. The aim is to implement a complete GAN pipeline using PyTorch, working with real image datasets, and understanding both the theoretical and practical aspects of GANs.

## Overview

This project:
- Demonstrates the construction of a GAN for generating cartoon face images.
- Covers dataset loading, preprocessing, model architecture (Generator and Discriminator), and training utilities.
- Uses the [Cartoon Faces - Google's Cartoon Set](https://www.kaggle.com/datasets/brendanartley/cartoon-faces-googles-cartoon-set) for experimentation.

## Features

- **Data Handling:** Automated downloading and extraction of the cartoon faces dataset.
- **Preprocessing:** Flexible image resizing, normalization, and batch loading.
- **Model Architecture:** Deep convolutional GANs with modular PyTorch code for both generator and discriminator.
- **Device Agnostic:** Code automatically leverages GPU if available.
- **Visualization:** Utility functions for inspecting dataset batches and generated images.

## Learning Resources

This implementation is based on my self-study, referencing multiple YouTube tutorials and academic research papers on GANs. The goal was to learn by doing and to replicate foundational GAN architectures as described in seminal papers like ["Generative Adversarial Nets" by Goodfellow et al. (2014)](https://arxiv.org/abs/1406.2661).

## Getting Started

### Requirements

- Python 3.7+
- PyTorch
- torchvision
- matplotlib
- kagglehub (for dataset download, or manual download)
- Google Colab or a machine with CUDA GPU recommended


## Acknowledgements

- **YouTube Tutorials:** I have referred to various YouTube videos explaining GANs, their architectures, and practical coding tips.
- **Research Papers:** Key ideas and implementations follow the original GAN paper and subsequent improvements in the literature.
- **Dataset:** [Google's Cartoon Faces Dataset](https://www.kaggle.com/datasets/brendanartley/cartoon-faces-googles-cartoon-set)

---

*This project is for educational purposes and self-learning, aiming to deepen understanding of GANs and generative deep learning.*
