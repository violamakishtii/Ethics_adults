# Ethics_adults
# ⚖️ Adult Dataset – Fairness & Ethics Analysis

## 📌 Overview
This project explores **fairness in machine learning** using the Adult Income dataset.

The goal is to:
- Train a classification model to predict income (`>50K` or `<=50K`)
- Analyze bias across demographic groups
- Apply a fairness mitigation technique
- Evaluate the trade-off between **accuracy and fairness**

---

## 📂 Dataset

The dataset used is:adult.cvs

### Key Features:
- `age` → Age of individual  
- `sex` → Gender  
- `race` → Ethnicity  
- `education` → Education level  
- `occupation` → Job type  
- `income` → Target variable (`>50K` or `<=50K`)  

---

## ⚙️ Project Workflow

### 1. Data Exploration (EDA)
- Analyzed distribution of:
  - Gender  
  - Race  
  - Age groups  
- Identified **underrepresented groups**

---

### 2. Data Preprocessing
- Handled missing values (`?`)
- Converted income to binary (0 / 1)
- Applied **one-hot encoding** to categorical features

---

### 3. Model Training
- Used **Logistic Regression**
- Split data into training and testing sets

---

### 4. Evaluation
Measured:
- **Accuracy**
- **Precision**
- **Recall**

---

### 5. Fairness Analysis

Evaluated model performance across:
- Gender  
- Race  
- Age groups  

Metrics used:
- Precision per group  
- Recall per group  

---

### 6. Bias Mitigation

Applied **reweighting technique**:
- Increased importance of underrepresented groups during training
- Used sample weights in Logistic Regression

---

## 📊 Results

### Before Mitigation:
- Higher accuracy  
- Noticeable bias between groups  
- Lower recall for underrepresented populations  

### After Mitigation:
- Fairness improved (more balanced precision/recall)  
- Slight decrease in overall accuracy  

---


---

## 📦 Libraries Used

- pandas  
- numpy  
- matplotlib  
- scikit-learn  

---

## ⚖️ Ethical Considerations

- Machine learning models can **inherit bias from data**
- Imbalanced datasets lead to **unfair predictions**
- Fairness techniques improve equity but may reduce accuracy
- Real-world systems must balance:
  - Performance  
  - Fairness  
  - Transparency  

---

## ✅ Key Insights

✔ Bias exists even in well-performing models  
✔ Underrepresented groups are often disadvantaged  
✔ Simple techniques like reweighting can improve fairness  
✔ There is always a trade-off between fairness and accuracy  

---

## ⚠️ Limitations

- Uses a single model (Logistic Regression)  
- Limited fairness techniques (only reweighting)  
- Dataset may not reflect current real-world demographics  

---

## 🚀 Future Improvements

- Use advanced fairness methods (e.g., adversarial debiasing)  
- Try different models (Random Forest, XGBoost)  
- Add fairness metrics like:
  - Equal Opportunity  
  - Demographic Parity  
- Build an interactive dashboard  

---

## 🧠 Conclusion

This project demonstrates that:

- High accuracy does not guarantee fairness  
- Bias detection is essential in ML systems  
- Ethical AI requires intentional design choices  

Balancing fairness and performance is a critical challenge in modern machine learning applications.

---

## 👤 Author

Viola Makishti  

