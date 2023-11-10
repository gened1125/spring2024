---
layout: home
title: Home
nav_exclude: false
nav_order: 1
seo:
  type: Course
  name: Artificial and Natural Intelligence
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

**Instructor: Professor Venkatesh Murthy**  ([vnmurthy@fas.harvard.edu](mailto:vnmurthy@fas.harvard.edu)) \
**Head TF: Kumaresh Krishnan**  ([kumaresh_krishnan@g.harvard.edu](mailto:kumaresh_krishnan@g.harvard.edu)) \
**Lecture: M/W 3-4:15PM | Location: Science Center Hall C**\
**Section times: Tentative times shown in schedule tab (Submit sectioning preferences on my.harvard after enrolling!)**

Quick Links
* [PDF version](https://canvas.harvard.edu/files/17006204/download?download_frd=1) of the course schedule and syllabus.
* [Course Preview Zoom Recording](https://harvard.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=ea20130f-9f05-40ee-835b-ae1d0145500a), where Prof. Murthy gives an overview of the course (Recorded for Spring 2022).
[//]: # * [Final paper guidelines](https://canvas.harvard.edu/files/17099112/download?download_frd=1)
[//]: # * [Grading rubric](https://canvas.harvard.edu/files/17303255/download?download_frd=1)

{% for module in site.modules %}
{{ module }}
{% endfor %}
