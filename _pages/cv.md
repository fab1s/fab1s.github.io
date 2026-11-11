---
title: "Curriculum vitae"
permalink: /cv/
layout: single
author_profile: true
---

{% assign cv_url = site.author.cv | relative_url %}

[Download my CV (PDF)]({{ cv_url }}){: .btn .btn--primary}
{: .cv-actions }

<figure class="paper-figure cv-preview">
  <iframe class="cv-pdf" src="{{ cv_url }}" title="Fabio Schreiber curriculum vitae" loading="lazy"></iframe>
  <figcaption><span class="paper-figure__label">PDF preview</span></figcaption>
</figure>
