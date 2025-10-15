# Measuring and Incorporating Correlations in Generative Adversarial Networks

This repository contains the implementation for the project **“Measuring and Incorporating Correlations in Generative Adversarial Networks (GANs)”**, which investigates advanced techniques to improve GAN performance by explicitly modeling **feature correlations** during image generation.

---

## 🧠 Project Overview

Traditional GANs often fail to capture complex dependencies among features, leading to less realistic outputs.  
This project focuses on incorporating **correlation-based loss functions** and **conditioning strategies** to stabilize training and enhance the **diversity** and **quality** of generated samples.

### Key Objectives:
- Model correlations between latent space and generated features.  
- Implement correlation-based loss functions.  
- Evaluate using **FID (Fréchet Inception Distance)**.

---

## 🧩 Description

The project involves training GAN models on **images** (e.g., CIFAR-10, CelebA) and introducing correlation-aware components to the generator or discriminator.  
The performance is measured using **torch-fidelity** metrics such as FID.

---

## ⚙️ Technologies Used

- **Python 3.10+**
- **PyTorch**
- **TorchVision**
- **NumPy**
- **Matplotlib**
- **Torch-Fidelity** (for FID and IS computation)
- **Google Colab GPU Runtime (Preferably T4)**

---

## 🚀 Step-by-Step Installation and Execution Guide

Instructions to follow to install and run the project on **Google Colab** or **locally**.

### Run on Google Colab
1. Open [Google Colab](https://colab.research.google.com/).
2. Upload the notebook file:  
   **`ML_Project_192_185.ipynb`**
3. Go to:  
   `Runtime → Change runtime type → Hardware accelerator → GPU(T4)`
4. Run all cells sequentially using `Runtime → Run all`.
5. The notebook will automatically:
   - Load the dataset (CIFAR-10)
   - Train the GAN model
   - Compute and display **FID**

---

## 📈 Evaluation Metrics

| Metric | Description |
|---------|--------------|
| **FID (Fréchet Inception Distance)** | Measures similarity between real and generated distributions. Lower is better. |

---

## 📊 Datasets

Datasets used:
- **CIFAR-10**

---

## 👩‍💻 Authors / Collaborators

- **Drishti Golchha (PES2UG23CS185)**  
- **G S S Surya Prakash (PES2UG23CS192)**  
