---
layout: about
title: home
permalink: /

profile:
  align: right
  image: self.jpg

news: false  # includes a list of news items
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---

I am currently a second-year CS Ph.D. student at Vanderbilt University, under the guidance of [Prof. Forrest Laine](https://engineering.vanderbilt.edu/bio/forrest-laine). My research primarily revolves around deep learning, optimization, and robotics. Currently I am doing work in deep learning and optimization to develop hybrid models for predicting real-time motion plans. I am interested in combining learning, optimization, and control techniques to create robust and performance-oriented predictive models. Before embarking on my journey at Vanderbilt, I completed my bachelor's degree in Mathematics and Mechanical Engineering at UT Austin. During my time there, I had the privilege of conducting research under the mentorship of [Prof. Yuke Zhu](https://www.cs.utexas.edu/~yukez/), [Prof. Luis Sentis](https://www.ae.utexas.edu/people/faculty/faculty-directory/sentis), and [Prof. Kevin Clarno](https://www.me.utexas.edu/people/faculty-directory/clarno).


## Software

<!-- code for GitHub repositories -->
{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.html repository=repo %}
  {% endfor %}
</div>
{% endif %}