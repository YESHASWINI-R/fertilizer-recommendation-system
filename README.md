# 🌱 Fertilizer Recommendation System using Machine Learning

This project predicts the most suitable fertilizer based on soil and environmental conditions using Machine Learning algorithms.
The system helps recommend fertilizers by analyzing factors such as temperature, humidity, moisture, and soil nutrient values.

The project was implemented using:

* Random Forest Classifier
* XGBoost Classifier

and compares both models to select the best-performing one.

---

## 📌 Project Objective

The main goal of this project is to build an intelligent fertilizer recommendation system that can assist in improving agricultural productivity and fertilizer management.

The model predicts the appropriate fertilizer using:

* Soil conditions
* Crop information
* Nutrient levels
* Environmental factors

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Matplotlib
* Seaborn
* Joblib
* Google Colab

---

## 📂 Dataset Information

Dataset used:

[Fertilizer Recommendation Dataset](https://www.kaggle.com/datasets/jshndeep/fertilizer-recommendation?utm_source=chatgpt.com)

### Dataset Features

| Feature         | Description            |
| --------------- | ---------------------- |
| Temparature     | Temperature level      |
| Humidity        | Humidity percentage    |
| Moisture        | Soil moisture          |
| Soil Type       | Type of soil           |
| Crop Type       | Type of crop           |
| Nitrogen        | Nitrogen value         |
| Potassium       | Potassium value        |
| Phosphorous     | Phosphorous value      |
| Fertilizer Name | Recommended fertilizer |

---

## 📊 Exploratory Data Analysis

Performed:

* Missing value checking
* Fertilizer distribution analysis
* Correlation heatmap visualization
* Feature inspection

The dataset did not contain missing values.

---

## ⚙️ Data Preprocessing

The following preprocessing steps were applied:

* Column name cleaning
* Handling numeric values
* Label Encoding for fertilizer names
* Train-Test Split
* Feature Scaling using `StandardScaler`

### Training/Test Split

* 80% Training Data
* 20% Testing Data

---

# 🤖 Machine Learning Models

## 🌳 Random Forest Classifier

### Accuracy

✅ **100%**

The Random Forest model achieved perfect classification accuracy on the test dataset.

---

## ⚡ XGBoost Classifier

### Accuracy

✅ **100%**

The XGBoost model also achieved perfect accuracy.

---

## 🏆 Best Model Selected

After comparison, the system selected:

```text id="g7q3np"
XGBoost
```

as the final model.

---

## 📈 Model Evaluation

Evaluation metrics used:

* Accuracy Score
* Classification Report
* Confusion Matrix

Both models showed excellent performance on the dataset.

---

## 💾 Saved Files

The trained files were saved using Joblib:

```bash id="f4v9sx"
fertilizer_recommendation_model.pkl
fertilizer_label_encoder.pkl
fertilizer_scaler.pkl
```

These files can later be reused for deployment and real-time predictions.

---

## 🧪 Sample Prediction

### Input

```python id="m1k8wp"
[30, 70, 40, 50, 30, 20]
```

### Output

```text id="t8z2la"
Recommended Fertilizer: Urea
```

---

## ▶️ How to Run the Project

### 1️⃣ Install Required Libraries

```bash id="x0s6wr"
pip install pandas numpy scikit-learn xgboost matplotlib seaborn joblib kaggle
```

### 2️⃣ Upload Kaggle API File

Upload your `kaggle.json` file in Google Colab.

### 3️⃣ Run the Notebook

Execute all notebook cells step by step.

---

## 🔄 Project Workflow

```text id="w5k2rz"
Dataset Collection
        ↓
Data Cleaning
        ↓
Exploratory Data Analysis
        ↓
Feature Scaling
        ↓
Model Training
        ↓
Model Comparison
        ↓
Fertilizer Recommendation
```

---

## 🚀 Future Improvements

* Build a web application using Flask or Streamlit
* Add real-time soil sensor integration
* Weather API integration
* Mobile application for farmers
* Deep Learning-based fertilizer recommendation

---

## 👩‍💻 Developed By

**Yeshaswini R**
---

## ⭐ GitHub

If you found this project useful, consider giving the repository a star ⭐
