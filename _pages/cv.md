---
layout: archive
title: "Curriculum vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

* PhD in Epidemiology and Clinical Research, Stanford University, 2025 (expected)
* MPH in Epidemiology and Biostatistics, University of California, Berkeley, 2021
* BA in Public Health and Data Science, University of California, Berkeley, 2020

## Research Experience

* **Data Science Research Assistant**, UC Berkeley School of Public Health: Colford-Hubbard Research Group (August 2018 - August 2021)
  * *Research Topics*: evaluation of school-located influenza vaccination campaigns; spatio-temporal analysis of enteropathogen transmission; estimation of COVID-19 case counts; risk factors of child growth faltering; evaluation of water, sanitation and hygiene (WASH) interventions
  * *Methods*: fixed-effects and random-effects regression analysis; geospatial risk factor analysis; Bayesian analysis; data visualizations and interactive dashboards; web scraping; database security and management; R package development (function documentation, website maintenance, robustness tests); software development for reproducibility and replicability
  * *Advisor*: Jade Benjamin-Chung, PhD, MPH

* **Undergraduate Research Assistant**, UC Berkeley School of Public Health: Nuru-Jeter Lab (January 2018 - May 2018)
  * *Research Topics*: effects of gentrification on preventable deaths in Alameda County
  * *Methods*: dynamic mapping with Python iWidgets; data dashboards; time-series analysis
  * *Advisor*: Melody Tulier DrPH, MPH, MCP

* **Undergraduate Research Assistant** , UC Berkeley School of Public Health: Madsen Lab (July 2017 - November 2017)
  * *Research Topics*: impact of Bay Area soda taxes on consumer behaviors and attitudes
  * *Methods*: community surveying; data collection; data entry
  * *Advisor*: Nadia Rojas, MPH

## Professional Experience

* **Data Science Intern**, Cricket Health (May 2021 - Present)
  * Refined claims-based models that track chronic kidney disease progression among the undiagnosed population to improve identification of eligible patients
  * Implemented clinically-relevant predictors for use across all predictive analytics projects

* **Data Science Intern**, Institute of Global Health Sciences - University of California, San Francisco (October 2020 - March 2021)
  * Contributed to COVID-19 contact-tracing efforts in San Francisco in collaboration with the San Francisco Department of Public Health
  * Conducted operational data analysis, created visualizations, and generated reports to make business processes more efficient
  * Identified critical gaps and data needs to answer questions used to prioritize activities, track outcomes, and assess performance of a team of contact tracers

* **Honors Fellow**, Fung Fellowship for Wellness and Technology Innovations (August 2018 - May 2020)
  * The Fung Fellowship is a two-year innovation lab focused on the development of health technology solutions under human-centered design frameworks. The fellowship is operated by the Fung Institute of Engineering Leadership in collaboration with the UC Berkeley College of Engineering and UC Berkeley School of Public Health.
  * Projects include:
    * *Deploying novel digital data collection methods for the enrollment of underrepresented populations in epidemiological studies*: designed a data transfer pipeline for individuals to donate personal data towards health studies through blockchain-backed transactions
    * *Developing an augmented-reality sensory treatment to mitigate cognitive decline in early-stage dementia patients*: Built a mid-fidelity prototype of portable augmented-reality playing cards to treat dementia through sensory engagement and nostalgia therapy

* **Performance Improvement Intern**, Sutter Health East Bay Medical Foundation (May 2018 - August 2018)
  * Developed an R Shiny application to display dynamic time-series visualizations of health outcome data relating to care site, care measure, and insurance populations
  * Developed an automated reporting system using continuously generated data that tracks progress made towards annual quality-of-care metrics. Used by the Integrated Quality Services Department to reallocate resources towards underperforming areas

* **Field Relations Liaison**, American Red Cross National Youth Council (July 2016 - June 2018)
  * Spearheaded partnership program between youth council members and regional chapter staff in support of national youth volunteerism
  * Collaborated with youth volunteers and chapter executives to author two case studies that highlight outstanding youth programs across the nation
  * Facilitated communication between National Headquarters and Regional Volunteer Services Officers, consulted national executives on best practices regarding youth volunteer involvement and engagement
  * Promoted youth involvement in public health programs including the Measles and Rubella Initiative, disaster relief fundraising, and disaster preparedness education

## Skills

**Languages**: R, Python, C++, Java, Javascript, SQL, Bash

**Software**: GitHub, Docker, Amazon Workspaces, Microsoft Suite

## [Publications](https://anna-nguyen.github.io/publications/)

### Published

<ul>{% for post in site.publications reversed %}
  {% if post.venue != 'Under Review' %}
    {% include archive-single-cv.html %}
  {% endif %}
{% endfor %}</ul>

### Under Review

<ul>{% for post in site.publications reversed %}
  {% if post.venue == 'Under Review' %}
    {% include archive-single-cv.html %}
  {% endif %}
{% endfor %}</ul>

## [Teaching](https://anna-nguyen.github.io/teaching/)

<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
