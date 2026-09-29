# 🪔 Diwali Sales Data Analysis

Exploratory data analysis of Diwali-season sales data using **Python (Pandas, NumPy, Matplotlib, Seaborn)** to understand customer buying behavior and find the segments, regions and product categories that drive festive sales.

---

## 📌 Objective

To analyze Diwali sales data and answer key business questions:

- Which gender and age group spend the most?
- Which states and zones generate the highest sales?
- Which occupations and product categories contribute most to revenue?
- Do married and unmarried customers spend differently?

The results can help businesses plan targeted marketing and inventory for the festive season.

## 📂 Dataset

| Detail | Value |
|---|---|
| Records | 11,251 (11,231 after cleaning) |
| Columns | 15 |
| Customer fields | User_ID, Cust_name, Gender, Age, Age Group, Marital_Status, Occupation |
| Location fields | State, Zone |
| Purchase fields | Product_ID, Product_Category, Orders, Amount |
| Coverage | 16 states, 15 occupations, 18 product categories |

## 🛠️ Tools & Technologies

- Python
- Google Colab / Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn

## 🔄 Methodology

1. **Data understanding:** checked shape, data types, `head()`, `tail()`, `info()` and `describe()`.
2. **Data cleaning:**
   - Dropped two completely empty columns (`Status`, `unnamed1`)
   - Removed 12 rows with missing `Amount`
   - Removed 8 duplicate rows
   - Final clean dataset: **11,231 rows × 13 columns**
3. **Analysis with Pandas:** `groupby` aggregations on gender, age group, marital status, state, zone, occupation and product category.
4. **Visualization:** bar plots and count plots using Seaborn and Matplotlib.
5. **Insights:** compared segments to identify the top contributors.

## 📊 Key Insights

**Overall:** total sales of about **₹10.6 crore** from **27,955 orders**. Average purchase amount ≈ ₹9,454 (median ≈ ₹8,109).

| Area | Finding |
|---|---|
| **Gender** | Women contributed about **70%** of total sales (₹7.43 crore vs ₹3.19 crore for men). |
| **Age group** | **26–35** is the top group with about **40%** of sales and the most orders (11,378). Ages 26–45 together account for about **61%**. |
| **Marital status** | Unmarried customers contributed about **58.5%** of sales, married customers about **41.5%**. |
| **Zone** | **Central** leads with about **39%**, followed by Southern (about 25%) and Western (about 17%). |
| **State** | **Uttar Pradesh** (about 18%), **Maharashtra** (about 14%), **Karnataka** (about 13%), then Delhi (about 11%). |
| **Occupation** | **IT Sector** (about 14%), **Healthcare** (about 12%) and **Aviation** (about 12%) spend the most. |
| **Product category (revenue)** | **Food** is the top category with about **32%** of revenue (₹3.39 crore), followed by Clothing & Apparel, Electronics & Gadgets and Footwear & Shoes. |
| **Product category (orders)** | **Clothing & Apparel** has the most orders (6,627), followed by Food (6,110) and Electronics & Gadgets (5,208). |

## ✅ Conclusion

Festive sales are driven mainly by **women aged 26–45**, customers from **Uttar Pradesh, Maharashtra and Karnataka**, and professionals in **IT, Healthcare and Aviation**. **Food** earns the most revenue, while **Clothing & Apparel** sells the most orders. Businesses can use these insights to focus campaigns on high-value customer groups and stock popular categories well before Diwali.

## ⚠️ Limitations & Future Scope

- The data covers a single festive season, so year-over-year trends can't be studied.
- Amounts are assumed to be in Indian rupees (₹).
- Future work: an interactive **Power BI dashboard**, customer segmentation, and a sales prediction model.

## 📁 Project Structure

```
Diwali-Sales-Data-Analysis/
├── README.md
├── Diwali Sales Data.csv
└── diwali_festival_data_analysis.ipynb
```

## ▶️ How to Run

1. Clone the repository or download the files.
2. Open `diwali_festival_data_analysis.ipynb` in Jupyter Notebook or Google Colab.
3. Keep `Diwali Sales Data.csv` in the same folder as the notebook.
4. Run all cells.

## 👤 Author

**Divyanshu Singh**
GitHub: [divyanshu12162001-dotco](https://github.com/divyanshu12162001-dotco)
