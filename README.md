# COVID-19-Analytics-Insights-Dashboard

Problem Statement

- During the COVID-19 pandemic, governments, researchers, and organizations needed real-time insights into the spread of the virus, vaccination progress, and healthcare readiness. However, raw data from multiple sources was scattered, complex, and difficult to analyze.

- This project addresses the challenge by building an interactive COVID-19 dashboard that:

- Consolidates global and country-level data.

- Tracks cases, deaths, vaccinations, and testing in real-time.

- Provides comparisons across countries and continents.

- Enables drill-down analysis for deeper insights.

---

🔹 Data Source

- Dataset: covid19, You can view and download from here: [Covid19](https://drive.google.com/file/d/1BH-xjWXT5kRS7VBf65riWwanU4LsXN76/view?usp=sharing)

- Data Mode: DirectQuery (live connection to BigQuery for real-time updates)

- SQL Queries: 10 optimized queries used for extracting metrics like cases, deaths, vaccinations, rolling averages, and continent-level comparisons.

---

🔹 Tech Stack / Tools

- Google BigQuery (SQL-based querying, cloud data warehouse)

- Power BI (data visualization & reporting)

- SQL (for data extraction & aggregation)

- DirectQuery Mode (real-time data connection)

- Tags: Power BI BigQuery SQL Data Visualization Analytics COVID-19

---

🔹 Dashboard Features

- ✅ Global Overview Page – Total cases, deaths, vaccinations, death %, and interactive map.
- ✅ Top Countries & Comparisons – Compare top countries by cases, deaths, vaccinations, and tests (toggle via bookmark buttons).
- ✅ Global Trend Page – Time-series of rolling averages and new cases/deaths.
- ✅ 7-Day Rolling Average Page – Drill-through visualization for daily new cases trend.
- ✅ GDP vs Vaccination Analysis – Correlation between economic strength and vaccination coverage.
- ✅ Top 5 Countries in Each Continent – Ranking-based bar charts combining total cases & continent splits.
- ✅ Drill-through Pages – Country/continent-specific breakdowns for detailed insights.

---

## 🔹 Insights from Analysis:

**1. Correlation between GDP and Vaccinated Percent**

![Correlation between GDP and Vaccinated Percent](https://github.com/ianmol3107/COVID-19-Analytics-Insights-Dashboard/blob/main/Visualization%20Snapshots/Correlation%20between%20GDP%20and%20Vaccinated%20Percent.png?raw=true)

**2. Detailed Case View (DTP)**

![Correlation between GDP and Vaccinated Percent](https://github.com/ianmol3107/COVID-19-Analytics-Insights-Dashboard/blob/main/Visualization%20Snapshots/Detailed%20Case%20View%20(DTP).png?raw=true)

**3. Global Overview**

![Correlation between GDP and Vaccinated Percent](https://github.com/ianmol3107/COVID-19-Analytics-Insights-Dashboard/blob/main/Visualization%20Snapshots/Global%20Overview.png?raw=true)

**4. Global Trend**

![Correlation between GDP and Vaccinated Percent](https://github.com/ianmol3107/COVID-19-Analytics-Insights-Dashboard/blob/main/Visualization%20Snapshots/Global%20Trend.png?raw=true)

**5. Top Countries and Comparisons**

![Correlation between GDP and Vaccinated Percent](https://github.com/ianmol3107/COVID-19-Analytics-Insights-Dashboard/blob/main/Visualization%20Snapshots/Top%20Countries%20and%20Comparisons.png?raw=true)

---

🔹 How to Use

- Start at Global Overview for high-level metrics.
- Use filters (date, country, continent) to customize view.
- Navigate between pages via tabs or buttons.
- Use drill-through to analyze country-level details.
- Explore bookmarks to switch between cases, deaths, vaccinations, tests views.
