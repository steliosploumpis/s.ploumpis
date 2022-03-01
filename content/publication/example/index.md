---
title: "Combining 3d morphable models: A large scale face-and-head model"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- S Ploumpis
- H Wang
- N Pears
- WAP Smith
- S Zafeiriou

# Author notes (optional)
#author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2019-06-20"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "019-06-20"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Conference on Computer Vision and Pattern Recognition*
publication_short: In *CVPR*

summary: Proceedings of the IEEE *Conference on Computer Vision and Pattern Recognition (**CVPR**), June 20, 2019*

abstract: Three-dimensional Morphable Models (3DMMs) are powerful statistical tools for representing the 3D surfaces of an object class. In this context, we identify an interesting question that has previously not received research attention, is it possible to combine two or more 3DMMs that (a) are built using different templates that perhaps only partly overlap,(b) have different representation capabilities and (c) are built from different datasets that may not be publicly-available? In answering this question, we make two contributions. First, we propose two methods for solving this problem, i. use a regressor to complete missing parts of one model using the other, ii. use the Gaussian Process framework to blend covariance matrices from multiple models. Second, as an example application of our approach, we build a new head and face model that combines the variability and facial detail of the LSFM with the full head modelling of the LYHM. The resulting combined model achieves state-of-the-art performance and outperforms existing head models by a large margin. Finally, as an application experiment, we reconstruct full head representations from single, unconstrained images by utilizing our proposed large-scale model in conjunction with the Face-Warehouse blendshapes for handling expressions.


tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openaccess.thecvf.com/content_CVPR_2019/papers/Ploumpis_Combining_3D_Morphable_Models_A_Large_Scale_Face-And-Head_Model_CVPR_2019_paper.pdf'
url_code: 'https://github.com/steliosploumpis/Universal_Head_3DMM'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?feature=player_embedded&v=fNlMGWm7bbk&t=4700s'

# # Featured image
# # To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

# # Associated Projects (optional).
# #   Associate this publication with one or more of your projects.
# #   Simply enter your project's folder or file name without extension.
# #   E.g. `internal-project` references `content/project/internal-project/index.md`.
# #   Otherwise, set `projects: []`.
# projects:
# - example

# # Slides (optional).
# #   Associate this publication with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides: "example"` references `content/slides/example/index.md`.
# #   Otherwise, set `slides: ""`.
# slides: example
---
