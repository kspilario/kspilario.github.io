---
permalink: /
title: "Process Systems Engineering Laboratory"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello! I am **Karl Ezra Pilario**, a faculty member in the Department of Chemical Engineering at the University of the Philippines Diliman, where I lead the Process Systems Engineering Laboratory (**PSEL@UPD**). 

Our laboratory specializes in *computational research* in engineering, with a particular focus on developing algorithms for *process design and modelling, optimization, control, and monitoring* (see upper left, lower left, upper right, lower right quadrants of our logo, respectively). Through our research, we aim to develop innovative solutions across various applications even beyond process industries, while contributing to the achievement of the U.N. Sustainable Development Goals.

<p align="center">
    <img src="images/psel_logo_2023.png" width="200">
</p>

Our Mission
======
**PSEL@UPD** is committed to advancing algorithmic, data-driven, and sustainable engineering solutions for process industries and related fields, including energy, water, and the environment. Our research leverages novel computational methods by integrating **machine learning**, **data analytics**, and **artificial intelligence** with fundamental **chemical engineering principles** to enhance process systems engineering activities.

Our Vision
======
In the long term, **PSEL@UPD** aspires to be a leading research group that nurtures students to become the *best researchers in computer-aided chemical engineering in the Philippines*, while being a trusted partner of industries and research institutions locally and globally.

Featured Research
======
Some of our most notable research and collaboration activities are as follows:

<div class="featured-research">
  {% for item in site.data.featured-research %}
    <div class="research-item">
      <div class="research-img-container">
        <img src="{{ item.image }}" alt="{{ item.title }}" class="research-img">
      </div>
      <div class="research-description">
        <h3>{{ item.title }}</h3>
        <p>{{ item.description | markdownify }}</p>
      </div>
    </div>
  {% endfor %}
</div>

