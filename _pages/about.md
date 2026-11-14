---
permalink: /
title: "Grigory Malinovsky"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


Bio
======
I am a postdoctoral researcher at EPFL, working with Prof. Volkan Cevher in [LIONS](https://www.epfl.ch/labs/lions/) on optimization for machine learning. I received my PhD in Applied Mathematics and Computational Sciences from King Abdullah University of Science and Technology (KAUST) in June 2026, advised by Prof. [Peter Richtárik](https://richtarik.org).

I develop optimization methods for efficient and reliable machine learning. My work connects stochastic and adaptive methods with communication-efficient federated learning, privacy guarantees, and robustness to unreliable participants.

During my PhD, I worked as a Research Intern Engineer at Samsung R&D Institute UK from April to October 2024, focusing on optimization theory for large language models.

My hobbies include fitness, basketball, drums, and piano.


Recent news
======
{% include base_path %}
<ul class="recent-news">
{% for post in site.posts limit:3 %}
  <li><strong>{% include news-date.html entry=post %}</strong> &mdash; {{ post.summary | default: post.title | markdownify | remove: '<p>' | remove: '</p>' }}</li>
{% endfor %}
</ul>

[All news]({{ base_path }}/year-archive/)


Education
======
PhD in Applied Mathematics and Computational Sciences  
[Computer, Electrical and Mathematical Sciences and Engineering Division](https://cemse.kaust.edu.sa)  
[King Abdullah University of Science and Technology](https://www.kaust.edu.sa/en)  
Jan. 2022 -- Jun. 2026  
Thuwal, Saudi Arabia  
Thesis: "Theoretical Foundations of Communication-Efficient, Robust, and Practical Distributed and Federated Optimization"  
Advisor: [Peter Richtárik](https://richtarik.org)

MS in Applied Mathematics and Computational Sciences  
[Computer, Electrical and Mathematical Sciences and Engineering Division](https://cemse.kaust.edu.sa)  
[King Abdullah University of Science and Technology](https://www.kaust.edu.sa/en)  
Aug. 2020 -- Dec. 2021  
Thuwal, Saudi Arabia  
GPA: 3.83/4.0  
Advisor: [Peter Richtárik](https://richtarik.org)

BS in Applied Mathematics and Physics  
[Department of Control and Applied Mathematics](https://mipt.ru/english/edu/departments/dcam)  
[Moscow Institute of Physics and Technology](https://mipt.ru/english/)  
Sept. 2014 -- Jul. 2019  
Dolgoprudny, Russia  
GPA: 4.73/5.0  
Thesis: "Averaged Heavy Ball Method"  
Advisor: [Boris Polyak](https://scholar.google.pk/citations?user=Zhlib28AAAAJ&hl=en)
