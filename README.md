# task--04--decodelabs_internship
# 📊 E-Commerce Sales Data Visualization Dashboard

> **Project 4: Data Analytics Industrial Training Kit (Batch 2026) | DecodeLabs**

An interactive, boardroom-ready **Excel dashboard** that turns 1,200 raw e-commerce orders into clear business insights using data cleaning, PivotTables, KPI cards and charts.

---

## 🎯 Objective

Take a raw e-commerce orders dataset, clean it, analyze it, and present the results in a single dashboard that a manager can read at a glance.

## 📁 Repository Structure

```
├── project_4.xlsx      # Final dashboard workbook
├── README.md           # Project documentation
└── screenshots/        # Dashboard preview images (add yours here)
```

## 🗂️ Workbook Sheets

| Sheet | Purpose |
|---|---|
| **Dashboard** | Final view with KPI cards and charts |
| **Raw data** | Original dataset (1,200 orders, 14 columns) |
| **Cleaned data** | Dataset after cleaning and validation |
| **Product Summary** | Orders, revenue, average order value and quantity per product |
| **Monthly Trend** | Orders and revenue by month |
| **Year Trend** | Orders and revenue by year (2023-2025) |
| **Order Status** | Breakdown of Delivered, Shipped, Pending, Cancelled, Returned |
| **Refferal Source** | Orders and revenue by marketing channel |
| **Payment Method** | Orders and revenue by payment type |

## 🧾 Dataset Overview

Columns: `OrderID`, `Date`, `CustomerID`, `Product`, `Quantity`, `UnitPrice`, `ShippingAddress`, `PaymentMethod`, `OrderStatus`, `TrackingNumber`, `ItemsInCart`, `CouponCode`, `ReferralSource`, `TotalPrice`

## 🛠️ Tools & Techniques

- **Microsoft Excel**
- Data cleaning and validation
- PivotTables and `GETPIVOTDATA`
- Formulas (`COUNTA`, `UNIQUE`)
- Charts and dashboard layout design

## 📈 Key Metrics (KPI Cards)

- **Total Orders:** 1,200
- **Total Revenue:** about $1.26M
- **Average Order Value:** about $1,050
- **Unique Customers:** calculated live on the dashboard

## 💡 Key Insights

- **Top products:** Printer and Chair lead in revenue (about $195K each); Printer also has the most orders (181).
- **Marketing:** Instagram is the strongest referral source, with 259 orders and about $275K revenue.
- **Order status:** Only about 19% of orders are *Delivered*, while Cancelled (250) and Returned (247) are high. This is a clear area to investigate in fulfilment and customer experience.
- **Payment methods:** Orders are spread fairly evenly across Cash, Credit Card, Debit Card, Gift Card and Online payments.
- **Yearly trend:** 2023 had the highest revenue; 2025 data is only partial, so it is not a like-for-like comparison.

## 🚀 How to Use

1. Clone or download this repository.
2. Open `project_4.xlsx` in Microsoft Excel (365 recommended, since the dashboard uses the `UNIQUE` function).
3. Go to the **Dashboard** sheet to explore the KPIs and charts.
4. Check the other sheets to see the PivotTables behind each chart.

## 📚 What I Learned

- Cleaning raw data before analysis
- Building PivotTables to summarize large datasets
- Choosing the right chart for each question
- Presenting insights in a way non-technical people can understand

## 🙏 Acknowledgements

Thanks to **DecodeLabs** for the hands-on Data Analytics Industrial Training Kit and internship experience.

## 👤 Author

**[Aryan kumar]**


---

⭐ If you found this project useful, consider giving it a star!
