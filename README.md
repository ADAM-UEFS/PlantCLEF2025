# PlantCLEF 2025

This repository keeps the code required for attempting to **PlantClef 2025 challenge**.

Challenge's details are available [here](https://www.kaggle.com/competitions/plantclef-2025).

---

# Proposal


## Results

We were able to achieve challenge's **5th position** with a score of **0.33331**, only **0.03148** behind the first position.

---

# Usage

## Environment

Our whole project was build using **Python**, mainly **PyTorch**.

More details about required packages and their versions are available on **requirements.txt**.


## Scripts

We have splitted the training into three different scripts:

- `run_feature_extraction.sh`: extracts the features from the images containing a single plant sample
- `run_kmeans.sh`: clusters the extracted features into **7806 clusters** one for each specie in the dataset
- `run_zero_shot.sh`: trains a narrow ViT to predict the feature vector

The scripts mentioned above should be called in the same order they are listed.

---

# Acknowledgements

---