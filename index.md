---
layout: default
title: DENG YI — Data Science Portfolio
---

# DENG YI

I am an MSc Data Science student at the University of Macau, focusing on Marketing Analytics. I am developing practical skills in Python analysis and data visualization, with an interest in turning clearly defined business questions into evidence that readers can inspect.

## Technical skills in development

- **Python and Pandas:** preparing small datasets, checking categories and totals, and calculating comparisons.
- **Matplotlib:** building labeled charts with clear scales, readable annotations, and accessible descriptions.
- **Data checking:** documenting sources, validating calculations, and distinguishing observations from explanations.
- **Data storytelling:** connecting a research question, a visual finding, and its limitations.
- **GitHub and reproducible work:** organizing source data, analysis scripts, outputs, and documentation in a repository.

## Project showcase

### Macao visitor source markets, 2024–2025

**Research question:** How did Macao's visitor source-market mix change between 2024 and 2025, and which markets accounted for the increase in arrivals?

**Data and approach:** Eight aggregate records cover four source-market categories and two complete calendar years. The analysis uses official Statistics and Census Service releases, with Python, Pandas, and Matplotlib for validation, calculations, and visualization.

![Two panels compare annual growth rates with contribution to the overall increase in Macao visitor arrivals. Taiwan had the highest growth rate, 19.4%, while mainland visitors accounted for 88.0% of the total increase.]({{ '/assets/macao-growth-and-contribution.png' | relative_url }})

**Main finding:** Total arrivals increased from **34,928,650 to 40,069,360 visits (+14.7%)**. Taiwan had the highest proportional growth (**19.4%**), but the much larger mainland market contributed **88.0%** of the total increase. Growth rate and growth contribution answer different questions and have different denominators.

**Marketing relevance:** A large source market can drive most additional demand even when a smaller market grows faster. This distinction helps frame further market research; a budget decision would also need visitor spending, trip purpose, and acquisition costs.

**Limitations:** These are visits, not unique people. Two annual observations cannot reveal seasonality or explain causes. The international category is aggregated, and the data contain no expenditure or conversion measures. The comparison describes 2024–2025, not current 2026 conditions.

**Project repository:** [data-science-project]({{ site.project_repository_url }}) — source records, analysis script, figures, calculation checks, and reproduction instructions.

**Project status:** {{ site.project_status }}

### Sources

- Statistics and Census Service. [2024 annual visitor arrivals](https://www.gcs.gov.mo/news/detail/en/N25AUB2Zwi), published 21 January 2025.
- Statistics and Census Service. [2025 annual visitor arrivals](https://www.gcs.gov.mo/news/detail/en/N26AWC98hd), published 23 January 2026.

The project repository records source definitions, acquisition dates, calculation methods, and reuse conditions.

## Next steps

Obtain classmate feedback on the explanation and chart, make a documented improvement, and consider extending the analysis with compatible monthly and expenditure data.

AI assistance supported code preparation, writing, and validation. This portfolio presents developing skills and inspectable project outputs; it does not claim independent proficiency beyond demonstrated work.
