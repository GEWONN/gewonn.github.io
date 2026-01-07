---
title: TRUST Network Members
excerpt: "Meet members of the TRUST network!"
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
