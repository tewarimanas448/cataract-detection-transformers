# Transformer-Based Cataract Detection using Knowledge Distillation

An AI-powered cataract detection system that leverages **Vision Transformers (ViT)** and **Knowledge Distillation** to train a lightweight **ResNet-18** model for accurate and efficient binary classification of retinal fundus images. This project was developed as a B.Tech Semester 6 project at The LNM Institute of Information Technology (LNMIIT). :contentReference[oaicite:0]{index=0}

---

## 📌 Overview

Cataracts are one of the leading causes of vision impairment worldwide. Early diagnosis is essential but often requires specialized equipment and expert ophthalmologists. This project aims to automate cataract detection from retinal fundus images using deep learning, making screening more accessible and scalable.

Our approach combines:
- 🧠 Vision Transformer (Teacher Model)
- 🎯 Knowledge Distillation
- ⚡ ResNet-18 (Student Model)

The resulting model achieves approximately **97.52% accuracy** while remaining computationally efficient for deployment. :contentReference[oaicite:1]{index=1}

---

## 🚀 Features

- Binary classification of retinal images
- Transformer-based teacher model
- Lightweight ResNet-18 student model
- Knowledge Distillation for efficient learning
- Automated image preprocessing
- PyTorch implementation
- Google Colab compatible
- High accuracy (~97.52%) :contentReference[oaicite:2]{index=2}

---

## 🏗️ Architecture

```text
Input Fundus Image
        │
        ▼
Vision Transformer (Teacher)
        │
Knowledge Distillation
        │
        ▼
 ResNet-18 (Student)
        │
        ▼
Prediction
(Cataract / Normal)
```

:contentReference[oaicite:3]{index=3}

---

## 📂 Dataset

**Dataset:** ODIR-5K (Ocular Disease Intelligent Recognition Dataset)

- Binary Classes:
  - Cataract
  - Normal
- Images resized to **224 × 224**
- JPEG / PNG format
- Source: Kaggle (ODIR-5K) :contentReference[oaicite:4]{index=4}

---

## 🛠️ Tech Stack

- Python
- PyTorch
- timm
- Torchvision
- Google Colab
- Vision Transformer (ViT)
- ResNet-18
- Knowledge Distillation :contentReference[oaicite:5]{index=5}

---

## 📁 Project Structure

```text
├── Cataract_Detection.ipynb
├── dataset/
│   ├── train/
│   ├── validation/
│   └── test/
├── models/
├── results/
├── images/
├── requirements.txt
└── README.md
```

---

## ⚙️ Methodology

1. Data Collection
2. Data Preprocessing
3. Teacher Model (Vision Transformer)
4. Student Model (ResNet-18)
5. Knowledge Distillation Training
6. Model Evaluation
7. Image Inference :contentReference[oaicite:6]{index=6}

---

## 📊 Results

| Metric | Value |
|---------|------:|
| Accuracy | **97.52%** |
| Task | Binary Classification |
| Classes | Cataract / Normal |

The distilled ResNet-18 achieves high accuracy while significantly reducing computational complexity compared to using a Vision Transformer alone. :contentReference[oaicite:7]{index=7}

---

## 💡 Advantages

- High prediction accuracy
- Lightweight deployment model
- Faster inference
- Reduced computational cost
- Suitable for automated screening
- Scalable for real-world applications :contentReference[oaicite:8]{index=8}

---

## ⚠️ Limitations

- Binary classification only
- Limited dataset diversity
- Performance depends on image quality
- Teacher model is computationally expensive during training :contentReference[oaicite:9]{index=9}

---

## 🔮 Future Work

- Multi-class cataract grading
- Improved knowledge distillation strategies
- Attention visualization (Grad-CAM)
- Multi-disease detection
- Web application deployment :contentReference[oaicite:10]{index=10}

---

## ▶️ Running the Project

Clone the repository:

```bash
git clone https://github.com/yourusername/cataract-detection.git
cd cataract-detection
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch the notebook:

```bash
jupyter notebook
```

or open the notebook in **Google Colab**.

---

## 👨‍💻 Authors

- Manas Tewari
- Madhav Gupta
- Sambhav Budhiraja

B.Tech Semester VI Project  
The LNM Institute of Information Technology (LNMIIT), Jaipur :contentReference[oaicite:11]{index=11}

---

## 📄 License

This project is intended for educational and research purposes.
