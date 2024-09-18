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
{{site.data.skills.a00}}
{{page.project-categories}}
{{page.project-categories[0].cat}}
{%- assign page.project-categories[2] = {"cat"="cat3"} -%}
{{page.project-categories}}