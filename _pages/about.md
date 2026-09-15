---
title: About Me
permalink: /
layout: single
---

I am a Research Engineer at the Methods Centre, Lund University, working at the intersection of social science, **quantitative methods**, and **geospatial analysis**. My current work focuses on infrastructure investment in Brazil and a research data platform for the Faculty of Social Sciences.

I earned my M.Sc. in Social Scientific Data Analysis at Lund University in 2025, following a B.A. in Sociology with a minor in Economics at LMU Munich. My [master's thesis, *Social Infrastructure and Structural (Dis)advantage*](https://lup.lub.lu.se/luur/download?func=downloadFile&recordOId=9209189&fileOId=9209190), developed with RISE, assessed equity in access to social infrastructure in Skåne County using GIS, road network accessibility, and geographically weighted regression.

## Experience

**Research Engineer** · Methods Centre, [Lund University](https://www.lunduniversity.lu.se/)  
*May 2026–present · Sweden*

- Leading development of a research data platform for the Faculty of Social Sciences, enabling discovery and exploration of large datasets.
- Leading quantitative research on infrastructure investment patterns across Brazil using computational and ecological methods with geospatial data.

**Master Thesis Student** · Research Institutes of Sweden (RISE)  
*February–May 2025 · Sweden*

- Applied GIS to assess equity in access to social infrastructure in Skåne County.
- Used road network-based accessibility metrics and geographically weighted regression.

**Research Intern** · Research Institutes of Sweden (RISE)  
*August–October 2024 · Sweden*

- Analysed and visualised spatial data for the City-Core Index using GIS in R.
- Processed datasets and integrated APIs to support urban research.

**Project Assistant** · Sociology Department, Lund University  
*April–December 2024 · Sweden*

- Used R to wrangle, analyse, and visualise ClinicalTrials.gov data.
- Prepared a dataset supporting a [published paper](https://www.tandfonline.com/doi/full/10.1080/09581596.2026.2670065) and a manuscript currently under review.

## Skills

- **Programming:** R (advanced), SQL (intermediate), Python (beginner)
- **Analysis:** Data wrangling, visualisation, regression, text and sentiment analysis
- **Geospatial:** sf, terra, GIS, accessibility analysis
- **Development and reporting:** Agentic engineering, Quarto, R Markdown

## Education

**M.Sc. Social Scientific Data Analysis**  
Lund University · 2023–2025

**B.A. Sociology, minor in Economics**  
LMU Munich · 2019–2023

## Selected projects

{% assign projects = site.portfolio | sort: 'order' %}
{% for project in projects limit:3 %}{% include project-entry.html %}{% endfor %}

[All five projects →](/projects/)
