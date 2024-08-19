---
layout: page
title: Staff
description: A listing of all the course staff members.
nav_order: 10
---

# Staff
### Add 'berkeley.edu' to the end of all emails.

## Instructor

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
<div class="role">
  {% for staffer in instructors %}
  {{ staffer }}
  {% endfor %}
</div>

## Head Teaching Assistants

{% assign staff = site.staffers | where: 'role', 'Head TA' %}
<div class="role">
  {% for staffer in staff %}
  {{ staffer }}
  {% endfor %}
</div>

## Teaching Assistants

{% assign staff = site.staffers | where: 'role', 'TA' %}
<div class="role">
  {% for staffer in staff %}
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


