---
title: CVPR '19 Oral Presentation

event: CVPR 2019
event_url: https://cvpr2019.thecvf.com/

location: Long Beach
address:
  #street: 450 Serra Mall
  city: Los Angeles
  region: CA
  #postcode: '94305'
  country: United States

summary: Combining 3D Morphable Models, A Largescale Face-and-Head Model
abstract: "Three-dimensional Morphable Models (3DMMs) are powerful statistical tools for representing the 3D surfaces
of an object class. In this context, we identify an interesting question that has previously not received research attention:
is it possible to combine two or more 3DMMs that (a) are built using different templates that perhaps only partly overlap, (b) have different representation capabilities and (c) are built from different datasets that may not be publicly available? In answering this question, we make two contributions. First, we propose two methods for solving this problem: i.~use a regressor to complete missing parts of one model using the other, ii.~use the Gaussian Process framework to blend covariance matrices from multiple models. Second, as an example application of our approach, we build a new face-and-head shape model that combines the variability and facial detail of the LSFM with the full head modelling of the LYHM. The resulting combined shape model achieves state-of-the-art performance and outperforms existing head models by a large margin. Finally, as an application experiment, we reconstruct full head representations from single, unconstrained images by utilizing our proposed large-scale model in conjunction with the FaceWarehouse blendshapes for handling expressions."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2019-06-20'
#date_end: '2030-06-01T15:00:00Z'
all_day: True

# Schedule page publish date (NOT talk date).
#publishDate: '2017-01-01T00:00:00Z'

authors: [S Ploumpis, H Wang, N Pears, WAP Smith, S Zafeiriou]
tags: []

# Is this a featured talk? (true/false)
featured: false

# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#   focal_point: Right

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/S_Ploumpis
url_code: "https://github.com/steliosploumpis/Universal_Head_3DMM"
url_pdf: "https://openaccess.thecvf.com/content_CVPR_2019/papers/Ploumpis_Combining_3D_Morphable_Models_A_Large_Scale_Face-And-Head_Model_CVPR_2019_paper.pdf"
#url_slides: ""
url_video: "https://www.youtube.com/watch?v=fNlMGWm7bbk&t=4700s"

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects:
# - example
---

<!-- {{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Wowchemy's [*Slides*](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://wowchemy.com/docs/writing-markdown-latex/).

Further event details, including [page elements](https://wowchemy.com/docs/writing-markdown-latex/) such as image galleries, can be added to the body of this page. -->
