# 🧠 MedRecon-ARU: Attention Residual U-Net for MRI & CT Image Reconstruction

This project applies an **Attention Residual U-Net (ARU-Net)** model to reconstruct **Brain MRI & CT images** that were artificially degraded by injecting noise.  
The goal is to evaluate how effectively deep learning can restore structural details even with small datasets.

---

# 🚀 Project Summary

- **Dataset:** 100 Brain MRI & CT images (publicly available)  
- **Noise:** Added Gaussian noise with variance = **0.5**  
- **Model:** Attention Residual U-Net  
- **Task:** Image reconstruction / denoising  
- **Metrics:** PSNR & SSIM  
- **Outcome:** The model successfully recovered structural information and achieved strong reconstruction quality.

This project demonstrates the potential of deep learning for medical image enhancement, especially in low-data or low-resource scenarios.

---

# 🏗️ Model Architecture: Attention Residual U-Net

The model includes:
- Encoder–decoder U-Net backbone  
- Residual blocks for stable training  
- Attention gates to emphasize important features  

This architecture is particularly effective for medical image reconstruction.

---

# 📊 Results (Sample)

| Original | Noisy (0.5) | Reconstructed |
|----------|--------------|----------------|
| ![](CT-Original Image.png) | ![](Noisey-CT Image.png) | ![](CT-Reconstructed Image.png) |

### **PSNR / SSIM Summary**
Brain & MRI image SSIM Train Vlidation & Test Result:
# Brain MRI Images Result:
    | PSNR ↑ | SSIM ↑ | Sample | 
|---------|-----------|-----|
Train | 27.42 dB | 0.78 | 82 |
Val | 28.68 dB | 78 | 10 |
Test| 27.7 dB | 0.75 | 11 |

Brain & MRI image SSIM Train Vlidation & Test Result:
# Brain MRI Images Result:
    | PSNR ↑ | SSIM ↑ | Sample | 
|---------|-----------|-----|
Train | 29.63 dB | 0.81 | 82 |
Val | 29.78 dB | 0.84 | 10 |
Test| 29.63 dB | 0.81 | 11 |
---

# ✨ Key Highlights (For Scholarship Evaluation)

- Small-data medical imaging experiment  
- Effective reconstruction despite only 100 images  
- Demonstrates strong understanding of:
  - Deep learning architectures  
  - Denoising  
  - Evaluation metrics  
- Shows ability to execute a full ML experiment independently  
- Relevant for EMJM fields: Medical Imaging, AI for Health, Bio-Data Science  

---

# 👨‍💻 Author

**Kawsar Mahmud**  
Deep Learning & Medical AI Enthusiast  
GitHub: `KMsojib`

---

# 📄 License
MIT License.