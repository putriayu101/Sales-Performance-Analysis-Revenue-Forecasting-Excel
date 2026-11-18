# 📊 Sales Performance Analysis & Revenue Forecasting (Excel)

> A business-style sales analysis built entirely in Microsoft Excel: data preparation, Pivot Table analysis across category, product, region and time, a month-to-date revenue projection, and a summary dashboard.

## 🖥️ Dashboard

<img width="1395" height="647" alt="image" src="https://github.com/user-attachments/assets/4dd99deb-0289-4123-8b24-1c869729b6f9" />

*Excel dashboard summarizing the key sales metrics from this project.*

## 🎯 Key Findings

- **Electronics** was the top category by revenue (**IDR 12,935,000**), and **Shoes** was the top product by revenue (**23.7%** of total sales), followed by T-Shirt (14.9%). By units sold, **T-Shirt** leads (82 of 355 units) and Laptop Sleeve is last (8 units), so the volume leader and the revenue leader differ.
- Monthly sales **peaked in February at IDR 10,050,000**.
- The **66% drop from April to May is a data-coverage effect, not a real decline**: the dataset ends on May 10, 2024. Compared like-for-like (April 1-10 vs May 1-10), May sales were slightly higher: IDR 3,190,000 vs IDR 3,035,000 (about +5%).
- **West** is the strongest region: **28% of total sales** and the **highest average spend (IDR 360,469)**. **South** is the weakest: tied for the fewest orders (30) and the lowest average spend (IDR 291,000).
- **85.37% of total sales revenue** came from high-value orders (order value ≥ IDR 200,000), versus 14.63% from low-value orders.
- Projected full-month May sales: **IDR 9,889,000** (month-to-date run-rate: IDR 3,190,000 ÷ 10 days × 31 days), about 4.5% above April and 1.6% below February's peak.

## 🧭 Business Questions & Approach

**Questions this project answers**

1. Which categories, products, and regions drive revenue?
2. How do sales trend over time, and is the latest drop real?
3. Which regions need attention, and what would help them?
4. What might full-month May sales look like, based on the first 10 days?

**Approach**

1. **Prepare** the raw data (format normalization, missing dates, text standardization)
2. **Analyze** with Pivot Tables and Pivot Charts across category, product, region, and time
3. **Project** full-month May sales from month-to-date data using a run-rate calculation
4. **Summarize** the results in a dashboard

## 📁 Dataset

| Info | Detail |
| ---- | ------ |
| Type | **Dummy (simulated) dataset**, created for practice, not real business data |
| Size | 130 order records: 70 initial records + 60 additional records added to give the analysis more data |
| Period | January 1, 2024 to May 10, 2024 |
| Location | Included in the portfolio workbook (see below) |

## 📄 Repository Files

| File | Description |
| ---- | ----------- |
| `Portofolio_Intermediate-Excel (version 2).xlsm` | Main workbook containing the datasets, analysis, and dashboard |
| `Mini Sales Performance Report Project.pdf` | Summary report of the project: the questions asked, the approach, and the results |
| `README.md` | Project documentation |

### Workbook Structure

| Sheet | Description |
| ----- | ----------- |
| `RAW Data Porto` | Raw dataset used in this project |
| `CLEAN Data Porto` | Dataset after data cleaning |
| `Mapping_Product` | Helper table used to standardize product names during cleaning |
| `Dataset Tambahan` | The 60 additional dummy records added to the dataset |
| `RILL Fix Data (Pivot)` | Final dataset used for analysis |
| `Portfolio-PIVOT+Chart` | Pivot Tables and Pivot Charts with analysis notes |
| `Tabel-Help Pivot` | Helper table for one of the Pivot analysis segments |
| `DASHBOARD` | Dashboard visualization of the results |
| `Dashboard-Sheethelp` | Helper sheet for building the dashboard |

## 🛠️ Tools & Skills

**Tool:** Microsoft Excel (Pivot Tables & Charts, run-rate projection, Dashboard)

**Functions and techniques:**

- Lookup & logic: `VLOOKUP`, `AND`, `IF`
- Conditional analysis: `COUNTIF`
- Dynamic arrays: `UNIQUE`, `FILTER`
- Text standardization: `TRIM`, `PROPER`, `SUBSTITUTE`
- Pivot Tables, Pivot Charts, and dashboard design

## 🧹 Data Preparation

- Checked for duplicate records: **none found**
- Normalized data formats
- **Filled 8 blank dates** with the date from the row directly above
- Standardized text formats and categories using `TRIM`, `PROPER`, and `SUBSTITUTE`
- Created the `Mapping_Product` table to standardize product names
- Verified dataset consistency before analysis

## 📈 Analysis & Insights

### 1. Total Sales per Category

<img width="545" height="366" alt="image" src="https://github.com/user-attachments/assets/80cfa220-69f8-48d0-83b4-3f2c255013bf" />

- **Electronics** contributed the highest revenue: **IDR 12,935,000**.

### 2. Sales Trend & Forecast

<img width="552" height="327" alt="image" src="https://github.com/user-attachments/assets/0f37425b-52fa-4cda-9507-404ce611cf6d" />

- Sales peaked in **February at IDR 10,050,000**.
- Sales appear to drop **66% from April to May**, but the dataset ends on **May 10, 2024**, so May is incomplete. The drop reflects missing data, not weaker performance.

<img width="385" height="95" alt="image" src="https://github.com/user-attachments/assets/3b1025d5-92aa-45d2-b6de-738121bfe5fe" />

- Forecast method: a month-to-date **run-rate projection**: (sales so far ÷ days elapsed) × days in the month = (IDR 3,190,000 ÷ 10) × 31 = **IDR 9,889,000**.
- That is about **4.5% above April** (IDR 9,460,000) and **1.6% below February's peak** (IDR 10,050,000), so May has the potential to approach the February record.
- This is a simple, indicative estimate: it assumes the first 10 days' daily average holds for the whole month and does not capture seasonality or day-to-day swings.

<img width="400" height="224" alt="image" src="https://github.com/user-attachments/assets/1fcf7ef3-4ad1-4833-86c9-d3543620a126" />

- Comparing **April 1-10 vs May 1-10**, May sales were slightly **higher**: **IDR 3,190,000 vs IDR 3,035,000** (about +5%), consistent with the projection that May is tracking in line with earlier months.
- **Checkpoint:** if sales have not picked up by around May 20, the projected figure will not be met, and the marketing and sales teams should step in to address it.

### 3. High-Value vs Low-Value Sales

<img width="425" height="399" alt="image" src="https://github.com/user-attachments/assets/935bb1d4-6c15-459f-b10b-a93e09627e20" />

- Each order's **Total Sales = Unit Price × Quantity**. An order is classified as "High" if its Total Sales is **≥ IDR 200,000**, and "Low" if it is below that.
- From January to May 2024, **85.37% of total sales revenue** came from high-value orders and 14.63% from low-value orders. The pattern held in every month, so high-value sales dominated revenue throughout.
- This measures **revenue share**, so it shows where the money comes from, not necessarily which items customers buy most often (see Product Rank below).

### 4. Total Sales per Region

<img width="674" height="379" alt="image" src="https://github.com/user-attachments/assets/1a8ecb2f-e3dd-4750-98ff-e79effa9794c" />

- **West** had the highest share of sales (**28%**), followed by **East, North, and South**.

### 5. Average Selling Price Trend

<img width="455" height="328" alt="image" src="https://github.com/user-attachments/assets/71e5b23d-d205-4b2e-babc-e58ffb533c50" />

- The average selling price per unit **rose gradually from January to May**, peaking in May at **IDR 145,500**. This may reflect a shift toward higher-priced products; it does not by itself show higher sales volume.

### 6. Category Performance per Region

<img width="643" height="329" alt="image" src="https://github.com/user-attachments/assets/138f0830-b671-4037-8f1b-5d2289cb2d33" />

- Each region leans toward a different category: **East** favors **Apparel** (IDR 4,980,000), **West** favors **Footwear** (IDR 4,990,000), and **North** and **South** favor **Electronics** (IDR 3,975,000 and IDR 2,970,000).
- **Accessories** has the lowest sales in East, North, and West. South is the exception: there, Footwear is lowest (IDR 1,470,000 vs IDR 1,875,000 for Accessories).
- By units sold (Sum of Quantity), Accessories sold more than Footwear, yet it has the **lowest total sales** overall (IDR 4,255,000), because its unit price is lower than the other categories.
- This does not mean customer interest in Accessories is low in every region. Possible ways to grow it: promote it on social media or launch new products to attract more buyers.

### 7. Regional Segmentation

<img width="621" height="6352" alt="image" src="https://github.com/user-attachments/assets/6c442233-3110-4368-90f3-c805a681fc83" />

| Region | Orders | Average Spend (IDR) | Takeaway |
| ------ | ------ | ------------------- | -------- |
| West | 32 | 360,469 | Highest average spend and highest sales share (28%). **Focus: upselling** and keeping loyalty high. |
| East | 38 | 296,447 | Most transactions, but a low average spend. |
| North | 30 | 322,000 | Fewest orders (tied with South) but a strong average spend. **Focus: maintain loyalty.** |
| South | 30 | 291,000 | Tied for fewest orders and the lowest average spend. Needs **promotion** to attract customers and **pricing strategy** to raise spending. |

- West and North show customers with high purchasing power, so the focus there is keeping transaction values high.

### 8. Product Performance

<img width="630" height="402" alt="image" src="https://github.com/user-attachments/assets/6524ebef-41bf-4bde-8d1d-4f1dfefbadb8" />

- **Shoes:** top product at **23.7%** of total sales and the main revenue driver.
- **T-Shirt:** strong secondary performer with consistent demand (**14.9%**).
- **Headphone:** key growth product in the electronics segment, with a double-digit share.
- **Mouse & Hoodie:** supporting products that provide steady volume.

### 9. Product Rank by Units Sold

<img width="375" height="245" alt="image" src="https://github.com/user-attachments/assets/51a88d0b-3da9-49bf-9a1d-a1f8be01b159" />

| Product | Units Sold |
| ------- | ---------- |
| T-Shirt | 82 |
| Cap | 53 |
| Mouse | 45 |
| Shoes | 39 |
| Belt | 34 |
| Keyboard | 21 |
| Headphone | 20 |
| Jacket | 20 |
| Hoodie | 19 |
| Sandals | 14 |
| Laptop Sleeve | 8 |
| **Total** | **355** |

- **T-Shirt** sold the most units (82, about 23% of all units), while **Laptop Sleeve** sold the fewest (8).
- Volume and revenue leaders differ: T-Shirt leads on units, but **Shoes** leads on revenue (23.7%) because of its higher unit price.

## ⚠️ Limitations

- The dataset is **dummy data** (130 records, 70 initial + 60 added). Findings illustrate the analytical method and are not conclusions about a real business.
- The May figure is a simple run-rate extrapolation from 10 days of data (it assumes a constant daily average), not a statistical forecast. Treat it as an indicative estimate.
- May is incomplete (data ends May 10), so month-over-month comparisons involving May need like-for-like periods.
- The 8 blank dates were filled with the date from the row above, which assumes the records are in chronological order.

## 🌻 About

This project is part of my data analyst portfolio.

|  |  |
| -- | -- |
| 📧 Email | [putriayulw10@gmail.com](mailto:putriayulw10@gmail.com) |
| 🌐 LinkedIn | [linkedin.com/in/putriayulichawardani](https://www.linkedin.com/in/putriayulichawardani) |
