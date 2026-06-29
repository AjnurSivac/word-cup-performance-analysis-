 # ⚽ FIFA World Cup Performance Analysis (1930–2022)

## Project Overview

This project analyzes FIFA World Cup match data from 1930 through 2022 using SQL, DuckDB, Python, Pandas, and Matplotlib to investigate a simple but compelling question:

> **Which countries have achieved the greatest FIFA World Cup success relative to their population?**

Traditional measures of World Cup success, such as championships, match wins, and goals scored, often favor countries with larger populations and longer football traditions. To provide a more balanced comparison, this project introduces the **World Cup Efficiency Index (WCEI)**, a custom metric that evaluates national team performance relative to population size.

---

## Research Question

**Which countries have achieved the greatest FIFA World Cup success relative to their population?**

---

## Business Problem

Traditional World Cup statistics measure overall success but do not account for differences in population size. Countries with larger populations naturally have access to a larger talent pool, making direct comparisons between nations less meaningful.

This project addresses that limitation by adjusting World Cup performance using historical population data to identify countries that consistently outperform expectations.

---

## Project Highlights

* Analyzed more than 90 years of FIFA World Cup match data using SQL and Python.
* Developed the **World Cup Efficiency Index (WCEI)** to evaluate football success relative to population.
* Combined multiple datasets using SQL joins and data transformation techniques.
* Applied Common Table Expressions (CTEs), window functions, CASE statements, and aggregations to answer a real-world analytical question.
* Created visualizations to communicate insights and identify historical World Cup underdogs.

---

## Datasets

### FIFA World Cup Matches Dataset

The primary dataset contains every FIFA World Cup match from 1930 through 2022, including:

* Tournament year
* Teams
* Match results
* Goals scored
* Tournament stage
* Host nation

### Population Dataset

Historical country population estimates were incorporated to calculate population-adjusted World Cup performance.

---

## Tools and Technologies

* SQL (DuckDB)
* Python
* Pandas
* Matplotlib
* Jupyter Notebook
* Git
* GitHub

---

## Methodology

The project followed the following analytical workflow:

1. Loaded FIFA World Cup match data into DuckDB.
2. Explored and validated the dataset using SQL.
3. Transformed match-level records into team-level performance data.
4. Calculated country-level statistics including:
   * Matches played
   * Wins
   * Draws
   * Losses
   * Goals scored
   * Goals conceded
5. Created a custom World Cup Performance Score based on match outcomes and tournament progression.
6. Loaded and cleaned historical population data.
7. Joined population data with tournament performance using SQL joins.
8. Calculated the World Cup Efficiency Index.
9. Ranked countries by population-adjusted performance.
10. Visualized results using Python.

---

## World Cup Efficiency Index (WCEI)

The **World Cup Efficiency Index (WCEI)** measures how efficiently a country converts its population into World Cup success.

**Formula**

```text
WCEI = Total Performance Score / Population (Millions)
```

A higher WCEI indicates stronger World Cup performance relative to population size.

---

## SQL Skills Demonstrated

* SQL joins
* Common Table Expressions (CTEs)
* CASE statements
* Aggregations
* GROUP BY
* UNION ALL
* Window functions
* Ranking
* Data transformation
* Feature engineering
* Data cleaning

---

## Python Skills Demonstrated

* Pandas
* Exploratory Data Analysis (EDA)
* Data visualization
* Statistical analysis
* Analytical storytelling

---

## Key Findings

Traditional football powers such as Brazil, Germany, Argentina, Italy, and France dominate raw measures of World Cup success.

However, after adjusting for population, several nations emerge as exceptional historical overperformers.

**Uruguay** remains one of the strongest historical examples, winning the FIFA World Cup in 1930 and 1950 despite having a relatively small population.

**Croatia** represents a modern example of sustained overperformance, reaching the FIFA World Cup Final in 2018 and earning third-place finishes in both 1998 and 2022.

Additional World Cup Cinderella stories further support the findings of this analysis:

* Cameroon became the first African nation to reach the World Cup quarterfinals in 1990.
* South Korea reached the semifinals as co-hosts in 2002.
* Costa Rica won the "Group of Death" and advanced to the quarterfinals in 2014.
* Morocco became the first African nation to reach the World Cup semifinals in 2022.

These performances demonstrate that football success is influenced by far more than population size alone. Strong player development systems, coaching, tactical organization, and football culture can allow relatively small nations to compete with and outperform countries possessing much larger populations.

---

## Sample Visualizations

The notebook includes visualizations such as:

* World Cup matches by tournament year
* Countries with the most World Cup wins
* Countries with the most goals scored
* World Cup Performance Score rankings
* World Cup Efficiency Index rankings
* Population versus World Cup performance

*(Screenshots of these visualizations can be found in the `images` folder.)*

---

## Skills Demonstrated

SQL • DuckDB • Python • Pandas • Data Cleaning • Data Transformation • Feature Engineering • SQL Joins • Window Functions • CTEs • Exploratory Data Analysis • Data Visualization • Analytical Storytelling

---

## Future Improvements

Potential future enhancements include:

* Incorporating FIFA World Rankings
* Adding GDP per capita
* Including player market value
* Comparing countries by confederation
* Building an interactive Power BI dashboard
* Building an interactive Tableau dashboard
* Developing predictive machine learning models for future World Cup performance

---

## Conclusion

This project demonstrates how SQL and Python can be combined to answer a meaningful analytical question using real-world data.

By developing the **World Cup Efficiency Index (WCEI)**, this analysis provides a population-adjusted perspective on international football success and highlights countries that consistently outperform expectations.

The findings show that population size alone does not determine success on the world's biggest football stage. Nations such as Uruguay, Croatia, Cameroon, South Korea, Costa Rica, and Morocco illustrate that exceptional football performance is driven by factors beyond population, including player development, coaching, tactical organization, and football culture.

---

## Author

**Ajnur Sivac**

Master of Science in Data Science

**Technical Skills:** SQL • Python • DuckDB • Pandas • Data Visualization • Data Analytics • Machine Learning
