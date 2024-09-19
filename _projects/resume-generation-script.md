---
layout: project
name: Resume Generation Script
include: true
cms-id: ""
start-date: 29 July 2024
end-date: 6 August 2024
description: Write a script that generates tailored resumes using JSON data and Markdown to ease the process of creating resume's tailored for each application.
project-page: ""
project-categories:
    - cat: "cat1"
    - cat: "cat2"

---

{% assign page['a00'] = site.data.skills['a00'] %}

{% assign page.skills['a01'] = site.data.skills['a00'] %}

{% assign skills['a01'] = site.data.skills['a00'] %}

{% assign skillarray = [site.data.skills['a00'],site.data.skills['a01']] %}

{% assign skillsingle = site.data.skills['a00'] %}


<p>`page['a00']` is {{page['a00'].skill}}</p>

<p>`page.a00.skill` is {{page.a00.skill}}</p>

<p>`page.skills['a01']` is {{page.skills.a01}}</p>

<p>`skills[a01]` is {{skills.a01}}</p>

<p>`skillarray` is {{skillarray}}</p>

<p>`skillsingle` is {{skillsingle}}</p>