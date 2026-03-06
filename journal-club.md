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
### March 24, 2026 (Tuesday), 11:00 am–12:00 pm (CET)

Guest Talk by *Daria Kostanian (Sirius University of Science and Technology)*

Development of coarse- and orientation-tuning for native letters in children

##### Abstract

<div style="font-size: 1rem; line-height: 1.2rem; padding-top: 1rem; margin-bottom: 1.5rem;">
We investigated neurophysiological letter coding in typically developing children (3.6—9.3 years) using an oddball fast periodic visual stimulation. By measuring neural discrimination responses to non-native (Georgian) letters embedded in streams of native (Russian) letters, it was found that even pre-readers show automatic discrimination of native from foreign scripts. In contrast, sensitivity to the standard orientation of native letters, as measured by the detection of inverted letters among upright Russian letters, emerged only after the onset of reading instruction and increased with age. These findings reveal two distinct trajectories in visual letter tuning: an early-emerging, coarse tuning driven by environmental exposure, and a more fine orientation tuning that depends on active reading acquisition.
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
