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
        - **Unity and AR Core**: Familiarity, but not extensively experienced. Utilized for AR applications
        
  - block: resume-languages
    content:
      title: Languages
      username: admin
      id: languages

---
