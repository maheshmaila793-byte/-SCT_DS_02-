# Task 2: Data Cleaning & Exploratory Data Analysis (EDA)

## 📌 Objective
Perform data cleaning and exploratory data analysis (EDA) on a dataset of choice.  
For this task, the **Titanic dataset** was used to explore relationships between variables and identify patterns and trends.

---

## 🛠️ Steps Performed

### 1. Data Loading
- Imported dataset (`task_2dataset.csv`) into a Pandas DataFrame.
- Displayed dataset info and first few rows.

### 2. Data Cleaning
- Handled missing values:
  - Filled missing **Age** with median.
  - Filled missing **Embarked** with mode.
  - Dropped **Cabin** column (too many missing values).
- Encoded categorical variables:
  - **Sex** → Male = 0, Female = 1
  - **Embarked** → S = 0, C = 1, Q = 2

### 3. Exploratory Data Analysis (EDA)
- Generated **summary statistics** for numeric columns.
- Visualized:
  - Age distribution (histogram).
  - Survival rate by Gender (bar plot).
  - Survival rate by Passenger Class (bar plot).
  - Survival rate by Embarked Port (bar plot).
  - Correlation heatmap (numeric features only).

---

## 📊 Key Insights
- **Gender:** Females had a significantly higher survival rate than males.
- **Class:** First‑class passengers had better survival chances compared to second and third class.
- **Embarked Port:** Passengers from port **C** showed higher survival rates compared to **S** and **Q**.
- **Age Distribution:** Most passengers were between 20–40 years old.
- **Correlation:** Passenger class and fare are strongly correlated; survival shows moderate correlation with gender and class.

---

## ⚙️ Tools & Libraries
- Python (Google Colab)
- Pandas
- Matplotlib
- Seaborn

---

## 📂 Files
- `task_2dataset.csv` → Titanic dataset sample used for analysis.
- `task2_notebook.ipynb` → Jupyter/Colab notebook with full code and outputs.
- `README.md` → Documentation of Task 2.

---

## ✅ Conclusion
This task demonstrates how **data cleaning** and **EDA** help uncover meaningful patterns in raw datasets.  
The Titanic dataset highlights how demographic and socio‑economic factors influenced survival outcomes.
