# Pizza Sales Analytics & Business Intelligence

**AICTE | IBM SkillsBuild Data Analytics with AI Internship 2026 — BharatCares**

**Author:** Pushpam Sharma

## Project Overview
This project analyzes pizza sales transactions and presents business intelligence insights through Power BI and Python. The analysis focuses on KPI monitoring, revenue and order trends, product/category/size performance, time patterns, and advanced Power BI analytics.

### Power BI report pages
1. Executive Dashboard
2. Product Performance
3. Time & Operational Analysis
4. Advanced Analytics
5. Pizza Details
6. Pizza Tooltip

## Problem Statement
Transactional sales data contains useful information about revenue, orders, product demand, and operating patterns. The project organizes these measures into an interactive analytical workflow so that findings can be communicated as evidence-based business insights and potential actions.

## Objectives
- Analyze overall revenue, orders, and pizzas sold.
- Monitor revenue performance and year-over-year change where applicable.
- Examine product, category, and size performance.
- Identify day, hour, day-part, and monthly patterns.
- Use Power BI advanced analytics to investigate drivers and relationships.
- Translate validated findings into business-oriented actions.

## Dataset
The project uses the **Pizza Place Sales** dataset published by Maven Analytics. Maven describes it as a year's worth of sales from a fictitious pizza place and lists **48,620 records and 12 fields** for the dataset. The original challenge describes the source as four related CSV tables covering orders, order details, pizzas, and pizza types.

**Official dataset source:** https://mavenanalytics.io/data-playground/pizza-place-sales

**Related challenge:** https://mavenanalytics.io/challenges/maven-pizza-challenge

The Excel file included in `data/` is the flattened 12-column project dataset used for the Python analysis. The uploaded file contains **48,620 data rows and 12 columns**, matching the published Pizza Place Sales dataset structure.

> **Internship compliance check:** The internship instructions require that the exact dataset used in internship/masterclass sessions not be reused. The Maven source is documented here, but whether BharatCares/IBM used this same dataset in a session is not established by the public dataset page. Confirm this point against the internship session materials before final submission.

## Dataset Fields
`pizza_id`, `order_id`, `pizza_name_id`, `quantity`, `order_date`, `order_time`, `unit_price`, `total_price`, `pizza_size`, `pizza_category`, `pizza_ingredients`, `pizza_name`

## Technologies Used
- Microsoft Power BI
- Power Query
- DAX
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- OpenPyXL
- GitHub

## Project Structure
```text
PushpamSharma-Pizza-Sales-Analytics/
├── PushpamSharma_PizzaSalesAnalytics.ipynb
├── PushpamSharma_ProjectReport.docx
├── README.md
├── requirements.txt
└── data/
    ├── pizza_sales_excel_file.xlsx
    └── README.md
```

## Python Notebook
`PushpamSharma_PizzaSalesAnalytics.ipynb` provides a reproducible workflow for:
- Loading the Excel dataset
- Inspecting shape, columns, data types, missing values, and duplicates
- Preparing date and time features
- Calculating total revenue, total orders, total pizzas sold, average order value, and average pizzas per order
- Analyzing revenue by category
- Analyzing product performance
- Analyzing revenue by day and hour

### Run the notebook
```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
jupyter notebook
```

Open `PushpamSharma_PizzaSalesAnalytics.ipynb` and run all cells from top to bottom.

## Business Intelligence Flow
```text
Raw Sales Data
      ↓
Data Cleaning & Preparation
      ↓
Exploratory Analysis
      ↓
KPI & Trend Analysis
      ↓
Power BI Dashboard
      ↓
Advanced Analytics
      ↓
Business Insights
      ↓
Potential Actions
```

## Insight Framework
Findings should be communicated as:

**Finding → Evidence → Business Implication → Recommended Action**

Specific numerical claims should be based on the validated dataset and dashboard outputs.

## Submission Checklist
- [x] `PushpamSharma_PizzaSalesAnalytics.ipynb`
- [x] `requirements.txt`
- [x] `PushpamSharma_ProjectReport.docx`
- [x] `README.md`
- [x] Dataset source documented
- [ ] Confirm the dataset was not used in the internship/masterclass sessions
- [ ] Run the notebook from top to bottom before final submission

## Author
**Pushpam Sharma**

AICTE | IBM SkillsBuild Data Analytics with AI Internship 2026
