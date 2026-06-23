# Netflix-Pandas-Analysis
This project provides an end-to-end data analysis of the Netflix movies and TV shows dataset. The primary objective was to transform raw, unstructured metadata into a clean, query-ready format to uncover global content trends.

# Technical Workflow
Data Cleaning: Addressed data integrity issues by identifying and handling missing values (NaN). Used .dropna() and .fillna() strategies to ensure accurate analysis.
Feature Engineering: Performed complex string manipulation on the duration column, converting text-based data (e.g., "90 min") into numerical integers to enable mathematical filtering.

# Data Transformation: 
Standardized date formats using Python Datetime objects and extracted temporal features (Year/Month) for time-series insights.

Data Filtering & Grouping: Utilized Boolean indexing and .groupby() methods to separate content types and identify top-performing directors and countries.
Key Insights

Successfully separated the library into Movies and TV Shows for specific metric analysis.

Filtered and identified "Long-form" content (movies > 120 minutes).

Mapped content distribution across the top 5 producing countries.

# Tools Used:

Language: Python 3.x

Library: Pandas

Environment: Google Colab / Jupyter Notebook
