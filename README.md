# ADR-Frequency-Analyzer

A Python-based Pharmacovigilance project that analyzes **Adverse Drug Reaction (ADR)** data to identify severity trends, summarize drug-related safety information, and visualize ADR distributions.

The project demonstrates how Python can be applied to basic pharmacovigilance data analysis using **Pandas**, **SQLite**, and **Matplotlib**.

---

# Project Overview

Pharmacovigilance focuses on monitoring the safety of medicines after they reach the market. ADR analysis helps healthcare professionals and regulatory authorities identify safety trends and support benefit-risk evaluation.

This project simulates a simple ADR analysis workflow by organizing adverse event data, performing severity-based analysis, storing records in a SQLite database, and visualizing ADR severity distribution.

---

# Features

### Data Processing

* Create a structured ADR dataset using Pandas.
* Organize adverse events by drug.
* Store ADR records in a SQLite database.
* Perform grouped data analysis.

### ADR Analysis

* Calculate ADR frequencies.
* Group adverse events by severity.
* Identify the drug with the highest reported ADR count.
* Query severe ADR records using SQL.

### Visualization

* Generate an ADR Severity Breakdown pie chart.
* Display the percentage distribution of Mild, Moderate, and Severe ADRs.

---

# Technologies Used

* Python
* Pandas
* SQLite3
* Matplotlib

---

# Workflow

### Step 1 — Create ADR Dataset

Build a structured dataset containing:

* Drug Name
* ADR Event
* Severity
* Report Count

### Step 2 — Data Analysis

* Group ADR reports by drug.
* Calculate total report counts.
* Identify the drug with the highest number of reported ADRs.

### Step 3 — Database Operations

* Store the processed data in SQLite.
* Query Severe ADR records using SQL.

### Step 4 — Visualization

Generate a pie chart showing the distribution of ADR severity categories.

---

# Example Insights

The project helps answer questions such as:

* Which drug has the highest number of ADR reports?
* How many ADRs are classified as Mild, Moderate, or Severe?
* Which severe ADRs require further attention?
* What is the overall ADR severity distribution?

---

# Learning Outcomes

Through this project, I explored:

* Data manipulation using Pandas.
* Data aggregation using `groupby()`.
* Basic SQL operations with SQLite.
* Database integration in Python.
* Data visualization using Matplotlib.
* Applying Python to Pharmacovigilance workflows.

---

# Future Improvements

* Import ADR data from CSV or Excel.
* Interactive dashboard using Streamlit.
* Signal detection using disproportionality analysis.
* Time-series analysis of ADR reports.
* Generate automated Pharmacovigilance reports.
* Support FAERS and EudraVigilance-style datasets.

---

# Disclaimer

This project uses sample ADR data created for educational purposes and is intended to demonstrate Python applications in Pharmacovigilance. It should not be used for clinical or regulatory decision-making.

---

# Author

**Shashank Limje**

Regulatory Affairs Student | Pharmacovigilance & Python Enthusiast | Continuous Learner
