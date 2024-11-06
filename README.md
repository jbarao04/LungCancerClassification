# Lung Nodule Classification 

Made by: 

- [Filipe Barros](https://github.com/filipeazuil)
- [Joao Barao](https://github.com/jbarao04)
- [Goncalo Arrobas](https://github.com/Garrobas)



### Project Overview
In this project our goal is to develop a Data Science-based solution to solve the problem of Lung Cancer Classification using Computerized Tomography (CT) Data. Lung cancer remains one of the most critical health challenges, and early, accurate detection plays a key role in improving patient outcomes. By leveraging machine learning models, this project aims to differentiate between benign and malignant lung nodules based on CT data.

### Data
The dataset consists of CT scan images from 1,010 patients. Each scan image includes detailed visual information that enables us to identify patterns associated with malignancy. Using feature extraction methods, we transform these images into a structured dataset, allowing for efficient analysis and model training.

# Project Roadmap
### 1. Feature Extraction
Notebook: FeatureExtraction - CNN3D.ipynb

Description: This notebook focuses on extracting features from CT scan images using a 3D Convolutional Neural Network (3D CNN). The 3D CNN processes the spatial structure of CT scan volumes, allowing us to capture detailed spatial features that are critical for distinguishing between benign and malignant nodules.

### 2. Data Cleaning and Feature Selection
Notebook: LungCancerClassification.ipynb

Description: After feature extraction, this step involves cleaning the dataset to handle missing values, outliers, and other inconsistencies. We also use feature selection techniques like PCA and t-tests to identify the most relevant features for classification.

### 3. Model Implementation and Evaluation
Notebook: LungCancerClassification.ipynb

Description: This notebook includes the implementation of machine learning models, including SVM, Random Forest, and an ensemble model. Hyperparameter tuning with Grid Search and model evaluation are also performed here, prioritizing sensitivity for accurate detection of malignant cases.

### 4. Results
Notebook: LungCancerClassification.ipynb

Description: The final results are analyzed and visualized, with a focus on metrics like AUC, sensitivity, and specificity. This step highlights the model’s effectiveness in distinguishing between benign and malignant nodules.

# Requirements

To install the requirements, run:

```bash
pip install -r requirements.txt
```

# References
- Liu, L., Liu, Y., & Zhao, H. (2018). Benign and malignant solitary pulmonary nodules classification based on CNN and SVM. *ACM International Conference Proceeding Series*.

- Xie, Y., Zhang, J., Xia, Y., Fulham, M., & Zhang, Y. (2018). Fusing texture, shape and deep model-learned information at decision level for automated classification of lung nodules on chest CT. *Information Fusion*.

- Torres, G. (2023). Prediction of Malignancy in Lung Cancer using several strategies for the fusion of Multi-Channel Pyradiomics Images. *EasyChair - PrePrint*.

- Shen, W., Zhou, M., Yang, F., Yang, C., & Tian, J. (2015). Multi-scale convolutional neural networks for lung nodule classification. In *Lecture Notes in Computer Science (including subseries Lecture Notes in Artificial Intelligence and Lecture Notes in Bioinformatics)*.

- Bak, S.H., Lee, H.Y., Lee, G., & Park, H. (2018). Radiomics in lung cancer from basic to advanced: Current status and future directions. *Korean Journal of Radiology*.

- Causey, J.L., Zhang, J., Ma, S., Jiang, B., Qualls, J.A., Politte, D.G., Prior, F., Zhang, S., & Huang, X. (2018). Highly accurate model for prediction of lung nodule malignancy with CT scans. *Scientific Reports*.

- Kumar, D., Wong, A., & Clausi, D. A. (2015). Lung nodule classification using deep features in CT images. Conference on Computer and Robot Vision, 133-138

- Dunn, B., Pierobon, M., & Wei, Q. (2023). Automated Classification of Lung Cancer Subtypes Using Deep Learning and CT-Scan Based Radiomic Analysis. Bioengineering, 10(690).

- Hesse, L.S., de Jong, P.A., Pluim, J.P.W., & Cheplygina, V. (2020). Primary Tumor Origin Classification of Lung Nodules in Spectral CT using Transfer Learning.

- S.P. Morozov, A.E. Andreychenko, N.A. Pavlov, A.V. Vladzymyrskyy, N.V. Ledikhova, V.A. Gombolevskiy, I.A. Blokhin, P.B. Gelezhe, A.V. Gonchar, V.Yu. (2020) CherninaMosMedData: Chest CT Scans with COVID-19 Related Findings Dataset.





