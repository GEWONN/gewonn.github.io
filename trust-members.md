---
title: The TRUST Network
excerpt: "The TRUST network aims to build a transparent, transferable, and sustainable foundation for psycholinguistic reading studies in German. The Network will bring together more than 20 researchers in the field to develop transferable and sustainable guidelines for researchers to address critical challenges, including methodological robustness, reproducibility, generalisability, and statistical power."
subnav-image: "/images/members/missing.jpg"
---

#### Meet the TRUST Network!
<p></p>

<div class="trust-members-list">
{% for member in site.data.trust-members %}
<p><b>{{ member.name }}</b></p>
<p>Institution: {{ member.affiliation }}</p>
<p>Research Area: {{ member.research }}</p>
<hr>
{% endfor %}
</div>
