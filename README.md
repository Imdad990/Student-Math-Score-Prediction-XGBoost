# Student-Math-Score-Prediction-XGBoost
High-accuracy student math score prediction using XGBoost with full ML pipeline and 99.36% R² accuracy.

# 🎓 Student Performance Prediction using XGBoost

This project uses advanced Machine Learning techniques to **predict student math scores** based on various factors like reading & writing scores, parental education, lunch type, gender, and test preparation.

---

## 🚀 Project Summary

The goal of this project is to build a predictive model that can **accurately estimate a student's math performance**. The model is trained on the **StudentsPerformance dataset** and achieves high accuracy using the **XGBoost Regressor**.

---

## 📈 Model Accuracy

- ✅ **R² Score (Test Data): 99.36%**
- ✅ **Root Mean Squared Error (RMSE): 1.16**

This means our model can **very accurately** predict math scores with minimal error.

---

## 🧠 Machine Learning Pipeline

The project follows a full ML pipeline:

1. **Data Collection** - Student performance dataset
2. **Data Cleaning** - Categorical encoding & scaling
3. **Feature Engineering** - Created new features like average score & read-math ratio
4. **Feature Selection** - Removed low-impact variables
5. **Model Selection** - Used `XGBoost` Regressor
6. **Training & Validation** - Split data (80/20), trained on 300 estimators
7. **Hyperparameter Tuning** - Optimized depth, learning rate, and sampling
8. **Evaluation** - R² Score and RMSE used
9. **Visualization** - Feature importance plotted

---

## 🗃️ Dataset Information

- Name: `StudentsPerformance.csv`
- Source: Open dataset on student performance
- Size: 1000 samples
- Features: Gender, Race, Parental Education, Lunch, Test Prep, Reading & Writing Scores

---

## 📊 Visualization

The feature importance plot shows the most impactful features contributing to math performance:

- `reading score`
- `writing score`
- `avg_score`
- `read_math_ratio`

---

## 🧾 Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib, Seaborn
- Google Colab

---

## ✅ Use Case

This model can help:

- **Teachers** to identify students needing extra help.
- **Educational Institutions** to analyze performance trends.
- **Data Science learners** to understand regression-based workflows.

---

## 👨‍💻 Author

**Imdad Ullah Khan**  
Machine Learning Developer | AI Consultant  
📍 Working on real-world AI projects  
📬 Connect on LinkedIn (optional)

---

## 🔗 License

Open source — feel free to use or improve.


