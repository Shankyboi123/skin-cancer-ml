# Skin Cancer Classifier (HAM10000)

## Overview
A machine learning project to classify dermoscopic skin lesion images using the 
HAM10000 dataset, built as a self-directed learning exercise in deep learning 
and computer vision — with a long-term goal of an awareness tool (not a 
diagnostic device).

## ⚠️ Disclaimer
This project is for educational purposes only. It is NOT a medical diagnostic 
tool and should never be used as a substitute for professional medical advice.

## Dataset
- **Source:** [HAM10000](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000) 
  (10,015 dermoscopic images, 7 lesion classes)
- Not included in this repo due to size — see Setup below.

## Project Status
🚧 Work in progress — currently in EDA phase (Week 1 of 6)

## Setup
1. Clone this repo
2. Create a virtual environment: `python -m venv .venv && source .venv/bin/activate`
3. Install dependencies: `pip install -r requirements.txt`
4. Download HAM10000 from Kaggle and place in `data/`
5. Set `DATA_DIR` in notebooks to your local path

## Project Structure
skin-cancer-ml/
├── notebooks/       # Jupyter notebooks (EDA, modeling)
├── data/            # Dataset (not tracked in git)
└── README.md

## Tech Stack
- Python, PyTorch (MPS acceleration on Apple Silicon)
- pandas, numpy, matplotlib, seaborn, scikit-learn
- Jupyter Lab

## Roadmap
- [x] Environment setup
- [x] Exploratory Data Analysis
- [ ] Model building (CNN, transfer learning)
- [ ] Model evaluation (with focus on melanoma recall given class imbalance)
- [ ] Deployment (FastAPI / HuggingFace Inference API)

## Author
Shshank Jha  — Commerce/Computer Science student specializing in Data Science, 
AI, and Actuarial Science
