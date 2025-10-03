# 🎓 Student Score Prediction

This project predicts students' **exam scores** based on various factors such as parental involvement, motivation level, resources, and more.  
We apply **regression models** (Linear, Polynomial) to analyze how different features affect student performance.  

---

## 📂 Project Structure
- `Student_Score_Prediction.ipynb` → Jupyter/Colab notebook with full workflow  
- `data/` → dataset (if provided separately)  
- `README.md` → project documentation  

---

## 🚀 Run in Google Colab
Easily run the notebook in Colab:  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/USERNAME/REPO/blob/main/Student_Score_Prediction.ipynb)

*(replace `USERNAME/REPO` with your GitHub repo path)*  

---

## 🔎 Project Workflow

### 1️⃣ Data Understanding & Cleaning
- Load dataset (`CSV` / provided data).  
- Handle missing values & duplicates.  
- Check data types and perform basic preprocessing.  

### 2️⃣ Feature Engineering
- Encode categorical features (`Label Encoding`, `One-Hot Encoding`).  
- Scale/transform numeric variables.  
- Drop irrelevant or highly correlated columns.  

### 3️⃣ Exploratory Data Analysis (EDA)
- Visualize feature distributions.  
- Correlation heatmaps.  
- Feature-target relationships.  

### 4️⃣ Model Training
- **Linear Regression**  
  - Baseline model  
- **Polynomial Regression**  
  - Test higher-order relationships  
- **Ridge & Lasso Regression**  
  - Regularization for better generalization  

### 5️⃣ Model Evaluation
- Metrics: **Mean Squared Error (MSE)**, **R² Score**  
- Compare models:  
  - Linear Regression: `MSE = ~0.79, R² = ~0.93`  
  - Polynomial Regression: `MSE = ~0.86, R² = ~0.92`  
  - Regularized models (to be added).  

### 6️⃣ Insights
- Exam scores have a **strong linear relationship** with the features.  
- Parental involvement, motivation level, and teacher quality are key predictors.  
- Polynomial regression didn’t improve results → linear model is sufficient.  

---

## 📊 Example Results

| Model                  | MSE   | R²   |
|-------------------------|-------|------|
| Linear Regression       | 0.797 | 0.932 |
| Polynomial (Degree=2)   | 0.860 | 0.926 |

---

## 🛠️ Tech Stack
- Python 🐍  
- Pandas, NumPy → Data handling  
- Matplotlib, Seaborn → Visualization  
- Scikit-learn → Regression models  

---

## 📌 Next Steps
- Add Ridge & Lasso regression results.  
- Plot **Predicted vs Actual** exam scores.  
- Explore feature importance.  

---

## 👩‍💻 Author
- Mariam Hamza  

