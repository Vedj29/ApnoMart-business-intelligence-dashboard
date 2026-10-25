# ApnoMart — Executive Business Insights
**Reporting period:** 1 May–28 October 2026  
**Tool:** Power BI  
**Dataset:** ApnoMart Sales Dataset (1,200 records)

## Dataset summary
- **Total sales:** 16,261,998.30
- **Total profit:** 4,419,736.17
- **Orders:** 1,200 unique orders
- **Overall profit margin:** 27.18% (total profit ÷ total sales)
- **Data checks:** 1,200 rows, 1,200 unique Order_ID values, no missing values, and no exact duplicate rows detected.

## Insight 1 — Revenue performance
Furniture generated the highest sales at **3,518,270.00**, representing **21.63%** of total revenue. Office Supplies was close behind at **3,380,834.45** (20.79% of revenue). October recorded the lowest monthly sales in the dataset at **2,472,054.20**, while July recorded the highest at **2,957,618.40**.

**So what:** Keep inventory and marketing investment aligned with demand in Furniture and Office Supplies, and investigate the October dip before setting the next quarter’s sales targets. Because the dataset ends on 28 October, October is a partial month and should not be compared directly with complete months without noting that limitation.

## Insight 2 — Profitability and discount review
Office Supplies generated the highest total profit at **1,176,657.32**, with a weighted profit margin of **34.80%** (profit ÷ sales). Electronics generated **558,395.07** profit on **2,957,520.05** sales, giving it the lowest weighted margin at **18.88%**. Electronics also had the highest average recorded discount (**14.06%**).

**So what:** Review Electronics’ product costs, discount rules, and order-level profitability. Test more targeted discounts rather than making a blanket discount reduction; use order-level analysis to determine which products and discount bands erode margin.

## Insight 3 — Customer and payment behavior
Corporate customers contributed the most revenue: **4,311,027.50** across **307 orders**, or **26.51%** of total sales. Cash was the largest payment method by sales at **3,574,076.95** (21.98% of sales), followed by UPI at **3,347,484.50** (20.58%).

**So what:** Protect corporate customer retention through account-focused offers and service, while keeping payment options broad. Test whether encouraging digital payments improves convenience or reduces processing costs before shifting payment incentives.

## Strategic recommendation
For the next quarter, prioritize a **profitability improvement plan for Electronics** while protecting demand in Furniture and Office Supplies. Review Electronics’ product-level margins and discount bands, test targeted discount changes on a small subset of products, and track sales, profit, and weighted margin together. In parallel, investigate the October sales dip using complete-month comparisons, since October data only runs through 28 October.

## Calculation notes
- Overall weighted profit margin = total profit ÷ total sales = **27.18%**.
- Category weighted margin = category total profit ÷ category total sales. This may differ from the simple average of the row-level `Profit_Margin` column.
- October covers **1–28 October 2026** in the provided data, so it is not a full calendar month.
- Currency units were not specified in the CSV; values are reported in the dataset’s numeric units without assuming a currency symbol.
