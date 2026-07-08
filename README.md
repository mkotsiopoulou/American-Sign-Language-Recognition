# American Sign Language Recognition
A deep learning project for recognizing American Sign Language (ASL) hand gestures using Convolutional Neural Networks (CNNs). The project investigates the impact of different batch sizes and data augmentation techniques on classification performance through multiple experimental configurations. The complete workflow is implemented using TensorFlow/Keras and documented in an interactive Quarto report.

---

# Project Overview
The objective of this project is to develop a Convolutional Neural Network capable of accurately recognizing American Sign Language (ASL) hand gestures from RGB images.
To evaluate the performance of the proposed approach, six experimental configurations were developed by combining three different batch sizes with two training strategies (with and without data augmentation). The trained models were compared using Accuracy, Precision, Recall and F1-score, while the best-performing model was further analyzed through training curves and a confusion matrix.
The project follows a complete deep learning workflow, including data preprocessing, model development, performance evaluation and result visualization.

---

# Methodology
The project follows the standard deep learning pipeline:
1. Dataset loading and inspection.
2. Image preprocessing and normalization.
3. Dataset splitting into training and testing sets.
4. Design and implementation of a custom CNN architecture.
5. Training multiple CNN models under different experimental settings.
6. Performance evaluation using Accuracy, Precision, Recall and F1-score.
7. Comparison of all experimental configurations.
8. Selection and detailed analysis of the best-performing model.
9. Generation of a fully documented Quarto report.

---

# Dataset
This project uses the **27 Class Sign Language Dataset**, publicly available on Kaggle.
The dataset consists of **22,801 RGB images** belonging to **27 American Sign Language gesture classes**, collected from **173 volunteers** under different lighting conditions, camera angles and backgrounds.

**Dataset characteristics**
- 22,801 RGB images
- 27 gesture classes
- Image resolution: **128 × 128 pixels**
- NumPy format (`X.npy`, `Y.npy`)

**Dataset:** [27 Class Sign Language Dataset](https://www.kaggle.com/datasets/ardamavi/27-class-sign-language-dataset)

**Reference Paper:** [A New 27 Class Sign Language Dataset Collected from 173 Individuals](https://arxiv.org/abs/2203.03859)

---

# Sample Results
The best-performing CNN model achieved the following classification performance:
| Metric | Value |
|:-------|------:|
| Accuracy | **92.57%** |
| Precision | **92.61%** |
| Recall | **92.57%** |
| F1-score | **92.54%** |

The repository also includes:
- Performance comparison across all experiments.
- Training and validation accuracy curves.
- Training and validation loss curves.
- Confusion matrix of the best-performing model.
- Complete Quarto report documenting the experimental workflow.

### Training & Validation Accuracy
![Training Accuracy](results/best_model_accuracy.png)

### Training & Validation Loss
![Training Loss](results/best_model_loss.png)

### Confusion Matrix
![Confusion Matrix](results/best_model_confusion_matrix.png)

---

# Technologies
- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- Quarto

---

# Applications
This project demonstrates how deep learning can be applied to image-based sign language recognition and similar computer vision problems.


Potential applications include:
- Sign language recognition systems
- Human–Computer Interaction (HCI)
- Accessibility technologies
- Educational tools
- Computer vision research
