---
layout: page
title: Links
tagline: My friends.
permalink: /links.html
---


{% for f in site.data.friends %}
<div class="link-chip">
 <img alt="{{f.describe}}" src="{{f.image}}" class="link-chip-icon">
 <a title="{{f.describe}}" target="_blank" class="link-chip-title" href="{{f.url}}">{{f.name}}</a>
</div>
{% endfor %}

[Linkedin](https://www.linkedin.com/in/feiyuzhang/) 

[Github](https://github.com/neo99zhang)

[Sony Alpha](https://alphauniverse.com/member/#/feiyu-zhang)

[Return to Home]({{ site.baseurl }})

<hr/>

  {% if site.data.social.valine_comment.enable  == true %}
  <script src="/comment/av-min.js"></script>
  <script src="/comment/Valine.min.js"></script>
  <div id="comments"></div>
  {% include comments.html %}
  {% endif %}
  {% include scripts.html %}

<!-- --- saved for reference. used to be billboard.md
layout: page
title: Billboard
tagline: Biu~
---

<div style="text-align:center">:shit:nothing...</div>

[Return to Home]({{ site.url }}) -->