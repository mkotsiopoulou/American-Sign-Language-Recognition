# American Sign Language Recognition
A deep learning project for the recognition of American Sign Language (ASL) hand gestures using Convolutional Neural Networks (CNNs). The project investigates the impact of different batch sizes and data augmentation techniques on classification performance. The complete workflow is documented through a Quarto report and implemented using TensorFlow/Keras.

---

# Project Overview
The objective of this project is to develop a Convolutional Neural Network capable of accurately classifying static images of American Sign Language gestures. Six different experiments were conducted by combining three batch sizes with two training strategies (with and without data augmentation). Each model was evaluated using Accuracy, Precision, Recall and F1-score, while the best-performing model was further analyzed using training curves and a confusion matrix.

---

# Methodology
The workflow followed in this project consists of the following stages:
- Loading and inspecting the dataset.
- Verifying image dimensions and class distribution.
- Splitting the dataset into training and testing subsets.
- Designing a custom CNN architecture.
- Training six different CNN models.
- Evaluating each model using standard classification metrics.
- Comparing experimental results.
- Selecting and analyzing the best-performing model.
- Generating a complete Quarto report.

---

# Sample Results
The best-performing model achieved:
| Metric | Value |
|--------|-------:|
| Accuracy | **92.57%** |
| Precision | **92.61%** |
| Recall | **92.57%** |
| F1-score | **92.54%** |

The repository also includes:
- Performance comparison of all experiments.
- Training and validation accuracy curves.
- Training and validation loss curves.
- Confusion matrix of the best-performing model.
- Fully reproducible Quarto report.

---

# Technologies
- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Quarto
- Jupyter Notebook

---

# Dataset
The project uses the **27 Class Sign Language Dataset** developed by Arda Mavi and Zeynep Dikle.
The dataset contains **22,801 RGB images** of **27 American Sign Language gesture classes**, collected from **173 volunteers** under different lighting conditions, backgrounds and camera angles. Each image has a resolution of **128 × 128 pixels**.

**Dataset:**  [27 Class Sign Language Dataset](https://www.kaggle.com/datasets/ardamavi/sign-language-digits-dataset)

**Related paper:**  [A New 27 Class Sign Language Dataset Collected from 173 Individuals](https://arxiv.org/abs/2203.03859)

**Dataset characteristics**
- 27 classes
- 22,801 RGB images
- Image resolution: **128 × 128 pixels**
- Alphabet letters (A–Z) and Space

---

# Applications
Potential applications include:
- Sign language recognition systems
- Human–Computer Interaction (HCI)
- Accessibility technologies
- Educational tools
- Computer vision research
