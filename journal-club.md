---
title: Journal Club
excerpt: "The GeWoNN Journal Club"
subnav-image: "/images/journal-club.jpg"
---

<div class="two-columns" style="--left-width: 50%; --right-width: 50%; --align-items: center;">
  <div>
    Welcome to the GeWoNN Journal Club! We meet once a month to discuss articles related to word and reading research. For more info, check out our past meetings. If you would like to join our Journal Club or present in our meetings, please <a href="https://bsky.app/profile/gewonnofficial.bsky.social">send us a private message via Bluesky</a>.
  </div>
  <div>
    {% include figure.html image="https://gewonn.github.io/images/journal-club-screenshot.png" width="100%" %}
  </div>
</div>
<br>

<h5>Journal Club Organisers</h5>

<ul style="padding-left: 1.2rem">
  <li>Jack E. Taylor (Goethe University Frankfurt, Germany)</li>
</ul>

<hr>

### Next Meeting:
### May 22, 2026 (Friday), 10:00 am–11:00 am (CET)

Paper Discussion moderated by *Dr Jack E. Taylor (Goethe University Frankfurt)*

> Morsanyi et al. (2025). Toward an Improved Understanding of Dyslexia: Reflections on a New Consensus Definition and Its Implications. https://doi.org/10.1002/dys.70022

##### Abstract / Info

<div style="font-size: 1rem; line-height: 1.2rem; padding-top: 1rem; margin-bottom: 1.5rem;">
The paper is available here: <a href="https://doi.org/10.1002/dys.70022">https://doi.org/10.1002/dys.70022</a>
</div>

<hr>

<h4>Past Meetings</h4>
<br>

<div class="journal-club-meeting-list">
{% for meeting in site.data.journal-club-meetings %}
<p><b>{{ meeting.date }}</b></p>
<p>{{ meeting.description }}</p>
<hr>
{% endfor %}
</div>
