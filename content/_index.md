---
title: "Diana's Academic Portfolio"
summary: "Diana Nikolaeva's personal academic portfolio featuring bio, publications, news, experience, and projects tutorials."
date: 2026-06-24
type: landing
sections:
  - block: hero
    content:
        title: "Diana — Researcher & Technologist"
        subtitle: "Exploring data, code, and open science with clarity and precision."
        image:
          src: assets/media/hero.jpg
          alt: Portrait of Diana
  - block: markdown
    content:
        id: bio
        title: About Me
        body: "Diana is a researcher passionate about reproducible science, scientific communication, and open-access publishing. This portfolio showcases sample projects illustrating key features including visual editing, LaTeX math, and data-driven workflows."
  - block: collection
    content:
        id: papers
        title: Selected Papers
        collection: publication
        limit: 5
        show_more_link: true
  - block: markdown
    content:
        id: news
        title: Latest News
        body:
          |
            - **2026-05-01:** Presented on data science reproducibility at OpenScience Summit.
            - **2026-04-10:** Published new article on applied machine learning in environmental studies.
            - **2026-03-15:** Awarded competitive fellowship for interdisciplinary research.
  - block: markdown
    content:
        id: experience
        title: Experience
        body:
          |
            - Postdoctoral Fellow, Institute of Data Science, 2024–Present
            - PhD Candidate, University of Tomorrow, 2018–2023
            - Research Intern, Open Source Lab, Summer 2019
  - block: collection
    content:
        id: projects
        title: Tutorial Projects
        collection: project
        limit: 5
---