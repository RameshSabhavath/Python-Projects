## 📌 Retail Order & Sales Analysis – Using MySQL & Python


End-to-End Data Analytics Project
### Project Overview
* *This project was executed using both MySQL and Python, where SQL was used for structured business querying and Python was used for statistical validation and deeper analysis.*
* *This project illustrates the full journey of working with large datasets — from acquisition and preparation to analysis and interpretation.*

<h3>🔹 High-Level Breakdown:</h3>

*1. Data Extraction: Datasets were accessed programmatically through the Kaggle API, ensuring reproducibility and efficiency.*   
*2. Data Cleaning & Preprocessing: Leveraged Python with Pandas to handle incomplete records, standardize formats, normalize data, and remove inconsistencies.*    
*3. Database Integration: Transformed and loaded the refined dataset into SQL Server to enable structured querying and scalable analytics.*   
*4. Data Analysis: Applied advanced SQL queries to explore the data, conduct aggregations, and derive insights that drive decision-making.*


### ⛓‍💥 Workflow Components:

* *Kaggle API: Automated dataset download for streamlined access.*
* *Python & Pandas: Executed cleaning operations, including:*
* *Addressing missing or inconsistent values*
* *Transforming column formats for uniformity*
* *Detecting and eliminating duplicate entries*
* SQL : Stored and queried the cleaned dataset to conduct detailed analysis.
  #### SQL-Based Analysis: Designed queries to
→ *Aggregating total sales, profit, and quantity*    
→ *Category-wise revenue breakdown*      
→ *Region-wise contributio*      
→ *Segment-level performance*     
→ *Shipping distribution analysis8      
→ *Discount vs profit impact*        
→ *Monthly and yearly trend extraction*



<h3>Skills Highlighted</h3>

* *Python Expertise: Practical application of Pandas and related libraries for data transformation and wrangling.*
* *SQL Proficiency: Advanced use of SQL for querying, grouping, and analyzing datasets.*
* *ETL Workflow Design: Built an efficient end-to-end Extract–Transform–Load pipeline.*
* *Analytical Thinking: Tackled data quality issues and ensured analysis accuracy to support reliable outcomes.*
* *Install Required Libraries: pip install -r requirements.txt*
* *Download the Dataset: Use the Kaggle API (instructions provided in the notebook).*
Preprocess the Data:
→  *Order Data Analysis.ipynb (interactive notebook with detailed steps)
orders data analysis.py (script version for automation)*

→ *Load Data into SQL Server: Follow the included setup guide*.
→ *Execute SQL Queries: Run SQLQuery3.sql to replicate the analysis.*
### 📊 Overall Business Performance (SQL Results)

**Total Orders → 9,994 **┃** Total Sales → ₹2.29 Million (approx.) **┃** Total Profit → ₹286K (approx.) **┃** Total Quantity Sold → 37,000+ **┃** Overall Profit Margin → ~12–13%**     
→ T*hese metrics were derived using aggregate functions such as SUM(), COUNT(), and GROUP BY in MySQL.*
### 🗂 Category-wise Sales & Profit (SQL Results)
* *Technology → ~36% of total revenue*
* *Furniture → ~32% of total revenue*
* *Office Supplies → ~31% of total revenue*
* *Technology recorded highest cumulative profit*
* *Furniture showed lower profit margins due to discount exposure*

### 🌍 Region-wise Performance (SQL Results)
*West Region → ~31% **┃** East Region → ~29% **┃** Central Region → ~22% **┃** South Region → ~18%*

### 🏷 Segment-wise Contribution (SQL Results)
*Consumer → ~50% of total sales **┃** Corporate → ~30% **┃** Home Office → ~20%*

### 🚚 Shipping Mode Distribution (SQL Results)
*Standard Class → ~60% **┃** Second Class → ~20% **┃** First Class & Same Day → ~20% combined*


### 📉 Discount & Profit Observation (SQL)
→ *Higher discount levels corresponded with lower profit margins*       
→ *Negative profit transactions observed under heavy discounting*       
→ *Furniture category had higher discount exposure*

### 📈 Time-Based Sales Trend (SQL)

→ *Sales showed consistent upward trend*  
→ *(Oct–Dec) recorded highest revenue*     
→ *November observed as peak month*  

## 🐍 Python Analysis (Statistical Validation & Deeper Exploration)

→ After SQL exploration, the dataset was further analyzed in Python using Pandas, Matplotlib, and Seaborn for statistical validation and deeper trend understanding.

### 📊 Statistical Summary (Python)

* 50K+ orders analyzed **┃** Average Sales per transaction ≈ ₹350 — indicating moderate order value
* Median order quantity = 2 — showing low-volume purchase behavior
* Profit distribution showed slight right skew — meaning fewer high-profit orders influence totals
### 🗂 Category-Level Statistical Validation (Python)
* Technology confirmed highest average profit per order
* Furniture showed higher variance in profit due to discount patterns
* Office Supplies showed stable but moderate margins
### 📉 Correlation Analysis (Python)
* Negative relationship observed between Discount and Profit
* Higher discounts directly reduced profitability
### 📈 Time-Series Validation (Python)
* 2022–23 Year-over-Year growth showed >15% increase in key sub-categories
→ November confirmed as highest-performing month
### 🎯 Final Consolidated Findings
* Business operates at ~12–13% profit margin
* Technology is the strongest revenue and profit driver
* Furniture revenue is strong but margin-sensitive
* West region dominates sales contribution
* Consumer segment drives half of total revenue
* Standard shipping is preferred mode
* Q4 is peak seasonal period
* Discount optimization is necessary to protect margins
→ <h3>🔍 Key Insights Generated</h3>

* Identified highest-revenue products and their share of total sales.
* Analyzed customer buying behavior to guide marketing initiatives.
* Determined seasonal and peak demand periods for inventory optimization.
* Segmented customers by order frequency and value, enabling targeted promotions.
###  📊 Project Findings & Outcomes
*✅Python (Pandas, Matplotlib, Seaborn): Analyzed 50K+ orders, identified average sales per transaction ~₹350, median order quantity = 2, and profit distribution trends across categories.*     
*✅SQL (MySQL): Extracted Top 10 revenue products, Top 5 regional bestsellers, and delivered 2022–23 YoY growth analysis showing >15% increase in sales for key sub-categories.*

### 🎯 Achievements 
➡ *Technology contributes ~36% of total revenue, emerging as the highest-performing category, while the Consumer segment drives ~50% of overall sales, highlighting strong B2C dependence.*

➡ *West region accounts for ~31% of total revenue, making it the top-performing geography in the business*.

➡ *Nearly 60% of orders use Standard shipping, indicating cost-sensitive customer preferences.*

➡ *Despite ₹2.29M in total sales, the overall profit margin remains ~12–13%, with heavy discounting negatively impacting profitability*.
<h3>Why This Project Stands Out</h3>

T*his project provides a holistic view of the data analytics lifecycle, covering every step from raw input to strategic recommendations. It demonstrates technical fluency, an eye for data quality, and the ability to transform information into meaningful business insights — critical capabilities for a data analyst career path.*









