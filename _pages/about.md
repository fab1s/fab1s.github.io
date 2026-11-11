---
title: About Me
permalink: /
layout: single
---

I am a Research Engineer at the Methods Centre, Lund University, working at the intersection of **sociology**, **quantitative methods**, and **geospatial analysis**. I develop a research data platform for the Faculty of Social Sciences, built by social scientists for social scientists. I am also in the early stages of exploring how GPS-based mobility data and sociological theory can help us understand where people from different social groups spend time and how much their routines overlap.

I earned my M.Sc. in Social Scientific Data Analysis at Lund University in 2025, following a B.A. in Sociology with a minor in Economics at LMU Munich. My [master's thesis, *Social Infrastructure and Structural (Dis)advantage*](https://lup.lub.lu.se/luur/download?func=downloadFile&recordOId=9209189&fileOId=9209190), developed with RISE, assessed equity in access to social infrastructure in Skåne County using GIS, road network accessibility, and geographically weighted regression.

## Selected projects

{% assign projects = site.portfolio | sort: 'order' %}
{% assign selected_projects = projects | slice: 0, 3 %}
<div class="project-list">
{% for project in selected_projects %}
  {% include project-card.html project=project heading='h3' %}
{% endfor %}
</div>

[All projects →](/projects/)

## Conference presentations

### Infrastructure, Race, and Urban Change in Brazil – Who Benefits?

<figure class="paper-figure conference-poster">
  <a class="conference-poster__preview" href="{{ '/files/brazil-infrastructure-cs2nordics-2026.pdf' | relative_url }}">
    <img src="{{ '/images/brazil-infrastructure-cs2nordics-2026.webp' | relative_url }}" alt="" width="595" height="840" loading="lazy">
    <span>View poster (PDF)</span>
  </a>
  <figcaption class="conference-poster__details">
    <p><strong>CS2Nordics 2026</strong><br>
    22 September 2026 · Aalborg University, Copenhagen</p>
    <p><a href="{{ '/projects/brazil-infrastructure/' | relative_url }}#flash-presentation">Flash presentation</a></p>
  </figcaption>
</figure>

## Experience

**Research Engineer** · [Lund Social Science Methods Centre, Lund University](https://www.sam.lu.se/en/research/lund-social-science-methods-centre)<br>
*May 2026–present · Sweden*

- Leading development of a research data platform for the Faculty of Social Sciences, enabling discovery and exploration of large datasets.
- Leading quantitative research on infrastructure investment patterns across Brazil using computational and ecological methods with geospatial data.

**Master Thesis Student** · [Research Institutes of Sweden (RISE)](https://www.ri.se/en/urban-development/architecture-and-planning/project/model-for-measuring-development-in-city-and)<br>
*February–May 2025 · Sweden*

- Applied GIS to assess equity in access to social infrastructure in Skåne County.
- Used road network-based accessibility metrics and geographically weighted regression.

**Research Intern** · [Research Institutes of Sweden (RISE)](https://www.ri.se/en/urban-development/architecture-and-planning/project/model-for-measuring-development-in-city-and)<br>
*August–October 2024 · Sweden*

- Analysed and visualised spatial data for the City-Core Index using GIS in R.
- Processed datasets and integrated APIs to support urban research.

**Project Assistant** · [Sociology Department, Lund University](https://www.soc.lu.se/en/start)<br>
*April–December 2024 · Sweden*

- Used R to wrangle, analyse, and visualise ClinicalTrials.gov data.
- Prepared a dataset supporting a [published paper](https://www.tandfonline.com/doi/full/10.1080/09581596.2026.2670065) and a manuscript currently under review.

## Skills

- **Programming:** R (advanced), SQL (intermediate), Python (beginner), Agentic engineering (via VS Code)
- **Tools:** Microsoft Excel (intermediate), Microsoft PowerPoint (intermediate), Microsoft Word (intermediate)
- **Language:** English (fluent), German (native), Portuguese (native), Mandarin (pre-intermediate, HSK3)
- **R Programming:** Data wrangling & visualization (tidyverse, ggplot2, dplyr), Regression (linear, logistic, mixed), ML (kNN, Naive Bayes, LDA, text/sentiment analysis), Web scraping (rvest, HTML, CSS, XPATH), GIS (sf, terra), Reporting (R Markdown, Quarto)
- **Certifications:** Data Scientist Associate Certificate ([DataCamp](https://www.datacamp.com/certificate/DSA0014363776447)) in R; SQL Associate Certificate ([DataCamp](https://www.datacamp.com/certificate/SQA0013090643605))

## Education

**M.Sc. Social Scientific Data Analysis**  
Lund University · 2023–2025

**B.A. Sociology, minor in Economics**  
LMU Munich · 2019–2023
