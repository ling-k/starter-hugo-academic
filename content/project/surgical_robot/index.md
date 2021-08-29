---
title: Image-Guided Surgical Robot 
summary: Surgical Robot for Bone Surgery 
tags:
- Robotics
date: "2021-08-18T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: "" 

links:
- name: Report
  url: https://ling-k.github.io/uploads/Report-Image-Guided-Surgical-Robot.pdf
url_code: ""
url_pdf: "https://ling-k.github.io/uploads/Report-Image-Guided-Surgical-Robot.pdf"
url_slides: "https://ling-k.github.io/uploads/surgical_robot_project_slides.pdf"
url_video: "https://www.youtube.com/watch?v=vR4T4orNpzU" 


    
    
# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
---

The conventional human-performed surgery of bone tumor resection has the drawbacks of imprecise, high labor intense on surgeons, longer recovery time. In this project, a surgical robot system for bone tumor resection is developed. First, the preoperative image of experimental bone is obtained by CT scanning. Then the surgeon is able to plan a surgery path by means of choosing key points on the 3D bone model. Second, the relationship between image space and surgical space is established. Finally the surgery path made by the surgeon in image space is mapped to surgical space and robot can receive the commands to operate the surgery. Meanwhile, the position of the surgical tool is displayed in image space in real time. Acetabular bone and thigh bone trials were performed at hospital and the outcome shows the feasibility of using robot to resect bone tumor.

As shown in the figure below, the brief scheme of this project is to use the CT data of the bone to guide the robot to do the bone resection surgery.
We first get the CT data of the bone and reconstruct it to a 3D model. Then, we load the 3D reconstructed image of the bone into 3D slicer,  an open source software for research in image guided therapy, in which the surgeon could make a surgical path by choosing key points. Second we build the relationship between image space and surgical space. This is realized by ICP algorithm with two separated steps.
Finally, we map the surgery path planned by the surgeon from image space to surgical space and command the robot to operate the surgery. Meanwhile, the position of the surgery tool is displayed in image space.  

![Car Image](Project-Scheme.png)
     
More details: [<span style="color:blue"> Report </span>](https://ling-k.github.io/uploads/Report-Image-Guided-Surgical-Robot.pdf), [<span style="color:blue"> Slides </span>](https://ling-k.github.io/uploads/surgical_robot_project_slides.pdf),  [<span style="color:blue"> Video </span>](https://www.youtube.com/watch?v=vR4T4orNpzU).

