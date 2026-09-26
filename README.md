# Diwali Sales Data Analysis 🪔📊

An Exploratory Data Analysis (EDA) project on Diwali sales data to uncover customer buying patterns, top-performing product categories, and regional sales trends.

## 📁 Dataset

The dataset (`Diwali Sales Data.csv`) contains customer transaction records with the following key fields:
- `User_ID`, `Cust_name`, `Product_ID`, `Product_Category`
- `Gender`, `Age`, `Age Group`, `Marital_Status`
- `State`, `Zone`, `Occupation`
- `Orders`, `Amount`

## 🛠️ Tools & Libraries

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🧹 Data Cleaning

- Removed irrelevant columns (`Status`, `unnamed1`)
- Checked and removed duplicate records
- Handled missing values using forward fill
- Renamed columns for clarity (e.g., `Shaadi` → `Marital_Status`)

## 📈 Analysis Performed

- **Gender-wise sales** — spending comparison between male and female customers
- **Age group analysis** — purchasing behavior across different age brackets
- **State-wise sales** — top-performing states by orders and revenue
- **Marital status trends** — spending patterns of married vs. unmarried customers
- **Occupation-wise sales** — which professions contribute most to sales
- **Product category performance** — most ordered vs. highest revenue-generating categories
- **Top-selling products** — identified best-selling product IDs and their categories

## 🔑 Key Findings

- **Married women aged 26–35** are the biggest buying segment.
- **Top 4 states by sales:** Uttar Pradesh, Maharashtra, Karnataka, and Delhi.
- Buyers from **IT, Healthcare, and Aviation** sectors purchase comparatively more than other occupations.
- **Clothing** has the highest order volume, but **Food** generates the most revenue.
- Top-selling products span categories including Stationery, Auto, Food, and Footwear.

## 🚀 How to Run

1. Clone this repository
```bash
   git clone <your-repo-url>
```
2. Install dependencies
```bash
   pip install pandas matplotlib seaborn jupyter
```
3. Open the notebook
```bash
   jupyter notebook data_anysis.ipynb
```

## 👤 Author

**Priyajit**

---
*Keep learning, keep analyzing!*
