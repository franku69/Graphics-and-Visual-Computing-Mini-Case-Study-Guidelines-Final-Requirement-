# CIFAR-10 Fusion: ResNet50 + MobileNetV2  
**Authors:** Postrero • Banaag • Englatiera

---

## 📌 Overview
This repository contains our Mini Case Study for **Graphics & Visual Computing**.  
We perform **image classification** on CIFAR-10 using a **fusion architecture** that merges features from **ResNet50** and **MobileNetV2** before classification.

The project demonstrates:
- Image processing & visualization  
- Deep learning architecture fusion  
- Feature-level concatenation  
- Performance comparison between baseline models and fused models  

All training, evaluation, and visualization steps are reproducible through the included Google Colab notebook.

---

## 🚀 How to Run (Google Colab)

1. Open the notebook:
Image_Classification_on_CIFAR_10_Using_a_Fusion_of_ResNet50_and_MobileNetV2_Features.ipynb

2. Set GPU:
Runtime → Change runtime type → GPU

4. Run all cells.

All generated figures will run:
This includes:
- samples.png  
- architecture.png  
- curves_baseline.png  
- curves_fusion.png  
- pred_examples.png  
- gradcam_examples.png  

---

## 🔁 Reproducibility

- **Random seed:** `42`  
- Full hyperparameters included in the notebook  
- Notebook executes end-to-end (data loading → training → visualization)  
- Results can be reproduced 1:1 by running the notebook on GPU
  


