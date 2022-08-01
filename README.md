# AI Driven Pose Detection

---

## 1.1. Table of contents
- [AI Driven Pose Detection](#ai-driven-pose-detection)
  - [1.1. Table of contents](#11-table-of-contents)
  - [1.2. About this repository](#12-about-this-repository)
  - [1.3. The Approach](#13-the-approach)
  - [1.4. Checklist](#14-checklist)

---

## 1.2. About this repository
This project aims at building an AI driven pose detection model to count bicep curls. At least to start with...

This [README.md](/README.md) file will feature a checklist to keep track of this projects status and an explanation to the approach taken to learn about the tools employed.

## 1.3. The Approach
In order to learn as much as possible from this project, I intend to tackle as few libraries at a time. Starting by building an AI based Pose Estimation program using the MediaPipe and OpenCV libraries that uses a webcam feed to render results of different poses on the screen. 

After building this program, I will then advance to building the DeepFit project using my enhanced understanding of the component libraries. 

The program will be written in Python using the Jupyter Notebook environment and will be comprehensive in its documentation for future reference. 

The logs for this project will be maintained in the [logs.md](logs.md) file. 

## 1.4. Checklist      
- [X] Create [`README.md`](/README.md) file
  - [X] Explain purpose
  - [X] Explain approach
- [X] Start a [`logs.md`](logs.md) file for both the DeepFit clone and the pose estimation projects
  - [X] Log creating the markdown file
- [X] Create notebook for AI driven pose detection
  - [X] Setup MediaPipe library
  - [X] Estimate poses
  - [X] Extract joint coordinates
  - [X] Calculating angles between joints
  - [X] Building a counter for bicep curls