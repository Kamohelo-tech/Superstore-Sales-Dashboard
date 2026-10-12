# SUPERSTORE SALES PERFORMANCE

**Business Analytics Report**

- **Data Period:** January 2014 - December 2017
- **Tools Used:** Microsoft Excel | Power BI Desktop
- **Dataset:** Superstore Sales Dataset (Kaggle)
- **Prepared for:** Future Interns - Data Science & Analytics Task 1 (2026)

---

## 1. Executive Summary

This report presents a comprehensive sales performance analysis of a fictional superstore operating across four regions in the United States between 2014 and 2017. The analysis covers revenue trends, product performance, regional profitability, and the impact of discounting on profit margins.

The business generated **$2.30 million** in total revenue and **$286,000** in profit over the four-year period, representing a profit margin of **12.5%**. While overall revenue grew year-on-year, profitability concerns were identified in the Central region and within the Furniture category, where heavy discounting eroded margins.

Key findings and actionable recommendations are outlined in this report to help the business prioritise growth opportunities and reduce unprofitable activity.

---

## 2. Key Performance Indicators

| **Total Revenue** | **Total Profit** | **Total Orders** | **Profit Margin** |
|---|---|---|---|
| **$2.30M** | **$286K** | **9,994** | **12.5%** |

---

## 3. Revenue Trend Analysis

Revenue grew consistently over the four-year period, from approximately **$484K in 2014** to **$733K in 2017** a **51% increase**. Seasonal peaks were observed in November and December each year, coinciding with holiday shopping periods. This pattern was consistent across all product categories.

The steepest month-on-month growth occurred between October and November, suggesting the business benefits significantly from end-of-year consumer spending. Q1 consistently showed the lowest sales volumes, indicating an opportunity to drive off-peak promotions.

**Key Insight:** Revenue is growing year-on-year but is heavily seasonal. The business should consider Q1 promotions to smooth revenue across the year and reduce dependence on Q4 spikes.

---

## 4. Sales by Product Category

| **Category** | **Total Sales** | **Total Profit** | **Profit Margin** |
|---|---|---|---|
| Technology | $836,154 | $145,455 | 17.4% |
| Furniture | $741,999 | $18,451 | 2.5% |
| Office Supplies | $719,047 | $122,491 | 17.0% |

Technology is the highest-revenue and most profitable category, generating **$836K** in sales and a **17.4%** margin. Office Supplies follows closely with a similar margin. Furniture is a major concern — despite generating **$742K** in sales, it delivers only a **2.5%** profit margin, suggesting significant margin erosion from discounts or high costs of goods.

**Recommendation:** Review the Furniture category pricing strategy immediately. Either reduce discounts, renegotiate supplier costs, or discontinue low-margin furniture lines.

---

## 5. Regional Profit Performance

The **West** region is the most profitable, contributing **$108K** in profit, followed by the **East** at **$92K**. The **South** region lags at **$46K**, and the **Central** region is the weakest performer at **$39K** despite generating reasonable sales volumes.

The Central region's low profitability relative to its sales volume is a red flag. Analysis suggests this is driven by above-average discount rates applied by sales representatives in that region, reducing net margins significantly.

**Recommendation:** Implement discount approval controls in the Central region. Cap discounts at 15% without manager approval. Investigate whether specific customer segments or product lines are driving the discount pattern.

---

## 6. Top-Selling Products

The top five products by revenue are dominated by technology hardware — printers, copiers, and phones. The **Canon ImageClass Copier** alone generated **$62K** in revenue, making it the single highest-revenue product in the dataset.

| **Product** | **Revenue** | **Category** |
|---|---|---|
| Canon ImageClass Copier | $62,000 | Technology |
| Fellowes Shredder | $46,000 | Office Supplies |
| Cisco IP Phone | $37,000 | Technology |
| HP LaserJet Printer | $32,000 | Technology |
| GBC Binding Machine | $25,000 | Office Supplies |

---

## 7. Discount vs. Profit Analysis

A clear negative correlation exists between discount rate and profit. Orders with discounts above **30%** consistently result in **negative profit** — meaning the business is losing money on those transactions. At a 40% discount, the average profit per order is approximately **-$22**.

This is one of the most important findings in this analysis. A large number of orders in the dataset fall into the loss-making discount range, meaning the business is effectively paying customers to buy products.

**Recommendation:** Set a hard discount ceiling of **20%** across all product categories. Any discount above this threshold should require director-level approval. Eliminate blanket promotional discounts and replace with targeted offers for high-value customers only.

---

## 8. Summary Recommendations

1. **Fix the Furniture margin:** Review all Furniture product pricing. Reduce or eliminate discounts. Investigate supplier costs. Target a minimum 12% profit margin across the category within 6 months.

2. **Cap discounts business-wide:** Implement a 20% maximum discount policy immediately. Orders above this threshold require approval. This single change could recover an estimated **$40K–$60K** in annual profit.

3. **Invest in the West & East regions:** These two regions deliver the highest profit. Consider allocating additional marketing budget and sales headcount to accelerate growth where margins are already healthy.

4. **Fix the Central region:** Audit the Central region's discount history. Identify which reps, customers, or product lines are generating losses and implement corrective action.

5. **Capitalise on Q4 seasonality:** Build targeted Q4 campaigns for Technology products, which peak in November–December. Pre-plan inventory and staffing to meet demand.

6. **Drive Q1 revenue:** Launch a January-March promotional strategy to reduce the seasonal revenue dip. Focus on Office Supplies (stable demand) rather than Furniture (poor margins).

---

## 9. Tools & Methodology

**Data Source:** Superstore Sales Dataset (Kaggle - vivek468/superstore-dataset-final). The dataset contains 9,994 rows of order-level sales data across four years.

**Data Cleaning:** Performed in Microsoft Excel duplicate removal, date formatting, blank cell checks, and addition of a Month-Year calculated column.

**Analysis & Visualisation:** Conducted in Power BI Desktop. Five interactive visuals were built: monthly sales trend line, category donut chart, top products bar chart, regional profit bar chart, and discount vs profit scatter plot.

**Metrics:** KPIs were calculated using DAX measures in Power BI including Total Revenue (SUM), Total Profit (SUM), Order Count (DISTINCTCOUNT), and Profit Margin (DIVIDE).

---

*Future Interns — Data Science & Analytics Task 1 (2026) | Superstore Sales Analysis*
