# Python-Retail-Sales-Revenue-Optimization-Pipeline
A Python data analysis project utilizing Pandas to clean, process, and analyze superstore sales and profit data. Features automated category performance summaries and business metrics tracking.

## 📌 Project Overview
This data analytics project conducts a multi-dimensional evaluation of **5,009 commercial transactions**, mapping the relationships between product portfolios, pricing strategies, and promotional elasticity. While the business demonstrates strong fundamental health with **$2,297,200.86 in gross revenue** and a consolidated net profit margin of **12.47%**, this analysis exposes sharp disparities at the categorical level where aggressive discounting causes severe margin erosion.

### 🐍 Python Libraries Used
  **Import core data analysis and visualization libraries **

`import numpy as np`  
`import pandas as pd`  
`import matplotlib.pyplot as plt`  
`import seaborn as sns`  
`import warnings`
`warnings.filterwarnings('ignore')`

# 1.Total Sales & Profit by Product Category
* As shown in Total Sales & Profit by Product Category, the corporate portfolio contains major performance gaps:
* Technology: The primary value generator, yielding peak overall profits on disciplined discount frames.
* Furniture: High revenue generation but extremely weak absolute profit output. High sales volume masks completely broken unit economics.

<img width="700" height="400" alt="1" src="https://github.com/user-attachments/assets/90c96a42-79fd-4ebd-8a83-8bd8f0a6b9f8" />

# 2.Impact of Discount Level on Average Profit
* 0% to 20% Tiers: Safely profitable. Light discounts (10%) hit peak structural margins, signaling a highly responsive and healthy customer cohort.
* 30%+ Tiers: The profit profile collapses into immediate net deficits. Every incremental unit sold at high discounts aggressively strips cash flow out of the enterprise.

<img width="700" height="400" alt="2" src="https://github.com/user-attachments/assets/12c30ca9-7c89-4c2f-909b-360042c8661d" />

# 3.Total Sales by Region
* Regional Distribution (Total Sales by Region): The West and East regions stand as dominant market strongholds, with the South requiring optimized sales penetration strategies.

<img width="700" height="400" alt="3" src="https://github.com/user-attachments/assets/1bfdd2a2-fe4e-445e-aee3-555032d4a1e4" />

# 4.Monthly Sales Trend Over Time
Chronological Ingestion (Monthly Sales Trend Over Time): A long-term look tracking monthly sales over sequential historical years, illustrating consistent macroeconomic stability mixed with distinct annual cyclical spikes.

<img width="700" height="400" alt="4" src="https://github.com/user-attachments/assets/ae0ce5a7-9251-4fd1-b2b1-dcba068f6168" />

# 5.Lifecycle Analytics (Customer Retention Cohorts)
* A detailed Cohort Matrix tracking repeat activity metrics over a 48-month index.
* This metric monitors customer retention behaviors by first purchase months, serving

<img width="700" height="410" alt="5" src="https://github.com/user-attachments/assets/1270d65b-240e-4219-80f4-e678bf548526" />






