# 🫀Valvular Heart Disease Detection in CAD Dataset

## 📝Classification of Valvular Heart Disease Using Machine Learning Algorithms

In this study, I worked on the classification of Valvular Heart Disease (VHD) types using the **Classification of Coronary Artery Disease** dataset from Kaggle. The dataset was preprocessed to transform the VHD feature into four separate binary columns:

- `VHD_Severe`
- `VHD_Mild`
- `VHD_Moderate`
- `VHD_N`

## 🤖Applied Machine Learning Algorithms

I applied and compared the performance of the following machine learning algorithms:

- **Logistic Regression**
- **Support Vector Regression**
- **Decision Tree**
- **Random Forest**
- **Naive Bayes**
- **k-Nearest Neighbors (kNN)**

## 🔧Metric Enhanced Models

Metric Enhanced SVM Model
In this model, a custom kernel function was created for SVM, combining sigmoid and RBF kernels. SMOTE was used to address class imbalance. The model's performance was evaluated through predictions and performance metrics.

Metric Enhanced kNN Model
In this model, a tangent-based distance metric was used instead of the traditional Euclidean distance for kNN. This new metric accounted for both linear distance and directional differences, leading to more accurate results. Performance evaluations were conducted.

---

## 🎯Objective

The aim of this analysis is to provide insights into the effective detection and classification of VHD types, contributing to early diagnosis and decision support in healthcare. Additionally, this study focuses on the examination, preparation, and cleaning of a dataset, conducting exploratory data analysis, visualizing the data, performing data transformation, and applying statistical analyses to explore relationships between variables. Furthermore, it aims to guide the process of building machine learning models, specifically showing how new kernel functions can be created and integrated into SVM and kNN algorithms.

## 📊Model Evaluation

The models were evaluated using the following performance metrics:

- **Accuracy**
- **True Positives (TP)**
- **True Negatives (TN)**
- **False Positives (FP)**
- **False Negatives (FN)**
- **Sensitivity**
- **Specificity**
- **Precision**
- **F1-Score**

---

## 🔍Results

I calculated the model's performance and results are here:

### VHD_N

![VHD_N](https://github.com/user-attachments/assets/12974cc5-5fa9-4134-bc12-b55f2b141149)

### VHD_mild

![VHD_mild](https://github.com/user-attachments/assets/1ca4cc36-61d0-4be6-ade0-9a539d8448c3)

### VHD_Moderate

![VHD_Moderate](https://github.com/user-attachments/assets/c0e27907-0ae3-4357-8c7e-bc39c028f5bc)

### VHD_Severe

![VHD_Severe](https://github.com/user-attachments/assets/40e3b2e7-dda2-4097-bf6a-39af1ba1fa27)

---

Feel free to explore the repository and check out the code, models, and results for a deeper understanding of the VHD classification process using machine learning.
