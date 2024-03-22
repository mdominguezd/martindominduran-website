---
title: 'Bridging domains: Assessment of Domain Adaptation methods for mapping Cashew crops in Africa'
summary: Here you can check the work that I have been doing for my Geo-Infromation Science MSc thesis.
tags:
  - Deep Learning
date: '2023-08-11'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Figure created to ilustrate the domain gap between cashew crops in Ivory Coast and Tanzania.
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: Go to the repo
    url: https://github.com/mdominguezd/Thesis_model_training
  - icon: file
    icon_pack: fab
    name: Documentation
    url: https://mdominguezd.github.io/CashewDA-docs/
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

**Abstract**

The recent implementation of commodity crop import regulations has highlighted the importance of refining crop mapping techniques from a regional to a global scale. Deep Learning models have shown great performance on this task. However, they struggle when trained on small or poor-quality datasets, and when implemented on a different domain than the one on which they were trained. Domain adaptation techniques emerge to address these issues. In this study, the performance of adversarial domain adaptation techniques was assessed for increasing the generalization capabilities of cashew crop semantic segmentation models trained on a source domain and applied to a target domain. Notably, an Attention U-Net + DANN model was trained using both a land cover benchmark dataset and a dataset created using PlanetScope images containing cashew crops from Ivory Coast (source domain) and Tanzania (target domain). Firstly, the shift between domains was evaluated through a time series analysis, an input and an inner feature distribution analysis. Secondly, the performance of the domain adaptation methods was assessed by comparing an unsupervised and a semi-supervised scenario with a lower-bound (source-only) and an upper-bound model (target-only). Finally, a web-application was built to locate cashew crops in the regions of interest and label data in these data-scarce regions. The proposed network reached a lower-bound F1-score of 0.02, an upper-bound F1-score of 0.62 and a relative improvement of 27% using domain adaptation. While the use of domain adaptation on the cashew dataset yielded a minor improvement, these methods demonstrated success on the semi-supervised scenario (92%) and on the benchmark dataset (45%). The low performances on the cashew dataset were attributed to the initial shift between the crop characteristics across the domains and the inherent difficulty faced by the domain adaptation method in aligning them. In addition, this study suggests that the domain shift observed is influenced by seasonal environmental variations, differences in cultivation practices, and potential sensor characteristic variations. Finally, the low performances of this study highlighted the need for improved data quality and expanded datasets in the domains studied. 

![Initial U-Net+DANN results](GoodDannResults.png)