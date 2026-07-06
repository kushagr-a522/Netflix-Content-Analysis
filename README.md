# Netflix Content Analysis
> Status: In Progress | Started July 2026 | Target: July 14, 2026

## About
**Analyst:** Kushagra Yadav  
**Tools:** Python | SQL | Power BI | Excel | Git  
**Dataset:** 8,807 Netflix titles | 2008–2021

---

## Objective
To analyze Netflix's content library and uncover key insights around content type distribution country-wise production, genre trends, and yearly growth -  with actionable recommendations for content strategy.

---

## Tools Used
- **Python** (Pandas, Matplotlib, Seaborn) - Data cleaning, EDA, visualization
- **SQL** (SQLite) - Business queries and aggregations
- **Power BI** —-Interactive dashboard
- **Excel** - Quick pivot table analysis
- **Git & GitHub** - Version control

---

## Dataset
- **Source:** Kaggle - Shivam Bansal
- 8,807 Netflix titles
- **12 columns:** show_id, type, title, director cast, country, date_added, release_year, rating duration, listed_in, description
- **Date range:** 1925 to 2021

---

## Excel Quick Analysis
Quick pivot table showing Movies vs TV Shows distribution:

![Excel Pivot](excel_pivot.png)

| Content Type | Total Titles |
|------------- |------------- |
| Movie        |        6,131 |
| TV Show      |        2,676 |
| **Total**    |     **8,807**|

---

## Business Questions This Project Will Answer
1. Which country produces the most Netflix content?
2. What is the ratio of Movies vs TV Shows on Netflix?
3. Which genres dominate the Netflix library?
4. How has Netflix grown its content library year over year - especially during COVID (2019–2021)?
5. What content ratings are most common and what does that say about Netflix's target audience?

---

## Project Structure
- `netflix_titles.csv` — Raw dataset
- `Netflix_Excel_Analysis.xlsx` — Excel pivot table analysis
- `excel_pivot.png` — Pivot table screenshot
- `Netflix_analysis.ipynb` — Full analysis notebook
- `.gitignore` — Excludes unnecessary files

---

## Progress
- [x] Dataset downloaded and loaded
- [x] Excel pivot table analysis done
- [x] Data structure and null values checked
- [x] Business questions defined
- [x] Null handling strategy documented
- [x] Data cleaning (Python)
- [ ] SQL queries
- [ ] EDA and visualizations
- [ ] Power BI dashboard
- [ ] Business insights write-up