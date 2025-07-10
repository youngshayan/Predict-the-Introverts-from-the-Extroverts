## 🧠 Personality Prediction: Introvert vs Extrovert

This project aims to predict whether a person is an **Introvert** or **Extrovert** based on their social behavior and personality traits using machine learning techniques.

### 📌 Objective

Build a classification model that analyzes various social behavior indicators (e.g., time spent alone, frequency of going outside, stage fear, etc.) and predicts personality type (Introvert/Extrovert).

### 🛠️ Technologies & Tools

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn (RandomForestClassifier, LabelEncoder, train\_test\_split, classification\_report)

### 📂 Project Structure

* `train.csv` – Labeled dataset used to train the model
* `test.csv` – Unlabeled dataset used to generate predictions
* `Prediction.ipynb` – Main notebook for data cleaning, model training, evaluation, and prediction
* `submission.csv` – Final predictions (Introvert/Extrovert) on the test set

### 🔍 Key Steps

* Handled missing data using median imputation
* Encoded target labels using LabelEncoder
* Trained a Random Forest model with train/validation split
* Evaluated model performance with precision, recall, F1-score
* Achieved \~96% accuracy with cross-validation
* Generated personality predictions for test dataset

### 🚀 Output

Accurate prediction of whether a person is an introvert or extrovert based on behavior-related features.

<img width="1562" height="792" alt="image" src="https://github.com/user-attachments/assets/badb0896-fb72-4946-969f-0d4af42fb311" />

