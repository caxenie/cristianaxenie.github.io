---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


Applied Antifragility in Natural Systems
![image](https://github.com/user-attachments/assets/59463b58-583e-4cf7-add5-2f62c0bb7a70)

As coined in the book of Nassim Taleb, antifragility is a property of a system to gain from uncertainty, randomness, and volatility, opposite to what fragility would incur. An antifragile system’s response to external perturbations is beyond robust, such that small stressors can strengthen the future response of the system by adding a strong anticipation component. Such principles are already well suited for describing behaviors in natural systems but also in approaching therapy designs and eco-system modelling and eco-system analysis.

The book introduces the framework of applied antifragility and possible paths to build systems that gain from uncertainty. We draw from the body of literature on natural systems (e.g. cancer therapy, antibiotics, neuroscience, and agricultural pest management) in an attempt to unify the scales of antifragility in one framework. The work of the Applied Antifragility Group in oncology, neuroscience, and ecology led by the authors provides a good overview on the current research status.

Official link: [Springer](https://link.springer.com/book/9783031903908)

Pre-orders: [Amazon](https://www.amazon.de/-/en/Cristian-Axenie/dp/3031903900)




Applied Antifragility in Technical Systems
![image](https://github.com/user-attachments/assets/a3ae4ac8-5d3b-4a18-8c2d-62b447ee24fa)

The book purpose is to build a foundational knowledge base by applying antifragile system design, analysis, and development in technical systems, with a focus on traffic engineering, robotics, and control engineering. The authors are interested in formalizing principles and an apparatus that turns the basic concept of antifragility into a tool for designing and building closed-loop technical systems that behave beyond robust in the face of uncertainty.

As coined in the book of Nassim Taleb, antifragility is a property of a system to gain from uncertainty, randomness, and volatility, opposite to what fragility would incur. An antifragile system’s response to external perturbations is beyond robust, such that small stressors can strengthen the future response of the system by adding a strong anticipation component. The work of the Applied Antifragility Group in traffic control and robotics, led by the authors, provides a good overview on the current research status.

Official link: [Springer](https://link.springer.com/book/9783031904240)

Pre-orders: [Amazon](https://www.amazon.de/-/en/Cristian-Axenie/dp/3031904249)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
