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
| ![](D:\H - Project Section\MedRecon-ARU Attention Residual U-Net for MRI & CT Image Reconstruction\CT-Original Image.png) | ![](D:\H - Project Section\MedRecon-ARU Attention Residual U-Net for MRI & CT Image Reconstruction\Noisey-CT Image.png) | ![](dD:\H - Project Section\MedRecon-ARU Attention Residual U-Net for MRI & CT Image Reconstruction\CT-Reconstructed Image.png) |

### **PSNR / SSIM Summary**
Your results file (`results.csv`) may include something like:

| Image | PSNR ↑ | SSIM ↑ |
|--------|---------|-----------|
| MRI_01 | 31.2 dB | 0.90 |
| MRI_02 | 32.8 dB | 0.92 |
| CT_01  | 29.7 dB | 0.88 |

(Use your actual values.)

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