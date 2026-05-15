# Customer Behaviour Analysis

A complete end-to-end data analytics project focused on analyzing customer shopping behavior using Python, SQL, PostgreSQL, and Power BI.  
The project transforms raw customer transaction data into meaningful business insights through data cleaning, exploratory analysis, SQL querying, and interactive dashboards.

---

## Project Overview

This project analyzes customer purchasing behavior to identify:

- Customer spending patterns
- Product category performance
- Revenue trends
- Customer segmentation
- Purchase frequency
- Rating and review insights
- Age-group based purchasing trends

The project demonstrates a real-world data analytics workflow including:

1. Data Cleaning & Preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Database Integration using PostgreSQL  
4. SQL-based Business Analysis  
5. Interactive Power BI Dashboard Creation  

---

## Tech Stack

### Programming & Analysis
- Python
- Pandas
- NumPy


### Database
- PostgreSQL
- SQLAlchemy
- psycopg2

### Visualization
- Power BI

### Tools
- Jupyter Notebook
- VS Code

---

## Project Workflow

### 1. Data Collection
Customer transaction dataset containing:
- Customer details
- Product information
- Purchase behavior
- Ratings & reviews
- Revenue-related fields

---

### 2. Data Cleaning & Preprocessing

Performed:
- Missing value handling
- Duplicate removal
- Data type correction
- Feature engineering
- Outlier treatment
- Data transformation

Example:
python
df["Review Rating"] = (
    df.groupby("Category")["Review Rating"]
    .transform(lambda x: x.fillna(x.median()))
)




