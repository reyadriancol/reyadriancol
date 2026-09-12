# Rey Colongon — Data & Analytics Portfolio

Data analyst and data science projects demonstrating hands-on work with SQL, Python
(pandas, scikit-learn), Tableau, and statistical analysis. Background: 15 years in
defense operations and maintenance in Okinawa, Japan; B.S. Business Analytics
(cum laude); M.S. Data Science (2026).

🔗 [LinkedIn](https://www.linkedin.com/in/rey-colongon-1b42aa81/)
📊 [Tableau Public](https://public.tableau.com/app/profile/rey.colongon5143)

---

## Projects

| Project | What it does | Skills | Links |
|---|---|---|---|
| **NTSB Aviation Accident Analysis** | Finds that 91% of maintenance-caused accidents are filed under the component that failed, not under maintenance — and that stricter maintenance regulation correlates with *higher* maintenance findings | PostgreSQL, Python, normalized schema, data validation | [Repo](https://github.com/reyadriancol/ntsb-aviation-accidents) |
| **DoD Contract Spending in Japan** | Finds that a 31-point collapse in market concentration was entirely one fuel supplier — after separating out a 1957 treaty obligation | SQL, PostgreSQL, Python, Tableau | [Repo](https://github.com/reyadriancol/dod-contract-spending-japan) · [Dashboard](https://public.tableau.com/app/profile/rey.colongon5143/viz/DoDContractSpendinginJapanFY2024FY2025/Dashboard1) |
| **Flight Delay Prediction** | Predicts whether a flight arrives 15+ minutes late, using BTS on-time performance data | SQL, Python, scikit-learn, Tableau | [Repo](https://github.com/reyadriancol/flight-delay-prediction) |
| **Regional Sales Analysis** | Multi-view Tableau story: revenue and profit by region, category treemaps, geographic profit mapping, delivery-time analysis | Tableau, LOD expressions, multi-table joins, parameters | [Dashboard](https://public.tableau.com/app/profile/rey.colongon5143/viz/RegionalSalesAnalysis_17867833174440/Story) |

---

## About this portfolio

Each project lives in its own repository and follows the same structure:

```
├── README.md          # problem, data, approach, findings, how to run
├── data/              # not committed — reproducible from the documented source
├── sql/               # queries, numbered in run order
├── notebooks/         # exploration & modeling
├── src/               # reusable Python scripts
└── visualizations/    # exported charts / dashboard workbooks
```

## ⚠️ Data & security note

Every dataset here is **public and unclassified** (e.g., USAspending.gov,
U.S. BTS TranStats, NASA C-MAPSS). Nothing in this portfolio comes from any
employer system, work data, or any non-public source.
This separation is intentional and strictly maintained.
