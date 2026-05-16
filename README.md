Netflix Content Analytics | Tableau
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
---
Project Summary
An interactive Tableau dashboard analyzing 6,000+ Netflix titles to map how the platform's content strategy has evolved — across genres, countries, and release years. Built to answer the question every streaming strategist cares about: what kind of content is winning, and where is it coming from?
---
Business Questions Answered
What is the split between Movies and TV Shows — and has that ratio shifted over time?
Which genres dominate the catalog, and which are underrepresented?
Which countries contribute the most content, and how has global production grown?
---
Tools & Techniques
Area	Details
Visualization	Tableau Public / Tableau Desktop
Analysis Type	Exploratory Data Analysis (EDA)
Features Used	Calculated fields, parameters, filters, sets
Interactivity	Dynamic filters, drill-down by country/genre/year
Data Source	Netflix Movies and TV Shows dataset (Kaggle)
---
Dataset Overview
6,000+ titles spanning Movies and TV Shows
Fields include: Title, Type, Genre, Country, Date Added, Release Year, Rating, Duration
Cleaned and structured for Tableau — handled nulls in Country and Date Added fields, standardized genre categories
---
Dashboard Views
View 1 — Content Overview
KPI tiles: Total Titles, Total Movies, Total TV Shows, % Movie share
Area chart: Content added to Netflix per year (growth trend)
Toggle: Filter between Movies and TV Shows
View 2 — Genre Breakdown
Bar chart: Top genres ranked by number of titles
Highlight: Top genres represent over 50% of total catalog
Parameter: Switch between Movies-only and TV Shows-only genre view
View 3 — Global Content Map
Filled map: Content volume by country of production
Bar chart: Top 10 content-producing countries
Insight: US dominates, but India and UK are significant contributors
View 4 — Movies vs. TV Shows Over Time
Stacked area chart: Movies vs. TV Shows added per year
Finding: Movies account for ~70% of total catalog — but TV Show additions have grown faster since 2016
---
Key Findings
Movies make up ~70% of Netflix's catalog, but TV Show growth has outpaced movies since 2016 — a strategic shift toward episodic content
Top 5 genres represent over 50% of total titles — the platform is concentrated, not diverse
The US produces the most content by far, but India and the UK are the next largest contributors — reflecting Netflix's global expansion strategy
Content additions peaked around 2019 and show a notable dip post-2020, likely reflecting COVID-era production delays
---
Screenshots
> *(Add your Tableau dashboard screenshots here)*
> Recommended: Overview page, Genre breakdown, Global map, Timeline view
Or view live on Tableau Public:
> 🔗 [View Interactive Dashboard]:https://public.tableau.com/app/profile/marykutty.dcruz7171/viz/Netflixdashboard_17703256166090/Netflix
---
How to Explore This Project
Option A — Tableau Public (recommended)
Click the live dashboard link above
Use the filters on the right to explore by country, genre, or year
Hover over any chart element for detailed tooltips
Option B — Tableau Desktop
Download the `.twbx` file from this repository
Open with Tableau Desktop or Tableau Public (free)
All data is packaged inside the workbook — no external connection needed
---
What I Learned
Building calculated fields to derive new dimensions (e.g. content age, decade groupings)
Using parameters to create toggle views — one dashboard, multiple questions answered
Telling a coherent data story across multiple views rather than isolated charts
Designing for non-technical audiences — every chart title is a question, every tooltip explains itself
---
Data Source
Kaggle — Netflix Movies and TV Shows
(Public dataset, free to use for portfolio and educational purposes)
---
Built by Marykutty Dcruz | LinkedIn | Richmond Hill, ON
