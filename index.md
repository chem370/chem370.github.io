---
layout: default
title: Course Information
nav_order: 1
description: "WCU CHEM 370"
permalink: /
has_children: true
---




<div class="card">
  {% for post in site.posts limit:1 %}
    <article class="post">

    <h1>This Week</h1>

      <div class="entry">
        {{ post.content }}
      </div>

      <a href="{{ site.url }}/weekly-summaries" class="read-more">[View Previous Weeks]</a>
    </article>
  {% endfor %}
</div>

-----

# Course Information

*CHEM 370 - Instrumental Analysis I (Laboratory)* is an introduction to instrumental analysis in the chemistry lab.  We will learn how to use and operate chemical instrumentation and learn how to reproducibly process the data they generate.

## Logistics

- Course materials will be posted on this site.
- Homework will be submitted through Microsoft Teams.  
  [ [Video: How to use Microsoft Teams](https://wcu.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=8cbd076b-a5e2-46e7-9fee-acb8012e09fc) ]
  
- General questions should be asked through Piazza.  
  [ [Video: How to use Piazza](https://wcu.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=0abad82d-58e0-49c9-aa39-acb8012e0a2e) ]
  
- Office hours will be held remotely in MS Teams.  Schedule a meeting via [Bookings](https://outlook.office365.com/owa/calendar/DrFischer@catamountwcu.onmicrosoft.com/bookings/).  
  [ [Video: How to schedule office hours](https://wcu.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=aee14c85-2213-49f4-bfb3-acb8012e0a68) ]

## Assignments

I put a lot of trust in you to complete your work, do it well, and ask questions when you don't understand something.  Many assignments will be "graded" automatically -- you will get feedback on screen as you complete them.  You may not get a formal grade for these, but neglecting them will certainly have a detrimental effect on your grade later in the semester!  Below are lists of the items that will be assessed for a grade.  

(*Assignment lists may change as needed or if class is moved to an online modality.*)

### Individual

- Lab 0 Tutorials (Exercises 0A & 0B)
- 5 lab notebooks (1 for each intro labs and 3 for the project lab)
- 4 instrument quizzes
- 1 peer review assignment
- Lab safety & participation
- Group participation

### Group Assignments

- 1 lab report (plus additional draft assignments)

There are no exams.  Lab notebooks consist of data processing completed in a Markdown notebook and a data processing language (e.g. Pluto and Julia, respectively).

*Please see the syllabus for a complete explanation of grading schemes.*
