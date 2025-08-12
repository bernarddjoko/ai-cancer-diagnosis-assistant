# 🧠 AI Cancer Diagnosis & Treatment Assistant

This project demonstrates a **multimodal AI system** for supporting cancer diagnosis using **chest X-rays** and **radiology reports**.  
The system combines a **ResNet-50 CNN** for image feature extraction, **ClinicalBERT** for text embeddings, and a **fusion module** for joint inference.  
**Grad-CAM** is integrated for visual explainability.

> ⚠️ **Disclaimer:** This project is for **academic demonstration only** and is not a medical device.

---

## 🚀 Project Overview

- **Objective**: Assist clinicians by integrating image and text data into a single AI pipeline.
- **Inputs**: Chest X-ray (image) + Radiology Report (text)
- **Outputs**: Mock AI-based prediction + Grad-CAM explainability
- **Tools**: PyTorch, TorchVision, Hugging Face Transformers, OpenCV, Matplotlib, SHAP  
  *(Future: Streamlit + FastAPI for deployment)*

---

## 🔧 Branch Structure

| Branch              | Purpose                                                      |
|---------------------|--------------------------------------------------------------|
| `Full-Code-Final`   | **Final submission branch** — complete end-to-end notebook   |
| `main`              | Stable, presentation-ready materials (README, slides, figures) |
| `dev-image`         | ResNet-50 + Grad-CAM pipeline                                |
| `dev-text`          | ClinicalBERT text embedding                                  |
| `dev-fusion`        | Mock multimodal fusion model                                 |

---

## 📂 Notebooks

| File                              | Branch            | Description                                   |
|-----------------------------------|-------------------|-----------------------------------------------|
| `notebooks/00_full_demo.ipynb`    | Full-Code-Final   | End-to-end runnable demo with all components  |
| `resnet50_gradcam.ipynb`          | dev-image         | Image classification + Grad-CAM visualization |
| `clinicalbert_embed.ipynb`        | dev-text          | ClinicalBERT embeddings from radiology reports |
| `fusion_demo.ipynb`               | dev-fusion        | Combines image and text features + binary classifier |

---

## 📈 Milestone Progress

- ✅ Phase 1: Image pipeline (**ResNet-50**, **Grad-CAM**)
- ✅ Phase 2: **ClinicalBERT** text embeddings
- ✅ Phase 3: **Fusion mock prototype** (binary output)
- 🔜 Deployment via **Streamlit** + **FastAPI** for an interactive demo

---

## 🧪 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/bernarddjoko/ai-cancer-diagnosis-assistant.git
cd ai-cancer-diagnosis-assistant
