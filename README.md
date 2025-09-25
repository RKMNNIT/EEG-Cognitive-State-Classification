# 🧠 EEG Cognitive State Classification

This repository contains the code and resources for the paper:  
**"Cognitive State Classification Using a Single-Channel Headset: An EEG Analysis Approach"**  
Published at **IEEE ICCCNT 2023, IIT Delhi**:contentReference[oaicite:1]{index=1}  

## 📌 Project Overview
We classify cognitive states (Math vs Relax) using EEG data recorded with the **Neurosky Mindwave Mobile 2 single-channel headset**.  
Machine Learning and Deep Learning models were evaluated for EEG-based brain state recognition.  

## ⚙️ Methodology
- **Feature Extraction:** Fast Fourier Transform (FFT), EEG power spectrum, statistical features  
- **Models Used:**
  - Logistic Regression  
  - Linear & Non-linear SVM  
  - Random Forest  
  - Gradient Boosting  
  - XGBoost  
  - Multi-Layer Perceptron (MLP)  
  - Neural Network (Deep Learning)  
- **Optimization:** Hyperparameter tuning with Random Search & Hyperband  

## 🏆 Results
- Random Forest achieved **89% accuracy**  
- XGBoost achieved **87% accuracy** (improved to **90% after tuning**)  
- Gradient Boosting reached **81% accuracy**  
- Other models (LR, SVM, MLP, NN) performed significantly lower (~59–60%)  

## 📊 Key Contribution
✅ Demonstrated reliable **cognitive state classification** using a **low-cost single-channel EEG headset**  
✅ Improved accuracy through **FFT-based feature extraction & hyperparameter tuning**  
✅ Published at a reputed IEEE Conference (ICCCNT 2023)  

## 📂 Repository Structure
- `notebooks/` → Jupyter/Colab notebooks for preprocessing & model training  
- `results/` → Performance metrics, confusion matrices  
- `paper/` → Published paper PDF  

## 📫 Citation
If you use this code or dataset, please cite:  
> R. K. Rai, D. K. Singh, L. Kumar, and M. A. Ansari,  
> "Cognitive State Classification Using a Single-Channel Headset: An EEG Analysis Approach,"  
> *Proc. 14th IEEE ICCCNT, IIT Delhi, 2023.* DOI: 10.1109/ICCCNT56998.2023.10306824:contentReference[oaicite:2]{index=2}  

---

