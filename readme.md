# Project Description
The project was developed during Vesuvius Surface Detection Challenge. The goal was to construct accurate Deep Learning model for segmentation of CT Scans for the facilitation of detecting and deciphering Pompeii Scrolls. - https://www.kaggle.com/competitions/vesuvius-challenge-surface-detection/overview

The project is divided into 2 parts:
- vesuvius analysis which attempts to get a couple of volumes and extract useful information and vesuvius segmentation which utilizes tuned model for a final inference and submission.
- The model was trained on Tesla P100 GPU.

Visualization of example CT Scan we are working with. The folds are easily visible thanks to Napari library for 3d imaging
<img width="1517" height="892" alt="image" src="https://github.com/user-attachments/assets/fc11f4dd-947e-4a00-89fd-5f247f42f1c6" />

Architecture of applied state of the art model - TransUnet
<img width="1063" height="519" alt="image" src="https://github.com/user-attachments/assets/56a686a0-1c8a-4861-a1f8-c2363f60a22d" />

The competition results - The model scores 0.549 on the leaderboard where 0.578 is the best achieveed result. 

The goal of this competition was to better understand state-of-the-art image segmentation models and help decipher ancient scrolls.
