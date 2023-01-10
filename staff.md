---
layout: page
title: Course Staff
nav_order: 4
description: A listing of all the course staff members.
---

# Course Staff

## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign headtf = site.staffers | where: 'role', 'Head Teaching Fellow' %}
{% assign num_headtf = headtf | size %}
{% if num_headtf != 0 %}
## Head Teaching Fellow

{% for staffer in headtf %}
{{ staffer }}
{% endfor %}
{% endif %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Fellow' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
## Teaching Fellows

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}
