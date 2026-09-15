---
title: About me
permalink: /
layout: single
---

I am a Research Engineer at the **Methods Centre at Lund University**. I work at the intersection of social science, quantitative methods, and geospatial analysis, with a focus on infrastructure, accessibility, and inequality.

My current work combines national-scale research on **infrastructure investment in Brazil** with the development of a **research data platform** for Lund's Faculty of Social Sciences.

## Research interests

Social infrastructure and spatial inequality · Geospatial accessibility · Computational social science · Research data platforms

## Selected projects

{% assign projects = site.portfolio | sort: 'order' %}
{% for project in projects limit:3 %}{% include project-entry.html %}{% endfor %}

[All five projects →](/projects/)

## Experience

<div class="entry">
<h3>Research Engineer</h3>
<p class="entry-meta">Lund University · Methods Centre · May 2026–present</p>
<p>Leading a research data platform and quantitative research on infrastructure investment patterns across Brazil.</p>
</div>
<div class="entry">
<h3>Master Thesis Student & Research Intern</h3>
<p class="entry-meta">RISE · Thesis: February–May 2025 · Internship: August–October 2024</p>
<p>GIS-based assessment of social infrastructure accessibility in Skåne County, and spatial data analysis for the City-Core Index.</p>
</div>
<div class="entry">
<h3>Project Assistant</h3>
<p class="entry-meta">Lund University · Sociology Department · April–December 2024</p>
<p>Prepared and analysed ClinicalTrials.gov data for academic research.</p>
</div>

## Education

**M.Sc. Social Scientific Data Analysis**  
Lund University · 2023–2025

**B.A. Sociology, minor in Economics**  
LMU Munich · 2019–2023

## Methods & tools

**Data analysis:** R, tidyverse, regression, text analysis  
**Geospatial:** sf, terra, GIS, accessibility analysis  
**Development & reporting:** SQL, Python, agentic engineering, Quarto, R Markdown

[Full CV](/cv/) · [Theses and research contributions](/research/)
