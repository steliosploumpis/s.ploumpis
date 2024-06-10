---
title: "FitMe: Deep Photorealistic 3D Morphable Model Avatars"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- A Lattas
- S Moschoglou
- S Ploumpis 
- B Gecer
- J Deng
- S Zafeiriou

# Author notes (optional)
#author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2023-05-10"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-05-10"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Conference on Computer Vision and Pattern Recognition*
publication_short: In *CVPR*

summary: Proceedings of the IEEE *Conference on Computer Vision and Pattern Recognition (**CVPR**), 2023*

abstract: In this paper, we introduce FitMe, a facial reflectance model and a differentiable rendering optimization pipeline, that can be used to acquire high-fidelity renderable human avatars from single or multiple images. The model consists of a multi-modal style-based generator, that captures facial appearance in terms of diffuse and specular reflectance, and a PCA-based shape model. We employ a fast differentiable rendering process that can be used in an optimization pipeline, while also achieving photorealistic facial shading. Our optimization process accurately captures both the facial reflectance and shape in high-detail, by exploiting the expressivity of the style-based latent representation and of our shape model. FitMe achieves state-of-the-art reflectance acquisition and identity preservation on single ``in-the-wild'' facial images, while it produces impressive scan-like results, when given multiple unconstrained facial images pertaining to the same identity. In contrast with recent implicit avatar reconstructions, FitMe requires only one minute and produces relightable mesh and texture-based avatars, that can be used by end-user applications.

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
url_code: "https://alexlattas.com/fitme"
url_pdf: "https://openaccess.thecvf.com/content/CVPR2023/papers/Lattas_FitMe_Deep_Photorealistic_3D_Morphable_Model_Avatars_CVPR_2023_paper.pdf"
#url_dataset: "https://alexlattas.com/fitme"
#url_slides: ""
#url_video: "https://www.youtube.com/watch?v=fNlMGWm7bbk&t=4700s"

# url_pdf: 'https://openaccess.thecvf.com/content_CVPR_2019/papers/Ploumpis_Combining_3D_Morphable_Models_A_Large_Scale_Face-And-Head_Model_CVPR_2019_paper.pdf'
# url_code: 'https://github.com/steliosploumpis/Universal_Head_3DMM'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: 'https://www.youtube.com/watch?feature=player_embedded&v=fNlMGWm7bbk&t=4700s'

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
