---
layout: archive
title: "my cv:"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **MD**, Drexel University College of Medicine, 2026\
  Philadelphia, PA
* **BS** in Neuroscience, University of Washington, 2020\
  Seattle, WA

Post-Graduate Residency Training
======
* Capital Health Medical Center, Hopewell, NJ\
  Transitional Year Residency, 2026-2027 
* University of Washington, Seattle, WA\
  Diagnostic Radiology Residency, 2027-2031 (expected)

Work experience
======
* Spring 2024: Academic Pages Collaborator
  * GitHub University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * GitHub University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * GitHub University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  
Skills
======
<div class="skills-grid">

  <div class="skill-chip">
    <i class="fa-brands fa-python"></i>
    <span>Python</span>
  </div>

  <div class="skill-chip">
    <i class="fa-brands fa-r-project"></i>
    <span>R</span>
  </div>

  <div class="skill-chip">
    <i class="fa-solid fa-cube"></i>
    <span>3D Slicer</span>
  </div>

  <div class="skill-chip">
    <i class="fa-solid fa-x-ray"></i>
    <span>Imaging</span>
  </div>

  <div class="skill-chip">
    <i class="fa-solid fa-chart-line"></i>
    <span>Data Science & Statistics</span>
  </div>

  <div class="skill-chip">
    <i class="fa-solid fa-file-lines"></i>
    <span>Scientific Writing</span>
  </div>

  <div class="skill-chip">
    <i class="fa-solid fa-database"></i>
    <span>REDCap</span>
  </div>

  <div class="skill-chip">
    <span class="skill-mask-icon skill-nigiri-icon" aria-hidden="true"></span>
    <span>Sushi</span>
  </div>

</div>
<!-- * Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3 -->

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Abstracts & Presentations
======
  <ul>{% for post in site.presentations reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* [RadDiscord](https://www.raddiscord.org/)  
  Moderator, 2023-Ongoing

* Radiological Society of North America\
  Medical Student Task Force, Research Subcommittee, 2024-2025

* [Vietnam Health Clinic](https://www.vnhealthclinic.org/)  
  Student Member, 2017
