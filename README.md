# 🧠 AI Cancer Diagnosis & Treatment Assistant

This project demonstrates a multimodal AI system for supporting cancer diagnosis using chest X-rays and radiology reports. The system combines a **ResNet-50 CNN** for image feature extraction, **ClinicalBERT** for text embeddings, and a **fusion module** for joint inference.

## 🚀 Project Overview

- **Objective**: Assist clinicians by integrating image and text data into a single AI pipeline.
- **Inputs**: Chest X-ray + Radiology Report
- **Outputs**: AI-based prediction + Grad-CAM explainability
- **Tools**: PyTorch, Hugging Face Transformers, Streamlit (future), SHAP/Grad-CAM

---

## 🔧 Branch Structure

| Branch         | Purpose                                      |
|----------------|----------------------------------------------|
| `main`         | Production-ready merged code                 |
| `dev-image`    | Notebook for ResNet-50 + Grad-CAM pipeline   |
| `dev-text`     | Notebook for ClinicalBERT + text embeddings  |
| `dev-fusion`   | Notebook for mock multimodal fusion model    |

---

## 📂 Current Notebooks

| File | Branch | Description |
|------|--------|-------------|
| `resnet50_gradcam.ipynb` | `dev-image` | Image classification + Grad-CAM visualization |
| `clinicalbert_embed.ipynb` | `dev-text` | Text embedding from radiology reports |
| `fusion_demo.ipynb` | `dev-fusion` | Combines image and text features + binary classifier |

---

## 📈 Milestone Progress

- ✅ Phase 1: Image pipeline (ResNet-50, Grad-CAM)
- ✅ Phase 2: ClinicalBERT text embedding
- ✅ Phase 3: Fusion mock prototype (binary output)
- 🔜 Integration into Streamlit for interactive demo

---

## 🧪 How to Run

1. Clone the repo  
   ```bash
   git clone https://github.com/bernarddjoko/ai-cancer-diagnosis-assist.git
   cd ai-cancer-diagnosis-assist
