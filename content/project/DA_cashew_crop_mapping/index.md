---
title: 'Domain Adaptation methods for mapping cashew crops in Africa'
summary: Here you can check the work that I have been doing for my Geo-Infromation Science MSc thesis.
tags:
  - Deep Learning
date: '2023-08-11'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Density of labels of cashew crops in source and target domains
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: Go to the repo
    url: https://github.com/mdominguezd/DomainAdaptationCashewCropMapping_MGIThesis
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
<!-- slides: example -->
---

In a nutshell, DA makes it possible to apply one model that has been trained in one source domain (dataset) to a target domain (dataset) that has a different data distribution than the source domain and that may have less or may not have any labels for training. The study area of my thesis will be Ivory Coast, which will be considered the source domain, and Tanzania, that will be the target domain.

In my MSc thesis, I will be implementing domain adaptation techniques to semantic segmentation models for cashew crop mapping in Africa to assess their potential for increasing the generalization capabilities of the models. More sepecifically, I will work with an adapted U-Net following the main ideas of the Domain Adversarial Neural Network (DANN) proposed by Ganin et al. (2015). 

**Initial results**

Some initial results are shown on the figure below. Numerically the implementation of the DANN network is improving the accuracy, however when the actual segmentation is evaluated, it is evident that the models need to improve. 

If you have any suggestions on how to improve the models, feel free to hit me up with an e-mail :).

![Initial U-Net+DANN results](GoodDannResults.png)