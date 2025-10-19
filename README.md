# Category Performance Dashboard Automation

### 📌 Project Overview
This project aimed to design and automate **comprehensive category performance dashboards** to monitor sales and growth trends across multiple e-commerce categories.  
The dashboards provided a unified, automated view of all key business metrics — enabling category, seller, and management teams to track performance efficiently and make informed decisions.

### 🧩 Problem Statement
Manually tracking KPIs across multiple data sources (orders, items, traffic, and engagement) was time-consuming and prone to delays.  
A need arose for an automated, **data-driven dashboard** that could consolidate metrics and highlight underperforming areas in real time.

### ⚙️ Approach
I developed a robust SQL solution to aggregate and compare category-level performance metrics — including **GMV**, **Orders**, **Items**, and **Buyers** — across different time periods such as:
- **Last Month (LM)**
- **Current Month (CM)**
- **Current Quarter (CQ)**
- **Current Year (CY)**  
alongside **Year-over-Year (YoY)** comparisons for growth and uplift analysis.

The output of this SQL query directly feeds into **Power BI** and **Google Sheets** dashboards for continuous visualization and automated updates.

### 📊 Key Features
- Automated data pipeline using **SQL (ODPS2)** for large-scale aggregation  
- Dynamic computation of **growth** and **uplift metrics** (Month-over-Month, Quarter-over-Quarter, Year-over-Year)  
- Categorization of performance into **industries** such as Electronics, Fashion, FMCG, Lifestyle, and Digital Goods  
- Seamless integration with **Power BI** and **Excel/Google Sheets** for visualization  
- Multi-granular tracking at **industry, category, and seller** levels  

### 🧠 Key Insights
- Enabled identification of **underperforming segments** and immediate corrective actions  
- Highlighted **growth opportunities** by tracking GMV, orders, and buyer funnel trends  
- Improved **forecast accuracy** through automated performance baselines  

### 🚀 Outcome
- Automated dashboards reduced manual reporting time significantly  
- Enhanced visibility of performance across multiple categories and teams  
- Data-backed insights helped **maximize growth** and **consistently surpass targets**  
- Improved collaboration between **category, commercial, and BI teams**  

### 🛠️ Tools & Technologies
- **SQL (ODPS2)** – Data extraction, aggregation, automation  
- **Power BI** – Visualization and dashboard automation  
- **Excel / Google Sheets** – Lightweight performance reporting  
- **Data Sources** – `daraz_cdm.dwd_drz_trd_core_df` and related transactional tables  

### 📈 Impact
This automation created a single source of truth for category performance, allowing for:
- **Faster, more accurate performance tracking**  
- **Strategic decision-making** driven by data  
- **Sustainable growth through proactive category management**

---

**Hashtags:**  
`#SQL` `#PowerBI` `#DashboardAutomation` `#EcommerceAnalytics` `#CategoryPerformance` `#DataAnalytics` `#GrowthAnalysis` `#BI` `#DataDrivenDecisions` `#Automation` `#Reporting`
