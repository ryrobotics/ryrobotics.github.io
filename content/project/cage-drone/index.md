---
title: Design of a Fully-autonomous Collision-resilient UAV
summary: This project presents the design of a collision-resilient UAV with 3D LiDAR and an onboard computer for autonomous drone tasks, such as search-and-rescue, exploration, and inspection.

tags:
  - UAV
date: '2023-04-30T00:00:00Z'

# Optional external URL for project (replaces project detail page).
# external_link: 'https://www.youtube.com/watch?v=I2o1NfcY26Q'

# youtube_id: "I2o1NfcY26Q"

# image:
#   caption: Photo by rawpixel on Unsplash
#   focal_point: Smart

links:
  # - icon: twitter
  #   icon_pack: fab
  #   name: Follow
  #   url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

# 1. Drone’s components

### 4K HD camera:
This camera offers impressive capabilities including 20MP photo capture, 4K@30FPS video recording, and Electronic Image Stabilization.

### Brushless DC Motor & Propeller:
Motors are responsible for spinning the propellers and generating thrust (up to a maximum of 6.4kg) to lift the drone off the ground.

### Onboard Computer
Onboard computer provides powerful computing capabilities for autonomous inspection algorithms and data collection.

### Carbon Fiber Composite Cage
The lightweight but reliable cage holds all the components together and protects the internal components from damage.

### 3D LiDAR
This compact yet powerful 3D LiDAR provides precise 360-degree data collection and perception, offering centimeter-level accuracy.

### Flight Controller
The flight controller is like the brain of the drone. It contains sensors (such as gyroscopes and accelerometers) and processes data to stabilize and control the drone's movements.

### Electronic Speed Controllers (ESCs)
ESCs control the speed and direction of each motor. They receive commands from the flight controller and adjust the power sent to the motors accordingly.

### Battery
The battery supplies power to the drone. It is a rechargeable lithium polymer (LiPo) battery with a capacity of 6000 mAh.



# 2. Advantages of our drone
### Speed
The drone is designed for quick deployment and ease of use. In our swimming pool trial, we completed the ceiling inspection, including pre-flight preparations and actual flights (about 20 mins), in just 2 hours.

### Safety
To ensure safety, the drone is equipped with a customized cage that fully covers its body, providing ample protection for both the drone and the surrounding facilities. Additionally, autonomous flight capabilities and intelligent collision avoidance algorithms contribute to safe and controlled operations.

### Accuracy
With its powerful 3D LiDAR (centimeter-level accuracy) and advanced localization algorithm, the drone can provide high-accuracy point cloud data collection. This precision allows operators to precisely identify and locate defects in the following inspections.

### Flexibility
The drone's design is tailored for inspections, making it adaptable to various application scenarios. For instance, an up-looking camera is included specifically for ceiling inspections, enhancing its performance in our swimming pool trial.

