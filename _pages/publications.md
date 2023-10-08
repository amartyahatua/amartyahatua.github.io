---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Patents
1. IMAGE DISPLAY: [KR20180035045A](https://worldwide.espacenet.com/patent/search/family/061977449/publication/KR20180035045A?q=pn%3DKR20180035045A)

2. DISPLAY DEVICE AND CONTROLLING METHOD THEREOF: [KR20170012998A](https://worldwide.espacenet.com/patent/search/family/058108912/publication/KR20170012998A?q=pn%3DKR20170012998A)

3. APPARATUS FOR CONTROLLING IMAGE DISPLAY AND METHOD THEREOF: [KR20160008893A](https://worldwide.espacenet.com/patent/search/family/055306847/publication/KR20160008893A?q=pn%3DKR20160008893A)


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
