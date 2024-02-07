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
**Lecture: M/W 3-4:15PM | Location: NW B103**\
**Section times: M: 4:30, 6:00; W: 4:30; R: 10:30, 1:30, 3:00; F: 1:30**\
[**Announcements**](https://canvas.harvard.edu/courses/129605/announcements) (Links to Canvas)\
**Office Hours** Prof. Murthy Tue 3:00-4:30pm, Biolabs 4027 (16 Divinity Ave)
Thurs 9:00-10:00am [Zoom](https://harvard.zoom.us/my/venki.murthy)

Quick Links
* [PDF version](https://canvas.harvard.edu/files/19232513/download?download_frd=1) of the course schedule and syllabus.
* [Course Preview Zoom Recording](https://harvard.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=ea20130f-9f05-40ee-835b-ae1d0145500a), where Prof. Murthy gives an overview of the course (Recorded for Spring 2022).
* [Final paper guidelines](https://canvas.harvard.edu/files/18788275/download?download_frd=1)
* [Grading rubric](https://canvas.harvard.edu/files/18788276/download?download_frd=1)

{% for module in site.modules %}
{{ module }}
{% endfor %}
