# customer-churn-prediction

# 📊 Customer Churn Prediction Using Machine Learning

This project aims to predict whether a customer will churn (leave a service) based on their demographics and usage behavior. The project uses a supervised machine learning approach with the **Random Forest Classifier** to build the prediction model.

---

## ✅ Project Objective

To identify customers who are likely to stop using the service by training a classification model on historical customer data.

---

## 📂 Dataset

- **Name**: Telco Customer Churn
- **Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Features**: Customer account information, service usage, demographic details
- **Target**: `Churn` (Yes/No)

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

---

## 🔧 Steps Performed

### 1. Import Required Libraries  
All necessary Python libraries were imported for data manipulation, visualization, and modeling.

### 2. Load the Dataset  
Dataset was loaded using `pandas` and basic information was explored.

### 3. Data Exploration  
Performed EDA (Exploratory Data Analysis) using `describe()`, `info()`, and visualized churn distribution.

### 4. Data Cleaning  
- Dropped unnecessary columns like `customerID`
- Converted `TotalCharges` to numeric
- Removed missing values

### 5. Encode Categorical Variables  
- Used `LabelEncoder` to encode the `Churn` column
- Used `get_dummies()` to handle categorical features

### 6. Split Data  
Used `train_test_split()` to split data into training and testing sets (80:20 ratio).

### 7. Feature Scaling  
Applied `StandardScaler` to normalize feature values.

### 8. Model Training  
Trained a `RandomForestClassifier` on the training data.

### 9. Model Evaluation  
Evaluated performance using:
- Accuracy Score
- Confusion Matrix
- Classification Report

### 10. Feature Importance  
Visualized the top features influencing churn using a bar graph of feature importances.

---

## 📈 Results

- Model Accuracy: **~X%** (fill in your result after testing)
- Top features contributing to churn were visualized.

---

## 📌 How to Run the Project

1. Clone the repository  


2. Navigate to the folder  


3. Run the Jupyter notebook  


---

## 💡 Future Improvements

- Try other models like XGBoost or Logistic Regression
- Hyperparameter tuning for better accuracy
- Build a Streamlit app to serve predictions

---

## 👨‍💻 Author

**Kedar** – Final Year Engineering Student | DevOps & ML Enthusiast  
Feel free to connect on [LinkedIn](www.linkedin.com/in/kedar-pattanshetti-565921325

)

