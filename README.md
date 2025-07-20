
---

## 📊 Dataset

- **Source**: UCI Machine Learning Repository – Adult Dataset
- **Features**: age, workclass, education, marital-status, occupation, relationship, race, sex, capital-gain, hours-per-week, etc.
- **Target**: `salary` (`<=50K` or `>50K`)

---

## ⚙️ Workflow

### ✅ Step 1: Data Preprocessing
- Handled missing values and encoded categorical columns.
- Removed invalid entries such as `Without-pay`, `Never-worked`.
- Outlier detection on features like `age` and `capital-gain`.

### 📊 Step 2: Exploratory Data Analysis
- Box plots and value counts for outlier and distribution checks.

### 🤖 Step 3: Model Building
- Applied machine learning models like:
  - Logistic Regression
  - Decision Tree
  - Random Forest
- Evaluated using accuracy, precision, recall, and F1-score.

---

## 🛠️ Technologies Used

- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Scikit-learn**
- **Jupyter Notebook**

---

## 🚀 Getting Started

### Clone the repository
```bash
git clone https://github.com/your-username/employee_salary_prediction_using_ml.git
cd employee_salary_prediction_using_ml
