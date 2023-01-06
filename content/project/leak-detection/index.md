---
title: Leak-detection in water pipeline with Machine Learning 
summary: Leak detection is a rising concern due to its financial impact on water utility companies from the water losses. To this ends, researchers has proposed a multitude of techniques to detect leakages ranging from model-based, transient-based, to data-driven methods. This thesis work aims to develop a machine-learning model to determine whether there are leaks in the pipeline. The empirical data for training is generated from the water laboratory of Oras factory, where it was calibrated to simulate different leaks scenarios. The second aim of this work is to prove that the advantages of machine-learning approach can compensate for its disadvantages. Compared with related studies modeling-based technique, this work also proves that machine-leanring based is more efficient and accurate. Specifically, In this work, an intelligent solenoid valve, with Silab’s EFR32MG22 controller as the processor, was utilized to collect pressure and flow rate measured from the pilot pipeline. Those measurements were transferred via Bluetooth SPP service to a desktop computer for filtering noise and feature-extraction. In model selection, a Support Vector Machine (SVM) model is chosen for the binary classification of leak vs. non-leak data. The model is then optimized by cross-validation with different data transformers on the training set and different hyperparameters of the SVM. The result of this thesis work has shown that using data transformed with Yeo-Johnson power transform yield the highest accuracy (97%) with testing data set.    
tags: ["leak detection", "transient analysis", "Deep Learning", "feature-extraction"]
date: "2022-11-29T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: https://www.researchgate.net/publication/360963340_Leakage_detection_in_water_supply_pipelines_using_machine_learning

image:
  caption: Pilot Pipeline to simulate leaks
  focal_point: Smart

links:
- icon: researchgate
  icon_pack: fab
  name: thesis article
  url: https://www.researchgate.net/publication/360963340_Leakage_detection_in_water_supply_pipelines_using_machine_learning
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---
