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
    id: programming
    content:
      title: Programming Languages
      skills:
        - name: Python
          icon: devicon-python
          description: Building AI solutions, with 4 years of experience.
        - name: Java
          icon: devicon-java
          description: Building scalable applications, with 3 years of experience.
        - name: JavaScript
          icon: devicon-javascript
          description: Frontend and backend development, with 5 years of experience.

  - blocxk: resume-skills
    id: other
    content:
      title: Other Skills
      skills:
        - name: Team Leadership
          icon: fas fa-users
          description: Leading cross-functional teams, with 2 years of experience.
        - name: Project Management
          icon: fas fa-tasks
          description: Managing projects from initiation to completion, with 3 years of experience.
        - name: Problem Solving
          icon: fas fa-brain
          description: Analyzing complex problems and finding innovative solutions.      
  - block: resume-languages
    content:
      title: Languages
      username: admin
---
