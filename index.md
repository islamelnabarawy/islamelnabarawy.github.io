---
title: Home
---

# Welcome!

## About Me ##

My name is Islam Elnabarawy. I'm a Ph.D. student at the Missouri University of Science and Technology. I work at the Applied Computational Intelligence Laboratory. My main interests are in neural networks, adaptive resonance theory, reinforcement learning, deep learning, and evolutionary computing.

## Posts ##

{% for p in site.posts %}
[{{ p.title }}]({{ p.url }})
{% endfor %}

## Pages ##

{% for p in site.pages %}
  {% if p != page %}
[{{ p.title }}]({{ p.url }})
  {% endif %}
{% endfor %}

## Links ##

[GitHub page](https://github.com/islamelnabarawy)

[Google Scholar profile](https://scholar.google.com/citations?user=9RuneH8AAAAJ&hl=en)

[LinkedIn profile](https://www.linkedin.com/in/islamelnabarawy/)

[YouTube channel](https://www.youtube.com/channel/UC_QIEsgIQwO8FlmSrlvdowA)

[Twitter](https://twitter.com/IslamElnabarawy)
