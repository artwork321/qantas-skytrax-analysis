# Qantas Reviews Dashboard (2015–2025)

The project analyzes Qantas flight reviews from Skytrax to uncover customer satisfaction trends, recurring complaints, and route-level insights from 2015 to 2025.

---

## Project Overview

- **Identify Worst Routes:** Shows which flight routes have the highest proportion of bad-to-medium reviews.  
- **Theme Analysis:** Creates themes that cover most aspects of Airline Service, and highlights the most frequent issues.
- **Keyword Analysis:** Extract common words in low-rating reviews to understand deeper what exactly was complaint about.

---

## Data Source

- Skytrax review pages
- Extract, Clean, Transform, and Load to Snowflake by another team
- Repository: https://github.com/MarkPhamm/skytrax-reviews/tree/main

---

## Technologies

- Python with NLTK, Transformer and Pandas
- Jupyter Notebook: [theme_analysis.ipynp](https://github.com/artwork321/qantas-skytrax-analysis/blob/main/python/theme_analysis.ipynb)
- Snowflake
- Power BI Desktop: [Qantas Analysis Power Bi Dashboard](https://github.com/artwork321/qantas-skytrax-analysis/blob/main/report/Qantas_Reviews_analysis_Dashboard.pbix  )

---

## Insights

### Overall Findings

![Overview](https://github.com/artwork321/qantas-skytrax-analysis/blob/main/report/Overview.png)

From 2015 to 2020, Qantas had an average rating of 3/5 across most service categories. This analysis focused on the number of low ratings rather than just the average, as it is a more reliable indicator of specific issues. The number of negative reviews plummeted during the COVID-19 pandemic due to border closures but surged back after 2022 before gradually decreasing, suggesting that service is slowly recovering.

### Post-2022 Performance

![Since 2022](https://github.com/artwork321/qantas-skytrax-analysis/blob/main/report/Since%202022.png)

Since 2022, Value for Money and Ground Service have emerged as the lowest-rated aspects. The most common themes in customer complaints are Delays and Disruptions (36.9%) and Staff Service (14.6%).

A route-specific analysis revealed a clear difference in the nature of complaints:

- Routes from Sydney were primarily associated with Staff Service issues, with reviews describing staff as rude and unhelpful.

- Routes from Melbourne were mainly criticized for flight delays.

For more detail report: [Qantas Review Insights](https://github.com/artwork321/qantas-skytrax-analysis/blob/main/report/Insights.pdf)


---

## Limitation

- Keywords and Themes Extraction can be improved for more accuracy.

---
