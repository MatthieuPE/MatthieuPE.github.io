---
title: Simulating bird flocking behavior - from simple rules to physical models
summary: Simulation of bird swarms using boids's rules and modeled a physical system to approach collective bird behavior.
tags:
  - Study projects
  - Python
date: '2023-06-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image: #pour faire apparaitre cette image, il faut qu'elle s'appelle 'featured.jpg'
  caption: Group project to simulate birds behavior using basic rules, or physics laws.
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: Codes
    url: https://github.com/MatthieuPE/Bird-flight-with-Boids-rules-or-physical-laws
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---
{{< figure src="boids.jpg"   caption="Example of a bird simulation using the rules of birds or the laws of physics. We can note the creation of groups for some parameters." numbered="false" resize_options="1x2">}}



**Supervisor :** Mourad Ismaïl, Associate Professor in Applied Mathematics, LIPHY, Université Grenoble Alpes, France.

In this project, we aimed to simulate bird swarms in a 2D infinite sky by using three simple rules proposed by Craig W. Reynolds in 1987. These rules, which are widely known as Boids, have been used in the cinema industry to simulate crowds. However, we wanted to model a system following physical laws to approach a collective bird behavior.

We found that to effectively simulate physical rules with many parameters, it is necessary to use at least a fourth-order approximation method, such as the Runge-Kutta method. We can obtain a conservative system, where groups of birds/particles are formed.

Our simulations can be useful for studying systems where clusters appear from any distribution of constituents. However, we acknowledged that the model could still be improved by adding obstacles, fluid effects, a third dimension of space, or restricting the birds' field of vision to 180°.

Overall, the understanding of collective behaviors is a scientific challenge that can be addressed by multiple disciplines such as biology, physics, and social sciences. By modeling the behavior of bird swarms, we can gain insights into how systems transition from a uniform state to swarm formations, which has practical applications in various fields.

