
---

## Breast Cancer Classification Using SVM and MLP

### Project Overview
This repository hosts two separate but related projects aimed at classifying breast cancer as benign or malignant using different machine learning models. The first project employs Support Vector Machine (SVM) techniques combined with feature extraction methods to classify histopathological images of breast tissues. The second project uses a Multilayer Perceptron (MLP), an artificial neural network, to analyze and classify breast cancer from X-ray images. Both projects emphasize feature selection, preprocessing, model training, and evaluation to achieve high classification accuracy.

### SVM Classification Approach
- **Data Processing**: Images were preprocessed using grayscale conversion and Gaussian blur to enhance feature extraction.
- **Feature Extraction**: Utilized shape and texture information, calculating metrics such as area, perimeter, and texture contrasts.
- **Feature Selection**: Recursive Feature Elimination (RFE) with an SVM was used to identify the most predictive features.
- **Normalization and Evaluation**: Features were normalized using Min-Max scaling. The model's performance was evaluated using confusion matrices and classification reports.

### MLP Classification Approach
- **Data Collection and Preprocessing**: Features were extracted from X-ray images and labeled as malignant or benign.
- **Feature Selection**: Used chi-squared tests within the SelectKBest method to determine the most relevant features.
- **Normalization and Model Building**: Applied Min-Max scaling. The MLP model included multiple layers with configurations optimized through hyperparameter tuning.
- **Results and Evaluation**: Performance was measured using precision, recall, and F1-score metrics detailed in a comprehensive evaluation section.

### Common Goals
Both projects aim to:
- Improve the accuracy and reliability of breast cancer diagnosis.
- Provide detailed analyses of model performances.
- Offer insights into the importance of specific features in breast cancer diagnosis.

### Technologies Used
- Python
- Libraries: OpenCV, SciKit-Learn, Pandas, NumPy
- Machine Learning Models: SVM, MLP
