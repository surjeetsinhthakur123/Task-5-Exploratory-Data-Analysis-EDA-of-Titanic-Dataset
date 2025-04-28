# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

## 📋 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the famous **Titanic Dataset** using **Python** libraries like `Pandas`, `Matplotlib`, and `Seaborn`.

The goal is to:
- Understand the structure of the data
- Identify patterns, trends, and anomalies
- Explore relationships between features
- Visualize important insights

---

## 📂 Files

| File Name              | Description                                      |
| ---------------------- | ------------------------------------------------ |
| `train.csv`             | Main dataset used for EDA (contains survival info) |
| `test.csv`              | Test dataset (not used heavily for EDA) |
| `gender_submission.csv` | Example submission file for Kaggle |
| `Titanic_EDA.ipynb`     | Jupyter Notebook with full EDA code |
| `EDA_Report.pdf`        | PDF report containing key visuals and findings |
| `README.md`             | Project overview and instructions |

---

## 🛠️ Tools Used

- **Python 3.x**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 📈 Key Steps Performed

1. **Loading Data**
2. **Data Inspection** (`.info()`, `.describe()`, `.head()`)
3. **Handling Missing Values**
4. **Univariate Analysis** (Histograms, Boxplots)
5. **Bivariate Analysis** (Barplots, Scatterplots)
6. **Correlation Heatmap**
7. **Pairplot for Feature Relationships**
8. **Summary of Key Findings**

---

## 📊 Important Findings

- **Females** had a much higher survival rate compared to **males**.
- **1st Class passengers** had better survival chances than 2nd and 3rd class passengers.
- Younger passengers (especially children) had slightly better survival rates.
- Passengers who paid **higher fares** tended to survive more.
- Missing values were mostly found in the `Age`, `Cabin`, and `Embarked` columns.

---

## 📢 How to Run

1. Clone or download this repository.
2. Install required libraries:

   ```bash
   pip install pandas matplotlib seaborn
   ```

3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook Titanic_EDA.ipynb
   ```

4. Run all cells to reproduce the analysis and visualizations.

---

## 📬 Contact

If you have any questions or suggestions, feel free to connect!

---

# 🚀 Happy Analyzing!
