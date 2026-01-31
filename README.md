# BREAST-CANCER-PREDICTION-USING-LOGISTIC-REGRESSION
Cancer prediction on Wisconsin Breast Cancer Dataset Using Supervised Learning - Logistic Regression. The model have achieved 94% of accuracy.

This project implements Logistic Regression to classify breast cancer as malignant [0] or benign [1] using the Breast Cancer Wisconsin dataset. 

The model is trained on 80% of the data and tested on 20%. Performance evaluation using accuracy, confusion matrix, and classification report shows high prediction accuracy, demonstrating the effectiveness of logistic regression for medical diagnosis tasks.

**Get the Breast Cancer Wisconsin dataset using below line**

```Python
from sklearn.datasets import load_breast_cancer
Data = load_breast_cancer()
df=pd.DataFrame(Data.data, columns=Data.feature_names)
```
**Model Confusion Matrix Heatmap**

<img width="505" height="470" alt="image" src="https://github.com/user-attachments/assets/9cfd0050-2ea3-499a-8830-01a637e7afca" />

