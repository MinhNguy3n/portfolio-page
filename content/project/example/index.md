---
title: Myoelectric and IMU for Robotic application and Smart System
summary: Read sEMG and IMUs data from Myo armband from gateway device for filtering and categorizing different hand gesturesM; Utilized MQTT protocol to bridge connection with microcontroller to remotely control robotic arm; Implemented gesture-based appliance control with HassIO. 
tags:
- IoT, Smart System, Assistive Technology, Signal Processing
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

Electromyography (EMG) has been widely used for detecting a person's hand poses and remote control applications. However, the traditional EMG-based control systems have limitations such as short controlling range, and supporting the limited number of devices. There is a need for a more advanced system that can deal with the limitations while maintaining a high quality of services such as high accuracy level and controlling complex devices. Hence, we present a real-time and remote control Internet-of-Things system using EMG signals together with motion-related signals such as acceleration and angular velocity. A user wearing the Myo-band at his/her arm can remotely control devices via 8 different hand gestures. The entire system was implemented and tested via two use cases of home assistant and robot arm control. The results show that the presented system could achieve a high level of accuracy e.g., 100% accuracy for simple control and 90% accuracy for complex cases. This system can be a potential approach for smart home controlling and assisting disabled people.  
