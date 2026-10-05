# 🛒 E-Commerce Sales Analysis using Python

An exploratory data analysis (EDA) of the **Superstore** e-commerce dataset. The project finds out **what sells, what earns profit, and where the business can improve**, using Python and clear visualizations.

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4c8cbf)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626)

---

## 📌 Project Overview

The goal of this project is to understand the sales and profit performance of an e-commerce store and to give simple, useful recommendations.

The analysis answers these questions:

- Which months have the highest and lowest sales and profit?
- Which product categories and sub-categories sell the most?
- Which ones earn the most profit, and which ones lose money?
- Which customer segment is the most valuable?
- How efficiently does each segment turn sales into profit?

---

## 📂 Dataset

- **Name:** Sample - Superstore
- **Size:** 9,994 rows and 21 columns
- **Key columns:** Order Date, Segment, Category, Sub-Category, Sales, Quantity, Discount, Profit
- **Data quality:** no missing values found

---

## 🛠️ Tools and Libraries

| Tool | Use |
|---|---|
| Python | Main programming language |
| Pandas | Data cleaning and analysis |
| NumPy | Numerical operations |
| Matplotlib | Charts |
| Seaborn | Statistical charts |
| Jupyter Notebook | Analysis and documentation |

---

## 🔍 Analysis Steps

1. Load the dataset and inspect it (`head`, `info`, `describe`)
2. Check for missing values and duplicates
3. Convert date columns and create new columns (month, year, day of week)
4. Analyze and visualize:
   - Monthly sales and profit
   - Sales and profit by category
   - Sales and profit by sub-category
   - Sales and profit by customer segment
   - Sales to profit ratio
5. Write key insights and recommendations

---

## 📊 Key Insights

### Overall
- **Total sales:** about $2.30M
- **Total profit:** about $286K
- **Overall profit margin:** about 12.5%

### Monthly Trend
- Sales are highest in **November ($352K)** and lowest in **February ($60K)**.
- **September to December** brings about **51.6%** of yearly sales, so there is a clear **seasonal pattern**.
- Profit is highest in **December ($43K)** and lowest in **January ($9K)**.

### Category
| Category | Sales Share | Profit Share |
|---|---|---|
| Technology | 36.4% | 50.8% |
| Furniture | 32.3% | 6.4% |
| Office Supplies | 31.3% | 42.8% |

- Sales are spread evenly, but **profit is not**.
- **Furniture** brings in about one-third of sales but only **6.4%** of profit.

### Sub-Category
- **Top sellers:** Phones, Chairs, Storage, Tables, Binders
- **Most profitable:** Copiers ($55.6K), Phones ($44.5K), Accessories ($41.9K), Paper ($34.1K)
- **Loss-making:** Tables (-$17.7K), Bookcases (-$3.5K), Supplies (-$1.2K)
- **Tables** is a top-5 seller but has the biggest loss. This is the main reason Furniture earns so little profit.

### Customer Segment
| Segment | Sales Share | Profit Margin | Sales to Profit Ratio |
|---|---|---|---|
| Consumer | 50.6% | 11.5% | 8.66 |
| Corporate | 30.7% | 13.0% | 7.68 |
| Home Office | 18.7% | 14.0% | 7.13 |

- **Consumer** is the biggest segment but has the lowest margin.
- **Home Office** is the smallest but the most efficient. A lower sales to profit ratio is better.

---

## ✅ Recommendations

- **Fix Furniture:** review pricing, discounts and costs for Tables and Bookcases.
- **Promote winners:** push Copiers, Accessories and Paper with bundles and campaigns.
- **Plan for the peak:** prepare stock and marketing for September to December.
- **Improve Consumer margin:** reduce discount leakage and grow Home Office and Corporate.

---

## 🔮 Future Improvements

- Check the effect of **discount** on profit, especially for Tables and Bookcases
- Add **region and state** level analysis
- Build an interactive dashboard in Power BI or Tableau

---

## 👩‍💻 Author

**Aafra**
Data Analyst | Mumbai, India
GitHub: [@Aafrakhan](https://github.com/Aafrakhan)

⭐ If you found this project useful, please give it a star!
