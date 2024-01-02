---
layout: home
title: Home
nav_exclude: true
seo:
  type: Course
  name: Algorithms, SHNU
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

<!-- {% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %} -->

## About the Class

Turing Award awardee [Knuth](https://en.wikipedia.org/wiki/Donald_Knuth) once said, "Computer Science is the study of algorithms". Even though the speed of computers is now so fast that we might even question whether Moore's Law still holds true, the significance of an efficient algorithm remains essential for us. 

Therefore, in this course, we aim to present various algorithms for numerous 'standard' algorithmic problems. We will illustrate both algorithm design techniques and the methods employed in algorithm analysis. By the end of the course, students will attain proficiency in applying fundamental algorithm design techniques and will become acquainted with the key theoretical instruments utilized in algorithm analysis. Moreover, since this course is designed for senior undergraduates, we will provide an introduction to notable subfields within algorithmic research, thereby offering potential directions for further study.

Enjoy the class!

See the [Syllabus page](syllabus.md) for more details on course policies.

## General Information

**Instructor:** [Qizhe Yang](https://basics.sjtu.edu.cn/~yangqizhe/), qzyang(at)shnu.edu.cn

**Time and Location:** &ensp;&nbsp;9:45 a.m.- 11:15 a.m. &nbsp;Every Monday in Week 1-16, <font color="#dd0000"> 奉贤3教楼308</font> 
 <br/>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;13:00 p.m.- 14:30 p.m. Every Friday in Week 1-8，&emsp; 奉贤3教楼312

 For more details about the class, see the [Schedule page](schedule.md).

## Final Exam

The final exam is scheduled for **January 3, 2024, from 10:45 a.m. to 12:15 a.m.** , and will be held in <font color="#dd0000"> 奉贤3教楼222</font> . Please note that it will be a **closed-book** exam.


## Course Feedback

We have set up a course questionnaire:

- [《算法设计与分析》课程调查问卷](https://www.wjx.cn/vm/eDmAYfp.aspx#)

Everyone is welcome to submit his/her questions or suggestions about this course.

**Updated in Dec 24, 2023**

Since we will finish the course in the next week, we have set up a new questionnaire for collecting the feedback of this course:

- [《算法设计与分析》完课调查问卷](https://www.wjx.cn/vm/YfWr24n.aspx# )

The questionnaire is not mandatory, but I will appreciate it if you can spend a few minutes to fill it out. Thank you!

# Announcements

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}