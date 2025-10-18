# Syed_Infosys_MileStone-2
Infosys Springboard Internship 6.0, Mile Stone-2 

# 🎓 Predicting Job Roles from Educational Background

This project was developed as part of the **Infosys Springboard Internship 6.0**.  
The primary goal is to **predict suitable job roles for students** based on their **educational background, skills, certifications, and project experiences** using **Machine Learning**.

---

## 🧭 Project Overview

The project focuses on exploring how a student's education and technical profile can be used to predict potential job roles in the IT industry.  
The steps involved in the project are:

1. **Data Collection** – A dataset of 500 students was created containing their education, skills, certifications, projects, and salary expectations.  
2. **Data Cleaning & Preprocessing** – Removed missing, null, duplicate, and redundant records to improve data quality.  
3. **Data Encoding** – Converted categorical variables (like skills and qualifications) into numerical form using **OneHotEncoder**.  
4. **Exploratory Data Analysis (EDA)** – Visualized trends and correlations between skills, education, and job roles.  
5. **Model Training** – Built a **Logistic Regression Model** to predict the most probable job role.  
6. **Model Evaluation** – Evaluated using metrics like Accuracy, ROC Curve, Predicted Probabilities, and Odds Ratios.  
7. **Visualization** – Used Seaborn and Matplotlib for advanced visualizations including ROC Curves, Partial Dependence Plots, and Predicted Probability Charts.  

---

## ⚙️ Tools & Technologies Used

| Category | Tools / Libraries |
|-----------|-------------------|
| Programming | Python |
| Data Handling | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Development Platform | Google Colab |
| Version Control | Git, GitHub |

---

## 🧹 Data Cleaning and Preprocessing

Before model building, several preprocessing tasks were performed:

- Removed **duplicate** and **redundant** rows  
- Handled **missing** and **null** values using imputation  
- Standardized text data (trimmed spaces, normalized formats)  
- Encoded categorical data using **OneHotEncoding**  
- Scaled features where required  

This ensured a clean, high-quality dataset ready for EDA and modeling.

---

## 📊 Exploratory Data Analysis (EDA)

EDA helped understand key relationships between features and the target variable (Job Role).  
Key observations:

- Students with **multiple certifications** and **hands-on projects** tend to have higher job opportunities.  
- **Programming skills** such as Python, SQL, and Java strongly correlate with roles like Data Analyst and Software Engineer.  
- **Higher education qualifications** generally lead to better salary expectations.

### Visualizations Included:
- Distribution of Job Roles  
- Count of Skills per Role  
- Salary Expectation vs Education Level  
- ROC Curve  
- Predicted Probability Plot  
- Odds Ratio Plot  
- Partial Dependence Plot  

---

## 🤖 Model Building – Logistic Regression

The **Logistic Regression model** was chosen for its interpretability and efficiency in multi-class classification problems.  
After training, the model was evaluated using multiple performance metrics.

### Model Pipeline:
1. Split data into training and testing sets (80:20)
2. Encoded categorical variables
3. Trained the model on encoded data
4. Predicted job roles on the test set
5. Evaluated and visualized results

---

## 📈 Model Evaluation

| Metric | Score |
|:--|:--|
| Accuracy | **0.86** |
| Precision | **0.84** |
| Recall | **0.83** |
| ROC AUC | **0.89** |

### Visualization Outputs:
- **ROC Curve:** Demonstrates model performance and class separation.  
- **Predicted Probability Plot:** Shows probability confidence for each predicted class.  
- **Odds Ratio Plot:** Highlights which features have the strongest impact on predictions.  
- **Partial Dependence Plot:** Explains how individual features influence the outcome.

---

## 🧠 Key Insights

- **Skills and Certifications** play a major role in determining employability.  
- **Education level** combined with **project experience** provides a strong indicator for job role suitability.  
- The Logistic Regression model successfully identified key factors influencing job predictions with strong interpretability.

---


---

## 🚀 How to Run the Project

1. Open `job_role_prediction.ipynb` in **Google Colab**.  
2. Run all cells sequentially:
   - Data Cleaning  
   - EDA  
   - Encoding  
   - Model Building  
   - Evaluation & Visualization  
3. View the final encoded dataset (with 0s and 1s) and prediction outputs.

---

## 👨‍🏫 Mentor

**Mr. Arun**  
Mentor, Infosys Springboard Internship 6.0  

---

## ✍️ Author

**Syed Sharshad**  
Infosys Springboard Intern  

📧 Email: *syedsharshad@gmail.com*  
📍 Location: India  

---

## 🪪 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## 🌟 Acknowledgement

Special thanks to **Infosys Springboard** for providing this internship opportunity and to **Mr. Arun** for his continuous mentorship and guidance throughout the project journey.

---

