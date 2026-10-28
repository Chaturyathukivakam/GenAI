<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0F172A,7C3AED,C084FC&height=220&section=header&text=Generative%20AI%20Projects&fontSize=40&fontColor=ffffff&fontAlignY=38&desc=GANs%20%C2%B7%20VAEs%20%C2%B7%20Style%20Transfer%20%C2%B7%20LLM%20Fine-Tuning%20%C2%B7%20Text%20Generation&descSize=15&descAlignY=60&descAlign=50" width="100%" alt="Header Banner"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow"/>
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="HuggingFace"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter"/>
  <img src="https://img.shields.io/github/stars/Chaturyathukivakam/GenAI?style=for-the-badge&color=yellow" alt="Stars"/>
</p>

---

## 📋 Executive Summary

A comprehensive portfolio of **Generative AI** projects spanning the full spectrum of modern generative models — from **DCGANs** and **StyleGAN2** to **Variational Autoencoders (VAEs)**, **Neural Style Transfer**, **CycleGAN**, and **Large Language Model fine-tuning**. Each project is implemented as an independent Jupyter Notebook with hands-on experiments, visualizations, and analysis.

This collection demonstrates practical expertise in training generative adversarial networks, exploring latent spaces, diagnosing and fixing mode collapse, performing image-to-image translation, fine-tuning GPT-2, and building AI-powered code explanation tools using Qwen LLMs.

---

## 📑 Table of Contents

- [Key Features & Capabilities](#-key-features--capabilities)
- [Project Catalog](#-project-catalog)
- [System Architecture](#-system-architecture)
- [Tech Stack Breakdown](#-tech-stack-breakdown)
- [Quickstart & Setup](#-quickstart--setup)
- [Project Directory Layout](#-project-directory-layout)
- [Author & Contributions](#-author--contributions)

---

## ✨ Key Features & Capabilities

- **DCGAN on Fashion-MNIST** — Full training pipeline with Generator & Discriminator networks, loss curves, and epoch-wise generated image progression using PyTorch
- **StyleGAN2 Latent Space Exploration** — Latent vector interpolation, dimension manipulation, and GIF generation using NVIDIA's pretrained StyleGAN2-ADA
- **Neural Style Transfer vs CycleGAN** — Side-by-side comparison of VGG19-based style transfer and CycleGAN (horse2zebra) image translation with analysis
- **Mode Collapse Diagnosis & Fix** — Deliberate GAN destabilization followed by recovery using label smoothing and learning rate tuning on MNIST
- **Discriminative vs Generative Models** — Logistic Regression (discriminative) vs Autoencoder (generative) comparison on MNIST digit classification
- **GPT-2 Text Generation Experiments** — Temperature, top-k, top-p, and repetition penalty analysis with comparative output tables
- **GPT-2 Fine-Tuning on Custom Text** — End-to-end fine-tuning pipeline using HuggingFace Trainer with custom conversational dataset
- **Variational Autoencoder (VAE)** — MNIST image compression, reconstruction, denoising, and latent dimension impact analysis
- **GitHub Repository Code Explainer** — LLM-powered tool using Qwen2.5-0.5B-Instruct to clone repos and generate natural-language code explanations

---

## 📖 Project Catalog

| Assignment | Notebook | Topic | Key Libraries |
|-----------|----------|-------|---------------|
| **Assignment 4** | `ASSIGNMENT_4.ipynb` | DCGAN Training on Fashion-MNIST | PyTorch, Torchvision |
| **Assignment 5** | `ASSIGNMENT 5 GEN AI .ipynb` | StyleGAN2 Latent Space Exploration | PyTorch, NVIDIA StyleGAN2-ADA |
| **Assignment 6** | `ASSIGNMENT_6.ipynb` | Neural Style Transfer vs CycleGAN | PyTorch, VGG19, CycleGAN |
| **Assignment 7** | `Assignment_7.ipynb` | Mode Collapse — Diagnosis & Fix | TensorFlow, Keras |
| **Assignment 10** | `Assignment_10.ipynb` | VAE — Compression, Reconstruction, Denoising | TensorFlow, Keras |
| **Assignment 11** | `Assignment_11_.ipynb` | Fine-Tuning GPT-2 on Custom Text | HuggingFace Transformers |
| **Mini Assignment** | `Local_GitHub_Repository_Code_Explainer.ipynb` | LLM-Powered Code Explainer | Qwen2.5, GitPython |
| **Experiment** | `Untitled11.ipynb` | Discriminative vs Generative Models (MNIST) | TensorFlow, Scikit-learn |
| **Experiment** | `Untitled13.ipynb` | GPT-2 Text Generation — Decoding Strategies | HuggingFace Transformers |

---

## 🏗️ System Architecture

```mermaid
flowchart TD
    A["🤖 Generative AI Projects"] --> B["🖼️ Image Generation"]
    A --> C["📝 Text Generation"]
    A --> D["🔬 Analysis & Comparison"]

    B --> B1["DCGAN<br/>Fashion-MNIST · PyTorch"]
    B --> B2["StyleGAN2<br/>Latent Interpolation · NVIDIA"]
    B --> B3["Neural Style Transfer<br/>VGG19 · Content + Style Loss"]
    B --> B4["CycleGAN<br/>Horse2Zebra Domain Transfer"]
    B --> B5["VAE<br/>MNIST · Compression · Denoising"]

    C --> C1["GPT-2 Text Generation<br/>Temperature · Top-k · Top-p"]
    C --> C2["GPT-2 Fine-Tuning<br/>Custom Dataset · HuggingFace Trainer"]
    C --> C3["Code Explainer<br/>Qwen2.5 LLM · GitPython"]

    D --> D1["Mode Collapse<br/>Diagnosis & Label Smoothing Fix"]
    D --> D2["Discriminative vs Generative<br/>LogReg vs Autoencoder"]
```

---

## 🛠️ Tech Stack Breakdown

| Category | Technology | Purpose |
|----------|-----------|---------|
| **Language** | Python 3.8+ | Core programming language |
| **Deep Learning** | PyTorch | DCGAN, StyleGAN2, Neural Style Transfer, CycleGAN |
| **Deep Learning** | TensorFlow / Keras | GAN mode collapse experiments, VAE, Autoencoders |
| **NLP / LLMs** | HuggingFace Transformers | GPT-2 text generation & fine-tuning, Qwen2.5 |
| **Training** | HuggingFace Accelerate | Distributed training & mixed precision |
| **Data** | HuggingFace Datasets | Dataset loading & tokenization |
| **Computer Vision** | Torchvision | Data transforms, VGG19 pretrained model |
| **Git Automation** | GitPython | Repository cloning for code explainer |
| **Visualization** | Matplotlib | Training curves, generated images, comparisons |
| **ML Utilities** | Scikit-learn | Logistic Regression, preprocessing |
| **Notebooks** | Jupyter / Google Colab | Interactive development with GPU support |

---

## 🚀 Quickstart & Setup

### Prerequisites

- Python 3.8 or higher
- GPU recommended (Google Colab with GPU runtime is ideal)
- ~5 GB disk space for model weights

### Installation

```bash
# Clone the repository
git clone https://github.com/Chaturyathukivakam/GenAI.git
cd GenAI

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate        # macOS / Linux
# venv\Scripts\activate          # Windows

# Install core dependencies
pip install torch torchvision tensorflow numpy matplotlib
pip install transformers datasets accelerate sentencepiece
pip install scikit-learn gitpython pillow imageio
```

### Run the Notebooks

```bash
# Launch Jupyter
jupyter notebook

# Or open any .ipynb file directly in Google Colab
```

> 💡 **Tip:** Assignments 4, 5, and 11 require GPU acceleration. Use Google Colab with a T4/A100 runtime for best results.

---

## 📂 Project Directory Layout

```
GenAI/
├── ASSIGNMENT_4.ipynb                          # DCGAN — Fashion-MNIST
├── ASSIGNMENT 5 GEN AI .ipynb                  # StyleGAN2 Latent Space Exploration
├── ASSIGNMENT_6.ipynb                          # Neural Style Transfer vs CycleGAN
├── Assignment_7.ipynb                          # Mode Collapse — Diagnosis & Fix
├── Assignment_10.ipynb                         # VAE — Compression & Denoising
├── Assignment_11_.ipynb                        # GPT-2 Fine-Tuning on Custom Text
├── Local_GitHub_Repository_Code_Explainer.ipynb # LLM-Powered Code Explainer (Qwen2.5)
├── Untitled11.ipynb                            # Discriminative vs Generative Models
├── Untitled13.ipynb                            # GPT-2 Text Generation Strategies
└── README.md                                   # Project documentation
```

---

## 👤 Author & Contributions

**Chaturya Thukivakam**

[![GitHub](https://img.shields.io/badge/GitHub-Chaturyathukivakam-181717?style=for-the-badge&logo=github)](https://github.com/Chaturyathukivakam)

Contributions, issues, and feature requests are welcome! Feel free to open a pull request.

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0F172A,7C3AED,C084FC&height=100&section=footer" width="100%" alt="Footer Banner"/>
</p>
