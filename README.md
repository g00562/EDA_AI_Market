# AI Job Market Analysis

## Overview
This project performs exploratory data analysis (EDA) on an AI Job Market dataset to understand trends in AI-related roles across different countries, job titles, and salary ranges.

The analysis focuses on identifying patterns in the global AI job market using statistical summaries and visualizations.

The project is implemented using **Python and Jupyter Notebook**.

---

## Open Report in Git Pages

```
https://g00562.github.io/EDA_AI_Market/
```

---

## Project Objectives
The main goals of this analysis are:

- Understand the structure of the AI job market dataset
- Perform univariate analysis on individual variables
- Perform bivariate analysis between job roles, salary, and country
- Identify patterns in AI job demand
- Analyze salary distribution across job roles and locations

---

## Dataset
Dataset used in this project:

**File:** `AI Job Market Dataset.csv`

Typical attributes in the dataset include:

- job_title
- salary
- country
- experience_level
- employment_type
- company_location
- remote_ratio
- company_size
- job_id (removed during preprocessing)

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas – Data manipulation
- NumPy – Numerical operations
- Plotly – Interactive visualizations

---

## Project Structure

```
AI-Job-Market-Analysis
│
├── AI_Job_Analysis.ipynb       # Main analysis notebook
├── AI Job Market Dataset.csv   # Dataset
├── AI_Job_Analysis.html        # HTML file of notebook
├── AI_Job_Market_Report.pdf    # Report of analysis in pdf file
├── index.html                  # Report of analysis in web formate
├── requirements.txt            # Contains dependencies to install
├── README.md                   # Project documentation
```

---

## Analysis Performed

### 1. Data Loading
The dataset is loaded using Pandas and basic information about the dataset is examined.

Key steps include:
- Dataset shape
- Data types
- Missing values
- Unique values

---

### 2. Data Cleaning
Data preprocessing includes:

- Removing unnecessary columns (e.g., job_id)
- Checking for missing values
- Reviewing unique values for categorical features

---

### 3. Univariate Analysis
Univariate analysis examines individual variables.

Examples include:
- Distribution of job titles
- Distribution of salaries
- Country-wise job counts
- Company size distribution

---

### 4. Bivariate Analysis
Bivariate analysis explores relationships between variables.

Key comparisons include:

- Salary vs Job Title
- Salary vs Country
- Job Role vs Location
- Experience Level vs Salary

---

### 5. Country-Based Analysis
This section analyzes:

- AI job distribution across countries
- Salary differences by country
- Regional demand for AI professionals

---

## Key Insights
Some insights that can be derived from this analysis include:

- Which AI roles are most common
- Countries with the highest demand for AI professionals
- Roles that offer the highest salaries
- Impact of experience level on salary

---

## How to Run the Project

### 1. Clone the repository
```bash
git clone https://github.com/g00562/EDA_AI_Market.git
```

### 2. Navigate to the project folder
```bash
cd ai-job-market-analysis
```

### 3. Install required libraries
```bash
pip install -r requirements.txt
```

### 4. Run the notebook
```bash
jupyter notebook
```

Open:
```
AI_Job_Analysis.ipynb
```

---

## Future Improvements

Possible improvements to this project:

- Add machine learning salary prediction
- Create interactive dashboards
- Build Power BI / Tableau visualization
- Perform time-based trend analysis

---
