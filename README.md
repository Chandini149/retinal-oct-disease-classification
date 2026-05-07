\# Retinal OCT Disease Classification Using Transfer Learning



This project develops a retinal OCT disease classification pipeline using transfer learning to classify OCT B-scan images into CNV, DME, DRUSEN, and NORMAL categories.



\## Models

\- MobileNetV2

\- EfficientNetB0



\## Methods

\- OCT image preprocessing

\- Transfer learning

\- Data augmentation

\- Class-weighted loss for imbalance handling

\- Model evaluation using accuracy, macro-F1, precision, recall, ROC-AUC, and confusion matrix

\- Grad-CAM explainability for model interpretation



\## Results



| Model | Accuracy | Macro-F1 | ROC-AUC |

|---|---:|---:|---:|

| MobileNetV2 | 81.9% | 82% | 97.2% |

| EfficientNetB0 | 83.7% | 84% | 97.6% |



EfficientNetB0 achieved the best overall performance and was selected for Grad-CAM explainability analysis.



\## Dataset



The dataset is not included in this repository due to size.  

Download the OCT2017 dataset from Kaggle:



`paultimothymooney/kermany2018`



Expected local structure:



```text

data/

&#x20; OCT2017/

&#x20;   OCT2017/

&#x20;     train/

&#x20;     test/

&#x20;     val/

