---
title: 'Experience'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: resume-awards
    content:
      title: Courses
      username: admin
  - block: resume-skills
    content:
      title: Skills & Hobbies
      username: admin
    design:
      show_skill_percentage: false
      columns: 1
  - block: markdown
  id: tech
  design:
    show_skill_percentage: false
    columns: 1
  content:
    title: Programming Languages
    text: |
      - ![Python](https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg) **Python**: Building AI solutions, with 4 years of experience.    
  - block: resume-languages
    content:
      title: Languages
      username: admin
---
