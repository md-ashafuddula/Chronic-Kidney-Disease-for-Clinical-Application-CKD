# Intelligent CKD Diagnostic System

Our work on CKD entitled [An Intelligent Diagnostic System to Analyze Early‐Stage Chronic Kidney Disease for Clinical Application](https://onlinelibrary.wiley.com/doi/full/10.1155/2023/3140270) published in a reputable journal "Applied Computational Intelligence and Sot Computing (IF: 3.88)" in 2023, we decided to share the code and data we used for this experiment.

## Abstract

Chronic kidney disease (CKD) is a progressive condition characterized by the gradual deterioration of kidney functions, potentially leading to kidney failure if not promptly diagnosed and treated. Machine learning (ML) algorithms have shown signifcant promise in disease diagnosis, but in healthcare, **clinical data pose challenges:** missing values, noisy inputs, and redundant features, afecting early-stage CKD prediction. Thus, **this study presents** a novel, fully automated machine learning approach to tackle these complexities by incorporating **feature selection (FS) and feature space reduction (FSR) techniques**, leading to a substantial enhancement of the model’s performance. A data balancing technique is also employed during preprocessing to address data imbalance issue that is commonly encountered in clinical contexts. Finally, for reliable CKD classifcation, an ensemble characteristics-based classifer is encouraged. Te efectiveness of our approach is rigorously validated and assessed on multiple datasets, and the clinical relevancy of the strategy is evaluated on the real-world therapeutic data collected from Bangladeshi patients. This study establishes the dominance of adaptive boosting, logistic regression, and passive aggressive ML classifers with **96.48% accuracy in forecasting unseen therapeutic CKD data, particularly in early-stage cases**. Furthermore, the efectiveness of the **FSR technique in reducing the prediction time signifcantly** is revealed. The outstanding performance of the proposed model demonstrates its efectiveness in addressing the complexity of healthcare CKD data by incorporating the FS and FSR techniques. This highlights its potential as a promising computer aided diagnosis tool for doctors, enabling early interventions and improving patient outcomes.

## Major Contributions:

1. The datasets are analyzed to ensure that no data loss occurs, even in the case of missing value.
2. The dimension reduction methodology is investigated in order to reduce the feature space; as a result, the model training and testing time could be reduced while simultaneously improving the overall results.
3. This study presented a generalized intelligent diagnostic system to analyze and predict renal disease at an early stage with unseen healthcare data. To the best of our knowledge, this is the frst work on CKD prediction with clinical unseen data.
4. A comprehensive analysis was performed on four diferent datasets **(i.e. CKD-15, CKD-21, Hybrid and Unseen cases)** to find the best ML models for CKD analysis.
5. Adaptive boosting, logistic regression, and passive aggressive techniques are recommended classifers for CKD analysis on unseen real-life data due to their robust ensemble capabilities.

## Model Design

Proposed intelligent system for clinically early-stage chronic kidney disease diagnosis.<img width="609" alt="image" src="https://github.com/user-attachments/assets/cb302820-294f-4ed6-a5d5-043027a5b76d">

## Result

Average train-test accuracy (%) comparison of ML models using PCA on chronic kidney disease data.<img width="649" alt="image" src="https://github.com/user-attachments/assets/5fe42fc2-d0e7-44f0-bfec-3424d0c8533b">

Experimental result analysis for clinical unseen dataset, i.e., training the model with CKD-15 and testing with CKD-21.<img width="847" alt="image" src="https://github.com/user-attachments/assets/2e2df373-fc22-4e34-aec0-ae40d5be0b58">

## Time reduction

Average model processing time comparison for the proposed model with and without PCA<img width="853" alt="image" src="https://github.com/user-attachments/assets/888f3426-b305-47be-bda6-a0e1158ec775">

## Reference Paper

We use the dataset from [UCI Machine Learning Repository](https://archive.ics.uci.edu/datasets)
1. [CKD-15](https://archive.ics.uci.edu/dataset/336/chronic+kidney+disease)
2. [CKD-21](https://archive.ics.uci.edu/dataset/857/risk+factor+prediction+of+chronic+kidney+disease)

**Please cite our paper:**

```
@article{md2023intelligent,
  title={An Intelligent Diagnostic System to Analyze Early-Stage Chronic Kidney Disease for Clinical Application},
  author={Md. Ashafuddula, NI and Islam, Bayezid and Islam, Rafiqul},
  journal={Applied Computational Intelligence and Soft Computing},
  volume={2023},
  number={1},
  pages={3140270},
  year={2023},
  publisher={Wiley Online Library}
}
```
