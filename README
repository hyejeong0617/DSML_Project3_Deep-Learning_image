# CIFAR-10 Image Classification Project

## 📚 Dataset
This project uses the CIFAR-10 dataset, which contains 60,000 color images (32×32) across 10 classes.  
All images were normalized, one-hot encoded, and resized (for transfer learning models when needed).

---

## ✨ Project Highlight
- Designed and trained multiple **custom CNN architectures**.
- Applied **transfer learning** using MobileNetV2, EfficientNetB0, and ResNet50.
- Compared performance across all models using consistent preprocessing and evaluation metrics.
- Best CNN reached **86%** accuracy, while best transfer learning model achieved **94.46%**.

---

## 🔄 Project Workflow Overview
1. Load and explore the CIFAR-10 dataset  
2. Preprocess data  
3. Build and train multiple CNN architectures  
4. Implement and fine-tune transfer learning models  
5. Evaluate models (accuracy, precision, recall, F1-score, confusion matrix)  
6. Compare custom CNNs with transfer learning  
7. Summarize key findings and prepare final presentation  

---

## 🧱 Part I: Custom CNN Models

### Models Evaluated
- **Baseline CNN** — ~69%  
- **Deeper CNN (30 epochs)** — ~77%  
- **Early Stopping version** — ~80%  
- **Data Augmentation version** — ~80%  
- **Best CNN (Aug + BatchNorm + LR Scheduler)** — **86%**

### Notes
- Regularization (augmentation, batch normalization) and optimized learning rates were essential for improving performance.
- The best CNN demonstrated a strong balance between simplicity and accuracy.

---

## 🤖 Part II: Transfer Learning

### Models Evaluated (Optimized)
- **MobileNetV2** — 87.13%  
- **EfficientNetB0** — 93.87%  
- **ResNet50** — **94.46%** (best overall model)

### Notes
- Fine-tuned versions consistently outperformed frozen-feature models.
- Transfer learning models captured richer features than custom CNNs, resulting in significantly higher accuracy.

---

## 🏆 Key Results

### Best Model
- **ResNet50 (fine-tuned)** — **94.46%**

### Major Findings
- Transfer learning outperformed custom CNNs by **8–9%**.  
- Lightweight pretrained models (e.g., MobileNetV2) still exceeded most CNN versions.  
- Custom CNNs improved significantly with better regularization and tuning but couldn’t match pretrained networks.

---

## 📁 Project Files
- **Part I:** Custom CNN Models → `CNNs.ipynb`  
- **Part II:** Transfer Learning → `TL1_MobileNetV2.ipynb`, `TL2_EfficientNetB0.ipynb`, `TL3_ResNet50.ipynb`  
- **Part III:** Model comparision/visualization →  `Model comparision.ipynb`
- **Presentation:** Key insights → `Project3_presentation(Hayley).pdf`



## 👨‍💻 Author

**Hyejeong Hayley Lee**  
📧 hyejeong0617@gmail.com