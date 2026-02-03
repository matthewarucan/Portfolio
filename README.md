## Featured Projects
**[Wellness Activity & Sleep Analytics Warehouse](https://github.com/matthewarucan/Wellness-Analytics-Pipeline/blob/main/README.md)**  
Built a production-style SQL analytics warehouse to transform raw wearable activity and sleep data into standardized, analytics-ready datasets, enabling consistent behavioral analysis and business insights.

**[Macro-Driven Market Pivot Analysis](https://github.com/matthewarucan/pivotanalysis-files/blob/main/README.md)**  
Analyzed a structural shift in the sneaker and apparel resale market by combining U.S. macroeconomic trends with multi-year financial data from leading footwear and apparel brands to assess changes in demand, margins, and inventory risk. Validated the findings through a controlled market trial in digital and vintage cameras, confirming stronger unit economics and more stable demand to support a data-driven strategic pivot.

**[Retail Channel Concentration & Revenue-at-Risk Analysis](https://github.com/matthewarucan/Adidas)**  
Developed an Excel-based scenario tool to quantify Revenue-at-Risk from retail channel churn, using Top-N share analysis, HHI, and substitution rate simulations to inform diversification strategy.

## SQL Projects
### [Wellness Activity & Sleep Analytics Warehouse](https://github.com/matthewarucan/Wellness-Analytics-Pipeline/blob/main/README.md)
This project demonstrates the design and implementation of a production-style analytics warehouse to analyze wearable activity and sleep data. Rather than relying on ad-hoc SQL queries, I built a rerunnable, layered SQL pipeline that separates raw data ingestion, cleaning, modeling, and analytics consumption.

Raw Fitbit CSV files are preserved in a STAGE layer as a system of record, transformed into standardized CLEAN tables, and aggregated into analytics-ready MART fact tables and business views. The warehouse includes ETL logic, deduplication, derived metrics (e.g., total active minutes, steps per active minute), and data quality checks to ensure trust and consistency.

**Tools:** MySQL, Tableau

**Key Skills & Concepts:**
SQL data cleaning, data modeling, ETL workflows, time-series analysis, analytics engineering, KPI definition, reusable views, data validation

### [Bellabeat Wellness Tech: Fitbit User Engagement Insights](https://github.com/matthewarucan/Google-Data-Analytics-Case-Study)
Explored Fitbit device usage to identify behavioral trends for Bellabeat, a women-focused health-tech brand. Used SQL to clean and aggregate daily activity, heart rate, and sleep metrics across thousands of users. Created Tableau dashboards highlighting peak engagement windows and fitness patterns, helping guide product marketing and feature prioritization.

**Tools Used:** MySQL, MS Excel, Tableau

## Excel Projects
### [Macro-Driven Market Pivot Analysis](https://github.com/matthewarucan/pivotanalysis-files/blob/main/README.md)  
Analyzed a structural shift in the sneaker and apparel resale market by combining U.S. macroeconomic indicators with public financial disclosures from leading footwear and apparel brands. Evaluated trends in inflation, real wage growth, consumer savings, and debt alongside multi-year revenue, margin, and inventory data from Nike, Adidas, and Ralph Lauren to determine whether declining resale performance was cyclical or structural. Findings showed that reduced purchasing power, elevated inventory levels, and increased discounting compressed resale margins and increased inventory risk across discretionary categories.

Validated these insights through a controlled market trial in the digital and vintage camera category. Tested pricing, sell-through rates, and customer willingness to pay for fully tested, complete products, achieving net profit margins of ~45% and sell-through rates near 80% across two months. This project demonstrates end-to-end business analysis: identifying macro risk, interpreting financial statements, running real-world experiments, and using data to support a strategic pivot.

**Tools Used:** Microsoft Excel
**Key Skills & Concepts:** Macroeconomic analysis, financial statement analysis, inventory and margin diagnostics, demand sensitivity, experimental validation, data-driven decision making

### [ER Games: Launch Strategy Evaluation](https://github.com/matthewarucan/ER-Games)
Modeled the launch strategy for ER Games’ new puzzle-RPG by analyzing player feedback, demographic segments, and regional sales projections. Used Excel to calculate KPIs, run A/B testing scenarios, and build classification models forecasting market performance. Created Tableau dashboards summarizing top launch regions and projected adoption curves, supporting go/no-go decisions by product stakeholders.

**Tools Used:** MS Excel, Tableau, JMP

### [Retail Channel Concentration & Revenue-at-Risk Analysis](https://github.com/matthewarucan/Adidas)
Performed a channel concentration and risk analysis on Adidas U.S. sales data to assess revenue dependency across Retailer × Region × State × City combinations. Used Excel to create a dynamic scenario tool and KPI dashboard that quantified Revenue-at-Risk (RaR) with adjustable substitution assumptions. Calculated Herfindahl–Hirschman Index (HHI) quarterly, revealing a shift from high concentration (HHI = 0.445 in 2020 Q1) to low (HHI = 0.021 in 2021 Q4). Identified critical channels (>2% of revenue) and provided actionable recommendations to diversify mid-tier partnerships, protect high-risk accounts, and monitor channel risk over time.

Mined over 1 million Airbnb listings to surface trends in guest reviews, listing quality, and seasonal pricing. Used Tableau to visualize key drivers of booking demand, including property type, availability windows, and review sentiment. Created visual summaries of high-converting listings to inform host strategies and market positioning.

**Tools Used:** Microsoft Excel (PivotTables, XLOOKUP, KPI Dashboards, Conditional Formatting)

## Tableau Projects
### [Sales Trends Visualization: eBay Seasonal Performance Dashboard](https://github.com/matthewarucan/Sales_Trends_Dashboard/blob/main/README.md)
Developed an interactive Tableau dashboard to analyze four years of personal eBay sales data (2021–2024) and identify seasonal trends by day, week, and month. The dashboard highlights peak revenue periods (e.g., Week 31, August weekends) and underperforming intervals (e.g., Week 53, October) through dynamic visuals.

Integrated KPIs, reference lines, and tooltips reveal that Sundays and Saturdays consistently lead in sales**, while Q4 shows a significant decline. This visualization supports strategic planning around promotional timing, free shipping campaigns, and Q4 recovery initiatives.

**Tools Used:** Tableau


## Python Projects
### [San Francisco Airbnb Regulation Impact Analysis](https://github.com/matthewarucan/Airbnb)
Evaluated the impact of San Francisco’s 2018 Airbnb regulations on housing markets using a Difference-in-Differences (DiD) approach. Cleaned and merged rent (ZORI), home value (ZHVI), and Airbnb listing datasets at the ZIP-code level, then classified areas by Airbnb activity intensity. Found that rent growth slowed in high-Airbnb ZIP codes post-policy, while home values continued to rise—suggesting the regulation curbed rental pressure without discouraging long-term investment. Delivered actionable insights through visualizations and statistical modeling using Python.

**Tools Used:** Python (Pandas, GeoPandas, Statsmodels, Matplotlib), Zillow/Inside Airbnb datasets

### [E-Commerce Revenue Optimization & Sales Trend Analysis](https://github.com/matthewarucan/E-commerce-Analytics/blob/main/README.md)
Conducted an end-to-end analysis of personal eBay sales data over a four-year span to identify drivers of seasonal revenue drops, particularly in Q4. Cleaned and transformed raw transaction data using Python (Pandas), then performed descriptive and time-series analyses to uncover trends. Key findings included a 111% increase in revenue from items offering free shipping and a 94% drop in Christmas-season sales compared to back-to-school periods. Delivered actionable strategies, such as targeted Q4 promotions, free shipping campaigns, and optimization of top-performing categories like men’s shoes.

**Tools Used:** Python (Pandas), MS Excel, Tableau


