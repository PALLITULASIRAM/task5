# 🏠 Task 5: Decision Trees & Random Forests - Housing Price Prediction

### 🎯 Objective
To understand and implement Decision Tree and Random Forest algorithms for **regression** tasks using the **Housing Price Prediction** dataset.

---

### 📘 Concepts Covered
- Decision Tree Regressor
- Random Forest Regressor
- Overfitting & Depth Control
- Feature Importance
- Cross-Validation

---

### 🧩 Tools Used
- Python  
- Scikit-learn  
- Pandas  
- Matplotlib  
- Seaborn  
- NumPy  

---

### ⚙️ Steps Performed
1. Imported libraries and loaded dataset from GitHub  
2. Cleaned missing values and encoded categorical features  
3. Trained a **Decision Tree Regressor** and visualized it  
4. Controlled overfitting using `max_depth` parameter  
5. Trained a **Random Forest Regressor** and compared performance  
6. Visualized **feature importances**  
7. Evaluated models with **cross-validation**

---

### 📈 Results
| Model | R² Score | MSE | Notes |
|--------|----------|-----|-------|
| Decision Tree | ~0.80 | Moderate | Overfits with deep trees |
| Limited Depth Tree | ~0.85 | Improved | Better generalization |
| Random Forest | ~0.90+ | Low | Best overall performance |

---

### 🧠 Learnings
- **Decision Trees** split data using the best feature thresholds.  
- **Random Forests** combine multiple trees for stronger generalization.  
- Controlling model complexity (like depth or estimators) avoids overfitting.  

---

### 🗂️ Dataset
[Housing Price Prediction Dataset](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)

---

### 🚀 How to Run
1. Open the notebook in **Google Colab**  
2. Run all cells in sequence  
3. View results, charts, and metrics  
4. Upload notebook & README to **GitHub**

---

### 👨‍💻 Author
**Palli Tulasiram**  
AI & ML Internship – Task 5  
