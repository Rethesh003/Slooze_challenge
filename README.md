# 📊 Slooze Challenge 

### 🧠 Project Overview  
This project is a **Data Science / Analytics case study** focused on improving inventory management and sales forecasting for Slooze.  
Analyzed multiple datasets related to purchases, inventory, sales, and vendors to uncover **actionable insights** that can optimize business operations.

---

## 📂 Dataset Structure  
| File | Description |
|------|--------------|
| `2017PurchasePricesDec.csv` | Product purchase prices by vendor |
| `BegInvFINAL12312016.csv` | Beginning inventory |
| `EndInvFINAL12312016.csv` | Ending inventory |
| `InvoicePurchases12312016.csv` | Invoice details for purchases |
| `PurchasesFINAL12312016.csv` | Purchase transactions |
| `SalesFINAL12312016.csv` | Sales data for all products |

All files are stored inside the **`data/`** folder.

---

## 🧾 Analysis Performed

### 1️⃣ Demand Forecasting
- Analyzed historical sales data to identify **monthly trends**.
- Applied **3-month moving average** to smooth sales variations.

### 2️⃣ ABC Analysis
- Categorized inventory into **A, B, C** classes:
  - **A:** High value (Top 70%)
  - **B:** Medium value (Next 20%)
  - **C:** Low value (Bottom 10%)
- Helps prioritize stock control and order frequency.

### 3️⃣ EOQ & Reorder Point
- Calculated **Economic Order Quantity (EOQ)** to balance ordering and holding costs.
- Determined **Reorder Points** using lead times and safety stock formula.

### 4️⃣ Lead Time Analysis
- Compared **Purchase Order Date** and **Receiving Date** to compute average lead times.
- Identified vendors with the longest delays.

### 5️⃣ Top Product Analysis
- Highlighted top-selling products by sales revenue.
- Compared **EOQ values** for high-value items.

### 6️⃣ Seasonal Trends
- Forecasted sales per product/store.
- Identified **seasonal peaks** (high-demand months).

---

## 📈 Key Visualizations
✅ Monthly sales trend (moving average)  
✅ ABC classification chart  
✅ EOQ comparison bar chart  
✅ Vendor lead time bar chart  
✅ Top 10 products by revenue  
✅ Seasonal trend lines for top 5 products  

---

## 💡 Insights & Recommendations
1. Prioritize **A-class items** for tighter stock control.  
2. Reduce vendor **lead time delays** through performance monitoring.  
3. Maintain **safety stock** for high-demand products.  
4. Adjust **EOQ** and **reorder points** regularly.  
5. Prepare **seasonal inventory** ahead of high-demand months.  

---

## 🧰 Tech Stack
- **Python**
  - pandas, numpy, matplotlib, seaborn  
- **Jupyter Notebook**
- **Git & GitHub**
- **Kaggle dataset source**

---

## 🚀 How to Run
```bash
# Clone this repository
git clone https://github.com/Rethesh003/Slooze_Challenge.git

# Open the notebook
jupyter notebook Slooze_Challenge.ipynb


