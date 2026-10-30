# 👥 Customer Demographics & Spending Score Analysis

An Exploratory Data Analysis project uncovering customer demographic patterns, income distributions, and spending behaviors to inform market segmentation and targeted marketing strategies.

---

## 📌 Project Overview

Understanding consumer purchasing power and spending tendencies is critical for designing targeted retail campaigns, optimizing product pricing, and improving customer lifetime value. This project analyzes customer demographic and transactional attributes to uncover key behavioral clusters based on income, age cohorts, professional occupations, and geographical regions.

---

## 📊 Dataset Overview

The dataset (`customers.csv`) includes detailed consumer profiles:

* **Customer Demographics:** `CustomerID`, `Gender`, `Age`, `Age_Group`, `Marital_Status`.
* **Socio-Economic Factors:** `Annual_Income`, `Occupation` (Engineers, Healthcare, Artists, Lawyers, Executives, etc.), `City`.
* **Behavioral Metric:** `Spending_Score` (Normalized customer purchasing index).

---

## 🔍 Key Findings & Business Insights

1. **Spending Score vs. Age Dynamics:**
   * Scatter plots show distinct clustering: younger age brackets frequently exhibit elevated spending scores regardless of base annual income, whereas older demographics exhibit more conservative spending patterns.

2. **Income Distribution & Gender Parity:**
   * Kernel Density Estimation (KDE) and box plot analyses reveal comparable median income levels across male and female customer segments, with normal dispersion across income tiers.

3. **Occupation & City Trends:**
   * Analysis of occupational cohorts highlights specific high-earning segments that represent prime targets for premium loyalty programs.
   * Cross-tabulated counts of City and Age Groups reveal distinct metropolitan concentration of young demographic shoppers.

4. **Correlation Analysis:**
   * Evaluation of numeric relationships highlights that Annual Income and Spending Score are not strictly linear, demonstrating that high earners do not automatically constitute high spenders — indicating the necessity of behavioral segmentation.

---

## 📈 Visualizations in the Notebook

* **Distribution Histograms:** Binned distribution of customer annual incomes.
* **Occupation Breakdown:** Horizontal bar charts of customer professions.
* **Demographic Proportions:** Pie charts depicting marital status distribution.
* **Geographical Counts:** Grouped bar charts tracking customer volume by city and age groups.
* **Behavioral Scatter Plot:** Scatter plot analyzing the relationship between customer age and spending score.
* **KDE Density Plots:** Kernel density estimation comparing income distributions across genders.
* **Correlation Heatmap:** Multi-variable correlation matrix examining demographic and financial variables.

---

## 🛠️ Tech Stack

* **Language:** Python 3.x
* **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `jupyter`
* **Dataset:** `customers.csv`

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/Zelarq/customer-segmentation-analysis.git
cd customer-segmentation-analysis
```

### 2. Set Up Virtual Environment
```bash
python -m venv venv
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook
```bash
jupyter notebook customers_project.ipynb
```

---

## 👤 Author

* **Sayanth N K**
* GitHub: [@Zelarq](https://github.com/Zelarq)
* Email: [sayanthnk32@gmail.com](mailto:sayanthnk32@gmail.com)
