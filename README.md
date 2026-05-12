# DAM-D-FINE

This repository contains the official open-source code for the lightweight road surface crack detection model DAM-D-FINE, associated with our manuscript submitted to Pattern Analysis and Applications. 

**Commitment:** We guarantee long-term public access to this repository to support future research and ensure the full reproducibility of our method.

## 🌟 What's Included
To ensure complete transparency and reproducibility, this repository explicitly provides:
- **Data Preprocessing Scripts:** Code to process and format the raw RDD2022 and SVRDD datasets.
- **Complete Training Scripts:** The full training pipeline with all hyperparameter configurations used in our paper, allowing researchers to train the model from scratch.
- **Testing & Inference Scripts:** Complete code for evaluating model metrics (mAP, Precision, Recall) and generating visual detection results.

## 📚 Supported Datasets
We provide complete support for two public road surface crack datasets. Please download the datasets and place them in the `data/` directory of this project following standard annotation formats.

- **RDD2022 Dataset**
  - *Official Download:* [https://figshare.com/articles/dataset/RDD2022_-_The_multi-national_Road_Damage_Dataset_released_through_CRDDC_2022/21431547](https://figshare.com/articles/dataset/RDD2022_-_The_multi-national_Road_Damage_Dataset_released_through_CRDDC_2022/21431547)

- **SVRDD Dataset**
  - *Official Download:* [https://zenodo.org/records/10100129](https://zenodo.org/records/10100129)

## 🛠️ Environment Requirements
Install core dependencies:
```bash
pip install torch torchvision einops opencv-python numpy tqdm

# 🛠️ Environment Requirements
Install core dependencies
pip install torch torchvision einops opencv-python numpy tqdm

Install full dependencies
pip install -r requirements.txt

# 🚀 Model Training
python train.py

# 🔍 Model Inference
python tools/inference/torch_inf.py


