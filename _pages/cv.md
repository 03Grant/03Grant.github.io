---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download the PDF version](/files/YinghaoHe_CV.pdf)

Education
======
* **Ph.D. in Computer Science**, Purdue University, West Lafayette, August 2025 – present
  * GPA 4.0/4.0
* **B.Eng. in Software Engineering**, Tongji University, Shanghai, September 2021 – June 2025
  * GPA 4.88/5.0, rank 4/228

Research experience
======
* **Mitigating sycophancy and contextual stubbornness in LLMs**, Purdue University and Analogy AI, May 2026 – September 2026
  * Developed CoPE-Bench to jointly evaluate sycophancy and contextual stubbornness across six conditions involving user pressure and contextual evidence.
  * Proposed SPAE, a training-free attention-steering method that uses model-identified token spans to suppress user pressure and amplify contextual evidence.
  * Evaluated SPAE across five backbones (4B to 27B) against six baselines. On Qwen3.5-9B, reduced pressure following from 24.5% to 6.0% and improved contextual updating from 50.5% to 60.2%, with no accuracy loss on no-conflict controls.
* **Disk-based vector retrieval**, Purdue University, August 2024 – April 2026
  * Designed and implemented a disk-based vector retrieval system using cluster-centroid indexing to support datasets exceeding memory capacity.
  * Developed a hybrid retrieval strategy combining compressed in-memory vector representations with multiple disk-reading methods.
  * Implemented estimated-distance filtering to exclude over 90% of candidate vectors before disk reads, reducing I/O while maintaining retrieval accuracy.

Work experience
======
* **Summer Research Intern**, [Analogy AI](https://analogyai.ai/), May 2026 – August 2026
  * Developed the sourcing and evaluation components of an agentic pipeline that converts natural-language data requests into curated datasets for LLM training.
  * Built agent-callable search tools across the web and specialized data platforms, alongside an agentic crawler for permitted websites, to scale raw-data collection.
  * Designed an evaluation loop combining agent-based assessment with external validation to identify deviations from user requirements and guide iterative data curation.

Honors and awards
======
* National Scholarship, Ministry of Education of China, 2021–2022 (top 1% of undergraduates nationwide)
* First-class Scholarship, Tongji University, 2022–2023 (top 3%)
* Merit Student, Tongji University, 2021–2022

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Skills
======
* Programming languages: C/C++, Python, Java, C#, Go, R
