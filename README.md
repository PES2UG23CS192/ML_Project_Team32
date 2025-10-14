# ML_Project_Team32
# Measuring and Incorporating Correlations in Generative Adversarial Networks

This project investigates techniques to improve **Generative Adversarial Network (GAN)** performance by explicitly modeling **feature correlations** during the image generation process.  
The objective is to explore **correlation-based loss functions** and **conditioning mechanisms** to enhance the quality and diversity of generated samples.

---

## 🧠 Project Overview

Traditional GANs often struggle to capture inter-feature dependencies effectively.  
This project focuses on incorporating correlation information into the training process to stabilize GAN training and produce more realistic outputs.

Key ideas explored:
- Modeling correlations between latent and generated features.  
- Using correlation-based regularization or loss terms.  
- Evaluating generated images using **FID (Fréchet Inception Distance)** and **Inception Score (IS)**.  

---

## 📊 Dataset

You can use open or synthetic datasets such as:
- **CIFAR-10**
- **CelebA**
- Custom or synthetic tabular datasets  

Datasets can be loaded using PyTorch’s `torchvision.datasets` or from public repositories.

---

## ⚙️ Implementation Details

The project was implemented in **Python** using **Google Colab** for GPU acceleration.  

### Major Libraries Used:
- `torch`, `torchvision`, `torch.nn`
- `numpy`, `matplotlib`
- `torch-fidelity` for FID/IS evaluation

---

## 🚀 How to Run on Google Colab

1. Open [Google Colab](https://colab.research.google.com/).  
2. Upload the notebook: **ML_Project_192_185.ipynb**.  
3. Enable **GPU Runtime**:  
   ```
   Runtime → Change runtime type → Hardware accelerator → GPU
   ```
4. Run all cells sequentially.  
5. The notebook will:
   - Train a GAN on your chosen dataset  
   - Compute **FID** and/or **Inception Score** for evaluation  

---

## 📈 Evaluation Metrics

- **Inception Score (IS):** Measures sample diversity and quality.  
- **Fréchet Inception Distance (FID):** Measures distance between real and generated distributions.  

Lower FID and higher IS indicate better model performance.

---

## 🧩 Possible Extensions

- Experiment with **correlation-based discriminators**.  
- Introduce **attention mechanisms** to capture feature dependencies.  
- Apply to **conditional GANs (cGANs)** or **StyleGAN architectures**.  

---

## 📚 References

- Goodfellow et al., *“Generative Adversarial Nets”*, NeurIPS 2014.  
- Heusel et al., *“GANs Trained by a Two Time-Scale Update Rule Converge to a Local Nash Equilibrium”*, NeurIPS 2017.  
- Radford et al., *“Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks”*, 2016.

---

## 👩‍💻 Authors

- **Drishti Golchha (PES2UG23CS185)**  
- Under the guidance of **[Your Instructor’s Name or Course Title]**
