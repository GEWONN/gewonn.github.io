---
title: Journal Club
excerpt: "The GeWoNN Journal Club"
subnav-image: "/images/journal-club.jpg"
---

<div class="two-columns" style="--left-width: 30%; --right-width: 70%; --align-items: center;">
  <div>
    Welcome to the GeWoNN Journal Club! We meet once a month to discuss articles related to word and reading research. For more info, check out our past meetings. If you would like to join our Journal Club or present in our meetings, please fill out <a href="https://forms.gle/TY6Cuxut87EjJE8u9">this form</a> or contact us at <a href="mailto:gewonn.contact.us@gmail.com">gewonn.contact.us@gmail.com</a>.
  </div>
  <div>
    {% include figure.html image="https://gewonn.github.io/images/journal-club-screenshot.png" width="100%" %}
  </div>
</div>

<hr>

### Next Meeting: January 21, 2026 (Wednesday), 9:00 am–10:00 pm (CET)

Guest Talk by *Dr Kurt Winsler (University of California, Davis)*

Experience-dependent Changes in the Visual Processing of Letters: Evidence from Electroencephalography Decoding

Link to the paper: [http://doi.org/10.1162/JOCN.a.99](http://doi.org/10.1162/JOCN.a.99)

##### Abstract

<div style="font-size: 1rem; line-height: 1.2rem; padding-top: 1rem; margin-bottom: 0.25rem;">
Learning to read involves the formation and tuning of letter representations, but it is unknown whether this orthographic tuning influences very early visual processing or only later processing. I will talk about a study which tested the hypothesis that experience increases the extraction of sensory information about letters by comparing the EEG activity elicited by upright and inverted letters. In a set of conventional univariate analyses, we found that inverted letters elicited larger P1 amplitudes (starting ca. 110 msec) and larger N170 amplitudes (starting ca.160 msec) compared with upright letters. These larger amplitudes could reflect enhanced processing, but they might instead reflect degraded processing. We therefore performed multivariate pattern classification (decoding) to assess the amount of information about letter identity in the neural signal. Specifically, we decoded which individual letter was presented from the pattern of voltage across the scalp at each time point. We found that decoding accuracy was greater for upright letters than for inverted letters during the P1 latency range (starting ca. 90 msec), particularly in electrodes over the left hemisphere and for letters presented foveally and in the right visual field. This provides evidence for enhanced tuning for upright letters in early visual processing. By contrast, we found higher decoding accuracy for inverted letters than for upright letters during and after the N170 component (starting ca.140 msec). These results demonstrate that massive experience with upright letters influences sensory processing, leading to enhanced feature extraction for highly familiar (upright) letter forms at an early stage, followed by enhanced neural discriminability for less familiar (inverted) letter forms at a later stage.
</div>
<br>

<h4>Journal Club Organisers</h4>

<ul style="padding-left: 1.2rem">
  <li>Anna Leung (Ludwig-Maximilians-University of Munich, Germany)</li>
  <li>Jack E. Taylor (Goethe University Frankfurt, Germany)</li>
</ul>

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
