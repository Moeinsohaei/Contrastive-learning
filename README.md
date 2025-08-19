# Contrastive-learning
Contrastive Learning on Histopathology Data
This repository provides a Jupyter Notebook pipeline for preparing and processing histopathology images (Colon Benign and Adenocarcinoma) from the **CellNet dataset** for contrastive learning tasks.

## Features
- ✅ Download CellNet dataset from Kaggle
- ✅ Organize images and masks for benign vs. cancerous tissues
- ✅ Apply **Cellpose** for nuclei segmentation
- ✅ Generate binary masks for each image
- ✅ Extract morphological features (centroid, bounding box, area) of nuclei
- ✅ Export results as CSV files for further analysis
- ✅ Prepare data for **contrastive representation learning** models (e.g., SimCLR)

## Applications
- Cancer vs. healthy tissue classification
- Nuclei segmentation and morphological analysis
- Pretraining histopathology models with contrastive learning
