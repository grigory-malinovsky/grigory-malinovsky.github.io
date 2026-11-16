---
permalink: /
title: "Grigory Malinovsky"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


{% include base_path %}

Bio
======
I am a postdoctoral researcher at EPFL, working with Prof. [Volkan Cevher](https://scholar.google.com/citations?user=hlWhzU8AAAAJ&hl=en) in [LIONS](https://www.epfl.ch/labs/lions/) on optimization for machine learning. I received my PhD in Applied Mathematics and Computational Sciences from King Abdullah University of Science and Technology (KAUST) in June 2026, advised by Prof. [Peter Richtárik](https://richtarik.org).

My research focuses on optimization theory and algorithm design for machine learning. I work on [communication-efficient federated learning]({{ base_path }}/research/communication-efficient-learning/), [privacy and robustness]({{ base_path }}/research/privacy-and-robustness/), and [optimization for deep learning]({{ base_path }}/research/optimization-for-deep-learning/).

During my PhD, I worked as a Research Intern Engineer at Samsung R&D Institute UK from April to October 2024, focusing on optimization theory for large language models.

My hobbies include fitness, basketball, drums, and piano.


Recent news
======
<ul class="recent-news">
{% for post in site.posts limit:3 %}
  <li><strong>{% include news-date.html entry=post %}</strong> &mdash; {{ post.summary | default: post.title | markdownify | remove: '<p>' | remove: '</p>' }}</li>
{% endfor %}
</ul>

[All news]({{ base_path }}/year-archive/)


Education
======
**PhD in Applied Mathematics and Computational Sciences**<br>
[KAUST](https://www.kaust.edu.sa/en) · Jan. 2022 – Jun. 2026<br>
Advisor: [Peter Richtárik](https://richtarik.org)

**MS in Applied Mathematics and Computational Sciences**<br>
[KAUST](https://www.kaust.edu.sa/en) · Aug. 2020 – Dec. 2021<br>
Advisor: [Peter Richtárik](https://richtarik.org)

**BS in Applied Mathematics and Physics**<br>
[MIPT](https://mipt.ru/english/) · Sept. 2014 – Jul. 2019<br>
Advisor: [Boris Polyak](https://scholar.google.pk/citations?user=Zhlib28AAAAJ&hl=en)

{% assign cv_link = site.data.navigation.main | where: 'title', 'CV' | first %}
Further details are available in my [CV]({{ base_path }}{{ cv_link.url }}).


Academic Service
======
- **Reviewing:** ICML, NeurIPS, ICLR, AISTATS, Transactions on Machine Learning Research, and IEEE Transactions on Automatic Control.
- **Program committees:** IEEE FLTA 2024 and federated learning workshops at ICML 2023 and NeurIPS 2022.
- **Seminar organization:** OPT ML group seminar, 2022.
