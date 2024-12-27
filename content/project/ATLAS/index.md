---
title: Solving a differential equation for calibration of the ATLAS detector via a neural networks.
summary: Implement neural network to solve differential equation of 1st or 2nd order. Solving equation on calibration function to improve precision of ATLAS detector.
tags:
  - Particle physics
  - Internships
  - Python
date: '2023-12-02T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image: #pour faire apparaitre cette image, il faut qu'elle s'appelle 'featured.jpg'
  caption: Group project to simulate birds behavior using basic rules, or physics laws.
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: Codes
    url: https://github.com/MatthieuPE/Solving-Differential-Equations-Using-Neural-Network
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

{{< figure src="distribution.jpg" caption="Calibration Example: using neural network solution for ODE-based calibration function" numbered="false" >}}

**Supervisor :** Pierre-Antoine Delsart, lecturer, ATLAS, LPSC, France.

The results of this internship have been presented in a [workshop of the collaboration]({{< relref "/event/altasworkshop" >}}).

The particle physics studied at the LHC by the ATLAS detector requires high-precision measurements.
precision. The energy quantities associated with hadronic jet objects cannot be used directly from experimental measurements, and must be corrected in order to be compared with theoretical predictions.
from experimental measurements, and must be corrected before they can be compared with theoretical predictions. This addresses this problem in the form of a nonlinear second-order differential equation on the calibration function
function, which has no analytical solution. A neural network is used to solve it. The aim is to
is to obtain an accurate calibration function by exploiting the non-linear capabilities of neural networks.

