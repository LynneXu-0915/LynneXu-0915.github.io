---
layout: archive
title: "CV"
permalink: /cv-json/
author_profile: false
redirect_from:
  - /resume-json
---
<small><em>Last updated: {{ site.time | date: "%B %d, %Y" }}</em></small>

{% include base_path %}

{% include cv-template.html %}

<div class="cv-download-links">
  <a href="{{ base_path }}/files/cv.pdf" class="btn btn--primary">Download Full CV as PDF</a>
  <a href="{{ base_path }}" class="btn btn--inverse">View Markdown CV</a>
</div>
