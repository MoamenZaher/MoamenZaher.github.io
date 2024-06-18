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
      - name: Programming Languages
        items:
          - name: Python
            description: building AI solutions, with 4 years of experience.
            percent: 95
            icon: devicon/python

    design:
      show_skill_percentage: false
      columns: 1

  - block: resume-skills
    id: hobbies
    content:
      title: Skills & Hobbies
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

    design:
      show_skill_percentage: false
      columns: 1
      
  - block: resume-languages
    content:
      title: Languages
      username: admin
---
