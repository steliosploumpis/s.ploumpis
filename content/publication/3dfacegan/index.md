---
title: "3DFaceGAN: Adversarial Nets for 3D Face Representation, Generation, and Translation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- S Moschoglou
- S Ploumpis 
- M Nicolaou
- A Papaioannou
- S Zafeiriou

# Author notes (optional)
#author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2020-05-06"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-05-06"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *International Journal of Computer Vision*
publication_short: In *IJCV*

summary: In *International Journal of Computer Vision (**IJCV**), May 6, 2020*

abstract: Over the past few years, Generative Adversarial Networks (GANs) have garnered increased interest among researchers in Computer Vision, with applications including, but not limited to, image generation, translation, imputation, and super-resolution. Nevertheless, no GAN-based method has been proposed in the literature that can successfully represent, generate or translate 3D facial shapes (meshes). This can be primarily attributed to two facts, namely that (a) publicly available 3D face databases are scarce as well as limited in terms of sample size and variability (e.g., few subjects, little diversity in race and gender), and (b) mesh convolutions for deep networks present several challenges that are not entirely tackled in the literature, leading to operator approximations and model instability, often failing to preserve high-frequency components of the distribution. As a result, linear methods such as Principal Component Analysis (PCA) have been mainly utilized towards 3D shape analysis, despite being unable to capture non-linearities and high frequency details of the 3D face - such as eyelid and lip variations. In this work, we present 3DFaceGAN, the first GAN tailored towards modeling the distribution of 3D facial surfaces, while retaining the high frequency details of 3D face shapes. We conduct an extensive series of both qualitative and quantitative experiments, where  the merits of 3DFaceGAN are clearly demonstrated against other, state-of-the-art methods in tasks such as 3D shape representation, generation, and translation.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
url_pdf: "https://link.springer.com/article/10.1007/s11263-020-01329-8"
#url_slides: ""

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
