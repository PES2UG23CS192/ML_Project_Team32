# Measuring and Incorporating Correlations in Generative Adversarial Networks

This repository contains the implementation for the project **“Measuring and Incorporating Correlations in Generative Adversarial Networks (GANs)”**, which investigates advanced techniques to improve GAN performance by explicitly modeling **feature correlations** during image generation.

---

## 🧠 Project Overview

Traditional GANs often fail to capture complex dependencies among features, leading to less realistic outputs.  
This project focuses on incorporating **correlation-based loss functions** and **conditioning strategies** to stabilize training and enhance the **diversity** and **quality** of generated samples.

### Key Objectives:
- Model correlations between latent space and generated features.  
- Implement correlation-based loss functions.  
- Evaluate using **FID (Fréchet Inception Distance)** and **Inception Score (IS)**.

---

## 👨‍💻 Team Information

| Role | Name | ID |
|------|------|----|
| Project Member | **Drishti Golchha** | PES2UG23CS185 |
| Project Member | **G S S Surya Prakash** | PES2UG23CS185 |
| Mentor / Instructor | *[Add instructor name here]* | *[Optional]* |

---

## 🧩 Description

The project involves training GAN models on **image or synthetic datasets** (e.g., CIFAR-10, CelebA) and introducing correlation-aware components to the generator or discriminator.  
The performance is measured using **torch-fidelity** metrics such as FID and IS.

---

## ⚙️ Technologies Used

- **Python 3.10+**
- **PyTorch**
- **TorchVision**
- **NumPy**
- **Matplotlib**
- **Torch-Fidelity** (for FID and IS computation)
- **Google Colab GPU Runtime**

---

## 🚀 Step-by-Step Installation and Execution Guide

Follow these instructions to install and run the project on **Google Colab** or **locally**.

### 🔹 Option 1: Run on Google Colab (Recommended)
1. Open [Google Colab](https://colab.research.google.com/).
2. Upload the notebook file:  
   **`ML_Project_192_185.ipynb`**
3. Go to:  
   `Runtime → Change runtime type → Hardware accelerator → GPU`
4. Run all cells sequentially using `Runtime → Run all`.
5. The notebook will automatically:
   - Load the dataset (CIFAR-10 or CelebA)
   - Train the GAN model
   - Compute and display **FID** and **Inception Score**

---

### 🔹 Option 2: Run Locally (Optional)

#### Step 1: Clone the Repository
```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
```

#### Step 2: Create a Virtual Environment
```bash
python -m venv gan-env
source gan-env/bin/activate  # On Windows use: gan-env\Scripts\activate
```

#### Step 3: Install Dependencies
```bash
pip install -r requirements.txt
```

If you don’t have a `requirements.txt`, install manually:
```bash
pip install torch torchvision numpy matplotlib torch-fidelity
```

#### Step 4: Run the Notebook
```bash
jupyter notebook ML_Project_192_185.ipynb
```

---

## 📈 Evaluation Metrics

| Metric | Description |
|---------|--------------|
| **FID (Fréchet Inception Distance)** | Measures similarity between real and generated distributions. Lower is better. |
| **Inception Score (IS)** | Evaluates diversity and quality of generated samples. Higher is better. |

---

## 📊 Datasets

You can use any of the following datasets:
- **CIFAR-10**
- **CelebA**
- Synthetic or custom datasets (optional)

---

## 🔮 Future Work

- Integrate **attention mechanisms** to capture feature dependencies.  
- Extend the approach to **conditional GANs (cGANs)** and **StyleGANs**.  
- Explore **hybrid correlation-based discriminators** for improved feedback.

---
## 👩‍💻 Authors / Collaborators

- **Drishti Golchha (PES2UG23CS185)**  
- **G S S Surya Prakash (PES2UG23CS185)**  
