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

{%- assign page.a00 = site.data.skills['a00'] -%}

just the variable is {{a00.skill}}

as a page variable is {{page.a00.skill}}