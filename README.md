# ECG-to-SCG Signal Transformation using Wavelet CycleGAN

## Overview  
In today’s fast-paced world, visiting hospitals for routine cardiovascular check-ups can be impractical. Fortunately, wearable devices with **Seismocardiogram (SCG) sensors** enable continuous, non-invasive heart monitoring.  

This project, **"Deep Learning-Based Approaches for Cardiovascular Monitoring Using SCG Signals,"** leverages a **Unified Attentive Cyclic Generative Adversarial Network (GAN)** to:  
- Convert SCG signals into ECG signals (and vice versa)  
- Improve the quality of SCG signals using **Wavelet Transformations**  
- Detect critical metrics like **heart rate variability, respiratory rate, and arrhythmias**  
- Enhance **smartwatch-based heart monitoring** for real-time alerts  

---

## Features  
- SCG-to-ECG Signal Synthesis using a **CycleGAN**  
- Wavelet Transform-Based Noise Reduction (DWT, IDWT)  
- Multi-Discriminator Setup for stable adversarial learning  
- QRS Complex Detection for accurate ECG analysis  
- Two Time-Scale Update Rule (TTSUR) for better GAN optimization  
- Deep Learning-Based Signal Classification using CNNs  
- SHAP (SHapley Additive exPlanations) Model Interpretability  

---

## Tech Stack  
- **Python** (NumPy, SciPy, TensorFlow, PyTorch)  
- **Wavelet Transforms** (PyWavelets)  
- **Machine Learning** (Scikit-Learn, SHAP)  
- **Deep Learning** (GANs, CNNs, TensorFlow/Keras)  
- **Signal Processing** (EDF File Handling, Filtering, QRS Detection)  

---

