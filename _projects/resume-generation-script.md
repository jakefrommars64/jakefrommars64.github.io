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
skills:
    - skill: a00

---
{{page.skills[0].skill}}

{{site.data.skills}}

{{page.project-categories}}

{{page.project-categories[0].cat}}

{% assign cat = 'cat3' %}

{% assign page.project-categories[2] = cat %}


{{page.project-categories}}
