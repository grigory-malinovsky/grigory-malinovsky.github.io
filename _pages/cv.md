---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
{% assign cv_link = site.data.navigation.main | where: 'title', 'CV' | first %}

Download my [curriculum vitae (PDF)]({{ base_path }}{{ cv_link.url }}).

You can also browse my [publications]({{ base_path }}/publications/), [presentations]({{ base_path }}/presentations/), and [teaching]({{ base_path }}/teaching/).
