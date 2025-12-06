📊 Retail Sales Analysis (Excel Project)

# This project analyzes a retail sales dataset using Excel.
# It includes data cleaning, formulas, pivot tables, and a final dashboard.

📁 Files Included

Retail-Sales-Analysis-Excel-Project/
│
├── Retail Sales Analysis Project.xlsx     
│
├── screenshots/
│      ├── dashboard.png
│      ├── dataset_before.png
│      ├── dataset_after.png
│      ├── pivot_tables.png
│      └── analysis.png
│
└── README.md

# 🧼 Data Cleaning (Summary)

# Steps performed in Dataset_After:

- Removed duplicates

- Fixed spelling & inconsistent names

- Trimmed extra spaces

- Corrected dates

- Filled missing Salesperson values

- Calculated new column: Revenue = Quantity × Price

# Excel Formulas Used

- Revenue

- =E2*F2

- =SUM(E2:E51)

- =AVERAGE(H:H)

- =SUMIFS(I:I,C:C,"Snacks")

- =AVERAGEIFS(H:H,C:C,"Bakery")

- =MAX(H:H)

- =MIN(H:H)

- =COUNTA(UNIQUE(B:B))

- =INDEX(B:B,MATCH(MAX(H:H),H:H,0))

- =SUMIFS(I:I,D:D,"South")


# 📊 Pivot Tables Created

- Inside Analysis I created:

- Revenue by Category

- Quantity by Region

- Monthly Revenue

- Salesperson Performance

- Product Sales Summary

# 📈 Dashboard

- The dashboard includes:

- Total Revenue

- Total Orders

- Average Rating

- Top Product

- Category Revenue (Bar Chart)

- Monthly Revenue (Line Chart)

- Region Quantity (Pie Chart)

- Salesperson Table

- Slicers for easy filtering

# Key Insights #

- Snacks & Bakery generate the highest revenue

- East region sells the highest quantity

- Neha and Ashwin are strong Sales persons

- January show high revenue

- Cake is one of the top-selling products

## Author
  Sreesanth k
- Email   : sreesanthk33@gmail.com
- Linkedin: www.linkedin.com/in/
sreesanth-k-5344a8379


