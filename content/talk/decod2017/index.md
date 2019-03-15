+++
title = "Anthropomorphic image reconstruction via sub-Riemannian geometry and hypoelliptic diffusion"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date = 2017-11-24T09:30:00+01:00
# date_end = 2019-03-15T16:07:26+01:00
all_day = false

# Schedule page publish date (NOT talk date).
publishDate = 2019-03-15T16:07:26+01:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Dario Prandi"]

# Location of event.
location = "CentraleSupélec, Gif-sur-Yvette"

# Name of event and optional event URL.
event = "1st DECOD Workshop"
event_url = "https://decod2017.sciencesconf.org/"

# Abstract. What's your talk about?
abstract = "In  this  talk  I  will  present  an  algorithm  of  image  reconstruction  based  on  a  model  of geometry of vision started with the works of Hubel and Wiesel at the end of the 50s, up to the works by Petitot, Citti and Sarti and our research group. One of the main features of this model is  that  the  primary  visual  cortex  V1  lifts  an  image  from  the  plane  to  the  bundle  of  directions  of the plane. Neurons are grouped into orientation columns, each of them corresponding to a point of this bundle. In this model a corrupted level set of an image is reconstructed by minimizing the energy necessary for the activation of the orientation columns corresponding to regions in which the  image  is  corrupted  gives  rise  to  a  sub-Riemannian  problem.  To  this  sub-Riemannian problem is naturally associated an hypoelliptic heat equation on the bundle of directions of the plane  that  can  be  used  to  reconstruct  a  \"natural\"  image.  One  of  the  main  difficulties  is  the numerical  integration  of  such  a  diffusion  equation  that  being  highly  non-isotropic  contains  two different  diffusion  scales.  We  solve  this  problem  by  using  techniques  of  non-commutative Fourier analysis on a suitable semi-discretization the group of rototranslations of the plane. The use of the knowledge of \"where\" the image is corrupted permits to reconstruct images with 97% of corruption obtaining result at the state of the art in image processing."

# Summary. An optional shortened abstract.
summary = ""

# Is this a featured talk? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Markdown Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Optional filename of your slides within your talk folder or a URL.
url_slides = ""

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Links (optional).
url_pdf = ""
url_video = ""
url_code = ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
