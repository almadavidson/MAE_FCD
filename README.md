Self-Supervised Lesion Detection Using a Masked Autoencoder

This repository contains the following materials:

Notebooks:
1. pre-train.ipynb - training stage 1 for weight initialization.
2. dl-project-training.ipynb - training stage 2 for training and generalization.
3. dl-project-evaluation.ipynb - evaluation of labeled FCD subject on an MAE trained on healthy subjects.

Datasets:
1. T1W images were taken from an open MRI dataset published on https://openneuro.org/datasets/ds004199/versions/1.0.6, and are also available on Kaggle at https://www.kaggle.com/datasets/almadavidson1/fcd-database.
2. Initial weights for training stage 2 and evaluation are available on https://www.kaggle.com/datasets/almadavidson/pretrained-weights.
3. Results for the evaluation step are under the folder "DL_Project_Evaluation_Output".
