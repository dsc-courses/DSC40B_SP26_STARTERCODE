---
layout: page
title: Staff
description: A listing of all the course staff members.
---

# Staff 🧑‍🏫
{: .fs-7 .fw-400 }

## Teaching Assistants

{% assign tas = site.staffers | where: 'role', 'Teaching Assistant' %}
<div class="role">
  {% for staffer in tas %}
  {{ staffer }}
  {% endfor %}
</div>

## Tutors

{% assign tutors = site.staffers | where: 'role', 'Tutor' %}
<div class="role">
  {% for staffer in tutors %}
  {{ staffer }}
  {% endfor %}
</div>
