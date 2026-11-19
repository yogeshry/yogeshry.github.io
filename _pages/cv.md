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
* **Ph.D., Computer Science (HCI and Visual Analytics)**, University of Alabama in Huntsville, 2024–present
  * Advisor: Dr. Haeyong Chung
* **Bachelor's degree, Computer Engineering**, Pulchowk Campus, Institute of Engineering, Tribhuvan University, Nepal, 2019

Research experience
======
* **Graduate Research Assistant**, University of Alabama in Huntsville, Aug 2024–present
  * Research funded by NASA IMPACT (Marshall Space Flight Center)
  * SIGMA: designed a declarative grammar for spatial interaction across multiple displays and built its runtime in Unity (C#) on HoloLens 2, streaming events to D3 and Vega-Lite clients
  * Walking Through Time: built the HoloLens 2 authoring application for hybrid tablet–AR timeline authoring
  * Visual analytics for mechanistic interpretability of AI-generated visualization (Vega-Lite and Altair)

Industry experience
======
* **Full Stack Developer**, Fetchly Labs, Texas, USA, May 2023–Jul 2024
  * Full-stack features with Python, Ruby on Rails, Vue, React, AWS, Docker, and GitHub Actions
* **AI Engineer**, Datag, Tokyo, Japan, Nov 2022–May 2023
  * Retrieval-augmented generation pipeline with vector search for CV-to-job matching; Dialogflow CX AI interviewer; LangChain experimentation layer
* **Backend Developer IV**, Centerbase / Legalfit, Texas, USA (remote), Nov 2021–Oct 2022
  * Django APIs and SEO- and ADA-compliant templates for a CMS serving 1,500+ law-firm websites
* **Software Engineer**, Cedar Gate Technologies / Deerwalk Inc., Kathmandu, Nepal, Sep 2019–Nov 2021
  * Centralized SSO (Apereo CAS, SAML, OAuth) for 400K+ users across 12+ applications; Spring Boot APIs; AWS SQS workflows

Skills
======
* **Visualization and XR:** D3, Vega-Lite, React, Unity, HoloLens 2
* **LLMs and ML:** LangGraph, LangChain, RAG pipelines, prompt engineering, TensorFlow
* **Languages:** Python, C#, Java, JavaScript, TypeScript, SQL
* **Backend and cloud:** Django, Spring Boot, AWS, Docker, PostgreSQL, Redis, Elasticsearch

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
