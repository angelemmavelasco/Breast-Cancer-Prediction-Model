# Breast Cancer Prediction Model

## Introduction
According to the World Health Organization (WHO), “Breast cancer is the most common cancer among women worldwide, impacting 2.3 million women each year and causing 670,000 deaths in 2022.” (World Health Organization, 2024).  
This emphasizes the critical importance of early detection and reliable diagnostic tools. Machine learning techniques can support healthcare professionals by providing accurate classification systems to distinguish between benign and malignant tumors.

## Project Description
This repository contains a complete data science workflow applied to the Breast Cancer Wisconsin (Diagnostic) dataset. The primary goal of this project is to develop and evaluate machine learning models capable of classifying tumors as benign or malignant, based on clinical features extracted from breast cell nuclei.

## Objectives
- Explore and clean the dataset to ensure data quality.  
- Perform feature scaling and dimensionality reduction using Principal Component Analysis (PCA).  
- Apply resampling techniques (SMOTE) to address class imbalance and improve recall for malignant cases.  
- Evaluate models using metrics such as accuracy, precision, recall, F1-score, confusion matrix, and ROC-AUC.  
- Focus the analysis on minimizing false negatives, as these represent the most critical risk in medical diagnosis.  

## Results
The experiments demonstrate that:
- Resampling significantly improved the recall for malignant cases, reducing the number of false negatives.  
- Final metrics reached approximately 95% accuracy, with balanced precision and recall across both classes.  

## Conclusion
This project highlights how data preprocessing, class balancing, and careful model evaluation are key to building reliable predictive models in healthcare. By prioritizing the detection of malignant cases, the analysis reflects the practical considerations of medical diagnosis, where avoiding missed cancer cases is more important than overall accuracy.

---

## References
World Health Organization. (2024, March 13). Breast cancer. Retrieved from https://www.who.int/es/news-room/fact-sheets/detail/breast-cancer

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/angelmmavelasco/Breast-Cancer-Prediction-Model.git
