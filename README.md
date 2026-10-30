# Student Marks Prediction using Machine Learning

Predicts a student's exam score from study hours, sleep hours, attendance and previous marks using Linear Regression.

## Dataset
`student_exam_scores.csv` has 200 students.
- Inputs: hours_studied, sleep_hours, attendance_percent, previous_scores
- Target: exam_score

## What the notebook covers
- Data loading, cleaning and EDA with graphs
- Train/test split (80/20), baseline model and Linear Regression
- Evaluation with MAE, MSE, RMSE and R2, plus confusion matrix and ROC-AUC
- Comparison with Decision Tree and KNN
- K-Means clustering
- Saving the model and predicting marks for a new student

## Results (test data)
- R2 = 0.854
- MAE = 2.31 marks
- RMSE = 2.79 marks
- Linear Regression performed better than Decision Tree and KNN

## How to run
1. Install the libraries: `pip install -r requirements.txt`
2. Start JupyterLab: `jupyter lab`
3. Open `Student_Marks_Prediction.ipynb` and choose Kernel > Restart & Run All

## Limitations
The dataset is small and has only four input features. Predictions are estimates, not guaranteed exam results.
