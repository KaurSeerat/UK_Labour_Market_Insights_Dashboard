# 🇬🇧 UK Labour Market Intelligence Dashboard

> Analysed **100,000+ UK job postings** to uncover hiring trends, salary distribution, and regional demand patterns using Power BI.

[![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=flat&logo=powerbi)](dashboard/)
[![Excel](https://img.shields.io/badge/Data-Excel%20%2F%20CSV-217346?style=flat&logo=microsoftexcel)](data/)

---

## 📊 Dashboard Preview

![Dashboard Overview](dashboard/dashboard_overview.png)

> Download the `.pbix` from `/dashboard/` and open in Power BI Desktop for full interactive filtering by job type, region, and salary band.

---

## 🎯 Business Problem

Recruiters, job seekers, and workforce planners need to answer:

- Which job roles are most in demand in the UK?
- Which regions have the highest hiring activity?
- How does job demand compare to salary levels across industries?
- What proportion of roles are contract vs permanent?

---

## 📈 Key Insights

| Finding | Detail |
|---|---|
| Highest demand role | Care Assistant — reflects sustained healthcare hiring pressure |
| Top hiring region | Greater Manchester (~5,500 postings) |
| Healthcare & Nursing | High demand, mid-range salaries — recruitment pressure point |
| Finance & Consultancy | Higher salaries despite lower posting volume |
| Contract share | Only ~13.4% of total postings — permanent roles dominate |

---

## 💡 Business Recommendations

- Organisations should prioritise healthcare recruitment strategies to address sustained demand
- Employers in high-demand sectors may need to increase salaries to remain competitive
- Recruitment agencies should focus resources on high-demand regions like Manchester
- Job seekers targeting higher pay should consider finance and consultancy roles

---

## 📊 Dashboard Features

- **KPI Summary** — total postings, % contract roles
- **Job Demand Analysis** — most in-demand job titles
- **Regional Analysis** — top UK cities by posting volume
- **Demand vs Salary** — relationship between demand and average salary by category
- **Interactive Filters** — job type (permanent, contract, temporary, apprenticeship)

---

## 🛠 Tools & Technologies

- **Power BI** — dashboard development, DAX measures, Power Query transformations
- **Excel / CSV** — source data and preprocessing

---

## 📂 Repository Structure

```
data/          → source dataset (job postings CSV)
dashboard/     → Power BI .pbix file + dashboard_overview.png
README.md
```

---

## 🚀 Future Improvements

- [ ] Add Python EDA notebook — salary distribution analysis, top skills by region using Pandas and Matplotlib
- [ ] Integrate more recent dataset for year-on-year trend comparison
- [ ] SQL-based analysis layer for deeper segmentation

---

## 👩‍💻 Author

**Seerat Kaur** — Junior Data Analyst

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/seerat-kaur-4878bb249/)
[![GitHub](https://img.shields.io/badge/GitHub-KaurSeerat-181717?style=flat&logo=github)](https://github.com/KaurSeerat)

**Related project:** [Anomaly Detection & Risk Scoring](https://github.com/KaurSeerat/Anomaly-Detection-And-Risk-Scoring) — end-to-end Python + SQL + Power BI analytics on financial transaction data.
