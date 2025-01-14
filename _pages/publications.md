---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

Conference Papers
---

**(*= equal contribution)**

* **[USENIX ATC'24]** "An Empirical Study of Rust-for-Linux: The Success, Dissatisfaction and Compromise", **Hongyu Li\***, **Liwei Guo\***, Yexuan Yang, Shangguang Wang, and Mengwei Xu. ***Best Paper Award!!***
* **[ASPLOS'23]** "Efficient NLP Inference at the Edge via Elastic Pipelining", **Liwei Guo**, Wonkyo Choe, and Felix Xiaozhu Lin.
* **[EUROSYS'22]** "Minimum Viable Device Drivers for ARM TrustZone", **Liwei Guo**, and Felix Xiaozhu Lin.
* **[USENIX ATC'19]** "Transkernel: Bridging Monolithic Kernels to Peripheral Cores", **Liwei Guo**, and Felix Xiaozhu Lin.
* **[EUROSYS'18]** "Power SandBox: Power Awareness Redefined", **Liwei Guo\***, **Tiantu Xu\***, Mengwei Xu, Xuanzhe Liu, and Felix Xiaozhu Lin.
* **[HotMobile'16]** "Decelerating Suspend and Resume in OS," Shuang Zhai, **Liwei Guo**, Xiangyu Li, and Felix Xiaozhu Lin.


Journal Papers
---

Still waiting for my first journal paper :)



<!-- New style rendering if publication categories are defined 
{% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        <h2>{{ category[1].title }}</h2><hr />
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}
-->
