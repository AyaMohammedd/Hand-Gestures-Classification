# Hand Gesture Recognition using Machine Learning

This project performs hand gesture recognition using 2D landmark coordinates extracted from hand images. The pipeline includes data preprocessing, visualization, model training using various ML algorithms, and performance evaluation.

## 📁 Dataset

- Input: CSV file containing hand landmark positions (`x1, y1, ..., x21, y21`) and gesture labels.
- Source: Generated using [MediaPipe](https://google.github.io/mediapipe/) (assumed).

## 🔍 Project Highlights

- 📊 **Data Visualization**: Plots of sample hand gestures with joint connections.
- 🧼 **Preprocessing**: Standard scaling and label encoding.
- 🤖 **Models Used**:
  - Random Forest
  - Support Vector Machine (SVM)
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - XGBoost Classifier
- 🔧 **Tuning**: GridSearchCV and RandomizedSearchCV for hyperparameter optimization.
- 💾 **Model Saving**: Trained models saved using `pickle` and `joblib`.

## 📈 Evaluation

- Accuracy and classification reports used for evaluation.
- Training and testing scores are printed for comparison.

## 🚀 How to Run

1. Clone the repo
2. Install dependencies
3. Run the Jupyter notebook:
   ```bash
   jupyter notebook Hand_gesture_project.ipynb



  Drive_link_for_project : https://drive.google.com/drive/folders/1dIFdLO22btfvV5G5CjVAoJ6WFJeL59tm
