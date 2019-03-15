+++
title = "A variational formulation of the sub-Riemannian model of the primary visual cortex"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date = 2016-05-11
# date_end = 2019-03-15T16:17:08+01:00
all_day = false

# Schedule page publish date (NOT talk date).
publishDate = 2019-03-15T16:17:08+01:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Dario Prandi"]

# Location of event.
location = "Voss, Norway"

# Name of event and optional event URL.
event = "Geometric Analysis in Control and Vision Theory"
event_url = "https://www.uib.no/node/91768"

# Abstract. What's your talk about?
abstract = "In this talk we present a new mathematical model for the human primary visual cortex V1 and its applications to image processing, based on the well-known sub-Riemannian Citti-Petitot-Sarti model. In this model the primary visual cortex is represented as the bundle $PT\\mathbb R^2$ of directions of the plane, where each point corresponds to a neuron with both spatial location and local orientation preferences. This structure is then endowed with a sub-Riemannian metric, mimicking the long and short range connections between neurons.<br>The main novelty of ou approach is the definition of the lift of 2D images to this space, and more generally of image restoration tasks (e.g. denoising or inpainting), through a dissipation of the energy by the cortical structure. More precisely, we define a variational procedure that lifts a visual stimulus (i.e. an image) to the cortical state that both minimizes its sub-Riemannian $H^1$ norm (minimum effort of the cortex hypothesis) and at the same time re-projects back to the same image (consistency hypothesis). In sharp contrast with previous definitions of lifts (e.g. via Gabor wavelets), this method does not make use of an a-priori fixed lift procedure. This allows us to integrate into this procedure the sub-Riemannian structure of the cortex, which in turn, makes the lift sensitive to the curvature of objects composing the image, without resorting to any  post-processing diffusion over the cortical surface. <br>We will focus, in particular, on the characterization of this lift as a wavelet-type transform lift where the wavelet is a highly anisotropic distribution on $\\mathbb R^2$, which allows for a rigorous derivation of the so-called extra-classical receptive fields.<br>This is joint work with G. Peyré, J.-M. Mirebeau and A. Sarti."

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
