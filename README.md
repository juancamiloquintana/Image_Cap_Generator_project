# Image Captions Generator: Project Overview

This project implements an automatic image description generator (*Image Captioning*) using pre-trained convolutional neural networks (CNNs) such as **Inception V3**, **ResNet**, and **VGG**, combined with natural language processing models (RNN / LSTM).

---

## 🚀 Features

- **Visual feature extraction** using pre-trained CNNs:
  - Inception V3
  - ResNet
  - VGG16
- **Caption generation** using a sequential model with LSTM.
- **Data preprocessing** and text tokenization for model training.
- **Evaluation** using metrics such as BLEU score.
- **User interface** to upload images and receive automatic captions.

---

## 📂 Dataset

- **FLICKR8k Dataset** for training and validation.
- Split into **training**, **validation**, and **test** sets.
- Dataset source: [https://www.kaggle.com/datasets/adityajn105/flickr8k/data](https://www.kaggle.com/datasets/adityajn105/flickr8k/data)

---

## 🛠️ Code and Resources Used

**Python Version:** 3.8+  
**Packages:**  
`tensorflow`, `keras`, `numpy`, `pandas`, `matplotlib`, `Pillow`, `nltk`, `scikit-learn`  

## 📜 References & Resources

- [A Report on Image Caption Generator (2024)](https://www.linkedin.com/pulse/report-image-caption-generator-md-tabish-shaikh-sptlc/)  
- Image Caption Generator (2025) — *Best Image Caption Generator Tools in 2025*  
- A step-by-step guide to building an image caption generator using Tensorflow (2023) — *by Khaled Emam | Medium*  
- Image Captioning: Describiendo el Mundo Visual con Palabras (2024) — *by OliverSumari | Medium*  
- Generación de subtítulos de imágenes con tecnología LLM: desafíos y aplicaciones (2024) — *LLM-Powered Image Caption Generation - Challenges, and Applications*  
- [Monitoring Text-Based Generative AI Models Using Metrics Like Bleu Score](https://arize.com/blog-course/generative-ai-metrics-bleu-score/)  
- [Image Caption Generator Using Flickr Dataset](https://www.youtube.com/watch?v=fUSTbGrL1tc)

**For Installation:**  
```bash
pip install -r requirements.txt

