---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.E. in Information Engineering and B.A. in French Studies, Shanghai Jiao Tong University, 2027 (expected)

Experience
======
* Sep 2024 ~ Present: Research Assistant
  * Shanghai Jiao Tong University, X-LANCE
  * Contributions included:
    * Designing **agentic frameworks** for scientific question answering: 1 paper accepted by ACL 2025.
    * Developing **question answering datasets** in the domain of artificial intelligence: 1 paper under review.
    * Designing **post-training** methods for agent tool use and planning: 2 paper under review.
  * Supervisor: Prof. Kai Yu and Prof. Lu Chen

* Jul ~ Sep 2024: Intern AI Engineer
  * Public Development Department, Shanghai Research Institute, Huawei Technologies Co., Ltd.
  * Contributions included:
    * Integrating DB-GPT, a **text-to-SQL** framework with proprietary database and vector database.
  * Supervisor: Yong Wang
  
Skills
======
* Python, C++, JavaScript

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
<!-- Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->

<div class="cv-download-links">
  <a href="{{ base_path }}/files/cv_en.pdf" class="btn btn--primary">Download CV as PDF</a>
</div>