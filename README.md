# 📊 Data Analytics Project

## 1. Overview

This project demonstrates an end-to-end data analytics workflow, from raw data to actionable business insights. It combines Python, SQL, and Power BI to clean, analyze, and visualize data, helping identify trends, patterns, and opportunities for better business decision-making.

**Project Objectives:**
- Perform Exploratory Data Analysis (EDA) to understand the dataset.
- Clean and prepare data for accurate analysis.
- Use SQL to answer business questions and extract insights.
- Build an interactive Power BI dashboard.
- Present findings through a structured report and presentation.

## 2. Dataset

- **Dataset Name:** customer_shoppin_behaviour
- **Source:** Kaggle
- **Format:** CSV
- **Number of Records:** 3900
- **Number of Columns:** 19
- **Domain:** Retail, Sales

The dataset contains business-related information used to analyze performance, customer behavior, sales trends, and other relevant metrics.

## 3. Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data analysis and preprocessing |
| Pandas & NumPy | Data manipulation and cleaning |
| Matplotlib, Seaborn & Plotly | Data visualization and EDA |
| MySQL / SQL Server | Querying data and business analysis |
| Power BI | Interactive dashboard development |
| Gamma | Creating the project presentation |
| Jupyter Notebook / VS Code | Writing and executing Python code |
| GitHub | Project documentation and version control |

## 4. Project Workflow

### Step 1: Data Loading
- Imported the dataset into Python using Pandas.
- Examined the dataset structure, columns, and data types.
- Checked the number of rows and columns.

### Step 2: Exploratory Data Analysis (EDA)
- Analyzed numerical and categorical variables.
- Identified trends, distributions, and relationships.
- Created visualizations to understand patterns in the data.
- Explored key business questions.

### Step 3: Data Cleaning & Preprocessing
- Handled missing and duplicate values.
- Corrected data types and inconsistent values.
- Identified invalid records and potential outliers.
- Created a clean dataset for further analysis.

### Step 4: SQL Analysis
- Imported the cleaned data into MySQL or SQL Server.
- Used SQL queries to answer business questions.
- Applied filtering, aggregation, grouping, joins, and subqueries where required.
- Calculated important business metrics and summarized findings.

### Step 5: Power BI Dashboard
- Connected Power BI to the prepared dataset.
- Created measures and calculated columns where necessary.
- Developed KPIs, charts, and interactive filters.
- Designed a dashboard to communicate business performance and insights.

### Step 6: Report & Presentation
- Prepared a report summarizing the methodology, analysis, and findings.
- Created a presentation using Gamma to communicate the project outcomes.
- Highlighted key insights and potential business recommendations.

## 5. Dashboard

The Power BI dashboard provides an interactive view of the project's key performance indicators and business trends.

**Dashboard Features:**
- KPI cards for important business metrics.
- Trend analysis over time.
- Category-wise and segment-wise comparisons.
- Interactive slicers and filters.
- Visual summaries of important findings.

**Dashboard Preview:**


<img width="890" height="494" alt="Screenshot 2026-10-14 225642" src="https://github.com/user-attachments/assets/8f37140b-69d8-402d-a3fa-f3cd5017e400" />



## 6. Key Results & Insights

The analysis focuses on identifying meaningful patterns and converting them into actionable insights.

Key findings include:

- **Business Performance:** [Add your main finding.]
- **Trends:** [Describe an important trend discovered.]
- **Category Analysis:** [Mention the best- or worst-performing category.]
- **Customer Analysis:** [Add a relevant customer insight, if applicable.]
- **Recommendations:** [Describe a practical action based on your findings.]

*Note: Replace these placeholders with insights supported by your actual analysis.*

## 7. Project Deliverables

- Python notebook containing EDA and data cleaning.
- SQL script containing business analysis queries.
- Power BI dashboard file (`.pbix`).
- Project report summarizing the findings.
- Gamma presentation highlighting the project workflow and results.

## 8. How to Run

### Prerequisites
Install Python and the required libraries. You will also need access to MySQL or SQL Server and Power BI Desktop to reproduce the complete workflow.

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
```

### Step 2: Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn plotly jupyter
```

### Step 3: Load the Dataset

Place the dataset in the project's `data/` directory and update the file path in the notebook.

```python
import pandas as pd

df = pd.read_csv("customer_shoping_behavior.csv")

print(df.head())
print(df.info())
```

### Step 4: Run the Analysis

Open Jupyter Notebook or VS Code, then execute the notebook cells in order to perform EDA and data cleaning.

### Step 5: Run SQL Queries

- Create or select a database in MySQL or SQL Server.
- Import the cleaned dataset into a database table.
- Open the SQL scripts in your preferred SQL client.
- Execute the queries to reproduce the business analysis.

Update database connection details and table names according to your setup.

### Step 6: Open the Dashboard

Open the `.pbix` file in Power BI Desktop. If prompted, update the data source and refresh the dataset.

## 9. Repository Structure

```text
customer_analysis_project/
│
├── Power Bi/        # Contains the Power BI dashboard file (.pbix)
├── Python/          # Contains the Jupyter Notebook (.ipynb) for EDA and data cleaning
├── SQL/             # Contains the SQL scripts (.sql) for business analysis
├── data/            # Contains the raw dataset (.csv)
├── Reports/         # Contains the final project report and presentation (PDFs)
│
├── LICENSE          # Open-source license
└── README.md        # Project documentation (this file)
```

## 10. Conclusion

This project demonstrates practical data analytics skills across data preparation, exploratory analysis, SQL-based business analysis, dashboard development, and insight communication.

It showcases the ability to transform raw data into meaningful information that can support data-driven business decisions.
