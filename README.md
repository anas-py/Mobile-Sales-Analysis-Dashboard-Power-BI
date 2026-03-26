# 📊 Mobile Sales Analysis Dashboard — Power BI

> An end-to-end **interactive sales analytics dashboard** built in Power BI, analyzing mobile phone sales performance across Indian cities for multiple brands.

![Dashboard Preview](screenshots/dashboard-overview.png)

---

## 🔍 Project Overview

This Power BI dashboard provides a comprehensive view of mobile phone sales across India. It enables stakeholders to explore revenue trends, customer satisfaction, payment preferences, and city-level distribution — all through a dynamic, filterable interface.

---

## ✨ Key Features

- **KPI Cards** — Total Sales (₹41M), Total Quantity (1K), Transactions (215), Average (₹40K)
- **Geographic Map** — Sales distribution across 15+ Indian cities (Delhi, Mumbai, Hyderabad, Kolkata, etc.)
- **Monthly Trend Line** — Total quantity sold across all 12 months with data labels
- **Customer Ratings** — Rating breakdown (1–5 stars) with percentage analysis
- **Payment Method Pie Chart** — UPI, Debit Card, Cash, Credit Card split
- **Brand Comparison Table** — Samsung, Apple, OnePlus side-by-side metrics
- **Mobile Model Bar Chart** — Top-performing models (OnePlus, iPhone SE, Galaxy N...)
- **Day-wise Sales Trend** — Sales performance by day of week
- **Dynamic Slicers** — Filter by Mobile Model, Payment Method, Brand, Day Name, and Month

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Dashboard development & publishing |
| **DAX** | Calculated measures and KPIs |
| **Power Query (M)** | Data cleaning and transformation |
| **Bing Maps** | City-level geographic visualization |

---

## 📈 Business Insights

- **OnePlus** leads in both quantity (382 units) and transactions (77), with ₹15.18M in sales
- **Apple** achieves the highest avg. transaction value despite fewer units
- **October** was the peak month with 154 units sold
- **Friday** records the highest daily sales at ₹7.2M
- **Credit Card** is the most used payment method (25.89%), followed closely by Cash (25.03%)
- **5-star ratings** dominate at 74 out of total responses (37.2%)

---

## 📁 Project Structure

```
mobile-sales-dashboard/
│
├── MobileSalesDashboard.pbix      # Main Power BI file
├── data/
│   └── mobile_sales_data.xlsx     # Source dataset
├── screenshots/
│   └── dashboard-overview.png     # Dashboard preview
└── README.md
```

---

## 🚀 How to Use

1. Clone or download this repository
2. Open `MobileSalesDashboard.pbix` in **Power BI Desktop**
3. Use the **month slicers** on the left panel to filter by time period
4. Use the **dropdown filters** to slice by Brand, Payment Method, Model, or Day
5. Hover over charts for detailed tooltips

---

## 📌 Dataset Details

- **Domain:** Retail / Consumer Electronics
- **Geography:** India (15+ cities)
- **Brands Covered:** Samsung, Apple, OnePlus
- **Time Period:** Full calendar year (Jan–Dec)
- **Metrics:** Sales revenue, quantity, transaction count, customer ratings

---

## 🙋 Author

**[Mohd Anas]**  
📧 work.anas.py@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/mohdanas-/) | [GitHub](https://github.com/anas-py)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
