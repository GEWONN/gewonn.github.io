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
  <li>Anna Leung (Ludwig-Maximilians-University of Munich, Germany)</li>
  <li>Jack E. Taylor (Goethe University Frankfurt, Germany)</li>
</ul>

<hr>

### Next Meeting:
### March 6, 2026 (Friday), 11:00 am–12:00 pm (CET)

Guest Talk by *Katharina von Kriegstein (TU Dresden)*

The role of sensory thalami and cortico-thalamic connections in developmental dyslexia

##### Abstract

<div style="font-size: 1rem; line-height: 1.2rem; padding-top: 1rem; margin-bottom: 1.5rem;">
Developmental dyslexia is a specific reading disorder with a high prevalence. It often has a substantial impact on the psychosocial well-being and academic achievement of affected individuals. Contemporary research characterizes developmental dyslexia as a multifactorial condition with phonological processing difficulties playing a central role. Neuroscientific research focuses often on explaining developmental dyslexia at the level of the cerebral cortex. However, this cortical focus leaves potential contributions from subcortical structures largely unexplained, particularly those of the sensory thalamus. In this talk, I will first summarize our work on the role of the auditory and visual sensory thalami, namely the medial geniculate body (MGB) and the lateral geniculate nucleus (LGN) in phonological and visual speech processing. I will then show that developmental dyslexia is characterised by alterations in these structures and that these alterations are related to key symptoms of developmental dyslexia.
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
