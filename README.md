# Estimating Obesity Levels Based on Eating Habits & Physical Condition

📊 A supervised and unsupervised data mining project using regression, classification, and clustering techniques to predict obesity levels based on eating habits, demographics, and physical activity data.

---

## 🧠 Objective

This project aimed to explore how lifestyle and physiological variables influence obesity levels, and to build predictive models that classify individuals into 7 distinct obesity categories.

---

## 📚 Dataset

- **Source**: UCI Machine Learning Repository  
- **Dataset**: Estimation of Obesity Levels Based on Eating Habits and Physical Condition  
- **Records**: 2,111 individuals from Mexico, Peru, and Colombia  
- **Features**: 16 predictors (e.g., age, gender, meal frequency, activity, water/alcohol intake)  
- **Target**: Obesity level (7 classes: Insufficient, Normal, Overweight I/II, Obesity I/II/III)

---

## 🧰 Tools & Libraries

- Python: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- Jupyter Notebook
- ML Models: Logistic Regression, Decision Trees, Random Forest, SVM
- Clustering Models: K-Means, Hierarchical Clustering
- Preprocessing: StandardScaler, One-Hot Encoding

---

## 🔍 Methods Used

### 📈 Regression
- Predicted **BMI** using Linear Regression
- R²: 0.50, RMSE: 5.66  
- Key Influences: Physical activity, age, meal frequency

### 📊 Classification
| Model | Accuracy |
|-------|----------|
| Logistic Regression | 62.88% (→ 86.52% with height/weight added) |
| Decision Tree | 93.38% |
| Random Forest | **95.51%** |
| SVM (Linear) | 93.85% |

- Top features: Weight, Height, Age, Vegetable Intake, Physical Activity

### 🔗 Clustering
- Applied **K-Means** and **Hierarchical Clustering**
- Identified 5 lifestyle-based behavioral clusters
- ARI scores: K-Means (0.19), Hierarchical (0.14)

---

## 📁 Project Structure

obesity-prediction-data-mining/
├── CIS9660_Group7_Project.ipynb # Main Jupyter notebook with all code and analysis
├── CIS9660_Group7_Final_Report.pdf # Final PDF report summarizing methodology and results
├── CIS9660_Group7_Project_Proposal_Slides.pptx # Project proposal presentation (optional)
└── README.md # Project overview and documentation


---

## 👥 Contributors

This project was completed as part of **CIS 9660 – Data Mining for Business Analytics** at Baruch College, Spring 2025.

**Group 7**:  
- Helly Harshad Shah  
- Khushwant Khatri  
- Vibha Gokhale  
- Maria Cristina Moreno Siguenza  
- Isha Thakkar  
- Khan Yunus

---

## 📌 Key Takeaways

- Tree-based models and linear SVM achieved >93% classification accuracy
- Lifestyle factors (snacking, physical activity) and physiological measures (height, weight) play major roles
- Unsupervised clustering reveals health behavior profiles not captured by labels

---

## 📬 Contact

📧 shah.hellyharshad11@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/helly-h-shah)


