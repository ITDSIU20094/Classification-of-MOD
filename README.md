# Mouth and Oral Disease Classification using InceptionResNetV2

This project is a **Deep Learning** implementation for classifying 7 types of mouth and oral diseases using the **InceptionResNetV2** model. The project is based on the scientific paper "Mouth and oral disease classification using InceptionResNetV2 method". The model achieves exceptionally high accuracy, demonstrating significant potential for assisting in medical diagnosis.

## 📂 Repository Structure

Below is the structure of this repository:

```
.
├── .ipynb_checkpoints/
├── Image/                  # Contains images for testing the model's predictions
├── Teeth_Dataset/          # The organized dataset folder
│   ├── Training/
│   ├── Validation/
│   └── Testing/
├── Mouth_and_Oral_Diseases_(MOD).ipynb  # The main notebook with all the source code
├── README.md             
├── Teeth_Dataset-20250624T164231Z-1-001.zip # The original zipped dataset
└── inceptionresnetv2_teeth.pth          # The trained model weights
```

## 📝 Project Overview

The goal of this project is to build an automated system capable of accurately classifying 7 distinct oral diseases from clinical images. The core technique is **Transfer Learning**, utilizing the InceptionResNetV2 model pre-trained on the ImageNet dataset.

[cite_start]The diseases targeted for classification are[cite: 599, 2440]:
1.  [cite_start]**CaS** (Canker Sores) [cite: 600]
2.  [cite_start]**CoS** (Cold Sores) [cite: 601]
3.  [cite_start]**Gum** (Gangivostomatitis) [cite: 602]
4.  [cite_start]**MC** (Mouth Cancer) [cite: 603]
5.  [cite_start]**OC** (Oral Cancer) [cite: 604]
6.  [cite_start]**OLP** (Oral Lichen Planus) [cite: 605]
7.  [cite_start]**OT** (Oral Thrush) [cite: 606]
