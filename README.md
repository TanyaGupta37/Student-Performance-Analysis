# 🎓 Student Performance Analysis & Prediction

## 📌 Overview
This project focuses on analyzing various factors that influence student academic performance and building machine learning models to predict final grades.

The dataset includes demographic, social, and academic attributes of students. Through exploratory data analysis (EDA) and predictive modeling, this project identifies key factors affecting performance and evaluates multiple machine learning algorithms.

---

## 🎯 Objectives
- Analyze the impact of social, academic, and personal factors on student performance  
- Visualize trends and relationships using charts and plots  
- Build and compare multiple machine learning models  
- Identify the most important features influencing final grades (G3)  

---

## 📂 Dataset
- **Source**: Kaggle – Student Performance Dataset  
- **Records**: 649 students  
- **Features**: 33 attributes  

### 🔑 Key Features:
- **Demographic**: age, gender, address  
- **Family Background**: parental education (Medu, Fedu), family support  
- **Lifestyle**: study time, alcohol consumption, absences  
- **Academic**: G1 (1st period), G2 (2nd period), G3 (final grade)  

### 🎯 Target Variable:
- **G3 (Final Grade)**  

---

## 🔍 Exploratory Data Analysis (EDA)

### 📊 Key Analyses Performed:
- Distribution of grades (G1, G2, G3)  
- Study time vs performance  
- Absences vs performance  
- Alcohol consumption vs grades  
- Failures vs grades  
- Correlation heatmap  

### 🔥 Key Insights:
- Previous grades (G1, G2) strongly influence final grade (G3)  
- Students with higher study time tend to perform better  
- High absences negatively affect performance  
- Students aspiring for higher education score significantly higher  
- Weekend alcohol consumption shows slight negative impact  

---

## ⚙️ Feature Engineering
- Created `avg_grade` = (G1 + G2) / 2  
- Created `result` (Pass/Fail classification based on G3)  

---

## 🤖 Machine Learning Models Used
- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  

---

## 📊 Model Evaluation Metrics
- Mean Absolute Error (MAE)  
- Mean Squared Error (MSE)  
- R² Score  

### 🏆 Best Performing Model:
- **Random Forest Regressor** (highest accuracy and stability)  

---

## 📈 Visualizations
- Histograms and count plots  
- Box plots for categorical comparisons  
- Scatter plots for relationships  
- Correlation heatmap  
- Feature importance graph  

---

## 🔑 Key Findings
- Academic history (G1, G2) is the strongest predictor  
- Motivation (higher education aspiration) plays a crucial role  
- Attendance (absences) significantly impacts performance  
- Lifestyle factors (alcohol, social activity) have moderate effects  

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 🚀 Future Improvements
- Hyperparameter tuning for better accuracy  
- Use advanced models (XGBoost, Neural Networks)  
- Perform classification (Pass/Fail prediction)  
- Deploy model using a web app  

---

## 📌 Conclusion
This project demonstrates how data analysis and machine learning can be used to understand and predict student performance. It highlights the importance of academic consistency, motivation, and attendance in achieving better results.

---

## 👩‍💻 Authors
**Tanya Gupta**  
**Khushboo Rajpal** <br>
B.Tech CSE – Machine Learning Project
