# ASD Detection Using Deep Learning
### An Explainable Deep Learning Framework for Autism Spectrum Disorder Detection from Facial Images

## Overview

This repository contains the experimental implementation of an undergraduate research project focused on Autism Spectrum Disorder (ASD) detection from facial images using deep learning techniques.

The project investigates different deep learning architectures, including Convolutional Neural Networks (CNNs) and Vision Transformers, to evaluate their performance in image-based ASD classification.

It also explores Explainable Artificial Intelligence (XAI) using Gradient-weighted Class Activation Mapping (Grad-CAM) to visualize image regions contributing to model predictions.

## Research Objectives

- Investigate deep learning approaches for ASD detection from facial images.
- Compare the performance of different CNN architectures and Vision Transformers.
- Evaluate transfer learning approaches for image classification.
- Explore model interpretability using Grad-CAM.
- Develop an explainable framework for examining model predictions.

## Dataset

The experiments were conducted using a facial image dataset containing:

| Dataset | Number of Images |
|---|---:|
| Training | 2,542 |
| Validation | 100 |
| Testing | 300 |
| **Total** | **2,942** |

## Deep Learning Architectures

The following architectures were investigated:

1. AlexNet
2. DenseNet121
3. MobileNetV2
4. MobileNetV3-Large
5. RegNetY-800MF
6. Vision Transformer (ViT-B/16)

## Experimental Results

Among the evaluated architectures, RegNetY-800MF achieved the best experimental performance.

| Evaluation Metric | Result |
|---|---:|
| Accuracy | 93% |
| Precision | 93% |
| Recall | 93% |
| F1-Score | 93% |
| AUC | 0.9679 |

**Best-performing architecture:** RegNetY-800MF

These results represent performance on the experimental dataset and do not establish clinical diagnostic validity.

## Explainable Artificial Intelligence

Grad-CAM was used to visualize the regions of facial images that contributed to the model's predictions.

This provides an additional perspective on model behavior and supports the interpretation of image classification results.

## Technologies and Tools

- **Programming Language:** Python
- **Deep Learning Framework:** PyTorch
- **Computer Vision:** TorchVision
- **Data Processing:** NumPy, Pandas
- **Image Processing:** OpenCV, Pillow
- **Model Evaluation:** Scikit-learn
- **Visualization:** Matplotlib, Seaborn
- **Explainability:** Grad-CAM
- **Development Environment:** Google Colab, Jupyter Notebook

## Repository Structure

```text
ASD-Detection-Deep-Learning/
│
├── ASD_Detection.ipynb
├── AlexNet.ipynb
├── DesNet121.ipynb
├── MobileNet_V2.ipynb
├── MobileNet_V3_Large_.ipynb
├── RegNetY_800MF.ipynb
├── ViT_B_16.ipynb
│
└── README.md
```

Each notebook contains the implementation and experiments associated with the corresponding architecture.

## How to Run

**1. Clone the repository**

```bash
git clone https://github.com/Hasibur02/ASD-Detection-Deep-Learning.git
```

**2. Navigate to the project directory**

```bash
cd ASD-Detection-Deep-Learning
```

**3. Open the notebooks**

The notebooks can be opened using Jupyter Notebook or Google Colab.

**4. Prepare the dataset**

Configure the dataset paths according to the directory structure expected by each notebook.

**5. Run the experiments**

Execute the notebook cells to perform model training, evaluation, and analysis.

## Research Status

- Undergraduate research project: Completed
- Model implementation and experimentation: Completed
- Research manuscript: Preparation ongoing
- Journal/Conference publication: Not yet submitted

## Related Application

**AutiSense – Android Application**

An Android application developed to demonstrate the research framework.

Repository: https://github.com/Hasibur02/AutiSense

## Author

**Md. Hasibur Rahman**  
B.Sc. in Computer Science & Engineering  
Shyamoli Engineering College, University of Dhaka

GitHub: https://github.com/Hasibur02  
LinkedIn: https://linkedin.com/in/hasibur-rahman-a57a74428

## Research Supervisor

**Golam Rabbi Hasan**  
Lecturer, Department of Computer Science & Engineering  
Shyamoli Engineering College

## Disclaimer

This project is an academic research initiative. The experimental framework is not a clinically validated diagnostic tool and should not be used for medical diagnosis or clinical decision-making.
