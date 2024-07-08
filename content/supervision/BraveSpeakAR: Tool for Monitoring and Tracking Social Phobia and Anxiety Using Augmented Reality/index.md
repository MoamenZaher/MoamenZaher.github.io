---
title: BraveSpeakAR:Tool for Monitoring and Tracking Social Phobia and Anxiety Using Augmented Reality
summary: BraveSpeakAR is a multi-modal, interdisciplinary project developed in collaboration with psychologist Amro Soliman.
date: 2024-06-10
type: blog
math: false
tags:
  - Bachelor
  - AR
  - Emotion Detection
  - Signal Processing
  - Audio Signal
  - Computer Vision
banner:
  image: 'supervision/BraveSpeakAR: Tool for Monitoring and Tracking Social Phobia and Anxiety Using Augmented Reality/featured.jpg'
image:
  # caption: 'Embed rich media such as videos and LaTeX math'
  image: ''

---

<!-- Project Description -->

## Overview
**BraveSpeakAR** is a multi-modal, interdisciplinary project developed in collaboration with psychologist Amro Soliman ([LinkedIn](https://www.linkedin.com/in/amro-soliman-104274b5/?originalSubdomain=eg)). The primary objective of this project is to assist individuals suffering from social phobia and anxiety related to public speaking by providing a comprehensive and interactive tool that leverages augmented reality (AR) and advanced machine learning techniques.

The core of BraveSpeakAR is a Flutter-based mobile application that enables participants to set up a simulated public speaking environment using AR. During the session, the performance of the participant is monitored and tracked across three key modalities: voice tones and stuttering, emotional responses, and body posture.

## Modalities and Techniques
- **Voice Tones and Stuttering**:
  - Dataset Collection: We developed a custom dataset for voice stuttering.
  - Techniques: The audio signals are converted into spectrograms, which are then analyzed using Convolutional Neural Network (CNN)-based models to detect patterns of stuttering and variations in voice tones.
- **Emotional Responses**:
  - Dataset Collection: We created a dataset for emotion detection based on facial expressions while participants wear AR devices.
  - Techniques: Emotion detection is performed using CNN-based models that analyze facial expressions captured during the AR sessions.

- **Body Posture**:
  - Dataset Collection: We developed a dataset for posture movement.
  - Techniques: Body posture is extracted using MediaPipe, and the movements are classified using a custom algorithm built upon the Dynamic Time Wrapping (DTW) algorithm. This approach was chosen due to the limited size of the dataset, allowing for accurate tracking and analysis of posture changes.

## Key Contributions
- **Interdisciplinary Collaboration**: This project combines expertise from psychology and computer science, ensuring a holistic approach to addressing social phobia and anxiety.

- **Multi-Modal Data Collection**: By collecting custom datasets for voice stuttering, emotion detection, and body posture, we ensure the tool is tailored to the specific needs of individuals with social phobia and anxiety.

- **Advanced Machine Learning Models**: Utilizing CNN-based models and dynamic time wrapping algorithms to analyze different modalities, providing comprehensive feedback on the participant's performance.

- **AR-Based Simulation**: The use of augmented reality to create realistic public speaking environments allows participants to practice and improve their skills in a safe and controlled setting.

- The project resulted into 2 conference publications.


## Publications
- A Scoring Approach for Improving Presentation Impact: Addressing Voice Stuttering, AR Glasses-Based Emotion Recognition, and Profiled Movement Assessment. 2024 6th International Conference on Computing and Informatics (ICCI) [DOI](https://doi.org/10.1109/ICCI61671.2024.10485076)

- Comparative Analysis of Movement Segmentation Techniques in Untrimmed Videos Using Optical Flow and Frame Differencing using the $1 Unistroke Recognizer. (Accepted at IMSA [an IEEE Conference] but not published yet)

BraveSpeakAR represents a significant step forward in the treatment and management of social phobia and public speaking anxiety. By integrating AR and machine learning, this tool offers a novel approach to helping individuals overcome their fears and build confidence in public speaking.

## Awards
The project was awarded the  second-best graduation project at the Faculty of Computer Science, October University for Modern Sciences and Arts (MSA), standing out among over 25 other exceptional projects in the Software Engineering department.

## Student List
- Mazen Waleed [LinkedIn](https://www.linkedin.com/in/mazen-walid-225582208/)
- Mostafa Ameen [LinkedIn](https://www.linkedin.com/in/mostafa-ameen-72511a1bb/)

## Main Supervisor
- Asoc. Prof. Ayman Ezzat [LinkedIn](https://www.linkedin.com/in/ayman4/)
 
 **Did you find this page helpful? Consider sharing it 🙌**
