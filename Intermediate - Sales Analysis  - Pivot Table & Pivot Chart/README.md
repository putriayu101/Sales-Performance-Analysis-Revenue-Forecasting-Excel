# 🧩 Mini Project – Excel Intermediate
This folder contains **intermediate-level Excel mini projects** focused on applying analytical functions and structured data analysis techniques to business-oriented datasets. The projects emphasize **data preparation and clear data visualization** using Microsoft Excel.

## 📁 Dataset
- The entire dataset consists of 130 data points. There are 70 original data points and 60 additional data points.
- The dataset covers the period from January 1, 2024 to May 10, 2024.
- A dummy dataset is used for this project and the dataset used is in the portfolio file.

## 📄 Files
File descriptions in the portfolio
  - **RAW Data Porto**: RAW dataset used in this project
  - **CLEAN Data Porto**: Clean dataset or dataset that has undergone data cleaning
  - **Mapping_Product**: Helper file used in the data cleaning process
  - **Dataset Tambahan**: Additional data added for this project
  - **RILL Fix Data (Pivot)**: FIX dataset used for analysis
  - **Portfolio-PIVOT+Chart**: Analysis results with Pivot tables and Pivot Charts along with analysis notes
  - **Tabel-Help Pivot**: Helper table in one of the analysis segments in the Pivot table
  - **DASHBOARD**: Analysis results formed in dashboard visualization
  - **Dashboard-Sheethelp**: Helper file in dashboard creation

## 🛠 Tools Used
- Microsoft Excel (Pivot Table, Chart, Forecasting, Dashboard) 

## 🎯 Project Focus
The Intermediate level projects aim to practice:
- Lookup and logical functions for analysis
- Dynamic formulas and conditional calculations
- Data aggregation using Pivot Tables
- Analytical visualization

## 📘 Key Skills Practiced
- Lookup & Reference: `VLOOKUP` `AND` `IF`
- Dynamic Arrays: `UNIQUE`, `SORT`, `RANDARRAY`
- Conditional Analysis: `COUNTIF`
- Pivot Tables & Charts
- Visualization Data

## 🧹 Data Preparation
Common preprocessing steps include:
- Removing duplicate records
- Data Format Normalization
- Handling missing or blank values - (Input Blank values with date before the blank)
- Standardizing text formats and categories - (Using `TRIM` `PROPER` `SUBSTITUTE`)
- Create "Mapping_Product" files to help standarize words
- Ensuring dataset consistency

## 📊 Project Output & Analysis - Pivot Table & Pivot Chart
The output of these mini projects typically includes:
- **Total Sales per Category**
  - The **Electronics category contributed the highest revenue of IDR 12,935,000**.  
    <img width="545" height="366" alt="image" src="https://github.com/user-attachments/assets/80cfa220-69f8-48d0-83b4-3f2c255013bf" />

- **Total Sales per Date / Trend Chart** <br>
    <img width="552" height="327" alt="image" src="https://github.com/user-attachments/assets/0f37425b-52fa-4cda-9507-404ce611cf6d" />
  - The highest peak of the trend was in **February at Rp 10,050,000**.
  - There was a **sharp decline** from April to May **by 66%**.
  - After further analysis, the **decline (*orange dotted line*) occurred due to a lack of data or irregular data duration**. The dataset used ends on **May 10, 2024**, so it can be said that **the data is still ongoing or a forecast**. 
  - After further analysis using **forecasting**, the results show that **in May, sales performance was stable at Rp 9,889,000 or 24%**, and even had the potential to match the sales record in February.<br>
    <img width="539" height="200" alt="image" src="https://github.com/user-attachments/assets/db61e120-deb4-43d8-8ce8-2eb1f0cd36d0" /> <br><br>
  - A comparative analysis was also conducted for April 1-10 vs. May. The results showed that **total sales in May were higher than in April**.<br>
    <img width="317" height="238" alt="image" src="https://github.com/user-attachments/assets/11f64595-6eff-4add-b200-d73dacc9015e" />

- **Total Sales High vs Low**
  - From **January to May 2024, approximately 85% of the most popular products were high-priced items**. Consumer interest remained consistent each month, suggesting that high-priced products dominated monthly sales.
    <img width="425" height="399" alt="image" src="https://github.com/user-attachments/assets/e55be7fd-e46e-4aac-b0ff-1ee359a9e412" />

- **Total Sales per Region** <br>
    <img width="554" height="466" alt="image" src="https://github.com/user-attachments/assets/53f43d9e-f92d-4454-b23d-646e88c1819b" />
  - The **highest sales percentage** came from the **West** region, which accounted for **28%** of total sales, followed by the **East, North, and finally South**.

- **Trend Harga Jual (Average per Unit)** <br>
    <img width="553" height="435" alt="image" src="https://github.com/user-attachments/assets/2cb58b99-0297-416a-9be3-ad01541a802e" />
  - On average, **sales from January to May 2024 increased**, peaking in May at Rp 145,500, meaning that **product sales increased gradually each month** (*orange bar graph*).

- **Total Sales of Each Category per Region**<br>
    <img width="674" height="474" alt="image" src="https://github.com/user-attachments/assets/0c1f06e1-1c7b-4990-862e-afe8d2417888" />
  - Judging from the **Sum of Quantity**, the **Accessories** category ranks third in terms of the number of buyers compared to the **Footwear** category, but its total sales are the lowest. This is because the **unit price of Accessories is lower than other categories**, so the graph shows that **Accessories** has the lowest sales.
  - From this, it cannot be said that buyer interest in the **Accessories** category is low in every region. However, we can **increase sales** in this category in several ways, **such as promoting it through social media or launching new products** to attract more customers to purchase items in this category.

- **Customer Segmentation** <br>
    <img width="621" height="352" alt="image" src="https://github.com/user-attachments/assets/778d1276-1c51-46b0-8263-046f26b89628" />
  - The **West is the most profitable region per transaction with the highest average spend of IDR 360,469**, even though it does not have the highest number of transactions (32 orders). **The strategic focus is on upselling** to increase the average spend closer to the total average price.
  - **East is the main transaction area with 38 orders**, but has a low average spend (IDR 296,447).
  - **North has a strong average spend (IDR 322,000)** despite having the fewest transactions (30 orders).
  - **South is the most underperforming region as it has the lowest number of transactions (30 orders) and the lowest average spend (IDR 291,000)**. The South region requires in-depth assistance in terms of promotion to increase the number of customers and pricing strategies to increase spending value. 
  - Based on the data, the West & North regions have customers with high purchasing power. Therefore, the strategic focus is on maintaining loyalty to keep transaction values high.

- **Product Performance** <br>
    <img width="630" height="402" alt="image" src="https://github.com/user-attachments/assets/865ba5b5-bd3e-4fdc-a1f2-3ea35e061fdb" />
  - **Shoes: The top-performing product (23.7%) and our primary revenue driver**, capturing nearly a quarter of the total market share.
  - **T-Shirt: A strong secondary performer** with consistent demand, maintaining a solid 14.9% contribution.
  - **Headphone: A key growth product in the electronics segment**, showing a healthy double-digit market share.
  - **Mouse & Hoodie: Supporting categories that provide steady volume and complete our core product ecosystem.**

## 📊Dashboard 
Excel simple dashboard from this project:														
<img width="1395" height="647" alt="image" src="https://github.com/user-attachments/assets/4dd99deb-0289-4123-8b24-1c869729b6f9" />

## 🎯 Learning Outcome
After completing the Intermediate projects, the learner is able to:
- Prepare and clean datasets for analysis
- Apply intermediate Excel functions effectively
- Perform structured business analysis using Pivot Tables
- Build meaningful charts for reporting
- Translate data into actionable insights

## 📌 Notes
- Projects are based on practical business scenarios
- Focus is on analytical reasoning rather than automation
- This level bridges basic skills and intermediate analysis

## ✅ Status
✔  Completed

