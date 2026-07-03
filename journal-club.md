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
### July 13, 2026 (Monday), 2:00 pm–3:00 pm (CET)

Guest Talk by Aleksandra Boiko (*RWTH Aachen University*)

> Examining The Effect Of Occipito-temporal Sulcus Morphology On Reading Performance In A Large Developmental Sample With And Without Developmental Dyslexia

##### Abstract / Info

<div style="font-size: 1rem; line-height: 1.2rem; padding-top: 1rem; margin-bottom: 1.5rem;">
A growing body of results suggests that the morphology of macroanatomical features, such as sulci, is linked to cognitive abilities. In the domain of reading, prior research has suggested a positive relationship between interruptions (gaps) in the occipito-temporal sulcus (OTS) and reading proficiency. Yet, studies examining this relationship have yielded mixed findings. While some studies report longitudinally accumulating effects of OTS gaps on reading performance (Bouhali et al., 2025), others find no effect in large homogeneous samples (Roell et al., 2022), or suggest the structural advantage is restricted to highly literate individuals (Cachia et al., 2018).

We aimed to clarify these discrepancies by examining the effect of OTS morphology on reading performance using a large, diverse developmental sample (n = 202, ages 6–21) from the publicly available Healthy Brain Network dataset, including individuals with developmental dyslexia.

We defined posterior and anterior OTS gaps in each hemisphere blind to participant diagnosis and linked OTS gap presence to performance on a standardized reading test.

Our findings show that the presence of an interrupted left anterior OTS was associated with significantly higher reading performance scores. However, this effect was only present in typical readers and when beginning readers were excluded. Conversely, in children with developmental dyslexia no significant performance difference between individuals with continuous and interrupted OTS morphology was found. These results may help reconcile inconsistencies in prior literature as they suggest that the functional advantage of anterior OTS interruptions may only manifest after reaching a specific level of reading proficiency.
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
