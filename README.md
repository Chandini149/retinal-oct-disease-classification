# Retinal OCT Disease Classification Using Transfer Learning

This project develops a deep learning pipeline for retinal Optical Coherence Tomography (OCT) disease classification. The goal is to classify OCT B-scan images into four categories: CNV, DME, DRUSEN, and NORMAL using transfer learning models.

The project was designed as a practical AI-based ophthalmology workflow, including OCT image preprocessing, class imbalance handling, model benchmarking, performance evaluation, and explainability using Grad-CAM.

## Project Motivation

Retinal OCT imaging is widely used in ophthalmology to assess retinal disease patterns. This project demonstrates how transfer learning can be applied to OCT image classification and evaluated using clinically relevant metrics such as class-wise recall, macro-F1 score, ROC-AUC, and confusion matrix analysis.

## Dataset

The dataset is not included in this repository due to size.

Dataset used: **Retinal OCT Images / OCT2017**  
Kaggle dataset: `paultimothymooney/kermany2018`

The dataset contains OCT images organized into the following classes:

- CNV
- DME
- DRUSEN
- NORMAL

Expected local folder structure:

```text
data/
  OCT2017/
    OCT2017/
      train/
        CNV/
        DME/
        DRUSEN/
        NORMAL/
      test/
        CNV/
        DME/
        DRUSEN/
        NORMAL/
      val/
        CNV/
        DME/
        DRUSEN/
        NORMAL/
