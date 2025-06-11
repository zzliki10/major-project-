# major-project-
Medical PPE detection and Verification system 
# Smart PPE Detection System

This repository contains the initial prototype files for a Smart PPE (Personal Protective Equipment) Detection System designed to identify whether individuals in a medical lab or industrial setting are wearing proper safety equipment.

## 📁 Project Structure


## 🎯 Project Objective

The objective of this system is to ensure compliance with PPE protocols using computer vision and deep learning techniques. The prototype demonstrates the capability to:

- Detect PPE elements (e.g., gloves, mask, lab coat).
- Use annotated image data to train object detection models.
- Verify dataset format compatibility with COCO standards.

## 🧠 Technologies Used

- Python
- COCO JSON Format
- Computer Vision (Deep Learning based PPE detection model)
- CSV handling for metadata

## 📦 Dataset

The dataset used for training is provided in:

- `ppe_train_coco.json`: Contains labeled image annotations in COCO format.
- `train.csv`: Lists images and potentially related metadata used during training.

> ⚠️ Note: This repository does **not** include the images themselves, only the references and annotations.

## 🚀 Getting Started

To train or test a model using this data:

1. Load the COCO annotations.
2. Pair with the actual image files (not included here).
3. Train using a framework like TensorFlow, PyTorch, or Detectron2.

## 📄 License

This project is part of academic research and is intended for educational use only.

## 🙏 Acknowledgements

- Developed as part of the **Smart PPE Detection and Compliance Verification System** project.
- Academic guidance under the Artificial Intelligence & Machine Learning Department, Cambridge Institute of Technology.


