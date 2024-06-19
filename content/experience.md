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
  - block: collection
    content:
      title: Awards & Certificates
      # subtitle: ''
      # text: 'Check out my recent blog posts below!'
      # Choose how many pages you would like to display (0 = all pages)
      count: 3
      # Filter on criteria
      filters:
        exclude_featured: false
        exclude_future: false
        exclude_past: false

        # The folders to display content from
        folders:
          - awards
      # Choose how many pages you would like to offset by
      # Useful if you wish to show the first item in the Featured widget
      offset: 0
      # Field to sort by, such as Date or Title
      # sort_by: 'Date'
      # sort_ascending: false
      order: desc
    design:
      # Choose a listing view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]

  - block: markdown
    content:
      text: |
        ## List of Trainings
        - **International Research and Publication**: Training provided by the Learning and Development Section at October for Modern Sciences and Arts (MSA) university. (2024)

        - **Research Ethics**: Training provided by the Learning and Development Section at October for Modern Sciences and Arts (MSA) university. (2024)

        - **Graduation Project Supervision**: Training provided by the Learning and Development Section at October for Modern Sciences and Arts (MSA) university.(2024)

        - **Information Security**: Training provided by the Learning and Development Section at October for Modern Sciences and Arts (MSA) university. (2024) 
        - **Planning and Time Management**: Training provided by the Learning and Development Section at October for Modern Sciences and Arts (MSA) university. (2024)
            
        - **Writing Reports**: Training provided by the Learning and Development Section at October for Modern Sciences and Arts (MSA) university. (2024)
        
        - **Mind Mapping**: Training provided by the Learning and Development Section at October for Modern Sciences and Arts (MSA) university. (2024)
        
        - **Buisness, Marketing and  Entrepreneurship**: Training provided by the Technology Innovation and Entrepreneurship Center (TIEC). (2018)
        
  - block: resume-skills
    content:
      title: Skills
      username: admin
    design:
      show_skill_percentage: false
      columns: 1
  - block: markdown
    content:
      text: |
        ## Python Frameworks and Libraries      
        - **Numpy and Pandas**: Utilized for processing data
        - **Seaborn and Matplotlib**: Utilized for data analysis and visualization
        - **OpenCV**: Utilized for tasks related to images/videos
        - **TensorFlow**: Used for model creation in deep learning projects
        - **TensorBoard**: Employed for visualizing the training process and model evaluation
        - **Mediapipe**: Used for human pose estimation tasks.
        - **YOLO**: Used for marker-less object detection and pose estimation tasks
        - **TUIO and ArUco**: Implemented for marker object detection
        - **Mediapipe**: Utilized for hand/pose estimation tasks
        - **Dlib and DeepFace**: Applied for various facial related tasks such as facial expression, facial recognition, gaze tracking, and landmark detection
        - **Unity and AR Core**: Familiarity, but not extensively experienced. Utilized for AR applications.
  - block: markdown
    content:
      text: |
        ## Volunteering
        - **Reviewer**: Volunteered as a reviewer in <a href="http://www.iwacce.org/" target="_blank">The Third International Workshop on Automation, Control and Communication Engineering (IWACCE2024)</a> conference held in Hihhot, China.
        - **Vice Head of The Operations Team**: Volunteered as vice head of <a href="http://imsa.msa.edu.eg/" target="_blank">First and Second conferences of Intelligent Methods, Systems, and Application</a> conference held in Cairo, Egypt.
        - **Event Organizer**: Volunteered as an organizer in the faculty scientific day (<a href="https://deepminds.msa.edu.eg/" target="_blank">Deep Minds</a>) held at October University for Modern Sciences and Arts (MSA) in Cairo, Egypt.
     
  - block: resume-languages
    content:
      title: Languages
      username: admin
      id: languages

---
