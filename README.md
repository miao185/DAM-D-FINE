# DAM-D-FINE
This repository contains the official open-source code for the lightweight highway pavement crack detection model DAM-D-FINE, associated with our manuscript submitted to The Visual Computer.

# 📚 Supported Datasets
We provide complete support for two public road damage / pavement crack datasets, with official download links as follows:
1. RDD2022 Dataset
The multi-national Road Damage Dataset released through CRDDC 2022
Official Download: https://figshare.com/articles/dataset/RDD2022_-_The_multi-national_Road_Damage_Dataset_released_through_CRDDC_2022/21431547
Description: Includes road damage images and annotations from Japan, India, Czech, Norway, the United States, and China.

2. SVRDD Dataset
Official Download: https://zenodo.org/records/10100129

Please download the datasets and place them in the data/ directory of this project following standard annotation formats.

# 🛠️ Environment Requirements
Install core dependencies
pip install torch torchvision einops opencv-python numpy tqdm

Install full dependencies
pip install -r requirements.txt

# 🚀 Model Training
python train.py

# 🔍 Model Inference
python tools/inference/torch_inf.py

# 📝 Citation
If you use this code or model in your research, please cite our manuscript submitted to The Visual Computer.
Recommended citations from The Visual Computer:
1. Road crack detection using pixel classification and intensity-based distinctive fuzzy C-means clustering. The Visual Computer, 2025, 41(3): 1689-1704.
2. Malleable pruning meets more scaled wide-area of attention model for real-time crack detection. The Visual Computer, 2025, 41(3): 2029-2046.

# ⚠️ Important Notice
This code repository is directly related to the manuscript submitted to The Visual Computer. All implementations are original contributions of the submitted work. Please cite the corresponding manuscript when using this code for academic research.
