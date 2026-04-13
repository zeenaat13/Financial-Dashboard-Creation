# Financial Dashboard Creation (Power BI)

## 📊 Project Overview
This project started with a raw financial dataset with multiple dimensions, including revenue, costs, profit, cash flow, and receivables, across months, regions, and product/service categories.

At the initial stage, my focus was primarily on understanding the dataset structure. I analyzed column quality, verified that all values were valid (100% valid, no nulls), and explored distinct values to understand how the data was distributed. This helped me realize that the dataset was multi-dimensional and suitable for building a comprehensive financial dashboard.

At this point, I focused on the technical side—focusing on columns and data types — rather than business insights. The real shift happened when I started asking business-driven questions like:

Is the company meeting its revenue targets?
Which products are actually profitable?
Is cash flow stable?
Are customers paying on time?

---

## 🎯 Objectives
- Monitor monthly financial performance  
- Track Revenue, Gross Margin %, EBITDA %, and Net Cash  
- Compare Budget vs Actual results  
- Analyze Product / Service performance  
- Evaluate Receivables Aging  
- Visualize Cash Flow movement  

---

## 🛠 Tools Used
- Power BI Desktop  
- Power Query  
- DAX  

---
## 📁 Repository Structure

- `Financial Dashboard Creation.pbix` – Power BI dashboard file  
- `data/` – Source dataset  
- `Dashboard_Screenshot/` – Dashboard preview images  
- `Financial_Dashboard_Documentation.pdf` – Project documentation  

---
## 🧹 Data Preparation
Using Power Query, I cleaned and structured the dataset by:

Ensuring correct data types (date, numeric, percentage)
Validating that there were no missing or incorrect values
Creating derived columns like Receivables Aging Buckets
Preparing the dataset for time-based and categorical analysis

This step ensured that the data model was reliable and ready for visualization.

---
## 📌 Key Features
- KPI Cards (Revenue, Gross Margin %, EBITDA %, Net Cash)  
- Revenue & Profit Trend  
- Budget vs Actual with Variance %  
- Product / Service Performance  
- Receivables Aging Analysis  
- Cash Flow Waterfall  
- Interactive slicers for Month, Region, Product/Service  

---
## 📊 Dashboard Development
The dashboard was built step by step, focusing on both analysis and storytelling:

- **Revenue & Profit Trend** helped identify monthly fluctuations and performance dips
- **Budget vs Actual Analysis** revealed consistent underperformance and planning gaps
- **Product/Service Performance** highlighted differences in profitability across offerings
- **Cash Flow Waterfall** was one of the most challenging parts, where I had to understand financial flow logic and correct ordering (Inflows → Outflows → Net Cash)
- **Receivables Aging Analysis** provided insights into customer payment behavior and collection efficiency
  <img width="1193" height="677" alt="financial Dashboard" src="https://github.com/user-attachments/assets/3aaa3b8d-3387-4c8c-8360-2d08847fb0f8" />


## ⚠️ Challenges Faced
- Moving from a technical mindset to a business-oriented mindset
- Writing accurate DAX measures and avoiding calculation errors
- Understanding financial concepts like EBITDA and cash flow
- Designing a clean and professional dashboard layout
- Correctly implementing advanced visuals like waterfall charts
- Interpreting visual outputs to generate meaningful insights


---
## 💡 Recommendations for Improvement
-Improve Budget Planning: Revenue consistently falls below budget across multiple months, indicating unrealistic forecasting. The company should incorporate historical trends and seasonality into its budgeting process.

- Focus on High-Margin Products/Services: While revenue is relatively balanced across products, profitability varies. The business should prioritize high-margin offerings and optimize or reassess low-margin ones.

- Region-Specific Strategy: Variations in receivables and performance across regions suggest the need for targeted strategies, such as improving collection efficiency or boosting sales in weaker regions.
- Continuous Monitoring of Variance: Regular tracking of budget vs actual performance should be implemented to quickly identify deviations and take corrective actions.


---
## 🚀 Conclusion
This project was a complete journey from raw data to actionable insights.

It not only strengthened my Power BI skills but also improved my ability to:

Analyze business problems
Communicate insights
Build professional dashboards

Overall, this experience transformed my approach from data handling to data-driven decision making.

## 📄 Documentation
Detailed logic, assumptions, and insights are available in `Financial_Dashboard_Documentation.pdf`.



