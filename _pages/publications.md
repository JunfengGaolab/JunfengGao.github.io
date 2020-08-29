---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


Learning from demonstration (LfD) has been used to help robots to implement manipulation tasks autonomously, in particular, to learn manipulation behaviours from observing the motion executed by human demonstrators. This paper reviews recent research and development in the field of LfD. The main focus is placed on how to demonstrate the example behaviours to the robot in assembly operations, and how to extract the manipulation features for robot learning and generating imitative behaviours. Diverse metrics are analysed to evaluate the performance of robot imitation learning. Specifically, the application of LfD in robotic assembly is a focal point in this paper.

[Download paper here](http://zuyuanzhu.github.io/files/Zhu2018-Survey.pdf)




{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
