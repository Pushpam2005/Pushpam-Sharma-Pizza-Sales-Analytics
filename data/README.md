# Pizza Sales Analytics & Business Intelligence

## Project Overview

This project analyzes pizza sales data and presents business intelligence insights through an interactive Microsoft Power BI dashboard.

The project focuses on:
- KPI monitoring
- Revenue and order trends
- Product/category/size performance
- Time and operational analysis
- Advanced analytics using Power BI
- Business-oriented insights and recommendations

The Power BI report contains six pages:
1. Executive Dashboard
2. Product Performance
3. Time & Operational Analysis
4. Advanced Analytics
5. Pizza Details
6. Pizza Tooltip

## Problem Statement

Pizza businesses generate large volumes of transactional sales data. Without structured analysis, it can be difficult to identify revenue trends, high- and low-performing products, peak operating periods, and areas requiring attention.

This project converts sales data into business-oriented information that can support decisions related to products, promotions, operations, and performance monitoring.

## Objectives

1. Analyze overall revenue, orders and quantity sold.
2. Monitor year-over-year revenue performance.
3. Identify high- and low-performing pizza products.
4. Analyze performance by category and pizza size.
5. Identify important day, hour and day-part patterns.
6. Provide interactive filtering and drill-down analysis.
7. Use Power BI advanced analytics features to explore business drivers.
8. Translate analytical findings into actionable business recommendations.

## Dashboard

The main deliverable is `PushpamSharma_Project.pbix`.

### Executive Dashboard
Provides KPI-level monitoring and revenue/category analysis.

### Product Performance
Provides product ranking and identifies products that may be promoted or reviewed.

### Time & Operational Analysis
Analyzes revenue by day, hour, day-part and month.

### Advanced Analytics
Uses Power BI Decomposition Tree, Key Influencers, Q&A and ranking analysis.

### Pizza Details
Provides detailed product-level analysis.

### Pizza Tooltip
Provides contextual information such as pizza name, revenue, orders, quantity, revenue contribution and rank.

## Technologies Used

- Microsoft Power BI
- Power Query / Power BI data transformation
- DAX measures
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- GitHub

## Project Structure

```text
PushpamSharma_Pizza_Sales_Analytics_Submission/
│
├── README.md
├── requirements.txt
├── PushpamSharma_PizzaSalesAnalytics.ipynb
├── PushpamSharma_Project.pbix
│
├── data/
│   └── README.md
│
└── PushpamSharma_ProjectReport.docx
```

## Dataset

**Important:** The internship session instructed students not to reuse the exact dataset used in the internship/masterclasses. The dataset used for this project must therefore be independently sourced or otherwise confirmed as different from the internship dataset.

Add the verified dataset source here before final submission:

> Dataset source: **[PASTE VERIFIED DATASET URL HERE]**

If the dataset is stored locally, place it in:

```text
data/
```

Do not commit a dataset to GitHub if its license or redistribution terms do not permit it.

## Python Analysis

`PushpamSharma_PizzaSalesAnalytics.ipynb` provides a reproducible Python analysis workflow covering:

- Dataset loading
- Data inspection
- Missing-value checks
- Duplicate checks
- Data-type preparation
- Descriptive statistics
- KPI calculations
- Category analysis
- Product analysis
- Time analysis
- Business observations

The notebook is intentionally written so that the dataset can be validated before analysis rather than silently assuming a particular source.

## How to Run the Python Notebook

### 1. Install Python

Use Python 3.10 or newer.

### 2. Create a virtual environment

Windows PowerShell:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

### 3. Install dependencies

```powershell
pip install -r requirements.txt
```

### 4. Add the verified dataset

Place the CSV file in the `data/` folder and update the `DATA_PATH` variable in the notebook if required.

### 5. Start Jupyter

```powershell
jupyter notebook
```

Open:

```text
PushpamSharma_PizzaSalesAnalytics.ipynb
```

## How to Open the Power BI Project

Open:

```text
ICT Project.pbix
```

using Microsoft Power BI Desktop.

If the dataset is stored externally, update the data source/path in Power BI and refresh the model.

## Business Intelligence Flow

```text
Raw Sales Data
      ↓
Data Cleaning & Preparation
      ↓
Exploratory Data Analysis
      ↓
KPI & Trend Analysis
      ↓
Power BI Dashboard
      ↓
Advanced Analytics
      ↓
Business Insights
      ↓
Recommendations / Actions
```

## Key Business Questions

The dashboard is designed to answer questions such as:

- What is the overall revenue performance?
- How are current results changing compared with the previous year?
- Which pizza categories contribute most to revenue?
- Which products perform strongly?
- Which products may require review?
- Which pizza sizes contribute most to sales?
- Which days and hours have stronger demand?
- Which day parts require operational attention?
- What factors can be explored through Power BI advanced analytics?

## Recommendations Framework

Final recommendations should be based on the verified dataset results and should follow this structure:

```text
Finding → Business Implication → Recommended Action
```

Examples of action areas include:
- Product promotion
- Product review/discontinuation analysis
- Peak-period staffing
- Inventory planning
- Targeted promotions during lower-demand periods
- Monitoring year-over-year performance

Do not claim a specific finding unless it is supported by the actual dataset/dashboard.

## Project Report

The project report is provided in:

```text
docs/PushpamSharma_ProjectReport.docx
```

It documents the project background, objectives, methodology, dashboard pages, analytics approach, limitations and submission checklist.

## Important Submission Check

Before submitting to BharatCares/IBM:

- [ ] Confirm that the dataset is not the exact internship/masterclass dataset.
- [ ] Add the verified dataset URL to this README.
- [ ] Run all cells in `PushpamSharma_PizzaSalesAnalytics.ipynb`.
- [ ] Check that the Power BI file opens correctly.
- [ ] Check the report screenshots and replace any placeholders if necessary.
- [ ] Confirm the GitHub repository contains the required project files.
- [ ] Do not upload passwords, API keys, tokens or private information.
- [ ] Do not submit a ZIP if the submission instructions prohibit ZIP files.

## Author

**Pushpam Sharma**

Academic Internship: **Data Analytics with AI**

