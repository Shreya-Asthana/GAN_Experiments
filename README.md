# GAN Experiments with MNIST and Anime Face Dataset 🎨🧠

This repository contains experiments with Generative Adversarial Networks (GANs) on two datasets: **MNIST** and **Anime Face**. It includes both basic and progressively improved models with clear separation in folders.

---

## 📁 Repository Structure

├── MNIST/\
│ ├── GAN_MNIST.ipynb # Basic GAN on MNIST\
│ └── GNN_CNN_GAN_MNIST.ipynb # GAN with GNN + CNN enhancement\
│\
├── AnimeFace/\
│ ├── DCGAN_Animeface.ipynb # Initial DCGAN for anime face generation\
│ └── DCGAN_Animeface_Improved.ipynb # Improved DCGAN with deeper architecture\

---
## 🔍 Project Overview

### MNIST
- **GAN_MNIST.ipynb**: Implements a basic GAN to generate handwritten digits from the MNIST dataset.
- **GNN_CNN_GAN_MNIST.ipynb**: Introduces a hybrid architecture combining Graph Neural Networks (GNNs) and CNNs into the GAN framework to explore structure-aware generation.

### Anime Face
- **DCGAN_Animeface.ipynb**: Implements a standard DCGAN trained on the [Kaggle Anime Face Dataset](https://www.kaggle.com/datasets/splcher/animefacedataset).
- **DCGAN_Animeface_Improved.ipynb**: Enhances the initial DCGAN with deeper generator and discriminator architectures for sharper, more detailed anime face generation.

---
## 🙏 Acknowledgements

- [Kaggle Anime Face Dataset by splcher](https://www.kaggle.com/datasets/splcher/animefacedataset)
- PyTorch Tutorials and DCGAN examples
